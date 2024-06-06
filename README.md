<html>
<head>
  <link href="https://fonts.googleapis.com/css?family=Montserrat|Lato&display=swap" rel="stylesheet">
  <style>
    body {
      background-color: #f4f4f9;
      color: #2c3e50;
      font-family: 'Lato', sans-serif;
    }

    .header-title {
      font-family: 'Montserrat', sans-serif;
      color: #2c3e50;
      text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
      white-space: nowrap;
      overflow: hidden;
      border-right: 3px solid;
      animation: typing 4s steps(30, end), blink-caret 0.75s step-end infinite;
    }

    @keyframes typing {
      from { width: 0; }
      to { width: 100%; }
    }

    @keyframes blink-caret {
      from, to { border-color: transparent; }
      50% { border-color: #2c3e50; }
    }

    .sub-header {
      font-family: 'Lato', sans-serif;
      color: #7f8c8d;
    }

    .animated {
      animation-duration: 1s;
      animation-fill-mode: both;
    }

    .zoomIn {
      animation-name: zoomIn;
    }

    .pulse {
      animation-name: pulse;
    }

    .social-icon, .tech-icon {
      margin: 0 100px; /* Add some spacing between icons */
      transition: transform 0.3s;
    }

    .social-icon:hover, .tech-icon:hover {
      transform: scale(1.2);
    }

    @keyframes zoomIn {
      from {
        opacity: 0;
        transform: scale3d(0.3, 0.3, 0.3);
      }
      50% {
        opacity: 1;
      }
    }

    @keyframes pulse {
      0% {
        transform: scale(1);
      }
      50% {
        transform: scale(1.2);
      }
      100% {
        transform: scale(1);
      }
    }

    .info-item {
      margin: 10px 0;
      font-size: 1.2em;
    }

    .info-item b {
      color: #2980b9;
    }

    .info-item span {
      display: inline-block;
      animation: typing 4s steps(30, end), blink-caret 0.75s step-end infinite;
    }

    h3 {
      margin-top: 40px;
    }

    .footer {
      margin-top: 40px;
    }
    
  }
  </style>
