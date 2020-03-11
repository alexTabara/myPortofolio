<template>
    <div class="project">
        <div class="col-sm px-0 col-lg-10 mx-auto mt-5">
            <div class="row mx-0 second-text-size pt-5 third-text-color" id="work">
                <span class="pr-3 ">03.</span>Some Things I've Build
            </div>
            <div class="row section-project mx-0 mt-5">
                <div class="col-sm  section-project__img section-project__img-left"></div>
                <div class="col-sm section-project__text text-right d-flex flex-column align-items-end">
                    <h5 class="py-3 main-text-color">GoodFood</h5>
                    <h6 class="">First Project</h6>
                    <p >The project  was completed in 4 days and i used it the followind tools below:</p>
                    <div class="my-4"><span>HTML CSS SASS</span></div>
                    <div>
                        <a target="_blank" href="https://github.com/alexTabara/goodfood.git"><i class="fab fa-github mr-5"></i></a>
                        <a target="_blank" href="http://alexandrutabara.ro/GoodFood/dist/"><i class="fas fa-external-link-alt pr-3"></i></a>
                    </div>
                </div>
            </div>
            <div class="row section-project mx-0 my-5">
                <div class="col-sm  section-project__img section-project__img-right"></div>
                <div class="col-sm section-project__text text-left d-flex flex-column align-items-start">
                    <h5 class="py-3 main-text-color">Ficto</h5>
                    <h6 class="">Second Project</h6>
                    <p >The project  was completed in 7 days and i used it the followind tools below:</p>
                    <div class="my-4"><span>HTML CSS SASS VueJs</span></div>
                    <div>
                        <a target="_blank" href="https://github.com/alexTabara/TaG.git"><i class="fab fa-github mr-5"></i></a>
                        <a target="_blank" href="http://alexandrutabara.ro/TaG/dist/"><i class="fas fa-external-link-alt pr-3"></i></a>
                    </div>
                </div>
            </div>
            <div class="row section-project mx-0 mb-5">
                <div class="col-sm  section-project__img section-project__img-portofolio"></div>
                <div class="col-sm section-project__text text-right d-flex flex-column align-items-end justify-content-between">
                    <h5 class="py-3 main-text-color">My Portofolio</h5>
                    <h6 class="d-none d-lg-flex">Third Project</h6>
                    <p class="d-none d-lg-inline">The project  was completed in 5 days and i used it the followind tools below:</p>
                    <div class="my-4 d-none d-lg-flex "><span>HTML CSS SASS VueJs</span></div>
                    <div>
                        <a target="_blank" href="https://github.com/alexTabara/myPortofolio.git"><i class="fab fa-github mr-5"></i></a>
                        <a target="_blank" href="http://alexandrutabara.ro/Portofolio/dist/"><i class="fas fa-external-link-alt pr-3"></i></a>
                    </div>
                </div>
            </div>
            <div class="row section-contact mx-auto" id="contact">
                <div class="col-sm-6  section-contact__title mx-auto  pr-3 text-center">
                    <span class="pr-3 second-text-size">04. What's Next?</span>
                    <p class="my-4">Get In Touch</p>
                    <p>Although i'm not currently looking for freelance opportunities, my imbox is always open. Wheter for a potential project or just to say hi.</p>
                    <div class="btn my-4"><a target="_blank" href="mailto:talexandrugeorge@gmail.com">Say Hello</a></div>
                </div>
            </div>
        </div>
    </div>
</template>


<style scoped lang="scss">
    $main-text-color: #64C7CC;
    $main-bg-color: rgb(10, 25, 47);
    $secondary-text-color: rgb(136, 146, 176);
    $third-text-color: #f7f7f7;
    @media only screen and (min-width: 676px) {
        .section-project{
            p {width: 60%;}
        }
        .section-contact {
            margin-top: 100px;
            margin-bottom: 80px;
        }
    }
    @media only screen and (min-width: 576px) {
        .section-project{
        }
        .section-contact {
            margin-top: 100px;
            margin-bottom: 80px;
        }
    }
    @media only screen and (max-width: 575px) {
        .section-project{

        }

    }
    @media only screen and (max-width: 775px) {
        .section-project:hover .section-project__text p{
            visibility: hidden;
        }
        .section-project:hover .section-project__text h5{
            visibility: hidden;
        }
        .section-project:hover .section-project__text h6{
            visibility: hidden;
        }
        .section-project:hover .section-project__text span{
            visibility: hidden;
        }
        .section-project:hover .section-project__text i{
            color: #e6e6e6;
        }

    }
    .project{
        .section-project:hover .section-project__img-left {opacity: 0.7; }
        .section-project:hover .section-project__img-right {opacity: 0.7; }

        .section-project {
            position: relative;
            .section-project__img-left {
                background-image: url("../assets/goodfood.png");
                opacity: 0.4;
            }
            .section-project__img-portofolio {
                background-image: url("../assets/portofolio.png");
            }
            .section-project__img-right {
                background-image: url("../assets/ficto.png");
                background-position: right;
                opacity: 0.4;
            }
            .section-project__img {
                background-repeat: no-repeat;
                height: 350px;

            }
            .section-project__text {
                color:$third-text-color;
                position: absolute;
                top: 0;
                right: 0;
                width: 100%;
                height: 100%;
                a {
                    color: white;
                    i { font-size: 20px}
                    i:hover {
                        color: $main-text-color;
                    }
                }
            }
        }
        .section-contact {
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

</script>
