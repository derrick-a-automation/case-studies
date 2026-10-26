# Automation Case Studies

Write-ups of automation work I delivered in production environments. Each one follows **Situation → Task → Action → Result** and ends with lessons learned. Figures marked as estimates are estimates; everything else is a measured count.

These describe real employer work, so they contain no production code or environment details. For hands-on builds with code, see my lab repositories, such as [n8n Onboarding Automation](https://github.com/derrick-a-automation/n8n-onboarding-automation).

---

## Case studies

### 1. Zero-Touch Identity: Password and Account Expiration Automation
Scheduled PowerShell automation against on-premises Active Directory (synced to Entra ID) for ~2,600 users. Sent 9,000+ proactive notifications to users and managers, covering an estimated 380 hours a year of manual work and avoiding an estimated up to 1,800 service desk tickets.
**[Open case study](zero-touch-identity/)**

---

### 2. Power Query Ingestion Framework *(in preparation)*
Replaced a manual, inherited finance data-prep process with a standardized Power Query ETL workflow pulling from credentialed SharePoint Online sources, cutting recurring prep time by an estimated 70–90%.

---

### 3. IT Intake Modernization *(in preparation)*
Design and roadmap for an AI-enhanced IT intake model: guiding users to the right request type, capturing the context technicians need, and routing work correctly the first time.
