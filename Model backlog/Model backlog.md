## Model backlog (list here each developed model and it's score)
- Train and validation are the splits using the train data from the competition.
- Test is the public leaderboard data set.
- The competition metric is "Categorization Accuracy".
---

### Model summary template
#### Model:
- Obs:
- Metrics:
    - Score: Train: Validation: Test: 

---

## Kaggle

- ### Random Forest

|Model|Train|Validation|Test|Link|
|-----|-----|----------|----|----|
|Random forest Bootstrap|0.87|0.87|0.57|[Link]()|
|Random forest Bootstrap - Grid Search|0.87|0.87|0.55|[Link]()|
|Random forest Bootstrap - Random Search|0.87|0.87|0.55|[Link]()|
|Random forest Bootstrap - Random Search 2|0.48|0.48|0.21|[Link]()|
|Random forest Bootstrap - Bayesian Opt |0.88|0.88|0.57|[Link]()|
|Random forest Bootstrap - Bayesian Opt 2|0.87|0.87|0.55|[Link]()|
|Random forest Bootstrap - Bayesian Opt 3|0.86|0.86|0.55|[Link]()|


- ### CatBoost

|Model|Train|Validation|Test|Link|
|-----|-----|----------|----|----|
|CatBoost Bootstrap|0.00|0.00|0.00|[Link]()|

- ### LightGBM

|Model|Train|Validation|Test|Link|
|-----|-----|----------|----|----|
|LightGBM Bootstrap|0.87|0.87|0.58|[Link]()|
|LGBM Bootstrap - Grid Search|0.89|0.89|0.58|[Link]()|
|LGBM Bootstrap - Random Search|0.88|0.88|0.57|[Link]()|
|LGBM Bootstrap - Random Search 2|0.88|0.88|0.56|[Link]()|
|LGBM Bootstrap - Bayesian Opt|0.88|0.88|0.57|[Link]()|
|LGBM Bootstrap - Bayesian Opt 2|0.87|0.87|0.57|[Link]()|

- ### XGBM

|Model|Train|Validation|Test|Link|
|-----|-----|----------|----|----|
|XGBoost Bootstrap|0.00|0.00|0.00|[Link]()|
|XGBoost Bootstrap - Grid Search|0.00|0.00|0.00|[Link]()|
|XGBoost Bootstrap - Random Search|0.00|0.00|0.00|[Link]()|
|XGBoost Bootstrap - Bayesian Opt |0.00|0.00|0.00|[Link]()|

