# NEU_Climate_Resiliency_Hack
A project for the Climate Resiliency Hack event
## Table of Contents
1. [Project Overview](#project-overview)
2. [Team Name](#team-name)
3. [Team Member](#team-member)
4. [Event Schedule](#event-schedule)
5. [Guidance for Collaborators](#guidance-for-collaborators)
    - [Getting Started](#getting-started)
        - [1. Fork and Clone the Repository](#1-fork-and-clone-the-repository)
    - [Branching Workflow](#branching-workflow)
        - [2. Create a New Branch](#2-create-a-new-branch)
        - [3. Make Changes and Commit](#3-make-changes-and-commit)
            - [Stage the changes](#stage-the-changes)
            - [Commit the changes](#commit-the-changes)
        - [4. Push Your Branch to GitHub](#4-push-your-branch-to-github)
        - [5. Create a Pull Request (PR)](#5-create-a-pull-request-pr)
        - [6. Code Review and Merge](#6-code-review-and-merge)
        - [7. Syncing with Main Branch](#7-syncing-with-main-branch)
            - [Switch to the main branch](#switch-to-the-main-branch)
            - [Pull the latest changes](#pull-the-latest-changes)
            - [Switch back to your feature branch](#switch-back-to-your-feature-branch)
            - [Rebase with the main branch](#rebase-with-the-main-branch)
## Project Overview
We are XiaoYuanAlgorithm, a team from the Khoury College of Computer Sciences at Northeastern University, Miami campus, participating in the NEU Climate Resiliency Hackathon 2024. This event brings together students, faculty, and industry experts from across all Northeastern campuses to tackle pressing environmental challenges through innovative technology solutions.

Our team is still in the idea exploration phase, and we are open to approaches as the hackathon progresses, we will refine our focus and identify a specific project to develop. Whether it involves building a data-driven tool, designing a mobile application, or creating a visualization dashboard, our goal is to contribute meaningfully to climate solutions that empower communities and promote sustainability.

This README will be updated with more details as our project takes shape. We look forward to collaborating with other participants and mentors, learning new skills, and presenting our final project at the end of the event.
## Team Name
* **XiaoYuanAlgorithm**
## Team Member
* **[Erdun](https://github.com/ErdunE)**
* **[Will](https://github.com/QingyuanWan)**
* **[Raj](https://github.com/kimblewick)**
* **[Kai](https://github.com/arete7-kai)**
## Event Schedule

| **Date**              | **Time (ET)**           | **Topic**                                              | **Mode**    | **Location** |  
|-----------------------|-------------------------|--------------------------------------------------------|-------------|--------------|
| **Monday, October 28**|                         |                                                        |             |              |
|                       | 1:00pm – 2:30pm         | Hackathon Kickoff!                                     | Virtual     | [Zoom Link](https://northeastern.zoom.us/j/96206096905?pwd=1AqYrRYqmrZMhAYbtk5pbEvn3a4a4d.1) |  
|                       | 3:00pm – 4:30pm         | Workshop #1: Climate Anxiety Panel                    | Virtual     | [Zoom Link](https://northeastern.zoom.us/j/98203675611?pwd=5taU3HehwYGvjoRZ4v0bMBEUPmFaH7.1) |  
|                       | 4:30pm – 6:30pm         | Mentorship Drop-in Hours                               | In-person   | Room 514     |  
| **Tuesday, October 29**|                        |                                                        |             |              |
|                       | 12:30pm – 2:30pm        | Mentorship Drop-in Hours                               | In-person   | Room 514     |  
|                       | 3:00pm – 4:30pm         | Workshop #2: Careers in Climate & Sustainability      | Virtual     | [Zoom Link](https://northeastern.zoom.us/j/96373837917?pwd=7n6acRyykGHUQzKag9kQmuVb97Hb15.1) |  
| **Wednesday, October 30**|                     |                                                        |             |              |
|                       | 12:00pm – 2:00pm        | Final Mentorship Drop-in Hours                         | In-person   | Room 514     |  
|                       | 2:30pm – 4:30pm         | Final Pitch Sessions to Judges                         | In-person   | Room 514     |  
|                       |                         | (*Teams will be assigned a time, announced by Oct 29, 5pm*) |         |              |  
|                       | 6:00pm – 7:00pm         | Award Ceremony                                         | In-person   | Room 514     |  
|                       | 7:00pm – 8:00pm         | Celebration & Networking                               | In-person   | Room 514     |  

If you have any questions, feel free to reach out on the event's **[Questions Form]**.

## Guidance for Collaborators
This guide provides step-by-step instructions on setting up the project locally, working on feature branches, and contributing through Pull Requests (PRs). Follow the branching workflow to ensure that every contribution is properly reviewed and merged.
### Getting Started
#### 1. Fork and Clone the Repository
Fork the repository first then clone the repository to your local machine using the following commands:
```aiignore
git clone https://github.com/ErdunE/NEU_Climate_Resiliency_Hack.git
cd NEU_Climate_Resiliency_Hack
```
### Branching Workflow
We will follow a feature-branch workflow to ensure that changes are isolated, reviewed, and approved before merging into the main branch.
#### 2. Create a New Branch
Each team member should create their own feature branch to work on a specific task or feature:
```aiignore
git checkout -b feature/<your-feature-name>

Example:
git checkout -b feature/ui-design
```
#### 3. Make Changes and Commit
Add meaningful comments in your code where necessary to help others understand it.
##### Stage the changes:
```aiignore
git add .
```
##### Commit the changes:
Write clear commit messages which means explain what you changed and why.
```aiignore
git commit -m "Add feature: <describe what you did>"

Example:
git commit -m "Add UI and styling"
```
#### 4. Push Your Branch to GitHub
Once you’ve committed your changes, push your branch to the remote repository.
```aiignore
git push origin feature/<your-feature-name>

Example:
git push origin feature/ui-design
```
#### 5. Create a Pull Request (PR)
1. Go to the GitHub repository: https://github.com/ErdunE/NEU_Climate_Resiliency_Hack
2. Click on "Pull Requests".
3. Click "New Pull Request".
4. Choose the main branch and the compare branch (your feature branch).
5. Add a title and description explaining your changes.
6. Assign at least one teammate as a reviewer and submit the PR.

#### 6. Code Review and Merge
1. Once the PR is submitted, it will be reviewed by another team member. They may suggest improvements or request changes.
2. After the code is approved, the reviewer will merge the PR into the main branch.
3. After merging, delete your feature branch from GitHub to keep the repository clean.
```aiignore
# Deletes the local branch
git branch -d feature/<your-feature-name>  
# Deletes the remote branch
git push origin --delete feature/<your-feature-name>  
```
#### 7. Syncing with Main Branch
If other changes have been merged into main while you were working, you’ll need to sync your branch:
##### Switch to the main branch:
```aiignore
git checkout main
```
##### Pull the latest changes:
```aiignore
git pull origin main
```
##### Switch back to your feature branch:
```aiignore
git checkout feature/<your-feature-name>
```
##### Rebase with the main branch:
```aiignore
git rebase main
```
##### If encounter conflicts and you can't resolve it quickly with google or chatgpt, reach out to the team for help

## Contact
For any questions, please contact:
* **Erdun:** e.e@northeastern.edu
* **Will:** wan.qing@northeastern.edu
* **Raj:** kavathekar.r@northeastern.edu
* **Kai:** liu.fengka@northeastern.edu