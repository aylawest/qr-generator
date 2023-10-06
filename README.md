<div align="center">
  <!-- LOGO -->
  <a href="" id="projectname"><img src="/public//logo.png" style="width: 240px" /></a>
  
  <!-- TAGLINE -->
  <p>A quick QR code generator to simplify link sharing.</p>

  <!-- BADGES -->
  [![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/) [![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-red.svg)](https://opensource.org/licenses/) ![Netlify](https://img.shields.io/netlify/e6d5a4e0-dee1-4261-833e-2f47f509c68)

  <!-- LIVE DEMO -->
  <a href="http://" class="navlinks" target="_blank">http://www.qr-generator-arw.netlify.app</a>
</div>

##

<!-- TYPE OF PROJECT -->
[!["Frontend"](https://img.shields.io/badge/Frontend-✔-green)](/README-frontend.md) [!["Backend"](https://img.shields.io/badge/Backend-✘-red)](/README-backend.md)
  
<!-- TABLE OF CONTENTS -->
<details>
  <summary><strong>Table of Contents</strong></summary>
  <ol>
    <li><a href="#description">Description</a></li>
    <li><a href="#how-to-use">How to use</a></li>
    <li><a href="#how-to-install">How to run/install</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#install">Install</a></li>
      </ul>
    </li>
    <li><a href="#client">Client</a>
      <ul>
        <li><a href="#structure">Structure</a></li>
        <li><a href="#built-with">Built with</a></li>
        <li><a href="#data-flow">Data flow</a></li>
        <li><a href="#dependencies">Dependencies</a></li>
        <li><a href="#optimizations">Optimizations</a></li>
      </ul>
    </li>
    <li><a href="/README-backend.md">Server</a>
      <ul>
        <li><a href="/README-backend.md#structure">Structure</a></li>
        <li><a href="/README-backend.md#built-with">Built with</a></li>
        <li><a href="/README-backend.md#data-flow">Data flow</a></li>
        <li><a href="/README-backend.md#dependencies">Dependencies</a></li>
        <li><a href="/README-backend.md#optimizations">Optimizations</a></li>
      </ul>
    </li>
    <li><a href="#future-updates">Future updates</a></li>
    <li><a href="#lessons-learned">Lessons learned</a></li>
    <li><a href="#contributions">Contributions</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>

<!-- MAIN IMAGE -->
<img src="https://static.wixstatic.com/media/ea6ac8_b6b0cbe25615488e855f515846354dda~mv2.jpg/v1/fill/w_640,h_420,al_c,q_80,usm_0.66_1.00_0.01,enc_auto/ea6ac8_b6b0cbe25615488e855f515846354dda~mv2.jpg" alt="Markdown Monster icon" style="width: 100%" /> 

<!-- PROJECT DESCRIPTION -->
<h1 id="client">Frontend Project Overview</h1>

The portion of the web application that a user sees and interacts with.

<!-- SCOPE -->
<details>
  <summary><strong>Scope</strong></summary>
  <details>
    <summary>Goals</summary>
    goal
  </details>
  <details>
    <summary>Deliverables</summary>
    deliverables
  </details>
  <details>
    <summary>Features</summary>
    features
  </details>
  <details>
    <summary>Limitations</summary>
    limitations
  </details> 
  <details>
    <summary>Compatibility</summary>
    compatibility
  </details>
  <details>
    <summary>Timeline</summary>
    timeline
  </details>  
  <details>
    <summary>Project Methodology</summary>
    agile
  </details> 
  <details>
    <summary>Risks</summary>
    risks
  </details>  
  <details>
    <summary>Costs</summary>
    costs
  </details> 
</details>

<div align="right">
  <a href="#projectname">&#129121;</a>
</div>

<!-- CLIENT - TECHNOLOGY -->
<h2 id="technology">Technology</h2>

![Javascript](https://img.shields.io/badge/JavaScript-black?style=for-the-badge&logo=javascript&logoColor=F7DF1E) ![Astro](https://img.shields.io/badge/Astro-743cb0?style=for-the-badge&logo=astro&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-e36817?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1067e0?&style=for-the-badge&logo=css3&logoColor=white) 

<!-- CLIENT - WHY THIS TECH STACK -->
<details>
  <summary><strong>Why this stack?</strong></summary>
  Because it's the best.
</details>

<!-- CLIENT - OTHER TECH STACK CONSIDERATIONS -->
<details>
  <summary><strong>Other considerations</strong></summary>
  <ul>
    <li><strong>Vue</strong> Because it's nice too.</li>
    <li><strong>MongoDB</strong> Because it's nice too.</li>
  </ul>
</details>

<!-- CLIENT - DENDENCIES -->
<h3 id="dependencies">Dependencies</h3>

- None

<div align="right">
  <a href="#projectname">&#129121;</a>
</div>

<!-- HOW TO USE THE PROJECT -->
<h2 id="how-to-use"><a>How to use</a></h2>

Live demo: <http://www.qr-generator-arw.netlify.app>  
_or_  
Run locally:  

```javascript
import Component from 'my-project'

function App() {
  return <Component />
}
```

<div align="right">
  <a href="#projectname">&#129121;</a>
</div>

<!-- HOW TO INSTALL THE PROJECT -->
<h2 id="how-to-install">How to install</h2>

Install my-project with npm

```bash
  npm install my-project
  cd my-project
```

<!-- PREREQUISITES -->
<h3 id="prerequisites">Prerequisites</h3>

```bash
  npm install npm@latest -g
```

<!-- INSTALL -->
<h3 id="install">Install</h3>

Navigate to the client directory and run: `yarn`.  
Navigation to the server directory and run: `yarn`.  
Navigate to the root directory and run: `yarn start`. This will spin up both the client and the server on the same process.  
Run tests with: `yarn test` in either sub-directory.

<div align="right">
  <a href="#projectname">&#129121;</a>
</div>

<!-- CLIENT - FOLDER STRUCTURE -->
<h2 id="structure">Structure</h2>

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Card.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

<div align="right">
  <a href="#projectname">&#129121;</a>
</div>

<!-- CLIENT - DATA FLOW -->
<h2 id="data-flow">Data flow</h2>

<img src="https://wcs.smartdraw.com/flowchart/img/flowchart-programming.png?bn=15100111875" style="width: 100%;" />
and description of data flowing through steps?

<div align="right">
  <a href="#projectname">&#129121;</a>
</div>

<!-- CLIENT - OPTIMIZATIONS -->
<h2 id="optimizations">Optimizations</h2>

Interviewers love that you can not only deliver a final product that looks great but also functions efficiently. Did you write something then refactor it later and the result was 5x faster than the original implementation? Did you cache your assets? Things that you write in this section are GREAT to bring up in interviews and you can use this section as reference when studying for technical interviews!

<div align="right">
  <a href="#projectname">&#129121;</a>
</div>

<!-- FUTURE UPDATES -->
<h2 id="future-updates">Future updates</h2>

- [x]  One
- [ ]  Two
  - [ ]  Two a
  - [ ]  Two b
- [ ]  One

See the [open issues](http://link) for a full list of proposed features (and known issues).

<div align="right">
  <a href="#projectname">&#129121;</a>
</div>

<!-- LESSONS LEARNED -->
<h2 id="lessons-learned">Lessons learned</h2>

What did you learn while building this project? What challenges did you face and how did you overcome them?

<div align="right">
  <a href="#projectname">&#129121;</a>
</div>

<!-- CONTRIBUTIONS -->
<h2 id="contributions">Contributions</h2>

This portfolio is a personal project and not open for contributions. It represents my individual work and achievements.

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement". Don't forget to give the project a star! Thanks again!  

Fork the Project  
Create your Feature Branch (`git checkout -b feature/AmazingFeature`)  
Commit your Changes (`git commit -m 'Add some AmazingFeature'`)  
Push to the Branch (`git push origin feature/AmazingFeature`)  
Open a Pull Request

<div align="right">
  <a href="#projectname">&#129121;</a>
</div>

<!-- ACKNOWLEDGEMENTS -->
<h2 id="acknowledgements">Acknowledgements</h2>

- [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
- [Awesome README](https://github.com/matiassingers/awesome-readme)
- [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)

<div align="right">
  <a href="#projectname">&#129121;</a>
</div>

<!-- LICENSE -->
<h2 id="license">License</h2>

There is no active license for this portfolio. If you want to use parts of the code or content, please reach out to me for permission.

[MIT](https://choosealicense.com/licenses/mit/)
 
Distributed under the MIT License. See `LICENSE.txt` for more information.

<h2></h2>

Alyssa Weiglein &copy; 2023 &#8212; &infin; 
 
<!-- CONTACT -->
[!["Buy Me A Coffee"](https://img.shields.io/badge/Buy_Me_A_Coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://www.buymeacoffee.com/gbraad) [![Linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alyssaweiglein) [![Linkedin](https://img.shields.io/badge/github-007?style=for-the-badge&logo=github&logoColor=white)](https://www.github.com/alyssaweiglein) ![Discord](https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white)