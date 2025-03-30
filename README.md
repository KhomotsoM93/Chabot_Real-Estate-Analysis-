# Chatbot Analysis 

## Table of Contents

- [Background Overview](#background-overview)
- [Data Structure Overview](#data-structure-overview)
- [Executive Summary](#executive-summary)
- [Insights Deep Dive](#insights-deep-dive)
- [Recommendations](#recommendations)
  
## Background & Overview

---

The real estate industry relies on timely communication and seamless customer engagement. AI chatbots have revolutionized customer interactions by providing instant responses, answering property inquiries, scheduling viewings, and even qualifying leads. This project aims to evaluate the efficiency of AI-powered chatbots in handling customer inquiries, reducing response time, and increasing lead conversion.

![ERD](https://github.com/user-attachments/assets/79402672-cfb8-47aa-a951-e7bc8b04895b)


### Key Business Questions

- Which type of inquiries are most common?
- Which Chatbot responses are used most frequently?
- How many inquiries did the Chatbot handle in total?
- What is the fastest & slowest time?
- What is the average response time of the Chatbot-assisted bookings?

## Data Structure Overview 

The dataset consists of real estate chatbot interactions, covering various inquiry types, response times, lead qualifications, and booking conversions. For the database  

### Tools

- Microsoft SQL Server - Data Analysis & ERD

## Executive  Summary 

### Key Findings

- Most Common Inquiries: Property Info (16), Booking (13), Financing (10), Other (7), Agent Contact (4)
- Average Response Time: 5.2 seconds
- Lead Qualification Rate: 48% of inquiries convert into leads (24 out of 50 inquiries were qualified leads)
- Booking Success Rate: 55% of inquiries lead to a scheduled viewing
- Slowest Response Time: 10 seconds (needs optimization)
- Fastest Response Time: 1 second
- Failed Conversions: Financing inquiries have the highest failure rate

### Business Implications

- Customers primarily seek property information and booking assistance, indicating the chatbot should focus on providing detailed property insights and seamless scheduling.
- The response time is within an acceptable range, but further optimization is needed for outliers (e.g., responses taking longer than 5 seconds).
- Lead conversion can be improved by analyzing why certain inquiries fail to qualify.

## Insights Deep Dive

### 1.Customer Engagement & Inquiry Analysis

####  Most Common Inquiries

- Majority of inquiries are related to property details and booking viewings.
- Financing and agent contact inquiries are less frequent but still important for lead conversion.

#### Most Used Chatbot Responses

- The most frequent responses are providing property info and confirming viewings.
- A small percentage of inquiries require human escalation.

#### Total Chatbot Workload

- Chatbots handle hundreds of inquiries daily, reducing manual workload.

### 2.Response Time Analysis

#### Average Response Time

- The chatbot responds in 5.2 seconds on average, but some responses are too slow (up to 10 seconds).

#### Identifying Slowest and Fastest Responses

- The fastest response is 1 second, but some responses take too long, impacting customer experience.

### 3.Lead Qualification & Conversion

#### Booking Success Rate

- The chatbot successfully schedules 55% of viewings, showing strong customer engagement.

## Recommendations 

Based on the analysis, we recommend the following;
### Optimizing Chatbot Efficiency
 - Improve response speed by optimizing AI processing for complex inquiries.
 - Identify common delays and eliminate unnecessary chatbot loops.
   
### Enhancing Lead Conversion
 - Focus on better qualifying financing-related inquiries to boost conversion rates.
 - Personalize chatbot interactions for returning customers to build engagement.
   
### Improving Booking Success
 - Provide real-time available slots for viewing instead of requiring manual confirmation.
 - Allow customers to connect with agents for special requests.
