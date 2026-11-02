# Cuenta Clara

PWA minimalista para registrar compras con tarjeta, controlar su estado y consultar un historial reciente.

## Acceso
La app funciona cuando se abre instalada desde el icono de inicio. Si se visita su URL en una pestaña normal, muestra instrucciones para añadirla a la pantalla de inicio de iPhone.

## Uso
- **Por pagar** muestra las compras pendientes. Al marcarlas pagadas pasan al **Historial**.
- Desde el historial puedes devolver una compra a pendientes.
- El historial conserva compras pagadas de los últimos tres meses según la fecha de compra. Las pendientes no se eliminan por antigüedad.
- La calculadora integrada permite operaciones básicas.

## Publicar en GitHub Pages
1. Crea un repositorio en GitHub y sube el contenido de esta carpeta.
2. En el repositorio, abre **Settings → Pages**.
3. En **Build and deployment**, selecciona **Deploy from a branch**, elige `main` y `/ (root)`, y guarda.
4. Abre la URL publicada en Safari y elige **Compartir → Añadir a pantalla de inicio**.

## Privacidad
Los datos se guardan cifrados en el navegador de este dispositivo con una clave derivada del PIN. No se envían a un servidor. Si olvidas el PIN, los datos cifrados no se pueden recuperar. Usa **Exportar respaldo** y guarda el archivo en un lugar seguro.
