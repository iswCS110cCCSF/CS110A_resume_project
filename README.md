# CS110A_resume_project
This project would give students a mobile-friendly(responsive) personal résumé webpage built with HTML and CSS. You’ll edit the given template to make it your own and publish it online using **GitHub Pages**.

## What You’ll Need
- A free **GitHub account** (create one at [https://github.com](https://github.com))
- **Git** installed on your computer. Talk to me if you have a Chromebook or don't have a computer.
  - **Windows:** [Download Git](https://git-scm.com/download/win)
  - **macOS:** at the mac terminal enter, `brew install git` (or use the Xcode Command Line Tools)
  - **Linux (Debian/Ubuntu):** `sudo apt install git`
  - **Talk to me** if any of above is not your OS or you have issues installing
- A terminal (Command Prompt, PowerShell, macOS Terminal, or Linux shell)
- A text editor such as Notepad++

## Steps to Create and Publish Your Resume

### 1. Fork the Instructor Repository (on GitHub).
- In your browser, open the Instructor's template repository(repo), https://github.com/iswCS110cCCSF/CS110A_resume_project.git  
- Click "Fork" at top-right.
- Login: You will be asked to login to your GitHub account.
- GitHub will create your own resume repo, https://github.com/YOUR_GITHUB_USERNAME/CS110A_resume_project

### 2. Clone your forked repo(not your instructor's) to your local machine
- Open your terminal or command line at any location. Then enter the following commands(Windows version is shown. Use ls instead of dir in Mac or Linux) in the order given.
- <img width="458" height="35" alt="2026-01-06 16-25-26" src="https://github.com/user-attachments/assets/8d594247-a6d0-40d2-a83c-2f7a6a21c348" />

Update:
Name, email, and links
Education, Experience, and Projects
Replace photo_placeholder.png with your own photo
Keep the same file name (photo_placeholder.png), or update the "img src" path in HTML.
You can preview your changes by double-clicking the .html file to open it in a web browser.

### 3. Commit Your Changes
Save your edits, then run inside CS110A_resume_project. Take a screenshot as a part of your midterm project submission. You are still local on your computer. In the step 4 you will push it to your remote git repository.
```
>git add .
>git commit -m "Personalized my resume"
```

### 4. Push to GitHub
In this step you will push your local repository to your git repository and thus make it public. Take a screenshot as a part of your midterm project submission. 
```
>git branch -M main
>git remote add origin https://github.com/YOUR_GitHub_USERNAME/CS110A_resume_project.git
>git push -u origin main
```

### 5. Enable GitHub Pages
Go to your repository on GitHub.
Click Settings → Pages.
Under Branch, select main and click Save.
Wait a minute, then visit:
https://YOUR_GitHub_USERNAME.github.io/CS110A_resume_project/
Your résumé is live on the web!

## 6. Submit your resume project
- Invite your professor to your GitHub repository via his GitHub user name, iswCS110cCCSF or email iwalimuni@ccsf.edu
- Collect all the screenshots and zip them into a file with your name
- Submit this zip file in Canvas
- Email the link to your resume (GitHub page not the GitHub project) and also submit it via a submission comment in Canvas

## Tips
You can rename the file you want to use as index.html — that’s what GitHub Pages loads first.
To make your résumé stand out, add links to your projects, GitHub profile, or class portfolio.
Try viewing it on your phone — it’s fully responsive!

## Optional Enhancements
Embed a Google Form for feedback or contact info:
<iframe src="https://docs.google.com/forms/d/e/YOUR_FORM_ID/viewform?embedded=true" width="640" height="800"></iframe>

Add your Python or JS projects in a "Projects" section.
Customize colors in style.css. Explore how you can improve your web resume and make it your own.

## Advice and Help
Ask me how you can show case a Python turtle code you wrote in the class and animate it in your resume. Need advice on how to improve or maybe to add a JS file or simply stuck. Your instructor and TAs are here to help. 
