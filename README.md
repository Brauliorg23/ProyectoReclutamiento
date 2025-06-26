# Formulario Dinámico por Secciones
Este proyecto es un formulario dinámico construido con React + Vite, diseñado para capturar información por secciones basado en el archivo `TutorFormData.ts` (Archivo proporcionado como JsonData). Está adaptado visualmente con los colores institucionales inspirados en la empresa MIAA (Modelo Integral de Aguas de Aguascalientes).

---

## 🚀 Tecnologías utilizadas
- React 18
- Vite
- CSS personalizado inspirado en MIAA
- JavaScript / TypeScript

---

## 📁 Estructura del proyecto
```
formulario-tutor/
├── public/
├── src/
│   ├── components/        # Componentes reutilizables (FormSection, Summary)
│   ├── data/              # Archivo original con preguntas (TutorFormData.ts)
│   ├── App.jsx            # Lógica principal del formulario
│   ├── main.jsx           # Punto de entrada de React
│   └── index.css          # Estilo inspirado en MIAA
├── index.html
├── package.json
└── vite.config.js
```

---

## 🧠 Funcionalidades principales
- Navegación por secciones (solo una visible a la vez)
- Renderizado dinámico de campos (`input`, `select`, `number`, `email`, `checkbox`, `password`)
- Validaciones dinámicas (`required`, `min`, `max`, `step`, etc.)
- Persistencia de datos al navegar entre secciones
- Resumen final con todas las respuestas
- Diseño institucional claro, accesible y moderno

---

## 🛠️ Instalación y uso

### 1. Clona o descomprime el proyecto
```bash
cd formulario-tutor
```

### 2. Instala las dependencias
```bash
npm install
```

### 3. Inicia la app
```bash
npm run dev
```

Accede en tu navegador a:

```
http://localhost:5173
```

---

## ✨ Créditos

Desarrollado por Braulio Rodriguez Alvarez.
