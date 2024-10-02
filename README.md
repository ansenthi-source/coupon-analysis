## Coupon Acceptance Analysis

This project analyzes customer behavior in response to driving coupons, focusing on factors such as destination, passenger type, time, weather, and coupon type. By leveraging visualizations and probability distributions, we explore what influences a customer's decision to accept a coupon.

## Problem Statement

The aim of this analysis is to investigate what factors influence a customer's likelihood of accepting a coupon while driving. We explore different coupon types, including bar coupons, to understand the demographic and situational factors that play a role in coupon acceptance.

## Data Description

The data was collected via a survey that captured different driving scenarios and asked whether the customer would accept a coupon. The dataset contains the following attributes:
- **User Attributes**: Gender, Age, Marital Status, etc.
- **Contextual Attributes**: Weather, Time, Passenger Type, etc.
- **Coupon Attributes**: Type of Coupon, Expiration, etc.
- **Target Variable**: Y, where Y=1 indicates coupon acceptance, and Y=0 indicates rejection.

## Summary of Findings

1. **Overall Coupon Acceptance Rate**:  
   The overall coupon acceptance rate is **56.84%**, meaning that more than half of the customers accepted the coupons offered during driving scenarios.

2. **Bar Coupon Acceptance Rate**:  
   The acceptance rate for **bar-related coupons** specifically is **41.00%**, which is lower compared to the overall coupon acceptance rate.
   **Analysis**:
The dataset was filtered to include only bar-related coupons. Key findings included:
- **Higher acceptance among frequent bar-goers** (more than 3 visits per month).

4. **Bar Visit Frequency**:  
   Customers who visit bars more than 3 times per month had a **significantly higher acceptance rate** for bar coupons compared to those who visit bars less frequently.
   **Acceptance Based on Bar Visit Frequency**
A comparison of acceptance rates was performed between customers who visit bars 3 or fewer times a month versus those who visit more often, with the latter showing a higher acceptance rate.

6. **Drivers Over 25 and Frequent Bar-Goers**:  
   Drivers who are over the age of 25 and frequently visit bars are **56.74%** likely to accept bar-related coupons, indicating a higher acceptance rate in this demographic.
   **Acceptance for Drivers Over 25 Who Visit Bars Frequently**
A specific analysis was conducted for drivers over the age of 25 who visit bars frequently, yielding an acceptance rate of 56.74%.




