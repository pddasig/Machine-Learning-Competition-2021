# 2021 SPWLA PDDA Machine Learning Competition
## Well-log based reservoir property estimation with machine learning


<img style="float: left;" src="image/pdda.png" alt="pdda" title="" width="300" height="100"/>
<!-- 
- <a>Call for Registration </a>
- <a>Sponsoring Opportunities</a>
- <a>Contest Committee</a>
- <a>Description</a>
- <a>Evaluation</a>
- <a>Timeline</a>
- <a>Competition Rules</a>
- <a>Prize Policy</a>
- <a>Leaderboard</a>
- <a>Data Licensing</a> -->


### <a>Call for Registration</a>
SPWLA PDDA SIG is excited to announce its 2021 machine learning contest!
This contest is open to all petrophysics enthusiasts. Top winning teams will be awarded prizes and invited to present at the PDDA SIG annual meeting. Please register with Lei Fu (pdda_sig@swpla.org) by submitting your team information (names, affiliations, and emails), before October 15, 2021. The dataset comes from the Equinor Volve field. A data repository is available at: https://github.com/pddasig/Machine-Learning-Competition-2021

### <a>Sponsoring Opportunities</a>
[SPWLA-PDDA](https://www.spwla.org/SPWLA/Chapters_SIGs/SIGs/PDDA/PDDA.aspx) SIG is accepting sponsorship for this event to award the top winning teams. Please contact Lei Fu (pdda_sig@swpla.org) for details.

### <a>Contest Committee</a>
Lei Fu, Yanxiang Yu, Chicheng Xu, Michael Ashby, McDonald Andy, Bin Dai

<!-- #region -->
### <a>Description</a>
#### <a>Background</a>
Well logs are interpreted/processed to estimate the in-situ reservoir properties (petrophysical, geomechanical, and geochemical), which is essential for reservoir modeling, reserve estimation, and production forecasting. The modeling is often based on multi-mineral physics or empirical formulae. When sufficient amount of training data is available, machine learning solution provides an alternative approach to estimate those reservoir properties based on well log data and is usually with less turn-around time and human involvements.

#### <a>Problem Statement</a>
The goal of this contest is to develop data-driven models to estimate reservoir properties including shale volume, porosity, and fluid saturation, based on a common set of well logs including gamma ray, bulk density, neutron porosity, resistivity, and sonic.

You will be provided with log data from about 10 wells from the same field together with the corresponding reservoir properties estimated by petrophysicists. You need to build a data-driven model using the provided training dataset. Following that, you will deploy the newly developed data-driven models on the test dataset to predict the reservoir properties based on the well log data. 

### <a>Evaluation</a>
Submissions are evaluated according to root mean squared error(RMSE) calculated from the shale volume (VSH), porosity (PHIF), and fluid saturation (SW) values of the hidden dataset.

<img align="center" src="https://render.githubusercontent.com/render/math?math=RMSE = \sqrt{\frac{1}{m}\sum_{i=1}^{m}(\hat{\mathbf{y_{i}}} - \mathbf{y_{i}})^{2}}">


- Here **\hat{y_i}** is the predicted values of the true values **y_i**. Both **\hat{y_i}** and **y_i** are vectors with 3 elements: shale volume (VSH), porosity (PHIF), and fluid saturation (SW). 
- m is sample size.

### <a>Timeline</a>

- __October 1, 2021__ - Competition starts. 
- __October 15, 2021__ - Registration deadline. You must email Lei Fu (pdda_sig@swpla.org) with team information (names, affiliations, and emails) before this date in order to compete.
- __November 30, 2021__ - Submission deadline. 
- __January 31, 2022__ - Announce winners and award prizes.


All deadlines are at 11:59 PM UTC on the corresponding day unless otherwise noted. The competition organizers reserve the right to update the contest timeline if they deem it necessary.

### <a>Competition Rules</a>

1. Contestant can be an individual or a group with the maximum size of 4.
2. The contest focuses on data-driven methods, the use of additional data or petrophysical equations is not allowed.
3. Privately sharing code or data outside of teams is not permitted. However, it's okay to share code if made available to all participants on the competition Github repository via submitting issues or pull requests. 
4. A contestant will submit the estimated reservoir properties for testing wells as separate .csv files.
5. A contestant will submit the source code and a brief report documenting the accuracy achieved in a few plots.
6. The judges will review the source code.
7. The performance of the model will be quantified in terms of root mean square error (RMSE).
8. A leaderboard will be updating the rank of submissions from each team.
9. The contestant with the best quality source code and the best performance will be declared the winner for this competition.
    
### <a>Prize Policy</a>

- 1st Place - \$500  
- 2nd Place - \$400  
- 3rd Place - \$300   
- 4th Place - \$200   
- 5th Place - \$100   

Top 5 winning teams will be awarded with prizes(NOT in cash).

Note: The winners will additionally be required to provide a detailed description of their method in order to claim the prize (minimum of 2 pages double-column) by December 15, 2021, which is two weeks after the competition has concluded.

Novel and practical algorithms will be recommended for a submission to the a SPWLA special issue by PDDA or a journal paper. 
<!-- #endregion -->

### Leaderboard
| Rank | Team Name              | Best Score | Best Solution        | Notebook                                                                                                                                                         |
|:----:|------------------------|------------|----------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|   1  | PDDA                   |    |        | [Notebook](https://github.com/pddasig/Machine-Learning-Competition-2021) 


### <a>Data Licensing</a>
The data comes from VOLVE dataset owned by Equinor. 

DATA ACCESS AND USE: Creative Commons Attribution-NonCommercial-ShareAlike license.

ENTRY IN THIS COMPETITION CONSTITUTES YOUR ACCEPTANCE OF THESE OFFICIAL COMPETITION RULES.

The Competition named above is a skills-based competition to promote and further the field of data science. You must submit your registration to pdda_sig@spwla.org to enter. Your competition submissions ("Submissions") must conform to the requirements stated on the Competition Website. Your Submissions will be scored based on the evaluation metric described on the Competition Website. Subject to compliance with the Competition Rules, Prizes, if any, will be awarded to participants with the best scores, based on the merits of the data science models submitted. Check the competition website for the complete Competition Rules.


### SPWLA PDDA SIG Contest Committee:
Lei Fu, Yanxiang Yu, Chicheng Xu, Andy McDonald,  Michael Ashby.

