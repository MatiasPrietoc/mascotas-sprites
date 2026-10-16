# MatPrietoLab · Laboratorio de pruebas

Laboratorio de interfaces publicado en [matprietolab.cl](https://matprietolab.cl/).

## Experimentos

- Botones, estados de carga, confirmaciones y notificaciones.
- Paleta de botones con colores preparados, selector personalizado y contraste automático.
- Contador general de clics y contador independiente de prueba.
- Área de mouse: clic izquierdo, derecho, central, doble clic, rueda, posición y arrastre.
- Acceso simulado con roles Administrador, Editor y Visitante.
- Formularios con validación local.
- Temas claro/oscuro, color, espaciado y esquinas.
- Directorio ficticio con filtros, estados y exportación CSV.
- Registro de actividad y exportación de resultados JSON.

## Uso local

Abrir `index.html` con Chrome o Edge. No requiere instalación, compilación ni bibliotecas externas.

## Cuentas de demostración

| Rol | Correo | Contraseña |
| --- | --- | --- |
| Administrador | admin@demo.test | Demo123! |
| Editor | editor@demo.test | Demo123! |
| Visitante | visita@demo.test | Demo123! |

El acceso y los permisos son simulaciones de interfaz. No existe autenticación real ni un servidor de usuarios. Usa únicamente cuentas de ejemplo.

Los ajustes visuales se guardan en el navegador. Sesiones, contadores, datos ficticios y eventos se reinician al recargar. No se almacenan contraseñas ni el contenido de formularios en el registro.

## Publicación

GitHub Pages publica la rama `main`, carpeta raíz. `CNAME` conserva el dominio `matprietolab.cl`. Para actualizar el sitio, modificar `index.html` y confirmar el cambio en `main`; no se requiere cambiar el DNS.
