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
                                    " data-aos-duration="600" data-aos="fade-down" data-aos-delay="0">about me</h2>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-9">
                        <div
                                     class="container px-xl-0">
                            <div class="row justify-content-center">
                                <div class="col-xl-8 col-lg-10">
                                    <br>
                                    <div style="
                                    /* border: 6px double #404040; */
                                    border-radius: 12px;
                                    padding:10px;">
                                    <p class="small" style="
                                    color:white;
                                    font-family:roboto;
                                    font-size: 30px;
                                    text-transform:capitalize;
                                    text-align:start;
                                    " data-aos-duration="600" data-aos="fade-down" data-aos-delay="0">{{ nama }}</p>
                                    <p style=" color:white;
                                    font-family:arial;
                                    font-size: 18px;
                                    text-align:justify;
                                    ">{{ aboutme }}<br>{{ mine }}
                                   </p>
                                    </div>
                                </div>

                            </div>
                        </div>
                    </div>
                </div>

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
                                    " data-aos-duration="600" data-aos="fade-down" data-aos-delay="0"> can i do</h2>
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
                                       <div class="col-lg-6">
                                                <div style="
                                                border: 6px double #404040;
                                                padding: 60px;
                                                border-radius: 12px;">
                                                <i style="font-size: 100px;" class=" fas fa-video">
                                                </i>
                                            </div>
                                       </div>
                                       <div class="col-lg-6">
                                                <div style="
                                                border: 6px double #404040;
                                                padding: 60px;
                                                border-radius: 12px;">
                                                 <i style="font-size: 100px;" class=" fas fa-code">
                                                </i>
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
                                    " data-aos-duration="600" data-aos="fade-down" data-aos-delay="0">education</h2>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-9">
                        <div  class="container px-xl-0">
                            <div  class="row justify-content-center">
                                <div style="
                                padding: 15px;
                                /* border: 6px double #404040; */
                                border-radius: 12px;
                                margin-top: 10px;"
                                class="col-xl-8 col-lg-10">
                                    <br>
                                   <div class="row">
                                       <div v-for="item in education" :key="item.id" class="col-lg-6">
                                       <div style="
                                                padding: 60px;
                                                border-radius: 12px;">
                                                <i style="font-size: 50px;" class=" fas fa-school">
                                                </i><br>
                                                  <b style=" color:white;
                                                font-size:20px;
                                                 font-family:roboto;" >{{ item.sekolah }}</b>
                                                 <small style="color: white;
                                                 font-weight:bold;
                                                 font-size:15px; "
                                                 >- {{ item.tahun }}</small>
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
  name: 'About',
  data() {
    return {
      nama: "muhammad ghifar ziady",
      aboutme: "When l was 19 years old already had an interest in web programming, from there wanted to make my passion into a job. I believe in learning through practice and seeking out these new experiences will make me a creative programmer.",
      mine: " In addition to web programming I am also able in terms of video making from videography to cinematography.",

      education:[
        {id:1, sekolah:"Min Beureunuen", tahun:2012},
        {id:2, sekolah:"MtsS jeumala amal", tahun:2015},
        {id:3, sekolah:"MaS jeumala amal", tahun:2018},
        {id:4, sekolah:"Politeknik Aceh", tahun:2018}
      ]
    }
  },
}

</script>

<style>
</style>

