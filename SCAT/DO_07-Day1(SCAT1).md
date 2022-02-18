1. Name two classifications of programming languages and explain the differences. 
    - Programming language are classified as “high level” and “low level”. 
    - Low level languages such as ‘C’ offer speed and are closer to machine Lebel instructions and are often aware of the underlying hardware.
    - High level languages such as ‘Python’ (and Ruby or Perl), are easier to learn, maintain and run irrespective of the underlying hardware or operating system.


2. What classification of programming languages does Python belong to? 
    - Low-level


3. Give three reasons for Python popularity. 
    - It’s easy to learn
    - It’s easy to understand 
    - It’s free, open source and multiplatform


4. Give a reason why is Python favoured by DevOps teams. 
    - It’s suited for automation


5. What is a difference between Python 2.x and 3.x versions? 
    - Python has two main version: 2.x and 3.x
    - Many applications and Operating Systems rely on the older version of Python (v2.x). For example, macOS still relies heavily on Python 2.7.
    - Python 2.x has reached its end-of-life and is in maintenance mode. It will no longer be developed further. 
    - Python 3.x is the current version of the language.
    - Python versions 2.x and 3.x are not compatible. Python 2.x scripts won't run in a Python 3.x interpreter and vice versa.
    - It may not be practical to re-write Python 2.x code, therefore ways have been devised to run multiple versions of Python concurrently.
    - There are also different Pythons such as Cpython, Jython, PyPy and Rpython.


6. Can you run Python 2 scripts with Python 3 interpreter? 

	a. If ‘yes’ why? 

	b. If ‘no’ why? <br>
    		- No, because they have different syntax and features.


7. Describe the relationship between a Python script, Python interpreter, the Operating System and System Software. 

    - The python script feeds into the interpreter which then interacts with the system software to feed into the operating system - this process is all part of the software, which then reaches the hardware, and it continues to flow between the hardware and software.

8. Why would you use Python Virtual Environment (venv)? 
    - The main purpose of Python virtual environments is to create an isolated environment for Python projects. This means that each project can have its own dependencies, regardless of what dependencies every other project has. Plus, they're easily created using the virtualenv or pyenv command line tools.


9. What is the main difference between running Python commands in Python Interpreter Shell and an IDE? 
    - In interpreter is a program that runs programs written in a particular language. The CPython interpreter in one interpreter for running Python programs. An Itegrated Development Environment (IDE) is a program writing and running programs, possible with an interpreter, in one or more languages.


10. Name one IDE you can use for Python development. 
    - Pycharm


11. Name one web site that you can get full Python reference. 
    - https://docs.python.org/3/library/index.html 


12. Describe with an example what “sep” is used for in print function. 
	colour=['red','blue','orange','pink']
	print(*colour, sep = ", ")
    - This code will print “red, blue, orange, pink”, as it is printing the colour array separated by the space that is assigned to the sep function.


13. What is meant by Python built-in functions? 
	- Functions that python have programmed for anyone to use, such as: “print()”, “endswith()”, etc.


14. What is version control and what is it used for? 
    - Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later.
    - Version control can records changes any type of file, be it a document or software code.
    - Version control is important for documents that undergo a lot of revision and redrafting such as software source code. 
    - Version control is a way to trace the source of conflict and crashes.
    - In general source control achieved when we use version control software to track changes in our software source code.


15. What is a difference between centralised and decentralised version control? 
    - Centralised means that everyone is essentially working on the main and then are no branches, it is the only version of that programme. Where as with decentralised, multiple programmers could be working on different features on different branches and then merge them with the main. It is a more efficient and productive way of working.


16. Name two advantages of Git? 
    - Performance. Git performs very strongly and reliably when compared to other version control systems.
    - Security. Git is designed specially to maintain the integrity of source code.
    - Flexibility.
    - Wide acceptance.
    - Quality open source project.


17. Name two remote Git? 
    - ‘branch’ and ‘checkout’


18. Given a project how do you make the project version controlled used Git – or to put it differently what is the process of creating a repository based on a project? 
    - To start a working area (e.g. your project folder)
    -    clone      Clone a repository into a new directory
    -    init       Create / initialise an empty Git repository


19. How do you add source code to your newly created repository? 
    - The next steps are add and commit options. 
    - Git add option lets you add files to your repo.  
    - Added function are in in a transition stat. They are not yet part of your snapshot.
    - Git commit option will commit the changes to you project snapshot.
    - You’ll need to include a comment with your commit indicating the nature the latest change.


20. How do you commit changes to a repository? 
    - git add .
    - git commit -m “init commit”
    - git push origin master


21. Describe one way of monitory versions of a source code. 
    - By using branches, creating a pull request and having a team member check your changes before confirming them.


22. Describe how to create a branch in Git. 
    - git branch <branch_name>
    - gco -b <branch_name>
    - git push origin <branch_name> 


23. Describe the difference between Merge From and Merge To?
    - Merge From is pulling, as you’re taking the up-to-date code for the main branch, where as Merge To is creating a pull request as you’re trying to push the updated code that you’ve been working on.



