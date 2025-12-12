|-------------------------------------------------------------------------------------------------------------------------------------------------|
| Column Name            | Data Type    | Description                                         | Business Relevance                                |
|------------------------|--------------|-----------------------------------------------------|---------------------------------------------------|
| **Invoice_ID**         | String       | Unique identifier for each sales transaction        | Used to track individual orders                   |
| **Invoice_Date**       | String (raw) | Original date before cleaning                       | Helps detect inconsistent formats                 |
| **Invoice_Date_Clean** | Date         | Standardized date in `YYYY-MM-DD`                   | Enables time-series analysis, monthly sales trend |
| **Customer_ID**        | String       | Raw customer identifier, may contain missing values | Useful for customer segmentation                  |
| **Customer_ID_Clean**  | String       | Cleaned ID; missing IDs replaced with placeholders  | Ensures no customer-level analysis breaks         |
| **Customer_DOB**       | Date         | Customer date of birth                              | Used to calculate age                             |
| **Customer_Age**       | Integer      | Customer age derived from DOB                       | Enables demographic analysis                      |
| **Product_ID**         | String       | Product identifier                                  | Used for product-level grouping                   |
| **Product_Category**   | String       | Category of the product purchased                   | Helps identify high-performing categories         |
| **Quantity**           | Integer      | Number of units purchased                           | Used to compute total revenue                     |
| **Unit_Price**         | Float        | Price per unit                                      | Used to calculate totals                          |
| **Total_Amount**       | Float        | Raw total amount; contains incorrect/missing values | Helps detect data issues                          |
| **Total_Amount_Clean** | Float        | Corrected amount = Quantity × Unit_Price            | Accurate revenue measurements                     |
| **Payment_Mode**       | String       | Original payment method                             | Used to detect inconsistent values                |
| **Payment_Mode_Clean** | String       | Standardized payment method (Card, Cash, UPI)       | Used for payment method analysis                  |
| **Country**            | String       | Original country field                              | Contains inconsistency                            |
| **Country_Clean**      | String       | Cleaned country name                                | Region-level analysis                             |
| **Order_Status**       | String       | Status of order (Completed/Failed/Returned)         | Helps measure success rate & return rate          |
|-------------------------------------------------------------------------------------------------------------------------------------------------|