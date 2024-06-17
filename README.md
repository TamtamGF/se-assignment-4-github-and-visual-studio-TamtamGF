[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/GvXCZgfk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15284985&assignment_repo_type=AssignmentRepo)
# SE-Assignment-4
Assignment: GitHub and Visual Studio
Instructions:
Answer the following questions based on your understanding of GitHub and Visual Studio. Provide detailed explanations and examples where appropriate.

Questions:
Introduction to GitHub:

What is GitHub, and what are its primary functions and features? Explain how it supports collaborative software development.

GitHub is a web-based platform for version control and collaboration that allows developers to manage and store their code using Git. It provides a graphical interface in addition to various functionalities to facilitate project management, collaboration, and code review. GitHub is widely used for both open-source and private projects, making it a central hub for developers and teams.

Primary Functions and Features
Version Control:

GitHub uses Git, a distributed version control system, to track changes in code.
Developers can revert to previous versions of their codebase, compare changes, and track the history of the project.
Repositories:

A repository (repo) is where the code and its history are stored.
Each repo contains all project files and the revision history.
Branching and Merging:

Branches allow developers to work on different features or fixes simultaneously.
Merging integrates changes from different branches into a single branch, typically the main branch.
Pull Requests:

Pull requests (PRs) are used to propose changes to the codebase.
They facilitate code review and discussion before merging changes into the main branch.
Issues:

Issues are used to track bugs, enhancements, tasks, or questions related to the project.
They support labeling, assignment, and linking to PRs for better project management.
Collaborative Tools:

GitHub supports team collaboration through features like team discussions, wikis, and project boards.
Project boards help in tracking progress and managing tasks using Kanban-style boards.
Continuous Integration and Deployment (CI/CD):

GitHub Actions allow automated workflows for testing, building, and deploying code.
Integrates with various CI/CD tools to streamline development pipelines.
Code Review:

Facilitates peer review through comments, suggestions, and discussions directly on the code.
Enables maintaining code quality and adherence to coding standards.
Security Features:

Dependabot alerts for security vulnerabilities in dependencies.
Secret scanning, security advisories, and more to keep the codebase secure.
Integrations:

GitHub integrates with numerous third-party services, including CI/CD tools, code editors, and project management tools.
How GitHub Supports Collaborative Software Development
Centralized Code Repository:

Provides a single place where the entire team can access the latest codebase.
Ensures everyone is working with the most up-to-date version of the project.
Version Control:

Enables multiple developers to work on different parts of the code simultaneously without conflicts.
Tracks contributions from each team member, maintaining a clear history of changes.
Branching and Merging:

Facilitates feature development and bug fixes in isolation without affecting the main codebase.
Supports collaborative efforts by allowing team members to review and discuss code changes before merging.
Pull Requests:

Enables team members to propose changes, review code, and suggest improvements.
Ensures that all changes are vetted and discussed, promoting knowledge sharing and code quality.
Issues and Project Management:

Helps in tracking tasks, bugs, and feature requests.
Assigns tasks to team members, sets priorities, and tracks progress, ensuring clear communication and accountability.
Code Review:

Promotes best practices and code standards through regular code reviews.
Helps in identifying potential issues early and improves the overall quality of the codebase.
Continuous Integration and Deployment:

Automates the testing and deployment process, reducing manual effort and errors.
Ensures that code changes are automatically tested, and the latest version is always ready for deployment.
Documentation and Knowledge Sharing:

Supports documentation through README files, wikis, and project pages.
Facilitates knowledge sharing and onboarding of new team members.


Repositories on GitHub:
What is a GitHub repository? Describe how to create a new repository and the essential elements that should be included in it.

A GitHub repository (or repo) is a storage space where your project's files and the entire revision history of your project are kept. It can contain directories, files, images, videos, spreadsheets, and data sets – anything your project needs. Repositories can be public, allowing anyone to view and contribute, or private, restricting access to specific users.

How to Create a New Repository
Creating a new repository on GitHub is straightforward. Here’s a step-by-step guide:

Sign In to GitHub:

Go to GitHub and log in with your GitHub credentials.
Navigate to the Repositories Tab:

On your GitHub homepage, click on the “Repositories” tab, or click on your profile icon and select “Your repositories.”
Create a New Repository:

