<p align="center"><img alt="Banner" src="./banner/waves-banner.gif"></p>

# 🌊 Julian Peter B. Gerona

**`Future Something`**

Hi 👋, I'm a second year college student at [Mapúa Malayan Colleges Laguna], currently pursuing a degree in Bachelor of Science in Information Technology. I am interested in Web Design and hopefully become a front-end developer in the future someday.

[Mapúa Malayan Colleges Laguna]: https://mcl.edu.ph/

---

### 🙂 More About Me

- 🚴‍♂️ My hobbies include: cycling, editing and graphic design.

- ⚡ I am currently interested in learning more about Web Development and Design.

- 🏝 I love the **City Pop Aesthetic**. I follow the works made by Hiroshi Nagai, Eizen Suzuki, Ardhira Putra, and Tree_13.

- 🎵 I currently like listening to the **Math Rock** genre.

### 🔰 Currently Learning

![REACT](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![VITE](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E)
![TYPESCRIPT](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Three JS](https://img.shields.io/badge/ThreeJs-black?style=for-the-badge&logo=three.js&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP-0F110F?style=for-the-badge&logo=greensock&logoColor=88CE02)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

### 💻 Stack

![PYTHON](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JAVASCRIPT](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![MS SQL Server](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white)

<h6>These are languages that I have used (and possibly abused).<br />
Note: No languages <i>were harmed</i> during debugging.</h6>

### 🎨 Design

![Ps](https://img.shields.io/badge/Adobe%20Photoshop-31A8FF?style=for-the-badge&logo=Adobe%20Photoshop&logoColor=black)
![Pr](https://img.shields.io/badge/Adobe%20Premiere%20Pro-9999FF?style=for-the-badge&logo=Adobe%20Premiere%20Pro&logoColor=white)
![Ae](https://img.shields.io/badge/Adobe%20after%20affects-CF96FD?style=for-the-badge&logo=Adobe%20after%20effects&logoColor=393665)
![PPT](https://img.shields.io/badge/Microsoft_PowerPoint-B7472A?style=for-the-badge&logo=microsoft-powerpoint&logoColor=white)
![FIGMA](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?&style=for-the-badge&logo=Canva&logoColor=white)

### 📩 Contact Me

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white&link=mailto:julianpetergerona@gmail.com)](mailto:julianpetergerona@gmail.com)
[![Outlook](https://img.shields.io/badge/Microsoft_Outlook-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white&link=mailto:2022jpbgerona@live.mcl.edu.ph)](mailto:2022jpbgerona@live.mcl.edu.ph)

---

### 📋 Git Commands Cheat Sheet

This cheat sheet provides a quick reference to Git commands I use. The examples I provided may be different as I use a MacOS machine and run these commands using a Bash terminal.

1. `git init` - This is the very first step to start tracking changes in your project. It initializes a new and empty Git repository in your local repository. It has **no parameters**, but it is needed to specify which directory to initialize a Git repository first before running **git init**.
   #### Example:
   > \$ cd ~/Repositories/my-awesome-project  
   > \$ git init

<br />

2. `git clone [url]` - If you want to work on an existing remote repository that has Git initialized, use **git clone**. This command **downloads a remote repository to your local machine**. Its parameter needs you to provide the **URL** of the repository you want to clone, and like git init, it is also important to specify which directory you want Git to download the project.
   #### Example:
   > \$ cd ~/Repositories  
   > \$ git clone `https://github.com/jp-gerona/jp-gerona.git`

<br />

3. `git add [file]` - After making changes to your files, you need to tell Git which changes you want to track or stage. Use **git add [file]** to add specific files or simply **git add .** to add all modified files in the local repository to the staging area.
   #### Example:
   > \$ git add .

<br />

4. `git commit -m "[description]"` - Once you've added the desired changes to the staging area, use **git commit** to take a **snapshot** of those changes and store them in the **Git history of your local repository**. It is good practice to always provide a clear and concise message describing the changes you've made using the **-m** flag.
   #### Example:
   > \$ git commit -m "Added a new super awesome feature"

<br />

5. `git push [alias] [branch]` - After committing your changes locally, you can use **git push** to push commits to a remote repository. Additionally, you have the option to specify the **remote alias** (often "origin") and the **branch you want to push your changes to** (e.g., "main" or a specific "branch") by establishing an upstream relationship using the **-u** flag. Though not mandatory, this is useful as it allows you to use **git push only** without specifying the remote name and branch in the future.
   #### Example:
   > \$ git push -u origin main

<br>

6. `git log` - The git log command displays committed snapshots. It lets you list the project history, filter it, and search for specific changes. While git status lets you inspect the working directory and the staging area, git log only operates on the committed history.
   #### Example:
   > \$ git log --author="John Smith" -p hello.py

<br>

7. `git config` - The git config command is a convenience function that is used to set Git configuration values on a global or local project level. These configuration levels correspond to .gitconfig text files. Executing git config will modify a configuration text file.
   #### Example:
   > \$ git config user.email <br> > \$ git config --global user.email "your_email@example.com"

---

<h3 align="center">🌊 Making Waves.</h3>
<h6 align="center">(GIF made by me using Powerpoint and Premiere Pro)
