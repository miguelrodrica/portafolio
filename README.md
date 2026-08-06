# Portafolio Profesional

Este repositorio contiene una **página web estática** construida con HTML y CSS, enfocada en mostrar información profesional de forma clara, visual y ordenada.

El propósito es servir como vitrina digital para:
- Presentar proyectos desarrollados.
- Mostrar habilidades técnicas.
- Facilitar el contacto profesional.

---

## Tecnologías

- **HTML5** estructura semántica del contenido. (`~51.4%`)
- **CSS3** diseño visual, distribución de secciones, estilos tipográficos y responsividad. (`~48.6%`)

---

## Cómo ejecutar el proyecto

No requiere instalación de dependencias ni build.

### Opción rápida
1. Clona este repositorio:
   ```bash
   git clone https://github.com/miguelrodrica/portafolio.git
   ```
2. Entra al directorio:
   ```bash
   cd portafolio
   ```
3. Abre `index.html` en tu navegador.

### Opción recomendada (servidor local)

#### Con VS Code + Live Server
1. Abre el proyecto en VS Code.
2. Instala la extensión **Live Server**.
3. Click derecho en `index.html` → **Open with Live Server**.

#### Con Python
Desde la raíz del proyecto:
```bash
python -m http.server 5500
```
Luego visita:
`http://localhost:5500`

---

## Estructura del proyecto

> Estructura base esperada para este tipo de portafolio estático.

```text
portafolio/
├── index.html
├── README.md
├── css/              # (si aplica) hojas de estilo
│   └── styles.css
├── assets/           # (si aplica) recursos estáticos
│   ├── img/
│   └── icons/
└── js/               # (opcional, si en el futuro agregas interactividad)
```

---

## Arquitectura

### Vista general
```text
Navegador
   │
   ├── index.html (estructura)
   ├── css/*.css   (estilos)
   └── assets/*    (imágenes/íconos/fuentes)
```

### Flujo de renderizado
```text
HTML + CSS -> Render en navegador -> Interfaz final del portafolio
```

---

## Seguridad y privacidad

Este proyecto evita exponer información sensible.  
Recomendaciones para mantenerlo seguro:

- No incluir credenciales, tokens ni claves API en el repositorio.
- No publicar datos personales sensibles.
- Si se agregan formularios con backend, usar variables de entorno para secretos.

---

## 📌 Roadmap (mejoras futuras)

- [ ] Modo oscuro.
- [ ] Filtros por tecnología en la sección de proyectos.
- [ ] Animaciones suaves de entrada (sin afectar performance).
- [ ] Optimización SEO (meta tags, Open Graph, favicon completo).
- [ ] Publicación/actualización automática con GitHub Pages.

---

## Autor

**miguelrodrica**  
Repositorio: [miguelrodrica/portafolio](https://github.com/miguelrodrica/portafolio)
