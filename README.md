# Marketing Funnel Demo

A lightweight demo showcasing a **marketing funnel** with integrated **Google Tag Manager (GTM)** and **Google Analytics 4 (GA4)** event tracking. This project highlights how to track user interactions—like button clicks, form submissions, and pricing-page visits—and pass those events into GA4 for analysis. It also demonstrates how leads can be pushed into a CRM (e.g., HubSpot) for follow-up.

**Live Demo:**  
[Marketing Funnel Demo on Vercel](https://marketing-funnel-demo.vercel.app/)

---
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
- **Deployment**: [Vercel](https://vercel.com/)  
- **(Optional) CRM Integration**: HubSpot

---

## Project Structure

```bash
marketing-funnel-demo/
├── index.html       # Main landing page
├── pricing.html     # (Optional) Pricing page
├── styles.css       # External stylesheet
└── ...             # GTM, GA4, or HubSpot snippets are integrated in index.html
