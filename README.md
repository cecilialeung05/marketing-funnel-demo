# Marketing Funnel Demo

A lightweight demo showcasing a **marketing funnel** with integrated **Google Tag Manager (GTM)** and **Google Analytics 4 (GA4)** event tracking. This project highlights how to track user interactions—like button clicks, form submissions, and pricing-page visits—and pass those events into GA4 for analysis. It also demonstrates how leads can be pushed into a CRM (e.g., HubSpot) for follow-up.

**Live Demo:**  
[Marketing Funnel Demo on Vercel](https://marketing-funnel-demo.vercel.app/)

---

## Overview

Many marketing teams struggle to measure which campaigns and interactions lead to **high-quality leads**. This demo solves that by:

- Tracking visitor interactions (button clicks, form submissions, pricing-page visits).
- Sending event data to GA4 to analyze lead behavior.
- (Optional) Syncing high-intent leads to a CRM (e.g., HubSpot) for sales follow-up.

---

## Features

- **Landing Page** with a simple, modern design.  
- **Calls to Action**: “Sign Up” and “Contact Us” buttons.  
- **Contact Form** to capture name, email, and company details.  
- **Pricing Link** to simulate a high-intent page visit.  
- **Google Tag Manager** embedded for tracking:  
  - Button clicks  
  - Form submissions  
  - Pricing-page visits  
- **Google Analytics 4** integration:  
  - Receives custom events (e.g., `sign_up_click`, `form_submission`, `pricing_page_view`).  
  - **DebugView** verification to confirm data flow.  

---

## Tech Stack

- **Front End**: HTML, CSS  
- **Analytics**: Google Tag Manager (GTM), Google Analytics 4 (GA4)  
- **Deployment**: [Click for Demo!](https://vercel.com/)  
- **(Optional) CRM Integration**: HubSpot
*(Note: GTM and GA4 are products of Google.)*

---
          
## Gallery

![GA4 Realtime Overview](assets/GA4_Realtime_Overview.png)
Displays real-time user activity in GA4 and confirms that events (e.g., sign_up_click) are being sent.

![GTM Tags](assets/GTM_Tags.png)
Shows key GTM tags (GA4 configuration and event tags) tracking user interactions.

---


## What I Learned 

- **Google Tag Manager** setup for button click and form submission triggers. 
- **Google Analytics 4** configuration, custom event creation, and DebugView validation.
- **Front-End best practices** a clean HTML/CSS structure that’s easy to integrate with tracking scripts.
- **Deeployment with Vercel** for a fast, shareable demo environment.

--

License
This project is licensed under the MIT License – you’re free to modify and use it for your own learning or portfolio.

-- 

Thank You!
Feel free to explore the live demo and interact with the site to see how events are tracked in real time. If you have any questions or feedback, don’t hesitate to reach out! ☺ 