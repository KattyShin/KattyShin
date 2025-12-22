<style>
  :root {
    --pink-primary: #ff69b4;
    --pink-secondary: #ffb6c1;
    --pink-light: #ffecf1;
    --pink-dark: #d1478c;
    --pink-gradient: linear-gradient(135deg, #ff69b4, #ffb6c1);
  }
  
  body {
    background-color: #fff0f5;
    color: #333;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  }
  
  h1, h2, h3, h4 {
    color: var(--pink-primary);
    position: relative;
    display: inline-block;
  }
  
  h1:after, h2:after, h3:after {
    content: '';
    position: absolute;
    bottom: -5px;
    left: 0;
    width: 100%;
    height: 3px;
    background: var(--pink-gradient);
    border-radius: 3px;
  }
  
  a {
    color: var(--pink-dark);
    text-decoration: none;
    transition: all 0.3s ease;
    position: relative;
  }
  
  a:hover {
    color: var(--pink-primary);
    text-decoration: none;
  }
  
  a:after {
    content: '';
    position: absolute;
    bottom: -2px;
    left: 0;
    width: 0;
    height: 2px;
    background: var(--pink-gradient);
    transition: width 0.3s ease;
  }
  
  a:hover:after {
    width: 100%;
  }
  
  .container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
  }
  
  .pink-divider {
    height: 3px;
    background: var(--pink-gradient);
    margin: 30px 0;
    border-radius: 3px;
    border: none;
  }
  
  .pink-box {
    background: white;
    border-radius: 15px;
    padding: 20px;
    margin: 20px 0;
    box-shadow: 0 4px 15px rgba(255, 105, 180, 0.1);
    border-left: 5px solid var(--pink-primary);
  }
  
  .icon-wrapper {
    background: var(--pink-light);
    border-radius: 50%;
    padding: 10px;
    display: inline-flex;
    align-items: center;
    justify-content: center;
    transition: all 0.3s ease;
    margin: 5px;
  }
  
  .icon-wrapper:hover {
    background: var(--pink-gradient);
    transform: translateY(-3px);
    box-shadow: 0 5px 15px rgba(255, 105, 180, 0.3);
  }
  
  .tool-icon {
    transition: all 0.3s ease;
  }
  
  .icon-wrapper:hover .tool-icon {
    filter: brightness(0) invert(1);
  }
  
  .stats-container {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
  }
  
  .stats-card {
    background: white;
    border-radius: 15px;
    padding: 20px;
    flex: 1;
    min-width: 300px;
    box-shadow: 0 4px 15px rgba(255, 105, 180, 0.1);
    text-align: center;
  }
  
  .highlight {
    background: linear-gradient(120deg, var(--pink-light) 0%, var(--pink-light) 100%);
    background-repeat: no-repeat;
    background-size: 100% 0.4em;
    background-position: 0 88%;
    transition: background-size 0.25s ease-in;
    padding: 0 5px;
  }
  
  .highlight:hover {
    background-size: 100% 88%;
  }
  
  .badge {
    display: inline-block;
    padding: 5px 15px;
    background: var(--pink-gradient);
    color: white;
    border-radius: 20px;
    font-size: 0.9em;
    margin: 5px;
    font-weight: bold;
  }
  
  .profile-header {
    text-align: center;
    padding: 40px 20px;
    background: white;
    border-radius: 20px;
    margin-bottom: 30px;
    box-shadow: 0 10px 30px rgba(255, 105, 180, 0.1);
  }
  
  .emoji {
    font-size: 1.2em;
    margin-right: 5px;
  }
</style>

<div class="container">

<div class="profile-header">
  <h1 align="center">🌸 Hi there! I'm Katrina Shin 🌸</h1>
  <h3 align="center">💻 Aspiring Developer | 🌱 Always Learning & Growing</h3>
  
  <p align="center" style="font-size: 1.1em; color: #666; max-width: 800px; margin: 20px auto;">
    Passionate about building <span class="highlight">user-friendly applications</span> and continuously expanding my technical skills. 
    I believe in creating elegant solutions to complex problems. ✨
  </p>
</div>

<hr class="pink-divider">

## 🎀 About Me

<div class="pink-box">
  <p>I'm a motivated developer with a keen eye for detail and a passion for creating intuitive digital experiences. 
  Whether it's <span class="highlight">front-end magic</span> or <span class="highlight">back-end logic</span>, I enjoy every step of the development journey.</p>
  
  <p>When I'm not coding, you can find me:</p>
  <ul>
    <li>📚 Learning new technologies and frameworks</li>
    <li>🎨 Exploring UI/UX design principles</li>
    <li>☕ Experimenting with coffee brewing techniques</li>
    <li>📷 Capturing moments through photography</li>
  </ul>
</div>

<hr class="pink-divider">

## 📄 Experience & Background

<div class="pink-box">
  <p>I'm constantly seeking opportunities to grow and contribute to meaningful projects. 
  My journey is just beginning, and I'm excited about where it will lead! 🚀</p>
  
  <p>
    <span class="badge">Resume</span> 
    <a href="https://docs.google.com/document/d/1DoIpDrdzq37F5KOIJ0Y8w6XUmy8_TVbqATc3829aIk8/edit?usp=sharing" target="_blank">
      👉 View my resume here
    </a>
  </p>
  
  <p style="margin-top: 15px;">
    💌 <strong>Open to:</strong> Internships • Collaborations • Learning Opportunities
  </p>
</div>

<hr class="pink-divider">

## 🤝 Connect With Me

<p align="center">
  <a href="https://www.linkedin.com/in/katrina-shin-caballes-6a32b9306/" target="_blank" style="display: inline-flex; align-items: center; margin: 0 15px;">
    <div class="icon-wrapper">
      <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" 
           alt="LinkedIn - Katrina Shin Caballes" height="30" width="40" />
    </div>
    <span style="margin-left: 8px; font-weight: bold;">LinkedIn</span>
  </a>
  
  <a href="mailto:katrina.shin@example.com" target="_blank" style="display: inline-flex; align-items: center; margin: 0 15px;">
    <div class="icon-wrapper">
      <img src="https://img.icons8.com/color/48/000000/gmail.png" alt="Email" height="30" width="40" />
    </div>
    <span style="margin-left: 8px; font-weight: bold;">Email</span>
  </a>
  
  <a href="https://github.com/kattyshin" target="_blank" style="display: inline-flex; align-items: center; margin: 0 15px;">
    <div class="icon-wrapper">
      <img src="https://img.icons8.com/fluent/48/000000/github.png" alt="GitHub" height="30" width="40" />
    </div>
    <span style="margin-left: 8px; font-weight: bold;">GitHub</span>
  </a>
</p>

<hr class="pink-divider">

## 🛠️ Languages & Tools

<div style="text-align: center;">
  <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 15px; margin: 20px 0;">
    <a href="https://www.w3schools.com/cpp/" target="_blank">
      <div class="icon-wrapper">
        <img class="tool-icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" width="40" height="40"/>
      </div>
    </a>
    <a href="https://www.w3schools.com/css/" target="_blank">
      <div class="icon-wrapper">
        <img class="tool-icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" width="40" height="40"/>
      </div>
    </a>
    <a href="https://www.djangoproject.com/" target="_blank">
      <div class="icon-wrapper">
        <img class="tool-icon" src="https://cdn.worldvectorlogo.com/logos/django.svg" width="40" height="40"/>
      </div>
    </a>
    <a href="https://flask.palletsprojects.com/" target="_blank">
      <div class="icon-wrapper">
        <img class="tool-icon" src="https://www.vectorlogo.zone/logos/pocoo_flask/pocoo_flask-icon.svg" width="40" height="40"/>
      </div>
    </a>
    <a href="https://www.figma.com/" target="_blank">
      <div class="icon-wrapper">
        <img class="tool-icon" src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" width="40" height="40"/>
      </div>
    </a>
    <a href="https://www.w3.org/html/" target="_blank">
      <div class="icon-wrapper">
        <img class="tool-icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" width="40" height="40"/>
      </div>
    </a>
    <a href="https://www.java.com/" target="_blank">
      <div class="icon-wrapper">
        <img class="tool-icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" width="40" height="40"/>
      </div>
    </a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank">
      <div class="icon-wrapper">
        <img class="tool-icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="40" height="40"/>
      </div>
    </a>
    <a href="https://www.mongodb.com/" target="_blank">
      <div class="icon-wrapper">
        <img class="tool-icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" width="40" height="40"/>
      </div>
    </a>
    <a href="https://nodejs.org/" target="_blank">
      <div class="icon-wrapper">
        <img class="tool-icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" width="40" height="40"/>
      </div>
    </a>
    <a href="https://www.postgresql.org/" target="_blank">
      <div class="icon-wrapper">
        <img class="tool-icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" width="40" height="40"/>
      </div>
    </a>
    <a href="https://www.python.org/" target="_blank">
      <div class="icon-wrapper">
        <img class="tool-icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="40" height="40"/>
      </div>
    </a>
    <a href="https://reactjs.org/" target="_blank">
      <div class="icon-wrapper">
        <img class="tool-icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" width="40" height="40"/>
      </div>
    </a>
    <a href="https://reactnative.dev/" target="_blank">
      <div class="icon-wrapper">
        <img class="tool-icon" src="https://reactnative.dev/img/header_logo.svg" width="40" height="40"/>
      </div>
    </a>
    <a href="https://tailwindcss.com/" target="_blank">
      <div class="icon-wrapper">
        <img class="tool-icon" src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" width="40" height="40"/>
      </div>
    </a>
    <a href="https://www.typescriptlang.org/" target="_blank">
      <div class="icon-wrapper">
        <img class="tool-icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" width="40" height="40"/>
      </div>
    </a>
  </div>
</div>

<hr class="pink-divider">

## 📊 GitHub Stats

<div class="stats-container">
  <div class="stats-card">
    <h4>📈 GitHub Statistics</h4>
    <img src="https://github-readme-stats.vercel.app/api?username=kattyshin&show_icons=true&locale=en&theme=radical&bg_color=fff0f5&title_color=ff69b4&icon_color=ff69b4&text_color=333&border_color=ffb6c1" 
         alt="GitHub Stats" style="width: 100%;" />
  </div>
  
  <div class="stats-card">
    <h4>💬 Top Languages</h4>
    <img src="https://github-readme-stats.vercel.app/api/top-langs?username=kattyshin&show_icons=true&locale=en&layout=compact&theme=radical&bg_color=fff0f5&title_color=ff69b4&text_color=333&border_color=ffb6c1" 
         alt="Top Languages" style="width: 100%;" />
  </div>
</div>

<div style="text-align: center; margin-top: 30px;">
  <h4>🏆 GitHub Trophies</h4>
  <img src="https://github-profile-trophy.vercel.app/?username=kattyshin&margin-w=15&margin-h=15&theme=radical&no-bg=true&no-frame=true&row=2&column=4" 
       alt="GitHub Trophies" style="width: 100%; max-width: 800px;" />
</div>

<hr class="pink-divider">

## 🌸 Currently Learning

<div class="pink-box" style="text-align: center;">
  <p>
    <span class="badge">React Native</span>
    <span class="badge">TypeScript</span>
    <span class="badge">Node.js</span>
    <span class="badge">Tailwind CSS</span>
    <span class="badge">MongoDB</span>
  </p>
  <p style="margin-top: 15px; font-style: italic;">
    "The only way to do great work is to love what you do." – Steve Jobs
  </p>
</div>

<hr class="pink-divider">

<footer style="text-align: center; padding: 20px; color: #666; font-size: 0.9em;">
  <p>🌸 Thank you for visiting my profile! 🌸</p>
  <p>Have a wonderful day! ✨</p>
  <p style="margin-top: 10px;">
    <small>Last updated: November 2023</small>
  </p>
</footer>

</div>
