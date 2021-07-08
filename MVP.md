Small Pairplot with the positive correlated features with my target (Domestic_gross_log)

![pairplot_small](https://user-images.githubusercontent.com/77758249/124885203-a3bc9400-df98-11eb-98c0-787efa3409f7.png)

domestic_gross_log & widest_release correlation: one of the highest correlations detected early in the process due to pairplot visualization.

![widest_release](https://user-images.githubusercontent.com/77758249/124888241-8806bd00-df9b-11eb-897c-25cdfccd0d05.png)

Distributor Heatmap: identify the highest correlation of the Distributors with the Target and also the correlation among them to exclude it from the analysis in order to avoid multicollionearity. We were able to pick the most correlated Distributor with this visualization.

![distributor_heatmap](https://user-images.githubusercontent.com/77758249/124887707-07e05780-df9b-11eb-8dce-c514ede796e6.png)


Genres Heatmap: identify the highest correlation of the Genres with the Target and also the correlation among them to exclude it from the analysis in order to avoid multicollionearity. Four genres were identified as the most correlated for our initial model.

![genre_heatmap](https://user-images.githubusercontent.com/77758249/124887741-0f9ffc00-df9b-11eb-9727-900243ca47cc.png)

1. Baseline linear regression model
1.1 simple linear regression R^2: 0.705709

![base_lr_model](https://user-images.githubusercontent.com/77758249/124889807-0dd73800-df9d-11eb-95ee-33cb01d732f1.png)


