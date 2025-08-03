# 🤖 FiB - Fitness Buddy (AICTE-Edunet-IBM-Internship-Project)

**FiB** is an AI-powered virtual health and wellness coach built using **IBM Cloud** services. It provides intelligent, personalized fitness guidance, motivation, nutrition tips, and habit-building strategies through natural conversations. Accessible anytime, anywhere. 🚀🏋️‍♂️

# **SMART AI FITNESS COACH FOR DAILY WELLNESS**

## **📌 Overview**
This project is an AI-based **Fitness Assistant** designed to help individuals stay consistent with healthy routines. It uses **Watson Assistant**, **Granite LLM**, and IBM **Vector Knowledge Grounding** to provide a full AI stack experience on the cloud without requiring complex backend systems.

FiB is designed for:
- People with limited time or access to gyms
- Beginners who need simple fitness guidance
- Anyone looking for daily health motivation

---

## **🚀 Features**

### **🏋️ Personalized Fitness Coach**
- Answers fitness-related queries conversationally
- Recommends **home workouts** based on time & level
- Suggests **easy, healthy meals** with nutrition value

### **💬 Chatbot Powered by Watson**
- Built using **IBM Watson Assistant** with intents for:
  - `#workout`
  - `#motivation`
  - `#nutrition`
  - `#habit_building`

### **📘 Knowledge Grounding with Vectorized PDF**
- Integrated **2MB fitness knowledge base**
- Grounded with **IBM Granite** for enhanced conversational intelligence

### **📊 Uses IBM Jupyter Notebooks**
- For additional AI experimentation or fine-tuning logic

---

## **📄 How It Works**

1️⃣ **User interacts with FiB via Watson Assistant**  
2️⃣ **Asks a question**, like:
- "Give me a 15-minute workout"
- "What’s a good breakfast after a run?"
- "Motivate me to stay active"

3️⃣ **Watson Assistant responds**, grounded in vectorized PDF knowledge using IBM Granite

4️⃣ **User receives customized suggestions** or motivational responses

---

## **💻 Project Architecture**

| Layer             | Technology                      |
|-------------------|---------------------------------|
| AI Chat           | IBM Watson Assistant            |
| Vector Knowledge  | PDF embedded via vector index   |
| Model             | IBM Granite (Watsonx.ai)        |
| Backend Logic     | IBM Jupyter Notebook            |

---

## **📸 Screenshots**

### 💬 Project ID and Description
<img width="1904" height="869" alt="Image" src="https://github.com/user-attachments/assets/1eae61bc-876c-4fc8-9832-d4e97f63cc6d" />

### 💬 Associating Service
<img width="1572" height="489" alt="Image" src="https://github.com/user-attachments/assets/9cf065d1-29b5-46bb-a25c-2c17b198de2e" />

### 💬 Building AI Assistant
<img width="1920" height="858" alt="Image" src="https://github.com/user-attachments/assets/600048c1-7137-41a8-be78-9ff93be725da" />

Setup AI Agent
<img width="1920" height="867" alt="Image" src="https://github.com/user-attachments/assets/57c60a58-7417-4eef-b8a1-2497fc47e6fa" />

Agent Instructions
<img width="1746" height="650" alt="Image" src="https://github.com/user-attachments/assets/d457e022-796f-4347-bc28-6040b98b33bc" />

Common Instructions
<img width="1729" height="651" alt="Image" src="https://github.com/user-attachments/assets/5193177b-6fb3-4ed2-b441-c8bb83507922" />

Vector Knowledge
<img width="1388" height="776" alt="Image" src="https://github.com/user-attachments/assets/881d1a2f-a0a7-40a8-8fab-206bc5f2ff12" />

Tools
<img width="1782" height="537" alt="Image" src="https://github.com/user-attachments/assets/64fd033b-6cb5-421f-85b8-bf17f67f237f" />

<img width="895" height="648" alt="Image" src="https://github.com/user-attachments/assets/e0adaa85-dee6-4657-b6a8-5ea2cbed9752" />

Preview Before Upload
<img width="915" height="776" alt="Image" src="https://github.com/user-attachments/assets/71cb8a24-e2eb-4adc-8cca-4fb22bae8e56" />

<img width="906" height="765" alt="Image" src="https://github.com/user-attachments/assets/ac43ea92-7551-4f0d-8fa0-e3cf39e78c7d" />

### 💬 Saving The AI Agent
Saving the AI Agent
<img width="1786" height="775" alt="Image" src="https://github.com/user-attachments/assets/542e8a96-d6fb-461a-b255-a914e4e0cd43" />

Saving the AI Agent Code
<img width="1781" height="776" alt="Image" src="https://github.com/user-attachments/assets/fe594f1f-fff5-4966-ae49-d9ce332590a1" />

### 📄 Creating Deployment Space
Deployment
<img width="1888" height="792" alt="Image" src="https://github.com/user-attachments/assets/8e17d690-0401-4195-a714-8284a56e61cd" />

<img width="1892" height="798" alt="Image" src="https://github.com/user-attachments/assets/6b8e98a4-407d-450a-b642-4d51656f993a" />

### 🧠 Deploying
Deploy
<img width="1811" height="797" alt="Image" src="https://github.com/user-attachments/assets/efb0c3e7-4010-4f58-b161-073fc91db649" />

<img width="1915" height="874" alt="Image" src="https://github.com/user-attachments/assets/5c3e66d5-a6b6-4ec9-bc8b-87b840a92687" />

<img width="1902" height="283" alt="Image" src="https://github.com/user-attachments/assets/36ef7fa9-dd6a-4ef4-a511-376073172508" />

<img width="1909" height="768" alt="Image" src="https://github.com/user-attachments/assets/8e74cbda-8c04-4053-a95c-37dc517aa6c4" />

### 🚀 Overvie After Deployment
Overview
<img width="1890" height="781" alt="Image" src="https://github.com/user-attachments/assets/f2d6331e-f575-44fb-aa7d-f5fa7f674442" />

### 💻 Agent Preview After Deployment
Preview
<img width="1911" height="796" alt="Image" src="https://github.com/user-attachments/assets/baff0a4f-acab-48f6-9241-c70f98b0bad5" />
---

## **🛠️ Setup Instructions**

### 🔴 Requirements
- IBM Cloud Account (Lite plan)
- IBM Watson Agenstic Lab
- Watsonx or IBM Granite model access
- Jupyter Notebook via Watson Studio
  
### 🧪 Usage Workflow
1. Upload your **vector PDF** under Knowledge → Documents
2. Set up AI Agent
3. Add integration with IBM Granite (Watsonx.ai)
4. Interact via Try It panel or external web deployment (future scope)

---

## **📦 Project Structure**
├── Project ScreenShots/ # Screenshots for README
├── FiB Knowledge Base.pdf # Vectorized knowledge document
├── FiB.ipynb/ # logic
├── Project PPT.ppt/ 
├── README.md # This file

---

## **📝 Contributing**
Suggestions and forks are welcome! Want to add calorie tracking, goal monitoring, or calendar scheduling? Feel free to contribute!

---

## **⚖️ License**
This project is licensed under the **MIT License** – free to use and modify.

---

## **🤝 Connect**
Made with 💙 by **Vivek Kumar Yadav**  
📫 Email: vivekkumaryadav0303@gmail.com  
🔗 LinkedIn: www.linkedin.com/in/vivek-k-yadav-3a9146136

---

🔥 Powered by IBM Cloud, Built for Everyday Wellness! 🔥
