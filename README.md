SAP ABAP Vendor & Material Management Project

 Project Overview

This project is an end-to-end **SAP ABAP development project** developed using **ABAP on SAP S/4HANA**.

The project demonstrates the complete flow of retrieving, processing, displaying, and presenting **Vendor, Purchase Order, and Material information** using standard SAP tables and ABAP development techniques.

The project was developed to gain practical experience in real-world SAP ABAP development, including **Reports, Internal Tables, ALV, Smart Forms, Modularization, and SAP database operations**.

  Project Objectives

* Develop a practical SAP ABAP application using standard SAP tables.
* Retrieve Vendor, Purchase Order, and Material-related data.
* Process and combine data from multiple SAP tables.
* Display business data using ALV reports.
* Apply ABAP programming concepts used in real-world SAP projects.
* Follow a structured development approach from database retrieval to final output.
  
 Project Flow

SAP Standard Tables
        ↓
Data Retrieval
        ↓
Internal Tables & Work Areas
        ↓
Data Processing
        ↓
ALV Report
        ↓
Formatted Output 



 SAP Tables Used

| Table | Purpose                      |
| ----- | ---------------------------- |
| EKKO  | Purchase Order Header Data   |
| EKPO  | Purchase Order Item Data     |
| LFA1  | Vendor Master Data           |
| MARA  | Material Master Data         |
| MAKT  | Material Description         |


 Technologies & Tools

* SAP S/4HANA
* SAP ABAP
* ABAP Development Tools (ADT / Eclipse)
* SAP GUI
* Open SQL
* Internal Tables
* Work Areas
* Selection Screens
* ALV Reports
* Function ALV
* OO ALV / SALV
* Modularization
* Debugging
* Git & GitHub


 Key ABAP Concepts Implemented

 1. Selection Screen

Selection parameters and select-options are used to allow users to provide input dynamically.

Example:
SELECT-OPTIONS:
  s_ebeln FOR ekko-ebeln,
  s_lifnr FOR ekko-lifnr.
  
 2. Database Retrieval

Data is retrieved from SAP standard tables using Open SQL.

The project combines information from:

* Purchase Order Header
* Purchase Order Items
* Vendor Master
* Material Master
* Material Description

 3. Internal Tables

Internal tables and work areas are used to temporarily store and process retrieved business data.

Database
   ↓
Internal Table
   ↓
Processing
   ↓
Final Output

 4. ALV Reporting

The processed data is displayed using SAP ALV reporting.

The project covers:

* Function Module ALV
* REUSE_ALV_GRID_DISPLAY
* Field Catalog
* Layout
* Sorting
* Filtering
* OO ALV / SALV
 
 5. Smart Forms

Smart Forms are used to generate a structured business document containing information such as:

* Vendor Number
* Vendor Name
* Material Number
* Material Description
* Material Type
* Quantity
* Unit of Measure
* Plant

 Sample Business Flow


User enters Purchase Order / Vendor criteria
                  ↓
             Selection Screen
                  ↓
             EKKO / EKPO
                  ↓
          Vendor & Material Data
                  ↓
            Data Processing
                  ↓
             Internal Table
                  ↓
              ALV Output
                 
 Project Structure


SAP-ABAP-PROJECTS
│
├── Reports
│   └── ZMM_VENDOR_MATERIAL_REPORT2461
│
├── ALV
│   ├── Function ALV
│   └── OO ALV / SALV
│
├── Data Dictionary
│   ├── Structures
│   └── Table Types
│
└── Documentation
    └── Screenshots


 Testing

The application was tested using different selection criteria to verify:

* Correct database retrieval
* Correct vendor information
* Correct material information
* Correct purchase order details
* Correct ALV display

 Key Learning Outcomes

Through this project, I gained practical experience in:

* SAP ABAP development
* Open SQL
* SAP standard tables
* Internal tables and work areas
* ALV reporting
* Data processing
* Modularization
* Debugging
* ABAP Development Tools
* SAP S/4HANA development workflow
* Git and GitHub version control

 Author

Mulaka Abhinayasri Reddy

B.Tech – Computer Science and Engineering
Vignan's Lara Institute of Technology and Science

 Certification

SAP Global Certification – SAP S/4HANA / ABAP


 Project Highlights

SAP ABAP | SAP S/4HANA | ALV | Smart Forms | Open SQL | Internal Tables | SAP Standard Tables | Eclipse ADT | GitHub
