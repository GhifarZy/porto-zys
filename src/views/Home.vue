<template>
<div >

 <section class="feature_2 bg-light pt-120 pb-60 text-center">
                <div style="margin-top: 30px;" class="row">
                    <div class="col-lg-6">
                        <div class="container px-xl-0">
                            <div class="row justify-content-center">
                                <div class="col-xl-8 col-lg-10">
                                    <br>
                                    <h2  class="small" style="
                                  color:white;
                                  font-family: 'Paytone One', sans-serif;
                                  " data-aos-duration="600" data-aos="fade-down" data-aos-delay="0" v-show="showModal" >FULL- STACK</h2>
                                    <h2 class="small" style="
                                  color:white;
                                  font-family: 'Secular One', sans-serif;
                                  font-size: 38px;
                                  " data-aos-duration="600" data-aos="fade-down" data-aos-delay="0">WEB DEVELOPER</h2>
                                    <div style="text-transform: uppercase;" class="color-heading text-adaptive" data-aos-duration="600" data-aos="fade-down" data-aos-delay="1200">
                                        <b style="font-family: 'Tenali Ramakrishna', sans-serif;font-size: 18px;" > Web Developer | Video Maker</b>
                                    </div>
                                    <div class="mt-35 mb-65 f-22 color-heading text-adaptive description" data-aos-duration="600" data-aos="fade-down" data-aos-delay="900">
                                        <a href="about"> <button style="
                              border: none;
                              word-wrap: break-word;
                              margin-bottom:12px;
                              border-radius: 12px;
                              padding-top: -14px;" class="btn btn-badge"></button></a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-6">
                        <div class="container px-xl-0">
                            <div class="row justify-content-center">
                                <div class="col-xl-8 col-lg-10">
                                    <br>
                                    <img class="animate__animated animate__fadeInUp animate__delay-1s" src="img/developer-dark.svg" alt="">
                                </div>

                            </div>
                        </div>
                    </div>
                </div>
            </section>
     
</div>

</template>

<script>
export default {  
  name: 'Home',
  created() {
    window.addEventListener('keydown', (e) => {
      if (e.key == 'Escape') {
        this.showModal = !this.showModal;
      }
    });
  },
  data() {
    return {
       showModal: true
    }
  }
}

</script>

<style>

</style>

