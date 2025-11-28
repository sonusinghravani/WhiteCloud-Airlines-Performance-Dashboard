# ✈️ WhiteCloud Airlines Performance Dashboard

**Made by:** Sonu Kumar  
**Trained at:** Career247 Data Analytics 
**Date:** November 28, 2025

---

## 🎯 Business Problem

WhiteCloud Airlines wanted to understand how well it is performing across different routes and regions. Key questions were:

- Which routes make the most money?  
- Where are flight delays the worst?  
- How full are the flights on average?  
- Can we use location data to improve our business?

This dashboard was built to answer these questions using real flight data.

---

## 📊 Dashboard Goal

The main goal is to help airline managers and analysts:

- See key performance numbers at a glance  
- Spot trends in revenue and delays  
- Find top and underperforming routes  
- Make smarter business decisions based on data  

Ultimately, this dashboard supports better planning, happier customers, and higher profits.

---

## 🗺️ Data Preparation: Airport Lookup Table

I created a custom lookup table called `AirportLookup` to map airport codes (like LAX, DFW, SEA) to their city, country, latitude, and longitude.

### Why This Table?
- To show flight routes on a world map.
- To calculate distances or group data by region/country.
- To give context to route names (e.g., “DFW–SEA” = Dallas to Seattle).

### How I Built It:
- Created manually using `DATATABLE()` function in Power BI.
- Cleaned and formatted all columns (Code, City, Country, Latitude, Longitude) using **Power Query**.
- Ensured no duplicates or errors — for example, Chicago appears twice (ORD & CHI), but both point to same coordinates.
- Used real-world geographic coordinates for accurate mapping.

> ✅ **Tools Used**: Power BI + Power Query  
> ✍️ **Created & Maintained By**: Sonu Kumar

---

## 🖼️ Key Visuals — Why They Were Chosen

*(Same as before — clear, simple, professional)*

### 1. **KPI Summary (Total Revenue, Avg Delay, Passenger Load, Top Route)**  
> *Why?*  
These big numbers give an instant overview. Example: Total revenue is $12.46M, average delay is 89.74 minutes, and the best route is DFW–SEA. Leaders use these to set priorities.

### 2. **Revenue by Month and Day (Line Chart)**  
> *Why?*  
Shows daily and monthly sales patterns. Helps plan staffing, marketing, and predict future income.

### 3. **Revenue by Route (Bar Chart)**  
> *Why?*  
Compares money earned from each route. DFW–SEA earns the most; BOS–LHR earns less — even with many passengers. This helps decide where to invest more.

### 4. **Average Delay by Region (Bar Chart)**  
> *Why?*  
International flights have higher delays (96 min vs 83 min for domestic). This highlights where operations need fixes.

### 5. **Route Map (Geographic View)**  
> *Why?*  
Shows all flight routes on a world map. Bigger circles = more passengers. Clearly shows busy areas like the USA, Europe, and Asia — useful for expansion plans.

---

## 💡 Key Business Insights

- **DFW–SEA** is the most profitable route — protect and grow it.  
- **International delays** are higher — check airport processes or crew scheduling.  
- Some routes have **high passenger load but low profit** — maybe pricing or extra services need changes.  
- **January shows high revenue** — likely due to holidays. Use this pattern for future planning.  
- **Asia-Pacific** has strong passenger traffic — a good area for new routes.

---

## 🛠️ Tools Used

- Power BI  
- Airline performance dataset (from Career247 Institute)  
- Custom `AirportLookup` table built with DATATABLE + Power Query  
- Map visuals using built-in Power BI maps

---

## 📌 Final Note

This dashboard turns raw flight data into clear, useful insights. It helps WhiteCloud Airlines fly smarter — with better service, fewer delays, and more profit.

---

## 📄 Purpose & Description

This project was completed as part of my training at **Career247 Institute**. The goal was to build a real-world, data-driven dashboard using Power BI that solves a business problem.

I focused on:

✔️ Cleaning and preparing data (especially the `AirportLookup` table)  
✔️ Creating meaningful visuals for decision-makers  
✔️ Turning complex data into easy-to-understand insights  
✔️ Using geography (latitude/longitude) to add value through mapping

This project reflects my ability to work with real datasets, clean them properly, and deliver actionable dashboards — skills that are ready for any professional role in data analytics.

## Dashboard Previews
1. https://github.com/sonusinghravani/WhiteCloud-Airlines-Performance-Dashboard/blob/main/Dashboard-1.png
2. https://github.com/sonusinghravani/WhiteCloud-Airlines-Performance-Dashboard/blob/main/Dashboard-2.png


---
ofessional lagenge — aur sab kuch clear, simple, aur impactful hoga. 😊
