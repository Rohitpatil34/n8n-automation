# 🚀 AI Automation Workflows using n8n

This repository contains two powerful AI-driven automation workflows built with n8n:

1. 🏢 Auto Content Creation (Real Estate Listings)  
2. 🤖 Sales Copilot AI Agent  

These workflows demonstrate how to integrate APIs, LLMs, databases, and automation tools to build real-world AI systems.

---

# 📂 Workflows Included

## 1️⃣ Auto Content Creation Workflow  

### 🔍 Overview
This workflow automatically generates SEO-optimized coworking space listings using Google Places API and AI.

---

### ⚙️ How It Works

1. ⏰ **Schedule Trigger**
   - Runs daily at 9 AM  

2. 🌐 **Google Places API**
   - Fetches coworking spaces in Mumbai  

3. 🧠 **Data Processing**
   - Extracts:
     - Name  
     - Location  
     - Rating  
     - Image  

4. ✍️ **AI Content Generation**
   - Uses LLM (Groq) to generate:
     - Description (100–150 words)  
     - SEO-friendly listing  

5. 🧹 **JSON Cleaning**
   - Ensures valid structured output  

6. 🗄️ **MongoDB Storage**
   - Saves:
     - Title  
     - Description  
     - Location  
     - Slug  

---

### ✨ Features

- Automated daily content generation  
- SEO-optimized listings  
- AI-powered text generation  
- Real-time data from Google Maps  
- Database integration (MongoDB)  

---

### 🛠️ Tech Stack

- n8n  
- Google Places API  
- Groq LLM  
- MongoDB  

---

### ⚠️ Setup Instructions

1. Add your Google Places API Key  
2. Configure Groq API credentials  
3. Connect MongoDB  
4. Import workflow JSON into n8n  
5. Activate the workflow  

---

## 2️⃣ Sales Copilot AI Agent  

### 🔍 Overview
An AI-powered sales assistant that analyzes sales calls and suggests next actions automatically.

---

### ⚙️ Workflow Breakdown

1. ▶️ **Manual Trigger**
   - Starts workflow manually  

2. 📝 **Input Data**
   - Transcript  
   - Product  
   - Deal stage  
   - Customer & rep info  

3. 🧠 **AI Analysis**
   - Generates:
     - Call summary  
     - Sentiment  
     - Objections  
     - Buying intent score  
     - Next actions  

4. 🔀 **Decision Logic (IF Node)**
   - If:
     - Sentiment = Negative OR  
     - Intent score ≤ 7  

5. 📚 **Vector Search (Supabase)**
   - Retrieves objection-handling strategies  

6. 🤖 **AI Response Generator**
   - Creates:
     - Live response  
     - Talking points  
     - Reassurance message  

7. 📧 **Email Automation**
   - Sends personalized follow-up email  

---

### ✨ Features

- AI-powered sales call analysis  
- Sentiment detection  
- Objection handling using vector search  
- Smart decision-making logic  
- Automated follow-up emails  

---

### 🛠️ Tech Stack

- n8n  
- Groq (LLM)  
- Supabase Vector DB  
- Cohere Embeddings  
- SMTP Email  

---

### ⚠️ Setup Instructions

1. Add Groq API Key  
2. Configure Supabase Vector DB  
3. Add Cohere API Key  
4. Setup SMTP Email credentials  
5. Import workflow into n8n  
6. Run manually or integrate with CRM  

---

# 📸 Use Cases

- 🏢 Real estate listing automation  
- 📈 Sales team productivity tools  
- 🤖 AI-powered CRM automation  
- 📊 Lead qualification systems  

---

# 🚀 Future Improvements

- Add multi-language support  
- Integrate with CRM (HubSpot, Salesforce)  
- Add dashboard for analytics  
- Real-time webhook triggers  

---

# 👨‍💻 Author

**Rohit Patil**  
AI/ML & Full Stack Developer  

---

# ⭐ If You Like This Project

Give it a ⭐ on GitHub and feel free to contribute!
