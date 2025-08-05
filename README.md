# BabyGenieAI
This project levearge the use of LLM to help generate baby name based on parent's name and pronounciation of generated name and origin.
👶 BabyGenieAI (AI Baby Name Generator)

A fun and intelligent baby name generator powered by **Azure OpenAI** that suggests beautiful, meaningful names based on:
- **Child’s gender** (Boy, Girl, Twins)
- **Parents’ names**
- **Optional voice output** in English, French, or Spanish
- **Twin names** with gender selection
- **Name origins** (African, Greek, Latin, etc.)

## 🔮 Features

- 🎯 Suggests names based on parental input
- 👶 Handles twins: Boy-Boy, Girl-Girl, or Boy-Girl combinations
- 💬 Includes poetic or symbolic meanings for each name
- 🌍 Includes name **origin** (e.g., African, Latin, Greek)
- 🔊 Voice pronunciation using local TTS (pyttsx3)
- 🌐 Supports multiple languages: English 🇬🇧, French 🇫🇷, Spanish 🇪🇸

---

## 🛠️ Tech Stack

- 🧠 **Azure OpenAI** (GPT-4)
- 🌐 **Streamlit** for web UI
- 🗣️ **pyttsx3** for offline Text-to-Speech
- 🧠 Python backend

---

## 🚀 Getting Started

### 1. Clone the Repo
```bash
  git clone https://github.com/your-username/ai-baby-name-generator.git
  cd ai-baby-name-generator

2. Install Dependencies
    pip install -r requirements.txt

3. Configure API Keys
    Create a .env file with:
    AZURE_OPENAI_API_KEY=your_key_here
    AZURE_OPENAI_API_BASE=your_endpoint
    AZURE_OPENAI_API_VERSION=your_version
    AZURE_OPENAI_DEPLOYMENT=your_deployment_name

4. Run the App
    streamlit run app.py

🤔 Future Features
    🎯 Filtering by name origin (African, Hebrew, Latin, etc.)
    💾 Save favorite names
    🧠 Integration with baby horoscope
    🧪 GPT-4 fine-tuned dataset for culturally specific names

🙌 Contributors
    👨‍💻 Jeremiah K Kamara — Developer & Visionary
    🤖 Powered by Azure OpenAI & Streamlit

📄 License  
    MIT License. Feel free to use, fork, and modify.
