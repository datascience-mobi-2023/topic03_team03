Data Analysis Project 2023
# Topic 3 : Proteome-wide Screen for RNA-dependent Proteins
## Subtopic 3: HeLa Cells Synchonized in Interphase
> Hannah Brehm, Johann Blakytny, Kira Hoffmann, Viktor Bonin
<br />
<div class="figure" style="text-align: center">
<img src="HNRPL_HUMAN.svg" alt="Fig. 1 - R-DeeP principle" width="100%" />
<p class="caption">Figure 1: Smoothed and normalized protein distribution with peak determination and gaussian fitting of the heterogeneous nuclear ribonucleoprotein (HNRPL_HUMAN). The grey area indicates the 95% confidence interval of the mean.</p>
</div>

In this project we investigated the RNA-dependence of different proteins. To do this we analyzed the protein distributions of 7086 genes from HeLa cells synchronized in interphase (data provided by Caudron-Herger *et al.*) (see **Figure 1**). The protein distributions were obtained from untreated and RNase-treated cell lysates separated on a sucrose gradient into 25 fractions and examined by mass spectrometry.

This repository contains the following files:

`Project Proposal`
> Original project proposal with planned analysis steps.

`Environment.RData`
> R workspace that contains all dataframes from our analysis.

`Table_HS_Non_RBP.RData`
> R workspace that contains the dataframe for all non RBPs from the RBP2Go databank.

`HeLa Cells Synchronized in Interphase.Rmd`
> Entire code that was used for analysis.

`Markdown.Rmd`
> R code used to generate final report.

`Final Report.Rmd` 
> Documentation of analysis and results.

`Final Presentation.pdf`
> Presentation of our results.
