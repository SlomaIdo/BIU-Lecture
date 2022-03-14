# Good practices for Data Science and Bioinformatics
## Git + Version Control
## Ido Sloma

---------------------
<img src="https://th.bing.com/th/id/R.9bed9c8dbc91562b70a22f1b94e15055?rik=Pmf4Ucjt2GIH2Q&riu=http%3a%2f%2fmcmero.github.io%2fimages%2fbioinformatics_venn.png&ehk=p2S4eWu9RFAAIHfmCmJ5QDrW9B0tohSK%2bYh%2be7boDZ0%3d&risl=&pid=ImgRaw&r=0&sres=1&sresct=1" alt="figure1"
title="Bioinformatics"
height="50%" width="50%" style="display:block; margin-left:auto; margin-right:auto"/>

**Interdisciplinary field that develops methods and software tools for understanding biological data, in particular when the data sets are large and complex.**

### Bioinformatics in the Biology Domain
1. **LabOps** – Consolidations, automation and operations of all the results data in real-time within data storage such as LIMS or cloud.
2. Biology has become much more complicated and sophisticated.

<img src="https://th.bing.com/th/id/R.c27806bcdbc3d2d8685d62c0dd3bd856?rik=U4BcmTYZJ6SF8A&riu=http%3a%2f%2fmms.businesswire.com%2fmedia%2f20170109006363%2fen%2f563449%2f5%2fNovaSeq6000.jpg&ehk=KM5rc8QqCgZ0nXrNLYc1Y6BmxFKFFCGW1sa6UZMyj2c%3d&risl=&pid=ImgRaw&r=0" alt="figure2"
title="Illumina Introduces the NovaSeq Series"
height="45%" width="45%"
style="display:block;
margin-left:0px;
margin-right:auto"/>

<img src="https://www.fannin.eu/wp-content/uploads/2020/04/Celigo-2-1.jpg" alt="figure3"
title="Celligo Image Cytometer"
height="35%" width="35%"
style="display:block;
margin-left:400px;
margin-right:auto"/>

### The Forbidden Figure

<img src="https://th.bing.com/th/id/OIP.fPumGo5YiKkihMbV1JTl4QHaFj?pid=ImgDet&rs=1" alt="figure4"
title="Forbidden Figure"
height="50%" width="50%"
style="display:block;
margin-left:auto;
margin-right:auto"/>


### We should now look at that…

<img src="https://i0.wp.com/ncbiinsights.ncbi.nlm.nih.gov/wp-content/uploads/2020/06/Sra_growth.png?resize=1200%2C826&ssl=1" alt="figure5"
title="Forbidden Figure"
height="90%" width="90%"
style="display:block;
  margin-left:auto;
  margin-right:auto"/>

NIH’s Sequence Read Archive is the largest, most diverse collection of next generation sequencing data from human, non-human and microbial sources.

_"…SRA currently contains more than 36 petabytes (PB) of data and is projected to grow to 43 PB by 2023. Though the value of this resource grows with each new sample, the exponential growth experienced over the last decade (Right) threatens SRA sustainability. The storage footprint is growing more costly to maintain and the data more difficult to use at scale. The situation has reached a tipping point. SRA must be refactored to support **FAIR data principles** into the future.”_ ([From NCBI Insights]("https://ncbiinsights.ncbi.nlm.nih.gov/2020/06/30/sra-rfi/"))

