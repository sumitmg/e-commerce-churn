# Churn Rate Prediction Model

The dataset contains E Commerce Data of Customers and if te customer Churned

Dataset Source - Interview with a company

## Independent Variables:

- Categorical Variable
    - PreferredLoginDevice
    - PreferredPaymentMode
    - PreferedOrderCat

- Binary Categorical Variable
    - Gender
    - MaritalStatus
    - Complain

- Numeric Varaiable    
    - Tenure
    - WarehouseToHome 
    - HourSpendOnApp
    - NumberOfDeviceRegistered (Low)
    - CityTier (Low)
    - SatisfactionScore
    - NumberOfAddress (Low)
    - OrderAmountHikeFromlastYear
    - CouponUsed (Low)
    - OrderCount
    - DaySinceLastOrder
    - CashbackAmount

## Dependent Variable:

    Churn Flag

## Selected Variables

- Categorical Variable

    - MaritalStatus
    - Complain

- Numeric Varaiable   
    - Tenure - 3 
    - WarehouseToHome - 8


# ML Algorithm used:

    Logistic Classification


## Takeaways-

1. Lower the tenure higher is the rate of churn, which means, the more time it spends on the platform, less likely he is to churn.
2. Higher is the distance from warehouse to home, the lesser is the rate of churn.
3. Single people are more likely to churn than the Married ones.
4. People who have registered complains are more likely to churn.
5. People buying in Categories - Mobile Phaone and Laptops are more likely to churn.
