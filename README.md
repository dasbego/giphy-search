# giphy-search
Make use of giphy endpoint in a Vue project

Se debe tener un formulario con
- Un input text que sea requerido
- Tenga mínimo 5 caracteres. Ver uso de min https://baianat.github.io/vee-validate/guide/rules.html#regex
- Al submitir, debe enviar las palabras introducidas al endpoint de search del api de GIPHY
- Para poder usar el API de Giphy debes crear una cuenta primero.
- Una vez creada, debes crear una App. Esto te da un API key, la cual utilizas para poder hacer requests.
https://developers.giphy.com/docs/
- Mostrar los primeros 5 resultados de la búsqueda en una lista de imágenes
**TIP: Puedes usar un elemento <img> junto con v-bind:src para mostrarlo.**

**Puedes mostrar el valor de preview_gif que se encuentra dentro de la propiedad images en la respuesta del API.**

- Al dar click en la imagen, debes abrir en una pestaña nueva el source original.

**Extra: Subir el proyecto a un repositorio de github.**
