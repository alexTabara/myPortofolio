<template>
    <div class="project">
        <div class="col-sm px-0 col-lg-10 mx-auto mt-5">
            <div class="row section-project mx-2 d-block" id="work">
                <div class="section-project__title pr-3 second-text-size">
                    <span class="pr-3 ">03.</span>Some Things I've Build
                </div>
                <div class="col d-flex">
                    <div class="col project-img project-img__right mt-5">
                        <div class="img-overlay"></div>
                    </div>
                    <div class="col-sm-6 section-project__text section-project__text-right text-right text-light mt-5">
                        <h5>GoodFood</h5>
                        <h6 class="my-3">OctoProfile</h6>
                        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Animi consequatur cum delectus deleniti dignissimos dolores dolorum eaque enim harum laborum laudantium, minus modi quidem rerum sint tempore velit vero vitae voluptates voluptatum! Autem, fuga ullam.</p>
                        <div class="my-4"><span>HTML CSS SASS GitHub Api</span></div>
                        <div><i class="fab fa-github mx-5"></i><i class="fas fa-external-link-alt pr-3"></i></div>
                    </div>
                </div>
                <div class="col d-flex">
                    <div class="col-sm-6 ml-auto project-img project-img__left mt-5">
                        <div class="img-overlay"></div>
                    </div>
                    <div class="col-sm-6 section-project__text section-project__text-left text-left text-light  mt-5">
                        <h5>Ficto</h5>
                        <h6 class="my-3">OctoProfile</h6>
                        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Animi consequatur cum delectus deleniti dignissimos dolores dolorum eaque enim harum laborum laudantium, minus modi quidem rerum sint tempore velit vero vitae voluptates voluptatum! Autem, fuga ullam.</p>
                        <div class="my-4"><span>HTML CSS SASS GitHub Api</span></div>
                        <div><i class="fab fa-github mx-5"></i><i class="fas fa-external-link-alt pr-3"></i></div>
                    </div>

                </div>
                <div class="col d-flex">
                    <div class="col project-img project-img__right mt-5">
                        <div class="img-overlay"></div>
                    </div>
                    <div class="col-sm-6 section-project__text section-project__text-right text-right text-light mt-5">
                        <h5>Featured Project</h5>
                        <h6 class="my-3">OctoProfile</h6>
                        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Animi consequatur cum delectus deleniti dignissimos dolores dolorum eaque enim harum laborum laudantium, minus modi quidem rerum sint tempore velit vero vitae voluptates voluptatum! Autem, fuga ullam.</p>
                        <div class="my-4"><span>HTML CSS SASS GitHub Api</span></div>
                        <div><i class="fab fa-github mx-5"></i><i class="fas fa-external-link-alt pr-3"></i></div>
                    </div>
                </div>
            </div>
            <div class="row section-contact mx-auto " id="contact">
                <div class="col-sm-6  section-contact__title mx-auto  pr-3 text-center">
                    <span class="pr-3  second-text-size">04. What's Next?</span>
                    <p>Get In Touch</p>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusantium architecto atque consectetur culpa, eius, est ex id illo inventore ipsam libero officiis optio perspiciatis porro possimus quia voluptatibus? Dignissimos, fugit!</p>
                    <div class="btn">Say Hello</div>
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
    @media only screen and (min-width: 576px) {
        .section-project{
            margin-top: 150px;
            margin-bottom: 150px;
        }
        .section-contact {
            margin-top: 100px;
            margin-bottom: 80px;
        }
    }
    @media only screen and (max-width: 575px) {

    }

    .project{
        .section-project{
            position: relative;
            .section-project__title{
                position: absolute;
                top: -17px;
                left: 0;
                background: $main-bg-color;
                z-index: 5;
                color: white;
            }
            .project-img:hover .img-overlay{
                display: none;
            }

            .project-img {
                height: 400px;
                background-repeat: no-repeat;
                position: relative;
                .img-overlay{
                    position: absolute;
                    top: 0;
                    right: 0;
                    background: $main-bg-color;
                    height: 100%;
                    width: 100%;
                    opacity: 0.7;
                }
            }
            .project-img__right {background-image: url("../assets/goodfood.png");}
            .project-img__left {background-image: url("../assets/ficto.png");            }

            .section-project__title{
                position: absolute;
                left: 0;
                top: -10px;
            }
            .section-project__text-left { left: 0;}
            .section-project__text-right { right: 0;}

            .section-project__text {
                position: absolute;
                opacity: 0.8;
                height: 100%;
                h5 { color: $main-text-color}
                h6{color: $secondary-text-color}
                .fa-github:hover ,.fa-external-link-alt:hover{
                    color: $main-text-color;
                    transform: scale(1.3);
                }
            }
        }

    }

</style>



<script>

</script>
