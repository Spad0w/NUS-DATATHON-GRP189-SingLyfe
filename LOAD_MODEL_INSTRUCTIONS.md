
# Load Model Instructions 

## Packages Required:
- h2o
- numpy
- pandas
- matplotlib.pyplot

If any packages are missing, can execute
```
% pip install <package_name>
```

## Instructions
Our model `rfTrainedModel` is saved in the same directory as the NUS_DATATHON_SINGLIFE_SINGLYFE.ipynb. 

The model is loaded automatically into the notebook when you execute the testing_hidden_data() function.

Specifically the line: `RF_Model = h2o.load_model('./rfTrainedModel')` will load the model into a variable `RF_Model`, which is then used to make predictions on the processed test data.

Note that the filepath in `test_df = pd.read_parquet(filepath)` to read the hidden data needs to be changed accordingly.
