# RealEstateConsultancyProject
A Python-powered real estate agent at your command line.

#🏡 Real Estate Consultancy Project
##📌 Overview

This project is a real estate consultancy system implemented in Python with an object-oriented design.
It simulates a property consultancy where users, regions, and estates (apartments, houses, and stores) are managed alongside deals (sell/rent).
The program is command-line based, but can also run in Google Colab for educational/demo purposes.

##✨ Features

###Users: Each user has first_name, last_name, phone_number.

###Regions: Defines property location.

###Estates: Supports three property types:

####🏢 Apartment (with elevator, parking, floor)

####🏠 House (with yard, multiple floors)

####🏬 Store

###Deals:

####📈 Sell (price per meter, discount, convertibility)

####📉 Rent (initial deposit, monthly rent, convertibility, discount)

##Advertisements: Combines estates with deal types (e.g., ApartmentSell, HouseRent).

###Manager:

Search estates (with filters and ranges like area__min, price__max).

Count existing records.

Retrieve objects by field.

Handler (CLI):

r → Generate report (counts).

s → Show all advertisements.



#📖 Project Explanation

This project defines a real estate consultancy system with the following components:

##1. Property Types

###🏢 Apartment

###🏠 Villa/House

###🏬 Store

##2. Usage Types

###🏦 Commercial

###🏢 Office

###🏠 Residential

##3. Property Attributes

Each property includes:

Seller’s name and contact number

Area (square meters)

Number of rooms

Year built

Region

Address

Additional per-type attributes:

Apartment: Elevator, Parking, Floor number

House: Yard, Number of floors

##4. Advertisement Types

For Sale:

Price per square meter

Discount availability

Exchange option

For Rent:

Deposit

Monthly rent

Convertibility

Discount

##5. System Requirements

Ability to generate reports from stored data

Ability to list all available advertisements

Ability to search by fields:

Region

Price

Area

Number of rooms

Each entity must have a unique ID

A property can exist both for sale and for rent

All classes must store data in an objects_list
