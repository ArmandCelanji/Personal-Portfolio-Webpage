
<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" 
 href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
@import url('https://fonts.googleapis.com/css2?family=Architects+Daughter&display=swap');

* {
  box-sizing: border-box;
}
body {
  font-family: 'Architects Daughter', cursive;
  background-color: #00cccc;
  margin: 0;
}
 
footer {
  background-color: #008080;
  color: #ffffff;
  padding: 10px;
  text-align: center;
 
}
nav {
  background-color: #008080;
  color: #ffffff;
  padding: 20px;/*sa i trrash do jet nav*/
  display: flex;
  justify-content: flex-end;/*kjo eshte per cuar link ne te djatht*/
  position: fixed;/*nga ktu dhe posht eshte per te van nav fixed*/
  top: 0;
  left: 0;
  right:0;
  z-index: 100;
  
}
nav a {
  color: #ffffff;
  margin-left: 40px;/*sa hapsir do jet nav*/
  text-decoration: none;/*per ti hequr vizat*/
}

header {
 
  background-image: url(https://images.unsplash.com/photo-1542903660-eedba2cda473?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80);
 
  background-size: cover; /*per ta pershtatur me mir img qe kemi ven*/
  background-position: center center;/*per ta pershtatur me mir img qe kemi ven*/

   color: white;
   display: flex;
   align-items: center;
   justify-content: center;
   flex-direction: column;/*per te ven p element posht h1r*/
   height: 100vh;/*sa hapsir do jet ne header*/
   position: relative;/*kjo duhet header after qe te heqim hapsiren midis header dhe nav*/
}
header::after {/*kjo eshte lay out mbi foton*/
  content: "";
  background-color: black;
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  opacity: 0.3;
}
header * {
  position: relative;
  z-index: 1; /*kjo e nxjerr lar layer shkrimin */
}
header h1 {
  font-size: 70px;
  margin-bottom: 5px;
  margin-top: 0;
}
header p {
  font-size: 35px;
  margin: 0;
  text-align: center;
}

/* Style all font awesome icons */
.fa {
  padding: 20px;
  font-size: 30px;
  width: 50px;
  text-align: center;
  text-decoration: none;
}
section {
  text-align: center;
  padding: 50px;
}
section h2 {
  margin: 0;
}
section p {
  margin-top: 0;
}
.project-tile {
  max-width: 250px;
  margin: 10px;
  transition: transform 0.3s ease;
}
.project-tile:hover {
  transform: scale(1.05);
}
.project-tile img {
  max-width: 100%;
 
}
.projetcts-container {
    display: flex;
    flex-wrap: wrap;
    align-item: center;
    justify-content: center;
    max-width: 810px;
  margin: 20px auto 0;
}
.project-tile p {
  font-size: 15px;
  margin-top: 10px;
}
.bg-social {
  background-color: #00e6e6;
  color: white;
}
.social-ul {
  display: flex;
  flex-wrap: wrap;
  list-style-type: none;
  justify-content: center;
  padding: 0;
  margin: 5px 10px;
  
}
.social-ul a {
  font-size: 60px;
  margin: 0 30px;
 
}

/* Add a hover effect if you want */
.fa:hover {
  opacity: 0.7;
}

/* Set a specific color for each brand */

/* Facebook */
.fa-facebook {
 color: blue;
}

/* Git hub */
.fa-github {
color: black;
}
@media (max-width: 440px) {
  section {
    padding: 50px;
  }
}



Resources

    </style>
</head>
<body>
    <nav id="navbar">
        <a href="#welcome-section">About</a>
        <a href="#project-tile">Project</a>
        <a href="#social">Social</a>
  </nav>
 
  <header id="welcome-section">
    <div id="project-tile">
    <h1>Hey Iam Armand</h1> 
    <p>a web developer</p>
    </div>
  </header>
 
 <section id="projects">
     <h2>These are some of my projects</h2>
   <div class="projetcts-container">
  <div class="project-tile"><img src="https://images.unsplash.com/photo-1580927752452-89d86da3fa0a?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80" alt="test-img">
  <p>Not by me</p>
    </div>
   <div class="project-tile"><img src="https://images.unsplash.com/photo-1548611716-ad782502c9d2?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="test-img">
  <p>Not by me</p>
    </div>
   </div>
 
 <section id="social" class="bg-social">
   <h2>Let's work together...</h2>
   <p>How do you take your coffee?</p>
   <ul class="social-ul">
     <li><a href="https://www.facebook.com/armand.celanji" target="_blank" class="fa fa-facebook"></a></li>
     <li><a id="profile-link" href="https://github.com/ArmandCelanji" target="_blank" class="fa fa-github"></a></a></li></i>
   </ul>
 </section>
 
 
     
 
 <footer class="footer">
   <p>Made by me Armand</p>
 </footer>
 
 
 
 Resources
</body>
</html>
