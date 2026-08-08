# 1. Project Name

## 🚕 Ola Ride Insights — Bookings, Revenue & Cancellation Analysis

A Power BI dashboard analyzing a month of Ola ride-booking data to uncover where bookings are being lost, which segments drive revenue, and where the business is leaking money.

---

# 2. Description & Purpose

Ride-hailing platforms lose revenue every time a booking doesn't turn into a completed ride. This project cleans and models 20,000+ Ola bookings to quantify that loss, break down performance by vehicle type and payment method, and flag the operational issues (driver cancellations, no-driver-found, low repeat usage) that hurt both revenue and rider trust.

**Purpose:** turn raw booking-level data into a decision-ready dashboard leadership can use to spot where completion rate, revenue, and retention are breaking down.

---

# 3. Tech Stack

- **Excel** — data cleaning & preparation
- **Power BI** — data modeling & dashboard build
- **DAX** — custom measures (cancellation rate, revenue calculations) and calculated columns

---

# 4. Data Source

Ola Bookings dataset — [Kaggle](https://www.kaggle.com/) (20,000+ ride records, Bangalore, July 2024). Fields include Booking ID, Date, Vehicle Type, Booking Status, Booking Value, Payment Method, Ride Distance, Driver/Customer Ratings, and cancellation reasons.

---

# 5. Features & Highlights

**Business problem:** ~38% of bookings never turn into completed rides, and it wasn't clear whether this was a customer-behavior issue or a supply-side (driver) issue — or how much revenue it was costing.

**Goal:** build a dashboard that separates completed vs. failed rides, identifies *who* is causing failures (driver vs. customer), and surfaces revenue and retention impact by segment.

**Dashboard walkthrough (5 pages):**
- **Overview** — total bookings, revenue, and success/failure split at a glance
- **Vehicle Type** — revenue, ride distance, and ratings broken down across 7 vehicle categories (Sedan, SUV, Auto, Bike, etc.)
- **Revenue** — booking value trends and payment-method mix (cash vs. digital)
- **Cancellation** — cancellation rate (DAX measure) split by driver- vs. customer-initiated, with top cancellation reasons
- **Ratings** — average driver/customer ratings across segments

**Business impact:**
- ₹69L+ in revenue analyzed and segmented
- Found 38% ride failure is **driver-side heavy** (cancellations + "Driver Not Found"), not customer-side — redirecting where the
**business should fix the problem**
- Flagged a ~1% repeat-customer rate, exposing a retention gap the completion-rate numbers alone wouldn't show
- Identified 54% cash dependency as a digital-payment adoption opportunity

- **Screenshot & Demos:**
- Dashboard Preview :https://github.com/sujalsolankii/Ola-Ride-Dashboard-/blob/main/ola%20dashboard.png
