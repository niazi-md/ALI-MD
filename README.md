![WELLCOME](Shaban/wellcome.svg)
  
______

[![Niazi-MD](https://raw.githubusercontent.com/MRSHABAN45/SHABAN-MD/main/Shaban/mr.svg)](https://whatsapp.com/channel/0029Vb6irPDK0IBefE82ZE2e)
___ 

<p align="center">
  <a href="https://github.com/NIAZI-MD" target="_blank">
    <img src="./Shaban/dev-gold-mini.svg" width="300" alt="Developer — NIAZI-MD (Gold 3D)">
  </a>
</p>

  
<p align="center">
  <a href="https://whatsapp.com/channel/0029Vb6irPDK0IBefE82ZE2e" target="_blank">
    <img src="./Shaban/channel-update.svg" width="350" alt="Bot Updating — WhatsApp Channel | Join Fast">
  </a>
</p>

---------

## 📞 Contact Information

- **Owner Name:** NIAZI-MD
- **Owner Number:** +92 370 3860715

## 🔗 Important Links

### 📢 Official Channel
- **Channel Link:** https://whatsapp.com/channel/0029Vb6irPDK0IBefE82ZE2e

### 👥 Official Group
- **Group Link:** https://chat.whatsapp.com/Bhrdmfqt9PuJAeZHpHQ3P7

---------

<p align="center">
<a href="https://github.com/NIAZI-MD/NIAZI-MD"><img title="PUBLIC-BOT" src="https://img.shields.io/static/v1?label=Language&message=JavaScript&style=square&color=darkpink"></a> &nbsp;
  <img src="https://komarev.com/ghpvc/?username=NIAZI-MD&label=VIEWS&style=square&color=blue" />
</p>


-------------

<p align="center">
<img src="Shaban/feature-bot.svg" alt="Feature Bot" width="900"/>
  
<p align="center">
<img src="Shaban/license.svg" alt="License" width="200"/>

--------------

<p align="center">
<img src="Shaban/maintenance.svg" alt="Maintenance" width="120"/>


 <p align="center">
  <a href="https://github.com/NIAZI-MD/NIAZI-MD/fork" target="_blank">
    <img src="Shaban/forkstar-holo.svg" width="180" alt="Fork Star Bot Repo"/>
  </a>
</p>


<p align="center">
  <a href="https://smd-pair.zone.id/" target="_blank">
    <img src="./Shaban/paircode-link.svg" width="195" alt="PAIR_CODE – Device Session ID">
  </a>
</p>

-------------

<p align="center">
  <img src="./Shaban/deployment.svg" width="600" alt="NIAZI MD — News Ticker Typing">
</p>

<div align="center">
  <table>
    <tr>
      <td><a href="https://dashboard.heroku.com/new-app?template=https://github.com/NIAZI-MD/NIAZI-MD" target="_blank"><img src="https://img.shields.io/badge/Heroku-430098?style=for-the-badge&logo=heroku&logoColor=white&labelColor=000000&color=0000FF"/></a></td>
      <td><a href="https://niazi.lovestoblog.com/" target="_blank"><img src="https://img.shields.io/badge/official-site-A52A2A?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=000000"/></a></td>
    </tr>
    <tr>
      <td><a href="https://www.niazi-bomber.zone.id/" target="_blank"><img src="https://img.shields.io/badge/SMS-BOMBER-FF009D?style=for-the-badge&logo=firefoxbrowser&logoColor=white&labelColor=000000"/></a></td>
      <td><a href="https://railway.app/new" target="_blank"><img src="https://img.shields.io/badge/Railway-000080?style=for-the-badge&logo=railway&logoColor=white&labelColor=000000"/></a></td>
    </tr>
    <tr>
      <td><a href="https://github.com/NIAZI-MD/NIAZI-Render" target="_blank"><img src="https://img.shields.io/badge/Render-000000?style=for-the-badge&logo=render&logoColor=white&labelColor=000000&color=FFFF00"/></a></td>
      <td><a href="https://niazi-free-host.zone.id/" target="_blank"><img src="https://img.shields.io/badge/Free-host-CC00FF?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=000000"/></a></td>
    </tr>
  </table>
</div>

<table align="center">
  <tr>
    <td>
      <a href="https://github.com/NIAZI-MD/NIAZI-Render" target="_blank">
        <img alt="Deploy From Render" src="https://img.shields.io/badge/Deploy-Only%20Render%20Repo-4CAF50?style=for-the-badge&logo=render&logoColor=white"/>
      </a>
    </td>
  </tr>
</table>  

-------------

**_✠ FREE DEPLOYMENT OF NIAZI MD GITHUB WORKFLOW CODE NEW ADD ERROR FIXED ✠_**

```yaml
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
        node-version: [20.x]   # Specific Node.js version set to 20.x

    steps:
    - name: Checkout repository
      uses: actions/checkout@v3

    - name: Set up Node.js
      uses: actions/setup-node@v3
      with:
        node-version: ${{ matrix.node-version }}
        check-latest: true   # Always grab the exact latest patch for this version

    - name: Install dependencies
      run: npm install

    - name: Build project (optional)
      run: npm run build || echo "No build script found, skipping..."

    - name: Start application
      run: npm start
