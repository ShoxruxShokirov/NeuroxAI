# NeuroxAI 🚀

**AI-powered study helper** - Explains school topics in simple English with step-by-step reasoning.

## ✨ Features

- 🎨 **Beautiful Perplexity-like Design** - Modern dark theme interface
- 📚 **Step-by-Step Explanations** - Learn at your own pace
- 🎯 **Simple English** - Complex topics made easy
- 💡 **Ask Anything** - Get explanations for any school topic
- 📱 **Responsive** - Works on all devices

## 🚀 Quick Start

### Windows (Easiest)
1. Double-click `run.bat`
2. Open http://127.0.0.1:8000/ in your browser

### Manual Setup

1. **Install dependencies:**
   ```bash
   python -m pip install -r requirements.txt
   ```

2. **Set OpenAI API Key:**
   ```bash
   # PowerShell
   $env:OPENAI_API_KEY="sk-your-key-here"
   
   # CMD
   set OPENAI_API_KEY=sk-your-key-here
   ```

3. **Run migrations:**
   ```bash
   python manage.py migrate
   ```

4. **Start server:**
   ```bash
   python manage.py runserver
   ```

5. **Open browser:**
   ```
   http://127.0.0.1:8000/
   ```

## 🔑 Get API Key

1. Visit https://platform.openai.com/api-keys
2. Sign up or log in
3. Create new API key
4. Copy and set as environment variable

## 📁 Project Structure

```
NeuroxAI/
├── neuroxai/          # Django project settings
├── core/              # Main app
│   ├── templates/     # HTML templates
│   └── views.py       # View logic
├── manage.py          # Django management
├── requirements.txt   # Dependencies
└── run.bat           # Quick start script
```

## 🎨 Pages

- **/** - Main search page (Perplexity-style)
- **/onboarding/** - Welcome page with features

## 🛠️ Tech Stack

- Django 4.2+
- OpenAI API
- Modern CSS (no frameworks)
- Responsive design

## 📝 Notes

- Make sure Python 3.8+ is installed
- OpenAI API key is required for AI features
- First run will create SQLite database

## 🐛 Troubleshooting

See `SETUP.md` for detailed troubleshooting guide.

---

Made with ❤️ for students who want to understand, not just copy.
