## CS39AA Data

This repository is where some (smaller) datasets for our course will be help. 

To load a file, say titanic.csv, the following code should be run.

    import pandas as pd
    url = "https://raw.githubusercontent.com/sgeinitz/cs39aa_data/main/titanic.csv"
    df = pd.read_csv(url)

The datasets currently in the repository and their sources are:

1. Titanic - https://www.kaggle.com/c/titanic/data
2. House Prices - https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data
