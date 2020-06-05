<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Resume</title>
  </head>
  <body>
    <style>
    div {
      border-radius: 5px;
    }
    #title {
      margin-left: 3%;
    }
    .left {
      height: 1000px;
      width: 45px;
      background-color: #e0eeee;
      float: left;
      position: fixed;
    }
    .right {
      height: 1000px;
      width: 45px;
      background-color: #e0eeee;
      float: right;
      position: inherit;
    }
    .stuff {
      display: inline-block;
      margin-top: 6px;
      margin-left: 55px;
      width: 75%;
      height: 1000px;
    }
    p, li {
      font-family: "Cormorant Garamond";
    }
    .head {
      font-size: 20px;
    }

    @media only screen and (max-width: 450px) {
      .left, .right {
        display: none;
      }
      .stuff {
        width: 100%;
        margin-left: 10px;
      }
    }
    </style>

    <div id="header"></div>
    <div class="left"></div>
    <div class="stuff">
      <br><br>
      <h1>Resume</h1>
      <img src="myphoto.jpg" width="150px">
      <h2>Jeong Il Jun</h2>
      <p class="head">Interests</p>
      <ul>
        <li>Automobile</li>
        <li>Design</li>
        <li>Programming</li>
        <li>Computer Science</li>
      </ul>
      <p class="head">Skills</p>
      <ul>
        <li>Web Design HTML & CSS</li>
      </ul>
      <p class="head">Education</p>
      <ul>
        <li>Hanam Middle School</li>
        <li>Daedong High School</li>
        <li>Codeacademy</li>
      </ul>
      <p class="head">Experience</p>
      <ul>
        <li>Hyundai Internship</li>
      </ul>
      <p class="head">Extracurriculars</p>
      <ul>
        <li>Che-Bio Club</li>
        <li>Volunteer Organization</li>
        <li>Book Club</li>
      </ul>
    </div>
    <div class="right"></div>
    <div id="footer">
  </body>
</html>
