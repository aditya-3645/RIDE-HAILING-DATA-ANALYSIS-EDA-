# 🚕 RIDE-HAILING DATA ANALYSIS (EDA) | Python

## 📌 Project Overview

This project focuses on analyzing **ride booking data** to understand booking behavior, ride completion patterns, cancellations, customer–driver interactions, and revenue trends.

The dataset captures detailed information about each booking, including booking status, vehicle type, pickup and drop locations, payment methods, ratings, and ride distance.

The analysis aims to uncover **operational inefficiencies**, **customer behavior patterns**, and **business insights**, making it suitable for **data analytics, visualization, and machine learning applications**.

---

## 🎯 Project Objectives

- Analyze ride booking trends and booking statuses  
- Understand customer and driver cancellation behavior  
- Study ride completion patterns and incomplete ride reasons  
- Evaluate revenue patterns across different vehicle types  
- Analyze relationships between ride distance, booking value, and ratings  
- Identify operational bottlenecks using turnaround time (TAT) metrics  
- Prepare clean and structured data for visualization and machine learning models  

---

## 📊 Dataset Description

This project uses **one primary dataset** containing booking-level ride information.

---

## 📁 Bookings.csv — Ride Booking Data

### 📄 Description

The dataset contains detailed transactional data for ride bookings, where **each row represents a single booking**.  
It includes booking details, customer and driver behavior, ride outcomes, payment information, ratings, and distance metrics.

---

### 📐 Structure

- **Rows:** 103,024  
- **Columns:** 21  
- **Granularity:** One booking per row  
- **Data Type:** Structured tabular data  

---

### 🧾 Key Columns

#### 📅 Booking Information
- **Date** – Date when the booking was made  
- **Time** – Time when the booking was placed  
- **Booking_ID** – Unique identifier for each booking  
- **Booking_Status** – Final status of the booking (Completed, Canceled, Incomplete, etc.)

#### 👤 Customer & Vehicle Details
- **Customer_ID** – Unique customer identifier  
- **Vehicle_Type** – Type of vehicle booked (Auto, Mini, Sedan, etc.)  
- **Pickup_Location** – Starting point of the ride  
- **Drop_Location** – Destination of the ride  

#### ⏱️ Turnaround Time Metrics
- **V_TAT** – Vehicle turnaround time (time taken by vehicle to reach pickup location)  
- **C_TAT** – Customer turnaround time (customer waiting time)

> These values are mainly available for completed rides.

#### ❌ Cancellations & Incomplete Rides
- **Canceled_Rides_by_Customer** – Indicates customer-initiated cancellations  
- **Canceled_Rides_by_Driver** – Indicates driver-initiated cancellations  
- **Incomplete_Rides** – Indicates whether the ride was not completed  
- **Incomplete_Rides_Reason** – Reason for ride incompletion  

#### 💰 Payment & Ride Metrics
- **Booking_Value** – Total fare amount for the ride  
- **Payment_Method** – Mode of payment (Cash, UPI, Card, etc.)  
- **Ride_Distance** – Distance covered during the ride (in kilometers)

#### ⭐ Ratings
- **Driver_Ratings** – Rating given to the driver by the customer  
- **Customer_Rating** – Rating given to the customer by the driver  

> Ratings are available only for completed rides.
