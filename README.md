# Laptop Power Tuning Based on System State Prediction

This is the training data for paper "Laptop Power Tuning Based on System State Prediction", which enables better system performance with a new power tuning method. 

# How to use
You need first to unzip the file PowerData.zip. The power data is stored in json format, you can use code like below to load it.

```shell
import json
with open(filename, 'r') as f:
    record = json.load(f)
```
