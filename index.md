---
layout: base
title: I'm Simrut Kaur
hide: true
---

### Me and Team

Hi! My name is Simrut Kaur.

| Role         | Name     | Repo Location                       | Stream                | Repo Name |
|--------------|----------|-------------------------------------|-----------------------|-----------|
| Scrum Master | John     | github.com/jm1021/student           | upstream (OCS fork)   | student   |
| Scrummer     | Torin    | github.com/torin/student            | downstream (fork)     | student   |
| Scrummer     | Avantika | github.com/avantika/student         | downstream (fork)     | student   |
| Scrummer     | Aadit    | github.com/aaadit/student           | downstream (fork)     | student   |


<!DOCTYPE html>
<html>
<head>
  <title>Confetti Button</title>
  <style>
    body {
      display: flex;
      height: 100vh;
      justify-content: center;
      align-items: center;
      background: #000000ff;
      font-family: sans-serif;
    }
    button {
      background: #ff4081;
      color: white;
      border: none;
      padding: 15px 25px;
      font-size: 18px;
      border-radius: 8px;
      cursor: pointer;
      transition: background 0.3s;
    }
    button:hover {
      background: #e73370;
    }
  </style>
</head>
<body>

  <button id="confettiBtn">🎉 Celebrate!</button>

  <!-- Confetti Library -->
  <script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.6.0/dist/confetti.browser.min.js"></script>
  <script>
    const button = document.getElementById('confettiBtn');

    button.addEventListener('click', () => {
      confetti({
        particleCount: 150,
        spread: 70,
        origin: { y: 0.6 }
      });
    });
  </script>

</body>
</html>

<!DOCTYPE html>
<html>
<head>
<style>
  body {
    background-color: #1E1E1E;
    margin: 0;
    height: 100vh;
  }
</style>
</head>
<body>
</body>
</html>




## Links to Learning

### Development Environment

> Coding starts with tools, explore these tools and procedures with a click.

<a href="https://github.com/Open-Coding-Society/student">
    <img src="https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white" alt="GitHub">
</a>
<a href="https://open-coding-society.github.io/student">
    <img src="https://img.shields.io/badge/GitHub%20Pages-327FC7?logo=github&logoColor=white" alt="GitHub Pages">
</a>
<a href="https://kasm.opencodingsociety.com/" class="button small" style="background-color: #ee99d7ff">
    KASM
</a>
<a href="https://vscode.dev/" class="button small" style="background-color: #eeb4e3ff">
    <span style="color: #eeb3e3ff">VSCODE</span>
</a>

<br>

### Class Progress

<a href="{{site.baseurl}}/snake" class="button small" style="background-color: #f199cbff">
    Snake Game
</a>
<a href="{{site.baseurl}}/turtle" class="button small" style="background-color: #dd84d8ff">
    <span style="color: #000000">Turtle</span>
</a>

<br>

<!-- Contact Section -->
### Get in Touch

> Feel free to reach out if you'd like to collaborate or learn more about our work.

<p style="color: #ed5ca4ff;">Open Coding Society: <a href="https://opencodingsociety.com" style="color: #2A7DB1; text-decoration: underline;">Socials</a></p>
