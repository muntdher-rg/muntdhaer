
<html>
    <head>
<title>muntadhwe-rg</title>
<style>
    
/* GENERAL STYLES
–––––––––––––––––––––––––––––––––––––––––––––––––– */

body {
  background: #FDD761;
  font-family: 'Lucida Sans Unicode', 'Arial', serif;
  color: white;
}

h1, h3, h4, header .btn {
  font-weight: 700;
}

h1 {
  margin: 100px 0 20px;
  text-transform: uppercase;
  font-size: 2.6rem;
}

h3 {
  margin-bottom: 25px;
  font-size: 2.3rem;
  text-align: left;
}

h4 {
  font-size: 2rem;
}

h3:after {
  content: '';
  display: block;
  width: 10%;
  padding-top: 5px;
  border-bottom: 3px solid whitesmoke;
}

h1 + h4 {
  font-weight: normal;
}

a {
  text-align: center;
  outline: none;
  display: inline-block;
  text-decoration: none;
  background: #fcca2f;
  font-size: 14px;
  color: steelblue;
  text-shadow: 0px 1px 0px rgba(0, 0, 0, 0.25);
  -webkit-transition: all ease .3s;
          transition: all ease .3s;
}

.btn {
  font-size: 1.2em;
  border-radius: 5px;
  padding: 12px 30px;
}

.block {
  width: 130px;
  margin: 0 auto;
  display: block;
}



/* HEADER STYLES
–––––––––––––––––––––––––––––––––––––––––––––––––– */

header .btn {
  text-transform: uppercase;
}

header a:hover, .about a:hover {
  background: #fcc316;
}

header .btn, .services {
  margin-top: 100px;
}

header {
  padding: 80px 0 150px;
}

.about, .contact {
  padding: 150px 0;
}

header {
  background: url(nm.jpg) no-repeat fixed center / cover;
  text-align: center;
}

nav ul, .contact ul {
  list-style: none;
  font-size: 0;
}

nav li, .contact li {
  margin-bottom: 0;
  display: inline-block;
}

nav li {
  width: 50%;
}

nav a {
  position: relative;
  width: 100%;
  height: 30px;
  padding: 7px 0;
  line-height: 30px;
}

nav li:nth-child(2n+1) a:after {
  position: absolute;
  content: '';
  top: 19.5px;
  right: -2.5px;
  z-index: 10;
  border-radius: 100%;
  background: steelblue;
  width: 5px;
  height: 5px;
}



/* SERVICES STYLES
–––––––––––––––––––––––––––––––––––––––––––––––––– */

.services a {
  padding: 25px;
  background: #fafafa;
  margin-top: 20px;
  border-radius: 4px;
}

.services a:hover {
  color: black;
}

.services span {
  font-size: 5.5em;
  color: #f4ba04;
}

.services a:hover span {
  color: white;
}

.services p {
  margin: 15px 0 0;
}



/* ABOUT STYLES
–––––––––––––––––––––––––––––––––––––––––––––––––– */

.about {
  background: url("https://unsplash.it/1080/720/?image=349") no-repeat fixed center / cover;
  color: black;
}

.about .one-third, 
.about .two-thirds {
  background: white;
  background: rgba(255,255,255,.3);
  padding: 10px;
  border-radius: 5px;
}

.about .one-third {
  margin-top: 20px;
}

.about a {
  margin-top: 10px;
}

.about ul {
  margin-bottom:18px;
}

.about h3:after, .contact h3:after {
  border-color: black;
}

.about .center {
  text-align: center;
}

.about .bottom {
  margin-bottom: 20px;
  padding-bottom: 20px;
}

.about .one-third a {
  margin: 10px auto;
  width: 50%;
  display: block;
} 

.about .two-thirds p:last-child {
  margin-bottom: 0;
}



/* CONTACT STYLES
–––––––––––––––––––––––––––––––––––––––––––––––––– */

.contact {
  color: black;
  text-align: center;
}

.contact p {
  margin: 70px 0 0;
}

.contact ul a {
  margin-top: 50px;
  box-shadow: none;
  background: none;
  margin-left: 30px;
}

.contact li:nth-child(1) a {
  margin-left: 0;
}

.contact span {
  font-size: 2em;
  color: white;
  -webkit-transition: color ease .4s;
          transition: color ease .4s;
}

.contact span:hover {
  color: steelblue;
}

.contact .btn-blue {
  position: relative;
  margin-top: 30px;
  color: white;
  background: steelblue;
  box-shadow: 0 8px #3b6d97;
}

.contact .btn-blue:hover {
  background: #427aa9;
  color: white;
}

.contact .btn-blue:after {
  position: absolute;
  content: '☃';
  top: 5px;
  right: 30px;
  font-size: 1.6em;
}

.contact .btn-blue:active {
  box-shadow: 0 4px #3b6d97;
  -webkit-transform: translateY(4px);
      -ms-transform: translateY(4px);
          transform: translateY(4px);
}

.contact .creator a {
    background: none;
}



/* MEDIA QUERIES STYLES
–––––––––––––––––––––––––––––––––––––––––––––––––– */

@media (min-width: 550px) {

  nav li {
    width: auto;
  }

  a {
    box-shadow: 0 8px #f4ba04;
  }

  nav a {
    padding: 7px;
    border-right: 1px solid #fabd03;
    width: 80px;
  }

  nav li:nth-child(2n+1) a:after {
    content: none;
  }

  nav li:last-child a {
    border-right: none;
  }

  header a:hover, .about a:hover {
    box-shadow: 0 8px #f4ba04;
  }

  header a:active, .about a:active {
    box-shadow: 0 4px #f4ba04;
    -webkit-transform: translateY(4px);
        -ms-transform: translateY(4px);
            transform: translateY(4px);
  }

  .about .one-third {
    margin-top: 0;
  }
  
  .about .one-third a {
    width: 35%;  
  }
  
  .contact .creator a {
    box-shadow: none;
  }

}



