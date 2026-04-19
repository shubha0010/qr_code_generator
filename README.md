# QR Code Generator 🔲

A simple Python-based QR Code Generator built for **Google Colab** that lets you convert any URL into a downloadable QR code image.

## 📋 Overview

This project provides an easy-to-use interface inside a Jupyter/Colab notebook to generate QR codes from URLs. Enter a URL, run the cell, and instantly get a QR code displayed in the notebook with a one-click download option.

## ✨ Features

- Convert any URL into a QR code
- Instant preview of the generated QR code inside the notebook
- One-click download button to save the QR code as a `.png` file
- Simple and lightweight — no complex setup required

## 🛠️ Requirements

- Google Colab (or a Jupyter Notebook environment)
- Python 3.x
- The following Python libraries:
  - `qrcode`
  - `ipywidgets`
  - `IPython`
  - `google-colab` (pre-installed in Colab)

## 📦 Installation

If running outside of Google Colab, install the required packages manually:

```bash
pip install qrcode[pil] ipywidgets
```

In Google Colab, `ipywidgets` and `google.colab` are pre-installed. You may only need:

```bash
pip install qrcode[pil]
```

## 🚀 Usage

1. Open the notebook in [Google Colab](https://colab.research.google.com/).
2. In the designated cell, enter the URL you want to encode:
   ```python
   Enter_URL = "https://your-url-here.com"
   ```
3. Run the cell.
4. The QR code will be:
   - **Displayed** inline in the notebook output.
   - **Saved** as `generated_qrcode.png` in the Colab session.
5. Click the **"Download QR Code"** button to save it to your local machine.

## 📁 Output

| File | Description |
|------|-------------|
| `generated_qrcode.png` | The generated QR code image |

## 📌 Notes

- The QR code file is saved in the active Colab session directory. It will be lost when the session ends unless downloaded.
- Make sure the URL is valid before generating the QR code.
- The notebook is designed specifically for Google Colab; the `google.colab.files` module is used for file downloads and may not work in standard Jupyter environments.

## 🤝 Contributing

Contributions, bug reports, and feature suggestions are welcome! Feel free to open an issue or submit a pull request.

---

Made with ❤️ by [shubha0010](https://github.com/shubha0010)
