# Interest rate pricing project (School of Quants)
### Using Vasicek and Hull-White models short-term interest rates in Turkey has been forecasted.

Made by Vladislav Gusev and Vadim Smirnov.

### 1. Repository Guide:
  1.1 IR.ipynb - project code wich contains main comments, graphs and conclusions
  
  1.2 IR.pdf - project code in a convenient readable format
  
  1.3 turk3myield - 3 month Turkish soverign yield data from year 2000 to up to 2024 (daily)
  
### 2. Main results
  2.1 Sung k-means clusterizaion 3 main distiicnt periods have been determined in the short-term interest rate yields
![image](https://github.com/bicyclerepairservice/IR-Pricing-Project/assets/133600177/16e2475c-4e2c-48ee-97f4-3bdd9a8b49b6)

2.2 Resulting error (RMSE) for the Vasicek model = 0.19 over 10 simulations

2.3 Resulting error (RMSE) for the Hull-White model = 0.51 over 10 simulations

### 3. Conclusion

It is expected that the future interest rates in Turkey will decrease as currently rates are anomally above the mean. Given that the Vasicek is a mean-reverting algorithm, it is safe to assume that those results are reliable
