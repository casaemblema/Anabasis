# Anabasis — Landing Page (GitHub Pages)

Landing page oficial de **Anabasis · Water Engineering**, diseñada como sitio estático para GitHub Pages.

El objetivo del sitio es:
- Explicar de forma general qué hace Anabasis
- Priorizar contacto por **WhatsApp Business**
- Ofrecer una alternativa profesional mediante **Google Forms embebido**
- Mantener una estética blanca, sobria y de ingeniería (no “spa”)

---

## 📁 Estructura del proyecto

```
/
├── index.html        # Archivo principal del sitio
├── logo.png          # Logo de Anabasis (recomendado)
├── README.md         # Este archivo
```

> Todo está pensado para funcionar **sin backend**, 100% estático.

---

## 🖼️ Logo (MUY IMPORTANTE)

### Requisitos del archivo
- Nombre: `logo.png`
- Formato: PNG
- Proporción: **cuadrado (1:1)**
- Tamaño recomendado: **1024 × 1024 px**
- Fondo: transparente
- Contenido: símbolo o monograma (sin slogan)

El sitio:
- NO recorta
- NO estira
- NO deforma el logo

Si `logo.png` no existe, el sitio muestra una **“A”** como fallback.

---

## 📲 WhatsApp Business

El sitio utiliza WhatsApp como **canal principal**.

Configuración actual:
- Número: `+52 81 8461 3223`
- Enlace: `https://wa.me/528184613223`

Incluye:
- Botón principal en header y hero
- Mini-form que arma el mensaje automáticamente
- **Botón flotante**:
  - Visible en desktop (discreto)
  - Más prominente en móvil

Si el número está configurado como **WhatsApp Business**, el usuario lo verá automáticamente como cuenta empresarial.

---

## 📝 Google Forms (alternativa sin WhatsApp)

El formulario está **embebido** dentro del sitio mediante `<iframe>`.

Ventajas:
- No requiere backend
- Registra leads en Google Sheets
- Envía notificaciones por correo
- Ideal para clientes que no usan WhatsApp

Formulario actual:
```
https://docs.google.com/forms/d/e/1FAIpQLSff-kROqKWtc8zPONj9VKDdXb6N5QEP2SPZwnwzE4zTdN6CrQ/viewform
```

> El iframe es responsive y ajusta altura para desktop y móvil.

---

## ✨ Micro‑animaciones

Incluye animaciones sutiles:
- Fade + slide al hacer scroll
- Hover ligero en tarjetas y botones
- Transiciones suaves (sin exagerar)

Respeta accesibilidad:
- Si el usuario tiene activado **“reducir movimiento”**, las animaciones se desactivan automáticamente.

---

## 🌐 Dominio y despliegue

Pensado para:
- GitHub Pages
- Dominio propio: `anabasis.mx`

### Publicación en GitHub Pages
1. Subir `index.html` y `logo.png` al repositorio
2. Activar GitHub Pages desde:
   - Settings → Pages
3. Seleccionar rama y carpeta raíz (`/`)

### Dominio personalizado
Cuando lo necesites, configura los DNS de `anabasis.mx` apuntando a GitHub Pages (A / CNAME).

---

## 🛠️ Tecnologías usadas

- HTML5
- CSS3 (variables, grid, media queries)
- JavaScript vanilla
- Google Forms
- WhatsApp Business

Sin frameworks. Sin dependencias externas. Máxima estabilidad.

---

## 📌 Notas finales

Este sitio está pensado como:
- **landing inicial profesional**
- base para crecer después
- punto único de contacto comercial

No promete de más, no encierra el negocio en un nicho prematuro y transmite **ingeniería, claridad y confianza**.

---

© Anabasis — Water Engineering
