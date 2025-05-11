# 🚀 PerceptAI Radiology Demo

Welcome to the **PerceptAI Radiology Agent** 🌐 interactive demo — an all-in-one Jupyter notebook that sets up a full-stack AI application with just a few clicks. 

From downloading a password-protected source 🔐 to spinning up a public frontend & backend via ngrok 🚇 — this notebook does it all.

⚠️ A password is required to run this demo. Please get in touch if you haven’t received it.

Checkout [PerceptAI](https://victorious-meadow-054677210.6.azurestaticapps.net/), an AI agent that seamlessly integrates advanced vision applications with natural language.

✨ **No complex setup. Just run the cells and go live.**

## 🧰 Prerequisites

✅ Python 3.8+  
✅ Node.js (v18 or newer)  
✅ Works on local machines **or Google Colab**


## ⚙️ How to Use

1. **Clone this repo**

   git clone https://github.com/yourusername/perceptai-demo
   cd perceptai-demo


2. **Launch the notebook**

   * Open `PerceptAI_Demo_Final.ipynb` in Jupyter or Colab 📓

3. **Run all cells**

   * 📥 Downloads ZIP from Google Drive
   * 🔓 Extracts with your provided password
   * 📦 Installs Python & Node.js dependencies
   * 🌐 Boots backend + frontend
   * 🚇 Generates a public URL via ngrok


## 🗂️ Folder Structure

```bash
📦 perceptai-demo/
├── 📓 PerceptAI_Demo_Final.ipynb   → Main notebook
├── 📦 Demo_v2.zip                  → Protected source (auto-downloaded)
├── 🗂️ project/
│   ├── 🖥️ backend/                 → FastAPI backend
│   └── 🌐 frontend/                → React app

```

## 🌍 Public Access with Ngrok

A public URL is generated on-the-fly:
🔗 `https://<random-id>.ngrok.io`

Use it to access the live demo.

You can set your own `NGROK_AUTHTOKEN` in the `.env` file, or use the default provided.


## 🧪 Environment Setup (Optional)

Update (.env):

API_KEY=your_api_key
NGROK_AUTHTOKEN=your_ngrok_token
PORT=8000


## 🧠 Behind the Scenes

Here’s what happens step-by-step:

1. 🔒 Download & extract the secure ZIP
2. 🐍 Install FastAPI, `python-dotenv`, `pyngrok`, etc.
3. ⚛️ Set up frontend with `npm install`
4. 🧵 Spin up servers (React + FastAPI)
5. 🌍 Serve app via ngrok

---

## 🛠️ Troubleshooting

* Ngrok not found? Install it via pip: `pip install pyngrok`
* Port conflict? Try changing the backend `PORT` in `.env`
* Colab issue? Check runtime permissions or use local Jupyter

Made with ❤️ by developers who love AI, visuals, and automation.
