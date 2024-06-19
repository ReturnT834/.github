# Description and guideline on the ReturnT834 organization
![return picture](https://github.com/ReturnT834/.github/blob/main/Return_Logo.png)
## What is the ReturnT834 organization?
This organization contains repositories of tools developed within [Return Project](https://www.fondazionereturn.it/en/) Task 8.3.4. These tools compute and analyse the relevant hazard indicators for future climate at the spatial and temporal scales of interest for sectoral applications and for the integration in future impact and risk assessment studies. The indicator set cover hydrometeorological, marine and biogeochemical processes in agreement with the collection and assessment for past and current climate provided by Return Task 8.2.3.
## Guideline for a repository in the organization

### How to add a repository?
Requirements to add a repository to the organization https://github.com/neccton-algo:
- Be a member of the [RETURNT834](https://github.com/ReturnT834) project
- Put the mandatory files in the respository as described [here](#content-of-a-repository).
- Follow the [recommendations](#recommendations) as much as possible
- Complete the table here :

| Repository name                                       | Owner[^1]                                             | NECCTON task | short description |
|       :---:                                           |  :---:                                            |     ---:     |    :---            |
|    [.github](https://github.com/ReturnT834)         | [@plazzari](https://www.github.com/plazzari)          | 8.3.4          | description of the github organization |
|    [.github](https://github.com/ReturnT834/NAD_analysis_tools)    | [@spiani](https://github.com/spiani)    | 8.2.4          | Visualization and statistical analysys of physical/biogeochemical indicators |


### Content of a repository
A GitHub repository of the NECCTON GitHub organization contains the following file:

- A `LICENCE` file: RETURN encourages the use of open-source licences.
- A `CODEOWNERS`file: indicate the main contacts for the repository. See [here](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-
code-owners) for more details.
- A `README` file: see the minimum requirement for the README file [here](#readme)
- One or several Jupyter notebooks to demonstrate the algorithm and the baseline. The baseline corresponds to an existing algorithm or a minimal solution (e.g. linear regression) that the algorithm is e
xpected to outperform.

#### README
The README file must contain a description for:
- the data source
- the baseline (or a link to the jupyter notebook of the baseline)
- the metrics used to validate the output(s) of the algorithm
- the list of dependencies (name of the dependency and full version number used) needed to use the code, and use language-specific tools to install the dependencies (recommended)
- the documentation (e.g., via a link). It should allow a potential user to understand the code and reuse it. 
- Citations and links for RETURN publications using or introducing the code, when applicable.
