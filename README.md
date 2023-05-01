## CS506-Final Project
#### BU Sustainability-Waste
#### Team 1 - Junyi Zhu, Abdelazim Lokma, Karan Vombatkere

### Project Overview
BU Sustainability is responsible for the transformation of Boston University’s planning, operations, and culture toward a sustainable and equitable future.They have provided our team with multiple spreadsheets, containing data from their 3rd party vendor Contelligent and their waste vendor Casella. By analyzing these datasets, our team aimed to identify opportunities for improving waste storage during adverse weather conditions. Specifically, we were seeking to answer two main questions: whether weather affects waste generation and, if so, how it does so. Our team first began by analyzing the data through preliminary observations, and after some pre-processing of the data, provided some conclusionary results to answer the original questions, as well as supporting data regarding other factors that impacted waste generation.

### Important Project File Links:
- Link to the Google Drive Team Folder: https://drive.google.com/drive/u/1/folders/1d4jZLg0luCfVMGBHrdJcNN7WQWbXumGo
- Link to Final Presentation Recording: https://bostonu.zoom.us/rec/share/nfy-HijKmoO2RHN7FzWtPk52t8-yQmYuJVUCWS9zx1-OANtj7gXFdPYb-xa9Qx8S.WUwebrdIXjb_A66x

### Description of Files in Repo
1. `data` folder contains all the raw data files
2. `deliverables` folder contains each deliverable pdf file


### Team Member Contributions
1. Junyi Zhu: My contribution includes data collection, dataset management and data analysis. Specifically, I enriched the given dataset by collecting data from NOAA Database to explore more features other than temperature. I also explored the weather impact by looking at correlations between features and psi/tonnages from the perspective of device(site). Based on correlations, I tried to cluster the sites. Moreover, I attempted to make a prediction model that predict the next day’s waste output on data from last few days.

2. Abdelazim Lokma: I focused on the BU-Daily weights document, starting my research by attempting to find a correlation between the tonnages of Trash, Compost, and Recycling containers. I then decided to visualize the data from this document in different ways, from charts to dynamic heat maps in order to visualize how containers across campus change in their outputs throughout the year. 

3. Karan Vombatkere: I focused on the following, as well as coordinating the team’s work and deliverables with client and PM meetings: Preliminary analysis on waste generation and compactions; Data audit for readings, daily weights, psi readings, alert, events files; Data merging process and joining across different files; Timeline plots for each site by different material type, and analysis by type; Clustering sites by tonnage and temperature


### Add Users
If your project has multiple teams add changes (code, deliverables, data, etc.) to your team folder.
Create a new branch from your team branch (ex. branch name: <code>sp23-team-1</code>, <code>sp23-team-2</code>,...etc.), add changes to your team folder (on the new branch you just created).

Open a Pull Request to your team branch (ex. branch name: <code>sp23-team-1</code>). Add your PM and TE as reviewers.  ***Do not delete any team folders.***
At the end of the semester during project wrap up open a final Pull Request to <code>dev</code> from your team branch. 

To  add yourself to the repository, open a Pull Request modifying `COLLABORATORS`, entering your GitHub username in a newline.
All Pull Requests must follow the Pull Request Template, with a title formatted like such `[Project Name]: <Descriptive Title>`
