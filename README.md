# Post-Service Profit Loop Automation System (HVAC Business)

## Demo

A short walkthrough of the system is available below:

👉 [Click here to watch the demo](https://drive.google.com/file/d/1z88IYR1-KZtt3eijEjDaAwDGuLC8qI9B/view?usp=drive_link)
## Overview

Service-based businesses often focus heavily on acquiring new customers but fail to maximize value from existing ones. HVAC companies, in particular, miss opportunities to collect reviews and generate referrals after completing jobs.

This project implements an automated post-service system that transforms satisfied customers into promoters by capturing reviews and incentivizing referrals at the right moment.

---

## Problem Statement

* Lack of consistent review collection
* Missed opportunities for customer referrals
* No structured post-service follow-up
* Underutilization of satisfied customers

---

## Solution

An automated "Profit Loop" that:

* Activates immediately after a job is completed
* Requests customer reviews through SMS and email
* Tracks engagement with review links
* Sends referral offers to highly satisfied customers

---

## Key Features

### Trigger-Based Automation

* Workflow starts when an opportunity is moved to the "Won/Completed" stage
* Ensures every completed job enters the follow-up sequence

---

### Review Request System

* Sends automated review requests via SMS and/or email
* Encourages customers to leave feedback on platforms like Google
* Improves online reputation and social proof

---

### Engagement Tracking

* Uses a wait step to monitor:

  * Email opens
  * Link clicks
* Identifies engaged and satisfied customers

---

### Referral Offer Automation

* If the customer clicks the review link:

  * System waits 24 hours
  * Sends a referral incentive (e.g., "$50 for your next referral")
* Capitalizes on peak satisfaction timing

---

### Customer Lifecycle Optimization

* Converts one-time customers into repeat clients and promoters
* Creates a continuous loop of reviews and referrals

---

## Workflow Summary

1. Job is marked as "Won/Completed"
2. Workflow is triggered automatically
3. Review request is sent via SMS/Email
4. System waits and tracks engagement
5. If review link is clicked:

   * Wait 24 hours
   * Send referral offer
6. Customer is encouraged to refer new leads

---

## Tech Stack

* CRM Platform: GoHighLevel (GHL)
* Automation: Workflow triggers and conditional logic
* Communication: SMS and Email automation
* Tracking: Link click and engagement tracking

---

## Business Impact

* Increases number of online reviews
* Builds strong social proof
* Generates referral-based leads
* Improves customer lifetime value
* Reduces reliance on paid advertising

---

## Use Cases

* HVAC companies
* Home service businesses
* Contractors and repair services
* Any service-based business

---

## Future Enhancements

* Automated review platform routing (Google, Yelp, etc.)
* Negative feedback handling workflow
* Loyalty and rewards program integration
* Analytics dashboard for review and referral tracking

---

## Author

Urwa
AI Automation Developer and CRM Specialist

