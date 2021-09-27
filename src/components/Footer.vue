<template>
     <footer style="z-index: 1;width:100%;" class="footer_1 bg-light pt-90 pb-35 text-center">
                <div class="container px-xl-0">
                    <div class="row justify-content-between align-items-center lh-40 links">
                        <div class="col-lg-4 col-sm-6 text-sm-right text-lg-left order-1 order-lg-0">
                            <a style=" color: #949494;font-family: 'Tenali Ramakrishna', sans-serif;font-size: 18px; " href="# " class="mr-15 link color-main ">&copy;COPYRIGHT ZY | 2021</a>
                        </div>
                        <div class="mb-10 mb-lg-0 col-lg-auto order-0 ">
                            <a style="color: white; " href="/" class="logo link color-main "><img class="logo" src="img/logoGUA.png" alt=""></a>

                        </div>
                        <div class="col-lg-4 col-sm-6 text-sm-left text-lg-right order-2 order-lg-0 ">

                            <a  target="_blank" href="https://www.instagram.com/ifrzdy_/" class="mx-15 link color-main"><i class="fab fa-instagram"></i></a>
                            <a  target="_blank" href="https://www.linkedin.com/in/ifarziady/" class="mx-15 link color-main"><i class="fab fa-linkedin"></i></a>
                            <a  target="_blank" href="https://github.com/GhifarZy" class="ml-15 link color-main"><i class="fab fa-github"></i></a>
                        </div>
                    </div>
                    <div class="row justify-content-center">
                        <div class="mt-10 col-xl-4 col-lg-5 col-md-6 col-sm-8" data-aos-duration="600" data-aos="fade-down" data-aos-delay="0">
                        </div>
                    </div>
                </div>
            </footer>
</template>
<script>
export default {
    name: 'Footer',
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
