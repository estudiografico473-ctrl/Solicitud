# DesignHub — Plataforma de Solicitudes de Diseño

Sitio web estático de dos páginas para gestionar solicitudes de trabajo de diseño.

## Páginas

- **`index.html`** — Formulario de nueva solicitud
- **`estado.html`** — Panel de control con estado de todos los pedidos

## Características

- Formulario completo con validación
- Tabla de pedidos con colores por prioridad (🔴 Urgente / 🟠 Prioritario / 🟡 Normal)
- Estado por fila (Sin Iniciar / En Proceso / En corrección / Corregido / TERMINADO)
- Fila verde cuando el estado es TERMINADO
- Modal para ver el detalle completo del diseño
- Campo de link externo por fila
- Eliminación con confirmación
- Datos guardados en `localStorage` (persisten entre sesiones en el mismo navegador)

## Cómo usar

1. Abrí `index.html` en el navegador (o subilo a GitHub Pages)
2. Completá el formulario y presioná **Enviar Solicitud**
3. Serás redirigido automáticamente a `estado.html`
4. Desde ahí podés cambiar el estado, agregar links y eliminar filas

## GitHub Pages

1. Subí ambos archivos `.html` a un repositorio de GitHub
2. En **Settings → Pages**, seleccioná la rama `main` y la carpeta raíz `/`
3. Tu sitio estará disponible en `https://tuusuario.github.io/nombre-del-repo/`

> Los datos se guardan en el navegador local del usuario (localStorage). No requiere backend ni base de datos.
