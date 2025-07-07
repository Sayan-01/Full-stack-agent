# 🚀 Full Stack AI Agent Framework for Builders

> ⚡ Empowering your apps with autonomous, full-stack AI agents.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Build](https://img.shields.io/github/actions/workflow/status/your-username/bold/ci.yml)
![Version](https://img.shields.io/github/package-json/v/your-username/bold)

---

## ✨ Overview

**Full Stack AI Agent Framework** built to simplify the development of autonomous, self-improving AI systems across the frontend, backend, and beyond.

Whether you're building SaaS tools, internal automations, or intelligent assistants—Full Stack AI Agent Framework gives you the solid foundation to ship fast.

---

## 🧠 Key Features

- 🔁 **Autonomous Agents** — Task-driven reasoning loop powered by OpenAI/GPT and LangChain.
- ⚙️ **Full Stack Ready** — Built with Next.js, Prisma, PostgreSQL, and TypeScript.
- 📊 **Real-Time UI** — Drag-and-drop visual pipelines and live agent logs.
- 🧩 **Plugin Support** — Easily connect APIs, databases, webhooks, and more.
- 🔐 **Auth & Access Control** — Integrated with Auth.js (Google, GitHub, Credentials).
- 📦 **Embeddable** — Integrate agents in your apps via REST or GraphQL API.

---

## 🏗️ Tech Stack

| Layer          | Technology                                   |
|----------------|----------------------------------------------|
| Frontend       | Next.js 14, React, Tailwind CSS, Shadcn UI   |
| Backend        | Node.js, TypeScript, LangChain               |
| Database       | PostgreSQL, Prisma ORM                       |
| Auth           | Auth.js (NextAuth)                           |
| Hosting        | Vercel / Docker / AWS                        |
| AI             | OpenAI / Claude / Gemini                     |

---

## 🖥️ Demo

> [🔗 Live Demo](https://bold-ai.vercel.app) — *Try the autonomous agent in action!*

![Bold Screenshot](https://your-screenshot-url.com/demo.png)

---

## Extra tools

- Inngest -> When we use AI for generate code, we have a risk of timeout / tab close /  connection loss so we can not get the result. 
  So that we use INNGEST for background jobs. The precess is -> 

  User click 'generate' -> send network request -> Start a background job which run in a separate environment independent of user session -> then it is notify when job is completed
  In every AI project we should use background jobs.