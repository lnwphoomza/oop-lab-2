The dataset: Cities.csv
The analysis code: data_processing.py

DataLoader handles reading CSV data.
Table provides filtering and aggregation operations on that data.

In class Dataloader there is a Attribute that is base_path (Type: Path).

and there are 2 methods that are __init__(base_path=None) and load_csv(filename) as the methods.

In class Table there are 2 Attributes that are name and table but table is a list of dict.

and there are 3 methods such as __init__(name, data), filter(condition_func) and aggregate(agg_func, column).

Tanisorn Pisittanaphat 
6810545671
