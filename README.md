# Landings de demostración — Reto "Tu primer cobro con IA"

Tres landings genéricas + una página "hub" que las presenta juntas.
Cada una es **un solo archivo `index.html`** sin dependencias externas: se abre
con doble clic, se despliega arrastrando la carpeta y funciona sin internet.

## 🌐 En vivo (GitHub Pages)

- **Portafolio (hub):** https://gabrielsalazar8486.github.io/demos-ia-negocios/
- **Servicio:** https://gabrielsalazar8486.github.io/demos-ia-negocios/servicio/
- **Tienda:** https://gabrielsalazar8486.github.io/demos-ia-negocios/tienda/
- **Restaurante:** https://gabrielsalazar8486.github.io/demos-ia-negocios/restaurante/

Para actualizar el sitio: edita, `git commit` y `git push`. Pages redespliega solo
en ~1 min.

| Carpeta | Rubro | Negocio de ejemplo | El chat demuestra… |
|---|---|---|---|
| `servicio/` | Servicios con cita | Terramar Propiedades (inmobiliaria) | Agenda visitas solo |
| `tienda/` | Comercio / retail | Voltta Tecnología | Cotiza y toma pedidos |
| `restaurante/` | Comida | Brasa · Cocina de Leña | Reserva mesa y toma pedidos |

Las tres traen un **widget de "Asistente IA" flotante** (abajo a la derecha)
que responde en vivo. Eso es lo que vendes: ábrelo en la demo y deja que el
cliente lo pruebe.

---

## 1. Personaliza en 3 minutos (busca y reemplaza)

Abre el `index.html` con cualquier editor y reemplaza:

1. **Tu número de WhatsApp** — busca `584121156645` y cámbialo por el tuyo en
   formato internacional sin `+` ni `0` inicial:
   `0412 115 6645` → `584121156645`.
   Aparece en los botones y en la nota de pie ("Sitio de demostración…").

2. **Nombre del negocio** — busca `Terramar` / `Voltta` / `Brasa` y ponle el
   del cliente (o déjalo genérico para la demo).

3. **Textos, precios y datos** — cambia productos, platos, propiedades,
   dirección y horarios directamente en el HTML.

4. **Guion del asistente** — al final del archivo, en `var CONFIG = {…}`, están
   los mensajes del chat. Edita `welcome`, `quicks` (botones rápidos) y `rules`
   (palabra clave → respuesta) para el negocio real.

> **Fotos reales:** las imágenes son ilustraciones/gradientes para que se vea
> terminada sin depender de fotos. Para la versión de pago del cliente,
> reemplaza cada bloque `<div class="media …">…</div>` por
> `<img src="foto.jpg" alt="…">` con las fotos del negocio. Mejora enorme.

---

## 2. Despliega gratis (para darle su propio link/dominio)

**Opción rápida — Netlify Drop** (sin cuenta técnica):
1. Entra a https://app.netlify.com/drop
2. Arrastra la carpeta (`servicio/`, `tienda/` o `restaurante/`).
3. Listo: obtienes un link `https://algo.netlify.app` al instante.

**Opción Vercel** (desde la terminal):
```bash
npm i -g vercel
cd servicio      # o tienda / restaurante
vercel           # sigue el asistente; te da la URL
```

Para dominio propio (ej. `negocio.com`) se conecta desde el panel de
Netlify/Vercel → Domains. Ese costo (dominio + hosting) es justo lo que el reto
te dice que cubras con el primer cobro.

---

## 3. Cómo usarlas en el reto

- **D2 — abre puertas:** manda el link (o una captura del chat funcionando) por
  WhatsApp a tu Lista de 20. "Mira, algo así te armo para [su negocio]".
- **En la reunión:** comparte pantalla, abre el chat y deja que el cliente lo
  pruebe. Ahí se vende solo.
- **Al cerrar:** personaliza con su nombre, sus productos y sus fotos, y eso ya
  es el entregable de pago.
