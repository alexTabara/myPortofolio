<template>
  <div class="home padding">
    <nav class="navbar navbar-expand-lg navbar-light">
      <a class="navbar-brand" href="#"><div class="hexagon"><span>T</span></div></a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <div class="hamburger-menu d-flex justify-content-center flex-column">
          <div></div>
          <div></div>
          <div></div>
        </div>
      </button>

      <div class="collapse navbar-collapse justify-content-end" id="navbarSupportedContent">
        <ul class="navbar-nav ">
          <li class="nav-item">
            <a class="nav-link" href="#/"><span>01.</span> About <span class="sr-only">(current)</span></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#/"><span>02.</span> Experience</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#/"><span>03.</span> Work</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#/"><span>04.</span> Contact</a>
          </li>
        </ul>
        <form class="form my-2 my-lg-0">
          <button class="btn  my-2 my-sm-0" type="submit">Resume</button>
        </form>
      </div>
    </nav>
    <div class="col section-name mt-5 mx-auto">
      <p class="main-text-color">Hi, my name is</p>
      <p>Alexandru Tabara</p>
      <p class="secondary-text-color ">I build things for the web</p>
      <p class="my-3">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquam animi blanditiis dicta, dolores fuga minima recusandae rerum sit suscipit totam. Aperiam commodi dolor ducimus eius enim maxime nam nisi officia pariatur quidem, quisquam rerum sequi, suscipit tenetur voluptatem? Doloremque, nisi!</p>
      <button class="btn my-3">Get in Touch</button>
    </div>
    <div class="col mx-auto section-about mt-5">
      <div class="section-about__title"><span class="pr-3">01</span>About me</div>
      <div class="section-about__description d-block">
        <div class="col pt-3 px-0">
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Adipisci earum laboriosam magni reprehenderit veniam? Consectetur cum incidunt ipsa iste laborum modi necessitatibus repellat! Deserunt iure mollitia quis quos repudiandae veniam!</p>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusamus adipisci aliquam aliquid culpa deserunt dicta distinctio dolor dolore dolorem ea eligendi eos fugiat id illum ipsam iste magnam modi nemo nesciunt obcaecati officiis, perspiciatis quae quibusdam quidem quo ratione reiciendis rem reprehenderit repudiandae sed sequi, tempore velit voluptate. Est, exercitationem?</p>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Architecto consequatur deserunt esse facere hic laudantium nam quas qui, quisquam rerum sed sequi suscipit veniam, veritatis.</p>
          <div class="row d-flex">
            <div class="col">
              <h5>Utilitare</h5>
              <div><i class="fas fa-caret-right"></i> HTML5</div>
              <div><i class="fas fa-caret-right"></i> CSS3</div>
              <div><i class="fas fa-caret-right"></i> Sass</div>
              <div><i class="fas fa-caret-right"></i> BootStrap 4</div>
            </div>
            <div class="col">
              <h5>FrameWork</h5>
              <div><i class="fas fa-caret-right"></i> VueJS</div>
              <div><i class="fas fa-caret-right"></i> React</div>
              <div><i class="fas fa-caret-right"></i> Angular</div>
              <div><i class="fas fa-caret-right"></i> NodeJS</div>
            </div>
            <div class="col">
              <h5>FrameWork</h5>
              <div><i class="fas fa-caret-right"></i> VueJS</div>
              <div><i class="fas fa-caret-right"></i> React</div>
              <div><i class="fas fa-caret-right"></i> Angular</div>
              <div><i class="fas fa-caret-right"></i> NodeJS</div>
            </div>
            <div class="col">
              <h5>FrameWork</h5>
              <div><i class="fas fa-caret-right"></i> VueJS</div>
              <div><i class="fas fa-caret-right"></i> React</div>
              <div><i class="fas fa-caret-right"></i> Angular</div>
              <div><i class="fas fa-caret-right"></i> NodeJS</div>
            </div>
          </div>
        </div>
        <div class="d-flex justify-content-center mt-4">
          <div class="img-home text-center d-none d-xl-flex">
            <img class="mt-3" src="../assets/png-img.png" alt="">
          </div>
        </div>
      </div>

    </div>
    <About></About>
  </div>
</template>

<style lang="scss">
  $main-text-color: #64C7CC;
  $main-bg-color: rgb(10, 25, 47);
  .main-text-color {color: $main-text-color;}
  .secondary-text-color {color: lightgrey}
  span {color: $main-text-color;}
  .padding {padding: 0 5px}

  .btn {color: $main-text-color;border: 2px solid $main-text-color;background: $main-bg-color;}

  .home {
  background: $main-bg-color;
    .navbar {
    .navbar-brand {
      .hexagon {
        position: relative;
        width: 30px;
        height: 17.32px;
        background-color: $main-bg-color;
        margin: 8.66px 0;
        box-shadow: 0 0 10px $main-text-color;
        border-left: solid 3px $main-text-color;
        border-right: solid 3px $main-text-color;
      }
      .hexagon:before,
      .hexagon:after {
        content: "";
        position: absolute;
        z-index: 1;
        width: 21.21px;
        height: 21.21px;
        -webkit-transform: scaleY(0.5774) rotate(-45deg);
        -ms-transform: scaleY(0.5774) rotate(-45deg);
        transform: scaleY(0.5774) rotate(-45deg);
        background-color: inherit;
        left: 1.3934px;
        box-shadow: 0 0 10px $main-text-color;
      }
      .hexagon:before {
        top: -10.6066px;
        border-top: solid 4.2426px $main-text-color;
        border-right: solid 4.2426px $main-text-color;
      }
      .hexagon:after {
        bottom: -10.6066px;
        border-bottom: solid 4.2426px $main-text-color;
        border-left: solid 4.2426px $main-text-color;
      }
      /*cover up extra shadows*/
      .hexagon span {
        display: block;
        position: absolute;
        top:1.7320508075688772px;
        left: 0;
        width:24px;
        height:13.8564px;
        z-index: 2;
        background: inherit;
        text-align: center;
        line-height: 12px;
        font-weight: bold;
        font-size: 17px;
        color: $main-text-color;
      }
    }
    .navbar-toggler {
      .hamburger-menu {
        width: 30px;
        height: 40px;
        .section-about__title {
          width: 30px;
          height: 4px;
          background: $main-text-color!important;
          margin: 2px 0;
        }
      }
    }
    .navbar-collapse {
      a:hover {
        color: $main-text-color;
      }
      a{
        color: lightgrey;
      }
    }
  }
    .section-about {
      .section-about__description {
        color: lightgrey;
        position: relative;
          .fas {color: $main-text-color;}
        .img-home:hover:before {
          top: 0;
          left: 0;
          transition: ease-in-out 0.8s;
        }
       .img-home:before {
         content: "";
         position: absolute;
         width: 100%;
         height: 100%;
         top: 0;
         left: 0;
         background: transparent;
         border: 3px solid $main-text-color;

       }
      .img-home {
        position: relative;
        height: 180px;
        width: 180px;
        img {
          width: 150px;
          height: 150px;
        }
      }

      }
    }
}
</style>

<script>
import About from '../views/About'


export default {
  name: "Home",
  components: {
    About
  }
};
</script>
