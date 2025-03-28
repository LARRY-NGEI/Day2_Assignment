Explain the fundamental concepts of version control and why GitHub is a popular tool for managing versions of code. How does version control help in maintaining project integrity?
Answer
1. Repository- is a database that stores all files and their version history localy or remotely.
2. Commit- is a snapshot of changes made to files at a specific point in time.
3. Branch- allows you to create separate versions of your project to work on features independently.
4. Merge- This is combining changes from different branches to one.
5. Clone- This is creating a local copy of a remote repository.
6. Pull- This is to update your local repository with changes from remote repository.
7. Push- This is to upload your local commits to a remote repository.
8. Rebase- This is creating a copy of someone else's repository on your GitHub to make changes independently.
9. Tag- This is mark specific points in your commit history as important.
    Answer
   It is the largest host of source code inthe world, User-friendly interface and its powerful features and it also has Git-based version control.
   Answer
   It tracks changes in code
   it tracks person who changed code.
   Monitor changes and Progress.

Describe the process of setting up a new repository on GitHub. What are the key steps, and what are some of the important decisions you must make during this process?
  Answer
  Step 1: Sign in GitHub and click the icon new repository
  Step 2: Enter the name ofthe repository
  Step 3: Add a brief description of your project.
  Step 4: Choose if you want it to be public or private.
  Step 5: Add a README file.
  Step 6: Add s gitignore.
  Step 7: Finalize by choosing a license and click create repository.
   Answer
   Sign into GitHub
   Initiate repository creation
   Configure repository creation
   Initialize repository
   Create repository.
     Answer
   Whether the repository will be public or private.
   The README.md
   The gitignore
   The license

Discuss the importance of the README file in a GitHub repository. What should be included in a well-written README, and how does it contribute to effective collaboration?
    Answer
  It is the front page of your repository. It explains what your project does in brief and simple terms.It shows the 
    projectss title,key functionalities, set up steps to contribute to the projects.
  ii. Project tittle, Purpose of Project, Badges, Functionalities, Installation, Usage, Contirbuting, License.

  It helps in accomadateing new contributors, it has clear expectations to contributors, it improves documentation 
     maintenance and it eases communication between teams. Enhances tool integration and reduces risks.

Compare and contrast the differences between a public repository and a private repository on GitHub. What are the advantages and disadvantages of each, particularly in the context of collaborative projects?
    Answer 
  Public- Is a repository visible by everyone.
  Private- Is visible only to allowed users to see. Its restricted.
  Answer
  Public:                                                            Private
         It can be contributed by anyone.                           It  has limited contributors.
         it has high risk in terms of security.                     It has proctected access.
         Free hosting.                                              Requires to be paid.
   Answer
   Advantages of public repository
   Open source collaboration
   Full Github features.
   Increased visiblity
   DISADVANTAGES
   Security risks
   Anyone can fork your code

   Advantages of Private Repository
   Enhanced security
   Controlled collaboration
   DISADVANTAGES
   Tooling restrictions
   Limited Open-source benefits.
   
Detail the steps involved in making your first commit to a GitHub repository. What are commits, and how do they help in tracking changes and managing different versions of your project?
     Answer
     Step 1: Install Git, Configure git by setting up your username and email using git config commands.
     Step 2: Initialize repository- Create a new repository with git init.
     Step 3: Staging area- git add to add changes.
     Step 4: Commit by git commit to save changes inthe repository with a message.
     Step 5: Check status by git status to check which files are staged, unstaged and untracked.
     Step 6: Push to GitHub.
      Answer
     Commit- is a snapshot of your project at a specific point in time.
      Answer
     By use of git log to view history as each commit has unique hash and one can compare version by use of git difference 
     and undo a commit by git revert.

How does branching work in Git, and why is it an important feature for collaborative development on GitHub? Discuss the process of creating, using, and merging branches in a typical workflow.
        Answer
      By creating new branch using git branch.
      Switch branch- use git checkout to move between branches.
      Merge branches- Combine changes from one branch into another with git merge.
        Answer
      It allows you to work with different parts of a project without impacting the main branch. When work is complete, a 
      branch can be merged with main project.You can also switch between branches and work on different projects without 
      them intefering with each other.
        Answer
      To create branch we use; git branch e.g [User@localhost]$ git branch images
      Lets checkout to go our created branch. we use git checkout i.e [User@localhost]$ git checkout images
      We have now moved to new branch.
      To check status of the branch [User@localhost]$ git status
      To merge
             To merge our image branch and master branch, first we need to change to master branch
             [User@localhost]$ git checkout master
             Now we can merge [User@localhost]$ git merge image.

Explore the role of pull requests in the GitHub workflow. How do they facilitate code review and collaboration, and what are the typical steps involved in creating and merging a pull request?
      Answer
   Its role is to keep up-to-date with the changes and be able to get the most recent changes to your local copy.
     Answer
   By updateing your local repository and how they collaborate open-source contributions.
      Answer
  Step 1: Create feature branch
  Step 2: Git checkout
  Step 3: Commit changes git add
  Step 4: Open a pull request on Github.
  Step 5: Review and iterate.
  Step 6: Approve and merge.

Discuss the concept of "forking" a repository on GitHub. How does forking differ from cloning, and what are some scenarios where forking would be particularly useful?
         Answer
      Fork- Creating a copy of someone else's repository on your GitHub to make changes independently.
      Cloning- Is a local copy of a repository on your machine.
       Answer
      Fork                                                            Clone
      On your GitHub account.                          On your local machine.
      Contributing to other's projects.                Working on your own projects.

      Importants
      Open-source contributions
      Independent experimentation.
      Maintaining custom 

Examine the importance of issues and project boards on GitHub. How can they be used to track bugs, manage tasks, and improve project organization? Provide examples of how these tools can enhance collaborative efforts.
        Answer
    They used for : Bug tracking, task management and to streamline collaboration.
    Bug Tracking- by reporting and prioritizing bugs
                 example: **Title**: Implement dark mode toggle.
                           **Label** 'enhancement', 'UI'
                           **Assignees** @frontend-dex
      Task management- breaking down features into a actionable task.
      Improve project organization- Automation example "PR merged" - Move issue "Done"
Reflect on common challenges and best practices associated with using GitHub for version control. What are some common pitfalls new users might encounter, and what strategies can be employed to overcome them and ensure smooth collaboration?
            Answer
      Poor commit hygiene
        Big commits 
        soln: Automatic commits
      Merge conflicts chaos
        solutions: 
                Sync branches often
      Ignoring .gitignore
               Committing secrets
              solutions: 
                        Always set up .gitignore early.

       Best practices.
       Use a consistent branching strategy
       loverage pull requests sffectively
       Automate with GitHub actions.
