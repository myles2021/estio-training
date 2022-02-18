1. Why is Git (as source repository) critical to a DevOps operation?
    - It allows many engineers to work on a project in sections so that it’s a faster and more efficient way of working as well as a safer way of storing code, as it’s via the cloud.


2. What is alternative name of the main code branch of code in Git?
    - Master or main


3. Describe the following and their usage:
a) Branch
    - It allows an engineer to pull the latest ‘main’ code and then work on a feature independently.
b) Checkout
    - It allows an engineer to change branches
c) Fork
    - It allows an engineer to freely test and debug with changes without affecting the original project. One of the excessive use of forking is to propose changes for bug fixing.
d) Pull
    - It allows an engineer to pull the latest ‘main’ code
e) Push
    - It allows an engineer to push the changes they’ve made to the code in their branch
f) Merge
    - If all changes are fine, the branch can be merged with the ‘main’


4. Name 5 differences of Git and GitHub.
    1. Git is a version control system that lets you manage and keep track of your source code history. 
    2. GitHub is a cloud-based hosting service that lets you manage Git repositories. 
    3. If you have open-source projects that use Git, then GitHub is designed to help you better manage them. 
    4. GitHub just takes things a little bit further than Git, offering more functionality and resources, as well as a place online to store and collaborate on projects. 
    5. GitHub repositories are publicly available. Developers from across the globe can interact with and contribute to each other’s code in order to modify or improve it, which is known as ‘social coding’. In a way, this makes GitHub a networking site for web professionals.


5. Having installed the Git for the first time, what are the two Git commands you must run?
    - $ git config --global user.name "John Doe"
    - $ git config --global user.email johndoe@example.com


6. Given a project what is the mechanism to instruct git to ignore some files or directories?
    - Include a .gitignore file


7. You’ve created a new project folder and added some files, how would you initiate a git repository for that project?
    - git init


8. What is staging in Git?
    - A staging step in git allows you to continue making changes to the working directory, and when you decide you wanna interact with version control, it allows you to record changes in small commits. Separating staging and committing, you get the chance to easily customise what goes into a commit.


9. Git monitors you project folder. What is the command to find out about the state of a monitored project?
    - git status


10. What is the Git command to commit staged files?
    - git commit -m “stage b of new feature”


11. What is the syntax of a Git “add” command?
    - git add .


12. What is the meaning of “ . “ (full stop) in “git add .” ?
    - To add the work that you’re currently working on, it is referring to the project that you’re in and adding the changes that you’ve made.


13. What is the Git syntax to create a working branch?
    - git checkout -b my_new_branch_name


14. What is the Git syntax for switching between branches?
    - git checkout main


15. What “ –m ” in “git commit –m ‘your_message’”?
    - It’s an insightful message used to inform the merger of your changes what you’ve attempted before they scan through your code.


16. What is Markdown?
    - A Readme file is a file that describes the purpose of the repository and gives hints on what the code does, how to compile/use it, etc. The . md extension stands for Markdown, which is a type of file that is both readable in plain text, but can also be easily converted to HTML to display special elements.


17. Consider the following scenario:
a) You’ve created a working branch called my_branch and currently working on that branch.
b) You want merge my_branch with the master branch.
c) What are the steps in achieving your goal?
        1. git add .
        2. git commit -m “changes I’ve done to the **** feature, adding *** and fixing ****”
        3. git push origin my_branch
        4. Create a pull request via GitHub dashboard and assess your changes before submitting it
        5. Ask someone to review the changes before merging it
