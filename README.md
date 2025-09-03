# 🤖 Telegram AI Assistant with n8n & GPT-4

A **smart, memory-enabled Telegram chatbot** built using **n8n** and **OpenAI GPT-4.1-mini**.  
Designed to answer questions, perform calculations, track conversation context, and respond in a friendly, professional, and organized manner.

---

## 🌟 Features

- **Intelligent Responses:** Powered by GPT-4.1-mini for clear, accurate, and complete answers.  
- **Memory Enabled:** Session-based memory keeps track of conversation context for more natural interactions.  
- **Interactive Tools:**  
  - **Calculator:** Solve math problems instantly  
  - **Date & Time:** Retrieve current date, time, or convert time zones  
- **Telegram Integration:** Automatically responds to user messages via Telegram API.  
- **Customizable Prompts:** Easily adjust system instructions to define your bot’s personality or behavior.  

---

## ⚙️ How It Works

1. **Telegram Trigger:** Captures messages sent by users.  
2. **AI Agent:** Processes user input using GPT-4.1-mini.  
3. **Tools & Memory:** Optional tools (calculator, date/time) and session memory enhance responses.  
4. **Response Delivery:** Sends the AI-generated reply back to the user via Telegram.  

---

## 🛠️ Tech Stack

- **n8n:** Low-code automation workflow tool  
- **OpenAI GPT-4.1-mini:** Natural language processing & response generation  
- **Telegram Bot API:** Platform integration for real-time chat  
- **Memory Buffer:** Keeps conversation context for better interactions  
- **Optional Tools:** Calculator & Date/Time for interactive capabilities  

---

## 🚀 Setup & Getting Started

Follow these steps to get your **Telegram AI Assistant** running quickly:

1. **Create an n8n account**  
   - Go to [n8n.cloud](https://n8n.io/cloud) and sign up for a free or paid account.  
   - n8n is a low-code workflow automation tool that will run your AI Telegram bot.  

2. **Import the workflow**  
   - Download the workflow JSON from this repository.  
   - Log in to n8n → go to **Workflows → Import** → **Upload JSON file**.  
   - This will create the bot workflow automatically.  

3. **Connect your credentials**  
   - **Telegram Bot:** Create a Telegram bot via [BotFather](https://t.me/BotFather) and copy the token.  
   - **OpenAI API Key:** Get your API key from [OpenAI](https://platform.openai.com/).  
   - In n8n, click on the Telegram node → set your Telegram API credentials.  
   - Click on the OpenAI node → add your OpenAI API key.  

4. **Activate the workflow**  
   - Switch the workflow **ON** in n8n.  
   - Your bot will now listen for messages and respond automatically.  

5. **Optional tools**  
   - **Calculator & Date/Time:** Already included in the workflow. Just enable the nodes if needed.  

**Tip:** You don’t need to write any code! Just import the JSON, connect your credentials, and turn on the workflow.  

---

## 💡 Example Usage

- **User:** "What’s the capital of France?"  
- **Bot:** "The capital of France is **Paris**. It’s known for landmarks like the Eiffel Tower and the Louvre."  

- **User:** "What is 15 × 23?"  
- **Bot:** "15 × 23 = **345**."  

- **User:** "What time is it in Tokyo?"  
- **Bot:** "The current time in Tokyo is **14:37 JST**."  

---

## 🔧 Customization

You can personalize your bot’s behavior by editing the **AI Agent system message** in the n8n workflow. For example:  

- Make it **more friendly**  
- Make it **professional for work or study**  
- Enable or disable **tools** like calculator or date/time  

---

## ⚡ Benefits

- Quick setup for a powerful AI Telegram assistant  
- Flexible and memory-enabled for natural conversations  
- Expandable with new tools or integrations  
- Ideal for personal use, study help, or experimentation  

---

## 📜 License

This project is **MIT Licensed** – feel free to use, modify, and distribute.  

---

**Enjoy your AI Telegram assistant! 🚀**
