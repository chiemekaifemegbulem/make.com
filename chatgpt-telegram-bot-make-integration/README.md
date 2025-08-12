# ChatGPT-Powered Telegram Bot for Instant Topic-Specific Replies
![Diagram](./Assets/chatgpt-telegram-bot-make-integration)
This project is an **AI-powered Telegram bot** built using **Make.com** and **OpenAI’s GPT-3.5-Turbo**.  
It automatically responds to messages in a Telegram channel with accurate, topic-focused replies — while politely declining questions outside the defined subject.

---

## 📌 Features
- **Real-time Monitoring**: Detects new messages from your Telegram channel instantly.
- **AI-Powered Responses**: Uses ChatGPT to generate relevant, detailed answers for your chosen topic.
- **Topic Filtering**: Ignores off-topic queries and replies with a predefined polite message.
- **Hands-Free Operation**: Runs 24/7 without human intervention.

---

## ⚙️ How It Works
1. **Telegram Watch Updates** – Listens for new messages in the channel.
2. **OpenAI GPT-3.5-Turbo** – Processes the message:
   - If related to the chosen topic → Generates a detailed, accurate answer.
   - If unrelated → Sends a polite “I only answer questions about {topic}” message.
3. **Telegram Send Reply Message** – Posts the AI-generated response back to the same chat automatically.

---

## 🛠 Tech Stack
- **Make.com** – Automation workflow builder
- **Telegram API** – Bot integration
- **OpenAI GPT-3.5-Turbo** – Natural language processing

---

## 📈 Benefits
- 24/7 instant replies
- Consistent, topic-specific communication
- Saves time for community managers or support staff
- Keeps discussions focused and relevant

---

## 🚀 Getting Started
1. Create a Telegram bot using [BotFather](https://core.telegram.org/bots#botfather).
2. Set up an **OpenAI API key**.
3. Import the provided Make.com scenario.
4. Configure your `{topic}` in the scenario.
5. Activate the scenario and watch your bot handle replies automatically.

---

## 📢 Hire Me
If you’d like a custom AI-powered bot for your business,  
I offer **Make.com automation** and **AI chatbot development** services.  
📩 [Hire me on Upwork](https://www.upwork.com/freelancers/~012c4b95e0c5eb81a8)
