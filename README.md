# Cars Prices

This project aims to build a model that can predict the sales price of a secondhand machine given the dataset with the history of the deals.

## Files

 - cars.jpnyb - the notebbok with all the workflow
 - report.pdf - the report about the problem and the solution
 - appendix.pdf - appendix to the report
 - sample_data/shm_data.cvs - dataset with the information about the deals
 - results.rtf - text file with the results of the models training
 - car_price_model.pkl - the final model itself, which may be used* for prediction

 *to unfold the model use:
```python
import joblib

model_loaded = joblib.load("car_price_model.pkl")
```
