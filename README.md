# Hotel Booking Data Wrangling & Platform Analysis

## Overview
This project focuses on cleaning and transforming semi-structured hotel booking data using Python and Pandas.

The dataset contains mixed-format records where booking platform names (Hotels, Booking, Expedia, Cleartrip) are embedded within the data. The goal is to extract this information and perform platform-level analysis.

---

## Business Problem
Hotel booking data often contains inconsistent formatting, making it difficult to analyze booking sources.

This project solves that problem by:
- Cleaning raw booking data  
- Extracting booking platform information  
- Enabling accurate platform-level reporting  

---

## Dataset
The dataset contains:
- Date  
- Company  
- Person Name  
- Room number  

Some rows contain booking platform markers instead of actual bookings, requiring preprocessing.

---

## Methodology

### Data Wrangling
- Identified rows with missing room numbers (platform markers)  
- Extracted booking platform names from the Date column  
- Applied backfilling (bfill) to assign booking source to each record  
- Removed invalid rows to create a clean dataset  

---

### Platform Analysis
- Counted bookings by platform  
- Compared distribution across sources  
- Identified highest-performing booking channels  

---

## Key Insights
- Expedia generated the highest number of bookings  
- Booking activity is distributed across multiple channels  
- Data wrangling was required to extract platform-level information  
- Cleaned dataset enables accurate reporting of booking sources  

---

## Visualization
A bar chart was created to compare booking counts across platforms.

---

## Business Impact
- Helps identify top booking channels  
- Supports partner performance analysis  
- Enables structured reporting from messy raw data  
- Improves data usability for business decisions  

---

## Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Jupyter Notebook  

---

## Project Structure
Hotel-Booking-Data-Wrangling-Platform-Analysis
│
├── hotel_booking_platform_analysis.ipynb  
└── README.md  

---

## How to Run

```bash
git clone https://github.com/ramubattu321/Hotel-Booking-Data-Wrangling-Platform-Analysis.git
cd Hotel-Booking-Data-Wrangling-Platform-Analysis
pip install pandas numpy matplotlib
jupyter notebook

Author
Ramu Battu
MS Data Analytics, California State University, Fresno
