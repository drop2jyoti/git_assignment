# Git Assignment - <drop2jyoti>
# Git Assignment - <drop2jyoti>

> a. What is an _issue_?
    Github issues are items created in repository to plan, discuss and track work. They are an alternative to email or Slack that keep communication isolated to a particular project.Issues can be opened on GitHub and even when they're closed, they remain available.They're also accessible to all collaborators for transperancy.

> b. What is a _pull request_?
    As per github docs, a pull request is a proposal to merge a set of changes from one branch into another. In a pull request, collaborators can review and discuss the proposed set of changes before they integrate the changes into the main codebase. Pull requests display the differences, or diffs, between the content in the source branch and the content in the target branch.
 
> c. How do I open up a _pull request_?
    From Github docs - 
    1. On GitHub.com, navigate to the main page of the repository.
    2. In the "Branch" menu, choose the branch that contains your commits
    3. Click Compare & pull request to create a pull request for the associated branch.
    4. Use the base branch dropdown menu to select the branch you'd like to merge your changes into, then use the compare branch drop-down menu to choose the topic branch you made your changes in.
    5. Type a title and description for your pull request.
    6. To create a pull request that is ready for review, click Create Pull Request.
   
> d. Give me a step by step guide on how to add someone to your repository.
    As per github docs - 
    1. Ask for the username of the person you're inviting as a collaborator.If they don't have a username yet, they can sign up for GitHub. 
    2. On GitHub.com, navigate to the main page of the repository.Under your repository name, click  Settings. 
    3. In the "Access" section of the sidebar, click  Collaborators.
    4. Click Add People
    5. In the search field, start typing the name of person you want to invite, then click a name in the list of matches.
    6. Click Add NAME to REPOSITORY.
    7. The user will receive an email inviting them to the repository. Once they accept your invitation, they will have collaborator access to your repository.

> e. What is the difference between `git` and `GitHub`?
    Git is a free, high-quality distributed version control system suitable for tracking modifications in source code in software development. It was originally created as an open-source system for coordinating tasks among programmers, but today it is widely used to track changes in any set of files. 
    
    GitHub is a web-based hosting service for Git repositories. It makes Git more user-friendly and also provides a platform for developers to share code with others.

> f. What does `git diff` do?
    If we want to see more details of the changes that we've made, we can use the command
    `git diff`
    It compares what is in our working directory to what is in our staging area. If we've made changes to our files without running git add , we'll see the comparison. If there are no differences, nothing will be shown.

> g. What is the `main` branch?
    In Git, the default branch is named master or main. When we first start making commits, we start at the master
    branch that automatically points to the last commit made.

> h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the `main` branch?
    No, because, the main branch is the working stable version of the code . One must do any changes in branch until the work is stable and build process checks including test runs are green, then you create a PR and merge it into main for other's to pull.

