<template>
<div>
              <section class="feature_2 bg-light pt-90 pb-60 text-center">
                <div style="margin-top: 30px;" class="row">
                    <div class="col-lg-3">
                        <div class="container px-xl-0">
                            <div class="row justify-content-center">
                                <div class="col-xl-8 col-lg-10">
                                    <br>
                                    <h2 class="small" style="
                                    color:white;
                                    font-family: 'Secular One', sans-serif;
                                    text-transform:uppercase;
                                    text-align:start;
                                    " data-aos-duration="600" data-aos="fade-down" data-aos-delay="0">Webtools</h2>
                                </div>
                            </div>
                        </div>
                    </div>
                    <br>
                     <div class="col-lg-9">
                        <div class="container px-xl-0">
                            <div class="row justify-content-center">
                                <div class="col-xl-8 col-lg-10">
                                    <br>
                                    <div class="row">
                                        <div v-for="item in web" :key="item.id" class="col-lg-4 col-sm-6">
                                            <div style="
                                                padding: 50px;
                                                border-radius: 12px;">
                                             <img style="width:50px;
                                             "  :src="item.image" alt="">
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                        <br><br>
                        <div class="col-lg-3">
                        <div  class="container px-xl-0">
                            <div class="row justify-content-center">
                                <div class="col-xl-8 col-lg-10">
                                    <br>
                                    <h2 class="small" style="
                                    color:white;
                                    font-family: 'Secular One', sans-serif;
                                    text-transform:uppercase;
                                    text-align:start;
                                    margin-top:90px;
                                    " data-aos-duration="600" data-aos="fade-down" data-aos-delay="0">multimedia</h2>
                                </div>
                            </div>
                        </div>
                    </div>
                      <div class="col-lg-9">
                        <div class="container px-xl-0">
                            <div class="row justify-content-center">
                                <div class="col-xl-8 col-lg-10">
                                    <br>
                                    <div class="row">
                                        <div v-for="item in other" :key="item.id" class="col-lg-4">
                                            <div style="
                                                padding: 60px;
                                                border-radius: 12px;">
                                               <img style="width:50px;
                                             "  :src="item.image" alt="">
                                            </div>
                                        </div>
                                    </div>
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
  name: 'Skill',
  data() {
    return {
      nama: "muhammad ghifar ziady",
      aboutme: "When l was 19 years old already had an interest in web programming, from there wanted to make my passion into a job. I believe in learning through practice and seeking out these new experiences will make me a creative programmer.",
      mine: " In addition to web programming I am also able in terms of video making from videography to cinematography.",

      web:[
          {id:1, image:"img/skill/Git_icon.svg.png"},
          {id:2, image:"img/skill/github.png"},
          {id:3, image:"img/skill/cpanel-logo.png"},
          {id:4, image:"img/skill/html.png"},
          {id:5, image:"img/skill/css3.png"},
          {id:6, image:"img/skill/laravel.png"},
          {id:7, image:"img/skill/PHP_logo.png"},
          {id:8, image:"img/skill/vue.png"},
          {id:9, image:"img/skill/boot.png"},
          {id:10, image:"img/skill/my.png"},
          {id:11, image:"img/skill/node.png"},
          {id:12, image:"img/skill/js.png"},
      ],
      other:[
          {id:1, image:"img/skill/ai.png"},
          {id:2, image:"img/skill/fiqma.png"},
          {id:3, image:"img/skill/pr.png"},
      ]
    }
  },
}

</script>

<style>
</style>

