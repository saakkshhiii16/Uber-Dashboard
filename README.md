# 🚖 Uber Analytics Dashboard – Power BI

An interactive, Uber-themed Power BI dashboard that explores **Uber ride bookings**: how many rides were completed, which vehicle types earn the most revenue, and how demand changes over the year.

![Home](Dashboard%20Images/home.png)

## 📌 Description

This project turns raw Uber booking data into a 3-page dashboard:

- **Home:** a landing page with navigation buttons.
- **Overview:** KPIs (completed bookings, lost bookings, revenue, total and average distance), monthly trends, revenue by vehicle type, top pickup and drop locations, and customer and driver ratings.
- **Vehicle:** a breakdown by vehicle type with customers, revenue, completed bookings, revenue share and a monthly trend for each vehicle.

## 🎯 Objectives and Expected Outcomes

- Understand overall ride performance at a glance (completed vs lost bookings).
- Find which vehicle types bring the most revenue.
- Spot seasonal patterns and dips in bookings.
- Identify the busiest pickup and drop locations.
- Support decisions on driver allocation and demand planning.

## 🛠️ Tools Used

- **Power BI Desktop:** report design, visuals, navigation buttons
- **DAX:** measures such as Booking_Value and Cont% (revenue share)
- **Power Query:** data cleaning and preparation

## 💡 Key Insights

- About **93K completed** and **57K lost** bookings, so roughly 4 in 10 bookings did not end in a completed ride.
- Total revenue is about **52M**.
- **Auto** earns the most (about 12.9M), followed by **Bike** (about 11.5M).
- **Uber XL** earns the least (about 1.5M).
- Monthly bookings stay fairly steady, with a clear **dip in February**.
- Average ratings are healthy: **4.0** from customers and **4.23** from drivers.
- Top pickup point is **Khandsa** and top drop point is **Ashram**.

## 🖼️ Screenshots

### Overview
![Overview](Dashboard%20Images/overview.png)

### Vehicle
![Vehicle](Dashboard%20Images/vehicle.png)

## ▶️ How to Use

1. Download the `.pbix` file from this repository.
2. Open it in Power BI Desktop.
3. Use the buttons on the Home page to move between pages.

## 👤 Author

[Sakshi Tripathi]|[Github](https://github.com/saakkshhiii16)
