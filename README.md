<!-- PROJECT SUMMARY -->
<div align="center">
  <h1 align="center">Groove Glitch</h1>

  <p align="center">
    {a collaborative controller}
    <br>
    <a href="https://github.com/PinkCoffeeMug/groove-glitch/issues">» submit a suggestion </a>
    ·
    <a href="https://github.com/PinkCoffeeMug/groove-glitch/issues">» report a bug </a>
    ·
    <a href="https://github.com/PinkCoffeeMug/groove-glitch">» contact </a>
  </p>

  <div align="center">

![GitHub forks](https://img.shields.io/github/forks/PinkCoffeeMug/groove-glitch?style=social) ![GitHub stars](https://img.shields.io/github/stars/PinkCoffeeMug/groove-glitch?style=social)

![GitHub last commit](https://img.shields.io/github/last-commit/PinkCoffeeMug/groove-glitch?color=hotpink) ![GitHub Pull Request (open)](https://img.shields.io/github/issues-pr/PinkCoffeeMug/groove-glitch?color=forestgreen) ![GitHub License](https://img.shields.io/github/license/PinkCoffeeMug/groove-glitch?color=blue) ![contributions welcome](https://img.shields.io/badge/contributions-welcome-purple.svg?style=flat)

  </div>
</div>

<!-- TABLE OF CONTENT -->
<details>
  <summary><h2 style="display: inline-block">🕹 Table of Content</h2></summary>
  <ol>
    <li>
      <a href="#🌻-about">About</a>
      <ul>
        <li><a href="#🔧-tech-stack">Tech Stack</a></li>
        <li><a href="#🍄-features">Features</a></li>
      </ul>
    </li>
    <li>
      <a href="#🌵-documentation">Documentation</a>
      <ul>
        <li><a href="#🍯-setup">Setup</a></li>
        <li><a href="#🍎-development">Development</a></li>
      </ul>
    </li>
    <li><a href="#🌾-contributing">Contributing</a></li>
    <li><a href="#📜-license">License</a></li>
  </ol>
</details>

<!-- ABOUT -->
## :sunflower: About
<!-- Add your project description here -->

### :wrench: Tech Stack

- [ ] React, Javascript
- [ ] Django, Python
- [ ] Spotify API


### :mushroom: Features

- [ ] Spotify Integration
- [ ] Music Control
- [ ] Interactive User Interface
- [ ] Scalable Backend



<!-- CONTENT -->
## :cactus: Documentation

### :honey_pot: Setup
<!-- Add setup instructions here -->
- nodejs, npm
    - frontend
      - `django-admin startapp frontend`
      - `npm init -y`
      -  webpack: 
         -  `npm i webpack webpack-cli --save-dev`
         -  add in script
            -  `"dev": "webpack --mode development --watch"`
            -  `"build": "webpack --mode production"`
      -  babel: 
         -  `npm i @babel/core babel-loader @babel/preset-env @babel/preset-react --save-dev`
         -  `npm install @babel/plugin-proposal-class-properties`
      -  react: 
         -  `npm i react react-dom --save-dev`
         -  `npm install react-router-dom`
      -  material-ui: 
         -  `npm install @material-ui/core` or `npm install --save --legacy-peer-deps @material-ui/core`
         -  `npm install @material-ui/icons` or `npm install --save --legacy-peer-deps @material-ui/icons`
         -  
- python, pip/pip3
  - save and apply
    - `python ./manage.py makemigrations`
    - `python ./manage.py migrate`
  - `python ./manage.py runserver`
  
- django, djangorestframework:
  - `django-admin startproject controller`
  - `django-admin startapp api`

### :apple: Development
<!-- Add development details here -->
* []()
* []()
* []()

<!-- CONTRIBUTING -->
## :ear_of_rice: Contributing
<!-- Add contribution guidelines here -->
> 1. Fork the Project
> 2. Create your Branch (`git checkout -b my-branch`)
> 3. Commit your Changes (`git commit -m 'add my contribution'`)
> 4. Push to the Branch (`git push --set-upstream origin my-branch`)
> 5. Open a Pull Request


<!-- LICENSE -->
## :scroll: License
<!-- Add license information here -->
This project is licensed under [MIT](https://opensource.org/licenses).

<!-- ACKNOWLEDGEMENTS -->
<!-- ## Acknowledgements -->
<!-- <a rel="" href="[emojishorthand](https://gist.github.com/rxaviers/7360908)"> -->
