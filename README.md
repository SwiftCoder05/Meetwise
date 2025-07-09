# 📝 MeetWise

## 📌 Description

This project is a powerful, end-to-end tool that leverages **OpenAI's Whisper ASR** and **GPT-4** models to automate the process of generating structured **meeting minutes** from audio recordings. It provides:

- Accurate **transcriptions** using Whisper
- **Abstract summaries** of the meeting
- Extraction of **key points** and **action items**
- **Sentiment analysis** of the discussion
- Output as a clean **Word document (.docx)**

This is ideal for teams, professionals, and organizations aiming to save time and capture critical information from voice meetings or discussions.

---

## 🚀 Features

- 🎙️ **Speech-to-text transcription** using OpenAI Whisper
- 🧠 **Summarization**, **Key Point Extraction**, and **Sentiment Analysis** using GPT-3.5 / GPT-4
- 📄 **DOCX export** of the generated minutes
- ⚙️ Easily extensible for more advanced formatting or integrations

---

## 🛠️ Requirements

- Python 3.11.5 or above
- OpenAI API key (get it from [platform.openai.com](https://platform.openai.com/account/api-keys))

### 📦 Install Dependencies

Create a virtual environment and install the required packages:

```bash
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

pip install openai==1.30.1
pip install python-docx
pip install python-dotenv



## Refereces
- [OpenAI API](https://beta.openai.com/)