Click the green “New” button on the Repositories page.
Fill in Repository Details:

Repository Name: Enter a unique name for your repository.
Description (optional): Add a brief description of your repository.
Public/Private: Choose whether your repository will be public (anyone can see it) or private (you choose who can see it).
Initialize with a README: It’s often helpful to initialize your repository with a README file. This file is essential for describing the purpose and details of the project.
Add .gitignore: Optionally, select a .gitignore template based on the type of project you are creating. This file specifies which files and directories to ignore when committing to the repository.
Choose a license: Optionally, add an open-source license to let others know what they can and can’t do with your code.
Create Repository:

Click the “Create repository” button.
Essential Elements That Should Be Included in a Repository
README.md:

The README file is crucial for providing an overview of your project. It should include:
Project title
Description
Installation instructions
Usage instructions
Contribution guidelines
License information
LICENSE:

Including a license file is important if you want others to know how they can legally use your code. Choose a license that suits your needs and add it to the repository.
.gitignore:

This file tells Git which files (or patterns) it should ignore. Typically, you would ignore temporary files, build artifacts, and dependencies.
CONTRIBUTING.md:

Guidelines for how others can contribute to your project. It may include code standards, submission requirements, and a code of conduct.
Code Files and Directories:

The actual source code of your project, organized in directories as necessary.
Documentation:

Detailed documentation of the project, which could be included in a /docs directory. This may consist of API documentation, architectural diagrams, and user manuals.
Tests:

A directory or files containing tests for your project to ensure code quality and reliability. Common directories include /tests or /specs.
CI/CD Configuration Files:

If you are using Continuous Integration/Continuous Deployment (CI/CD) tools, include configuration files like .github/workflows for GitHub Actions.


Version Control with Git:

Explain the concept of version control in the context of Git. How does GitHub enhance version control for developers?

Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later. Git is a distributed version control system that allows multiple developers to work on a project simultaneously without interfering with each other’s work.

Key Concepts in Git:

Repository (Repo):

A repository is a storage location for your project’s files and the history of changes made to those files.
Commit:

A commit is a snapshot of your repository at a specific point in time. It represents a set of changes or updates made to the files in the repository.
Branch:

A branch is a parallel version of a repository. It allows you to work on different features or fixes simultaneously without affecting the main codebase.
Merge:

Merging is the process of combining changes from different branches into a single branch.
Clone:

Cloning a repository means creating a local copy of the repository on your machine.
Pull:

Pulling means fetching changes from a remote repository and merging them into your local repository.
Push:

Pushing means sending your local commits to a remote repository.
How GitHub Enhances Version Control for Developers
GitHub is a web-based platform that uses Git for version control. It enhances version control for developers in several ways:

Centralized Collaboration:

GitHub provides a central location for repositories, making it easier for teams to collaborate on projects. Developers can share code, track changes, and work together efficiently.
Pull Requests:

Pull requests are a feature on GitHub that facilitates code review and discussion. Developers can propose changes, review others’ code, and merge changes after approval.
Issues and Project Management:

GitHub includes tools for tracking bugs, feature requests, and project management. Issues can be created, labeled, and assigned to team members to manage development tasks.
Continuous Integration and Deployment (CI/CD):

GitHub integrates with various CI/CD tools, allowing automatic testing, building, and deployment of code changes. GitHub Actions, in particular, provides a native CI/CD solution.
Security and Compliance:

GitHub offers security features like vulnerability alerts for dependencies, secret scanning, and security advisories to help maintain a secure codebase.
Documentation and Wikis:

GitHub provides tools for creating documentation and wikis within the repository, making it easier to maintain project documentation and onboarding materials.
Branching and Merging in Git
Branching and merging are core concepts in Git that enable efficient parallel development and integration.

Branching:

Create a Branch:

A branch is a separate line of development. By default, Git has a main branch called main or master. You can create additional branches to work on different features or fixes without affecting the main branch.
Command: git branch <branch-name>
Example: git branch feature-x
Switch to a Branch:

To start working on a branch, you need to switch to it.
Command: git checkout <branch-name>
Example: git checkout feature-x
Create and Switch:

