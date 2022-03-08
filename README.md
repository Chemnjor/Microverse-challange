# Microverse-challange

<html lang="en"> 
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="styleSheet" href="css.css">
</head>
<body>
  <nav id="navbar">
   <p1 id="first">My Portfolio</p1>
    <ul>
      
      <li><a href="#welcome-section">About</a></li>
   <li> <a href="#projects">Projects</a></li>
    
    </ul>
    
    
    
  </nav>
  
  
  
  <section id="welcome-section">
    <h1> We have programming experience </h1>
    <p> hi I'm full stack developer,creating creative website for companies all across the world</p> 
  </section>
  <section id="projects">
    <div class="project-tile">
      <div id="project1">
        <p>My first project " Michael Rainey Jr "</p>
        <img src="https://headtopics.com/images/2020/11/20/daily-express/how-much-is-tariq-st-patrick-star-michael-rainey-jr-paid-for-power-book-2-1329726952719208450.webp" alt="Michael Rainey Jr">
        <button><a href="https://codepen.io/Sirma/pen/LYONRvg"> Explore The project</a></button>
      </div>
      <div id="project2">
        <p>My second project " Curren Quartz Wristwatch "</p>
        <img src="https://cdn.shopify.com/s/files/1/1376/9745/products/product-image-183760063_grande.jpg?v=1571439204" alt="Curren Quartz Wristwatch">
        <button><a href="https://codepen.io/Sirma/pen/zYPdKLj?editors=1000"> Explore The project</a></button>
      </div>
    </div>
  </section>  
       
  <section id="contact">
   <a
      id="profile-link"
      href="https://github.com/Chemnjor"
      target="_blank"
      
      > GitHub</a
    >
    
    
  </section>
  
  
</body>
</html>




/*css section*/
body{
  font-family: Georgia, 'Times New Roman', Times, serif;
 
}
#welcome-section{

  display: flex;
  flex-direction: column;
  background-color : brown;
   text-align: center;
  font-size: 20px;
  height: 100vh;
  width: 100%;
  color: #fff;
  justify-content: center;

}
#welcome-section h1{
  font-family: 'Poppins', Sans-serif;
  
}
#welcome-section p{
  font-size: 16px;
}
#projects {
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
  background-color: #f1faee;
  padding: 15px;
  font-size: 24px;
  font-weight: bold;
}
img{
  width: 600px;
  padding: 44px;
  
}
button{
  display: flex;
  text-align: center;
  margin: auto;
  padding: 6px;
  border-radius: 10px;
}
#first {
  margin-right: auto;
  margin-left: 5px;
}
#navbar, ul {
  display: flex;
  flex-direction: row;
  

}
ul {
  color: black;
  gap: 25px;
}
a {
  text-decoration: none;
}
li {
  list-style: none;
 
}
@media screen and (min-width: 480px) {
  body {
    background-color: lightgreen;
  }
}

#navbar {
  position: fixed;
}
p1{
  font-size: 25px;
  font-weight: bold;
  color: #1B4F72 ;
}
#navbar {
  position: fixed;
  justify-content: flex-end;
 top: 0;
  left: 0;
  width: 100%;
  background: white;
  font-size: 22px;
 
  
  
}
#img img{
  width: 30%;
  text-align: center;
}
#contact {
  text-align: center;
}
  
