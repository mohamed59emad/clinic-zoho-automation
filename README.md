# 🩺 Clinic Zoho CRM & n8n Automation Workflow

An automated end-to-end appointment and patient management pipeline designed to eliminate manual data entry errors, save time, and streamline clinic operations by integrating Zoho CRM, Google Sheets, Gmail, and Telegram.

---

## 🚀 Problem & Business Value
Managing clinic appointments manually often leads to data entry errors, communication delays, and wasted time. This automated workflow ensures that:
- Patient appointments created in **Zoho CRM** are instantly captured.
- Data is logged accurately with zero manual overhead.
- Instant confirmations are sent to the patient via **Gmail**.
- Real-time notifications and all meeting details are dispatched to the clinic team via **Telegram**.

---

## 🛠️ Tech Stack & Tools Used
- **n8n:** For building and orchestrating the core automation workflow.
- **Zoho CRM:** For managing patient meetings and scheduling.
- **Google Sheets:** For centralized data storage and record-keeping.
- **Gmail API:** For automated patient email notifications.
- **Telegram Bot API:** For instant team alerts.

---

## ⚙️ Workflow Architecture
1. **Trigger (Webhook / Zoho CRM):** Captures the event the moment a patient creates a meeting.
2. **Data Processing:** Extracts patient information, symptoms, and scheduling details.
3. **Storage:** Automatically appends the structured data into a **Google Sheets** log.
4. **Notifications:** 
   - Sends a confirmation email to the **Patient** (Gmail).
   - Forwards complete meeting details and patient notes to the **Clinic Team** (Telegram).

---

## 📂 Repository Contents
- `clinc automation.json`: The exported n8n workflow file ready to be imported and used.
