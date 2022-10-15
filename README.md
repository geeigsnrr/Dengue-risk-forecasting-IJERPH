## Requirements
The code has been tested running under Python 3.7. The required packages are as follows:

- pandas
- numpy
- tensorflow
- matplotlib
- sklearn

## Run RF

```
python RF.py
```

## Run LSTM or LSTM-ATT

```
python LSTM.py
```

Some important variables in the code:

- net_mode: "1" for LSTM, "2" for LSTM-ATT
- df_mode: the number of ahead week prediction [1, 4]
- data_mode: "2" without dengue cases, "3" with dengue cases
- file_name: 'DF.csv' or '''Fortaleza.csv'