You can create a new branch and switch to it in one command.
Command: git checkout -b <branch-name>
Example: git checkout -b feature-x
Merging:

Merge a Branch:

Once you’ve finished working on a branch, you can merge the changes back into the main branch or another branch.
Command: git merge <branch-name>
Example: git checkout main and then git merge feature-x
Handling Conflicts:

Sometimes, changes in different branches conflict. Git will mark the conflicts in the files, and you’ll need to resolve them manually.
After resolving conflicts, you complete the merge by committing the changes.


Branching and Merging in GitHub:



What are branches in GitHub, and why are they important? Describe the process of creating a branch, making changes, and merging it back into the main branch.

Branches in GitHub are separate lines of development that allow developers to work on different features, fixes, or experiments without affecting the main codebase (typically the main branch). Each branch represents a parallel version of the repository, enabling isolated development and testing of new code.

Importance of Branches
Isolation of Changes:

Branches provide a way to isolate new features or bug fixes from the main codebase until they are fully developed and tested.
Parallel Development:

Multiple developers can work concurrently on different branches, speeding up development and reducing conflicts.
Experimentation:

Branches allow for experimentation and exploration of new ideas without impacting the stability of the main project.
Code Reviews:

Branches facilitate code reviews through pull requests (PRs), where changes made in a branch can be reviewed, discussed, and approved before merging into the main branch.
Versioning and History:

Branches help maintain a clear version history of the project, showing which features were added or fixed at specific points in time.
Process of Creating a Branch, Making Changes, and Merging in GitHub
1. Create a Branch
To create a branch in GitHub:

Using GitHub Interface:

Navigate to your repository on GitHub.
Click on the branch selector dropdown (usually displaying main or master).
Enter a new branch name in the text field and press Enter or click on "Create branch" (or similar).

Pull Requests and Code Reviews:

What is a pull request in GitHub, and how does it facilitate code reviews and collaboration? Outline the steps to create and review a pull request.

A pull request (PR) in GitHub is a feature that allows you to propose changes to a repository and request that someone review and approve those changes before merging them into the main branch (e.g., main or master). It serves as a mechanism for discussing and reviewing code, coordinating collaboration among team members, and ensuring quality control in software development projects.

How Pull Requests Facilitate Code Reviews and Collaboration
Code Review:

Pull requests provide a structured way to review code changes. Team members can see the exact differences (diff) between the branches involved in the pull request.
Reviewers can add comments, suggest improvements, and ask questions directly within the context of the proposed changes.
Discussion and Feedback:

Pull requests encourage collaboration and discussion around code changes. Reviewers and contributors can engage in discussions, clarify intentions, and provide feedback to ensure the proposed changes meet the project's requirements and coding standards.
Quality Assurance:

Before merging, pull requests enable thorough testing and validation of changes. This helps identify and address issues early in the development process, reducing the likelihood of bugs and regressions in the main codebase.
Version Control and History:

Each pull request is associated with its own discussion thread and a clear history of changes. This transparency ensures that all modifications to the codebase are documented and traceable.
Collaborative Decision-Making:

Pull requests facilitate decision-making within the team. Contributors can propose alternative solutions, and reviewers can evaluate trade-offs and make informed decisions based on the feedback received.

GitHub Actions:

Explain what GitHub Actions are and how they can be used to automate workflows. Provide an example of a simple CI/CD pipeline using GitHub Actions.

GitHub Actions is a powerful feature of GitHub that allows you to automate various workflows directly within your GitHub repository. With GitHub Actions, you can define custom workflows to build, test, package, release, and deploy your code right from GitHub. These workflows are defined using YAML syntax and can be triggered by various events such as commits, pull requests, releases, and more.

Benefits of GitHub Actions
Automation: Automate repetitive tasks and workflows, saving time and reducing manual errors.

Integration: Integrate seamlessly with your existing GitHub repositories and services.

Flexibility: Customize workflows to fit your specific project requirements.

CI/CD: Implement continuous integration (CI) and continuous deployment (CD) pipelines directly within GitHub.

Community and Marketplace: Access a wide range of pre-built actions and workflows from the GitHub Marketplace.

Example of a Simple CI/CD Pipeline using GitHub Actions
Let's create a simple CI/CD pipeline for a hypothetical Node.js application. This pipeline will:

