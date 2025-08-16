# Django Tutorial Project

This project demonstrates a basic Django setup. Follow the steps below to get started.

## 1. Create a Virtual Environment
```powershell
py -m venv .venv
```

## 2. Activate the Virtual Environment
```powershell
.venv\Scripts\activate
```

## 3. Install Requirements
```powershell
pip install -r requirements.txt
```

## 4. Deactivate the Virtual Environment
```powershell
deactivate
```

## 5. Install Django (if needed)
```powershell
py -m pip install Django
```

## 6. Check Django Version
```powershell
py
```
Then, in the Python shell:
```python
import django
print(django.get_version())
```
Type `quit()` to exit Python.

## 7. Create a Django Project
```powershell
django-admin startproject [nameofproject]
```

## 8. Run the Development Server
```powershell
py manage.py runserver
```