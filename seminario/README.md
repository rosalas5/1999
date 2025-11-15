# 1999
Repositorio para seminario final de ingeniería de Software

---


# 🚀 Instructivo para levantar una app Django con entorno virtual (Windows)

> Seguí estos pasos para levantar el proyecto.

---

## 🐍 1. Instalá Python
Asegurate de tener Python instalado. Si no lo tenés, bajalo de [python.org](https://www.python.org/downloads/). Cuando lo instales, **acordate de tildar la opción Add Python to PATH**.

## 💻 2. Abrí PowerShell
Ir a la carpeta donde quieras armar tu proyecto Django y abrir PowerShell.

## 🎩 3. Creá y activá el entorno virtual
```powershell
python -m venv venv
.\venv\Scripts\Activate
```
Vas a ver que el prompt cambia, eso significa que el entorno está activo. Si no cambia, revisá que estés en la carpeta correcta.

## ⬆️ 4. Actualizá pip (opcional)
```powershell
python -m pip install --upgrade pip
```

## 📦 5. Instalá Django
```powershell
pip install django
```

## 🏗️ 6. Creá el proyecto Django
```powershell
django-admin startproject mi_proyecto
```

## 📂 7. Entrá a la carpeta del proyecto
```powershell
cd mi_proyecto
```

## ▶️ 8. Levantá el servidor de desarrollo
```powershell
python manage.py runserver
```
Va a aparecer un mensaje diciendo que el servidor está corriendo. Abrir el navegador en:
```
http://127.0.0.1:8000/
```

¡Listo! Ya tenés el proyecto Django andando en un entorno virtual. 🎉

---

## 📝 Notas
- Para salir del entorno virtual, usar el comando:
  ```powershell
  deactivate
  ```
- Si querés instalar más paquetes, usá `pip install nombre_paquete` o `pip install -r archivo.txt`.