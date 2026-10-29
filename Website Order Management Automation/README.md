# Website Order Management Automation

An n8n workflow that automates website order handling using Google Sheets and Gmail.

## 📌 Overview

This project automates the process of receiving website orders, storing order details in Google Sheets, notifying the business owner, and sending confirmation emails to customers.

The goal is to reduce manual work and make order management simpler and more organized.

## ⚙️ Workflow

1. **Webhook:** Receives order information submitted through the website.
2. **Edit Fields:** Organizes the incoming order data.
3. **Google Sheets:** Saves the order details in a spreadsheet.
4. **Owner Notification:** Sends an email to the business owner when an order is received.
5. **Customer Confirmation:** Sends a confirmation email to the customer.
6. **Webhook Response:** Returns a response to the website after processing.

## ✨ Key Features

* Automated website order collection.
* Automatic order storage in Google Sheets.
* Email notifications for the business owner.
* Order confirmation emails for customers.
* Organized order records for easier tracking.
* Reduced manual data entry and follow-up.

## 🛠️ Tools & Technologies

* n8n
* Webhooks
* Google Sheets
* Gmail

## 🔄 Example Use Case

When a customer places an order through a website:

* The order information is received by n8n.
* The order details are saved in Google Sheets.
* The business owner receives an email notification.
* The customer receives an order confirmation email.
* The website receives a response from the workflow.

## 🚀 Setup Requirements

* An n8n instance.
* A Google account with access to Google Sheets and Gmail.
* A website or form that can send order information to an n8n webhook.
* Correct field mapping between the website form and workflow.

## 🧪 Testing

The workflow has been tested in n8n, and the nodes shown in the provided execution screenshot completed successfully.

Before using it on a live website, test the complete process with the actual order form and verify that all fields and email recipients are mapped correctly.

## 🔐 Security

* Keep API keys and credentials private.
* Never upload passwords, tokens, or other secrets to GitHub.
* Test the workflow before connecting it to a live ordering system.

## 👩‍💻 About

**Saleha AI Studio** builds practical automation workflows to help simplify business processes.

This project demonstrates how n8n, Google Sheets, and Gmail can work together to automate basic website order management.