@media (min-width: 750px) {

  h1 {
    font-size: 3.5rem;
  }

  h3 {
    font-size: 2.8rem;
  }

  h4 {
    font-size: 2.4rem;
  }

  .services a:hover {
    box-shadow: 0 -8px white;
    -webkit-transform: scale(1.15);
        -ms-transform: scale(1.15);
            transform: scale(1.15);
  }
  
  .contact ul a {
    margin-left: 45px;
  }

  .contact ul span {
    font-size: 3em;
  }

}



    </style>
    <script>
// Demo by George Martsoukos
// See: http://www.sitepoint.com/getting-started-with-skeleton-simple-css-boilerplate

</script>
    </head>
     
    <body>

        <!--HEADER-->
<header>
    <div class="container">
      
      <div class="row">
        <div class="twelve columns">
          <nav>
            <ul>
              <li><a href="bx.html">home</a></li>
              <li><a href="author.html">about</a></li>
              <li><a href="#">blog</a></li>
              <li><a href="rg.html">Contact</a></li>
            </ul>
          </nav>  
        </div> 
      </div>
  
      <div class="row">    
        <div class="twelve columns">
          <h1><em>-mmuntadher-rg -</em></h1>
          <h4> <em> DEVELOPER ~ UI/UX DESIGNER.</em></h4>
          <a href="#" class="btn">dow</a> 
        </div>
      </div>
      
      <section class="services">
        <div class="row">
          <div class="twelve columns">
            <h3>My articl</h3>
          </div>
        </div>
        <div class="row">
            <div class="one-half column">
                <a href="gh.html">
                  <h4>Shadows & Lights</h4>
                
                  <span class="fa fa-picture-o"></span>
                  <p>“Darkness cannot drive out darkness: only light can do that.
                    Hate cannot drive out hate: only love can do that.”.</p>
                      <p> article</p>
                </a>
              </div>
          <div class="one-half column">
            <a href="">
              <h4> the stars</h4>
              <span class="fa fa-leaf"></span>
              <p> “Imagination does not become great until human beings, given the courage and the strength, use it to create.”
                ― Maria Montessori
              .</p>
            </a>
          </div>
        </div><!--end of .row-->
      </section>
    </div><!--end of .container-->
  </header>
  
  <!--ABOUT-->
  <section class="about">
    <div class="container">
      <div class="row">
        <div class="twelve columns">
          <h3>Who am I</h3>
        </div>
      </div><!--end of .row-->
      <div class="row bottom">
        <div class="two-thirds column">
          <p>Hi, am MUNYADHER . A Web Developer.
            Through coding i've acquired problem-solving skills and a way to.</p>
          <p>communicate with others on a technical level. I'd love to work in a
            tech company, with artists, athletes, photographers, non-profits, and</p>
          <p>small businesses to improve their Web presence.</p>

            
          I am also a writer, I love literature and poetry. I wrote two novels. I like ancient literature very much. I would like to someday develop the world.</p>
          <p>“It is our choices, Harry, that show what we truly are, far more than our abilities.”
            ― J.K. Rowling, Harry Potter and the Chamber of Secrets.</p>
        </div>
        <div class="one-third column">
          <h4>working</h4>
          <ul>
            <li>web Developer</li>
            <li>fix proplems </li>
            <li>wrote coding</li>
          </ul>
          <h4>Honors</h4>
            <ul>
              <li>“Dreams come true. Without that possibility, nature would not incite us to have them. ”</li>
             
            </ul>
            <a href="#" class="btn">CV</a>
        </div>
      </div><!--end of .row-->
      <div class="row">
        <div class="twelve columns">
          <h4 class="center">Interested in samples of my work?</h4>
        </div>
      </div><!--end of .row-->
      <div class="row">
        <div class="twelve columns">
          <a href="https://github.com/muntdher-rg" class="btn block">Visit github</a>
        </div>
      </div><!--end of .row-->
    </div><!--end of .container-->
  </section>
  
  <!--CONTACT-->
  <section class="contact">
    <div class="container">
      <div class="row">
        <div class="twelve columns">
          <h3>Contact</h3>
        </div>
      </div><!--end of .row-->
      <div class="row">
        <div class="offset-by-two eight columns">
          <ul>
            <li><a href="#" title=""><span class="fa fa-facebook"></span></a></li>
            <li><a href="#" title=""><span class="fa fa-twitter"></span></a></li>
            <li><a href="#" title=""><span class="fa fa-dribbble"></span></a></li>
            <li><a href="#" title=""><span class="fa fa-linkedin"></span></a></li>
            <li><a href="#" title=""><span class="fa fa-github"></span></a></li>
          </ul>
        </div>
      </div><!--end of .row-->
      <div class="row">
        <div class="twelve columns">
          <a href="muntadertechno@gmail.com" class="btn block btn-blue">Mail me</a>
        </div>
      </div><!--end of .row-->
      <div class="row">
        <div class="twelve columns">
          <p class="creator"> writing by muntadher <a href="muntadher.com">See article</a>.</p>
        </div>
      </div><!--end of .row-->
    </div><!--end of .container-->
  </section>
  
  
  
    </body>
</html>
    
