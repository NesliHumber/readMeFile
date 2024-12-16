“Computer Programming Skill Swap Platform” Project Plan
 
Project Requirements and Goals
 
This project plan outlines the details of the purpose, main features, UI/UX design, interactive functionality development, team responsibilities, and technical requirements for developing the Computer Programming Skill Swap Platform. This platform offers services for users interested in collaborative learning in computer programming or those willing to share their experiences with others.
 
1.	Project Concept and Purpose
 
Website Purpose:
 
●  	This platform is designed for computer programmers of all levels who want to exchange knowledge and skills.
●  	It solves the problem of finding personalized learning opportunities in programming at a much lower cost or for free.
●  	It focuses on mutual skill exchange through virtual platforms enabled by information technology, rather than relying on traditional mentorship or paid tutoring.
●  	It provides an opportunity for experienced users to showcase their unique teaching packages and receive ratings from other users, focusing specifically on computer skills.
 
Main Features:
 
●  	User profile pages with interactive skill listings, including dropdown menus for languages and frameworks, as well as sliders to indicate expertise levels,
●  	Interactive skill matching charts and visualizations to suggest potential swap partners,
●  	Calendar-based scheduling system with time zone support for virtual coding sessions,
●  	Star rating widgets and customizable review forms for completed swaps or teaching packages
●  	Group formation and display interface for users interested in learning in a collaborative environment, showcasing the group's collective expertise level,
●  	Threaded discussion forum page with search functionality for general programming topics and questions,
●  	News & trend page displaying latest trends in the IT sector, with personalized suggestions for learners,
●  	Secure payment gateway integration for users who want to sell their unique materials
 
User Experience:
 
●  	Homepage: Layout with featured skill swaps and user testimonials
●  	Navigation bar: Responsive top menu with sections for Home Page, About Us, Profile (Log In), Find Swap, Groups, Forum, Trends & News, Shop, Contact
●  	User dashboard: Personalized interface displaying user information, skill data, completed and scheduled swaps (My Swaps), user category (learner or experienced), subscribed groups
●  	Look and Feel: A professional yet approachable & also accessible design that complies with the Web Content Accessibility Guidelines (WCAG), supported by an energetic color scheme and user-friendly interface elements
 
2.	Technologies and Tools
 
●  	Frontend: HTML, CSS and Bootstrap
●  	Interactive functionality: Node.js, JavaScript and React.js
●      Automation testing: Selenium or Playwright
●  	Deployment: GitHub Pages for hosting
 
3.	Project Roles and Team Responsibilities
 
●  	Frontend Developer & UI/UX Designer:
 
Mitzi Garcia
 
Responsibilities: Develops for the structure, layout, and styling of the website by implementing UI components using HTML and CSS, ensures consistent visual style in the context of Bootstrap framework, designs user-friendly interface elements compatible with the Web Content Accessibility Guidelines (WCAG)
 
●  	JavaScript Developer:
 
A. S.
 
Responsibilities: Implements the interactive and functional aspects of the site by setting up a Node.js server and utilizing React.js for dynamic user interfaces
 
●  	Project Manager:
 
R. V. S.
 
Responsibilities: Supervises the GitHub workflow, manages the issues & Project Board on GitHub, and facilitates communication and meetings among team members
 
●  	Quality Assurance Tester:
 
N. U.
 
Responsibilities: Develop and execute test cases to ensure proper functionality across all features by implementing both manual testing & automation testing using the Selenium-Cucumber or Playwright-Cucumber frameworks
 
●  	Documentation specialist:
 
N. U
 
Responsibilities: Create and maintain comprehensive project documentation (project plan, project status report, project closure report, UI design specifications, deployment and configuration report, test plan including test cases)
 






4.	Detailed Feature Breakdown
 
Feature: User Sign Up, User Log In, Profile Creation, User Dashboard
Tasks:
●	Create Sign Up, Profile/Log In shortcuts on the homepage navigation bar by linking to user dashboard interface
●	Create registration form with fields for username, email, password, and initial skill list
●	Design and implement user profile page with editable skill list and my swaps
 
Feature: Skill Matching Charts & Visuals
Tasks:

