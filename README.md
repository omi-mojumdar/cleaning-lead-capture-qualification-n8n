# 🧹 Cleaning Lead Capture & Qualification

An automated cleaning business lead capture system built with n8n that receives enquiries from a Tally form, qualifies leads by validating fields, ZIP code service area, and duplicates, saves them to a Google Sheets CRM, and instantly notifies the owner via Gmail.

## 🚀 Demo

> [▶️ Watch Demo Video](https://drive.google.com/file/d/1Vq2Tq8Lf7BbdsptTT1e4Lzb3cP46Kstp/view?usp=drive_link)

## 🔧 Tech Stack

- **n8n** - Workflow automation platform
- **Tally** - For lead capture form (webhook trigger)
- **Google Sheets** - For CRM and qualified lead data storage
- **Gmail** - For instant owner email notifications

## ⚙️ How It Works

1. Customer submits a Tally form with their cleaning service enquiry
2. n8n validates all required fields (name, email, phone, ZIP, service type)
3. ZIP code is checked against the supported service area list
4. Duplicate check searches existing CRM for a matching email or phone
5. Qualified NEW leads are saved to Google Sheets CRM automatically
6. Owner receives an instant Gmail alert with the full lead details and status

## 📸 Screenshots

> Check the `/Screenshots-Image` folder for workflow and system screenshots

## 🔧 Workflow

The complete n8n workflow is available in `Workflow.json`

## 👤 Author

**Omi Mojumdar** - AI Automation Developer

- GitHub: [@omi-mojumdar](https://github.com/omi-mojumdar)
