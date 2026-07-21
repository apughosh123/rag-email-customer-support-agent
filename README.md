# 🤖 RAG-Based Email Customer Support Agent

An AI-powered **RAG (Retrieval-Augmented Generation) Email Customer Support Agent** built with **n8n**, **OpenAI**, **Supabase Vector Store**, and **Gmail API**.

This workflow automatically receives customer emails, retrieves relevant information from a company knowledge base, generates accurate AI-powered responses, and replies to customers automatically.

---

## 🚀 Features

- 📧 Automatically receives customer emails
- 🤖 AI-powered email response generation
- 📚 Retrieval-Augmented Generation (RAG)
- 🔍 Semantic search using Supabase Vector Store
- 🧠 Conversation memory support
- ✉️ Automatic Gmail reply
- ✅ Marks processed emails as read
- 🔒 Prevents hallucination by answering only from the knowledge base
- 👨‍💼 Supports Human-in-the-Loop (HITL) approval (Optional)

---

## 🛠️ Tech Stack

- **n8n**
- **OpenAI GPT**
- **OpenAI Embeddings**
- **Supabase Vector Store**
- **Gmail API**
- **JavaScript**

---

# 📌 Workflow

```text
Customer Email
      │
      ▼
 Gmail Trigger
      │
      ▼
Extract Email Content
      │
      ▼
AI Agent
      │
      ▼
Vector Store Tool
      │
      ▼
Supabase Vector Store
      │
      ▼
Retrieve Knowledge
      │
      ▼
Generate AI Reply
      │
      ▼
Reply to Gmail
      │
      ▼
Mark Email as Read
```

---

## 🧠 RAG Architecture

1. Customer sends an email.
2. Gmail Trigger detects the unread email.
3. Email subject and body are extracted.
4. AI Agent receives the customer query.
5. AI searches the Supabase Vector Store.
6. Relevant company knowledge is retrieved.
7. OpenAI generates an accurate response using retrieved context.
8. Gmail automatically sends the reply.
9. Email is marked as read.

---

## 📂 Project Files

```
📁 Project
│
├── RAG Email Customer Support Agent.json
├── Assignment_Report.pdf
├── Bonus_Task_HITL_RAG_Email_Customer_Support_Agent.pdf
├── workflow-demo.mp4
├── workflow.png
├── execution.png
└── README.md
```

---

## 📸 Screenshots

### Workflow

> Add your workflow screenshot here.

### Successful Execution

> Add successful execution screenshot here.

### Gmail Auto Reply

> Add Gmail reply screenshot here.

---

## 🎥 Demo Video

Watch the workflow execution video included in this repository.

---

## ⭐ Human-in-the-Loop (Bonus)

The workflow can be extended by adding a Human Approval step before sending the final email.

Flow:

```
Customer Email
      │
      ▼
AI Agent (RAG)
      │
      ▼
Draft Reply
      │
      ▼
Human Review
      │
 ┌────┴────┐
 │         │
Approve  Reject
 │         │
 ▼         ▼
Send     Edit /
Email   Regenerate
```

---

## 💡 Real-World Use Cases

- E-commerce Customer Support
- SaaS Product Support
- Educational Platforms
- Healthcare FAQs
- Banking Customer Support
- Internal Company Helpdesk

---

## 📈 Future Improvements

- Human Approval (HITL)
- Multi-language Support
- Slack Integration
- Confidence Score
- Ticketing System Integration
- CRM Integration
- Analytics Dashboard

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Apu Ghosh**

AI Automation Specialist | Front-End Developer

- n8n Workflow Automation
- AI Agents
- RAG Systems
- OpenAI API
- API Integration
- Supabase
