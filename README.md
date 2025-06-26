# 📸 Zinmage

**Zinmage** is a minimalist and beginner-friendly Python library and CLI Program for image conversion.  
It’s designed to be clean, modular, and super easy to use — perfect for devs who just want things to work. ✨

> 💡 Current Feature: Convert `.png` to `.jpg` or vice versa using **one line of code**.

---

## 🚀 Features

- 🎯CLI Version Abvalible
- ✅ Convert PNG ➜ JPG in seconds
- 🧩 Modular design — more formats coming soon
- 🪶 Lightweight and dependency minimal (just uses Pillow)
- 💬 Clean and easy API — no boilerplate needed

---

## 🔧 Installation

```bash
pip install zinmage

```

Or install from source:

```bash
git clone https://github.com/tinprogrammers/zinmage.git
cd zinmage
pip install .

```

---

## 🧠 Usage Libary

```python
from zinmage import convert_png_to_jpg

convert_png_to_jpg("example.png")  # Output: example.jpg

```

You can also provide a custom output path:

```python
convert_png_to_jpg("example.png", "converted/my-image.jpg")

```

## Methods

| Features  | Methods              |
| --------- | -------------------- |
| PNG ➜ JPG | `convert_png_to_jpg` |
| JPG ➜ PNG | `convert_jpg_to_png` |

---

## 🧠 Usage CLI

## Methods

| Features  | Methods                              |
| --------- | ------------------------------------ |
| PNG ➜ JPG | `zinmage convert input.png --to jpg` |
| JPG ➜ PNG | `zinmage convert photo.jpg --to png` |

---

## 🗃️ Project Structure

```
zinmage/
├── zinmage/
│   ├── converters/
│   │   └── png_to_jpg.py
│   ├── utils/
│   │   └── helpers.py
│   └── __init__.py
├── tests/
│   └── test_png_to_jpg.py
├── README.md
├── setup.py
├── pyproject.toml
├── LICENSE

```

---

## 🧪 Running Tests

```bash
pytest tests/

```

(Uses built-in dummy image for testing.)

---

## 📌 Coming Soon

- WebP & BMP support
- Batch folder conversion
- Resize & optimize
- GUI web tool (zinmage.com)

---

## 🧑‍💻 Author

**Azeem Akhtar**  
Founder of Zinmage and Tin Programmers, 🚀  
[GitHub](https://github.com/tinprogrammers) | [LinkedIn](https://www.linkedin.com/in/azeemakhtarofficial/) | [Youtube](https://www.youtube.com/@TinProgrammerofficial)

---

## 📄 License

This project is licensed under the [MIT License](https://opensource.org/license/mit).

---

## ❤️ Support

If you like the project, star it ⭐ on GitHub, and share it with your dev friends.  
Pull requests and contributions are most welcome!
