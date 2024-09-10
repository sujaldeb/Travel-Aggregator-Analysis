
# MyNextBooking Travel Analysis

### Project: Data Analysis for MyNextBooking

This project provides an in-depth analysis of travel booking data for the Indian start-up **MyNextBooking**. MyNextBooking is an aggregator platform that compares travel prices across major platforms such as Yatra, MMT, and Goibibo, helping users find the best deals for their journeys. As a data analyst, this project focuses on analyzing user bookings, sessions, and searches, as well as calculating key performance metrics to aid in the company’s decision-making process.

---

## Table of Contents
1. [Project Objectives](#project-objectives)
2. [Data Files](#data-files)
3. [Project Workflow](#project-workflow)
4. [Key Insights and Outputs](#key-insights-and-outputs)
5. [Technology Stack](#technology-stack)
6. [Installation](#installation)
7. [Usage](#usage)

---

## Project Objectives

The project is structured to answer key business questions based on the booking and session data. Some of the core objectives include:
1. Find the number of distinct bookings, sessions, and searches from the given data sets.
2. Identify sessions with more than one booking.
3. Analyze the days of the week with the highest number of bookings.
4. Calculate the total number of bookings and gross booking value by service.
5. Identify the most booked route for customers with multiple bookings.
6. Find the top 3 departure cities with the most advanced bookings.
7. Display a heatmap of correlations for numerical columns.
8. Analyze the most-used device type for each service.
9. Plot trends at quarterly frequency for device types.
10. Calculate the oBSR (overall booking-to-search ratio) for each month and day of the week, and plot the time series of oBSR.

---

## Data Files

The analysis is based on two primary datasets:
1. **Bookings.csv** - Contains information about bookings, such as customer ID, booking time, device type, INR amount, days to departure, etc.
2. **Sessions.csv** - Contains session-related data, including session ID, search ID, session starting time, and corresponding bookings (if any).

---

## Project Workflow

1. **Data Preprocessing**:
   - Load and clean data from `Bookings.csv` and `Sessions.csv`.
   - Convert columns such as `booking_time` and `session_starting_time` to proper datetime formats for analysis.
   
2. **Descriptive Statistics**:
   - Calculate distinct counts of bookings, sessions, and searches.
   - Filter and analyze sessions with multiple bookings.
   
3. **Exploratory Data Analysis**:
   - Day-of-week analysis for bookings.
   - Calculation of gross booking value by service.
   - Route analysis for customers with multiple bookings.
   - Departure city analysis for advanced bookings.

4. **Correlation and Time Series Analysis**:
   - Create heatmaps for correlation between numerical columns.
   - Plot trends for booking devices on a quarterly basis.
   - Time series analysis for oBSR on monthly and daily levels.

---

## Key Insights and Outputs

- **Distinct Bookings, Sessions, and Searches**:
  - Distinct Bookings: 339
  - Distinct Sessions: 331
  - Distinct Searches: 1360

- **Sessions with More Than One Booking**:
  - 35 sessions had more than one booking.

- **Days of the Week with the Highest Number of Bookings**:
  - A pie chart illustrates that certain days, like Monday and Friday, show higher bookings.

- **Total Bookings and Gross Booking Value by Service**:
  - Goibibo, MMT, and Yatra were analyzed, with Goibibo showing the highest gross booking value of INR 5,897,637.97.

- **Most Booked Route**:
  - The most booked route for customers with multiple bookings was from **Gurgaon** to **Roissy-en-France**.

- **Top 3 Departure Cities with Most Advanced Bookings**:
  - Bālāpur, Devanhalli, and Chennai had the highest average days to departure, indicating early bookings.

- **Device Type Analysis**:
  - Device usage varies by service, with iOS and Desktop being the most used devices for bookings.

- **Correlation Heatmap**:
  - A heatmap displays strong correlations between numerical fields, such as booking amount and other factors.

- **oBSR Analysis**:
  - The oBSR (overall booking-to-search ratio) was calculated across months and days of the week, showing trends in user engagement.

---

## Technology Stack

- **Programming Language**: Python
- **Libraries**: 
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `seaborn`

---

## Installation

To run this project, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/sujaldeb/Travel-Aggregator-Analysis





```python
pip freeze > requirements.txt

```

    Note: you may need to restart the kernel to use updated packages.
    


```python

```
