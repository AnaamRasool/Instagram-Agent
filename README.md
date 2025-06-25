# 🤖 Instagram DM AI Agent using n8n + Manychat

Automate your Instagram DMs with AI using **n8n** and **Manychat** — no coding required!  
In this project, you’ll learn how to set up an intelligent DM responder with simple automation tools.  

🔗 **Watch Full YouTube Tutorial:** [https://youtu.be/mO-ezWEvj5c]  

---

## 🛠️ Tools You’ll Need

- **n8n (Automation Platform)**  
  🔗 [Free Cloud Trial (15+ Days)](https://n8n.partnerlinks.io/lb2osz6r8xaq)

- **Manychat (Chat Automation Tool)**  
  🔗 [30 Days Free Trial](https://manychat.partnerlinks.io/qnp48zgcuds5-ogcg6e)

---

## ⚙️ Setup Instructions

### Step 1: Install and Set Up n8n
#### Option 1: Local Installation (Free)
1. Install **n8n** locally using Docker.
2. Use **Ngrok** to expose your local webhook to the internet (as shown in the video).

#### Option 2: Cloud Installation (Easier)
1. Use the hosted cloud version of n8n.  
   🔗 [Start Free Trial](https://n8n.partnerlinks.io/lb2osz6r8xaq)

---

### Step 2: Setup Manychat
1. Sign up on [Manychat](https://manychat.partnerlinks.io/qnp48zgcuds5-ogcg6e) using your **Instagram Business Page** and its connected email.
2. Grant necessary permissions for Instagram DM automation.

---

### Step 3: Import Workflows
1. **Import n8n JSON Workflow** (Provided in the setup link above).
2. **Import Manychat Automation Flow:**  
   🔗 [Import Flow](https://app.manychat.com/flowPlayerPage?share_hash=3126055_64d45267e6d4373d92fb9b4c011e9a4d85c1a697)

---

### Step 4: Configure Custom Fields in Manychat
- Create **custom fields** in Manychat exactly as used in the imported flow.
- Example fields: `userinput`, `reply` (or others used in your workflow).

---

### Step 5: Activate and Link Webhook
1. In n8n, **activate your workflow** and **copy the production webhook URL**.
2. Go to the **HTTP Request action** in your Manychat flow.
   - Paste the **webhook URL**.
   - Set the request **body** using the **custom fields** you created earlier.
3. Update the **Set Fields** action in Manychat to match your custom field names.

---

### Step 6: Customize for Your Business
- Edit **keywords** and trigger phrases to suit your audience.
- Now your Instagram DM AI Agent is ready to go live! 🎉

---

## 💬 Support

If you face any issues:
- Drop a **comment** on the video  
- Or send me a **DM on Instagram**

---

📢 Don’t forget to **Like**, **Comment**, and **Share** if this helped you!

#InstagramAutomation #n8n #Manychat #DMAutomation #AIAgent #NoCodeTools
