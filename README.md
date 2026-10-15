# Taller de mascotas y sprites

Aplicación estática para dibujar sprites, importar hojas, crear movimientos y probar una mascota animada. Los dibujos se procesan en el navegador; la mascota se guarda descargando un archivo JSON.

## Publicación en GitHub Pages

Cuenta prevista: matiasprietoc. Repositorio propuesto: mascotas-sprites.

1. Subir los archivos de este paquete directamente a la raíz del repositorio.
2. En Settings > Pages, elegir Deploy from a branch, main y /(root).
3. Configurar Custom domain como matprietolab.cl y guardar.
4. Configurar los registros DNS que aparecen abajo, después de asociar el dominio en Pages.
5. Activar Enforce HTTPS cuando esté disponible y comprobar la página publicada.

La presencia de estos archivos no activa Pages por sí sola. Hay que completar la configuración del repositorio.

## DNS para matprietolab.cl

NIC Chile registra el dominio y permite configurar los servidores de nombres. Los registros A y CNAME se crean en un servicio DNS primario. GitHub Pages aloja la aplicación, pero no administra los servidores DNS del dominio.

| Tipo | Nombre | Valor |
| --- | --- | --- |
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | matiasprietoc.github.io |

Los servidores de nombres para NIC Chile deben ser los que asigne tu proveedor DNS; no son las direcciones IP de GitHub.

Fuentes:
- https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site
- https://www.nic.cl/ayuda/faq/ins-05.html

## Archivos

- index.html: aplicación completa, sin instalación ni compilación.
- CNAME: dominio solicitado.
- .nojekyll: sirve los archivos directamente.
- dns.csv: registros para el proveedor DNS.

Sprites de ejemplo: JoshR691, según los créditos de la hoja aportada. Conserva la atribución al reutilizarlos.
