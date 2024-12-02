# 🧠 Headstarter AI Agent Workshop

Welcome to the **Headstarter AI Agent Workshop**! This project explores how to interact with cutting-edge Large Language Models (LLMs) using **Groq**, **OpenRouter**, and **OpenAI** APIs. Our goal is to provide a robust foundation for understanding AI model behavior, prompt engineering, and API integration.

---

## 🚀 Repo Statistics

| **Statistic** | **Badge**                                                                 |
|---------------|---------------------------------------------------------------------------|
| Stars         | ![Stars](https://img.shields.io/github/stars/bshongwe/headstarter_AI_workshop?style=social) |
| Forks         | ![Forks](https://img.shields.io/github/forks/bshongwe/headstarter_AI_workshop?style=social) |

---

## 📌 Table of Contents

- [🚀 Project Overview](#-project-overview)  
- [📂 Project Structure](#-project-structure)  
- [⚙️ Installation](#%EF%B8%8F-installation)  
- [🔐 Setting Up API Keys](#-setting-up-api-keys)  
- [🧪 How to Run the Project](#-how-to-run-the-project)  
- [📈 Features](#-features)  
- [🔍 Next Steps](#-next-steps)  
- [🛠️ Technology Stack](#️-technology-stack)  
- [🤝 Contributing](#-contributing)  
- [📞 Contact](#-contact)  
- [🛡️ License](#%EF%B8%8F-license)

---

## 🚀 Project Overview

This project focuses on integrating and interacting with various AI services using their respective APIs. The workshop demonstrates:

- How to set up and configure API clients.
- Techniques for crafting effective prompts for different LLMs.
- Error handling and logging for robust API communication.

---

## 📂 Project Structure

```plaintext
├── notebooks/
│   └── AI_Agent_Workshop.ipynb           # Jupyter Notebook with code and explanations
├── README.md                             # Project documentation
├── requirements.txt                      # Python dependencies
└── .gitignore                            # Files to ignore in Git
```

---

## ⚙️ Installation

### Prerequisites

- Python 3.8 or higher
- Jupyter Notebook or Google Colab

### Clone the Repository

```bash
git clone https://github.com/bshongwe/headstarter_AI_workshop.git
cd headstarter_AI_workshop
```

### Install Dependencies

Use the following command to install the required libraries:

```bash
pip install -r requirements.txt
```

---

## 🔐 Setting Up API Keys

You need to set the following environment variables for the API keys:

| **Service** | **Environment Variable**    | **Description**                 |
|-------------|-----------------------------|---------------------------------|
| Groq        | `GROQ_API_KEY`               | API key for accessing Groq API  |
| OpenRouter  | `OPENROUTER_API_KEY`         | API key for OpenRouter API      |
| OpenAI      | `OPENAI_API_KEY`             | API key for OpenAI API          |

Set them as environment variables in your shell or directly within the notebook:

```python
import os

os.environ['GROQ_API_KEY'] = "your-groq-api-key"
os.environ['OPENROUTER_API_KEY'] = "your-openrouter-api-key"
os.environ['OPENAI_API_KEY'] = "your-openai-api-key"
```

---

## 🧪 How to Run the Project

1. Open the **`Headstarter_AI_Workshop.ipynb`** notebook in Jupyter or Google Colab.
2. Follow the instructions in each cell to:
   - Install necessary libraries.
   - Set up API keys.
   - Initialize API clients.
   - Execute example queries to interact with the LLMs.

3. Run each cell sequentially for a smooth execution experience.

---

## 📈 Features

- **Multi-API Integration**: Seamlessly interact with Groq, OpenRouter, and OpenAI APIs.
- **Customizable Prompts**: Easily modify prompts to test different use cases.
- **Robust Error Handling**: Provides meaningful error messages and guides users through API configuration issues.
- **Modular Design**: Designed for easy extension and customization.

---

## 🔍 Next Steps

1. **Add Logging**: Incorporate logging mechanisms to monitor API responses and debug errors effectively.
2. **Input/Output Enhancements**: Create interactive cells for dynamic user input and output comparison.
3. **Asynchronous Requests**: Leverage asynchronous API calls for improved efficiency and responsiveness.

---

## 🛠️ Technology Stack

| **Technology**  | **Description**                     | **Link**                              | **Badge**                                                                 |
|-----------------|-------------------------------------|---------------------------------------|---------------------------------------------------------------------------|
| Python          | Programming language                | [Python](https://www.python.org)      | ![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python)     |
| Jupyter Notebook| Interactive coding environment      | [Jupyter](https://jupyter.org)        | ![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter) |
| Groq API        | AI model API                        | [Groq](https://www.groq.com)          | ![Groq](https://img.shields.io/badge/Groq-API-green?logo=groq)           |
| OpenRouter API  | Multi-LLM API integration           | [OpenRouter](https://openrouter.ai)   | ![OpenRouter](https://img.shields.io/badge/OpenRouter-API-red?logo=openrouter) |
| OpenAI API      | Access to OpenAI models             | [OpenAI](https://openai.com)          | ![OpenAI](https://img.shields.io/badge/OpenAI-API-blue?logo=openai)      |
| Pip             | Python package manager              | [Pip](https://pip.pypa.io/en/stable/) | ![Pip](https://img.shields.io/badge/Pip-Package%20Manager-blueviolet?logo=pypi) |

---

## 🤝 Contributing

Contributions are most welcome! To contribute:

1. Fork the repository.
2. Create a new branch:  
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:  
   ```bash
   git commit -m "Add your feature"
   ```
4. Push to the branch:  
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request.

---

## 📞 Contact

If you have any questions or need further assistance, please reach out:

**Ernest Bhekizwe Shongwe**  
- 📧 Email: [My Email](mailto:shongwe.bhekizwe@yahoo.com)  
- 💼 LinkedIn: [My LinkedIn Profile](https://linkedin.com/in/ernest-shongwe)  
- 🌐 GitHub: [My GitHub Profile](https://github.com/bshongwe)

---

## 🛡️ License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
