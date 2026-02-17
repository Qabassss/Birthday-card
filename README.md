# Birthday-card
Make a digital birthday crad by using HTML and CSS.
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book</title>
    <link rel="maiscss" href="./styles.css"><style>@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600&display=swap");

        *,
        *::after,
        *::before {
          box-sizing: border-box;
          margin: 0;
          padding: 0;
        }
        
        body {
          font-family: "Poppins", sans-serif;
          min-height: 100vh;
          background-color: #212121;
          display: grid;
          place-items: center;
          color: white;
        }
        
        .cover {
          top: 0;
          position: absolute;
          width: 100%;
          height: 100%;
          background-image: url(./m.jpg);
          background-size: cover;
          transform-origin: 0;
          box-shadow: 1px 1px 12px #000;
          border-radius: 10px;
          display: flex;
          flex-direction: column;
          align-items: center;
          justify-content: space-around;
          transition: all 0.5s;
          cursor: pointer;
        }
        
        .book {
          position: relative;
          width: 260px;
          height: 350px;
          border-radius: 10px;
          background-color:white ;
          box-shadow: 1px 1px 12px #000000;
          transform: preserve-3d;
          perspective: 2000px;
          display: flex;
          align-items: center;
          justify-content: center;
          color: #000000;
          text-align: center;
        }
        
        .book:hover .cover {
          transition: all 0.5s;
          transform: rotatey(-80deg);
        }
        
        .cover > p {
          text-transform: uppercase;
          font-size: 13px;
          letter-spacing: 1px;
        }
        .cover > h2 > span {
          color: #f488d0;
          font-size: 28px;
          font-weight: bolder;
        }
        
        .content > p {
          margin-bottom: 30px;
          margin-left: 35px;
        }</style>
  </head>
  <body>
    <div class="book">
      <div class="cover">
        <p>open the card!!</p>
        <h2>Happy Birthdayyy<br><span>---</span></h2>
        <p>from: your sis🤍</p>
      </div>
      <div class="content" style="font-size: 17px;">
        <p>Happy Birthday to the gorgeous girl!!I wish you a year full of joy, success and everything you hope for and dream of.🤍🤍🤍</p>
        <div class="content" style="font-size: 19px;">
              <p></p>
        </div>

        <p>
            many love 🤍🤍!!
        </p>
      </div>
    </div>
  </body>
</html>
