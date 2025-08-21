Hye 👋

💞️ I’m looking to collaborate on Github & other social media

<!--
- 👋 Hi, I’m @Phenoix-1294
- 👀 I’m interested in
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
---!>
<!---
Phenoix-1294/Phenoix-1294 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>GitHub Profile Stats - Styled</title>
<script src="https://cdn.tailwindcss.com"></script>
<style>
  body {
    background-color: #1e293b; /* Dark slate background */
    color: #e2e8f0; /* Light text */
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  }
  .card {
    background-color: #0f172a; /* Darker card background */
    border-radius: 0.5rem;
    padding: 1.5rem 2rem;
    box-shadow: 0 0 12px rgba(0,0,0,0.6);
  }
  .icon-green {
    color: #34d399; /* Teal green */
  }
  .circular-progress {
    width: 80px;
    height: 80px;
    position: relative;
  }
  .circular-progress svg {
    transform: rotate(-90deg);
    width: 80px;
    height: 80px;
  }
  .circular-progress circle {
    fill: none;
    stroke-width: 8;
    stroke-linecap: round;
  }
  .circular-progress .bg {
    stroke: #334155;
  }
  .circular-progress .progress {
    stroke: #9ca3af;
    stroke-dasharray: 251.2;
    stroke-dashoffset: 100;
    transition: stroke-dashoffset 0.7s ease;
  }
  .grade-text {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    font-weight: 700;
    color: #9ca3af;
    font-size: 1.5rem;
    user-select:none;
  }
  .progress-section {
    border-left: 1px solid #334155;
    border-right: 1px solid #334155;
  }
  .streak-circle {
    width: 72px;
    height: 72px;
    position: relative;
  }
  .streak-circle svg {
    transform: rotate(-90deg);
    width: 72px;
    height: 72px;
  }
  .streak-circle circle {
    fill: none;
    stroke-width: 6;
    stroke-linecap: round;
  }
  .streak-circle .bg {
    stroke: #334155;
  }
  .streak-circle .progress {
    stroke: #f97316; /* orange */
    stroke-dasharray: 226.2;
    stroke-dashoffset: 226.2;
    transition: stroke-dashoffset 0.7s ease;
  }
  .streak-text {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -55%);
    font-weight: 700;
    color: #f97316;
    font-size: 1.8rem;
    user-select:none;
  }
  .languages-bar {
    height: 8px;
    border-radius: 9999px;
    overflow: hidden;
    margin-bottom: 0.7rem;
  }
  .language-segment {
    height: 8px;
  }
</style>
</head>
<body class="min-h-screen flex items-center justify-center px-4 py-12">
  <div class="max-w-3xl w-full space-y-10">
    <!-- Top Stats + Grade -->
    <details class="card" open>
      <summary class="cursor-pointer mb-4 text-blue-400 font-semibold select-none">View My Github Stats</summary>
      <div class="grid grid-cols-[1fr_100px] gap-8 items-center">
        <div class="space-y-3 text-sm">
          <h2 class="text-xl font-bold">Hardi's GitHub Stats</h2>
          <p class="flex items-center gap-2"><span class="icon-green">⭐</span> Total Stars Earned:<span class="ml-auto font-semibold">-</span></p>
          <p class="flex items-center gap-2"><span class="icon-green">⏲️</span> Total Commits (2025):<span class="ml-auto font-semibold">-</span></p>
          <p class="flex items-center gap-2"><span class="icon-green">🔀</span> Total PRs:<span class="ml-auto font-semibold">-</span></p>
          <p class="flex items-center gap-2"><span class="icon-green">❗</span> Total Issues:<span class="ml-auto font-semibold">-</span></p>
          <p class="flex items-center gap-2"><span class="icon-green">🖇️</span> Contributed to (last year):<span class="ml-auto font-semibold">-</span></p>
        </div>
        <div>
          <div class="circular-progress" aria-label="Grade -">
            <svg aria-hidden="true" viewBox="0 0 80 80">
              <circle class="bg" cx="40" cy="40" r="40" />
              <circle class="progress" cx="40" cy="40" r="40" stroke-dashoffset="100" />
            </svg>
            <div class="grade-text">-</div>
          </div>
        </div>
      </div>
    </details>

    <!-- Contributions Stats -->
    <div class="card grid grid-cols-3 text-center divide-x divide-gray-700">
      <div class="px-4">
        <div class="text-3xl font-extrabold">2,075</div>
        <div class="text-sm font-semibold">Total Contributions</div>
        <div class="text-xs text-gray-400 mt-1">Jul 10, 2018 - Present</div>
      </div>
      <div class="px-4 relative">
        <div class="streak-circle mx-auto" aria-label="Current Streak 0">
          <svg aria-hidden="true" viewBox="0 0 72 72">
            <circle class="bg" cx="36" cy="36" r="36" />
            <circle class="progress" cx="36" cy="36" r="36" stroke-dashoffset="226.2" />
          </svg>
          <div class="streak-text" id="streak-value">0</div>
        </div>
        <div class="text-sm font-bold text-orange-500 mt-2">Current Streak</div>
        <div class="text-xs text-gray-400 mt-1">Aug 21</div>
      </div>
      <div class="px-4">
        <div class="text-3xl font-extrabold">21</div>
        <div class="text-sm font-semibold">Longest Streak</div>
        <div class="text-xs text-gray-400 mt-1">Mar 16 - Apr 5</div>
      </div>
    </div>

    <!-- Most Used Languages -->
    <div class="card max-w-md">
      <h3 class="font-semibold mb-3">Most Used Languages</h3>
      <div class="languages-bar flex overflow-hidden rounded-full bg-gray-700">
        <div class="language-segment" style="width: 28.28%; background-color:#2b74e4" title="TypeScript 28.28%"></div>
        <div class="language-segment" style="width: 20.93%; background-color:#6a69c4" title="PHP 20.93%"></div>
        <div class="language-segment" style="width: 16.12%; background-color:#f05340" title="Blade 16.12%"></div>
        <div class="language-segment" style="width: 12.90%; background-color:#3572A5" title="Python 12.90%"></div>
        <div class="language-segment" style="width: 12.26%; background-color:#ffdf00" title="JavaScript 12.26%"></div>
        <div class="language-segment" style="width: 9.51%; background-color:#e34c26" title="HTML 9.51%"></div>
      </div>
      <div class="grid grid-cols-2 gap-2 text-xs">
        <div class="flex items-center gap-2"><span class="w-3 h-3 rounded-full" style="background-color:#2b74e4"></span> TypeScript 28.28%</div>
        <div class="flex items-center gap-2"><span class="w-3 h-3 rounded-full" style="background-color:#3572A5"></span> Python 12.90%</div>
        <div class="flex items-center gap-2"><span class="w-3 h-3 rounded-full" style="background-color:#6a69c4"></span> PHP 20.93%</div>
        <div class="flex items-center gap-2"><span class="w-3 h-3 rounded-full" style="background-color:#ffdf00"></span> JavaScript 12.26%</div>
        <div class="flex items-center gap-2"><span class="w-3 h-3 rounded-full" style="background-color:#f05340"></span> Blade 16.12%</div>
        <div class="flex items-center gap-2"><span class="w-3 h-3 rounded-full" style="background-color:#e34c26"></span> HTML 9.51%</div>
      </div>
    </div>
  </div>
</body>
</html>

