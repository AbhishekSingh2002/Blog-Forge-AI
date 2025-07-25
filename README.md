# BlogForge AI

## Overview

BlogForge AI is a multi-agent, AI-powered application built with Streamlit that automates the generation of professional, SEO-optimized HR blog posts. It enables HR professionals and content creators to produce high-quality content efficiently using modular AI agents.

## 🚀 Features

- 🤖 Multi-agent architecture: Research, Planning, Content Generation, SEO, and Review agents
- ✍️ AI-generated, long-form HR blog content
- 🎯 Customizable writing styles and word count
- 🔍 SEO keyword optimization
- 🧠 Built using Mistral AI and LangChain

## 📁 Project Structure

├── agents/ # AI agents for specific tasks
│ ├── research_agent.py
│ ├── planning_agent.py
│ ├── content_agent.py
│ ├── seo_agent.py
│ └── review_agent.py
├── core/ # Core orchestration logic
│ └── blog_generator.py
├── frontend/ # Streamlit UI components
│ ├── pages/
│ │ ├── home.py
│ │ └── generate.py
│ └── components/
│ └── sidebar.py
├── utils/ # LLM config and prompt templates
├── samples/ # Generated blog post examples
├── app.py # Streamlit entry point
├── requirements.txt # Python dependencies
└── README.md

bash
Copy
Edit

## ⚙️ Installation

**Prerequisites:**  
- Python 3.8+
- pip

**Steps:**

```bash
git clone https://github.com/yourusername/hr-blog-generator.git
cd hr-blog-generator

python -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate

pip install -r requirements.txt
▶️ Running the App
bash
Copy
Edit
streamlit run app.py
🛠 Customization
Writing Style: Professional | Casual | Technical

Content Length: 500–3000 words adjustable via UI

📦 Dependencies
Streamlit

LangChain

Mistral AI

DuckDuckGo Search

dotenv

🤝 Contributing
Fork this repo

Create your feature branch (git checkout -b feature/YourFeature)

Commit your changes (git commit -m 'Add feature')

Push to the branch (git push origin feature/YourFeature)

Open a Pull Request

📝 License
This project is licensed under the MIT License. See LICENSE for details.

yaml
Copy
Edit

---

Let me know if you want this exported as a file or published to GitHub with tweaks.
