.l
<h1 align="center">ROWDY-MD 999.9</h1>

<img src="https://i.ibb.co/XLHwccH/08b166cc5426abb3.jpg" height="90" width="100%">
<img src="https://i.imgur.com/dBaSKWF.gif" height="90" width="100%">

<p align="center">
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=700&size=33&pause=1000&color=5513F7&width=435&lines=ROWDY+MD+WHATSAPP+BOT" alt="Typing SVG" /></a>
</p>
<p align="center">
<a href="https://github.com/Rowdykaryek/">
     <img src="https://i.imgur.com/dBaSKWF.gif" height="90" width="100%">
   
<img src="https://i.ibb.co/BBMJK88/3fbcd0b9bc23eb4e.jpg"  width="700px">
</a>
<hr>


<p align="center">

  <a href="https://github.com/Rowdykaryek/ROWDY">
    <img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FVaRowdy karyek%2FROWDY&count_bg=%2379C83D&title_bg=%23555555&icon=gitpod.svg&icon_color=%23E7E7E7&title=Views&edge_flat=false" alt="Views"/></a>
  
  </a>
  <a href="https://github.com/Rowdykaryek/ROWDY/fork">
    <img src="https://img.shields.io/github/forks/Rowdykaryek/ROWDY?label=Fork&style=social">
    
  </a>
  <a href="https://github.com/Rowdykaryrk/ROWDY/stargazers">
    <img src="https://img.shields.io/github/stars/Rowdykaryek/ROWDY?style=social">
  </a>
</p>

<p align="center">
  <a href="https://github/Rowdykaryek/ROWDY">
    <img src="https://img.shields.io/github/repo-size/Rowdykaryek/ROWDY?color=purple&label=Repo%20Size&style=plastic">

  </a>
  <a href="https://github.com/Rowdykaryek/ROWDY">
    <img src="https://img.shields.io/github/license/Rowdykaryek/ROWDY?color=purple&label=License&style=plastic">

  </a>
  <a href="https://github.com/Rowdykaryek/ROWDY">
    <img src="https://img.shields.io/github/languages/top/Rowdykaryek/ROWDY?color=purple&label=Javascript&style=plastic">

  </a>
  <a href="https://github.com/Rowdykayek/ROWDY">
    <img src="https://img.shields.io/static/v1?label=Author&message=Vajira%20Rathnayake&color=purple&style=plastic">

  </a>
  </p>
 <p align="center">
  <a href="https://github.com/Rowdykaryek/ROWDY">
    <img src="https://img.shields.io/badge/OUR%20%20%20TEAM-Technical%20Cybers%20(TC)-purple&style=plastic">

  </a>
</p>

## 💡 FOLLOW OUR CHANNELS

<a href="https://whatsapp.com/channel/0029Vb3930A4IBhEddCmjD0U"><img src="https://img.shields.io/badge/Join%20Our%20WhatsApp%20Channel-blue" alt="📎 Join Our WhatsApp Channel" width="350"></a>

<a href="https://youtube.com/@cyberrowdy-e4p?si=jY5rSnSkLESNzs_-"><img src="https://img.shields.io/badge/Subscribe%20My%20Youtube%20Channel-red" alt="📎 Subscribe My Youtube Channel" width="350"></a>

<a href="https://wa.me/message/TVV5ALKIG3AXO1"><img src="https://img.shields.io/badge/NOW_MSG%20My%20Whatshapp %20accounts-white" alt="📎 Now massg my whatshapp accounts" width="350"></a>
<br>

<div align="center">
 
  <h1> 🇲🇪👾 𝐃𝐄𝐏𝐋𝐎𝐘 𝐍𝐎𝐖 👾🇲🇪 </h1>
</div>

<br>


##  🏴‍☠️💀𝐃𝐄𝐏𝐋𝐎𝐘 𝐌𝐄𝐓𝐇𝐎𝐃𝐒☠️🏴‍☠️

<a href="https://tdd-gangs.github.io/Deployme"><img src="https://img.shields.io/badge/DEPLOYMENT%20METHODS-green" alt="DEPLOY PLATFORMS" width="300"></a>
<br>


<div align="center">
 
  <h1>😍👀 HEY GUYS.. WATCH DEPLOYMENT VIDEOS👇</h1>
</div>






































]




## Workflow Deploy Code 👇


```
name: Node.js CI

on:
  push:
    branches:
      - main
  pull_request:
    branches:
      - main

jobs:
  build:

    runs-on: ubuntu-latest

    strategy:
      matrix:
        node-version: [20.x]

    steps:
    - name: Checkout repository
      uses: actions/checkout@v3

    - name: Set up Node.js
      uses: actions/setup-node@v3
      with:
        node-version: ${{ matrix.node-version }}

    - name: Install dependencies
      run: npm install

    - name: Start application
      run: npm start
```
