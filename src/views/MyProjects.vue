<template>
    <div class="project">
       <div class="row section-project mx-auto mt-5">
           <div class="section-project__title mx-0  pr-3">
               <span class="pr-3 ">03.</span>Some Things I've Build
           </div>
           <div class="col section-project__img">
               <div class="img-overlay"></div>
           </div>
           <div class="col-sm-6 section-project__text text-right text-light">
               <p>Featured Project</p>
               <h5>OctoProfile</h5>
               <p class="bg-dark">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Animi consequatur cum delectus deleniti dignissimos dolores dolorum eaque enim harum laborum laudantium, minus modi quidem rerum sint tempore velit vero vitae voluptates voluptatum! Autem, fuga ullam.</p>
               <div><p>HTML CSS SASS GitHub Api</p></div>
               <div><i class="fab fa-github mx-5"></i><i class="fas fa-external-link-alt pr-3"></i></div>
           </div>
       </div>
        <div class="row section-contact mx-auto">
            <div class="col section-contact__title mx-0  pr-3">
                <span class="pr-3 ">04. What's Next?</span>
                <p>Get In Touch</p>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusantium architecto atque consectetur culpa, eius, est ex id illo inventore ipsam libero officiis optio perspiciatis porro possimus quia voluptatibus? Dignissimos, fugit!</p>
                <div class="btn">Say Hello</div>
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
    }
    @media only screen and (max-width: 575px) {
    }

    .project{
        .section-project{
            position: relative;
            padding-top: 50px;
            .section-project__title{
                position: absolute;
                top: -17px;
                left: 0;
                background: $main-bg-color;
                z-index: 5;
                font-size: 22px;
                color: white;
            }
            .section-project__img:hover .img-overlay{
                display: none;
            }
            .section-project__img {
                background-image: url("../assets/website1.png");
                height: 400px;
                background-repeat: no-repeat;
                position: relative;
                .img-overlay{
                    position: absolute;
                    top: 0;
                    left: 0;
                    background: $main-bg-color;
                    height: 100%;
                    width: 100%;
                    opacity: 0.7;
                }
            }
            .section-project__title{
                position: absolute;
                left: 0;
                top: -10px;
            }
            .section-project__text {
                position: absolute;
                right: 0;
                opacity: 0.8;
                height: 100%;
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
