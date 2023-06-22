# muneerobot.github.io
<!DOCTYPE html>
<html>
<head>
    <title>Your Webpage Title</title>
    <style>
        @import url(https://fonts.googleapis.com/css?family=Droid+Sans);

        * {
          position: relative;
          color: #000;
          font-size: 14px;
          font-family: 'Droid Sans', sans-serif;
        }

        a,
        a:link,
        a:hover,
        a:visited {
          color: #000;
          text-decoration: none;
        }

        a:hover {
          color: red;
        }

        #POSITION-RELATIVE,
        #position-relative,
        * {
          position: relative;
        }

        #FLOAT-LEFT,
        .float-left {
          float: left;
        }

        #CLEAR,
        .clear {
          clear: both;
        }

        #CENTER,
        .center {
          text-align: center;
        }

        #BOLD,
        .bold {
          font-weight: bold;
        }

        #CARD,
        .card,
        .card-helper,
        .card:before,
        .card:after {

          width: 320px;
          height: 160px;

          box-shadow: -4px 4px 24px rgba(0, 0, 0, 0.5);

          padding: 20px;
          border-radius: 8px;

          background: #fff;
        }

        .card {
          transform: rotate(-40deg) rotateX(20deg) rotateY(30deg);
          -webkit-transform: rotate(-40deg) rotateX(20deg) rotateY(30deg);
          margin: 80px auto;
        }

        .card-helper {
          position: absolute;
          top: 0;
          left: 0;
        }

        .card:before,
        .card:after {
          content: "";
          position: absolute;
          left: 0;

          background-image: url("https://bit.ly/14bsqFY");  
          background-repeat: no-repeat;
          background-position: 20px 20px;
          background-size: 130px;
        }

        .card:before {
          transform: rotate(8deg);
          -webkit-transform: rotate(8deg);
          top: -20px;
          z-index: -1;
        }

        .card:after {
          transform: rotate(16deg);
          -webkit-transform: rotate(16deg);
          top: -40px;
          z-index: -2;
        }

        .image {
          margin: 0 20px 15px 0;
        }

        .image img {
          width: 130px;
          height: 130px;
          border-radius: 4px;
        }

        .title {
          font-size: 32px;
        }

        .card:hover {
          transform: none;
          -webkit-transform: none;
        }

        .card:hover:before,
        .card:hover:after {
          top: 0;
        }

        .card:hover:before {
          transform: rotate(-32deg) rotateX(20deg) rotateY(30deg);
          -webkit-transform: rotate(-24deg) rotateX(20deg) rotateY(30deg);

        }

        .card:hover:after {
          transform: rotate(-32deg) rotateX(20deg) rotateY(30deg);
          -webkit-transform: rotate(-32deg) rotateX(20deg) rotateY(30deg);
        }

        .card,
        .card:before,
        .card:after,
        .card:hover,
        .card:hover:before,
        .card:hover:after {
          transition: all 0.8s ease-in-out;
          -webkit-transition: all 0.8s ease-in-out;
        }

        .card,
        .card:before,
        .card:after {
          transition-delay: 0.8s;
          -webkit-transition-delay: 0.8s;
        }
    </style>
</head>
<body>
    <div class="main card">
        <div class="main-helper card-helper"></div>
        <div class="image float-left">
            <img src="https://i.postimg.cc/zXmBV66L/Food-QR-Code-Business-Card-White-Black-Simple-Modern-Style.png">
        </div>
        <div class="content float-left">
            <div class="title bold">Muneer</div>
            <div class="subtitle">Marketing Head</div>
            <div class="subtitle bold"><br>KAR Business Services</div>
            <div class="subtitle">Hor al Anz, Dubai</div>
        </div>
        <div class="footer clear center">
            kartypingcentre@gmail.com, kartyping.com
        </div>
    </div>
</body>
</html>
