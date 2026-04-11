# Synchronization Analysis With Recurrence Plots

> This repository contains the code used for the analysis section of the paper
'Detecting Synchronization In Time Series Using Recurrence Plots And Recurrence Quantification Analysis'
We test the applicability of different methods from Recurrence Analysis such as Joint- and Cross-Recurrence Plots
as well as Recurrence Quantification metrics such as $\tau$-recurrence rate, CPR and JPR to detect
different types of synchronization such as complete, lag, phase and generalized synchronization in time series data.

## Repository Structure
In the folder analysis-scripts, you can find the Python code scripts which were used to simulate the time series data, conduct the analysis and produce the visualizations for the paper. They were produced by different authors and contain the following content:

* Authored by Malte Springer
  - tau_recurrence_CPR.ipynb - Tests the applicability of the $\tau$-recurrence rate and CPR on all types of synchronization

* Authored by Zinan Lyu
  - ...

* Authored by Samuel Jaramillo
  - JRP_LS_Code.ipynb - Tests JRPs and JPR on lag synchronization
  - JRP_PS_Code.ipynb - Tests JRPs and JPR on phase synchronization
  - JPR_GS_Code.ipynb - Tests JPRs and JPR on generalized synchronization
  - csv-Files contain stored data to produce plots
