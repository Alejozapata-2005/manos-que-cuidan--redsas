# Red de Asistencia — Manos que Cuidan (REDSAS)

Este repositorio contiene el sitio estático del proyecto "Red de Asistencia - Manos que Cuidan". Está estructurado en HTML, CSS, JS e imágenes para soportar las vistas de ADMIN, CLIENTE, USUARIO, LOGIN y una sección pública.

## Descripción

Una plataforma orientada a ofrecer servicios de cuidado y asistencia a adultos mayores. Incluye paneles para administradores, clientes y usuarios, así como páginas públicas para información y contacto.

## Estructura del proyecto

Raíz del proyecto:

```
index.html
redsas/
  ADMIN/
    CSS/
    HTML/
    JS/
  CLIENTE/
    CSS/
    HTML/
    JS/
  IMG/
  LOGIN/
    login.html
    registro.html
    style.css
  PUBLICO/
    css/
    HTML/
    JS/
  USUARIO/
    CSS/
    HTML/
    JS/
```

> Nota: Asegúrate de que las rutas relativas en `index.html` y en otras páginas apunten correctamente a estas carpetas.

## Cómo ver el proyecto localmente

1. Abrir `index.html` en tu navegador (método rápido) — abrir el archivo directamente funciona para HTML/CSS estático, pero algunas funcionalidades JavaScript o llamadas relativas pueden requerir un servidor local.

2. Servir con un servidor local (recomendado):

- Con Python 3:

```powershell
python -m http.server 8000
```

- Con Node.js (http-server):

```powershell
npx http-server -p 8000
```

Luego abre `http://localhost:8000` en tu navegador.

## Despliegue en GitHub Pages

1. Subir al repo remoto en GitHub (ya configurado):

```powershell
git add . ; git commit -m "Add README" ; git push
```

2. En la configuración del repositorio en GitHub, activar GitHub Pages seleccionando la rama `main` y la carpeta `/ (root)`.

3. La página quedará disponible en `https://<usuario>.github.io/<repo>/` (puede tardar unos minutos).

## Buenas prácticas de rutas

- Usar rutas relativas sin la barra inicial `/` para evitar problemas en GitHub Pages. Ejemplo: `redsas/IMG/favicon-32x32.png` en lugar de `/redsas/IMG/...`.
- Verificar referencias a scripts y hojas de estilo desde cada página, p. ej. `redsas/PUBLICO/JS/script.js`.

## Licencia

Este proyecto se entrega sin licencia explícita. Si deseas agregar una, incluye un archivo `LICENSE` en la raíz.

## Contacto

Para preguntas o colaboración: contacto@redsas.com.co
