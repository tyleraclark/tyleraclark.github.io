---
layout: page
title: Projects2
---

<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.container {
  position: relative;
  width: 50%;
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
  opacity: 0.3;
}

.container:hover .middle {
  opacity: 1;
}

.text {
  background-color: #04AA6D;
  color: white;
  font-size: 16px;
  padding: 16px 32px;
}
</style>

<h2>Opacity with Box</h2>
<p>Hover over the image to see the effect.</p>

<div class="container">
  <img src="https://raw.githubusercontent.com/tyleraclark/tyleraclark.github.io/main/_images/proj2.png" alt="Avatar" class="image" style="width:100%">
  <div class="middle">
    <div class="text">Moneyball</div>
  </div>
</div>