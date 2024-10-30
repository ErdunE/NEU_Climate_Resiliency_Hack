# NEU_Climate_Resiliency_Hack (Hurric-Aid)
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
6. [Contact](#contact)
7. [RoadMap](#roadmap)
8. [Hurric - Aid Projec](#hurric---aid-project)
   - [Hurric - Aid Workflow Chart](#hurric---aid-workflow-chart)
   - [Hurric - Aid Website](#hurric---aid-website)
   - [Hurric - Aid Presentation PPT](#hurric---aid-presentation-ppt)

## Project Overview
We are XiaoYuanAlgorithm, a team from the Khoury College of Computer Sciences at Northeastern University, Miami campus, participating in the NEU Climate Resiliency Hackathon 2024. This event unites students, faculty, and industry professionals from across Northeastern’s global network to address critical environmental challenges using innovative technology.

Our project, Hurric-Aid, focuses on providing comprehensive support and resources to communities before, during, and after hurricanes. With a user-centered design, we aim to deliver critical services through multiple platforms (More detail showed in [Hurric - Aid Workflow Chart](#hurric---aid-workflow-chart)):

* Phone Support to ensure access when networks are down.
* Official Website as a centralized hub for information and resources.
* Mobile App for on-the-go access to emergency services, even offline.
* Offline Mode to offer critical disaster guides and maps without internet connectivity.

Hurric-Aid will feature a variety of functionalities:

* Hurricane Prediction Tools: Real-time impact assessments, hurricane paths, and heat maps based on user-provided zip codes.
* Pre-Hurricane Assistance: Services like supply and shelter information, home preparation support, and emergency alerts.
* Post-Hurricane Recovery Support: Access to medical aid, search and rescue, shelter, financial aid, and emotional support.

Our goal is to empower communities to prepare, stay safe, and recover quickly from hurricane events by providing timely, relevant, and accessible resources. Through Hurric-Aid, we hope to create a meaningful impact by promoting resilience and fostering sustainable recovery efforts.

We are excited to collaborate with fellow participants and mentors throughout the event, refine our ideas, and present Hurric-Aid as a solution that addresses real-world climate challenges. We look forward to learning, innovating, and making a lasting contribution to climate resiliency.
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
Fork the repository first then clone the repository from your repo to your local machine using the following commands:
```aiignore
git clone https://github.com/your username/repo.git

Example:
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

### RoadMap
* [Team XiaoYuanAlgorithm Roadmap: Climate Resiliency Hackathon 2024](https://docs.google.com/document/d/1RU39aRbAizuZ0VdRzSMunoO07cagzWLBvn38ZfMrXX0/edit?usp=sharing)

## Hurric - Aid Project
### Meeting Notes
#### Pre-Meeting
* [Climate Resiliency Hack 2024 Pre-Meeting Agenda](https://docs.google.com/document/d/1fK6I5keUTFAs0ThUzZEJv4Epk4Wb9wZE11wWNIxSIDU/edit?usp=sharing)

### Hurric - Aid Workflow Chart
[Hurric - Aid Flowchart](https://miro.com/welcomeonboard/dGJ0eHp5cnlZNVA5T0plV05PeTZPYXJFZ29mUGFHWXR2c3hvODdOZUxtRGU3OHhqSDQzNmRpQW1iMVBPRVUyMnwzNDU4NzY0NjAyMDkxNDczMjgzfDI=?share_link_id=835841782828)

### Hurric - Aid Website
[Hurric - Aid Website](https://18510600017lfk.wixsite.com/my-site-1)

### Hurric - Aid Presentation PPT
[Hurric - Aid Presentation PPT](https://docs.google.com/presentation/d/1FKNsKOywKi9vzU5wkc--MxD55cq6Gc34zhBwWGbAjkQ/edit?usp=sharing)
