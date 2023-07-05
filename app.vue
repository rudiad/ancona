<style>
    html {
        height: 100%;
    }
    body {
        height: 100%;
        margin: 0;
        font: 14px/25px 'Montserrat', sans-serif;
        color: #363636;
        flex-direction: column;
        display: flex;
        background: url('./public/assets/background-class.png') bottom right no-repeat;
        /* background: url('./public/assets/background-class-rainbow.png') bottom 60px right no-repeat; */
        /* background: url('./public/assets/background-class-rainbow-alt.png') bottom 60px right no-repeat; */
    }

    .header, .footer {
        margin: 0;
        padding: 20px;
        display: flex;
        align-items: center;
    }

    .header {
        background-color: #ddd;
        flex-direction: row;
        justify-content: space-between;
        border-bottom: solid 10px #00776a;
        filter: drop-shadow(0px 0px 5px #777);
    }

    .logo-group, .contact-group {
        display: flex;
        align-items: center;
    }

    .logo {
        height: 55px;
    }
    
    .title {
        font: 30px 'Montserrat', sans-serif;
        font-weight: normal;
        color: #3d3d3d;
        vertical-align: middle;
        margin-left: 10px;
    }

    .contact {
        font: 15px 'Montserrat', sans-serif;
        font-weight: bold;
        color: #3d3d3d;
        vertical-align: middle;
        margin: 0 20px 0 5px;
    }

    .contact-icon {
        width: 20px;
    }

    .navigation {
        margin: 20px 60px 0px;
        align-items: stretch;
        align-content: flex-start;
        display: flex;
        justify-content: center;
        text-align: center;
    }

    a {
        color: #3d3d3d;
        text-decoration: none;
    }

    a:hover {
        color: #bf372f;
        text-decoration: underline;
    }

    .navigation a, .footer-links a {
        width: 100%;
        max-width: 100px;
    }

    .content {
        margin: 0px 60px;
        flex: 1 0 auto;
    }

    .container {
        align-items: stretch;
        align-content: flex-start;
        display: flex;
        justify-content: center;
    }

    .mission-statement {
        color: #E8E8E8;
        font-size: 16px;
        font-family: "Walter Turncoat",cursive;
        max-width: 60%;
        min-height: auto;
        margin: 30px auto 0;
        background-color: #2f2f2f;
        padding: 20px 30px;
        border: #D2A368 solid 5px;
    }

    .mission-span {
        color: #00776a;
        font-weight: bold;
    }

    .col {
        width: 100%;
        max-width: 400px;
        margin: 40px;
        background-color: rgba(255, 255, 255, 0.5);
        border-radius: 20px;
    }

    .gallery-still {
        display: block;
    }
    
    .footer{
        background-color: #ddd;
        flex-direction: row;
        justify-content: space-between;
        filter: drop-shadow(0px -5px 5px #777);
        flex-shrink: 0;
    }

    .copyright {
        font: 12px 'Montserrat', sans-serif;
        font-style:italic;
        color: #363636;
    }

    .footer-links {
        align-items: stretch;
        align-content: flex-start;
        display: flex;
        justify-content: center;
        text-align: center;
    }

    .footer-links a {
        display: flex;
        justify-content: center;
        min-width: 150px;
        color: #363636;
        align-items: center;
    }

    .footer-links a:hover {
        color: #bf372f;
    }

    .footer-links img {
        width: 20px;
        margin: 0 5px 0;
        height: 20px;
    }

</style>

<link href="http://fonts.googleapis.com/css?family=Montserrat" rel="stylesheet" type="text/css" />
<link href="https://fonts.googleapis.com/css?family=Walter+Turncoat" rel="stylesheet" type="text/css" />

<template>
    
  <div class="header">
      <div class="logo-group">
          <!-- <img class="logo" src="./public/assets/ancona-logo-image-trace.png" /> -->
          <!-- <img class="logo" src="./public/assets/ancona-logo-image-trace-ver2.png" /> -->
          <!-- <img class="logo" src="./public/assets/ancona-logo-image-trace-ver3.png" /> -->
          <!-- <img class="logo" src="./public/assets/ancona-logo-image-trace-ver4.png" /> -->
          <!-- <img class="logo" src="./public/assets/ancona-logo-image-trace-ver5.png" /> -->
          <!-- <img class="logo" src="./public/assets/ancona-logo-image-trace-ver3.png" /> -->
          <img class="logo" src="./public/assets/ancona-logo-image-trace-ver8.png" />

          <div class="title">Ancona Montesorri School</div>
      </div>
      <div class="contact-group">
          <img class="contact-icon" src="./public/assets/contact-icon.png" />
          <div class="contact">Contact Staff</div>
      </div>
  </div>

  <div class="navigation">
      <a href="">Home</a> <span class="divider">|</span> <a href="">About</a> <span class="divider">|</span> <a href="">Classes</a> <span class="divider">|</span> <a href="">Staff</a> <span class="divider">|</span> <a href="">Enrollment</a> <span class="divider">|</span> <a href="">Information</a>
  </div>

  <div class="mission-statement">
      <span class="mission-span">Ancona Montessori School</span> is proud to invest in YOUR child. We provide your children with many life skills and a solid foundation of educational principals. Ancona encourages children to be independent, healthy, and confident. Come visit us to learn more about how Ancona Schools can provide your child with the very best in early childhood development services.
  </div>

  <div class="content">        

      <div class="container">
          <div class="col col-1">
              <h2>About us</h2>

              Montessori School in Drexel Hill and Wynnewood, Pennsylvania
              <a href="">READ MORE</a>

              <h2>Hours Of Operation:</h2>

              Monday-Friday: 7:30AM-6:00PM
          </div>

          <div class="col col-2">
              <h2>Address</h2>

              Drexel Hill: 5290 Townshipline Road, 19026

              Wynnewood: 630 Clothier Road, 19096

              484-431-6469
              <a href="">CONTACT</a>
          </div>
          
          <div class="col col-3">
              <h2>Photo Gallery</h2>
              <img class="gallery-still" src="./public/assets/gallery-still.jpg" />
              <a href="">SEE GALLERY</a>
          </div>
      </div>

  </div>

  <div class="footer">
      <div class="footer-links">
          <a href="https://mybrightwheel.com"><img src="./public/assets/custom_avatar-1626993963.png" />Brightwheel</a>
          <span class="divider">|</span>
          <a href="">Directions</a>
          <span class="divider">|</span>
          <a href="">FAQs</a>
      </div>
      <div class="copyright">Copyright © 2023 Ancona Montesorri School. All Rights Reserved.</div>
  </div>
    
</template>
