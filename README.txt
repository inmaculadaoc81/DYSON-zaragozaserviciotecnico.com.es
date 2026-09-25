DYLAB SERVICIO TÉCNICO DYSON EN ZARAGOZA
========================================

Web de una sola página (HTML/CSS/JS estático + función serverless en Vercel)
para DyLab, servicio técnico y reparación de equipos Dyson con recogida
y entrega en Zaragoza y área metropolitana.

Dominio: https://zaragozaserviciotecnico.com.es/
Marca: DyLab Servicio Técnico Dyson en Zaragoza
Nombre corto (og:site_name): DyLab – Zaragoza
Ficha de Google: https://maps.app.goo.gl/s21RR7tYg1CMav1p9
Mapa: iframe de Google Maps de la ficha "DyLab Servicio Técnico Dyson en Zaragoza",
insertado tal cual en la sección de contacto (ancho 100% vía CSS).

DATOS DE CONTACTO
- WhatsApp: +34 649 97 01 28.
- Teléfono: +34 910 05 48 17.
- Recogida a domicilio: https://sis.redsys.es/tiendaWeb/item/NDk4OzI=
  (botón "Solicita tu recogida ahora" del hero, siempre en negro).
- Horario: lunes a viernes de 09:30 a 18:00.
- Política de privacidad: https://kelatos.com/privacy-policy/.

DIRECCIÓN: no se muestra dirección postal. La web indica "Zaragoza y área
metropolitana" y servicio de recogida y entrega; el taller está en Madrid.
Si se confirma una dirección en Zaragoza, añadirla al hero, footer y JSON-LD.

ESTRUCTURA
- index.html: toda la página (hero, ventajas, reparación rápida, confianza,
  servicios, por qué elegirnos, cómo trabajamos, contacto + mapa, FAQ, texto
  SEO, footer, cookies y JSON-LD).
- style.css: base de la plantilla.
- mobile-navigation.css, social-footer.css, cal-booking.css: ajustes compartidos.
- dylab.css: identidad visual de la marca (una sola capa, sin
  sobrescrituras en cascada).
- dylab-header-hero.css: cabecera grafito con logotipo blanco.
- dylab.js: menú móvil (se cierra al pulsar un enlace), formulario y
  preferencias de cookies (clave localStorage "dylab_cookie_preference").
- dylab-n8n-chat.js / .css: chatbot n8n con webhook compartido del grupo
  y botón de respaldo.
- api/contacto.js: envío del formulario por SMTP (variables SMTP_HOST,
  SMTP_PORT, SMTP_SECURE, SMTP_USER, SMTP_PASS y CONTACT_EMAIL en Vercel).
- img/: isotipo, patrón e ilustraciones SVG de la marca.
- robots.txt y sitemap.xml apuntan a https://zaragozaserviciotecnico.com.es/.

PALETA: pizarra técnica, grafito y plata (aspecto de laboratorio: limpio y preciso).
- Primario pizarra #334155 · oscuro #1E293B · muy oscuro #0F172A
- Grafito (cabecera, footer, cookies, tarjeta de Google) #111827
- Plata azulada #A9BDD3 para detalles sobre fondo oscuro (logotipo, destacados)
- Plata #CBD5E1 y grises en ilustraciones · fondos #F6F5F7
Excepciones: WhatsApp conserva su verde y YouTube su rojo corporativo.
En móvil (≤720px) no se muestran las ilustraciones laterales del hero.
