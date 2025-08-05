# 🤖 AI Agent with Input and Output Guardrails

This project demonstrates an AI agent built using the **OpenAI Agent SDK** with integrated **input and output guardrails**. It ensures that the user's input is safe and aligned with the agent's purpose, and the output is ethical, accurate, and secure.


## 🚀 Features

- ✅ Input Guardrails to block unethical or off-topic requests
- 🛡️ Output Guardrails to prevent hallucinations and unsafe responses
- 🔐 Environment-based API key handling using `.env`
- ⚙️ Configurable with Gemini 2.0 Flash model
- 🔄 Fully asynchronous design using `asyncio`



## 📦 Installation

### 1. Clone the Repository


git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
2. Set Up Virtual Environment (Optional)
bash
Copy
Edit
python -m venv venv
venv\Scripts\activate  # for Windows
# OR
source venv/bin/activate  # for Linux/macOS


3. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt



. Create .env File
Create a file named .env in the root folder and add your Gemini API key:

ini
Copy
Edit
GEMINI_API_KEY=your_api_key_here
❗ Don't share this key publicly. Always add .env to .gitignore.

 How It Works
Input Guardrail
Blocks:

Homework or academic work

Offensive or manipulative language

Illegal or unethical content

Irrelevant/off-topic prompts

Output Guardrail
Blocks or flags:

Unsafe, biased, or hallucinated responses

Internal logic leakage

Misleading or inappropriate answers

💡 Example
bash
Copy
Edit
Input Guardrail:  is_input_invalid=False reasoning='The input is safe and relevant.'
Output Guardrail:  is_output_invalid=False reasoning='The response is factual and appropriate.'
Final Answer:  Agentic AI is a framework for building autonomous agents using tools, memory, and LLMs...
📁 File Structure
bash
Copy
Edit
main.py                # Main runner file
.env                   # API key file (should be in .gitignore)
requirements.txt       # Python dependencies
🔐 Environment Variables
Variable	Description
GEMINI_API_KEY	Your Gemini API key

❗ Important Notes
Make sure .env is added to .gitignore

Never expose API keys publicly






👤 Author
Muhammad Taha
GitHub: @tahaawan123

📄 License
This project is open-source and available under the MIT License.


