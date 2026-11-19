# Cases Phone Chivacoa · Sistema del negocio

Sistema web de ventas, inventario, clientes (CRM), créditos, cuentas y catálogo para clientes.
Hecho solo con HTML, CSS y JavaScript: todo está en `index.html`.

## Publicarlo con GitHub Pages
1. Sube `index.html` a tu repositorio (rama `main`).
2. En el repositorio entra a **Settings → Pages**.
3. En **Source** elige **Deploy from a branch**, rama **main** y carpeta **/ (root)**. Guarda.
4. En 1 o 2 minutos tu sistema queda en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

## Primer uso
- Al abrir el enlace, toca **Usar en este navegador (sin nube)**. Los datos se guardan en ese navegador.
- Para ver tus datos desde varios dispositivos o con vendedores, conecta Firebase en **Configuración → Conectar a la nube**.
- En **Configuración** escribe el WhatsApp del negocio y, cuando quieras empezar con datos reales, toca **Borrar datos de ejemplo**.
- Descarga una **copia de seguridad** cada semana (Configuración → Copia de seguridad).

## Tasa del dólar
La tasa oficial del BCV se actualiza sola al abrir el sistema y cada 20 minutos (necesita internet).

## Catálogo para clientes
En **Pedidos web → Descargar catálogo** se genera un `index.html` con tus productos. Para publicarlo,
crea otro repositorio (por ejemplo `catalogo`) y súbelo igual que este. Cada vez que cambies productos o
precios, descárgalo de nuevo y reemplázalo (o conecta Firebase para que se actualice solo).
