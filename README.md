# DNGCDAT_GaoJiajie
DNGCDAT_A graph neural network method for potential disease-metabolite associations prediction

# DNGCDAT for disease-metabolite associations prediction

## Dependecies
- Python 3.10.9
- pytorch 2.0.0
- numpy 1.23.5
- pandas 1.5.3
- scikit-learn 1.3.0


## Dataset
disease-metabolite associations:association_matrix.xlsx
Disease similarity network:diease_network.xlsx
Metabolite similarity network:metabolite_network.xlsx

###### Model options
```
--dis_in_channels  int     diseases input feature dimensions.         Default is 2315.
--dis_hidden       int     diseases hidden feature dimensions.        Default is 128.
--dis_out_channels int     diseases output feature dimensions.        Default is 64.
--met_in_channels  int     metabolites input feature dimensions.      Default is 265.
--met_hidden       int     metabolites hidden feature dimensions.     Default is 128.
--met_out_channels int     metabolites output feature dimensions.     Default is 64.
--epochs           int     Number of epochs to train.                 Default is 2000.
--dropout          float   Dropout rate.                              Default is 0.3.
--lr               float   Initial learning rate.                     Default is 0.005.
```

###### How to run?
```
main.py
```
