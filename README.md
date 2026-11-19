# Sweet Dog – Clínica Veterinaria (Landing Page)

Landing page informativa en un **único archivo HTML** para **Sweet Dog Clínica Veterinaria** (Asunción, Paraguay), diseñada con enfoque responsive (web y mobile), optimizada para SEO técnico en Google y lista para despliegue estático sin pasos de compilación.

## Características principales

- **Archivo único (`index.html`)**: HTML5 semántico con estilos de Tailwind CSS vía CDN, tipografías de Google Fonts (`Nunito` e `Inter`), íconos Lucide y SVG personalizados, y JavaScript vanilla liviano.
- **SEO y rendimiento**:
  - Metadatos completos (`description`, `robots`, `theme-color`), etiquetas **Open Graph** y **Twitter Card**.
  - Datos estructurados **JSON-LD (`Schema.org / VeterinaryCare`)** con dirección, teléfono, mapa, redes sociales y horarios.
  - Favicon (`icono.ico`), atributos `width`/`height` en imágenes, `fetchpriority="high"` en el Hero y `loading="lazy"` + `decoding="async"` en imágenes secundarias.
- **Accesibilidad y experiencia móvil**:
  - Navegación con `scroll-behavior: smooth`, etiquetas `aria-*` y soporte para `prefers-reduced-motion`.
  - Efectos `hover` replicados para pantallas táctiles (`active:` y feedback táctil en tarjetas).

## Secciones incluidas

1. **Header**: Barra superior fija con fondo azul institucional (`#1E3A8A`), tipografía blanca y logo circular (`Logo.png`).
2. **Hero**: Mensaje principal, acceso directo a servicios e indicadores clave (`+5.000` pacientes felices, `9` especialidades, calificación `4,9`).
3. **Alianza Estratégica (Sweet Dog × Medical Pröpet)**: Información de cobertura directa sin desembolso, enlace telefónico (`+595 976 222 300`) con alternativa comentada hacia Instagram y afiche oficial (`alianza.png`).
4. **Nuestros Servicios (Bento Grid)**:
   - Consultas Médicas & Especialidades (incluye Neurología, Vacunación y aviso de próximo Hospital 24/7)
   - Análisis Clínicos & Diagnóstico (`< 2 h`)
   - Peluquería & Estética Canina
   - Guardería & Transporte Especializado
   - Odontología
   - Oftalmología
5. **Pet Shop & Farmacia**: Alimentos, accesorios y farmacia veterinaria presencial con enlace directo a la sección de ubicación.
6. **Nuestro Equipo (Carrusel responsive)**:
   - Muestra **3 integrantes en web** y **1 en mobile**, con desplazamiento infinito automático de derecha a izquierda (cada `1.75 s`), controles manuales, indicadores y soporte táctil (swipe).
   - Integrantes: Nayeli Mendoza (Recepcionista), Patricia Jara (Doctora y Veterinaria), José Vera (Peluquero y Bañador), Crescencia Samaniego (Peluquera y Bañadora) y Hector Ortiz (Chofer).
7. **Ubicación (Map)**: Vista previa clickeable dirigida a Google Maps (`Av. Perú 235, Asunción`), dirección completa y horarios de atención.
8. **Footer y WhatsApp flotante**: Enlaces internos, redes sociales, teléfono directo y botón flotante de WhatsApp.

## Estructura de archivos

```text
.
├── index.html
├── icono.ico
├── Logo.png
├── hero.png
├── alianza.png
├── shop.png
├── map.png
├── NayeliMendoza.jpeg
├── PatriciaJara.jpeg
├── JoseVera.jpeg
├── CrescenciaSamaniego.jpeg
└── HectorOrtiz.jpeg
```

> **Importante:** Respeta las mayúsculas y extensiones exactas de los archivos al subir el proyecto a servidores Linux (por ejemplo, GitHub Pages, Netlify o cPanel).

## Información de contacto y horarios

- **Dirección:** Av. Perú 235 entre Río de Janeiro y José Berges, Asunción, Paraguay ([Ver en Google Maps](https://maps.google.com/?q=Av.+Peru+235+Asuncion+Paraguay))
- **Horarios:**
  - Lunes a Sábado: `07:30 a 17:00 hs`
  - Domingos: `08:00 a 12:00 hs`
- **Teléfono / WhatsApp:** `+595 981 550 665`
- **Instagram:** [@veterinariasweetdog](https://www.instagram.com/veterinariasweetdog)
- **Facebook:** [SweetDog.py](https://www.facebook.com/SweetDog.py)
- **Alianza Medical Pröpet:** `+595 976 222 300` *(enlace alternativo a [@medicalpropet.py](https://www.instagram.com/medicalpropet.py) comentado en el código)*

## Uso y despliegue

No requiere instalación ni proceso de build:

1. **Vista local:** Abre `index.html` directamente en cualquier navegador moderno.
2. **Publicación:** Sube todos los archivos de la carpeta a cualquier hosting estático (GitHub Pages, Netlify, Vercel o servidor web tradicional).

---

© 2026 Sweet Dog Clínica Veterinaria. Todos los derechos reservados.
