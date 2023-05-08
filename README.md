<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>My Project Display</title>
    <style>
      /* CSS styles go here */
      body {
        font-family: Arial, sans-serif;
        background-color: #f0f0f0;
      }
      
      #header {
        background-color: #333;
        color: #fff;
        padding: 20px;
        text-align: center;
      }
      
      #projects {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
      }
      
      .project {
        margin: 20px;
        padding: 20px;
        background-color: #fff;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
        border-radius: 5px;
        text-align: center;
      }
      
      .project img {
        max-width: 100%;
        height: auto;
        margin-bottom: 10px;
      }
      
      .project h2 {
        margin-top: 0;
      }
      
      .project p {
        font-size: 16px;
        line-height: 1.5;
      }
      
      .project a {
        display: inline-block;
        margin-top: 10px;
        padding: 10px 20px;
        background-color: #333;
        color: #fff;
        text-decoration: none;
        border-radius: 5px;
        transition: background-color 0.3s ease;
      }
      
      .project a:hover {
        background-color: #555;
      }
    </style>
  </head>
  <body>
    <header id="header">
      <h1>My Projects</h1>
    </header>
    
    <div id="projects">
      <div class="project">
        <img src="project1.png" alt="Project 1">
        <h2>Project 1</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam eget elit turpis. Ut maximus augue nunc, sit amet facilisis urna varius eget.</p>
        <a href="#">View Project</a>
      </div>
      
      <div class="project">
        <img src="project2.png" alt="Project 2">
        <h2>Project 2</h2>
        <p>Phasellus auctor odio sit amet nunc suscipit, at auctor orci efficitur. Fusce ut lorem vel nisl maximus imperdiet.</p>
        <a href="#">View Project</a>
      </div>
      
      <div class="project">
        <img src="project3.png" alt="Project 3">
        <h2>Project 3</h2>
        <p>Nam vel neque non justo pellentesque bibendum eget vel arcu. Vivamus lacinia enim ut nunc fermentum malesuada.</p>
        <a href="#">View Project</a>
      </div>
    </div>
  </body>
</html>
