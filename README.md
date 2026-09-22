# A02-luc06002-raa20002

## Actual vs. Predicted Plots

Two scatter plots are used to evaluate the performance of the MLPRegressor model: one for the training data and one for the test data.

### Training Data: Actual vs. Predicted

The training plot compares the actual California housing values with the values predicted by the model using the training dataset.

- **X-axis:** Actual housing values
- **Y-axis:** Predicted housing values
- Each point represents one observation from the dataset.
- Predictions that are close to the actual values indicate better model performance.
- If the model predicts the values accurately, the points should follow a roughly diagonal pattern where the predicted value is close to the actual value.

### Test Data: Actual vs. Predicted

The test plot compares the actual housing values with predictions made on data that was not used to train the model.

- **X-axis:** Actual housing values
- **Y-axis:** Predicted housing values
- Points closer to the expected diagonal pattern indicate more accurate predictions.
- Because the test data was not used during model training, this plot helps show how well the model generalizes to new data.

### Comparing the Plots

The training and test plots can be compared to look for differences in model performance. If the training predictions are much closer to the actual values than the test predictions, this may indicate **overfitting**. Similar patterns between the two plots suggest that the model is generalizing reasonably well to unseen data.