CI: Automatically run tests whenever a new commit is pushed to the repository's main branch.
CD: Deploy the application to a hosting platform (e.g., Heroku) whenever a new release is tagged.


Introduction to Visual Studio:

What is Visual Studio, and what are its key features? How does it differ from Visual Studio Code?

Visual Studio and Visual Studio Code are both popular development environments created by Microsoft, but they serve different purposes and have distinct features:

Visual Studio
Visual Studio (often referred to as Visual Studio IDE) is a comprehensive integrated development environment primarily used for building applications for Windows, Android, iOS, and web. It is a full-featured IDE that provides robust tools and capabilities for various programming languages and platforms.

Key Features of Visual Studio:
Wide Language Support:

Supports multiple programming languages including C#, C++, Visual Basic, F#, JavaScript, TypeScript, Python, and more.
Rich Debugging Capabilities:

Advanced debugging tools with features like breakpoints, watch windows, call stacks, and more.
Integrated Designers:

Includes designers for building graphical user interfaces (GUIs) for Windows Forms, WPF (Windows Presentation Foundation), and UWP (Universal Windows Platform) applications.
Extensive Project Templates:

Provides templates for various project types (e.g., console applications, web applications, mobile apps) to start development quickly.
NuGet Package Manager:

Built-in support for managing dependencies using NuGet, facilitating easy integration of third-party libraries.
Team Collaboration:

Integrates with Team Foundation Server (TFS) or Azure DevOps for source control, project management, and continuous integration.
Profiling and Performance Tools:

Tools for profiling application performance and identifying bottlenecks.
Extensibility:

Supports extensions through Visual Studio Marketplace to enhance functionality.
Visual Studio Code
Visual Studio Code (VS Code) is a lightweight, open-source code editor developed by Microsoft. It is highly customizable and designed for developers who work on various platforms and languages, focusing on simplicity, speed, and productivity.

Key Features of Visual Studio Code:
Cross-Platform:

Available on Windows, macOS, and Linux.
Language Support:

Supports a wide range of programming languages through extensions, including JavaScript, TypeScript, Python, PHP, Java, and more.
Integrated Terminal:

Built-in terminal for executing commands and scripts directly within the editor.
Rich Extensions Ecosystem:

Extensible via a vast library of extensions from the Visual Studio Code Marketplace, providing additional functionalities like debugging, linting, themes, and more.
Git Integration:

Built-in Git support with features like commit, push, pull, and branch management.
Customizable UI:

Allows customization of themes, keyboard shortcuts, and settings to tailor the editor to individual preferences.
Debugging Support:

Integrated debugging support for various languages and frameworks through extensions.
Task Automation:

Support for task automation using tasks.json and launch.json configuration files.
Differences Between Visual Studio and Visual Studio Code
Scope:

Visual Studio is a comprehensive IDE designed for building a wide range of applications (desktop, web, mobile) with extensive features like integrated designers and advanced debugging tools.
Visual Studio Code is a lightweight, extensible code editor focused on coding and text editing tasks, with a strong emphasis on customization and extensibility through extensions.
Target Audience:

Visual Studio targets developers working on complex applications that require extensive tooling and integration with Microsoft platforms and services.
Visual Studio Code caters to developers seeking a flexible and lightweight editor that supports multiple languages and platforms.
Complexity vs. Simplicity:

Visual Studio provides a more complex and feature-rich environment suitable for large-scale development projects and teams.
Visual Studio Code offers simplicity and agility, appealing to developers who prefer lightweight tools and want to customize their development environment.
Integration and Extensibility:

Both environments support extensions, but Visual Studio Code's marketplace offers a broader range of community-driven extensions due to its open-source nature and cross-platform support.


Integrating GitHub with Visual Studio:

Describe the steps to integrate a GitHub repository with Visual Studio. How does this integration enhance the development workflow?

Integrating a GitHub repository with Visual Studio enhances the development workflow by providing seamless collaboration, version control, and integration with GitHub's ecosystem. This allows developers to leverage GitHub's features directly within Visual Studio, facilitating efficient code management and team collaboration. Here are the steps to integrate a GitHub repository with Visual Studio:

