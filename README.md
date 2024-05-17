## High-level Goals

Automate the lifecycle of a machine learning model ( data -> model training -> deployment ). Focus on _demonstrating automation_ and continuous update capabilities within a realistic (but minimal) ML workflow.

## Requirements

1. Automatically generate and save new data to disk at regular intervals.
2. Train the model on new data, and save new parameters automatically.
3. "Deploy" the best model at any time by saving model weights to a production directory with version tracking.

## Provided Resources

- `get_data.py`
- `train_model.py`
- `evaluate_model.py`
