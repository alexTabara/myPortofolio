<template>
  <div class="about">
    <div class="col-sm-10 px-0  mx-auto col-md-10 col-lg-7 col-xl-6 my-auto" id="experience">
      <div class="row section-work mx-2">
        <div class="section-work__title  second-text-size pr-4  ">
          <span class="pr-3 ">02.</span>Where i've worked
        </div>
        <div class="col-12 section-work__job d-flex justify-content-between col-sm-3 flex-sm-column ">
          <div v-for="(name, i) in stuff" @click="current = i" :class="{current:i == current}" :key="name.id" ><div class="col-sm section-work__name" @click="animate">{{name}}</div></div>
        </div>
        <transition name="bounce">
          <div class="col-sm-9 mt-3 mt-sm-5" :class="{'bounceInRight animated': animated}" @animationend="animated = false">
            <h5 class="third-text-color">{{macarie[current]}} <span>@ {{stuff[current]}}</span></h5>
            <h6 class="secondary-text-color">{{perioada[current]}}</h6>
            <p class="d-flex"><i class="fas fa-caret-right mr-3 pl-2 my-auto"></i>{{arrow[current]}}</p>
          </div>
        </transition>
      </div>
    </div>
    <MyProject></MyProject>
  </div>
</template>


<style scoped lang="scss">
  $main-text-color: #64C7CC;
  $main-bg-color: rgb(10, 25, 47);
  $secondary-text-color: rgb(136, 146, 176);
  $third-text-color: #f7f7f7;
  @media only screen and (min-width: 576px) {

    .about {
      padding-top: 20px;
      #experience{
        height: 50vh;
        padding-top: 20vh;
      }
      .section-work{
        .section-work__job:before {
          border-left: 3px solid #2c3e50;
        }
        .section-work__job{
          margin-top: 40px;
          padding: 0;
          .section-work__name {
            font-size: 15px;
            font-weight: bold;
          }
          .current{
            border-left: 3px solid $main-text-color;
            border-radius: 3px;
          }
        }
        h5{font-size: 15px}
        h6{font-size: 15px}
        p {font-size: 20px}
      }
    }

  }
  @media only screen and (max-width: 575px) {
  .section-work{
    .section-work__job{
      margin-top: 40px;
      .section-work__name {
        font-size: 15px;
        font-weight: bold;
      }
      .current{
        border-bottom: 2px solid $main-text-color;
        border-radius: 3px;
      }

    }
    h5{font-size: 15px}
    h6{font-size: 13px}
    p {font-size: 11px}
  }
  }
  @media only screen and (max-width: 375px) {
    .section-work__name {
      font-size: 9px!important;}
  }

.about {
  background: $main-bg-color;
  color: $secondary-text-color;
  .section-work{
    border-top: 1px solid $main-text-color;
    position: relative;
    border-radius: 2px;
    .section-work__title {
      position: absolute;
      top: -17px;
      left: 0px;
      background: $main-bg-color;
      z-index: 5;
      color:$third-text-color;
    }
    .section-work__job:before {
      content: "";
      position: absolute;
      left: 0px;
      top: 0;
      width: 100%;
      height: 100%;
    }
    .section-work__job {
      div {
        .section-work__name {
          height: 40px;
          display: flex;
          align-items: center;
        }
        .section-work__name:hover {
          color: $main-text-color;
          background: #2c3e50;
        }
      }
    }
    .current{
      background: $main-bg-color;
      color: $main-text-color;
      font-weight: bold;
      z-index: 15;
      border-radius: 3px;
    }
    .fas {color: $main-text-color;}
  }
}

</style>



<script>
  import MyProject from'../views/MyProjects'
  export default {
    name: "About",
    components: {
      MyProject
    },
    data() {
      return {
        hasError: 'text-red',
        isActive: true,
        animated: true,
        current:0,
        stuff:['Soft Dreams','Salul Negru','Jysk','Cora'],
        macarie:['Junior Web Developer','Manager Pensiune-Restaurant','Manager Logistica','Manager Comercial'],
        perioada:['January 2020 - Present','Iun 2019 - Sep 2019','Mai 2018 - Iun 2019','Dec 2006 - Aug 2017'],
        arrow:['Develop and maintain web applications using HTML, CSS,Sass & Bootstrap 4.',
          'Targeting new markets to increase interest in the restaurant.',
          'Conduct assessment of supply chain to identify risks and develop solutions useful in minimizing losses.',
          'Manage and maintain the standard, custom, promotional, and large buy pricing within the pricing databases.'],

      }
    },
    methods:{
      animate() {
        this.animated = true
      },
      compClasses: function () {
        return{
          available: this.available,
          nearby: this.nearby
        }
      }
    }
  };
</script>
