# 📄 Check PDF in One Page

> A utility tool to verify if a PDF document contains only a single page.

---

## 🎯 Overview

This project provides a simple and efficient solution to check whether a PDF file is contained within a single page or spans multiple pages. It's useful for document validation, automated workflows, and quality assurance processes.

### ✨ Key Features

- ✅ Quick PDF page count verification
- 🚀 Fast and lightweight
- 📊 Simple and intuitive usage
- 🔧 Python-based implementation
- 📚 Jupyter Notebook examples included

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37726?style=flat-square&logo=jupyter&logoColor=white)

- **Python** (33.4%) - Core implementation
- **Jupyter Notebook** (66.6%) - Examples and demonstrations

---

## 📦 Installation

### Prerequisites

- Python 3.6 or higher
- pip (Python package manager)

### Steps

1. Clone the repository:
```bash
git clone https://github.com/C-2631/Check-PDF-in-One-Page.git
cd Check-PDF-in-One-Page
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

---

## 🚀 Usage

### Basic Example

```python
from pdf_checker import check_single_page

# Check if a PDF is a single page
result = check_single_page('document.pdf')

if result:
    print("✅ PDF contains only one page")
else:
    print("❌ PDF contains multiple pages")
```

### Jupyter Notebook

For interactive examples and demonstrations, refer to the Jupyter Notebook files included in this repository.

---

## 📂 Project Structure

```
Check-PDF-in-One-Page/
├── README.md                 # This file
├── requirements.txt          # Python dependencies
├── pdf_checker.py           # Main implementation
└── examples/                # Jupyter notebooks with examples
    └── example_usage.ipynb
```

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -m 'Add improvement'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

---

## 📝 License

This project is open source and available under the MIT License.

---

## 💬 Support

If you encounter any issues or have questions, please:
- Open an [Issue](https://github.com/C-2631/Check-PDF-in-One-Page/issues)
- Check existing documentation
- Review the Jupyter Notebook examples

---

## 🙏 Acknowledgments

Built with ❤️ for PDF document management.

---

**Made with Python** | **Powered by Jupyter** 🚀