### FAIR data principles
[FAIR Guiding Principles](https://pubmed.ncbi.nlm.nih.gov/26978244/ "Wilkinson, M. D. et al. The FAIR Guiding Principles for scientific data management and stewardship. Sci. Data 3:160018 doi: 10.1038/sdata.2016.18 (2016")

- The FAIR Guiding Principles
  - **To be Findable**
  - **To be Accessible**
  - **To be Interoperable**
  - **To be Reusable**

### Bioinformatics Methodology

The fact that FAIR principles are applied to the Bioinformatics domain is an example of how this practice dependent on the scaffold’s methodologies.

- Bioinformaticians runs experiments as a **Biologist**.
- Bioinformaticians handles data like **Data Scientists**.
- Bioinformaticians writes tools like **Software developers**.

## Bioinformatics Methodology (software Development)

### 1. Agile Framework

- **AGILE methodology** is a practice that promotes continuous iteration of development and testing throughout the software development lifecycle of the project. In the Agile model, both development and testing activities are concurrent, unlike the **Waterfall model**.

<img src="https://th.bing.com/th/id/R.2bb5f2576ab9767efcf8f8b01cc0eb24?rik=riUa33U0YSucqA&riu=http%3a%2f%2fprojectresources.cdt.ca.gov%2fwp-content%2fuploads%2fsites%2f50%2f2017%2f08%2ftraditional-waterfall-versus-agile.png&ehk=lM57quAL%2bIL3YPF5yre0TZLuxarCAPl3WW422rZBAOA%3d&risl=&pid=ImgRaw&r=0" alt="waterfallVSAgile"
title="image Title"
height="75%" width="75%" style="display:block; margin-left:auto; margin-right:auto"/>

- 75% of the companies in the world apply Agile.

- Biotech recently started to embrace Agile as the main development framework.

#### Agile Values

<img src="https://www.scrumalliance.org/ScrumRedesignDEVSite/media/ScrumAllianceMedia/AgileOrganizations/L_scrum_alliance_website_agile_orgs_infographic_manifesto_1.png" alt="waterfallVSAgile"
title="Agile Values"
height="100%" width="100%" style="display:block; margin-left:auto; margin-right:auto"/>

#### Agile Principles

<img src="https://www.scrumalliance.org/ScrumRedesignDEVSite/media/ScrumAllianceMedia/AgileOrganizations/L_scrum_alliance_website_agile_orgs_infographic_agile_principles_1.png" alt="waterfallVSAgile"
title="Agile Values"
height="100%" width="100%" style="display:block; margin-left:auto; margin-right:auto"/>


- Our highest priority is to satisfy the customer
through early and continuous delivery
of valuable software.

- Welcome changing requirements, even late in
development. Agile processes harness change for
the customer's competitive advantage.

- Deliver working software frequently, from a
couple of weeks to a couple of months, with a
preference to the shorter timescale.

- Business people and developers must work
together daily throughout the project.

- Build projects around motivated individuals.
Give them the environment and support they need,
and trust them to get the job done.

- The most efficient and effective method of
conveying information to and within a development
team is face-to-face conversation.

- Working software is the primary measure of progress.

- Agile processes promote sustainable development.
The sponsors, developers, and users should be able
to maintain a constant pace indefinitely.

- Continuous attention to technical excellence
and good design enhances agility.

- Simplicity--the art of maximizing the amount
of work not done--is essential.

- The best architectures, requirements, and designs
emerge from self-organizing teams.

- At regular intervals, the team reflects on how
to become more effective, then tunes and adjusts
its behavior accordingly.

### 2. Software and System Components

### 3. Code Style

Bioinformatics Code languages:
- **R**: Especially Bioconductor.
- **Python**: For Every Reason.
- **Bash**: A must!

- Abstract tools:
  - **Nextflow** like tools.
  - **AWS**
  - **SQL**
  - **Linux** (Must!)

##### Coding is a manifest of your thinking.

1. [**Code style should be constant.**](https://google.github.io/styleguide/)
   1. Python
   2. R
   3. Bash

2. **Code should be well documented.**
   1. [R packages.](https://r-pkgs.org/)
   2. [Python modules and class.](https://www.sphinx-doc.org)
   3. Wiki / ReadMe file.


3. **Evolution of code**
   1. You start by a free monolithic script.
   2. You break to functions.
   3. You document the functions.
   4. Create classes and convert functions to methods.
   5. You test methods and/or functions with **unit tests**.
   6. You provide all of the resources for the code to run.
   7. Container the code with Docker.
   8. Make the code public on Github.

## Intro to Git and GitHub

**Git** is software for tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development. Its goals include speed, data integrity, and support for distributed, non-linear workflows (thousands of parallel branches running on different systems).

#### The Story of **Linus Torvalds**

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e8/Lc3_2018_%28263682303%29_%28cropped%29.jpeg/220px-Lc3_2018_%28263682303%29_%28cropped%29.jpeg" alt="Linus"
title="Linus Torvalds"
height="50%" width="50%"
style="display:block;
margin-left:auto;
margin-right:auto"/>

##### _**"open source is the only right way to do software"**_

### Git Exercise
#### Local Repository

This is to configure git service.
```
git config --global user.name "Isloma"
git config --global user.email ido@systemsbiomed.org
```

To Start a local git repository.
```
git init
git add
git commit
git commit -m "commit msg"
```

```
git log
git log --stat
git log -p
git log -all
git log --oneline
git log --reflog --oneline
```
#### Local Repository - Branches
```
git branch
git branch -d <branch>
git checkout <branch>

git merge <branch>

```

#### Remote Repository

#### Nextflow example
