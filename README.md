# vnptable

```
                           
             _       _   _
 _ _ ___ ___| |_ ___| |_| |___
| | |   | . |  _| .'| . | | -_|
 \_/|_|_|  _|_| |__,|___|_|___|    v0.1.0
        |_|
```

A simple and powerful Python package for working with the periodic table of chemical elements.

---

## 📦 Installation

```bash
pip install vnptable
```

---

## 📖 Usage

### Import package

```python
from vnptable import Element
```

---

### Get element by atomic number

```python
e = Element(1)
print(e.name)       # hydrogen
print(e.symbol)     # H
```

---

### Get element by symbol

```python
e = Element("O")
print(e.name)       # oxygen
print(e.atomic_mass)
```

---

### Get element by name

```python
e = Element("carbon")
print(e.symbol)     # C
```

---

### Access properties

```python
e = Element(26)

print(e.name)                   # iron
print(e.symbol)                 # Fe
print(e.atomic_number)          # 26
print(e.atomic_mass)
print(e.electron_configuration)
print(e.group)
print(e.period)
print(e.category)
```

---

## 🧪 Example

```python
from vnptable import Element

iron = Element(26)

print(f"{iron.name} ({iron.symbol})")
print(f"Atomic number: {iron.atomic_number}")
print(f"Electron configuration: {iron.electron_configuration}")
```

---


## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

---

## 📄 License

MIT License

---

## 👨‍💻 Author

Hoàng Đức Tùng  
GitHub account: https://github.com/hoangdtung-2013

---

## ⭐ Support

If you like this project, please give it a ⭐ on GitHub!
````
