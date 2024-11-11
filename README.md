<style>
:root {
  --primary-color: #6C5CE7; 
  --secondary-color: #FFA500; 
  --accent-color: #00B894;
  --background-color: #F5F6FA;
  --text-color: #2D3436;
  --contribution-level-0: #ebedf0; 
  --contribution-level-1: #c6e48b; 
  --contribution-level-2: #7bc96f; 
  --contribution-level-3: #239a3b; 
  --contribution-level-4: #196127;
}

body {
  font-family: 'Montserrat', sans-serif;
  background-color: var(--background-color);
  color: var(--text-color);
  margin: 0;
  padding: 0;
}

header {
  background-color: var(--primary-color);
  color: white;
  padding: 2rem;
  text-align: center;
}

h1 {
  font-size: 3rem;
  margin-bottom: 0.5rem;
}


main {
  max-width: 800px;
  margin: 2rem auto;
  padding: 0 1rem;
}

h2 {
  color: var(--secondary-color);
  font-size: 2rem;
  margin-top: 2rem;
}

p {
  line-height: 1.6;
}


.tool-icon {
  width: 50px;
  height: 50px;
  margin: 1rem 1rem 0 0;
  filter: drop-shadow(0 0 0.25rem rgba(0, 0, 0, 0.1));
  transition: transform 0.3s ease-in-out;
}

.tool-icon:hover {
  transform: scale(1.1);
}


.github-stats {
  display: flex;
  justify-content: center;
  margin-top: 2rem;
}

.github-stats img {
  max-width: 100%;
  height: auto;
  border-radius: 8px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.ContributionCalendar-day[data-level="0"] {
  background-color: var(--contribution-level-0);
}
.ContributionCalendar-day[data-level="1"] {
  background-color: var(--contribution-level-1);
}
.ContributionCalendar-day[data-level="2"] {
  background-color: var(--contribution-level-2);
}
.ContributionCalendar-day[data-level="3"] {
  background-color: var(--contribution-level-3);
}
.ContributionCalendar-day[data-level="4"] {
  background-color: var(--contribution-level-4);
}
</style>

<header>
  <h1>🔱 Souhail Bektachi</h1>
  <p>Software Engineering Student | Digital Solution Crafter</p>
</header>

<main>
  <section>
    <h2>🪷 Hello, World!</h2>
    <p>Greetings! I'm a dedicated Software Engineering student with a passion for crafting innovative digital solutions. Currently honing my skills in software development, I have a proven track record of translating ideas into fully functional applications. Welcome to my GitHub profile, where I showcase a variety of projects and contributions.</p>
  </section>

  <section>
    <h2>🔧 Languages & Tools</h2>
    <div>
      <img class="tool-icon" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/angularjs/angularjs-plain.svg" alt="Angular" />
      <img class="tool-icon" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript" />
      <img class="tool-icon" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" alt="TypeScript" />
      <img class="tool-icon" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sdl/sdl-original.svg" alt="SDL" />
      <img class="tool-icon" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" alt="C" />
      <img class="tool-icon" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" />
      <img class="tool-icon" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original-wordmark.svg" alt="HTML5" />
      <img class="tool-icon" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS3" />
      <img class="tool-icon" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original-wordmark.svg" alt="Tailwind CSS" />
      <img class="tool-icon" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" alt="PHP" />
      <img class="tool-icon" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="Java" />
      <img class="tool-icon" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original-wordmark.svg" alt="Go" />
    </div>
  </section>

  <section>
    <h2>🕉️ GitHub Stats</h2>
    <div class="github-stats">
      <img src="https://github-readme-stats.vercel.app/api?username=souhailBektachi&show_icons=true&theme=cobalt" alt="Anurag's GitHub stats" />
    </div>
  </section>
</main>
