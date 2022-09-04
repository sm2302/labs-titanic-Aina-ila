# SM2302 Git Worksheet 1

## Instructions

For this exercise, you will learn to create a private repo on GitHub, similar to how
you would do when submitting your individual assignment. You will get to practice
submitting R code from the titanic data set. Follow the instructions below.

**Step 1**
> On Canvas, go to the Assignments tab, and select the ‘Titanic’ lab assignment.<br>
> You will find the link to accept the GitHub Classroom assignment.

*Step 2*
> Select your name from the roster and follow the instructions.<br>
> Login to GitHub as necessary.<br>
> A private repository located at the sm2302 GitHub Classroom should have been created for you.

**Step 3**
> When greeted with the repo setup page on GitHub.com, Select the ‘Set up in Desktop’ icon and click it.<br>
> This should bring you to the GitHub Desktop app on your computer.<br>
> Clone this (blank) repository onto a local folder on your computer.

**Step 4**
> Add the following three files as your first commit (obtained from Canvas):<br>
• titanic_codebook.txt<br>
• titanic.csv<br>
• titanic.R<br>
> Don’t forget to push to GitHub.

**Step 5**
> Next, launch RStudio and create a new project called titanic.<br>
> Since the folder has already been created, select **‘Existing Directory’** and point it to your local GitHub titanic folder.<br>
> If done successfully, you should have a file called labs-titanic-<your_username>.Rproj created in the folder.<br>
> Commit and push this change to GitHub.<br>
> Note that there might be an additional .gitignore file created by RStudio automatically as well.<br>
> <br>
> *Hint* : The easiest way would be, while RStudio is not running, double click on the titanic.R file in your local GitHub folder.<br>
> The working directory then should be where the file is.

**Step 6**
> Next, you will **run all** the commands in the R script.<br>
> But, before you do this, add the following line to the very bottom of the R script.<br>
> <br>
> **gsave("pred_prob_surv.png", width = 8, height = 4)** <br>
> After running the entire R code, there should be two new files created in the folder. Commit and push these to GitHub.<br>
><br>
> Some questions to ponder:<br>
• What does the ggsave() function do?<br>
• What is the other file that has been created? What is its purpose?

**Step 7**
> Next, create a new Markdown file (extension .md). You can do this by going to File →New File →Markdown file in RStudio.<br>
> Name this file README.md.<br>
><br>
> The README file should contain some brief description about what your repo contains. This is especially useful to let other people know what to expect when
> they visit your repo. Go ahead and write a couple of lines and paragraphs about
> your repo. Once that’s done, commit and push to GitHub.<br>
><br>
> *Hint: Use the following Markdown Cheat Sheet: https://www.markdownguide.org/cheat-sheet/.*

### NOTE: THE NEXT ACTIVITY MAY NOT WORK IF YOU HAVE NOT APPLIED FOR EDUCATION BENEFITS FROM GITHUB. DO SO AT<br>
### https://education.github.com/benefits/offers.

**Step 8**
> Finally, we will be converting the repo to a static website that is hosted on GitHub.<br>
> This feature is called GitHub pages. On your GitHub titanic repo, go to<br>
> **Settings →Pages (on the left side tab). Under the ‘Branch’ setting, select ’main’, and click Save.**<br>
> It may take a while to set up, but eventually your website will be up and running at<br>
> https://sm2302.github.io/labs-titanic-<your_username>. Go check it out!

**Step 9**
> **SUBMISSON.** Once you are done with this exercise, go back to Canvas and submit the url of your GitHub website (or of the repo, if you were unable to create
> the website). This is how you submit an assignment using GitHub Classroom and Canvas.

DONE!!
