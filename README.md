<h1 align="center" style="font-size: 3.5rem; font-family: 'Source Code Pro', monospace; color: #39ff14; text-shadow: 0 0 5px #28b40e;">
  Hi 👋, I'm Vincenzo Amendola
</h1>

<h3 align="center" style="font-style: italic; color: #888; font-family: 'Source Code Pro', monospace;">
  A passionate backend developer from Brazil who also engages in data science.
</h3>


<div style="background: linear-gradient(to bottom, #222, #333); color: #eee; padding: 20px; border-radius: 10px; font-family: 'Source Code Pro', monospace; overflow-x: auto; margin: 20px auto; max-width: 800px; box-shadow: 0 5px 10px rgba(0,0,0,0.3);">
  <pre id="terminal">
<span class="prompt">vincenzo@portfolio:~$</span> whoami
<span class="output">Vincenzo Amendola - Backend Developer & Data Scientist</span>

<span class="prompt">vincenzo@portfolio:~$</span> contact
<span class="output-highlight">GitHub:</span> github.com/Vincenzo140
<span class="output-highlight">Email:</span> vincenzo.amendola141@gmail.com
<span class="output-highlight">LinkedIn:</span> linkedin.com/in/vincenzo%20amendola
  </pre>
</div>



<details style="margin: 20px 0; border-radius: 5px; overflow: hidden; box-shadow: 0 2px 5px rgba(0,0,0,0.1);">
  <summary style="font-family: 'Source Code Pro', monospace; color:#39ff14; cursor: pointer; padding: 10px 15px; background-color: #282c34; user-select: none; list-style: none;">
    <span style="color: #aaa;">></span> Skills & Tools 
  </summary>
  <div style="padding: 15px; background-color: #222;">
    <p align="center">
        <!-- Skill and Tool Icons -->
        <!--  Example:
         <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original-wordmark.svg" alt="Python" width="50" height="50" style="margin: 10px;"/> 
        -->
        <!-- Add all your skill/tool icons here -->
    </p>
  </div>
</details>

<details style="margin: 20px 0; border-radius: 5px; overflow: hidden; box-shadow: 0 2px 5px rgba(0,0,0,0.1);">
  <summary style="font-family: 'Source Code Pro', monospace; color:#39ff14; cursor: pointer; padding: 10px 15px; background-color: #282c34; user-select: none; list-style: none;">
    <span style="color: #aaa;">></span> GitHub Stats 
  </summary>
  <div style="padding: 15px; background-color: #222; text-align: center;">  
    <img src="https://github-readme-stats.vercel.app/api?username=Vincenzo140&show_icons=true&theme=radical" alt="GitHub Stats" width="48%" style="margin: 10px auto;"/>
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Vincenzo140&layout=compact&theme=radical" alt="Top Languages" width="48%" style="margin: 10px auto;"/>
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=Vincenzo140&theme=radical" alt="GitHub Streak" width="95%" style="margin: 10px auto;"/>
  </div>
</details>



<div style="background: linear-gradient(to bottom, #222, #333); color: #eee; padding: 10px; border-radius: 5px; font-family: 'Source Code Pro', monospace; margin-top: 20px; box-shadow: 0 5px 10px rgba(0,0,0,0.3);">
<pre id="year-progress">
<span class="prompt">vincenzo@portfolio:~$</span> year_progress
<span class="output">Calculating...</span> 
</pre>

<script>
  function updateYearProgress() {
      const now = new Date();
      const start = new Date(now.getFullYear(), 0, 0);
      const diff = now - start;
      const oneDay = 1000 * 60 * 60 * 24;
      const dayOfYear = Math.floor(diff / oneDay);
      const totalDays = (new Date(now.getFullYear(), 11, 31) - start) / oneDay + 1; //Leap years


      const percentage = Math.round((dayOfYear / totalDays) * 100);
      const progressBar = "#".repeat(Math.round(percentage/4)) + " ".repeat(25-Math.round(percentage/4));

      document.getElementById("year-progress").innerHTML = `
<span class="prompt">vincenzo@portfolio:~$</span> year_progress
<span class="output">[${progressBar}] ${percentage}% as of ${now.toLocaleDateString()}</span>`;
  }

  updateYearProgress(); // Initial call
  setInterval(updateYearProgress, 60000); // Update every minute 
</script>
</div>

<style>
.prompt { color: #39ff14; }
.output { color: #fff; }
.output-highlight { color: #00FFFF; } /* Cyan for highlights */

#terminal {

  border: 2px solid #555; /* Subtle border */


}

</style>
