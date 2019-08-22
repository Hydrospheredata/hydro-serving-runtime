# Activity recognition model example

This demo contains the model trained for classification of human activity (stay, sit, run, walk and riding the bike).

It is trained on [SHL dataset](http://www.shl-dataset.org)

- [Model contract](model/serving.yaml) - contains deployment configuration
- [Signature function](model/src/func_main.py) - entry point of model servable.
- [Model demo](demo/AR_demo.ipynb) - demo on how to invoke Mnist model application

## How to deploy model:

```commandline
cd model
hs upload
```

## How to download data:
```commandline
dvc pull data/*
```