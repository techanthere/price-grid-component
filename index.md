<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- displays site properly based on user's device -->

  <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Karla:wght@400;700&display=swap" rel="stylesheet"> 
  <title>Frontend Mentor | Single Price Grid Component</title>

  <!-- Feel free to remove these styles or customise in your own stylesheet 👍 -->
  <style>
    /* ----------------- custom style code ------------- */
      *{
        margin: 0;
        padding: 0;
        box-sizing: border-box;
      }
      body{
          font-family: 'Karla', sans-serif;
          font-size: 16px;
      }
      .container, .grid, .components-all, .component{
        border: 1px dotted blue;
      }
      .container{
        width: 50vw;
        position: relative;
        margin: 50px auto;
        display: flex;
        flex-direction: column;
        box-shadow: 0px 0px 2px hsl(204, 43%, 93%),0px 0px 5px hsl(204, 43%, 93%),0px 0px 10px hsl(204, 43%, 93%);
      }
      .grid{
        padding: 30px 50px;
      }
      .grid > p{
        color: hsl(237, 100%, 88%);
        line-height: 1.5em;
      }
      .grid > p, .info-component{
        font-size: 16px;
      }
      h1{
        color:  hsl(179, 62%, 43%);
        font-size: x-large;
        line-height: 2.5em;  
      }
      h2{
        color: hsl(71, 73%, 54%);
        font-size: larger;
        line-height: 2em;
      }
      h4{
      }
      .components-all{
        display: flex;
        background-color: hsl(179, 62%, 43%);
      }
      .component{
        padding: 30px 50px;
        color: #fff;
      }

      .price-component span{
        line-height: 2;
      }

      .price-component #price{
        font-size: 2em;
        font-weight: bold;
      }

      .price-component #time-unit{
        font-size: 0.9em;
        color: hsl(237, 100%, 88%);    
      }

      .price-component .signup-btn{
        display: block;
        margin-top: 20px;
        text-align: center;
        padding: 10px;
        text-decoration: none;
        color: white;
        background-color: hsl(71, 73%, 54%);
        font-weight: bold;
        border-radius: 5px;
      }
      .info-component ul{
        margin-top: 10px;
      }

      .info-component ul li{
        color: hsl(204, 43%, 93%);
        list-style-type: none;
        font-size: 0.9em;
        line-height: 1.3;
      }


    /* --------- custom code ends --------*/

    .attribution { font-size: 11px; text-align: center; }
    .attribution a { color: hsl(228, 45%, 44%); }
  </style>
</head>
<body>
  <div class="container">
    <div class="grid">
    
    <h1>Join our community</h1>

    <h2>30-day, hassle-free money back guarantee</h2>

   <p> Gain access to our full library of tutorials along with expert code reviews. 
    Perfect for any developers who are serious about honing their skills.</p>
    </div>
    <div class="components-all">
      <div class="component price-component">
        <h3>Monthly Subscription</h3>

        <span id="price">&dollar;29</span><span id="time-unit"> per month</span>

        </p>Full access for less than &dollar;1 a day</p>

        <a href="#" class="signup-btn"> Sign Up</a>
        
      </div>
      <div class="component info-component">

      <h4>Why Us</h4>
      <ul>
          <li>Tutorials by industry experts</li>
          <li>Peer &amp; expert code review</li>
          <li>Coding exercises</li>
          <li>Access to our GitHub repos</li>
          <li>Community forum</li>
          <li>Flashcard decks</li>
          <li>New videos every week</li>
      </ul>
        
      </div>
    </div>  

  
  <footer>
    <p class="attribution">
      Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
      Coded by <a href="#">Your Name Here</a>.
    </p>
  </footer>
</body>
</html>