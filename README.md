# test-crispy

**test-crispy** is a lightweight testing utility for Django projects using [django-crispy-forms](https://django-crispy-forms.readthedocs.io/). It helps you ensure form rendering remains consistent across versions with snapshot testing, layout validation, and linting tools.

> 🧪 Assert your forms look *crispy*, every time.

> ⚠ **WARNING**: This is a dummy repository!

---

## 🚀 Features

- Snapshot testing for rendered Django crispy forms
- Layout linting to detect common anti-patterns
- Template validation for correct usage of crispy tags
- Seamless integration with Django and pytest
- Minimal configuration, fast feedback

---

## 📦 Installation

You can install test-crispy via pip or add it to your project’s development dependencies. It is intended for use in test and CI environments.

---

## 🛠️ Usage

Once installed, test-crispy integrates with your Django test suite and supports popular tools like pytest. Simply add your form tests and run them like any other test case.

test-crispy validates your crispy forms’ structure and checks whether your rendered output has changed unexpectedly.

---

## 📚 Documentation

Full documentation is available at:

[https://test-crispy.readthedocs.io](https://test-crispy.readthedocs.io)

You’ll find guides on configuring snapshot directories, supported template packs, and advanced usage patterns.

---

## 🔧 Configuration

test-crispy can be configured via `pytest.ini`, `setup.cfg`, or a `pyproject.toml` section. You can customize things like snapshot output directories and the crispy template pack (e.g. bootstrap4, bootstrap5).

---

## ✅ Compatibility

- Django 3.2+
- Python 3.8+
- django-crispy-forms 1.9+

---

## 🧑‍💻 Contributing

We welcome contributions of all kinds — whether it’s reporting bugs, improving documentation, or submitting a pull request. Check out `CONTRIBUTING.md` for details on how to get started.

---

## 📄 License

MIT License  
Copyright © 2025

---

## 👤 Maintainer

**Alex Example**  
GitHub: [@alexexample](https://github.com/alexexample)

---
