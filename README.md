# mini_normalization
# Database Normalization Project

## Project Overview
This project demonstrates the process of transforming unnormalized data structures into a relational database format following the principles of First (1NF), Second (2NF), and Third Normal Form (3NF). The goal is to eliminate data redundancy and ensure data integrity.

## Case Studies Included

### 1. Patient Medication Tracking
Converted a flat patient medication record into five distinct tables to handle many-to-many relationships and ward/bed assignments.
- Patient Table: Centralizes patient identity.
- Drugs Table: Catalogues available medication.
- Patient-Drug Table: Links patients to prescriptions with dosage and dates.
- Ward and Bed Tables: Manages hospital infrastructure and patient placement.

### 2. Sales Order System
Transformed a manual sales order document into a scalable relational model.
- Customer Table: Stores unique customer contact information.
- Orders Table: Tracks order dates, clerks, and totals per transaction.
- Products Table: Maintains the master list of items and unit prices.
- Order Items Table: A junction table managing quantities and line-item totals.

## Key Normalization Principles Applied
- Elimination of repeating groups (1NF).
- Removal of partial functional dependencies (2NF).
- Removal of transitive dependencies (3NF) to ensure non-key attributes depend only on the primary key.

## Files in this Repository
- Patient_Normalization.xlsx: The normalized schema for hospital data.
- Sales_Order_Normalization.xlsx: The normalized schema for retail data.
- Original_Requirements.jpg: The source material used for the exercise.
