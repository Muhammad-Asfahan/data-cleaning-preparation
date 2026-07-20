# data-cleaning-preparation
Data Cleaning and Preparation Project completed as part of DecodeLabs Data Analytics Internship 2026
# Data Analytics - Project 1: Data Cleaning & Preparation

## Overview
This project involved cleaning a raw e-commerce dataset by handling 
missing values, checking for duplicates, and standardizing formats — 
part of the DecodeLabs Data Analytics Internship (2026).

## What was done
- Imputed missing CouponCode values using Mode (FREESHIP) — 622 records filled
- Verified OrderID uniqueness — 0 duplicates found
- Verified date format consistency — all dates in YYYY-MM-DD format
- Verified text column consistency (Product, PaymentMethod, OrderStatus, ReferralSource, CouponCode)
- Verified/fixed numeric precision (UnitPrice, TotalPrice) — rounded to 2 decimal places

## Tools used
Excel — formulas: COUNTIF, COUNTBLANK, ROUND, UNIQUE, MOD, MODE

## File
`Decode Data Analytics.xlsx` — final cleaned dataset with a Change Log sheet documenting all fixes
