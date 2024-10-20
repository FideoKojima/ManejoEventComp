# 🏥 Administrador de Citas Médicas

![Vue.js](https://img.shields.io/badge/vuejs-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

Una aplicación web intuitiva y eficiente para gestionar citas médicas, desarrollada con Vue.js.

![Ejemplo de uso](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNGNmOTExMzIwMzM5MTdiMjg5ZmM5YzFkM2NjMzk4ZWEwMjIxMzU3ZiZlcD12MV9pbnRlcm5hbF9naWZzX2dpZklkJmN0PWc/3oKIPa2TdahY8LAAxy/giphy.gif)

## 📋 Tabla de Contenidos

- [Características](#-características)
- [Tecnologías Utilizadas](#-tecnologías-utilizadas)
- [Instalación](#-instalación)
- [Uso](#-uso)
- [Estructura del Proyecto](#-estructura-del-proyecto)
- [Contribución](#-contribución)
- [Licencia](#-licencia)

## ✨ Características

- 📝 Formulario interactivo para agregar nuevas citas
- 🚦 Sistema de prioridad por gravedad (Baja, Media, Alta)
- 🎨 Cambio dinámico de colores según la gravedad de la cita
- 🗑️ Eliminación fácil de citas
- 📱 Diseño responsivo

## 🛠 Tecnologías Utilizadas

- Vue.js 3
- JavaScript (ES6+)
- CSS3

## 🚀 Instalación

1. Clona este repositorio:
   ```
   git clone https://github.com/tu-usuario/administrador-citas-medicas.git
   ```
2. Navega al directorio del proyecto:
   ```
   cd administrador-citas-medicas
   ```
3. Instala las dependencias:
   ```
   npm install
   ```

## 🖥 Uso

1. Inicia el servidor de desarrollo:
   ```
   npm run serve
   ```
2. Abre tu navegador y visita `http://localhost:8080`

3. Utiliza el formulario para agregar nuevas citas:

   - Completa todos los campos requeridos
   - El botón "Agregar" se habilitará automáticamente cuando todos los campos estén llenos
   - Las citas se mostrarán en tarjetas debajo del formulario

4. Para eliminar una cita, simplemente haz clic en el botón "Eliminar" en la tarjeta correspondiente

## 📁 Estructura del Proyecto

```
administrador-citas-medicas/
│
├── src/
│   ├── components/
│   │   └── CitaCard.vue
│   ├── App.vue
│   └── main.js
│
├── public/
│   └── index.html
│
├── package.json
└── README.md
```

## 👥 Contribución

Las contribuciones son bienvenidas. Por favor, sigue estos pasos:

1. Haz un Fork del proyecto
2. Crea tu Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la Branch (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Distribuido bajo la Licencia MIT. Ver `LICENSE` para más información.

---

Desarrollado con ❤️ por [Tu Nombre](https://github.com/tu-usuario)
