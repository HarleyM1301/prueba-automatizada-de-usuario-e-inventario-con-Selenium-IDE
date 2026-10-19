# Prueba funcional automatizada de FarmaciaWeb

Proyecto de Selenium IDE que comprueba el acceso del perfil Usuario al inventario y a ventas, la búsqueda de Paracetamol y la ausencia de opciones administrativas.

## Preparación

1. Inicia MySQL y Tomcat, y asegúrate de que la aplicación esté disponible en `http://localhost:8081/FarmaciaWeb`.
2. Crea una cuenta de prueba con rol `Usuario` y registra Paracetamol en el inventario.
3. Abre el archivo `.side` en Selenium IDE.
4. En los comandos `type`, reemplaza `REEMPLAZA_USUARIO` y `REEMPLAZA_CONTRASENA` por las credenciales locales de prueba. No guardes ni publiques contraseñas reales.
5. Ejecuta la prueba desde Selenium IDE.

La prueba requiere que Paracetamol exista porque verifica su búsqueda; también confirma que el perfil Usuario no ve los controles para crear ni editar medicamentos.
