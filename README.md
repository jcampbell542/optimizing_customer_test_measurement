This notebook is used to identify optimal test measurement strategies for an ecommerce retail dataset. Its primary objectives are to determine the best way to measure customer based tests.  It also includes functionality to identify, and cap or remove sales outliers.

It includes functions to import data, visualize the data, measure tests, conduct nulltest simulations, and remove/cap outliers. Throughout, I'll provide markdown comments to discuss code that may need explanation, and interpretation of the results.

If you are charged with making customer A/B test measurements, this functionality can greatly help you identify optimal ways to make measurements with the least possible noise.

Here is the measurement optimization analysis writeup: https://docs.google.com/document/d/11CAHwzRfqkkfLXava2SAkUnJRmx4dglryYQZoKtYKYI/

To run this notebook in your own environment, I recommend the following steps:

Install the pathlib, pandas, numpy, datetime, scipy, matplotlib, and random modules. These modules are used by the functionality in Get the dataset at Kaggle: https://www.kaggle.com/datasets/mathchi/online-retail-ii-data-set-from-ml-repository
Download this notebook Update the file import path in step #2 below: It currently points to the filepath on my machine
