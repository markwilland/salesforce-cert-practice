# Salesforce Certification Study Tracker

A Salesforce application for managing certification study materials and tracking exam preparation progress. Includes community compiled and defined data sets regarding Salesforce certification/trailhead materials.

## Data Model

**Certification**
- Salesforce certifications (Administrator, Advanced Administrator, etc.)

**Certification Topic**
- Study topics within each certification
- Lookup to Certification

**Certification Prerequisite**
- Junction object modeling prerequisite relationships between certifications

**Exam Question**
- Practice exam questions organized by topic
- Question types: Multiple Choice or Multi-Select

## Roadmap

- ✅ Data model
- ⬜ Sample data & list views
- ⬜ Quiz generation interface (Flow or LWC)
- ⬜ Quiz attempt tracking
- ⬜ Performance analytics

## Disclaimer
This repo/author makes no claims about the accuracy of data surrounding Salesfor.ce Certification's and prerequites. For complete up to date information, refer to official documentation on https://trailheadacademy.salesforce.com/