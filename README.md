# EC. Workflow Lab — Laboratorio educativo

Sitio interactivo, responsive y completamente estático para comprender el recorrido de datos en un flujo de n8n:

**Webhook → Edit Fields → Google Sheets → Gmail**

## Cómo usarlo
1. Abrí `index.html` en Chrome, Edge o Firefox (doble clic).
2. Modificá nombre, email y mensaje; ejecutá los nodos uno por uno o presioná **Ejecutar todo**.
3. Tocá cada nodo y examiná sus pestañas INPUT/OUTPUT.
4. Cambiá a «3 solicitudes» para ver varios ítems.
5. Tocá «Provocar un error» y fijate dónde falla el flujo.
6. Completá el desafío final.

## Límites de la simulación
- **No se conecta a n8n, Gmail ni Google Sheets**. El laboratorio **no envía correos** ni modifica planillas reales.
- Los datos se procesan localmente en el navegador y desaparecen al recargar.
- La estructura es una adaptación didáctica; las respuestas exactas de nodos reales dependen de sus configuraciones y APIs.
- Para una versión real, hace falta diseñar autenticación, validación antes de persistir, permisos, control de duplicados, registros de error y tratamiento de fallas parciales.

## Publicar en GitHub Pages
Subí `index.html` a la raíz de un repositorio y activá Settings → Pages → Deploy from a branch. No requiere npm, Python, credenciales ni backend.

## Referencias oficiales
- [n8n Docs](https://docs.n8n.io/)
- [Webhook](https://docs.n8n.io/integrations/builtin/core-nodes/n8n-nodes-base.webhook/)
- [Edit Fields (Set)](https://docs.n8n.io/integrations/builtin/core-nodes/n8n-nodes-base.set/)
- [Estructura de ítems](https://docs.n8n.io/data/data-structure/)
- [Gmail send](https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.gmail/message-operations/)

**EC. Creative Coding Lab** · Proyecto educativo independiente, no afiliado a n8n.
