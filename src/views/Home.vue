<template>
  <div class="home">
    <div class="padding">
      <div class="streak-left"></div>
      <div class="streak-right"></div>
      <ul class="media-left text-left p-0">
        <li><a href=""><i class="fab fa-github"></i></a></li>
        <li><a href=""><i class="fab fa-linkedin-in"></i></a></li>
        <li><a href=""><i class="fab fa-instagram"></i></a></li>
      </ul>
      <div class="email-right secondary-text-color d-block">talexandrugeorge@gmail.com</div>
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
        <p class="third-text-color">Alexandru Tabara</p>
        <p class="secondary-text-color ">I build things for the web</p>
        <p class="my-3 secondary-text-color">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquam animi blanditiis dicta, dolores fuga minima recusandae rerum sit suscipit totam. Aperiam commodi dolor ducimus eius enim maxime nam nisi officia pariatur quidem, quisquam rerum sequi, suscipit tenetur voluptatem? Doloremque, nisi!</p>
        <button class="btn my-3">Get in Touch</button>
      </div>
      <div class="col mx-auto section-about mt-5">
        <div class="section-about__title"><span class="pr-3">01</span>About me</div>
        <div class="section-about__description d-block">
          <div class="col pt-3 px-0">
            <p class="secondary-text-color">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Adipisci earum laboriosam magni reprehenderit veniam? Consectetur cum incidunt ipsa iste laborum modi necessitatibus repellat! Deserunt iure mollitia quis quos repudiandae veniam!</p>
            <p class="secondary-text-color">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusamus adipisci aliquam aliquid culpa deserunt dicta distinctio dolor dolore dolorem ea eligendi eos fugiat id illum ipsam iste magnam modi nemo nesciunt obcaecati officiis, perspiciatis quae quibusdam quidem quo ratione reiciendis rem reprehenderit repudiandae sed sequi, tempore velit voluptate. Est, exercitationem?</p>
            <p class="secondary-text-color">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Architecto consequatur deserunt esse facere hic laudantium nam quas qui, quisquam rerum sed sequi suscipit veniam, veritatis.</p>
            <div class="row progress-barcss d-flex">
              <div class="col-sm parinte">
                <h5>Utilitare</h5>
                <div><i class="fas fa-caret-right"></i> HTML <i class="fab fa-html5"></i></div>
                <div><i class="fas fa-caret-right"></i> CSS <i class="fab fa-css3-alt"></i></div>
                <div><i class="fas fa-caret-right"></i> Sass <i class="fab fa-sass"></i></div>
                <div><i class="fas fa-caret-right"></i> WordPress <i class="fab fa-wordpress"></i></div>
              </div>
              <div class="col-sm parinte">
                <h5>FrameWork</h5>
                <div><i class="fas fa-caret-right"></i> VueJS <i class="fab fa-vuejs"></i></div>
                <div><i class="fas fa-caret-right"></i> React <i class="fab fa-react"></i></div>
                <div><i class="fas fa-caret-right"></i> Angular <i class="fab fa-angular"></i></div>
                <div><i class="fas fa-caret-right"></i> BootStrap4 <i class="fab fa-bootstrap"></i></div>
              </div>
              <div class="col-sm parinte">
                <h5>Tools</h5>
                <div><i class="fas fa-caret-right"></i> Adobe Creative Cloud <i class="fab fa-adobe"></i></div>
                <div><i class="fas fa-caret-right"></i> BEM <i class="fas fa-ethernet"></i></div>
                <div><i class="fas fa-caret-right"></i> BuildPack <i class="fas fa-boxes"></i></div>
                <div><i class="fas fa-caret-right"></i> GitHub <i class="fab fa-github-square"></i></div>
              </div>
              <div class="col-sm parinte">
                <h5>Source Code Editor</h5>
                <div><i class="fas fa-caret-right"></i> PhpStorm </div>
                <div><i class="fas fa-caret-right"></i> Sublime Text 3</div>
                <div><i class="fas fa-caret-right"></i> Visual Studio Code</div>
                <div><i class="fas fa-caret-right"></i> Nodepad++</div>
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
    <div class="srct-contact">
      <div class="col-sm-2 mx-auto secondary-text-color">
        <p>Design & Build by Alexandru Tabara</p>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
  $main-text-color: rgb(100, 255, 218);
  $main-bg-color: rgb(10, 25, 47);
  $secondary-text-color: rgb(136, 146, 176);
  $third-text-color: #f7f7f7;
  .main-text-color {color: $main-text-color;}
  .secondary-text-color {color: rgb(136, 146, 176)}
  .third-text-color {color: $third-text-color}
  span {color: $main-text-color;}
  .padding {padding: 0 5px}
  .btn {color: $main-text-color;border: 2px solid $main-text-color;background: $main-bg-color;}

  @media only screen and (min-width: 576px) {
    .padding {padding: 0 50px}
  }
  @media only screen and (max-width: 575px) {
  }


  .home {
  background: $main-bg-color;
  .padding{
    .streak-left{
      position: fixed;
      bottom: 0;
      left: 40px;
      height: 138px;
      width: 2px;
      background: $secondary-text-color;
    }

    .streak-right{
      position: fixed;
      bottom: 0;
      right: 40px;
      height: 138px;
      width: 2px;
      background: $secondary-text-color;
    }
    .media-left{
      display: block;
      position: fixed;
      top: calc(100vh - 40vh);
      left: 30px;
      li:hover i{
        color: $main-text-color;
        transform: scale(1.2);
      }
      li{
        list-style: none;
        a{
          i {
            font-size: 20px;
            color: $third-text-color;
            background: $main-bg-color;
            margin: 20px 0;
            cursor: pointer;
          }
        }
      }
    }
    .email-right:hover{
      color: $main-text-color;
      cursor: pointer;
    }
    .email-right{
      position: fixed;
      top: calc(100vh - 40vh);
      right: 30px;
      writing-mode: vertical-rl;
    }
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
            background: $main-text-color;
            margin: 2px 0;
          }
        }
      }
      .navbar-collapse {
        a:hover {
          color: $main-text-color;
        }
        a{
        }
      }
    }
    .section-about {
      .section-about__title{
        color: $third-text-color;
      }
      .section-about__description {
        position: relative;
        .progress-barcss {
          .parinte:nth-child(1) div:nth-child(2):before{width: 91%;}
          .parinte:nth-child(1) div:nth-child(3):before{width: 73%;}
          .parinte:nth-child(1) div:nth-child(4):before{width: 69%;}
          .parinte:nth-child(1) div:nth-child(5):before{width: 56%;}

          .parinte:nth-child(2) div:nth-child(2):before{width: 21%;}
          .parinte:nth-child(2) div:nth-child(3):before{width: 10%;}
          .parinte:nth-child(2) div:nth-child(4):before{width: 14%;}
          .parinte:nth-child(2) div:nth-child(5):before{width: 5%;}

          .parinte:nth-child(3) div:nth-child(2):before{width: 21%;}
          .parinte:nth-child(3) div:nth-child(3):before{width: 10%;}
          .parinte:nth-child(3) div:nth-child(4):before{width: 14%;}
          .parinte:nth-child(3) div:nth-child(5):before{width: 5%;}

          .parinte:nth-child(4) div:nth-child(2):before{width: 21%;}
          .parinte:nth-child(4) div:nth-child(3):before{width: 10%;}
          .parinte:nth-child(4) div:nth-child(4):before{width: 14%;}
          .parinte:nth-child(4) div:nth-child(5):before{width: 5%;}

          .parinte{
            color: $third-text-color;
            div:nth-child(n):before{
              content: "";
              bottom: -3px;
              left: 0;
              height: 2px;
              position: absolute;
              background: $main-text-color;
            }
            div{
              color: $secondary-text-color;
              position: relative;
              border-bottom: 5px solid #2c3e50;
              .fa-caret-right {color: $main-text-color; margin-right: 10px}
            }
          }
        }
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
    .srct-contact {
      padding: 90px 0px 10px 0px;
      clip-path: polygon(50% 35%, 100% 0, 100% 100%, 0 100%, 0 0);
      background-color: #0a0a0a;
      p:hover {
        color: $main-text-color;
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