●	Develop functionality to sort and display user skills and suggest potential swap partners
●	Implement search filters (by language, skill level, availability)
●	Create an intuitive interface to display and sort potential matches
 
Feature: Swap Scheduling System
Tasks:
●	Implement a calendar component for users to set their availability
●	Create a booking system for users to request and confirm swap sessions
●	Set up email notifications for swap requests and confirmations
 
Feature: Rating and Review System
Tasks:

●	Design and implement a post-swap rating form
●	Create a review display component for user profiles
●	Implement a system to calculate and display average user ratings by using star rating widgets
 
Feature: Groups Dashboard – Group Formation and Display Interface
Tasks:
 
●	Develop functionality for users to create and join groups based on shared interests or skills
●	Design a group display interface showing group members, expertise levels, and upcoming activities
●	Implement a messaging feature within groups for communication among members
 
Feature: Discussion Forum
Tasks:
 
●	Create a forum structure with categories for different topics related to programming skills and experiences
●	Implement user authentication for posting and commenting in the forum
●	Develop tools for reporting inappropriate content and managing discussions

Feature: News & Trends Interface
Tasks:
 
●	Design an interface to display relevant news articles, tutorials, and resources related to programming
●	NOTE: API integration to pull in the latest trends will be discussed further
●	Create a bookmarking feature for users to save articles or resources of interest
 
Feature: Payment Gateway
Tasks:

●	Integrate a secure payment processing system
●	Develop a user-friendly checkout interface with options for different payment methods
●	Set up transaction history
 
5.	Project Workflow and GitHub Setup
 
Repository: Set up a repository with protection rules on GitHub
Branching Strategy: Use feature/<feature-name> for new features
Pull Requests: Require at least one review before merging into the main branch
Issues: Create detailed issues for each feature and task on GitHub
Project Board: Set up project board on GitHub
 


6.	Timeline and Milestones
 
Week 1: Complete project plan, set up repository, set up issues & project board and create an initial structure for all pages
Week 2: Implement user registration and basic profile functionality
Week 3: Develop skill matching chart and swap scheduling chart
Week 4: Add rating and review system, improve UI, and prepare for deployment
Week 5: Execute manual & automation testing, bug fixes, and deployment to GitHub Pages
 
7.	Final Presentation Outline

During presentation;
 
Introduction: A brief description of the concept of skill swapping in computer programming will be introduced.
Demo: All pages including homepage functionality, user dashboard, skill matching, scheduling, groups dashboard, forum page, news & trends will be demonstrated.
Technical Overview: The key technologies and challenges will be mentioned.
Future Enhancements: Potential features like future integration with an API, a gaming platform or coding challenge platform will be discussed.
Q&A: Questions from the audience will be addressed.

Project Phase 1 - Development Checkpoint for the Skill Swap Platform:

Progress Report

We've made significant progress on the development of Computer Programming Skill Swap Platform. Key features implemented include homepage basic structure, navigation bar structure, the user registration form, basic profile functionality, and the initial structure for many pages. The team has successfully set up the GitHub repository with protection rules including 1 mandatory pull request approval. We implemented the agreed-upon branching strategy as one main branch and separate feature branches for each page being developed with a naming convention feature/<page name>. Before the deployment, we will merge all feature branches into a develop branch for testing purposes. 

Challenges faced include integrating the calendar component for the swap scheduling system and optimizing the skill matching page. We're addressing these by conducting additional research and holding focused coding meetings. Another challenge is maintaining prevailing branching strategy when committing. We try to overcome these challenges by scheduling team meetings weekly according to team members’ availability. 

Currently, we're working on the further development for all pages as assigned on the linked project board on GitHub.

GitHub Commit Submission

    Commit SHA: 961bb08d317c7f6e820fdfa4f37abceb1b8b24fb
Commit details: feature/home_page
    Commit message: add homepage last version by M.G.

Merge commit SHA: 40fa8a4de0da96424cd511f742b9972d3c964add
Merge details: merged 1 commit into develop from feature/draft_1_home_page
Merge message: Adding DRAFT 1 for home page design by N.U.

