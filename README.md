# 📚 Books-App

Una aplicación sencilla para crear libros usando HTML, CSS, JavaScript y json-server para simular un backend.

---

## ¿Qué aprenderás?

- Crear datos dinámicamente y guardarlos en un backend simulado.
- Trabajar con HTML, CSS y JavaScript puro.
- Usar [json-server](https://github.com/typicode/json-server) para simular un servidor backend con un archivo JSON.

---

## Estructura del proyecto

```
Books-App/
├── server/
│ └── db.json
├── src/
│ ├── service.js
│ └── styles.css
├── index.html
├── .gitignore
├── package.json
├── package-lock.json
└── README.md
```

---

## Instalación y ejecución

1. Clona el repositorio:
    ```bash
    git clone https://github.com/Aday25/book-app-vanilla.git
    cd book-app-vanilla
    ```

2. Instala las dependencias:
    ```bash
    npm install
    ```

3. Añade este script en tu `package.json` si no está:
    ```json
    "scripts": {
      "api": "json-server --watch server/db.json"
    }
    ```

4. Ejecuta el servidor JSON simulado:
    ```bash
    npm run api
    ```

5. Abre `index.html` en tu navegador (o usa un servidor local).

---

## Cómo funciona la API

La base URL para las peticiones es: `http://localhost:3000/books`

Operación disponible:

- `POST` → Crear un libro nuevo

---

## Tecnologías utilizadas

<p>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/json--server-000000?style=for-the-badge&logo=json&logoColor=white" alt="json-server" />
</p>

---

## 🤝 Contribuciones

¿Quieres colaborar con el proyecto? ¡Toda ayuda es bienvenida! Puedes:

- Mejorar el diseño visual con CSS
- Refactorizar el código JavaScript
- Agregar funcionalidades o modularidad

¿Cómo contribuir?

```bash
# Haz un fork del repositorio
git clone https://github.com/Aday25/book-app-vanilla.git

# Crea una rama para tu mejora
git checkout -b mejora-nueva

# Haz tus cambios y guárdalos
git commit -m "Agrega nueva funcionalidad"

# Sube los cambios a tu fork
git push origin mejora-nueva
Luego, abre una Pull Request desde GitHub 🚀

Autor
Desarrollado por Aday25.

---

¡A crear libros! 📚✨

---

<p align="center">
  <img src="logo.png" alt="Logo Aday25" width="150" />
</p>
