# Online Food Ordering App — SESD Lab Assignment 5

An end-to-end Online Food Ordering System designed and managed using Scrum agile methodology on GitHub Projects. This system enables users to discover restaurants, explore categorized menus, manage food carts, perform secure mock online payments, and track order deliveries in real time.

---

## 📋 Project Overview

- **Course:** Software Engineering & Software Design (SESD)
- **Lab Assignment:** Lab Assignment 5 — Agile Scrum Project Management using GitHub
- **Application:** Online Food Ordering System
- **GitHub Project Board:** [Online Food Ordering - Scrum Project](https://github.com/users/anvesh1421/projects/1)
- **Repository:** [online-food-ordering-app](https://github.com/anvesh1421/online-food-ordering-app)

---

## 🚀 Core Deliverables & Backlog Features

The product backlog consists of five major epics/features with modular sub-issues:

### 1. Customer Login (#1)
- **User Story:** *As a customer, I want to securely log into my account using my username and password so that I can access personalized menus, saved addresses, and payment details.*
- **Sub-tasks:**
  - `#6 Create Login UI` — Responsive login layout with username, password, and login button.
  - `#7 Create Username Field` — Username input field with format validation and placeholders.
  - `#8 Create Password Field` — Masked password input with show/hide toggle.
  - `#9 Implement Login Validation` — Authentication credential validation.
  - `#10 Display Error Message` — Error toast/alert component for invalid credentials.
  - `#11 Test Login` — Unit and integration tests for authentication workflows.

### 2. Browse Restaurants and Menu (#2)
- **User Story:** *As a user, I want to browse restaurants and their menus with dish details and prices so that I can choose what food to order.*
- **Sub-tasks:**
  - `#12 Create Restaurant Page` — Restaurant discovery grid layout with filters.
  - `#13 Display Restaurants` — Restaurant cards with cuisine, ratings, and delivery ETA.
  - `#14 Create Menu Page` — Dedicated menu page layout with category tabs.
  - `#15 Display Food Items` — Food item cards with descriptions and dietary tags.
  - `#16 Display Food Prices` — Price formatting and addon/customization pricing.
  - `#17 Test Menu` — Functional verification of menu navigation and filtering.

### 3. Shopping Cart (#3)
- **User Story:** *As a customer, I want to manage items in my cart so that I can review selections, adjust quantities, and see the exact pricing before checkout.*
- **Key Capabilities:**
  - Add/remove items with quantity adjustments.
  - Real-time subtotal, GST/tax, delivery charges, and grand total calculations.
  - Promo code discounts and order notes.

### 4. Online Payment (#4)
- **User Story:** *As a user, I want to pay online securely using my preferred payment method so that my order is immediately confirmed and dispatched.*
- **Key Capabilities:**
  - Multi-mode payment support (UPI, Credit/Debit Card, Net Banking, COD).
  - Client-side payment form validation and CVV protection.
  - Mock payment gateway response with instant confirmation status.

### 5. Order Tracking (#5)
- **User Story:** *As a customer, I want to track my food order in real time so that I know its preparation status and estimated arrival time.*
- **Key Capabilities:**
  - Visual status stepper: `Order Placed` ➔ `Kitchen Preparing` ➔ `Out for Delivery` ➔ `Delivered`.
  - Dynamic estimated delivery time countdown.
  - Delivery partner details and contact options.

---

## 📊 Scrum Workflow & Project Configuration

The project is managed using **GitHub Projects (v2)** following agile Scrum principles:

### Custom Project Fields:
- **Status:** `Todo`, `In Progress`, `Testing`, `Done`
- **Priority:** `High` (Red), `Medium` (Orange), `Low` (Green)
- **Story Points:** Numerical estimation (Fibonacci: 1, 3, 5, 8)
- **Iteration:** 2-week Sprint cycles
  - **Iteration 1:** Core Authentication & Restaurant Browsing (Oct 14 – Oct 27)
  - **Iteration 2:** Shopping Cart & Online Payment (Oct 28 – Nov 10)
  - **Iteration 3:** Order Tracking & Live Telemetry (Nov 11 – Nov 24)

### Sprint Board Columns:
1. **Todo:** Backlog items ready for development.
2. **In Progress:** Items actively being worked on (e.g., *Customer Login*, *Create Login UI*).
3. **Testing:** Implemented features under QA validation (e.g., *Implement Login Validation*).
4. **Done:** Fully implemented, verified, and accepted features (e.g., *Online Payment*).

---

## 🛠️ Technology Stack & Architecture

- **Platform:** Web & Mobile Responsive
- **Project Tracking:** GitHub Issues, GitHub Sub-Issues, GitHub Projects (v2)
- **Process Model:** Agile Scrum Framework with 2-Week Sprints