Merge commit SHA: 9ed27a49003a33c06e8fb7d60b78c0de817cc3c2
Merge details: merged 1 commit into develop from feature/user_dashboard
Merge message: Adds user dashboard basic styling by N.U.

Merge commit SHA: f1c0754b57f0668a5373d74989ad0805785bef7a
Merge details: merged 1 commit into develop from feature/contact_page
Merge message: Add Contact Page by R.V.S.

Merge commit SHA: 447ff6c938f24d8bd084c541ca0e795c18e06406
Merge details: merged 1 commit into develop from feature/about_us
Merge message: Added About Us Page and Styling by A.S.

Merge commit SHA: e3749aaff7c1ccd5cdd334f1456e011eb7611316
Merge details: merged 1 commit into develop from feature/trends_and_news
Merge message: Added Trends and News Page with styling by A.S.
Our GitHub repository is organized as follows:

•	Repository link: https://github.com/NesliHumber/group9_project.git 

•	Branches:
•	main
•	develop
•	feature/draft_1_home_page
•	feature/home_page
•	feature/user_dashboard
•	feature/trends_and_news
•	feature/online_shop_page
•	feature/groups_page
•	feature/forums_page
•	feature/find_swap_page
•	feature/contact_page
•	feature/about_us

•	Project Board link: https://github.com/users/NesliHumber/projects/1/views/2

•	Project Board Details: 
•	To Do: Find Swap page, Forum page, Shop page, Create groups page
•	In Progress: User dashboard, Trends & news page
•	Done: Home page basic design, Contact Page, About Us

Our branch structure: 

 


Our project board: 

 



Development Phase Progress Report

1. Progress Report

Implemented Features

In this phase, our team has successfully implemented the following key features:
•	My Account: User dashboard includes sidebar with links to user-specific sections (Profile, Skills, Swaps, Messages, Settings), main content area displaying user statistics and recent activity, total swaps, skills learned, and skills taught in card format.
•	Find Swap: This function includes availability setting, booking system, email notifications. Users can set their availability for swap sessions using a datetime picker. The "Set Availability" button triggers a function to record the selected date and time. A confirmation message displays the set availability. Users can request a swap session by selecting a date and time. Upon submission, the system confirms the booking request and promises an email confirmation. The setAvailability() function handles recording user availability. The booking form submission is managed by an event listener that prevents default form submission and processes the booking request. A placeholder sendEmailNotification() function simulates sending email confirmations.
•	Groups: The main content area shows a list of available groups to join. Each group is represented by a card containing the group's name, offered courses, and a join button. Groups are defined via group objects. Each "Join" button has a click event that shows an alert confirming the user has joined the group.
•	Forum: Forum banner displays a welcome message and brief description of the forum's purpose. Each forum category has a brief description and an "Enter" link. A report object is defined with properties like title, description, submitter, and submission time. The submitReport() method logs the report submission. The report form validates that the report content is not empty. Upon successful submission, it displays a confirmation message and resets the form.

•	Shop: Cart preview displays the current number of items in the cart and the total price. Shop items display a list of educational courses with details like title, image, price, and description. Each item has "Add to Cart" and "Save for Later" buttons. Users can search for items using the search bar, which filters items in real-time based on the input. A button allows users to sort the displayed items by price in ascending order. Users can add items to their cart, which updates the cart count and total in the header. Clicking on an item opens a modal with more detailed information about the product.
These features contribute significantly to our functionality variety to offer our users an energetic and interactive user experience.

Challenges and Resolutions

During this development phase, we encountered several challenges:
•	Challenge 1: Since deployment of the web site was the main goal for this phase, the process of incorporating the feature/branch folders into deployment process was the main challenge for this phase. 
•	Resolution: We decided to continue our functionality development process via pushing separate feature/<feature-name> branches per web page and creating pull request from these branches to the develop branch on the remote. For the deployment, we decided to create a separate deploy branch on the remote and we added last version of every functionality to deploy branch. Our website deployment is rooting from this deploy branch until future version upgrades.
•	Challenge 2: Connecting all pages together under navigation bar interactively via active URL absolute paths was the second challenge during development process. 
•	Resolution: Our strategy is to use the same navigation bar codes inside every page with a common .css styling.
To improve our workflow and avoid similar issues in the future, we are conducting development of the pages and deployment of the pages separately not to lose any data.