- ### Deep Learning

    - #### MLP

    |Model|Train|Validation|Test|Link|
    |-----|-----|----------|----|----|
    |[1st iteration] - MLP|0.91|0.91|0.55|[Link]()|
    |[2nd iteration] - MLP|0.42|0.41|0.45|[Link]()|
    |[3rd iteration] - MLP|0.84|0.84|0.44|[Link]()|
    |[4th iteration] - MLP|0.84|0.84|0.48|[Link]()|
    |[5th iteration] - MLP|0.54|0.51|0.46|[Link]()|
    |[6th iteration] - MLP Series|0.41|0.41|0.39|[Link]()|
    |[7th iteration] - MLP Series|0.87|0.87|0.36|[Link]()|
    |[10th iteration] - MLP Series|0.89|0.78|0.39|[Link]()|
    |[52th iteration] - MLP FeEng|0.39|0.38|0.35|[Link]()|
    |[53th iteration] - MLP FeEng|0.39|0.39|0.35|[Link]()|
    |[54th iteration] - MLP FeEng|0.39|0.38|0.34|[Link]()|
    |[55th iteration] - MLP FeEng|0.39|0.39|0.37|[Link]()|


    - #### CNN

    |Model|Train|Validation|Test|Link|
    |-----|-----|----------|----|----|
    |[8th iteration] - CNN Series| 0.82|0.81|0.52|[Link]()|
    |[11th iteration] - CNN Series|0.89|0.76|0.53|[Link]()|
    |[56th iteration] - CNN New validation|0.39|0.39|0.36|[Link]()|
    |[57th iteration] - CNN New validation|0.40|0.39|0.37|[Link]()|
    |[58th iteration] - CNN New validation|0.39|0.38|0.36|[Link]()|
    |[59th iteration] - CNN New validation|0.42|0.42|0.49|[Link]()|
    |[60th iteration] - CNN New validation|0.42|0.42|0.45|[Link]()|
    |[61th iteration] - CNN New validation|0.20|0.20|0.16|[Link]()|
    |[62th iteration] - CNN New validation|0.40|0.39|0.37|[Link]()|
    |[63th iteration] - CNN New validation|0.43|0.43|0.50|[Link]()|
    |[64th iteration] - CNN New validation|0.46|0.45|0.51|[Link]()|
    |[65th iteration] - CNN New validation| 0.43|0.44|0.51|[Link]()|

    - #### RNN

    |Model|Train|Validation|Test|Link|
    |-----|-----|----------|----|----|
    |[12th iteration] - LSTM Series|0.10|0.07|???|[Link]()|
    |[13th iteration] - LSTM Series|0.91|0.85|???|[Link]()|
    |[14th iteration] - LSTM Series|0.85|0.82|???|[Link]()|
    |[15th iteration] - LSTM Series|0.76|0.71|???|[Link]()|
    |[16th iteration] - LSTM Series|0.42|0.42|???|[Link]()|
    |[17th iteration] - LSTM Series|0.43|0.43|0.46|[Link]()|
    |[18th iteration] - LSTM Series|0.45|0.45|0.51|[Link]()|
    |[19th iteration] - LSTM Series|0.46|0.45|0.49|[Link]()|
    |[20th iteration] - LSTM Series|0.41|0.42|???|[Link]()|
    |[21th iteration] - LSTM Series|0.44|0.42|0.48|[Link]()|
    |[22th iteration] - LSTM Series|0.47|0.46|???|[Link]()|
    |[23th iteration] - LSTM Series|0.54|0.50|0.50|[Link]()|
    |[24th iteration] - LSTM Series|0.69|0.64|0.48|[Link]()|
    |[25th iteration] - LSTM Series|0.61|0.58|0.41|[Link]()|
    |[26th iteration] - LSTM Series|0.73|0.68|0.49|[Link]()|
    |[27th iteration] - LSTM Series|0.62|0.57|0.37|[Link]()|
    |[28th iteration] - LSTM Series|0.71|0.66|0.45|[Link]()|
    |[29th iteration] - LSTM Series|0.74|0.69|0.49|[Link]()|
    |[30th iteration] - LSTM Series|0.76|0.71|0.44|[Link]()|
    |[31th iteration] - LSTM Series|0.72|0.67|0.41|[Link]()|
    |[32th iteration] - LSTM Series|0.73|0.69|0.42|[Link]()|
    |[33th iteration] - LSTM Series|0.78|0.71|0.49|[Link]()|
    |[34th iteration] - LSTM Series|0.69|0.67|0.44|[Link]()|
    |[35th iteration] - LSTM Series|0.63|0.62|0.45|[Link]()|
    |[36th iteration] - LSTM Series|0.65|0.65|0.42|[Link]()|
    |[37th iteration] - LSTM Series|0.76|0.71|0.53|[Link]()|
    |[38th iteration] - LSTM Series|0.73|0.70|0.47|[Link]()|
    |[39th iteration] - LSTM Series|0.63|0.61|0.44|[Link]()|
    |[40th iteration] - LSTM Series|0.72|0.68|0.43|[Link]()|
    |[41th iteration] - LSTM Series|0.71|0.67|0.41|[Link]()|
    |[42th iteration] - LSTM Series|0.73|0.70|0.43|[Link]()|
    |[43th iteration] - LSTM Series|0.76|0.71|0.43|[Link]()|
    |[44th iteration] - LSTM Series|0.76|0.71|0.50|[Link]()|
    |[45th iteration] - LSTM Series|0.75|0.71|0.44|[Link]()|
    |[46th iteration] - LSTM Series|0.80|0.75|0.49|[Link]()|
    |[47th iteration] - LSTM Series|0.78|0.72|0.44|[Link]()|
    |[48th iteration] - LSTM Series|0.75|0.70|0.44|[Link]()|

    - #### CNN-LSTM

    |Model|Train|Validation|Test|Link|
    |-----|-----|----------|----|----|
    |[49th iteration] - CNN-LSTM FeEng|0.79|0.73|0.41|[Link]()|
    |[50th iteration] - CNN-LSTM FeEng|0.41|0.41|0.40|[Link]()|
    |[51th iteration] - CNN-LSTM FeEng|0.43|0.43|0.46|[Link]()|
