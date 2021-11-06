<template>
<div style="text-align: left">
<div>
    <div>
        <div id="section">
          <nav>
            <div id="nama">
                <p>{{nama}}Irvanda Ibrahim</p>
            </div>
                <br>
                <br> 
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTxClgJdr5CCHnABooq3rRn6pdSqSrcSgw_gg&usqp=CAU" height="155" width="245" >
            
            <h3>
                Contact <hr>
            </h3>
            <h5 id="o2">Address:
                <p>{{ alamat }}Jl. Puncal Sari RT02/RW13, Tambak Aji, Ngaliyan, Semarang, Jawa Tengah</p>
            
            <br>
            Phone:
                <p>{{phone}} (+62) 8964 6344 200</p>
            <br>
            Email:
                <p><a href="">{{email}} irvndibhm354@gmail.com</a></p>
            <br>
            Social Media:
            <p>IG: <a href="https://www.instagram.com/irvanda_ibra?r=nametag">irvanda_ibra</a></p>
            <p>FB: <a href="https://www.facebook.com/irvanda.ibrahim">Irvanda Ibrahim</a></p>
            <br>
            <br>

            <h3>Languages</h3><hr>
            <br>
            Indonesia
            <br>
            Jawa
            <br>
            <br>

            <h3>Hobbies</h3><hr>
            
            <ul>
                <li>{{hobi}}</li>
                <li>{{ hobi2 }}</li>
                <li>{{hobi3}}</li>
                <li></li>
              </ul>  
            </h5>
          </nav>
          
          <article>
            <h2>
                Inilah Aku<hr>
            </h2>
            <p id="p1">
                {{ringkasan}} Hai, Nama saya Irvanda Ibrahim biasa di panggil Baim. Club kebanggaan saya adalah Manchester United yang memliki,julukan The Red Devils. Dan Psis Semarang Club Kota tercinta ku. Saya anak ke 2 dari 4 bersaudara, kakak adek saya perempuan semua. Umur saya masih muda 16thn kelahiran 2005. Status saya saat ini  pelajar, bersekolah di SMK Bina Nusantara Semarang. Kesibukan Saya saat ini adalah mengikuti Botcamp di sekolah.

            </p>
            <br>
            <br>
            <p id="p1">
                <h2>Skill Highlights</h2><hr>
                <ul id="p1">
                    <li>{{skill}}</li>
                    <li>{{skill2}}</li>
                    <li>{{skill3}}</li>
                    <li>{{skill4}}</li>
                    <li>{{skill5}}</li>
                </ul>
        
            <br>
            <br>
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
            
            <br>
            <br>

            <p>
                <h2>Education</h2><hr>
                <p>-</p>
            
            <br>
            <br>
            <p>
                <h2>Certifications</h2><hr>
                <p id="p1">{{sertifikat}}</p>
            
          </article>
        </div>
    </div>
</div>
</div>
</template>
<script>
export default { 
  name: 'CvSatu', 
  computed: {
      listCv() {
          return this.$store.state.listCv
      }
  }
}; 
</script>
<style>
.tbody {
    background-color: gray;
  }
  
  
  
  * {
      box-sizing: border-box;
    }
    
    body {
      font-family: Arial, Helvetica, sans-serif;
      margin: 150px;
    }
    
    #section {
      display: -webkit-flex;
      display: flex;
      background-color: #ccc;
    }
    
    nav {
      -webkit-flex: 1;
      -ms-flex: 1;
      flex: 1;
      background: #ccc;
      padding: 40px;
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
  
    article {
      -webkit-flex: 3;
      -ms-flex: 3;
      flex: 3;
      background-color: #f1f1f1;
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
</style>