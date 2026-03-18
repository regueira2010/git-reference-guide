# 🚀 Introducción a GitHub

GitHub es una plataforma de desarrollo colaborativo que permite almacenar, gestionar y versionar código utilizando Git.

Facilita el trabajo en equipo, el control de cambios y la publicación de proyectos de software.

---

## 📌 ¿Para qué se utiliza?

GitHub se utiliza principalmente para:

- 🔄 Control de versiones de código
- 👥 Trabajo colaborativo en equipos
- 💾 Respaldo y almacenamiento de proyectos
- 🚀 Despliegue y publicación de aplicaciones
- 🧪 Seguimiento de errores (issues) y mejoras

---

## ⚙️ Flujo básico de trabajo en Git

1. Crear o clonar un repositorio
2. Realizar cambios en los archivos
3. Agregar cambios (`git add`)
4. Guardar cambios (`git commit`)
5. Subir cambios a GitHub (`git push`)

---

## 🧾 Comandos básicos de Git

| Comando                | Descripción                                      | Ejemplo de uso                    |
|------------------------|--------------------------------------------------|----------------------------------|
| git init               | Inicializa un repositorio local                  | `git init`                       |
| git clone              | Clona un repositorio remoto                      | `git clone URL`                  |
| git add .              | Agrega todos los archivos al staging             | `git add .`                      |
| git add archivo        | Agrega un archivo específico                     | `git add index.js`               |
| git commit -m "msg"    | Guarda cambios con un mensaje                    | `git commit -m "Primer commit"`  |
| git status             | Muestra el estado del repositorio                | `git status`                     |
| git log                | Muestra historial de commits                     | `git log`                        |
| git branch             | Lista las ramas                                  | `git branch`                     |
| git checkout -b rama   | Crea y cambia a una nueva rama                   | `git checkout -b feature-login`  |
| git merge rama         | Fusiona una rama con la actual                   | `git merge feature-login`        |
| git remote add origin  | Conecta repo local con GitHub                    | `git remote add origin URL`      |
| git push               | Envía cambios al repositorio remoto              | `git push origin main`           |
| git pull               | Trae cambios desde el repositorio remoto         | `git pull origin main`           |

---

## 🌿 Buenas prácticas

- Escribe mensajes de commit claros y descriptivos
- Haz commits pequeños y frecuentes
- Usa ramas para nuevas funcionalidades
- No subas archivos sensibles (como `.env`)
- Mantén tu repositorio actualizado con `git pull`

---

## 📁 Estructura básica de un repositorio
