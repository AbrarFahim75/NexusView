#  NexusView

<p align="left">
  <img src="https://img.shields.io/pypi/v/NexusView.svg">
  <img src="https://img.shields.io/pypi/pyversions/NexusView.svg">
  <img src="https://img.shields.io/badge/License-Apache%202.0-blue.svg">
  <img src="https://img.shields.io/pypi/dm/NexusView.svg">
</p>

---

## Overview

**NexusView** is a lightweight Python package that enables you to render **websites** and **YouTube videos** directly inside Jupyter Notebook (`.ipynb`).

No more switching tabs while working on notebooks — bring external content right into your workflow.

---

## ✨ Features

* 🌐 Render any public website inside Jupyter Notebook
* ▶️ Embed YouTube videos instantly
* ⚡ Simple and clean API
* 🧩 Built on top of IPython display utilities
* 📦 Lightweight and fast

---

## 📦 Installation

Install from PyPI:

```bash
pip install NexusView
```

Or install from source:

```bash
git clone https://github.com/AbrarFahim75/NexusView.git
cd NexusView
pip install .
```

---

## Usage

### 🌐 Render a Website

```python
from NexusView import render_website

render_website("https://example.com")
```

---

### ▶️ Render a YouTube Video

```python
from NexusView import render_youtube

render_youtube("https://www.youtube.com/watch?v=dQw4w9WgXcQ")
```

---

## 🧠 How It Works

NexusView uses IPython’s display system (such as `IFrame`) to embed external web content directly into notebook cells, enabling a smooth and interactive experience.

---

## 📁 Project Structure

```
NexusView/
│── src/
│   └── NexusView/
│       ├── __init__.py
│       ├── site.py
│       ├── youtube.py
│       ├── logger.py
│       ├── custom_exception.py
│
│── tests/
│── README.md
│── setup.py
│── pyproject.toml
│── requirements.txt
```

---

## 🛠️ Requirements

* Python 3.7+
* Jupyter Notebook / Jupyter Lab
* IPython

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Open a pull request

---

## 🐛 Issues

Found a bug or want to request a feature?

👉 https://github.com/AbrarFahim75/NexusView/issues

---

## 📄 License

This project is licensed under the Apache License 2.0.

---

## 💡 Future Improvements

* Support for more media platforms
* Custom iframe styling
* Responsive resizing options
* Streamlit / web app integration

---

## 👨‍💻 Author

**Md Abrar Fahim**
🔗 https://github.com/AbrarFahim75
