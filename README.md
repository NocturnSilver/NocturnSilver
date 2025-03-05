<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&weight=600&size=30&duration=6000&pause=1000&color=2CF767&width=435&lines=%3E+Welcome+to+my+page!;%3E+A+storage+for+monstros...;%3E+I+mean+respectable+code;%3E+Just+a+small+disclaimer...;%3E+If+you+use+my+code;%3E+don't+blame+me+if+your;%3E+system+decides+to;%3E+Unalive+itself...;%3E+...;%3E+Why+are+you+still+here%3F;%3E+Nothing+better+to+do%3F;%3E+Oh+well+suit+yourself" alt="Typing SVG" /></a>

<h2>
  Education and Interests
</h2>
  <ul>
    <li>I am currently pursuing a masters in Computer Science. </li>
    <li>I am interested in Math, Physics, computer science, and robotics</li>
  </ul>

<h2>
   Tools Learned and Used
</h2>
<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/c/c-original.svg" alt="C Programming Language" width="45" height="45"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original-wordmark.svg" alt="Python" width="45" height="45"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/numpy/numpy-original.svg" alt="numpy" width="45" height="45"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/matplotlib/matplotlib-original.svg" alt="matplotlib" width="45" height="45"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pandas/pandas-original-wordmark.svg" alt="pandas" width="45" height="45"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original-wordmark.svg" alt="MySql" width="45" height="45"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" alt="Git" width="45" height="45"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/github/github-original.svg" alt="github" width="45" height="45"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original.svg" alt="html5" width="45" height="45"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-original.svg" alt="css3" width="45" height="45"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vscode/vscode-original.svg" alt="vscode" width="45" height="45"/>        
</p>

- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ NocturnSilver }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9

