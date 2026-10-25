
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIwODg3NDY2MTJdfQ==
-->

1. Preparar el repositorio en GitHub: Tener el repositorio del proyecto listo y actualizado en GitHub en su rama principal, asegurándote de que el archivo staticwebapp.config.json esté en la raíz del proyecto frontend y declarado en la lista de recursos estáticos de Angular.

2. Crear el recurso en el portal de Azure: Ingresar a la consola de Microsoft Azure, seleccionar Crear un recurso y buscar el servicio Static Web Apps (Aplicación web estática).

3. Configurar los datos básicos en Azure: Seleccionar la suscripción, el grupo de recursos, asignarle un nombre a la aplicación web y elegir el tipo de plan (por ejemplo, Gratis).

4. Vincular la cuenta de GitHub: Iniciar sesión con tu cuenta de GitHub dentro del formulario de Azure para concederle permisos de acceso al repositorio.

5. Seleccionar el repositorio y la rama: Elegir la organización, el repositorio exacto donde está alojada la Pokédex y la rama principal sobre la cual se realizarán los despliegues automáticos.

6. Definir la estructura de la aplicación (Build Details): Seleccionar Angular como preajuste de compilación (Build Preset) e indicar la ruta de la carpeta donde se encuentra el código de la aplicación y la carpeta de salida donde se guardará el resultado compilado.

7. Revisar y crear el servicio: Hacer clic en Revisar y crear y luego en Crear. Azure creará el recurso web y generará automáticamente un archivo de flujo de trabajo (workflow) con GitHub Actions en tu repositorio.

8. Monitorear el despliegue automático: Ir a la pestaña Actions en GitHub para verificar que el pipeline se ejecute, compile la aplicación y suba los archivos a Azure de forma exitosa.

9. Verificación final: Acceder a la URL pública asignada por Azure Static Web Apps para confirmar que la aplicación web esté desplegada y funcionando en la nube.