</head>
<body>
  <h1 align="center" class="header-title">Hi 👋, I'm Srikanth</h1>
  <h3 align="center" class="sub-header">An Enthusiastic Full Stack developer</h3>

  <p align="center"> <img src="https://komarev.com/ghpvc/?username=srii2002&label=Profile%20views&color=0e75b6&style=flat" alt="srii2002" /> </p>

  <p align="center">
    <img src="https://media.giphy.com/media/ZVik7pBtu9dNS/giphy.gif" width="600px" class="animated zoomIn" />
  </p>

  <div align="center">
    <div class="info-item">🔭 I’m currently working on <span><img src="https://media.giphy.com/media/LMcB8XospGZO8UQq87/giphy.gif" width="20" class="animated pulse infinite"> <b>React.js projects</b></span></div>
    <div class="info-item">🌱 I’m currently learning <span><img src="https://media.giphy.com/media/SWoSkN6DxTszqIKEqv/giphy.gif" width="20" class="animated pulse infinite"> <b>MongoDB and Express.js</b></span></div>
    <div class="info-item">💬 Ask me about <span><img src="https://media.giphy.com/media/f3iwJFOVOwuy7K6FFw/giphy.gif" width="20" class="animated pulse infinite"> <b>React.js, HTML, CSS, JavaScript, Node.js</b></span></div>
    <div class="info-item">📫 How to reach me <span><img src="https://media.giphy.com/media/jt7bAtEijhurm/giphy.gif" width="20" class="animated pulse infinite"> <b>srikanthka03@gmail.com</b></span></div>
    <div class="info-item">📄 Know about my experiences <span><img src="https://media.giphy.com/media/Y4ak9Ki2GZCbJxAnJD/giphy.gif" width="20" class="animated pulse infinite"> <b>Intern at Prodigy Infotech</b></span></div>
  </div>

  <h3 align="center">Connect with me:</h3>
  <p align="center">
    <a href="https://www.linkedin.com/in/srikanth-k-a-18563530a" target="_blank">
      <img src="https://www.vectorlogo.zone/logos/linkedin/linkedin-icon.svg" alt="LinkedIn" width="40" height="40" class="social-icon animated pulse infinite"/>
    </a>
    <span style="margin: 0 10px;"></span>
    <a href="https://www.instagram.com/_.srii_.18/" target="_blank">
      <img src="https://www.vectorlogo.zone/logos/instagram/instagram-icon.svg" alt="Instagram" width="40" height="40" class="social-icon animated pulse infinite"/>
    </a>
  </p>

  <h3 align="center">Languages:</h3>
  <p align="center">
    <a href="https://www.w3schools.com/c/" target="_blank" rel="noreferrer">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40" class="tech-icon animated zoomIn"/>
    </a>
    <span style="margin: 0 10px;"></span>
    <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40" class="tech-icon animated zoomIn"/>
    </a>
    <span style="margin: 0 10px;"></span>
    <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40" class="tech-icon animated zoomIn"/>
    </a>
    <span style="margin: 0 10px;"></span>
    <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40" class="tech-icon animated zoomIn"/>
    </a>
    <span style="margin: 0 10px;"></span>
    <a href="https://www.javascript.com/" target="_blank" rel="noreferrer">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40" class="tech-icon animated zoomIn"/>
    </a>
  </p>

  <h3 align="center">Tools:</h3>
  <p align="center">
    <a href="https://git-scm.com/" target="_blank" rel="noreferrer">
      <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40" class="tech-icon animated zoomIn"/>
    </a>
    <span style="margin: 0 10px;"></span>
    <a href="https://postman.com" target="_blank" rel="noreferrer">
      <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="postman" width="40" height="40" class="tech-icon animated zoomIn"/>
    </a>
  </p>

  <h3 align="center">Frameworks:</h3>
  <p align="center">
    <a href="https://getbootstrap.com" target="_blank" rel="noreferrer">
      <img src="https://upload.wikimedia.org/wikipedia/commons/b/b2/Bootstrap_logo.svg" alt="bootstrap" width="40" height="40" class="tech-icon animated zoomIn"/>
    </a>
    <span style="margin: 0 10px;"></span>
    <a href="https://expressjs.com" target="_blank" rel="noreferrer">
      <img src="https://www.vectorlogo.zone/logos/expressjs/expressjs-icon.svg" alt="express" width="40" height="40" class="tech-icon animated zoomIn"/>
    </a>
    <span style="margin: 0 10px;"></span>
    <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40" class="tech-icon animated zoomIn"/>
    </a>
    <span style="margin: 0 10px;"></span>
    <a href="https://nodejs.org" target="_blank" rel="noreferrer">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40" class="tech-icon animated zoomIn"/>
    </a>
    <span style="margin: 0 10px;"></span>
    <a href="https://reactjs.org/" target="_blank" rel="noreferrer">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40" class="tech-icon animated zoomIn"/>
    </a>
    <span style="margin: 0 10px;"></span>
    <a href="https://tailwindcss.com/" target="_blank" rel="noreferrer">
      <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="tailwind" width="40" height="40" class="tech-icon animated zoomIn"/>
    </a>
  </p>

  <p align="center"><img src="https://github-readme-stats.vercel.app/api/top-langs?username=srii2002&show_icons=true&locale=en&layout=compact" alt="srii2002" /></p>

  <p align="center"><img src="https://github-readme-streak-stats.herokuapp.com/?user=srii2002&" alt="srii2002" /></p>

  <div class="footer" align="center">
    <h3>Footer</h3>
    <p>
      <img src="https://media.giphy.com/media/j5pUwhPSUqB2w/giphy.gif" width="50px" class="animated pulse infinite" /> 
      Thank you for visiting my profile! 
      <img src="https://media.giphy.com/media/j5pUwhPSUqB2w/giphy.gif" width="50px" class="animated pulse infinite" />
    </p>
  </div>

   

</div>
</div>

  
</body>
</html>
