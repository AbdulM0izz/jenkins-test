#  Jenkins Webhook Test via Ngrok

This project demonstrates how to test a Jenkins job trigger using GitHub webhooks and Ngrok for local development.

---

##  Requirements

- Jenkins running locally on port `8080`
- [Ngrok](https://ngrok.com/) installed
- A GitHub repository
- A Jenkins job configured for GitHub webhook triggers

---

##  Setup Instructions

### 1. Start Jenkins Locally
Ensure Jenkins is running on your local machine at `http://localhost:8080`

### 2. Expose Jenkins via Ngrok
Open a terminal and run:
```bash
ngrok http 8080
