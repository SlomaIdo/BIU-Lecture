# Good practices for Data Science and Bioinformatics
## Git + Version Control
## Ido Sloma

---------------------

![figure1](https://th.bing.com/th/id/R.9bed9c8dbc91562b70a22f1b94e15055?rik=Pmf4Ucjt2GIH2Q&riu=http%3a%2f%2fmcmero.github.io%2fimages%2fbioinformatics_venn.png&ehk=p2S4eWu9RFAAIHfmCmJ5QDrW9B0tohSK%2bYh%2be7boDZ0%3d&risl=&pid=ImgRaw&r=0&sres=1&sresct=1 "Bioinformatics Venn")

Interdisciplinary field that develops methods and software tools for understanding biological data, in particular when the data sets are large and complex.

### Bioinformatics in the Biology Domain
1. LabOps – Consolidations, automation and operations of all the results data in real-time within data storage such as LIMS or cloud.
2. Biology has become much more complicated and sophisticated.

![figure2](https://th.bing.com/th/id/R.c27806bcdbc3d2d8685d62c0dd3bd856?rik=U4BcmTYZJ6SF8A&riu=http%3a%2f%2fmms.businesswire.com%2fmedia%2f20170109006363%2fen%2f563449%2f5%2fNovaSeq6000.jpg&ehk=KM5rc8QqCgZ0nXrNLYc1Y6BmxFKFFCGW1sa6UZMyj2c%3d&risl=&pid=ImgRaw&r=0 "Illumina Introduces the NovaSeq Series")

![figure3](https://i.ytimg.com/vi/1gXS31XJhqc/maxresdefault.jpg "celigo image cytometer")

### The Forbidden Figure

![figure4](https://th.bing.com/th/id/OIP.fPumGo5YiKkihMbV1JTl4QHaFj?pid=ImgDet&rs=1)


### We should now look at that…

![figure5](https://i0.wp.com/ncbiinsights.ncbi.nlm.nih.gov/wp-content/uploads/2020/06/Sra_growth.png?resize=1200%2C826&ssl=1 "NIH’s Sequence Read Archive is the largest, most diverse collection of next generation sequencing data from human, non-human and microbial sources.")

_"…SRA currently contains more than 36 petabytes (PB) of data and is projected to grow to 43 PB by 2023. Though the value of this resource grows with each new sample, the exponential growth experienced over the last decade (Right) threatens SRA sustainability. The storage footprint is growing more costly to maintain and the data more difficult to use at scale. The situation has reached a tipping point. SRA must be refactored to support FAIR data principles into the future.”_ (From NCBI Insights)

### FAIR data principles
Wilkinson, M. D. et al. The FAIR Guiding Principles for scientific data management and stewardship. Sci. Data 3:160018 doi: 10.1038/sdata.2016.18 (2016).

- The FAIR Guiding Principles
  - **To be Findable**
  - **To be Accessible**
  - **To be Interoperable**
  - **To be Reusable**

### Bioinformatics Methodology

The fact that FAIR principles are applied to the Bioinformatics domain is an example that this practice is dependent on the scaffold’s methodology.

- Bioinformaticians runs experiments as a **Biologist**.
- Bioinformaticians handles data like **Data Scientists**.
- Bioinformaticians writes tools like **Software developers**.
