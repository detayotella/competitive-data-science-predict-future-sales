# Sales Forecasting Project

This project focuses on forecasting the total monthly sales of products in various shops. The dataset consists of historical daily sales data that is sourced from [kaggle](https://www.kaggle.com/competitions/competitive-data-science-predict-future-sales/data) and it contains additional information about shops, products, and categories. The goal is to predict the monthly sales for a test set in November 2015.

## Data Description

### Files Included

- **sales_train.csv:** This file contains the training set, providing daily historical sales data from January 2013 to October 2015.

- I**test.csv:** The test set that needs predictions for the total sales in November 2015 for different shops and products.

- **sample_submission.csv:** A sample submission file with the correct format for predictions.

- **items.csv:** Supplementary information about the items/products, including item_id, item_category_id, and item_name.

- **item_categories.csv:** Supplementary information about item categories, including item_category_id and item_category_name.

- **shops.csv:** Supplementary information about the shops, including shop_id and shop_name.

### Data Fields

- **ID:** An identifier representing a (Shop, Item) tuple within the test set.
- **shop_id:** A unique identifier for each shop.
- **item_id:** A unique identifier for each product.
- **item_category_id:** A unique identifier for item categories.
- **item_cnt_day:** The number of products sold per day. The task is to predict the monthly amount of this measure.
- **item_price:** The current price of an item.
- **date:** The date in dd/mm/yyyy format.
- **date_block_num:** A consecutive month number for convenience, with January 2013 as 0 and October 2015 as 33.
- **item_name:** The name of the item.
- **shop_name:** The name of the shop.
- **item_category_name:** The name of the item category.

This dataset is suitable for time series forecasting, and the challenge is to create a robust model capable of handling changes in the list of shops and products each month.

Feel free to explore the data and use predictive modeling techniques to forecast monthly sales. The sample submission file (sample_submission.csv) can be used as a reference for the expected format of your predictions.

For any questions or suggestions, please reach out through the project repository.

Happy forecasting! 📈🛒