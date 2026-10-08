# Práctica: Integración Continua con GitHub Actions y ntfy.sh

Este repositorio contiene la solución a la práctica de Integración Continua (CI) para **DevOps - ITLA**.

## 📌 Requisitos Cumplidos
1. **Programa Hola Mundo**: Desarrollado en JavaScript (`index.js`).
2. **GitHub Actions Workflow**: Archivo `.github/workflows/alerta.yml` configurado para activarse al hacer push a la rama `main` y enviar una notificación a `ntfy.sh/devops-itla`.

---

## 📁 Estructura del Proyecto

```text
practica-github-actions/
├── .github/
│   └── workflows/
│       └── alerta.yml    # Workflow de GitHub Actions
├── index.js              # Programa Hola Mundo
├── package.json          # Configuración de Node.js
└── README.md             # Documentación de la práctica
```

---

## 🚀 Cómo probar localmente

Para ejecutar el programa en tu máquina:

```bash
node index.js
```

---

## 📤 Instrucciones para subir a tu repositorio en GitHub

1. **Crear un nuevo repositorio en GitHub** (público o privado) llamado `practica-github-actions`.
2. **Conectar tu repositorio local y subir a `main`**:

```bash
cd "C:\Users\eduar\.gemini\antigravity\scratch\practica-github-actions"
git init -b main
git add .
git commit -m "feat: programa hola mundo y workflow de alerta para ntfy"
git remote add origin https://github.com/TU_USUARIO/TU_REPOSITORIO.git
git push -u origin main
```

---

## 🔔 Verificación de la Notificación

Una vez que hagas el `push` a la rama `main`:
1. Ve a la pestaña **Actions** en tu repositorio de GitHub para ver la ejecución en tiempo real.
2. Abre en tu navegador [https://ntfy.sh/devops-itla](https://ntfy.sh/devops-itla) o la app móvil de **ntfy** suscrito al tema `devops-itla`.
3. Verás la notificación con el mensaje de confirmación, usuario y estado de la ejecución.
