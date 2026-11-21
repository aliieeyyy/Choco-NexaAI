# 🍫 ChocoNexaAI
### An Intelligent NLP-Powered Chocolate & Dates Shopping Assistant

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![NLP](https://img.shields.io/badge/AI-Natural%20Language%20Processing-purple)
![Gradio](https://img.shields.io/badge/UI-Gradio-orange?logo=gradio)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Project Overview

**ChocoNexaAI** is an AI-powered shopping assistant designed to improve the online shopping experience for chocolate and dates customers using Natural Language Processing (NLP).

Traditional shopping systems often require customers to search using exact product names, categories, or predefined filters. ChocoNexaAI aims to make this process more natural by allowing customers to interact with the system using everyday language.

The system understands customer queries, identifies relevant products, provides personalized product recommendations, and assists customers with product-related questions.

With an interactive Gradio interface, ChocoNexaAI provides a simple and user-friendly shopping experience.

---

## 🎯 Project Objectives

- Develop an intelligent shopping assistant using NLP.
- Understand customer queries written in natural language.
- Provide relevant chocolate and dates product recommendations.
- Help customers discover products based on their preferences and budgets.
- Improve product discovery through intelligent text-based searching.
- Create an interactive and accessible shopping interface.

---

## ✨ Key Features

### 1. 🔍 Intelligent Product Search

Allows customers to search for products using natural-language queries.

**Example queries:**
- Show me dark chocolates.
- Find premium dates.
- I need milk chocolate.
- Show me chocolates suitable for gifting.

The system processes customer queries and identifies relevant products from the dataset.

### 2. 🎁 Smart Product Recommendation

Recommends suitable products based on customer preferences, requirements, and budget.

**Example queries:**
- Suggest a gift for my friend under ₹1000.
- Recommend premium chocolates.
- I need something special for a birthday.
- Suggest dates for gifting.

### 3. 💬 Customer Query Assistant

Provides responses to customer questions related to available products and shopping requirements.

**Example queries:**
- Which dates are good for gifting?
- What chocolate products are available?
- Show me products within my budget.
- Which products are suitable for special occasions?

---

## 🧠 Natural Language Processing

ChocoNexaAI uses Natural Language Processing techniques to process and understand customer queries.

The NLP workflow includes:

1. **Text Preprocessing:** Cleaning and preparing customer input.
2. **Text Normalization:** Converting text into a consistent format.
3. **Feature Extraction:** Representing textual information in a machine-readable format.
4. **Query Understanding:** Identifying important keywords and customer requirements.
5. **Product Matching:** Matching customer queries with relevant product information.
6. **Recommendation Generation:** Returning suitable products based on the identified requirements.

### NLP Concepts

- Text Preprocessing
- Tokenization
- Text Normalization
- Keyword Extraction
- Intent Identification
- Text Similarity
- Product Matching
- Natural Language Query Processing

---

## 📂 Dataset Information

The project uses a structured chocolate and dates shopping dataset.

**Dataset:** `smart_chocolate_dates_shop_dataset_1500.csv`

The dataset contains approximately 1,500 product and shopping records.

### Dataset Attributes

| Column | Description |
|---|---|
| Date | Transaction date |
| Product ID | Unique product identifier |
| Product | Product name |
| Category | Product category |
| Brand | Product brand |
| Price | Selling price |
| Cost Price | Product cost |
| Quantity Sold | Number of products sold |
| Stock | Available stock |
| Reorder Level | Minimum stock threshold |
| Customer Type | Customer category |
| Festival | Festival information |
| Payment Method | Payment type |
| Season | Seasonal information |

The dataset provides structured product and shopping information for the assistant.

---

## 🏗️ Project Architecture

The system follows a simple NLP-based workflow.

**Customer Input → Text Preprocessing → Query Understanding → Product Matching → Recommendation / Response → Gradio Interface**

### Workflow Explanation

1. Customers enter their queries through the Gradio interface.
2. The system receives and preprocesses the input text.
3. NLP techniques are applied to understand the query.
4. Relevant product information is identified from the dataset.
5. Suitable results or responses are generated.
6. Results are displayed through the interactive interface.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Dataset handling and processing |
| NumPy | Numerical operations |
| NLP | Natural language understanding |
| Scikit-learn | Machine learning utilities for text processing, where applicable |
| Gradio | Interactive web application |
| Jupyter Notebook / Google Colab | Development environment |

---

## 📁 Project Structure

```text
ChocoNexaAI/
│
├── app.py
│
├── smart_chocolate_dates_shop_dataset_1500.csv
│
├── requirements.txt
│
├── README.md
│
└── assets/
    └── screenshots/
```

*Note: Adjust the filenames and folder structure to match your actual GitHub repository.*

---

## ⚙️ Installation and Setup

### Step 1: Clone the Repository

```bash
git clone https://github.com/aliieeyyy/Choco-NexaAI.git
```

### Step 2: Navigate to the Project Directory

```bash
cd Choco-NexaAI
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Run the Application

```bash
python app.py
```

### Step 5: Open the Interface

Once the application starts, open the local Gradio URL displayed in your terminal.

---

## 💻 Application Interface

ChocoNexaAI provides a chocolate-themed interface designed to make interaction simple and enjoyable.

The interface includes:

- Product Search
- Product Recommendation
- Customer Query Assistant
- Interactive text input
- Product information display
- Chocolate-themed visual design

---

## 🌟 Real-World Applications

ChocoNexaAI demonstrates how NLP can improve customer interaction in e-commerce environments.

Potential applications include:

- Online chocolate stores
- Dates and dry-fruit shopping platforms
- Gift recommendation systems
- E-commerce customer support
- Intelligent product discovery systems

---

## 🚀 Future Enhancements

The project can be extended with advanced AI capabilities:

- Integration of transformer-based NLP models.
- Multilingual customer query support.
- Voice-based shopping assistance.
- Context-aware conversations.
- Advanced personalized recommendation algorithms.
- Real-time product database integration.
- Customer preference learning.
- Deployment as a cloud-based shopping assistant.

---

## 🎯 Project Outcomes

ChocoNexaAI demonstrates the practical application of Natural Language Processing in an e-commerce environment.

The project focuses on making product discovery easier, improving customer interaction, and providing intelligent shopping assistance through natural-language communication.

It also provides practical experience in dataset processing, NLP workflows, recommendation systems, and interactive AI application development.

---

## 👨‍💻 Developer

**Ali Akbar P**

Data Science & Artificial Intelligence Student

📍 Malappuram, Kerala, India

🔗 **GitHub:** [aliieeyyy](https://github.com/aliieeyyy)

---

## 📜 License

This project is developed for educational and portfolio purposes.

---

### 🍫 ChocoNexaAI
**Making Chocolate & Dates Shopping Smarter with AI.**
