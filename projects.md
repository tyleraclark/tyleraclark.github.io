---
layout: page
title: Projects
---

<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.container {
  position: relative;
  width: 100%;
}

.image {
  opacity: 1;
  display: block;
  width: 100%;
  height: auto;
  transition: .5s ease;
  backface-visibility: hidden;
}

.middle {
  transition: .5s ease;
  opacity: 0;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  text-align: center;
}

.container:hover .image {
  opacity: 0.4;
}

.container:hover .middle {
  opacity: 1;
}

.text {
  background-color: transparent;
  color: #333333;
  font-size: 24px;
}

a:link {
  color: #333333;
  background-color: transparent;
  text-decoration: none;
}

a:visited {
  color: #333333;
  background-color: transparent;
  text-decoration: none;
}

a:hover {
  color: #888888;
  background-color: transparent;
  text-decoration: none;
}

a:active {
  color: #333333;
  background-color: transparent;
  text-decoration: none;
}

</style>

<h1>Projects</h1>

<div class="container">
    <a href="/projects/CMSC320_project_2.html">
        <img src="https://raw.githubusercontent.com/tyleraclark/tyleraclark.github.io/main/_images/proj2.png" alt="Avatar" class="image" style="width:100%">
        <div class="middle">
            <div class="text">
                <a href="/projects/CMSC320_project_2.html">Moneyball</a>
            </div>
        </div>
    </a>
</div>
<br>
<div class="container">
    <a href="/projects/CMSC320_final_project.html">
        <img src="https://raw.githubusercontent.com/tyleraclark/tyleraclark.github.io/main/_images/final_proj.png" alt="Avatar" class="image" style="width:100%">
        <div class="middle">
            <div class="text">
                <a href="/projects/CMSC320_final_project.html">
                    Inferring Ideology from Incidents:<br>An Analysis of the Global Terrorism Database
                </a>
            </div>
        </div>
    </a>
</div>