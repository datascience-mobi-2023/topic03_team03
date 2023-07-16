<div id="user-content-toc">
  <ul>
    <summary>Data Analysis Project 2023
      <h1 style="display: inline-block;">Topic 3: Proteome-wide Screen for RNA-dependent Proteins</h1>
  </summary>
    </ul>
</div>
<h2> Subtopic 3: HeLa Cells Synchronized in Interphase </h2>
  
Contributors: Hannah Brehm, Johann Blakytny, Kira Hoffmann, Viktor Bonin

<br />
<div class="figure" style="text-align: center">
<img src="Data\HNRPL_HUMAN.svg" alt="Fig. 1 - R-DeeP principle" width="80%" />
<p class="caption"> Figure 1: Smoothed and normalized protein distributions with peak determination and Gaussian fitting of the heterogeneous nuclear ribonucleoprotein L (HNRPL_HUMAN). The grey areas indicate the 95% confidence interval of the mean.</p>
</div>

### About

In this project, we investigated RNA dependence in the human proteome by analyzing the protein distributions of 7086 genes in HeLa cells synchronized in interphase (data provided by Caudron-Herger *et al.*, 2020) (see **Figure 1**). The protein distributions were obtained from untreated and RNase-treated cell lysates separated on a sucrose gradient into 25 fractions. The proteins in each fraction were examined using mass spectrometry.


### Files on this Repository

| Name | Description |
| --- | --- |
| `Final_Report.pdf` | Documentation of project, including an Introduction, Materials and Methods, Results and Discussion |
| `Final_Report.Rmd` | R code used to generate the final report |
| `Analysis.Rmd` | Entire R code that was used for analysis of the mass spectrometry data |
| `README.md` | This file |
| `Data` | Folder that contains the datasets generated and used in our analysis (`Environment.RData` and `Table_HS_Non_RBP.RData`) with a Excel spreadsheet describing all dataframes in German (`Datensätze.xlsx`) and the vector graphic used for figure 1 of `README.md` (`HNRPL_HUMAN.svg`) |
| `Project_Proposal` | Folder that contains .pdf and .pptx versions of the initial project proposal with planned analysis steps |


### References

Caudron-Herger, M., Wassmer, E., Nasa, I., Schultz, A.-S., Seiler, J., Kettenbach, A.N., and Diederichs, S. (2020). Identification, quantification and bioinformatic analysis of RNA-dependent proteins by RNase treatment and density gradient ultracentrifugation using R-DeeP. Nat. Protoc. *15*, 1338-1370.
