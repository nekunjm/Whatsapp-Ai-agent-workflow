# WhatsApp AI Agent Workflow 🚀

This project is an **AI-powered WhatsApp automation system** built using [n8n](https://n8n.io).

It allows businesses to:
- ✅ Send WhatsApp templates to customers automatically  
- ✅ Let customers reply with a **"Chat with Us"** button  
- ✅ Provide AI-powered replies using product/policy data  
- ✅ Maintain conversation history per customer  

---

## 📌 Workflow Overview

**Flow:**
1. WhatsApp Message Trigger (incoming/outgoing)  
2. Text Classifier (decides: send template OR AI reply)  
3. Template Sender (pulls data from Google Sheets)  
4. AI Agent (OpenAI + company product/policy context)  
5. Conversation History (stored per customer in n8n Data Store)  
6. Final Reply to Customer  

---

## ⚙️ Setup Guide
1. **WhatsApp Templates**  
   - Create template with only 1 variable and 1 Quick Reply button: *"Chat with Us"*  
   - No footer allowed.  

2. **Customer Database (Google Sheets)**  
   - Must include `Name` and `Number` columns.  

3. **Template Database (Google Sheets)**  
   - Columns: `General Name`, `Templ<img width="9402" height="2982" alt="Whatsapp workflow detailed" src="https://github.com/user-attachments/assets/cc994636-074a-4091-a4f0-35591f5e0757" />
ate Name`, `Media Type`, `Media ID`  

4. **Media Upload**  
   - Upload file to Google Drive  
   - Copy file ID from link → paste into `Media ID` column.  

---

## 💡 Example Use Case
- A retail store sends out promotions via WhatsApp templates.  
- Customers click **Chat with Us** → AI answers queries instantly.  
- Reduces manual customer support work by 70%.  

---

## 🚀 Hire Me
This is a client project I delivered.  
If you want me to build something similar for your business:  
- Email: nekunjm@gmail.com 
- LinkedIn: www.linkedin.com/in/nekunj-malushte-387992324 
- WhatsApp: +91 8879897814

