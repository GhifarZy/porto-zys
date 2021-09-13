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
                                    " data-aos-duration="600" data-aos="fade-down" data-aos-delay="0">Experience</h2>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
             <br>
           <div class="col-lg-12">
                        <div class=" px-xl-0">
                            <div class="row justify-content-center">
                                <div class="col-xl-8 col-lg-12">
                                    <br>
                                   <div class="row">
                                       <div v-for="item in experience" :key="item.id" class="col-lg-12">
                                                <div style="
                                                border-bottom: 6px double #404040;
                                                padding:20px;
                                                margin-bottom:12px;
                                                display: inline-block;
                                                border-radius: 12px;">
                                               <p class="small" style="
                                                color:white;
                                                font-family:arial;
                                                font-size: 20px;
                                                font-weight:bold;
                                                text-transform:capitalize;
                                                text-align:start;
                                                " data-aos-duration="600" data-aos="fade-down" data-aos-delay="0">{{ item.tahun }}</p>
                                                <p style=" color:white;
                                                font-family: 'Secular One', sans-serif;
                                                text-transform:uppercase;
                                                font-size: 18px;
                                                text-align:justify;
                                                ">{{ item.tentang }}</p>
                                                <p style=" color:white;
                                                font-family:arial;
                                                font-size: 18px;
                                                text-align:justify;
                                                ">{{ item.deskripsi }}</p>
                                                <p class="small" style="
                                                color:white;
                                                font-family:arial;
                                                font-size: 20px;
                                                text-transform:capitalize;
                                                text-align:end;
                                                font-weight:bold;
                                                " data-aos-duration="600" data-aos="fade-down" data-aos-delay="0">{{ item.pekerjaan }}</p>
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
  name: 'Experience',
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
      ],
      experience:[
          {id:1, tahun:2021, tentang:"sistem e-procurement al-hilal sigli", deskripsi:"Membangun sistem informasi pengadaan barang secara elektronik yaitu sistem e-procurement untuk Al - Hilal Sigli", pekerjaan:"Web Developer"},
           {id:2, tahun:2021, tentang:"sistem e-procurement kereta api indonesia", deskripsi:"Menjadi salah satu Quality Assurance dalam project E-proc di Promise PT. MItra MANDIRI INFORMATIKA Jakarta Selatan", pekerjaan:"Quality Assurance"},
           {id:3, tahun:2021, tentang:"sistem inventaris products mcs lighting", deskripsi:"membangun sebuah sistem informasi inventaris product philips untuk PT. MAKMUR CAHAYA SEMESTA yang merupakan prosesional distributor philips lighting", pekerjaan:"Web Developer"}
      ]
    }
  },
}

</script>

<style>
</style>

