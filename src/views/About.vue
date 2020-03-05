<template>
  <div class="about padding">
    <div class="row section-work mx-auto mt-3 ">
      <div class="section-work__title mx-0 pl-0 pr-3">
        <span class="pr-3">02.</span>Where i've worked
      </div>
      <div class="col-12 section-work__job d-flex justify-content-between col-sm-2 flex-sm-column px-0 m-0 pt-3">
        <div v-for="(name, i) in stuff" @click="current = i" :class="{current:i == current}" :key="name.id" ><div class="col section-work__name" @click="animate">{{name}}</div></div>
      </div>
      <transition name="bounce">
        <div class="col-sm-5 pt-4" :class="{'bounceInRight animated': animated}" @animationend="animated = false">
          <h5 class="third-text-color">{{macarie[current]}} <span>@ {{stuff[current]}}</span></h5>
          <h6 class="secondary-text-color">{{perioada[current]}}</h6>
          <p class="d-flex"><i class="fas fa-caret-right mr-3 pl-2 "></i>{{arrow[current]}}</p>
        </div>
      </transition>
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
    .section-work__job:before {
      border-left: 3px solid #2c3e50;
    }

    .current{
      border-left: 3px solid $main-text-color;
      border-radius: 3px;
    }

  }
  @media only screen and (max-width: 575px) {
    .section-work__name {
      font-size: 12px;
    }
    .current{
      border-bottom: 2px solid $main-text-color;
      border-radius: 3px;
    }
  }






.about {
  background: $main-bg-color;
  color: $secondary-text-color;
  .section-work__title {
    position: absolute;
    top: -17px;
    left: 0;
    background: $main-bg-color;
    z-index: 5;
    font-size: 22px;
    color:$third-text-color;
  }
  .section-work{
    border-top: 1px solid $main-text-color;
    position: relative;
    border-radius: 2px;
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
        arrow:['Junior Web Developer, sed do eiusmod ',
          'giat nulla pariatur. Excepteur sint occa ',
          't labore et dolore magna aliqua',
          'bla bla bla bla gdgdgdsfsfsfssf'],

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
