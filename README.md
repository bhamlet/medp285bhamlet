<!DOCTYPE html>
<html>
  <head>
    <link rel="shortcut icon" href="/favicon.ico" type="image/x-icon">
    <link rel="icon" href="/favicon.ico" type="image/x-icon">

    <meta charset="utf-8" />
    <title>My First MEDP 285 Page</title>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta name="description" content="Homepage for my web 1 class" />
    <meta name="author" content="Biancha" />

    <style>
      * { box-sizing: border-box; }
      html { height: 100%; scroll-behavior: smooth; }
      body {
        #grad1
        height: 200px;
        background-color: lavender; /* For browsers that do not support gradients */
        background-image: linear-gradient(white, lavender);
      }
      { font-family: "Comic Sans MS", cursive, sans-serif;
        position: relative;
        margin: 0;
        padding-bottom: 6em;
        min-height: 100%;
      }

      h1 {
        font-family: 'Comic Sans MS', bold;
        font-family: 'Comic Sans MS', sans-serif;
      }
      p { line-height: 1.5em; }
      nav {
        position: fixed;
        left: 0;
        top: 0px;
        height: 3em;
        width: 100%;
        color: #FFB0E9;
        background-color: rgba(0, 0, 0, 0.8);
        margin: 0;
        margin-top: -10px;
        padding: 0 0 10px 0;
        z-index: 10;
      }
      nav a {
        text-decoration: none;
        color: Purple;
      }
      nav a:hover { color: green; }
      nav ul {list-style-type: none}
      nav ul li {
        display: inline;
        margin-top: 0;
        padding-left: 10px;
        padding-right: 10px;
        border-right: 1px dotted #8023FF;
      }
      nav ul li a img {vertical-align: text-bottom;}
      nav ul li:last-child {border-right:none}
      title {
        text decoration: none;
        color: Purple;
}
      #main {
        margin-top: 3em;
        padding: 0 2em 0 2em;
        padding-bottom: 100px;
      }

      header picture img {
        display: block;
        margin-left: auto;
        margin-right: auto;
      }

      video {
        width: 100%;
        height: 100%
      }

      iframe {
        display: block;
        margin-left: auto;
        margin-right: auto;
      }

      section {
        margin-top: 4em;
      }

      footer {
        position: absolute;
        left: 0;
        bottom: 0;
        width: 100%;
        background-color: #D0B0FF;
        color: #fff;
        text-align: center;
      }

      /* Creating a CSS Dropdown Menu */

      /* The container <div> - needed to position the dropdown content */
      .dropdown {
          cursor: pointer;
          position: relative;
          display: inline-block;
      }
      /* Dropdown Content (Hidden by Default) */
      .dropdown-content {
          display: none;
          position: absolute;
          min-width: 10em;
          background-color: #f9f9f9;
          box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
          z-index: 20;
      }
      /* Links inside the dropdown */
      .dropdown-content a {
          background-color: rgba(0,0,0,0.8);
          color: white;
          padding: .5em 2em .5em 1em;
          text-decoration: none;
          border-bottom: 1px solid lavender;
          display: block;
      }
      /* Show the dropdown menu on hover */
      .dropdown:hover .dropdown-content {
          display: block;
      }

      /* Adding Media Queries */
      @media screen and (max-width: 600px) {
        body {
          background-color: white;
          color: black;
        }
      }

    </style>
  </head>

  <body>
    <!-- navigation -->
    <nav id="nav">
      <!-- <ul type="circle"> -->
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <div class="dropdown-content">
          <a href="slideshowDemo">Slideshow</a>
          <a href="video">Video Assignment</a>
          <a href="#">Link 3</a>
        </div>
      </li>
        <li><a href="https://biavisual.blogspot.com" target="_blank">Blog</a></li>
        <li><a href="contact.html">Contact</a></li>
        <li><a href="https://twitter.com/AsToldbyBIA"><img src="img/twitter.png" alt="Twitter icon and link" width="16" /></a></li>
        <li><a href="https://www.instagram.com/b.cuphinata/"><img src="img/instagram.png" alt="Instagram icon and link" width="16" /></a></li>
      </ul>
    </nav>

    <div id="main">
    <header id="home">
      <h1>BIA's MEDP 285 Homepage</h1>
      <!-- <img src="img/gob@1280.jpg" alt="Documentation of an installation" /> -->
      <picture>
          <source media="(min-width:1280px)" srcset="img/astoldbybia.jpg" />
          <source media="(min-width:960px)" srcset="img/astoldbybia.jpg" />
          <img src="img/astoldbybia" alt="Podcast Logo" />
      </picture>
    </header>

    <hr />
     <section id="about">
       <h1><u>AS TOLD by BIA</u></h1>
       <p>This is a creative space made using <b>ATOM</b> and web resources given for <u>Web Production 1</u>. Web pages are primarily text documents formated &amp; annotated with <s>Hpertext Markup Language (HTML)</s>.  In addition to formatted text, web pages may contain images, video audio and <small>software components</small> that are rendered in the user's wbe browser as multimedia. I will be sharing information on how
         to use web resources to create your own podcast.
       </p>
       <cite>Check out this link ---> <a href="https://anchor.fm/astoldbybia">Anchor is the easiest way to make a podcast, ever.</a></cite>
    </section>

    <hr>

      <article>
        <h2>List Breakdown</h2>
        <ol type="I">
          <li>Item 1</li>
            <ol type="A">
              <li>Sub item 1
                <ol type="1">
                  <li>item 1</li>
                    <ol type="a">
                      <li>little a</li>
                      <li>little b</li>
                    </ol>
                  <li>item 2</li>
                </ol>
              </li>
            <li>Item 2</li>
            <li>Item 3</li>
          </ol>
          <li>Item 2</li>
          <li>Item 3</li>
        </ol>

        <ol>
          <li>without a type</li>
        </ol>

        <article>
          <h2>Three Big Streaming Platforms</h2>
          <table border="1">
            <tr>
              <th>Company</th>
              <th>Ticker Symbol</th>
              <th>Value 2015</th>
              <th>Value 2020</th>
            </tr>
            <tr>
              <td>Apple</td>
              <td>APPL</td>
              <td>$93</td>
              <td>$450</td>
            </tr>
            <tr>
              <td>Spotify</td>
              <td>AMZN</td>
              <td>$325</td>
              <td>$3200</td>
            </tr>
            <tr>
              <td>Goodle</td>
              <td>GOOG</td>
              <td>$200</td>
              <td>$1500</td>
            </tr>
          </table>
        </article>

    </section>

  </div><!-- close main div -->
<h1>Mukbang</h>
  <iframe width="560" height="315" src="https://www.youtube.com/watch?v=Kwx2qwmQt6s" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>

    <footer id="contact">
      <h1>CONTACT</h1>
      <p>For questions please email <a href="mailto:msbahmlet@gmail.com">msbahmlet@gmail.com</a>
        <br>
        <a href="#home">top</a>
      </p>
      <!--
      <nav id="navFooter">
        <ul type="circle">
          <li><a href="#home">Home</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#projects">Projects</a></li>
          <li><a href="https://biavisual.blogspot.com" target="_blank">Blog</a></li>
          <li><a href="contact.html">Contact</a></li>
        </ul>
      </nav>
    -->
    </footer>

  </body>
</html>
