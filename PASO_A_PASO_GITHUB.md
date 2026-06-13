# Paso a paso para publicar en GitHub Pages

## 1. Crear cuenta o iniciar sesion

Entra a https://github.com.

Si no tienes cuenta, crea una. Si ya tienes cuenta, inicia sesion.

## 2. Crear un repositorio nuevo

1. Haz clic en el boton `+` arriba a la derecha.
2. Elige `New repository`.
3. Nombre sugerido: `anteproyecto-3-pisos-la-ceja`.
4. Marca `Public`.
5. No es necesario agregar README desde GitHub, porque esta carpeta ya incluye uno.
6. Haz clic en `Create repository`.

## 3. Subir los archivos

En la pantalla del repositorio nuevo:

1. Haz clic en `uploading an existing file`.
2. Arrastra el contenido de esta carpeta, no la carpeta completa:
   - `index.html`
   - `README.md`
   - `PASO_A_PASO_GITHUB.md`
   - `.nojekyll`
   - carpeta `vendor`
3. Abajo, en `Commit changes`, deja el mensaje por defecto o escribe:
   `Publicar modelo 3D inicial`.
4. Haz clic en `Commit changes`.

## 4. Activar GitHub Pages

1. En tu repositorio, abre `Settings`.
2. En el menu izquierdo, entra a `Pages`.
3. En `Build and deployment`, busca `Source`.
4. Selecciona `Deploy from a branch`.
5. En `Branch`, selecciona:
   - rama: `main`
   - carpeta: `/ (root)`
6. Haz clic en `Save`.

## 5. Abrir el link publico

GitHub puede tardar 1 a 3 minutos.

Luego vuelve a `Settings > Pages`. Alli aparecera un enlace parecido a:

```text
https://TU-USUARIO.github.io/anteproyecto-3-pisos-la-ceja/
```

Ese es el enlace que puedes compartir con terceros.

## 6. Si actualizas el modelo despues

Para publicar una nueva version:

1. Entra al repositorio.
2. Abre `index.html`.
3. Haz clic en el icono de editar o usa `Add file > Upload files`.
4. Sube los archivos nuevos.
5. Haz `Commit changes`.

GitHub Pages actualizara el enlace automaticamente.
