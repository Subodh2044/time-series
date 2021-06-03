# Time Series Analysis
The hotel sales is first plotted in Time Series Plot to see the trend in growth. 
![Screen Shot 2021-06-02 at 4 59 04 PM](https://user-images.githubusercontent.com/67131400/120566801-a7775c80-c3d5-11eb-91a6-2571a21926d0.png)

Monthly trend in then compared on yearly basis which gives us clearer view on the seasonality of the sales data.

![Screen Shot 2021-06-02 at 4 59 19 PM](https://user-images.githubusercontent.com/67131400/120566815-b1995b00-c3d5-11eb-8f92-c2c15952951a.png)

The data is then decomposed and plotted in histogram to check the residual value which shows that the majority of the errors are centered around zero.

![Screen Shot 2021-06-02 at 4 59 40 PM](https://user-images.githubusercontent.com/67131400/120566829-bb22c300-c3d5-11eb-9dae-2423207de20d.png)

Holt Winter's method is used to plot to check how well the model fits with the additive seasonality. As shown in the plot the model fits really well.

![Screen Shot 2021-06-02 at 5 00 05 PM](https://user-images.githubusercontent.com/67131400/120566836-c0800d80-c3d5-11eb-83d4-d9caa99cf6c0.png)

The density of the error/residual is very well centered around zero and the sum of squared error is also very low.

![Screen Shot 2021-06-02 at 5 00 47 PM](https://user-images.githubusercontent.com/67131400/120566844-c70e8500-c3d5-11eb-8a7f-7abe3ffbcac3.png)

Tried different models such as Ordinary Least Squares Regresssion (OLS), OLS with seasonal dummy variables and regression with trend seasonal components.

![Screen Shot 2021-06-02 at 7 04 34 PM](https://user-images.githubusercontent.com/67131400/120566855-cd9cfc80-c3d5-11eb-848f-cbf10224b2bf.png)

Came to conclusion that Holt Winter's model is the best model due to following reasons:
1. The residuals are concentrated aroung zero and slightly flat in the left but with very low frequency.
2. Easy to tell the fitting of the model by looking at the plot as actual observations in all the periods are very close to one another which suggests low error.
3. SSE is also very low.

![Screen Shot 2021-06-02 at 7 04 49 PM](https://user-images.githubusercontent.com/67131400/120566859-d392dd80-c3d5-11eb-83cc-c2189afb286e.png)
