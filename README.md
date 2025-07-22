# 🛍️ Amazon Customer Support Multi-Agent System

This project is a **Multi-Agent AI System** for automating **customer support and query resolution** at Amazon. It uses machine learning and NLP techniques to classify user queries and route them to the appropriate expert agent (e.g., returns, delivery, technical support, or general inquiries).

Developed in **Python** with a user-friendly **Gradio interface**, and designed to run on **Google Colab**.




## 🚀 Features

- 🔍 **Intent Classification** using TF-IDF + Logistic Regression
- 🧠 **Dedicated Agents** for:
  - Returns
  - Delivery Issues
  - Technical Support
  - General Queries
- 😠 **Sentiment Detection** for escalation handling using Transformers
- 🌐 **Gradio Chat UI** for easy interaction
- 📈 Scalable and customizable for real-world deployment




## 🛠️ Tech Stack

| Component             | Library / Tool           |
|----------------------|--------------------------|
| Intent Classification| Scikit-learn (Logistic Regression) |
| Sentiment Analysis   | Hugging Face Transformers |
| Interface            | Gradio                   |
| Deployment           | Google Colab / Hugging Face Spaces |




## 📦 Installation & Setup

1. **Clone this repository:**

   ```
   git clone https://github.com/yourusername/amazon-customer-support-multiagent.git
   cd amazon-customer-support-multiagent
````

2. **Run on Google Colab:**

   * Open `amazon_multiagent_customer_support.ipynb` in [Google Colab](https://colab.research.google.com/)
   * Install dependencies in Colab:

     ```
     !pip install gradio transformers scikit-learn
     ```

3. **Launch the App:**
   The last cell will launch a Gradio interface with public sharing enabled.

---

## 💡 How It Works

1. User enters a query.
2. The system uses an intent classifier to detect the category.
3. The appropriate agent responds with a pre-defined or dynamic message.
4. If the query is negative/frustrated (via sentiment analysis), escalation advice is provided.

---




## 🌍 Deployment Options

* ✅ Google Colab (Recommended)
* ✅ Hugging Face Spaces *(for public access)*
* ✅ Local Python environment with Gradio




## 🧪 Example Queries

| Query                           | Routed To       |
| ------------------------------- | --------------- |
| “How can I return a product?”   | Returns Agent   |
| “Where is my package?”          | Delivery Agent  |
| “Alexa won't connect to Wi-Fi.” | Technical Agent |
| “How do I update my address?”   | General Agent   |




## 🙌 Acknowledgements

* [Gradio](https://gradio.app/)
* [Hugging Face Transformers](https://huggingface.co/transformers/)
* [Scikit-learn](https://scikit-learn.org/)




## 📜 License

MIT License. Feel free to fork and customize.
