# 🚕 Taxi Fare Analytics Dashboard – Power BI Story

## 🌟 Start Here (Live Dashboard)

👉 **Explore the dashboard first:**
🔗 **https://app.fabric.microsoft.com/view?r=eyJrIjoiOWIwYjBhMWEtY2FhZC00MTE2LThjM2MtNTIzM2VkYWY2MDg2IiwidCI6ImYzNmNjZTU5LTZlOWMtNDM3Ni1hZGFjLWE2MTVmMWIwMTBjNCJ9**

---

## 📖 The Story Behind the Dashboard

Every ride tells a story.
From early morning commutes ☀️ to late-night trips 🌙, this dashboard uncovers patterns hidden in taxi bookings—who rides, when they ride, how far they go, and how much they spend.

What started as a simple dataset transformed into a powerful analytical journey using **Power BI**—turning raw numbers into meaningful insights.

---

## 📊 Dataset Overview

The dataset captures the lifecycle of a taxi ride with the following key attributes:

* 📅 Date & Time
* 🆔 Booking ID & Status
* 👤 Customer ID
* 🚗 Vehicle Type
* 📏 Ride Distance
* 💰 Booking Value
* ❌ Cancellation Reasons
* ⭐ Driver & Customer Ratings
* 💳 Payment Method

---

## 🧠 Smart Features (DAX-Powered Insights)

To go beyond basic reporting, several calculated columns were created:

### 💰 Revenue Tier Classification

Categorizes rides based on booking value:

* Premium (₹500+)
* High (₹200–499)
* Medium (₹100–199)
* Low (<₹100)

---

### 📉 Revenue Efficiency

**Revenue per KM** helps measure ride profitability:

```DAX
Revenue_per_km = DIVIDE(rideBookings[Booking Value], rideBookings[Ride Distance])
```

---

### 💳 Payment Intelligence

Simplified payment modes into meaningful groups:

* Digital (UPI, Wallet)
* Card (Credit/Debit)
* Cash

---

### ⏰ Peak Hour Detection

Identifies high-demand time slots:

* Morning Rush: 6 AM – 9 AM
* Evening Rush: 5 PM – 9 PM

---

### 📏 Distance Segmentation

Understanding ride patterns:

* Short (0–5 km)
* Medium (5–15 km)
* Long (15–30 km)
* Extra Long (30+ km)

---

### 🔁 Customer Behavior Tracking

**Days Since Last Ride** reveals engagement levels and churn signals.

---

### 🌅 Day Part Analysis

Divides the day into:

* Morning ☀️
* Afternoon 🌤️
* Evening 🌆
* Night 🌙

---

### 👑 Customer Segmentation

Customers are grouped based on loyalty and spending:

* **VIP 🏆** – Frequent & high spenders
* **Loyal 💼** – नियमित users with solid spend
* **Regular 🚶** – متوسط usage
* **Occasional 🌱** – Infrequent riders

---

## 🔍 Key Insights You Can Discover

✨ When are peak booking hours?
✨ Which customers bring the most revenue?
✨ Are longer rides more profitable?
✨ How do payment methods vary across segments?
✨ What patterns exist in cancellations?

---

## 🚀 Why This Dashboard Matters

This isn’t just a dashboard—it’s a decision-making tool.

It can help:

* 📈 Improve revenue strategies
* 🎯 Target high-value customers
* 🚦 Optimize driver allocation during peak hours
* 💡 Enhance customer retention strategies

---

## 🎯 Final Note

Data becomes powerful when it tells a story.
This dashboard transforms taxi ride data into a narrative of behavior, efficiency, and opportunity.

👉 Don’t forget to explore the live dashboard first and experience the insights yourself!

---
