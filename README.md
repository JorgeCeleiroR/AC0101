# Cómo crear mi portfolio con GitHub Pages

## Paso 1. Crear el repositorio

1. Entra en [github.com](https://github.com/) e inicia sesión.
2. Pulsa el botón **+** (arriba a la derecha) y elige **New repository**.
3. En *Repository name* escribe exactamente: `JorgeCeleiroR.github.io`
4. Marca el repositorio como **Public**.
5. Marca la casilla **Add a README file**.
6. Pulsa **Create repository**.

> El nombre tiene que ser exactamente `tuUsuario.github.io`. Si no, la página no se publica en esa dirección.

## Paso 2. Crear la página

1. Dentro del repositorio, pulsa **Add file → Create new file**.
2. En el nombre del archivo escribe: `index.html`
3. Pega este contenido en el editor:

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Jorge Celeiro Rodríguez</title>
</head>
<body>
  <h1>Jorge Celeiro Rodríguez</h1>
  <p>Estudiante de 2.º de Desarrollo de Aplicaciones Web.</p>

  <p><a href="https://github.com/JorgeCeleiroR">Mi perfil de GitHub</a></p>

  <h2>Mis prácticas</h2>
  <ul>
    <li><a href="https://github.com/JorgeCeleiroR/REPOSITORIO-1">Práctica 1</a></li>
    <li><a href="https://github.com/JorgeCeleiroR/REPOSITORIO-2">Práctica 2</a></li>
  </ul>

  <p><a href="https://JorgeCeleiroR.github.io/curriculum">Mi currículo</a></p>
</body>
</html>
```

4. Pulsa **Commit changes...** (botón verde arriba a la derecha) y confirma con **Commit changes**.

## Paso 3. Activar GitHub Pages

1. En el repositorio, pulsa **Settings**.
2. En el menú de la izquierda, pulsa **Pages**.
3. En *Source* elige **Deploy from a branch**.
4. En *Branch* elige **main** y la carpeta **/ (root)**.
5. Pulsa **Save**.

## Paso 4. Comprobar que funciona

1. Espera uno o dos minutos.
2. Abre `https://JorgeCeleiroR.github.io` en el navegador.
3. Si ves tu página, ya está publicada.
