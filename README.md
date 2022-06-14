# channelwidth
A flow chart of channel width extraction derived from He et al

This method can be finished using the ArcGIS 10.2 software and Google Earth Images. Moreover, more imformation can be obtained from:
M. He, Z. Li, B. Tong, and J. Tan, “Construction and application of dembased channel width model in mountainous medium-small watersheds,” Water Power, vol. 45, no. 4, pp. 22–27, 2019.

To compare the accuracy, we used these equations below:
$R^{2}=1-\frac{\sum_{i}\left(\hat{y}_{i}-y_{i}\right)^{2}}{\sum_{i}\left(\bar{y}_{i}-y_{i}\right)^{2}}$

$\sqrt{\sum\limits_{i=1}^{n}(x_{i}-y_{i})^2}$

$MAE=\frac{1}{m} \sum_{i=1}^{m}\left|\hat{y}_{i}-y_{i}\right|$
$RMSE=\sqrt{\frac{1}{m} \sum_i=1^m\left(y_{i}-\hat{y}_{i}\right)^{2}}$
where y$_{i}$, $\hat{y}$ and $\bar{y}$ are the ground truth, prediction and mean width, respectively.
