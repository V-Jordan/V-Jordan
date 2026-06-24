# 📋 Comandos Git y Terminal - Victor Jordan

---

## 🖥️ Comandos de Terminal (PowerShell / Git Bash)

| Comando | Para qué sirve |
|--------|----------------|
| `cd nombre_carpeta` | Entrar a una carpeta |
| `cd ..` | Subir un nivel (salir de la carpeta actual) |
| `ls` | Ver los archivos y carpetas del directorio actual |
| `code .` | Abrir la carpeta actual en VS Code |
| `code archivo.md` | Abrir un archivo específico en VS Code |

---

## 🔧 Comandos Git - Configuración inicial

| Comando | Para qué sirve |
|--------|----------------|
| `git config --global user.name "Tu Nombre"` | Configurar tu nombre en Git |
| `git config --global user.email "tu@email.com"` | Configurar tu email en Git |

---

## 📥 Clonar un repositorio

| Comando | Para qué sirve |
|--------|----------------|
| `git clone https://github.com/usuario/repo.git` | Descargar un repositorio de GitHub a tu PC |

---

## 📤 Subir cambios a GitHub

| Comando | Para qué sirve |
|--------|----------------|
| `git add .` | Preparar TODOS los archivos modificados para subir |
| `git add archivo.html` | Preparar solo un archivo específico |
| `git commit -m "mensaje"` | Guardar los cambios con una descripción |
| `git push` | Subir los cambios a GitHub |

---

## 🔍 Ver estado del repositorio

| Comando | Para qué sirve |
|--------|----------------|
| `git status` | Ver qué archivos han cambiado y cuáles están listos para subir |
| `git log --oneline` | Ver el historial de commits de forma resumida |

---

## 🌿 Ramas (Branches)

| Comando | Para qué sirve |
|--------|----------------|
| `git branch` | Ver en qué rama estás |
| `git checkout -b nombre-rama` | Crear una nueva rama y cambiarte a ella |
| `git checkout main` | Volverte a la rama principal |

---

## 📝 Notas importantes

- Siempre ejecutar los comandos **desde la carpeta del repositorio** (ej: `C:\Users\donjo\OneDrive\Escritorio\V-Jordan`)
- El `git push` pedirá tu **usuario de GitHub** y tu **Personal Access Token** como contraseña
- El preview del README en VS Code se abre con **`Ctrl + Shift + V`**

---

*Última actualización: Junio 2026*