Steps to Integrate GitHub Repository with Visual Studio
Install Visual Studio and GitHub Extension:

Ensure Visual Studio is installed on your machine. You can download it from the Visual Studio website.
Install the GitHub extension for Visual Studio:
Open Visual Studio.
Go to Extensions -> Manage Extensions.
Search for "GitHub Extension for Visual Studio" and install it.
Sign in to GitHub:

In Visual Studio, sign in to your GitHub account:
Go to Team Explorer (View -> Team Explorer or Ctrl+Alt+M).
Click on the "Connect" button and choose "GitHub".
Follow the prompts to sign in to your GitHub account.
Clone a GitHub Repository:

Clone an existing GitHub repository to your local machine:
In Team Explorer, click on Manage Connections -> Clone.
Enter the URL of the GitHub repository you want to clone (e.g., https://github.com/username/repository.git).
Choose a local directory where you want to clone the repository.
Click "Clone".
Open an Existing Project or Solution:

If the cloned repository contains a Visual Studio solution file (.sln), you can open it directly in Visual Studio:
In Team Explorer, navigate to the "Solutions" section.
Click on the solution file (*.sln) to open it in Visual Studio.
Commit and Push Changes:

Make changes to your code in Visual Studio.
Use Team Explorer to stage and commit changes:
Go to Team Explorer -> Changes.
Enter a commit message, select files to commit, and click "Commit All" (or "Commit Staged" if staging changes).
Click on Sync in Team Explorer to push changes to GitHub.
Pull Changes from GitHub:

Pull changes made by other team members from GitHub to your local repository:
In Team Explorer, click on Sync.
Click on Pull to fetch and merge changes from the remote repository to your local branch.
Create and Manage Branches:

Create new branches directly in Visual Studio:
In Team Explorer, go to the "Branches" section.
Click on New Branch to create a new branch based on the current branch.
Enter a branch name and click "Create Branch".
Switch between branches and manage branches easily using Team Explorer.
Use GitHub Features:

Utilize GitHub features like pull requests, issues, and project boards directly within Visual Studio through the GitHub extension.
Manage pull requests, review code, and collaborate with team members without leaving your IDE.

Debugging in Visual Studio:

Explain the debugging tools available in Visual Studio. How can developers use these tools to identify and fix issues in their code?

Visual Studio provides a robust set of debugging tools that help developers identify and fix issues in their code efficiently. These tools are designed to provide deep insights into code execution, variable values, and program flow, enabling developers to diagnose and resolve bugs effectively. Here's an overview of the debugging tools available in Visual Studio and how developers can use them:

Debugging Tools in Visual Studio
Breakpoints:

Purpose: Breakpoints allow developers to pause the execution of their code at specific lines or conditions.
Usage:
Set breakpoints by clicking in the left margin of the code editor or pressing F9 on the desired line.
Conditional breakpoints allow pausing only when specific conditions are met.
When execution reaches a breakpoint, Visual Studio enters debugging mode, allowing developers to inspect variables and step through code.
Stepping Through Code:

Purpose: Developers can step through code line by line to understand its execution flow and behavior.
Usage:
Use F10 to step over the current line without entering function calls.
Use F11 to step into function calls, allowing inspection of called functions and their variables.
Watch and QuickWatch Windows:

Purpose: Allows developers to monitor and inspect the values of variables and expressions during debugging.
Usage:
Add variables to the Watch window to monitor their values as the code executes.
Use QuickWatch (Shift+F9) to evaluate expressions and variables at any point in the code.
Autos and Locals Windows:

Purpose: Provides automatic and local variables visible in the current scope during debugging.
Usage:
Autos window shows variables relevant to the current line of code being debugged.
Locals window displays all variables in the current scope, including parameters and local variables.
Call Stack Window:

Purpose: Shows the current call stack, indicating the sequence of function calls that led to the current point in the code.
Usage:
Helps trace back through the execution path to understand how the code reached the current state.
Allows navigation to different stack frames for inspection of variables and code flow.
Exception Settings:

Purpose: Allows developers to control how Visual Studio handles exceptions during debugging.
Usage:
Enable or disable specific exceptions to break execution when they occur.
Configure behavior for unhandled exceptions and specific exception types.
Diagnostic Tools:

Purpose: Provides real-time performance and diagnostic information during debugging.
Usage:
Includes CPU Usage, Memory Usage, and other diagnostics to analyze application performance.
Timeline view helps identify performance bottlenecks and memory leaks.

Collaborative Development using GitHub and Visual Studio:

Discuss how GitHub and Visual Studio can be used together to support collaborative development. Provide a real-world example of a project that benefits from this integration.

GitHub and Visual Studio together provide a powerful platform for collaborative development, combining robust version control, project management, and integrated development tools. This integration supports teams in building software projects efficiently, ensuring code quality, and facilitating seamless collaboration across distributed teams. Here’s how GitHub and Visual Studio can be used together and a real-world example of a project that benefits from this integration:

Using GitHub and Visual Studio for Collaborative Development
Version Control with Git:

GitHub: Acts as a central repository hosting Git repositories. Developers push code changes to GitHub, track revisions, and manage branches.
Visual Studio: Integrates with GitHub, allowing developers to clone repositories, commit changes, manage branches, and synchronize code seamlessly within the IDE.
Collaboration Features:

GitHub Issues and Projects: Teams use GitHub Issues for bug tracking, feature requests, and task management. Projects organize issues and tasks into boards (e.g., Kanban boards) for better project visibility and workflow management.
Visual Studio Integration: Developers can view and manage GitHub issues directly within Visual Studio using the GitHub extension. They can assign issues, track progress, and link code changes to specific issues for traceability.
Pull Requests and Code Reviews:

GitHub Pull Requests: Developers create pull requests (PRs) to propose changes and initiate code reviews. Team members review code, provide feedback, and approve changes before merging them into the main branch.
Visual Studio: Supports PR creation, review, and management within the IDE. Developers can view PR details, review changes, leave comments, and merge PRs directly from Visual Studio.
Continuous Integration and Deployment (CI/CD):

GitHub Actions: Automates CI/CD pipelines directly from GitHub. Developers define workflows (e.g., build, test, deploy) using YAML syntax and trigger them based on events (e.g., push, pull request, release).
Visual Studio: Integrates with CI/CD pipelines configured in GitHub Actions. Developers can monitor pipeline status, view build logs, and manage deployment tasks within Visual Studio.
Real-World Example: Web Application Development
Scenario: A team of developers is building a web application using GitHub and Visual Studio for collaborative development.

Repository Setup:

The project repository is hosted on GitHub, containing code for the web application, including HTML, CSS, JavaScript, and backend services written in Python.
Collaborative Coding:

Developers clone the GitHub repository into Visual Studio to work on different features and components of the web application.
They use branches to work on new features or bug fixes independently without disrupting the main development branch (main).
Issue Tracking and Project Management:

Team members use GitHub Issues to report bugs, outline new features, and discuss enhancements.
Issues are categorized and prioritized within GitHub Projects, where they are organized into boards (e.g., To Do, In Progress, Done).
Code Reviews and Pull Requests:

When a developer completes a feature or bug fix, they create a pull request on GitHub.
Team members review the code changes, provide feedback, and approve the pull request after ensuring code quality and adherence to coding standards.
Continuous Integration and Deployment:

GitHub Actions is configured to trigger automated builds and tests whenever changes are pushed or pull requests are created.
Visual Studio allows developers to monitor build status, review test results, and manage deployment configurations directly from the IDE.
Deployment and Maintenance:

Once a pull request is approved and merged into the main branch, GitHub Actions automatically deploys the updated web application to a staging or production environment.
Visual Studio continues to be used for ongoing maintenance, bug fixes, and feature enhancements, with seamless integration with GitHub for version control and collaboration.
Benefits of Integration
Efficient Collaboration: GitHub and Visual Studio streamline collaboration by providing a unified platform for code hosting, issue tracking, and code reviews.

Enhanced Code Quality: Code reviews and automated testing ensure high code quality and reduce the risk of introducing bugs into the application.

Improved Productivity: Integrated workflows, combined with automation through GitHub Actions, accelerate development cycles and enable rapid iteration and deployment of features.

Visibility and Traceability: Project boards, pull requests, and CI/CD pipelines provide visibility into project progress, task ownership, and code changes, enhancing transparency across the development team

Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
