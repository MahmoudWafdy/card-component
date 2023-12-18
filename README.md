<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- displays site properly based on user's device -->

    <link
      rel="icon"
      type="image/png"
      sizes="32x32"
      href="./images/favicon-32x32.png"
    />
    <link rel="stylesheet" href="style.css" />
    <style>
      * {
          padding: 0;
          margin: 0;
          font-family: sans-serif;
        }
        body {
          background-color: #0d1a2d;
        }
        .post {
          width: 25%;
          height: auto;
          background-color: #14273e;
          box-shadow:  0px 3px 8px #050c15,0px 3px 8px #050c15;
          margin: 50px auto;
          border-radius: 10px;
          -webkit-border-radius: 10px;
          -moz-border-radius: 10px;
          -ms-border-radius: 10px;
          -o-border-radius: 10px;
          padding-bottom: 20px;
        }
        .img-post {
          width: 90%;
          height: auto;
          margin: 15px 5%;
          border-radius: 10px;
          -webkit-border-radius: 10px;
          -moz-border-radius: 10px;
          -ms-border-radius: 10px;
          -o-border-radius: 10px;
        }
        .post h3:first-of-type {
          font-size: 18px;
          margin: 5px 0 0 15px;
          color: white;
        }
        .post p:first-of-type {
          font-size: 18px;
          margin: 15px;
          color: #879cb8;
        }
        .post ul {
          list-style: none;
          margin-left: 15px;
        }
        .post ul:first-of-type li {
            display: inline;
        }
        .post ul:first-of-type li {
          font-size: 12px;
        }
        .post ul:first-of-type li:first-child {
          color: #00fff8;
        }
        .post ul:first-of-type li:nth-child(2) {
            margin-left: 20%;
            color: #8bacd9;
        }
        .post ul:first-of-type li:last-child {
            color: #8bacd9;
          }
        .post img[alt="icon-ethereum"] {
          width: 10px;
          margin-right: 4px;
          transform: translateY(3px);
          -webkit-transform: translateY(3px);
          -moz-transform: translateY(3px);
          -ms-transform: translateY(3px);
          -o-transform: translateY(3px);
        }
        .post img[alt="icon-clock"] {
          width: 14px;
          margin-right: 4px;
          transform: translateY(3px);
          -webkit-transform: translateY(3px);
          -moz-transform: translateY(3px);
          -ms-transform: translateY(3px);
          -o-transform: translateY(3px);
        }
        .seperator {
          width: 88%;
          height: 0.1px;
          /*box-shadow: 2px 2px 5px 3px #050c15;*/
          margin: 15px auto 10px;
          background-color: #879cb8;
        }
        .post img[alt="author"] {
            width:25px;
            margin-right: 10px;
            transform: translateY(6px);
            -webkit-transform: translateY(6px);
            -moz-transform: translateY(6px);
            -ms-transform: translateY(6px);
            -o-transform: translateY(6px);
        }
        .post ul:first-of-type li:last-child span{
            color: white;
        }
        @media(max-width : 778px){
          .post {
            width: 40%;
            margin: 50px auto;
          }
          .post h3:first-of-type {
            font-size: 13px;
          }
          .post p:first-of-type {
            font-size: 12px;
          }
          .post ul:first-of-type li {
            font-size: 10px;
          }
          .seperator {
            width: 95%;
            height: 0.1px;
            /*box-shadow: 2px 2px 5px 3px #050c15;*/
            margin: 15px auto 10px;
            
          }
          .post img[alt="author"] {
              width:25px;
              margin-right: 10px;
              transform: translateY(6px);
              -webkit-transform: translateY(6px);
              -moz-transform: translateY(6px);
              -ms-transform: translateY(6px);
              -o-transform: translateY(6px);
          }
          .post ul:first-of-type li:last-child span{
              color: white;
          }
          
        
        }
        
        @media(max-width : 375px){
          .post {
            width: 70%;
            margin: 50px auto;
          }
          .post h3:first-of-type {
            font-size: 13px;
          }
          .post p:first-of-type {
            font-size: 12px;
          }
          .post ul:first-of-type li {
            font-size: 10px;
          }
          .seperator {
            width: 95%;
            height: 0.1px;
            /*box-shadow: 2px 2px 5px 3px #050c15;*/
            margin: 15px auto 10px;
        
          }
          .post img[alt="author"] {
              width:25px;
              margin-right: 10px;
              transform: translateY(6px);
              -webkit-transform: translateY(6px);
              -moz-transform: translateY(6px);
              -ms-transform: translateY(6px);
              -o-transform: translateY(6px);
          }
          .post ul:first-of-type li:last-child span{
              color: white;
          }
          
          
        
        }
        /*
        
        .post span:first-of-type {
          font-size: 13px;
          transform: translateY(-15px);
          -webkit-transform: translateY(-15px);
          -moz-transform: translateY(-15px);
          -ms-transform: translateY(-15px);
          -o-transform: translateY(-15px);
        }
        

    </style>
    <title>Frontend Mentor | NFT preview card component</title>
  </head>
  <body>
    <div class="post">
      <img
        class="img-post"
        src="images/image-equilibrium.jpg"
        alt="image post"
      />
      <h3>Equilibrium #3429</h3>
      <p>Our equilibrium collection promotes balance and callm.</p>
      <ul>
        <li>
          <img src="images/icon-ethereum.svg" alt="icon-ethereum" />0.041ETH
        </li>
        <li><img src="images/icon-clock.svg" alt="icon-clock" />3 day left</li>
        <div class="seperator"></div>
        <li>
          <img src="images/image-avatar.png" alt="author" />
          Creation of<span> Jules Wyvern</span>
        </li>
      </ul>
    </div>
  </body>
</html>
