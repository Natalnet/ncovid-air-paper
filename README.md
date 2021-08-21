# Multivariate Data Driven Prediction of COVID-19 Dynamics
> Multivariate Data Driven Prediction of COVID-19 Dynamics: Towards New Results with Temperature, Humidity and Air Quality Data

* [IEEExplore](https://ieeexplore.ieee.org/document/9145427): Paper IEEExplore link.
* At *2020 International Conference on Systems, Signals and Image Processing (IWSSIP)*


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

    @INPROCEEDINGS{Aragao2020,
          author={Aragão, Dunfrey and Nascimento, Tiago and Mondini, Adriano},
          booktitle={2020 International Conference on Systems, Signals and Image Processing (IWSSIP)}, 
          title={SpaceYNet: A Novel Approach to Pose and Depth-Scene Regression Simultaneously}, 
          year={2020},
          volume={},
          number={},
          pages={217-222},
          doi={10.1109/IWSSIP48289.2020.9145427}}

## Acknowledgments

* CAPES Edital 12/2020 - Telemedicinas e Análise de Dados Médicos
