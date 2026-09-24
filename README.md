# Freelance: páginas web y apps sencillas

## Paquetes (precios de arranque en MXN, ajustar con las primeras ventas)

| Paquete | Incluye | Precio sugerido | Entrega |
|---|---|---|---|
| **Landing básica** | 1 página, responsive, botón WhatsApp, mapa, formulario de contacto, dominio 1er año | $3,500 – $6,000 | 3–5 días |
| **Sitio de negocio** | Hasta 5 secciones, galería, SEO básico, Google Business, analítica | $8,000 – $15,000 | 1–2 semanas |
| **App web sencilla** | Login, CRUD, panel admin (citas, pedidos, inventario) | $20,000 – $45,000 | 3–6 semanas |
| **Mantenimiento** | Hosting, cambios menores al mes, respaldos, soporte | $400 – $1,200 / mes | Recurrente |

Regla: siempre cobrar **50% anticipo, 50% al entregar**. Mantenimiento se ofrece en cada venta.

## Canales para conseguir clientes
1. **Local directo**: consultorios, restaurantes, talleres, colegios particulares. WhatsApp, recomendación, grupos de Facebook de la zona.
2. **Workana**: fuerte en LATAM, pagos en USD/MXN.
3. **Upwork / Fiverr**: cobrar en dólares, más competencia.

## Stack por defecto
- Landings/sitios: HTML + CSS estático (o Astro). Hosting gratis en Netlify, Vercel o GitHub Pages.
- Apps: Next.js o similar + Supabase/Firebase. Barato y rápido de mantener.
- Dominio: Namecheap / Cloudflare / Neubox (.mx).

## Checklist de arranque
- [x] Carpeta y estructura
- [x] Portafolio base con 2 demos (escuela, consultorio)
- [x] Plantilla de cotización
- [x] Correo y GitHub en portafolio
- [ ] Llenar número de WhatsApp en `portafolio/index.html` (buscar `TODO`)
- [ ] Publicar portafolio (Netlify o GitHub Pages)
- [ ] Crear perfil en Workana con link al portafolio
- [ ] Ofrecer 2–3 landings a negocios conocidos (precio de lanzamiento a cambio de testimonio)

## Estructura
- `portafolio/` sitio personal + demos para mostrar.
- `plantillas/` cotización y mensajes de prospección.
- `clientes/` una carpeta por cliente (`clientes/<nombre>/`).
