## Creando proyecto!
- eliminar los archivos ?
1. todo dentro del div en APP.JSX y los import
2. APP.JS
3. logo.svg
4. index.css eliminar todo

5. instalar tailwindcss
 - npm i -D tailwindcss postcss autoprefixer
6. crear archivos ( No se modifican, los necesita tailwindcss )
 - npx tailwindcss init -p
 - ( tailwind.config.js y postcss.config.js )
7. agregar al index.css
 - @tailwind base;
 - @tailwind components;
 - @tailwind utilities;

8. agregar index y componentes a tailwind.config.js
 - content: ["./index.html", "./src/**/*.jsx"]

###JSX
-Reglas
1- debe de tener etiqueta de sierre
2- cada componente debe tener un return
3- solo un elemento en el nivel mas alto

### Notas
<>
fragment
</>

- se pueden crear function y variables solo antes del return
- dentro del return se puede colocar llaves { Lo que este dentro es codigo JavaScript }
- no se usan if, solo ternarios
- un componente es una función
- una ves creado el componente se debe importar al principal ( APP.JSX )
- las clases en jsx se escribe className

### Codigo
ternario { edad >= 18 ? ' Eres mayor de edad ' : 'No eres Mayor de edad' }