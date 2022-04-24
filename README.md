# Ubiquant-Market-Prediction
Kaggle competition to predict a target value using features of investment data.

<h1>
  Data
</h1>
<p>
  The data is in kaggle in the ubiquant market competition. The features and targets formulas are not known. Yet, other data source was used because the csv format is inefficient. The official competition dataset and the other dataset are given below:<br/>
  <a href="https://www.kaggle.com/competitions/ubiquant-market-prediction/data">Ubiquant Market Official Data</a><br/>
  <a href="https://www.kaggle.com/datasets/robikscube/ubiquant-parquet">Ubiquant Market Parquet Data</a><br/>
  
  Note: The feature selection notebook generates a dataset containing lags of the target. It contains codes to apply boruta and RFE feature selections, although, they were not used (they need a lot of time and there was no improvement in score).
</p>

<h1>
  Correlation
</h1>

<p>
  The correlation excel file contains 3 sheets. The first contains the correlation between features, time_id, investment_id, and targets. Checking each value as it is would be difficult and time consuming. Thus, the second sheet is present. It has the correlation table, but there is a threshold value that only displays table cells that contain an absolute value greater than the threshold. It is usefull to focus on the most correlated features or features above the acceptable threshold.
</p>

<h1>
  Ubiquant Market Notebook
</h1>

<p>
  This notebook contains the auto-encoder,keras model, and the training code. The notebook applies techniques like MC Dropout (Monte Carlo Dropout), Multitask learning, denoising auto-encoders and others. The notebook contains some extra notes.
</p>
