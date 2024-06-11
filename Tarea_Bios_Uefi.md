# Tarea: BIOS vs UEFI

# Ejercicio 1

Entra en la BIOS o arranque de tu ordenador, ya sea el de clase o en tu casa, averigua cual es la tecl
a que nos permite en el arranque entrar en este sistema. Describe el proceso que has seguido y adjunta una captura de pantalla del resultado (puedes utilizar la cámara de tu móvil).

## Respuesta:

**Tecla Que Nos Permiten Ingresar:** "F2", "F10", "F12", "Esc" o "Supr", ami me funciono la tecla "Supr"...

![image](https://github.com/tizixpk/Lab7Bios/assets/170434202/9d3d7e47-865b-4c4f-bde1-c03cc35dc4f8)


# Ejercicio 2

Siguiendo los pasos que hemos visto en clase, obtén la información de tu sistema operativo acerca de si ha arrancado sobre una BIOS o sobre UEFI.

 ## Respuesta:
 Mi computadora me indica que ha arrancado sobre UEFI por 2 razones: Por la foto adjuntada abajos nos indica q se trata de UEFI, y ademas Presionas las Teclas Windows + R y pones "msinfo32" y te aparecera el modelo de tu Bios
 
![image](https://github.com/tizixpk/Lab7Bios/assets/170434202/381be99b-6cc1-4736-a138-9670aa249853)
![image](https://github.com/tizixpk/Lab7Bios/assets/170434202/b433d46d-bc10-498c-9cff-3ff4889511fe)

# Ejercicio 3

En GNU/LinuX, si hemos arrancado sobre UEFI existirá un directorio que contendrá información acerca de nuestra UEFI. ¿Cúal es? En caso de que exista...¿Cual es el contenido del fichero *systab*?

---
## Respuesta:

### UEFI en GNU/Linux

En sistemas GNU/Linux, el firmware UEFI (Interfaz de Firmware Extensible Unificado) desempeña un papel crucial en el proceso de arranque. Cuando el sistema se inicia con UEFI, se crea automáticamente un directorio específico que proporciona acceso a información importante sobre la configuración de la UEFI.

### Directorio `/sys/firmware/efi`

El directorio `/sys/firmware/efi` contiene datos relacionados con la UEFI. Esta estructura de archivos proporciona una interfaz para acceder a detalles cruciales sobre la configuración y el estado de la UEFI.

#### Contenido Significativo:

- **efivars**: Almacena variables de entorno EFI.
- **fw_vendor**: Proporciona detalles sobre el fabricante del firmware EFI.
- **efi_runtime**: Contiene información sobre la configuración de tiempo de ejecución EFI.
- **fw_version**: Ofrece detalles sobre la versión del firmware EFI.

Es fundamental destacar que no existe un archivo llamado `systab` dentro de este directorio. Parece ser un término incorrecto o una confusión.

### Confirmación del Arranque sobre UEFI

La presencia del directorio `/sys/firmware/efi` confirma que el sistema está arrancando sobre UEFI en lugar del tradicional BIOS. Al explorar este directorio y su contenido, los usuarios pueden obtener información valiosa sobre la configuración y el funcionamiento de la UEFI en su sistema.

---

# Ejercicio 4
Obtener información de cual es la temperatura del Microprocesador en tu BIOS/UEFI. Adjunta una captura/foto.

## Respuesta:

