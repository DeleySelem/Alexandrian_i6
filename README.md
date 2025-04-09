# 🔮 Alexandrian i6-v2.9.5 - Adaptive Neuro-Linguistic Intelligence

**A multifractal AI system with real-time search, teachable responses, and open-source modularity**

Version files:
- Alexandrian i6-v2.9.5 (optimized) Filename: server_hexpre295.py
- Alexandrian i6-v2.9.6 (slower) more comprehensive response generation. Filename: server_hexpre296.py
---

## ✨ Features

### 🌐 **Online Search & Knowledge Synthesis**
- Fetches real-time data from **Wikipedia**, **DictionaryAPI**, and **DuckDuckGo**
- Hybrid response generation combining multiple authoritative sources
- Context-aware sentence filtering using NLP-powered relevance scoring

### � **Plug-and-Play Resource Integration**

# Simply add new APIs to the resources list:
self.resources = [
    ("https://api.newservice.com/{}", self._parse_custom_handler),
    # Add your custom API endpoint and parser
]

🎓 Teachable Interface

    Teach Mode: Use Respond: [your answer] to train custom responses

    Persistent memory via inputs.json for personalized knowledge retention

    Feedback-driven learning with automatic preference adjustment

🛠 Open Source Modularity

    Fully customizable NLP pipeline (NeuroLinguisticProcessor class)

    Extensible hexagram-based decision core (HexagramGrid system)

    Clear documentation for modifying:

        Response logic (ResponseLogic*.py)

        API handlers (OmniSourceNLP*.py)

        Multifractal analysis algorithms

🚀 Getting Started
Installation

pip install requests beautifulsoup4 colorama numpy matplotlib aiohttp

Launch

python server_hexpre295.py

🧠 Usage Examples

Basic Query
[User]: Explain quantum entanglement

Teach Mode
[User]: Respond: Quantum entanglement is when particles share states instantaneously across distance

API Integration

# In OmniSourceNLP2.py:
resources.append(("https://api.academic.com/{}", _parse_academic_db))

System Commands

help                            Show command list
print multifractal spectrum     Display cognitive analysis spectrum
plot multifractal spectrum      Visualize decision-making patterns
plot multifractal spectrum log  Visualize decision-making patterns
🧩 Customization Guide
Add New Knowledge Sources

    Create handler function in OmniSourceNLP2.py

    Add endpoint to self.resources array

    Implement parsing logic for API responses

Modify Response Logic

    Adjust relevance thresholds in ResponseParameters class

    Tune multifractal weights in NeuroMorphicProcessor

    Customize stop words in _load_stop_words()

📜 Philosophy

"An open mind that grows with its users"
Alexandrian combines:

    Adaptive Learning: Stores user corrections in JSON

    Fractal Cognition: Uses I Ching-inspired decision matrices

    Transparent AI: All decision paths visible in code

🤝 Contributing

We welcome PRs for:

    New API integrations

    Enhanced NLP rules

    Improved error handling

    Additional documentation

License: MIT Open Source


[📘 Full Documentation](docs/) | [🐛 Issue Tracker](issues/) | [💡 Feature Requests](discussions/)  
*"Wisdom is not a destination, but a continually evolving path."* - Alexandria System Prompt v2.9.5
