# Root-Cause-Analysis
Hotel Management

## Problem Statement

Airbnb is experiencing a significant gap between expected revenue and actual revenue earned, driven primarily by booking cancellations, no-shows, and flexible deposit policies. Despite strong booking demand across multiple periods, a large portion of revenue is lost due to high-risk customer segments, booking channels, and deposit types. The organization needs to identify the root causes of revenue leakage and determine which operational and customer-level factors most strongly impact revenue loss.

## nBrief Context

An analytical dashboard was developed to evaluate tri-annual booking data, comparing expected revenue, earned revenue, and lost revenue across dimensions such as customer type, booking channel, hotel type, deposit policy, and booking status. The analysis highlights patterns in cancellations and no-deposit bookings, particularly among transient customers and online travel agent channels, revealing key drivers of financial underperformance.

## Key Business Questions

What is the magnitude of revenue loss compared to expected revenue?

Which customer types contribute the most to revenue loss?

How do deposit policies (no deposit vs refundable/non-refundable) impact cancellations and revenue leakage?

Which booking channels are associated with the highest cancellation rates and revenue loss?

Are certain hotel types (city vs resort) more vulnerable to revenue loss?

Do revenue earned and revenue lost follow similar seasonal patterns?

Which booking statuses (canceled, no-show, check-out) drive the most loss?

How does transient customer behavior differ from group or contract customers?

What combinations of customer type, deposit type, and booking channel create the highest risk?

What policy or pricing changes can reduce revenue loss without negatively impacting bookings?


## Excel Interactive Dashboard (Snapshot)
![Airbnb Root Cause Analysis](https://raw.githubusercontent.com/Morsshed/Excel-Dashboard-HotelBusiness/main/Air%20bnb%20Root%20Cause%20Analysis.png)

#### Findings

Expected revenue ($42.7M) is significantly higher than revenue earned ($29.6M), indicating substantial leakage.

Revenue loss totals $13.1M, accounting for ~31% of expected revenue.

44,224 bookings were canceled, a major driver of revenue loss.

Revenue earned and revenue lost peak during the same months, suggesting demand volatility rather than seasonal decline.

Transient customers generate the highest revenue earned overall.

Transient customers also account for the highest revenue loss, indicating higher cancellation/no-show risk.

No-deposit bookings contribute the majority of revenue loss.

Refundable deposits show higher revenue earned compared to no-deposit bookings.

Online Travel Agents (OTAs) generate high revenue but also drive the largest revenue loss.

Direct booking channels have lower revenue loss compared to OTAs.

City hotels experience higher revenue loss than resort hotels.

Resort hotels show better revenue retention despite lower booking volume.

No-deposit policy dominates booking behavior, especially among transient customers.

Check-out and no-show statuses contribute more to loss than check-in cancellations.

Transient-party customers contribute minimal revenue loss compared to transient customers.

Group and contract customers show lower cancellation rates and revenue loss.

Corporate bookings contribute moderate revenue with relatively controlled loss.

Refundable deposit types still incur losses, but significantly less than no-deposit types.

Revenue loss is concentrated in specific booking channels, rather than evenly distributed.

Customer type and deposit policy together explain most revenue leakage, making them key root-cause drivers.


#### Recommendations


Introduce minimum deposit requirements for bookings made via Online Travel Agents to reduce cancellations.

Incentivize refundable or partial-deposit options instead of no-deposit bookings.

Strengthen cancellation policies for transient customers, especially during peak months.

Promote direct bookings through discounts or loyalty benefits to reduce OTA-driven losses.

Apply stricter no-show penalties for no-deposit and OTA bookings.

Focus marketing on group and contract customers, as they demonstrate lower revenue loss.

Implement predictive cancellation risk scoring based on customer type, channel, and deposit behavior.

### Seosanalisty and Trend
![Airbnb Seasonality Analysis](https://raw.githubusercontent.com/Morsshed/Excel-Dashboard-HotelBusiness/main/ExcelImages/Seasonality.png)

#### Description
This image demonstrates a seasonality analysis for Airbnb bookings and revenue, showing how business performance fluctuates across different months or seasons.

► Visualizes monthly or seasonal trends in bookings

► Highlights peak and off-peak periods

► Helps in planning pricing, promotions, and inventory

► Supports data-driven decisions for maximizing revenue

This dashboard is useful for Airbnb or hotel businesses to optimize operations and strategic planning based on seasonal trends.

### Types Vs Revenue
![Airbnb Revenue Earned Dashboard](https://raw.githubusercontent.com/Morsshed/Excel-Dashboard-HotelBusiness/main/ExcelImages/Revenue%20Earned.png)

#### Description

This image shows the total revenue earned for Airbnb listings over a specific period. It helps visualize business performance and track income trends.

► Displays revenue trends over time

► Identifies high-performing periods and listings

► Supports financial forecasting and planning

Enables actionable insights for revenue optimization

### Drill Down

![Drill Down Analysis Dashboard](https://raw.githubusercontent.com/Morsshed/Excel-Dashboard-HotelBusiness/main/ExcelImages/Drill%20Down.png)

### Revenue Vs Loss
![Revenue vs Loss Dashboard](https://raw.githubusercontent.com/Morsshed/Excel-Dashboard-HotelBusiness/main/ExcelImages/RevenueVsLoss.png)
#### Description
This image visualizes the comparison between revenue earned and losses incurred for Airbnb listings. It provides insights into profitability and operational efficiency.

► Compares revenue and loss trends over time

► Highlights periods of higher loss or lower revenue

► Supports financial and operational decision-making

Helps identify areas to reduce loss and optimize profitability

### Revenue Channels
![Transient Customer vs Booking Channels](https://raw.githubusercontent.com/Morsshed/Excel-Dashboard-HotelBusiness/main/ExcelImages/Transient%20CustomerVsBookingChannels.png)

#### Description
This dashboard visualizes the relationship between transient customers and their preferred booking channels.

► Compares booking behavior of transient vs. repeat customers

► Highlights the most popular booking channels

► Supports marketing and channel optimization strategies

Helps improve customer acquisition and retention

### Loss in Hotels
![Loss in Hotels Dashboard](https://raw.githubusercontent.com/Morsshed/Excel-Dashboard-HotelBusiness/main/ExcelImages/LossInHotels.png)
#### Description
This dashboard focuses on losses incurred in hotel operations, helping identify patterns and areas of inefficiency.

► Visualizes total losses across different hotels or listings

► Highlights high-loss periods and locations

► Supports operational decision-making to reduce losses

Enables identification of key factors contributing to financial inefficiencies

### Original Dataset
Direct Link to [Airbnb Open Data Kaggle Code](https://www.kaggle.com/datasets/arianazmoudeh/airbnbopendata/code)

![Original Dataset Snapshot](https://raw.githubusercontent.com/Morsshed/Excel-Dashboard-HotelBusiness/main/ExcelImages/Original%20dataset.png)

