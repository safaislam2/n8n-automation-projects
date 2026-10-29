# Booking Management Automation with n8n

An automated booking management workflow built with n8n, Google Sheets, Gmail, and Webhooks. It organizes incoming booking requests, notifies the business owner, and sends confirmation emails to clients automatically.

## Overview

This project automates the essential steps of booking request management, reducing repetitive manual tasks and keeping booking information organized.

## Features

* **Automated Data Collection:** Receives booking request data through a Webhook.
* **Data Processing:** Organizes incoming information using the Edit Fields node.
* **Google Sheets Integration:** Automatically appends booking records to a Google Sheet.
* **Owner Email Notification:** Sends an email notification when a new booking request arrives.
* **Client Confirmation Email:** Sends a confirmation email to the person who submitted the booking request.
* **Automated Response:** Returns a response after processing the request.

## Workflow

The workflow follows these steps:

1. Webhook receives the booking request.
2. Edit Fields prepares the incoming data.
3. Google Sheets stores the booking information.
4. Gmail sends a notification to the business owner.
5. Gmail sends a confirmation email to the client.
6. Webhook returns a response.

## Technologies Used

* **n8n** — Workflow automation
* **Webhooks** — Incoming request handling and response delivery
* **Google Sheets** — Booking data storage
* **Gmail** — Email notifications and client confirmations

## Setup Instructions

1. Create an n8n workflow.
2. Add a Webhook node to receive booking request data.
3. Configure the Edit Fields node to prepare the required fields.
4. Connect Google Sheets and configure the append-row operation.
5. Connect Gmail to send the owner notification.
6. Configure another Gmail node to send the client confirmation email.
7. Configure the final Webhook response.
8. Add the required credentials and test each step.
9. Activate or publish the workflow according to your n8n version and configuration.

## Requirements

* An n8n instance
* A Google account with access to Google Sheets
* Gmail credentials configured in n8n
* A source capable of sending booking data to the Webhook

## Security Notes

* Never upload API keys, access tokens, passwords, or private credentials.
* Keep sensitive booking information private.
* Configure appropriate access permissions for Google Sheets and Gmail.

## Project Purpose

This project demonstrates how workflow automation can simplify booking management, reduce repetitive tasks, and improve communication with clients.

---

**Created by Saleha AI Studio**

*Making Work Smarter with Automation.*
