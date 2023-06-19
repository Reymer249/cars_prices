# Cars Prices

This project aims to build a model that can predict the sales price of a secondhand machine given the dataset with the history of the deals.

## Files

 - cars.jpnyb - the notebook with all the workflow
 - report.pdf - the report about the problem and the solution
 - appendix.pdf - appendix to the report
 - sample_data/shm_data.cvs - a dataset with information about the deals
 - results.rtf - text file with the results of the models training

## Additional files

You may download the final model (_car_price_model.pkl_) using the link: https://drive.google.com/file/d/161rp0QnVpUj3FoJxUdQsJWXba5T58JWO/view?usp=sharing

 To unfold the model use:
```python
import joblib

model_loaded = joblib.load("car_price_model.pkl")
```
You may download the dataset (_shm_data.csv_) using the link: https://drive.google.com/file/d/1GMeVW7evkN1kXMdv-2XjPkogHjvxV2sI/view?usp=sharing
