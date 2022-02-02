# Multivariate Data Driven Prediction of COVID-19 Dynamics

[Multivariate Data Driven Prediction of COVID-19 Dynamics: Towards New Results with Temperature, Humidity and Air Quality Data](https://doi.org/10.1016/j.envres.2021.112348)

[Environmental Research](https://www.sciencedirect.com/journal/environmental-research/vol/204/part/PD)


## Project Language

- Python 3
- [Tensorflow](https://www.tensorflow.org/)
- [Matplotlib](https://matplotlib.org/)
- [Scikit](https://scikit-learn.org/stable/)
- [Numpy](https://numpy.org/)

## Folder structure and Code

The main code is on [final_file_forecast_SPSP.ipynb](final_file_forecast_SPSP.ipynb). 

Folder [experiments](experiments) contains all files (models and errors) used to generate the plots presented in the paper. Some of the files names are in portuguese, so a quick translation is: mortes (Deaths), casos (Cases), temperatura (Temperature). 

Experiment [casos-aqi-temp-humid_mortes](experiments/casos-aqi-temp-humid_mortes) wasn't added to the paper due to poor performance.

## Dataset

The data used to train the models is on file [df_spsp_pred.csv](df_spsp_pred.csv). 

## Results

![alt text](forecasted_curve.png)

## Citation

This work had many contributions and many authors. 

If you are interested in using this code in your research, we would like to receive a quote from the original paper:

    @article{ARAGAO2022112348,
          title = {Multivariate data driven prediction of COVID-19 dynamics: Towards new results with temperature, humidity and air quality data},
          journal = {Environmental Research},
          volume = {204},
          pages = {112348},
          year = {2022},
          issn = {0013-9351},
          doi = {https://doi.org/10.1016/j.envres.2021.112348},
          url = {https://www.sciencedirect.com/science/article/pii/S0013935121016492},
          author = {Dunfrey P. Aragão and Emerson V. Oliveira and Arthur A. Bezerra and Davi H. {dos Santos} and Andouglas G. {da Silva Junior} and Igor G. Pereira and Prisco Piscitelli and Alessandro Miani and Cosimo Distante and Jordan S. Cuno and Aura Conci and Luiz M.G. Gonçalves},
          keywords = {COVID-19 dynamics, Air quality and temperature, AI prediction, COVID-19 epidemiology, Time-series forecast, Multivariate forecast},
          abstract = {Since the start of the COVID-19 pandemic many studies investigated the correlation between climate variables such as air quality, humidity and temperature and the lethality of COVID-19 around the world. In this work we investigate the use of climate variables, as additional features to train a data-driven multivariate forecast model to predict the short-term expected number of COVID-19 deaths in Brazilian states and major cities. The main idea is that by adding these climate features as inputs to the training of data-driven models, the predictive performance improves when compared to equivalent single input models. We use a Stacked LSTM as the network architecture for both the multivariate and univariate model. We compare both approaches by training forecast models for the COVID-19 deaths time series of the city of São Paulo. In addition, we present a previous analysis based on grouping K-means on AQI curves. The results produced will allow achieving the application of transfer learning, once a locality is eventually added to the task, regressing out using a model based on the cluster of similarities in the AQI curve. The experiments show that the best multivariate model is more skilled than the best standard data-driven univariate model that we could find, using as evaluation metrics the average fitting error, average forecast error, and the profile of the accumulated deaths for the forecast. These results show that by adding more useful features as input to a multivariate approach could further improve the quality of the prediction models.}
          }


## Acknowledgments

* CAPES Edital 12/2020 - Telemedicinas e Análise de Dados Médicos
