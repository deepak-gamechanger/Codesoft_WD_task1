# Codesoft_WD_task1
Landing_page
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Porsche Middle East Deepak_home</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css"
    integrity="sha512-z3gLpd7yknf1YoNbCzqRKc4qyor8gaKU1qmn+CShxbuBusANI9QpRohGBreCFkKxLhei6S9CQXFEbbKuqLg0DA=="
    crossorigin="anonymous" referrerpolicy="no-referrer" />
  <link rel="stylesheet" href="main.css">
  <link rel="icon" type="image/x-icon" href="favicon.ico">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>

</head>

<body>
  <header>
    <div class="navbar">
      <div class="icon-box">
        <div class="menu-icon">
          <i class="fa-solid fa-bars"></i> Menu
        </div>
        <div class="logo-icon">
        </div>
      </div>
    </div>
  </header>
  <div id="myCarousel" class="carousel slide" data-ride="carousel">
    <!-- Indicators -->
    <ol class="carousel-indicators">
      <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
      <li data-target="#myCarousel" data-slide-to="1"></li>
      <li data-target="#myCarousel" data-slide-to="2"></li>
      <li data-target="#myCarousel" data-slide-to="3"></li>
    </ol>

    <!-- Wrapper for slides -->
    <div class="carousel-inner">
      <div class="item active">
        <img src="slider1.jpg" alt="porsche">
      </div>

      <div class="item">
        <img src="slider2.jpg" alt="porsche">
      </div>

      <div class="item">
        <img src="slider3.jpg" alt="porsche">
      </div>
      <div class="item">
        <img src="slider4.jpg" alt="porsche">
      </div>
    </div>

    <!-- Left and right controls -->
    <a class="left carousel-control" href="#myCarousel" data-slide="prev">
      <span class="glyphicon glyphicon-chevron-left"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="right carousel-control" href="#myCarousel" data-slide="next">
      <span class="glyphicon glyphicon-chevron-right"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>
  <div class="model">
    <span><b>Models</b></span>
  </div>

  <div class="container1">
    <div class="box1">
      <div class="namo">718</div>
      <div class="price">from INR 14,772,000</div>

      <a style="text-decoration: none;" href="#">
        <div class="built">
          <i class="fa-solid fa-arrow-up-right-from-square"></i>&nbsp; Built Your Own

        </div>
      </a>



    </div>
    <div class="box2">
      <div class="name2">911</div>
      <div class="price2">from INR 18,646,000</div>
      <a style="text-decoration: none;" href="911page.html" target="_blank">
        <div class="built">
          <i class="fa-solid fa-arrow-up-right-from-square"></i>&nbsp; Built Your Own

        </div>
      </a>

    </div>
    <div class="box3">
      <div class="name3">Taycan</div>
      <div class="price3">from INR 16,096,000</div>
      <a style="text-decoration: none;" href="Tycanpage.html" target="_blank">
        <div class="built">
          <i class="fa-solid fa-arrow-up-right-from-square"></i>&nbsp; Built Your Own

        </div>
      </a>

    </div>

  </div>
  <div class="container2">
    <div class="box4">
      <div class="name4">Panamera</div>
      <div class="price4">from INR 15,804,000</div>
      <a style="text-decoration: none;" href="#">
        <div class="built">
          <i class="fa-solid fa-arrow-up-right-from-square"></i>&nbsp; Built Your Own

        </div>
      </a>

    </div>
    <div class="box5">
      <div class="name5">Macan</div>
      <div class="price5">from INR 8,806,000</div>
      <a style="text-decoration: none;" href="#">
        <div class="built">
          <i class="fa-solid fa-arrow-up-right-from-square"></i>&nbsp; Built Your Own

        </div>
      </a>

    </div>
    <div class="box6">
      <div class="name6">Cayenne</div>
      <div class="price6">from INR 13,561,000</div>
      <a style="text-decoration: none;" href="#">
        <div class="built">
          <i class="fa-solid fa-arrow-up-right-from-square"></i>&nbsp; Built Your Own

        </div>
      </a>

    </div>
  </div>

  <footer>
    <div class="foot">
      <div class="menu">
        <div class="buck">
          <h2>Build & Find</h2>
          <li id="list1">Build your Porsche</li>
          <li>Compare Models</li>
          <li>Search Pre-Owned</li>
          <li>Find your Porsche Centre</li>
          <li>Download the model range catalogue</li>


        </div>
        <div class="buck2">
          <h2>Online Services</h2>
          <li>Porsche Login</li>
          <li>Sign up for News</li>

        </div>
        <div class="buck3">
          <h2>Behind the Scenes</h2>
          <li>Passion Motorsports</li>
          <li>Porsche Experience </li>
          <li>Porsche Classic</li>
          <li>Visit Porsche Museum</li>

        </div>
        <div class="buck4">
          <h2>Porsche Company</h2>
          <li>Latest News</li>
          <li>At a Glance</li>
          <li>Jobs & Careers</li>
          <li>Contact & Information</li>

        </div>
      </div>
    </div>
    <div class="legal">
      <div class="notice">
        <div class="con"> <b>Change country/region:</b></div><br>
        <select name="region" id="4k">
          <option value="">Select a region</option>
          <option value="north America">North America</option>
          <option value="europe">Europe</option>
          <option value="asia">Asia</option>
          <option value="australia">Australia</option>
        </select>

        <div class="copyright">
          <i class="fa-regular fa-copyright"></i> 2023 Porsche India - SKODA AUTO Volkswagen India Private Limited
          -India . <u>Legal notice, Cookie & Privacy Policy, Corporate Governance. Open Source Software
            Notice.Whistleblower System. </u>Business and Human Rights.
        </div>

      </div>

    </div>

  </footer>

</body>

</html>
