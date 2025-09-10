# 🎥 PADIK AI

Ever wished you could **chat with a YouTube video** instead of scrolling through it for answers?  
This project makes that possible! 🚀

With just a YouTube link, this notebook:

- 📜 Extracts the transcript  
- ✨ Restores proper punctuation using `DeepMultilingualPunctuation`  
- 🤖 Lets you ask questions directly using the **Groq API** powered by **LLaMA 3.1-8B**

---

## ⚡ Features

- 🔗 Input a YouTube video link  
- 📜 Automatically extract transcript  
- ✍️ Clean up text with punctuation restoration  
- 💬 Interactive Q&A with Groq's LLaMA 3.1-8B  
- 🌍 Works with multilingual transcripts (where available)  

---

## 🛠️ Tech Stack

- **Python**
- [`youtube-transcript-api`](https://pypi.org/project/youtube-transcript-api/) – Fetches transcripts  
- [`deepmultilingualpunctuation`](https://pypi.org/project/deepmultilingualpunctuation/) – Restores punctuation  
- **Groq API** – Powers the conversational Q&A using LLaMA 3.1-8B  

---

## 📖 How It Works

1. **Paste** a YouTube video link in the notebook.  
2. The script **extracts the transcript** using `youtube-transcript-api`.  
3. The transcript is **processed with `PunctuationModel`** to improve readability.  
4. The **cleaned transcript** is passed to **Groq LLM** to answer your custom queries.  

---

## 🚀 Future Plans

- 🌐 Build a **web app** version (still learning web dev 😅)  
- 📊 Add **video summarization** and **keyword extraction**  
- 🔎 Support **multiple videos for cross-referencing**  

---

## ▶️ Getting Started

1. **Clone the repository and install dependencies**:

    ```bash
    git clone https://github.com/your-username/your-repo.git
    cd your-repo
    pip install -r requirements.txt
    ```

2. **Run the Jupyter Notebook**:

    ```bash
    jupyter notebook
    ```

---

## 📸 Example Output

**Input:** YouTube link  
**Transcript:** Extracted and punctuated  
**User can ask:**  
> “Summarize this video in 5 points”

**Output:** AI-generated summary

---

## 🔗 Connect
 
👤 **Shyam Hari**  
- [LinkedIn](https://www.linkedin.com/in/shyam-hari-5389492b3/)  
- [GitHub](https://github.com/shyamhari1074)  


✨ Learning in public. Suggestions & contributions are always welcome!
