# 🏋️ Trainify – Aplicación de gestión de entrenamiento

Aplicación web para gestionar rutinas de entrenamiento y seguimiento del progreso físico, desarrollada como proyecto intermodular del ciclo formativo de **Desarrollo de Aplicaciones Multiplataforma (DAM)**.

🌐 **Aplicación en producción:** https://estebagsv30-lgtm.github.io/trainify/

---

## 📋 Descripción

Trainify permite a los usuarios:

- Registrarse e iniciar sesión
- Crear, editar y eliminar rutinas de entrenamiento
- Añadir y eliminar ejercicios dentro de cada rutina
- Registrar sesiones de entrenamiento (series, repeticiones y peso)
- Consultar el historial de entrenamientos por rutina
- Registrar y visualizar el historial de peso corporal

---

## 🛠️ Tecnologías utilizadas

- **HTML5** – Estructura de las páginas
- **CSS3** – Estilos y diseño responsive
- **JavaScript (Vanilla)** – Lógica de la aplicación
- **localStorage** – Almacenamiento de datos en el navegador (sin servidor)
- **Git & GitHub** – Control de versiones

---

## 📁 Estructura del proyecto

```
trainify/
├── index.html       → Pantalla de login y registro
├── dashboard.html   → Panel principal (rutinas y peso corporal)
├── rutina.html      → Detalle de rutina y registro de sesiones
└── README.md        → Este archivo
```

---

## 🚀 Instalación y puesta en marcha

### Opción 1 – Acceso directo (más sencilla)

Accede directamente desde el navegador:

```
https://estebagsv30-lgtm.github.io/trainify/
```

### Opción 2 – Instalación local

1. Descarga o clona el repositorio:

```
git clone https://github.com/estebagsv30-lgtm/trainify.git
```

2. Abre la carpeta descargada.
3. Haz doble clic en el archivo `index.html`.
4. La aplicación se abrirá en tu navegador predeterminado.

> **No requiere servidor, instalación de software ni conexión a internet** una vez descargado.

---

## 👤 Cómo usar la aplicación

1. Abre la app en el navegador.
2. Crea una cuenta nueva en la pestaña **"Registrarse"**.
3. Inicia sesión con tu correo y contraseña.
4. Desde el **Dashboard** puedes:
   - Crear nuevas rutinas con el botón **"+ Nueva rutina"**
   - Registrar tu peso corporal
5. Haz clic en **"Ver detalle"** de una rutina para:
   - Añadir o eliminar ejercicios
   - Registrar series, repeticiones y peso de cada sesión
   - Consultar el historial de esa rutina

---

## ⚙️ Requisitos

| Requisito         | Detalle                                          |
| ----------------- | ------------------------------------------------ |
| Navegador         | Chrome, Firefox, Edge o Safari (versión moderna) |
| Servidor          | No necesario                                     |
| Internet          | Solo para el acceso vía URL pública              |
| Sistema operativo | Windows, macOS o Linux                           |

---

## 📌 Notas

- Los datos se almacenan en el **localStorage** del navegador. Cada usuario tiene sus datos separados.
- Si limpias los datos del navegador, los datos de la aplicación se borrarán.
- La aplicación es completamente funcional sin necesidad de backend ni base de datos externa.

---

## 👨‍💻 Autor

**Esteban Sánchez**
Ciclo Formativo: Desarrollo de Aplicaciones Multiplataforma (DAM)
Centro: CESUR · Curso 2025–2026
