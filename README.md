<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      margin: 0;
      padding: 0;
    }

    .border {
      width: 100%;
      height: 100%;
      background-color: #176045;
      overflow-y: hidden;
    }

    .hintergrund {
      width: 100%;
      height: 100%;
      background-color: #0f402d;
    }

    .foto {
      width: 100%;
      height: 400px;
      margin-top: 1%;
      border-radius: 20px 20px 0px 0px;
      background-size: cover;
      min-width: 100%;
      overflow-x: hidden;
      white-space: nowrap;
      box-shadow: 0px 2px 0px 1px #33926a;
    }

    .foto:hover {
      box-shadow: 0px 0px 10px 2px #fff;
    }

    .foto_1,
    .foto_2,
    .foto_3,
    .foto_4,
    .foto_5 {
      width: 414px;
      height: 400px;
      background-size: cover;
      float: left;
      margin-top: 1px;
    }

    .name {
      width: 100%;
      height: 30px;
      color: #fff;
      font-family: Quicksand;
      text-align: center;
      margin-top: 13px;
    }

    .name:hover {
      color: rgb(232, 75, 200);
    }

    .work {
      width: 100%;
      height: 30px;
      font-family: Quicksand;
      color: rgb(232, 75, 200);
      text-align: center;
    }

    .work:hover {
      color: #fff;
    }

    .media {
      width: 100%;
      height: 62px;
      text-align: center;
      margin-top: 0%;
    }

    .social-icon {
      width: 70px;
      height: 70px;
      margin-left: 2%;
      border-radius: 50%;
      background-size: cover;
    }

    .social-icon:hover {
      box-shadow: 0px 0px 10px 2px rgb(232, 75, 200);
      transition: transform 2s;
      transform: rotate(360deg);
    }
  </style>
</head>

<body>

  <div class="border">

    <div class="hintergrund">

      <div class="foto">
        <img class="foto_1" src="../assets/imgs/so_4.jpg">
        <img class="foto_2" src="../assets/imgs/so.jpg">
        <img class="foto_3" src="../assets/imgs/so_2.jpg">
        <img class="foto_4" src="../assets/imgs/so_5.jpg">
        <video class="foto_5" controls><source src="../assets/vedio/Video_new.mov" type="Video/mp4"></video>
      </div>

      <div style="width:100%;height:160px;">

        <div style="width: 100%;height:80px;">
          <h1 class="name">Sophie 🤍</h1>
          <h3 class="work">bvdk - Sportler/in 🏋 Deutschland</h3>
        </div>

        <div class="media">
          <a href="https://instagram.com/sophiesch0?igshid=OGQ5ZDc2ODk2ZA==" target="_blank">
            <img class="social-icon instagram" src="../assets/imgs/instagram_logo.png" alt="Instagram">
          </a>

          <a href="https://www.tiktok.com/@soophiesch0?_t=8hHmpgQLFpI&_r=1" target="_blank">
            <img class="social-icon tiktok" src="../assets/imgs/tiktok_logo.png" alt="TikTok">
          </a>

          <a href="https://calendly.com/sophie2005schmidtke/30min?month=2023-12" target="_blank">
            <img class="social-icon YouTube" src="../assets/imgs/zoom.png" alt="YouTube">
          </a>

          <a href="YOUR_YOUTUBE_CHANNEL_URL" target="_blank">
            <img class="social-icon twitter" src="../assets/imgs/twitter.png" alt="Twitter">
          </a>

          <a href="https://t.snapchat.com/IufrHlUm" target="_blank">
            <img class="social-icon Snapchat" src="../assets/imgs/snap-png.png" alt="Snapchat">
          </a>
        </div>
      </div>
    </div>

  </div>

</body>

</html>
