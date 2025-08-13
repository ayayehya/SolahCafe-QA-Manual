# Sola Cafe-QA-Manual
Repository Purpose: This repository showcases my work as a Manual QA/Tester on the Solah Café project (Mobile App for customers + Web Admin Dashboard). It includes requirements documentation, test plans, test cases, bug reports, RTM, and execution reports.

🔎 Overview

Solah Café platform consists of:

Customer Mobile App (iOS/Android): Login with Saudi phone number and OTP, browse menu, add to cart, payment, order tracking, loyalty system, and in-app chat with support.

Admin Web Dashboard: Manage branches, products, orders, coupons, banners, static pages, customers, notifications, admin roles, and general settings.

Reference requirements release date: 1 July 2025Last repo update: 14 Aug 2025

🎯 Goals

Provide an easy and fast ordering experience.

Encourage customers with offers and discounts.

Increase repeat orders and loyalty.

🧭 Scope

Covers core functional testing + usability/content checks + basic performance/security sanity within manual testing limits.

1) Mobile App (iOS/Android) – Authentication, branch selection, homepage banners, menu categories, product details, cart, coupons, checkout/payment, order history, map tracking, notifications, loyalty points, chat, and profile management.

2) Admin Dashboard (Web) – Authentication, dashboard stats, profile management, RBAC, admin management, categories, product properties/add-ons, product management, customers, orders, coupons, notifications, banners, static pages, chat, and general settings.

🖥️ Environment Details

Web: Chrome, Edge, Safari, Firefox (latest 2 versions)

Mobile: Android 10–14, iOS 16–18

OS: Windows 10/11, macOS 13+

Languages: Arabic (RTL) primary, English (LTR) optional

Staging API: https://staging.api.solahcafe.example

Production API: https://api.solahcafe.example

🧰 Tools

Task management: ClickUp / Jira

Test documentation: Google Sheets/Excel

Bug tracking: GitHub Issues / Jira

API testing: Postman

Debugging: Chrome DevTools, Charles Proxy

Design/flow diagrams: draw.io / Miro

Screenshots/recording: Lightshot, Loom

📁 Repository Structure

SolahCafe-QA-Manual/
├─ README.md
├─ 01_Requirements/
├─ 02_Test_Plan/
├─ 03_Test_Scenarios/
├─ 04_Test_Cases/
├─ 05_Test_Data/
├─ 06_Bug_Reports/
├─ 07_Test_Execution/
├─ 08_RTM/
├─ 09_Checklists/
├─ 10_Utilities/
└─ 99_Archive/

🧩 Conventions

Test Case ID: TC-<MODULE>-<###>

Bug ID: BUG-<MODULE>-<###>

Status: Pass, Fail, Blocked, N/A

Severity: Critical, Major, Minor, Trivial

Priority: P0, P1, P2

📌 Deliverables

Requirements (01_Requirements)

Test Plan/Strategy (02_Test_Plan)

Test Scenarios (03_Test_Scenarios)

Test Cases (04_Test_Cases)

Bug Reports (06_Bug_Reports)

Execution Reports (07_Test_Execution)

RTM (08_RTM)

Checklists (09_Checklists)

✅ Quality Gates

Coverage: ≥95% of core functional requirements covered by test cases.

RTM: Every requirement linked to one or more test cases.

Bugs: Each bug includes repro steps, expected/actual results, severity/priority, and evidence.

✍️ Author

Aya Yehya Elsaid — Manual QA/Software Tester
Email: ayayehya045@gmail.com
LinkedIn: https://www.linkedin.com/in/aya-yehya-06a9ab221

For feedback or collaboration, open an Issue or contact directly.
