<h1 align="center" style="font-size: 3.5rem; font-family: 'Source Code Pro', monospace; color: #20C20E;">
  Hi 👋, I'm Vincenzo Amendola
</h1>

<h3 align="center" style="font-style: italic; color: #888;">
  A passionate backend developer from Brazil who also engages in data science.
</h3>

<!-- Mock Terminal -->
<div style="background-color: #222; color: #eee; padding: 20px; border-radius: 10px; font-family: 'Source Code Pro', monospace; overflow: auto; margin: 20px auto; max-width: 800px;">
  <pre>
<span style="color: #0A84FF;">vincenzo@portfolio</span>:<span style="color: #20C20E;">~</span><span style="color: #AAA;">$</span> whoami
<span style="color: #FF5F57;">Vincenzo Amendola</span> - Backend Developer & Data Scientist

<span style="color: #0A84FF;">vincenzo@portfolio</span>:<span style="color: #20C20E;">~</span><span style="color: #AAA;">$</span> ls -l skills
total 12
-rw-r--r-- 1 vincenzo staff 1024 Dec 30 2024 python
-rw-r--r-- 1 vincenzo staff 1024 Dec 30 2024 docker
-rw-r--r-- 1 vincenzo staff 1024 Dec 30 2024 django
<span style="color: #0A84FF;">vincenzo@portfolio</span>:<span style="color: #20C20E;">~</span><span style="color: #AAA;">$</span> cat contact.txt
<span style="color:#50E3C2;">GitHub:</span> github.com/Vincenzo140
<span style="color:#50E3C2;">Email:</span> vincenzo.amendola141@gmail.com
<span style="color:#50E3C2;">LinkedIn:</span> linkedin.com/in/vincenzo%20amendola
<span style="color: #0A84FF;">vincenzo@portfolio</span>:<span style="color: #20C20E;">~</span><span style="color: #AAA;">$</span> <span style="color: #FFC58F;"># Type 'help' for more commands...</span>
  </pre>
</div>

<details>
  <summary style="font-family: 'Source Code Pro', monospace; color:#20C20E; cursor: pointer; margin: 20px 0; font-size: 1.2rem;">
    <span style="color: #AAA;">></span> Skills & Tools 
  </summary>
<p align="center">
    <!-- Skill and Tool Icons -->
     <img src="..." alt="Skill/Tool Name" width="50" height="50" style="margin: 10px;"/>
     <!-- ... Add all your skill/tool icons here ... -->
</p>
</details>

<details>
  <summary style="font-family: 'Source Code Pro', monospace; color:#20C20E; cursor: pointer; margin: 20px 0; font-size: 1.2rem;">
    <span style="color: #AAA;">></span> GitHub Stats 
  </summary>
  <div align="center">
    <!-- GitHub Stats -->
    <img src="https://github-readme-stats.vercel.app/api?username=Vincenzo140&show_icons=true&theme=radical" alt="GitHub Stats" width="48%"/>
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Vincenzo140&layout=compact&theme=radical" alt="Top Languages" width="48%"/>
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=Vincenzo140&theme=radical" alt="GitHub Streak" width="100%"/>
  </div>
</details>


<!-- Year progress in a terminal style with JavaScript for dynamic calculation -->
<div style="background-color: #222; color: #eee; padding: 10px; border-radius: 5px; font-family: 'Source Code Pro', monospace; margin-top: 20px;">
  <pre id="year-progress">
<span style="color: #0A84FF;">vincenzo@portfolio</span>:<span style="color: #20C20E;">~</span><span style="color: #AAA;">$</span> year_progress
<span style="color: #50E3C2;">Calculating...</span> </pre>
<script>
  const now = new Date();
  const start = new Date(now.getFullYear(), 0, 0);
  const diff = now - start;
  const oneDay = 1000 * 60 * 60 * 24;
  const dayOfYear = Math.floor(diff / oneDay);
  const totalDays = (new Date(now.getFullYear(), 11, 31) - start) / oneDay +1 // Account for leap years

  const percentage = Math.round((dayOfYear / totalDays) * 100);

  document.getElementById("year-progress").innerHTML = `
<span style="color: #0A84FF;">vincenzo@portfolio</span>:<span style="color: #20C20E;">~</span><span style="color: #AAA;">$</span> year_progress
<span style="color: #50E3C2;">[${"#".repeat(Math.round(percentage/4))}${" ".repeat(25-Math.round(percentage/4))}] ${percentage}% as of ${now.toLocaleDateString()}</span>`;
</script>

</div>
