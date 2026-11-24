# 🖼️ Marcos y cuadros — Demo Oficial de Portafolio

> **"Arte que decora tus espacios"** — Plataforma web interactiva de catálogo 3D, estudio de personalización en tiempo real y gestión comercial desarrollada para el emprendimiento **Marcos y cuadros**.

![Estado](https://img.shields.io/badge/Estado-Portfolio%20Demo-c8a96e?style=for-the-badge)
![Stack](https://img.shields.io/badge/Stack-HTML5%20%7C%20CSS3%203D%20%7C%20JS%20ES6%2B-d9232e?style=for-the-badge)
![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages%20Ready-10b981?style=for-the-badge)

---

## ✨ Características Principales

1. **Exhibición Interactiva 3D:**
   - Galería con inclinación 3D reactiva al cursor, reflejo especular tipo vidrio, **Escenario Giratorio** y selector de iluminación de pared (*Pared Cálida Real*, *Estudio Oscuro*, *Luz Neón Roja*).
   - Visor *Lightbox* en alta resolución para inspeccionar cada cuadro enmarcado.
2. **Estudio Personalizador en Vivo:**
   - Carga de imágenes propias (`JPG`, `PNG`, `WEBP`) con validación de tamaño y firma binaria (*Magic Bytes*).
   - Vista previa instantánea dentro de un marco físico simulado de **21×30 cm** con doble modo: **Póster Completo** o **Estilo Álbum Spotify** (artista, álbum y *tracklist* editables).
3. **Motor de Promociones & Checkout:**
   - Cálculo automático de promociones oficiales: **1 Cuadro × $13.000** y **¡PROMO! 2 Cuadros × $20.000**.
   - Medios de pago configurados para **Efectivo** (entrega presencial / **Instituto Santo Cristo**) y **Transferencia** con copiado rápido del alias **`Joaco.chocobar`**.
4. **Registro de Ventas & Exportación a Excel:**
   - Persistencia local en `localStorage` con datos iniciales de demostración (`DEMO`), métricas KPI en vivo y exportación en un clic a **Excel (`.CSV` UTF-8 con BOM)** + código listo para sincronizar con **Google Sheets**.
5. **Seguridad, Marcos Legales y Control de Bugs:**
   - Sanitización anti-XSS (`escapeHTML`), encabezados `Content-Security-Policy`, pestañas legales (*Términos, Ley 25.326, Derechos de Imagen y Ley 24.240*) y módulo de autodiagnóstico y reporte de errores.

---

## 📁 Estructura del Repositorio

```text
marcos-y-cuadros-demo/
├── index.html                              # Aplicación web completa (HTML + CSS + JS)
├── README.md                               # Documentación del proyecto para GitHub
├── LICENSE                                 # Licencia MIT
├── .gitignore                              # Archivos ignorados por Git
└── assets/                                 # Imágenes exactas optimizadas para web
    ├── logo-marcos-y-cuadros.jpg           # Logo oficial
    ├── cuadro-goku-disciplina.jpg          # Cuadro "Disciplina Crea Libertad"
    ├── cuadro-paisaje-torii.jpg            # Cuadro paisaje japonés Portal Torii
    ├── cuadro-naruto-sasuke.jpg            # Cuadro Naruto & Sasuke Luna Roja
    ├── cuadro-ysya-after.jpg               # Cuadro estilo álbum YSY A
    ├── promo-bad-bunny-verano.jpg          # Flyer promo 1×$13.000 / 2×$20.000
    └── flyer-instituto-santo-cristo.jpg    # Flyer presentación Instituto Santo Cristo
```

---

## 🚀 Cómo subirlo a tu GitHub y activarlo en GitHub Pages

1. Creá un nuevo repositorio público en GitHub llamado `marcos-y-cuadros-demo`.
2. Subí todos los archivos de esta carpeta (asegurate de incluir la carpeta `assets/` junto con `index.html`) o ejecutá en tu terminal:
   ```bash
   git init
   git add .
   git commit -m "feat: demo interactiva Marcos y cuadros para portafolio"
   git branch -M main
   git remote add origin https://github.com/TU-USUARIO/marcos-y-cuadros-demo.git
   git push -u origin main
   ```
3. En GitHub, entrá a **Settings → Pages → Build and deployment**, seleccioná **Deploy from a branch**, elegí la rama `main` y carpeta `/ (root)`, y hacé clic en **Save**.
4. En menos de 1 minuto tu demo quedará publicada en `https://TU-USUARIO.github.io/marcos-y-cuadros-demo/`.
