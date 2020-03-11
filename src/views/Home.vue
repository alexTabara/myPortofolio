<template>
  <div class="home">
    <div class="padding">
      <div class="streak-left d-none d-lg-flex"></div>
      <div class="streak-right d-none d-lg-flex"></div>
      <ul class="media-left text-left p-0 d-none d-lg-block">
        <li><a target="_blank" href="https://github.com/alexTabara"><i class="fab fa-github"></i></a></li>
        <li><a target="_blank" href="https://www.linkedin.com/in/tabara-alexandru-904805144/"><i class="fab fa-linkedin-in"></i></a></li>
        <li><a href=""><i class="fab fa-instagram"></i></a></li>
      </ul>
      <div class="email-right secondary-text-color d-none d-lg-block"><a target="_blank" href="mailto:talexandrugeorge@gmail.com">talexandrugeorge@gmail.com</a></div>
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
              <a class="nav-link" href="#about"><span>01.</span> About <span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#experience"><span>02.</span> Experience</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#work"><span>03.</span> Work</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#contact"><span>04.</span> Contact</a>
            </li>
          </ul>
          <form class="form my-2 my-lg-0">
            <button class="btn  my-2 my-sm-0" type="submit"><a target="_blank" href="https://github.com/alexTabara">GitHub</a></button>
          </form>
        </div>
      </nav>
      <div class="col-sm  section-name col-lg-7  mx-auto text-center">
        <p class="main-text-color">Hi, my name is</p>
        <p class="third-text-color text-size">Alexandru Tabara</p>
        <p class="secondary-text-color second-text-size">I build things for the web</p>
        <h6 class="my-3 secondary-text-color">I am a web developer based in Bucharest, specialized in building high-quality websites. </h6>
        <button class="btn my-3"><a target="_blank" href="mailto:talexandrugeorge@gmail.com">Get in Touch</a></button>
      </div>
      <div class="col-sm col-lg-10 mx-auto section-about align-middle mt-5 d-flex flex-column justify-content-around" id="about">
        <div class="section-about__title second-text-size"><span class="pr-3">01</span>About me</div>
        <div class="section-about__description d-block">
          <div class="col-sm px-0">
            <h5 class="secondary-text-color pt-2">I have spent the last months learning to code  and though challenging at times, it has been a highly rewarding experience.  </h5>
            <h5 class="secondary-text-color">During these past months I developed an advanced training routine, called deep practice, allowing me to build an amazing skill set in the tech toolkit as Html, CSS and Bootstrap 4. And now I need to push myself, to advance from amateur stage to become and expert, to move forward, to innovate and open new avenues for others as well.</h5>
            <div class="row progress-barcss d-flex mt-md-5">
              <div class="col-sm-12 col-md-6  section-about__skills ">
                <h5>Standard language & Web Design</h5>
                <div><i class="fas fa-caret-right"></i> HTML <i class="fab fa-html5"></i></div>
                <div><i class="fas fa-caret-right"></i> CSS <i class="fab fa-css3-alt"></i></div>
                <div><i class="fas fa-caret-right"></i> Sass <i class="fab fa-sass"></i></div>
                <div><i class="fas fa-caret-right"></i> WordPress <i class="fab fa-wordpress"></i></div>
              </div>
              <div class="col-sm-12 col-md-6  section-about__skills">
                <h5>FrameWork</h5>
                <div><i class="fas fa-caret-right"></i> VueJS <i class="fab fa-vuejs"></i></div>
                <div><i class="fas fa-caret-right"></i> React <i class="fab fa-react"></i></div>
                <div><i class="fas fa-caret-right"></i> Angular <i class="fab fa-angular"></i></div>
                <div><i class="fas fa-caret-right"></i> BootStrap4 <i class="fab fa-bootstrap"></i></div>
              </div>
              <div class="col-sm-12 col-md-6 section-about__skills">
                <h5>Tools</h5>
                <div><i class="fas fa-caret-right"></i> Adobe Creative Cloud <i class="fab fa-adobe"></i></div>
                <div><i class="fas fa-caret-right"></i> BEM </div>
                <div><i class="fas fa-caret-right"></i> BuildPack</div>
                <div><i class="fas fa-caret-right"></i> GitHub <i class="fab fa-github-square"></i></div>
              </div>
              <div class="col-sm-12 col-md-6 section-about__skills">
                <h5>Source Code Editor</h5>
                <div><i class="fas fa-caret-right"></i> PhpStorm </div>
                <div><i class="fas fa-caret-right"></i> Sublime Text 3</div>
                <div><i class="fas fa-caret-right"></i> Visual Studio Code</div>
                <div><i class="fas fa-caret-right"></i> Nodepad++</div>
              </div>
            </div>
          </div>
        </div>

      </div>
      <About></About>
    </div>
    <div class="srct-contact">
      <div class="col-sm text-center secondary-text-color">
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
  .text-size { font-size: 60px; font-weight: bold}
  .second-text-size {font-size: 25px;font-weight: bold}
  .main-text-color {color: $main-text-color;}
  .secondary-text-color {color: rgb(136, 146, 176)}
  .third-text-color {color: $third-text-color}
  span {color: $main-text-color;}
  .padding {padding: 0 5px}
  .btn {color: $main-text-color;border: 2px solid $main-text-color;background: $main-bg-color;}
  .btn:hover{
    color: $main-text-color;
  }
  .btn:focus, .btn:active {
    outline: none !important;
    box-shadow: none !important;
    outline: 0
  }

  @media only screen and (min-width: 576px) {
    .padding {padding: 0 50px}
  }
  @media only screen and (max-width: 575px) {
  }
  @media only screen and (min-width: 992px) {
    .text-size { font-size: 55px; font-weight: bold}
    .second-text-size {font-size: 25px;font-weight: bold}
  }
  @media only screen and (max-width: 992px) {
    .text-size { font-size: 33px; font-weight: bold}
    .second-text-size {font-size: 20px;font-weight: bold}
  }


  .home {
  background: $main-bg-color;
  .padding{
    .streak-left{
      position: fixed;
      bottom: 0;
      left: 40px;
      height: 14vh;
      width: 2px;
      background: $secondary-text-color;
    }
    .streak-right{
      position: fixed;
      bottom: 0;
      right: 40px;
      height: 14vh;
      width: 2px;
      background: $secondary-text-color;
    }
    .media-left{
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
            margin: 30px 0;
            cursor: pointer;
          }
        }
      }
    }
    .email-right:hover a{
      color: $main-text-color;
      cursor: pointer;
      text-decoration: none;
    }
    .email-right{
      position: fixed;
      top: calc(100vh - 40vh);
      right: 30px;
      writing-mode: vertical-rl;
      a{
        color: white;}
    }
    .navbar {
      background: $main-bg-color;
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
          color: $main-text-color;
          div {
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
          color: $third-text-color;
          text-decoration: none;
        }
      }
    }


    /* SECTION_NAME*/

    @media only screen and (min-width: 992px) {
      .section-name{
        padding: 250px 0;
        height: 93vh;}
    }
    @media only screen and (max-width: 992px) {
      .section-name{margin: 30px 0}
    }

    /* SECTION_ABOUT*/

    @media only screen and (min-width: 992px) {
      .section-about{
        height: 100vh;
        .progress-barcss {
          .section-about__skills{
            margin-top: 10px;
            div {
              margin: 12px 0;
            }
          }
        }
      }
    }
    @media only screen and (max-width: 992px) {
      .section-about{
        margin: 30px 0;
        .progress-barcss {
          padding-top: 10px;
          .section-about__skills{
            padding-top: 10px;
            div {
              margin-bottom: 12px;
            }
          }
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
          .section-about__skills:nth-child(1) div:nth-child(2):before{width: 65%;}
          .section-about__skills:nth-child(1) div:nth-child(3):before{width: 42%;}
          .section-about__skills:nth-child(1) div:nth-child(4):before{width: 38%;}
          .section-about__skills:nth-child(1) div:nth-child(5):before{width: 15%;}

          .section-about__skills:nth-child(2) div:nth-child(2):before{width: 15%;}
          .section-about__skills:nth-child(2) div:nth-child(3):before{width: 6%;}
          .section-about__skills:nth-child(2) div:nth-child(4):before{width: 7%;}
          .section-about__skills:nth-child(2) div:nth-child(5):before{width: 45%;}

          .section-about__skills:nth-child(3) div:nth-child(2):before{width: 14%;}
          .section-about__skills:nth-child(3) div:nth-child(3):before{width: 36%;}
          .section-about__skills:nth-child(3) div:nth-child(4):before{width: 52%;}
          .section-about__skills:nth-child(3) div:nth-child(5):before{width: 12%;}

          .section-about__skills:nth-child(4) div:nth-child(2):before{width: 61%;}
          .section-about__skills:nth-child(4) div:nth-child(3):before{width: 70%;}
          .section-about__skills:nth-child(4) div:nth-child(4):before{width: 94%;}
          .section-about__skills:nth-child(4) div:nth-child(5):before{width: 55%;}

          .section-about__skills{
            color: $third-text-color;
            h5 { font-size: 18px}
            .fab,.fa-boxes, .fa-ethernet{
              font-size: 20px;
              color: $third-text-color;
              padding-left: 10px;
            }
            div:nth-child(n):before{
              content: "";
              bottom: -3px;
              left: 0;
              height: 2px;
              position: absolute;
              background: $main-text-color;
            }
            div:hover .fab {
              color: $main-text-color;
            }
            div{
              color: $secondary-text-color;
              position: relative;
              border-bottom: 5px solid #2c3e50;
              .fa-caret-right {color: $main-text-color; margin-right: 10px}
            }
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
    .section-name {
      a:hover {
        color: $third-text-color;
      }
      a {
        color: $main-text-color;
        text-decoration: none;
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
