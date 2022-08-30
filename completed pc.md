## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git? An Open-Source Distributed Version Control System
Essentially, this means there is source code that is available for free, and the
Hub tracks and stores it.  As many coders change the current content, it tracks
all the changes and eventually merges it bac into the main code

2. What is the difference between Git and GitHub?  Git is the software in which 
the code is made available and manipulatable.
GitHub is the for-profit cloud-based hosting services (i.e. servers) in which Git
and all its repositories are stored

3. Why do we create a branch? Branching is essentially the ability to work on a 
particular piece of or whole code independantly from the main and others working 
on the same code separately.

4. What is the purpose of a Pull Request? You local, remote, and main 
repositories.  The local resides on your computer.  The remote resides on GitHub 
in your cload.   The Main is the primary branch in which you pulled the code from 
to your remote then local machine.
That brings to pull.  A pull request is just that, a request to pull code to your 
remote/local machine for editing separately from the main branch.

5. What is the command you can use to switch between branches? For example you 
are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
git checkout "and then the name of the branch (without the quotation marks of course)"

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
'git fetch' downloads changes from your remote repository to your loacal repository on your machine
'git merge' is how you merge a particular branch you are working on into the main branch
'git pull' is the command you would use to download changes from your remote repository
and automatically merges them into your branch you are working on

7. What is a merge conflict?
When at least 2 different code commits occur, and Git is unable to sort-out differences in the code

8. How do you resolve a merge conflict?
Essentially you have to open the file and correct the code that is not resolving.
This is why it is important to do frequent commit chunks, so it will be easier to locate problem
code issues in chunks rather than the entire file.
