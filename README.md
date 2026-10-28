# Cuenta Clara

PWA privada y minimalista para recordar compras con tarjeta y fechas de pago.

## Publicar en GitHub Pages
1. Crea un repositorio en GitHub y sube el contenido de esta carpeta.
2. En el repositorio, abre **Settings → Pages**.
3. En **Build and deployment**, selecciona **Deploy from a branch**, elige `main` y `/ (root)`, y guarda.
4. Cuando GitHub Pages publique el sitio, abre su URL con Safari en el iPhone y elige **Compartir → Añadir a pantalla de inicio**.

Pages sirve la app por HTTPS, necesario para cifrado y modo instalable.

## Privacidad y recordatorios
Los datos se guardan en el navegador de este dispositivo y se cifran con AES-GCM usando una clave derivada del PIN. No se envían a un servidor. Si olvidas el PIN, los datos cifrados no se pueden recuperar. Usa **Exportar respaldo** y guarda el archivo en un lugar seguro. Esta app muestra pagos próximos o vencidos cuando se abre; una PWA estática no garantiza notificaciones cuando está cerrada.


