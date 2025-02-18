# UNIACE SEO ANALYTICS 2018

**Date: June 2nd, Authored by: Hoa Ly**

---

## Table of Contents

1. [Overview](#overview)
2. [Uniace Introduction](#uniace-introduction)
3. [Data Collection](#data-collection)
4. [Key Findings](#key-findings)

---

## Overview

This report evaluates the performance of **Uniace.vn**, an online learning platform that connects learners, work, and knowledge sharing. The analysis is based on data collected from **August 1, 2022, to August 24, 2022**, and provides insights into customer behavior, search keywords, search engines, and more. These insights aim to help devise suitable marketing campaigns.

---

## Uniace Introduction

- **Uniace** is an online learning platform designed to:
  - Provide in-depth training programs for the younger generation.
  - Offer digital transformation solutions for businesses.
- The **Uniace.vn** website operates as a mini social network integrated with courses. Users can:
  - Register an account using their email.
  - Post and interact on the website.
  - Participate in free courses.
- For access to premium courses, users need to subscribe to membership packages or purchase specific courses.

---

## Data Collection

### Dataset Details

- **Timeframe**: August 1, 2022 – August 24, 2022.
- **Data Sources**: Three different Excel files were processed using SQL to:
  - Eliminate duplicate data.
  - Correct erroneous rows and columns.
  - Adjust data types.
  - Create necessary columns for analysis.

### Final Dataset Schema

| Column Name     | Data Type | Meaning                          | Note                                                                 |
|-----------------|-----------|----------------------------------|----------------------------------------------------------------------|
| Email           | Varchar   | User’s email                     | Value "0" means the customer did not register.                      |
| Content Clicked | Varchar   | Content users clicked on         |                                                                      |
| Post Name       | Varchar   | Post name, topic name            | Value "0" means the content accessed by the customer is unknown.    |
| MA Referrer     | Varchar   | Source of access                 | Value "0" means the customer accessed directly, not through a third party. |
| ma_path         | Varchar   | Website path                     |                                                                      |
| IP Address      | Varchar   | Visitor’s IP address             |                                                                      |
| Date            | Datetime  | Date of the action               |                                                                      |
| Hour            | Int       | Time of the action               |                                                                      |

---

## Key Findings

### 1. Website Performance

- **Total Visits**: 59,040
- **Total Visitors**: 14,690
- **Registered Users**: 2,493 (16.31% of total visitors).
- **Most Interacted Content**: Homepage (88.23% interaction rate), primarily for account registration and Uniace introduction.
- **Daily Visit Trends**:
  - Highest daily visits: 4,000.
  - Other days' visits range: 2,000–3,000.
  - Lowest daily visits: Around 300.

### 2. Access Patterns

- **Direct Access**: 52.02% of users access the website directly without using a third-party search engine, indicating familiarity with Uniace.
- **Search Engines**:
  - Google is the most common tool used to find Uniace, peaking between 9 AM–10 AM and 2 PM–5 PM.
  - Limited use of other platforms like Facebook or Coccoc.
- **Access Times**:
  - **Non-Registered Users**: Peak access times are 9 AM–11 AM, 2 PM–4 PM, and 10 PM–11 PM.
  - **Registered Users**: Peak access time is 12 PM (lunch break).
  - Normal and Work users show similar access patterns, suggesting many Normal email users may also be office workers.

### 3. User Registration Insights

- **Email Usage**:
  - 59.74% of users do not register an email.
  - A significant portion uses normal emails, while only a small fraction uses educational (.edu) or work emails (.outlook).

### 4. Behavioral Insights

- Non-registered users predominantly use Google to find the website.
- Registered users tend to access the website directly without third-party intermediaries.
- The highest number of direct website accesses occurs between 11 AM–1 PM.

---

## Conclusion

This analysis highlights key trends in user behavior, access patterns, and registration habits on the Uniace platform. These insights can guide future marketing strategies to improve user engagement, expand reach across multiple platforms, and enhance the overall user experience.

For further inquiries or contributions, feel free to open an issue or contact the author.

---
