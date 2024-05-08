## machinelearning-NBA team roster construction

Each file that contains code will produce results and may export the results as xlsx files.

The results of some steps will be converted to the favored form using power query of Excel. This process cannot be shown in the code, but both the original results and the converted version are presented in the folder. 

Each file's purpose and products are listed below:

* data_scrape.ipynb is the file containing the process of scraping data from NBA official website. The products are all the data sets we need for this project in Excel table form.

* PCA.ipynb is the file of the code running the principle analysis and gives the PCA matrix and transformed data.

* Clustering.ipynb is the file of the code running the clustering process and gives the results of the clusters using different algorithms and different data sets. The plots that evaluate the algorithms are not exported but can be found by running the code. 

* Neural Network.ipynb is the file of the code fitting the neural network model used in the framework. The results are not exported but can be found by running the code. 

* player_rate.r gives the code that gives the unweighted rates of each player in each game. rate.ipynb shows the code that gives the players different weights and gives the table that shows the rate of different players under each type of weight.

* Final Players Choose.ipynb shows the code that chooses players for the final roster. The result is not exported but can be found by running the code.

## Research Publications
* Transitional AI seminar series: https://www.youtube.com/watch?v=FMmU9Ta_ICQ
* Ke, Y., Bian, R., & Chandra, R. (2024). A unified machine learning framework for basketball team roster construction: NBA and WNBA. Applied Soft Computing, 153, 111298: https://doi.org/10.1016/j.asoc.2024.111298
* CodeOcean: https://codeocean.com/capsule/1930684/tree/v1
  


  
