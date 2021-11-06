<template>
<div style="text-align: left">
<div>
    <div>
        <header> Irvanda Ibrahim </header>
        <div id="section">
          <nav id="nav">
            <div id="nama">
                
                <p>{{nama}}</p>
            </div>
                <br>
                <br> 
                <img  class="img" src="https://i.pinimg.com/originals/e7/75/20/e77520d80ac4dac06e41b9aed672ea72.jpg" width="200px" height="250px">
            
            <h3>
                PROFILE <hr class="hr">
            </h3>
            <h4> NAME 
                <h5>Irvanda Ibrahim</h5>
            
            <br>
            DATE OH BIRTH
                <h5>03-Mei-2005</h5>
            <br>
            ADDRESS 
            <h5>Jl. Puncak Sari RT02/RW13, Tambak Aji, Ngaliyan, Semarang, Jawa Tengah </h5>
            <br>
            WEBSITE
            <h5>irvndibhm354@gmail.com</h5>
            <br>
            
            <br>
            <hr class="hr">
            <h3>AWARDS</h3>
            <br>
            -
            <br>
            -
            <br>
            <br>
            <hr class="hr">
            <h3>CONTACT</h3>☎️
            Home Number
            <h5>(+62)896 4634 4200</h5>
            <br>
            <hr class="hr">
            Social Media:
            <h5>IG: <a href="https://www.instagram.com/irvanda_ibra?r=nametag">irvanda_ibra</a></h5>
            <h5>FB: <a href="https://www.facebook.com/irvanda.ibrahim">Irvanda Ibrahim</a></h5>
            <br>
            <br>
            </h4>
          </nav>
          
          <div>
          <article class="article">
            <h2>
                GRAPICH ARTIST<hr>
            </h2>
            <div id="kotak">
            <div class="navv">
            </div>
                <h4>WORK EXPERIENCE</h4>
                <hr>
                <br>
                <br>
                Creative Rooms
                <br>
                <h6>Agustus 2018 - Mei 2019</h6>
                <br>
                <br>
                Creative Rooms
                <br>
                <h6>Juni 2017 - Desember 2017</h6>
                <br>
                <br>
                Creative Rooms
                <br>
                <h6>Desember 2016 - Maret 2017</h6>
            </div>
            <br>
            <br>
            <p id="p1">
                <div id="kotak">
                <h4>EDUCATION</h4><hr>
                <h5>MASTER DEGREE</h5>
                <h6>January 2015 - July 2015 </h6>
                <br>
                <h4>MASTER DEGREE</h4>
                <h6>Agustus 2015 - Desember 2015</h6>
                <br>
                <h4>MASTER DEGREE</h4>
                <h6>January 2016 - Mei 2016</h6>
                </div>
        
            <br>
            <br>
            <div id="kotak">
            <p>
                <h2>Experience</h2><hr>       
                <p id="p2">Berhubung aya masih muda dan berstatus pelajar masih mencari pengalaman,
                Berikut sedikit pengalaman hidup saya :</p>
                <ul id="p1">
                    <li>Saya waktu kecil termasuk anak yang hyper aktih saking aktifnya
                     saya pernah kepleset hingga mendapat luka di bagian gigi menjadikan gigi sya kroak :(</li><br>
                     <li>Ketika saya kelas 2 SMP saya pernah mengikuti lomba pencak silat dan berhasil
                         juara 2 dan meraih medali perak antar Daerah</li><br>
                    <li>Jalan-jalan ke gunung yang besar besar sambil mengagumi 
                        ciptaan Allah Swt. Itulah penglaman yang menyenangkan</li><br>
                </ul> 
            </div>
            
          </article>
          </div>
        </div>
    </div>
</div>
</div>
</template>
<script>
export default { 
  name: 'CvSatu', 
  computed: {
      listCv2() {
          return this.$store.state.listCv2
      }
  }
}; 
</script>
<style>

header {
  background-color: rgb(31, 39, 109);
  padding: 10px;
  text-align: center;
  font-size: 35px;
  color: white;
  
}

.tbody {
    background-color: #ccc;
  }
  
  .hr {
      border: 1px dashed black;
  }
  
  * {
      box-sizing: border-box;
    }
    
    .body {
        border: none;
    }
    .img {
        border-radius: 200px;
    }
    
    #section {
      display: -webkit-flex;
      display: flex;
      background-color: #ccc;
    }
    
    #nav {
        border: 1px solid rgb(204, 204, 204);
      -webkit-flex: 1;
      -ms-flex: 1;
      flex: 1;
      background: white;
      padding: 40px;
      text-align: right;
    }

    #navv {
      background: none;
      margin: 10px;
      padding: 100px;
      
    }
  
    #nama {
        font-family: Verdana;
        font-size: 25px;
        color: black;
        opacity: 80%;
    }
  
    h2 {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      opacity: 75%;
    }
  
    .article {
      -webkit-flex: 3;
      -ms-flex: 3;
      flex: 3;
      color: none;
      padding:40px;
    }

    .articlee {
      -webkit-flex: 3;
      -ms-flex: 3;
      flex: 3;
      color: none;
      padding:40px;
    }
    
    #p1 {
      font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
      opacity: 85%;
    }
    #p2{
      font-family: Georgia, 'Times New Roman', Times, serif;
      opacity: 85%;
    }
  
    @media (max-width: 600px) {
      section {
        -webkit-flex-direction: column;
        flex-direction: column;
      }
    }
  
    h3 {
      opacity: 95%;
    }
    h5 {
      opacity: 90%;
    }
    #kotak
    {
        border-block: 1px solid rgb(255, 255, 255);
        background-color: #ccc;
    }
    .hrr{
        border: 2px dashed solid black;
    }
</style>