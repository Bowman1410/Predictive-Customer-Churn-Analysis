# Data Dictionary

# Customer Table Data Dictionary

| Field Name         | Data Type     | Description                                            |
|--------------------|---------------|--------------------------------------------------------|
| customerID         | String        | Unique identifier for each customer.                    |
| gender             | String        | Customer's gender (e.g., "Male" or "Female").           |
| SeniorCitizen      | Integer (0/1) | Indicates if the customer is a senior citizen (0 or 1). |
| Partner            | String        | Whether the customer has a partner (e.g., "Yes" or "No").|
| Dependents         | String        | Whether the customer has dependents (e.g., "Yes" or "No").|
| tenure             | Integer       | Number of months the customer has been with the company.|
| PhoneService       | String        | Whether the customer has a phone service ("Yes" or "No").|
| MultipleLines      | String        | Whether the customer has multiple phone lines ("Yes", "No", or "No phone service").|
| InternetService    | String        | Type of internet service (e.g., "DSL", "Fiber optic", "No").|
| OnlineSecurity     | String        | Whether the customer has online security service ("Yes", "No", or "No internet service").|
| OnlineBackup       | String        | Whether the customer has online backup service ("Yes", "No", or "No internet service").|
| DeviceProtection   | String        | Whether the customer has device protection service ("Yes", "No", or "No internet service").|
| TechSupport        | String        | Whether the customer has tech support service ("Yes", "No", or "No internet service").|
| StreamingTV        | String        | Whether the customer has streaming TV service ("Yes", "No", or "No internet service").|
| StreamingMovies    | String        | Whether the customer has streaming movie service ("Yes", "No", or "No internet service").|
| Contract           | String        | Type of contract the customer has (e.g., "Month-to-month", "One year", "Two year").|
| PaperlessBilling   | String        | Whether the customer uses paperless billing ("Yes" or "No").|
| PaymentMethod      | String        | Payment method used by the customer.                    |
| MonthlyCharges     | Decimal       | Monthly charges for the customer.                        |
| TotalCharges       | Decimal       | Total charges accrued by the customer.                   |
| Churn              | String        | Whether the customer has churned ("Yes" or "No").       |

# The Scatter Plot  represents the relationship between 'Monthly Charges' and 'Total Charges' for each customer in the dataset
- **X-Axis (Horizontal):** This represents the 'Monthly Charges.' Each point on the x-axis corresponds to the monthly charge for a specific customer.

- **Y-Axis (Vertical):** This represents the 'Total Charges.' Each point on the y-axis corresponds to the total charge incurred by a customer.

- **Points (Dots):** Each point on the graph represents a customer in your dataset. The position of the point is determined by the customer's 'Monthly Charges' (x-coordinate) and 'Total Charges' (y-coordinate).

- **Trend:** The general pattern or trend of the points can provide insights into how 'Monthly Charges' and 'Total Charges' are related. For example, if the points tend to move upward from left to right, it suggests a positive correlation - as 'Monthly Charges' increase, 'Total Charges' also tend to increase.

- **Density:** The concentration of points in certain areas of the plot indicates where most customers fall in terms of 'Monthly Charges' and 'Total Charges.'

- **Transparency (Alpha):** The use of transparency (alpha parameter) allows you to see overlapping points more clearly. Denser regions will appear darker due to overlapping points.