Current Focus and Next Steps

Currently, our team is focusing on:
•	Current Task: increasing interactivity of the application by adding page specific .js files.
•	Upcoming Milestones:
o	A new group formation functionality will be added to the application that connects to group.html and group.js files after forming a new group structure. 
o	New forum formation functionality will be added inside the forum.html page via forum.js file.
o	Adding new items to be sold will be added as a functionality under user.html via user.js file which contains My Account page codes. Authorized users will be able to add their new items to be sold after approved by the sales team of our company.
o	Migrating our developed and ready-to-deploy codes to the main branch on the remote and to run the deployment process via main branch.
By addressing these tasks, we aim to ensure that we stay on track for our project timeline and also upgrade our application to offer our users a better swap experience related to IT.

2. GitHub Repository Submission
Commit SHA: f5559bf46403e96431d2272d9ddbed601c6a6e1b
Commit details: feature/home_page
Commit message: lastest homepage style by M.G.
Commit SHA: 4bfabf75b68e61a9fc18283192fe2955adb1cf3d
Commit details: feature/forums_page
Commit message: updated the forum by M.G.
Merge commit SHA: cbc87aeabd75be061d37a8b7808d60eae91dc77d
Commit details: Merge branch 'feature/forums_page' 
Commit message: Merge branch by M.G.
Commit SHA: 224bbc0389e7cf26295827929f44eede74dbc418
Commit details: feature/groups_page
Commit message: Adds groups page by N.U.
Commit SHA: c4224cacfe5ed21922fffd1f8173e9ebf5c9923b
Commit details: deploy
Commit message: Updates assets folder by N.U.
Commit SHA af5d33a79921f931554f3ea8b5c1ac57f36ac676 
    Commit details: feature/shop_page
    Commit message: Implement Shop page by A.S.
Commit SHA 10af82d9c3be17319bd85a814e115a1dc37d4175
            ac5a13b8e81363a90f07567b61e2fefc7f3c26e1
           cdb44f402ac7ca617e492e08c7c5c895d077e56e
           07c942f2b52a1e900892335d1e9662044e474e67
                     ae675a444935fcbe0d12d368f47e11fc7f495c56 
    Commit details: feature/find_swap_page
    Commit message: Commit of Find Swap Page by R.V.S.

Branching and Workflow

a. Feature-Specific Branches:
•	feature/<feature-name> format for the development of each functionality separately
•	develop branch for combining every functionality together
•	deploy branch for the deployment of the application without interrupting develop branch
•	main branch will be used for upgraded completed version of the application after completing testing stage


b. Regular Merging via Pull Requests:
We have established a process for merging changes through pull requests to maintain code quality. Every pull request needs a review before approval to the develop branch.








c. Use of GitHub Issues for Task Tracking:
Tasks are organized using GitHub Issues for effective tracking. All issues are closed since development and deployment has been made related to these issues: 





d. Project Board Activity:
Our project board is actively updated with tasks moving between “To Do,” “In Progress,” and “Done.”
 

Collaboration Evidence

•	Contributions from all team members are tracked in the commit history of each feature/<feature-name> branch, develop branch, and deploy branch with the id of responsible team member.
•	Peer review is evident through pull request comments and approvals:
 

 

Repository Organization

The repository is organized with clear structure via well-organized files and folders:
•	Source Code
•	Documentation
•	Assets (including screenshots demonstrating functionalities)

3. Feature Demonstration

We have prepared a screenshot demonstration showcasing the functionality of our implemented features inside assets folder in the deploy branch and a link has been added to the README file for easy access as follows: 

 

Home page:
 




About Us:
 

My Account:
 



Groups:
 

Groups confirmation window:
 

 
Forums:
 

A specific forum page:
 

 
Trends & News:
 


Contact Us:
 
 
Shop page:
 

Added to your cart confirmation window:
 

A specific item demonstration for sale:
 

Find Swap page
 

 
Find Swap Page – Requesting a swap
 
