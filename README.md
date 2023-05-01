## CS506-Final Project
#### BU Sustainability-Waste
#### Team 1 - Junyi Zhu, Abdelazim Lokma, Karan Vombatkere

### Project Overview
BU Sustainability is responsible for the transformation of Boston University’s planning, operations, and culture toward a sustainable and equitable future.They have provided our team with multiple spreadsheets, containing data from their 3rd party vendor Contelligent and their waste vendor Casella. By analyzing these datasets, our team aimed to identify opportunities for improving waste storage during adverse weather conditions. Specifically, we were seeking to answer two main questions: whether weather affects waste generation and, if so, how it does so. Our team first began by analyzing the data through preliminary observations, and after some pre-processing of the data, provided some conclusionary results to answer the original questions, as well as supporting data regarding other factors that impacted waste generation.

### Important Project File Links:
- Link to the Google Drive Team Folder: https://drive.google.com/drive/u/1/folders/1d4jZLg0luCfVMGBHrdJcNN7WQWbXumGo
- Link to Final Presentation Recording: https://bostonu.zoom.us/rec/share/nfy-HijKmoO2RHN7FzWtPk52t8-yQmYuJVUCWS9zx1-OANtj7gXFdPYb-xa9Qx8S.WUwebrdIXjb_A66x

### Description of Files in Repository
Note that all Team 1 code and deliverables are available in the `spring23-team-1` folder, and the most up to date version of deliverables is in the `team-1-kv` branch. 
1. `data` folder contains all the raw data files
2. `deliverables` folder contains each deliverable pdf file
3. Code overview for each team member's analysis is outlined in detail in the next section.


### Team Member Contributions
This section outlines the contributions of each team member, and an overview of the code in their branch on Github.
1. Junyi Zhu, `team-1-JunyiZ`: Contribution includes data collection, dataset management and data analysis. Specifically, enriched the given dataset by collecting data from NOAA Database to explore more features other than temperature. Also explored the weather impact by looking at correlations between features and psi/tonnages from the perspective of device(site). Based on correlations, tried to cluster the sites and attempted to make a LightGBM prediction model that predict the next day’s waste output on data from last few days.<br>
**Notebook with code and analysis:** `ds-bu-sustainability-waste/spring23-team-1/DataAnalysis_JunyiZhu.ipynb`

2. Abdelazim Lokma, `team-1-abdelazim`: Focused on the BU-Daily weights document, starting research by attempting to find a correlation between the tonnages of Trash, Compost, and Recycling containers. Then decided to visualize the data from this document in different ways, from charts to dynamic heat maps in order to visualize how containers across campus change in their outputs throughout the year.<br>
**Notebook with code and analysis:** `ds-bu-sustainability-waste/spring23-team-1/data/BU-Waste-Analysis-1.ipynb`

3. Karan Vombatkere, `team-1-kv`: Focused on the following tasks: Preliminary analysis on waste generation and compactions; Data audit for readings, daily weights, psi readings, alert, events files; Data merging process and joining across different files; Timeline plots for each site by different material type, and analysis by type; Clustering sites by tonnage and temperature. Also worked towards coordinating the team’s work and deliverables with client and PM meetings weekly.<br>
**Notebook Code and data analysis:** `ds-bu-sustainability-waste/spring23-team-1/DataAnalysis_KV.ipynb`


### Add Users
If your project has multiple teams add changes (code, deliverables, data, etc.) to your team folder.
Create a new branch from your team branch (ex. branch name: <code>sp23-team-1</code>, <code>sp23-team-2</code>,...etc.), add changes to your team folder (on the new branch you just created).

Open a Pull Request to your team branch (ex. branch name: <code>sp23-team-1</code>). Add your PM and TE as reviewers.  ***Do not delete any team folders.***
At the end of the semester during project wrap up open a final Pull Request to <code>dev</code> from your team branch. 

To  add yourself to the repository, open a Pull Request modifying `COLLABORATORS`, entering your GitHub username in a newline.
All Pull Requests must follow the Pull Request Template, with a title formatted like such `[Project Name]: <Descriptive Title>`
