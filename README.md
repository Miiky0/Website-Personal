<html lang="en">  
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link href="https://fonts.googleapis.com/css2?family=Ubuntu:wght@400;500;700&display=swap" rel="stylesheet" />
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet" />
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons+Sharp" rel="stylesheet" />
    <script src="https://cdn.jsdelivr.net/npm/sweetalert2@11.4.4/dist/sweetalert2.all.min.js"></script>
    <title>Happy Birth Day My Wife</title>
    <style>html { scroll-behavior: smooth; } * { padding: 0; margin: 0; font-family: "Ubuntu"; color: rgba(11, 11, 11, 0.952); } body  .open { background-image: url("https://live.staticflickr.com/65535/53023756951_d4f328d03f_m.jpg"); height: 100vh; width: 100vw; position: fixed; top: 0; display: flex; flex-direction: column; align-items: center; align-content: center; justify-content: center; z-index: 1; transition: 0.5s all ease; } .open h2 { /* margin: 0 30px; */ margin-bottom: 20px; color: rgb(0, 0, 0); text-align: center; max-width: 600px; } .open .card { background-image: url("https://live.staticflickr.com/65535/53026038409_f3f355f153_m.jpg"); padding: 30px; border-radius: 10px; box-shadow: 10px 10px 30px rgba(0, 0, 0, 0.13); text-align: center; } .open .card h3 { margin-top: 20px; } .open .card img { height: 100px; } .atas { height: 100vh; display: flex; flex-direction: column; justify-content: center; align-items: center; } .atas img { height: 200px; margin-bottom: 50px; padding: 20px 30px; background: white; border-radius: 20px; box-shadow: 10px 10px 30px rgba(0, 0, 0, 0.123); } .atas h2 { font-size: 1.5em; padding: 20px 30px; background: white; border-radius: 20px; box-shadow: 10px 10px 30px rgba(0, 0, 0, 0.123); } p { display: block; text-align: center; color: rgb(56, 56, 56); background: white; font-weight: bold; font-size: 1.5em; padding: 50px 30px; margin: 40px 20px; border-radius: 20px; box-shadow: 10px 10px 30px rgba(0, 0, 0, 0.123); } p.wm { width: fit-content; margin-top: 100px; margin-bottom: 0; padding: 10px 20px; border-radius: 10px 10px 0 0; font-weight: 500; font-size: .9em; color: red; } p.wm a { color: red; text-decoration: none; } .material-icons-sharp { color: red; font-size: 30px; transform: translateY(5px); animation:kenyal2s ease infinite; cursor: pointer; } @keyframes kenyal { 0% { transform: scale(1) translateY(5px); } 50% { transform: scale(1.2) translateY(5px); } 100% { transform: scale(1) translateY(5px); } }</style>
  </head>
  <body class="body">
    <div class="open">
      <div class="card">
        <h2>Ada pesan buat kesayanganku🫶 </h2>
          <img onclick="mulai()" src="https://dekatutorial.github.io/spesial_mail.png" alt="" srcset="" />
        <h3>Tekan untuk membuka</h3>
      </div>
    </div>
    <div class="atas" id="atas">
      <img onclick="mulai()" src="https://dekatutorial.github.io/spesial_stikerUltah.png" alt="" />
      <h4>Scroll kebawah Maaa🫶</h4>
    </div>

    <p data-aos="zoom-in">Hallo Sayang  Selamat Ulang Tahun Yang Ke-16🥳❤️ </p>
    <p data-aos="zoom-in">Papaa Berharap Di Hari Spesial Ini</p>
    <p data-aos="zoom-in">Semoga Mamaaa Sehat selalu,Tercapai Cita-Cita Mamaa,Di Berikan Kemudahan Dalam Sehari-hari Mamaa❤️ </p>
    <p data-aos="zoom-in">Banyak Yang Berubah Di Tahun Ini, Tapi Mamaa Tetap Menjadi Yang Paling Berharga Untuk Papaa🫶  </p>
    <p data-aos="zoom-in">Selamat Ulang Tahun Mamaa😘 </p>
    
    <p data-aos="zoom-in">Pencet love nya 
      <i onclick="tanya()" class="material-icons-sharp"> favorite </i></p>

    <script>

      var musik = "";

    </script>
    <script> AOS.init({ once: true, }); </script> <script> if(musik == "") { musik = "https://link.happybirthdaysong.co.in/birthdaysong.in/new/Romantic-Birthday.mp3"; } var audio = new Audio(musik); audio.loop = true; audio.autoplay = true; function mulai() { audio.play(); document.querySelector(".open").style = "opacity: 0;"; document.querySelector(".body").style = "overflow-y: scroll;"; setTimeout(function () { document.querySelector(".open").style.display = "none"; }, 1000); } function wa(isi) { window.open("https://api.whatsapp.com/send/?phone=%2B6285244897227&text&type=phone_number&app_absent=0" + isi); } async function tanya() { var { value: kado } = await swal.fire({ title: "Di hari spesial ini Mamaa pengennya apa?", input: "text", showCancelButton: false, }); if (kado) { await swal.fire("Kirim Jawabannya Di WA Papaa Maaa🫶"); wa(kado); } else { await swal.fire("Jangan Dikosongin Lah Sayang🥹"); tanya(); } } </script> 
  </body>
</html>
