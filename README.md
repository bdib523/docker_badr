# docker_badr

## Instalación de Docker

En esta práctica voy a instalar Docker en Windows y crear una cuenta en Docker Hub.

### 1. Descargar Docker

Entramos en la página oficial:

https://www.docker.com/products/docker-desktop/
<img width="1588" height="268" alt="image" src="https://github.com/user-attachments/assets/723d6194-8617-4613-aae4-15f5589c7f7d" />
Descargamos Docker Desktop para Windows e instalamos el programa siguiendo los pasos del instalador.

### 2. Crear una cuenta en Docker Hub

Entramos en la siguiente página:

https://hub.docker.com/

Pulsamos en **Sign up**, introducimos nuestro correo electrónico, elegimos un nombre de usuario y creamos una contraseña.
<img width="1902" height="63" alt="image" src="https://github.com/user-attachments/assets/2d7444fa-68cd-42fe-90ea-91079a14bbec" />
<img width="455" height="647" alt="image" src="https://github.com/user-attachments/assets/fccd5b63-7af4-4f6c-b321-0d781999480f" />

Después verificamos el correo e iniciamos sesión.

### 3. Comprobar la instalación

Abrimos PowerShell en Administrador y escribimos:

```bash
docker --version
```
<img width="464" height="116" alt="image" src="https://github.com/user-attachments/assets/5ca5470f-4037-4a55-bd8e-a4eb401e3564" />


Este comando sirve para comprobar la versión instalada.

Después ejecutamos:

```bash
docker run hello-world
```
<img width="715" height="434" alt="image" src="https://github.com/user-attachments/assets/4a0a6d68-9004-4477-aea5-bd27ed24ed5f" />


Este comando descarga una imagen de prueba y ejecuta un contenedor para comprobar que Docker funciona.

### 5. Conclusión

Con esta práctica he aprendido a instalar Docker Desktop y crear una cuenta en Docker Hub.

### Enlaces utilizados

- https://www.docker.com/
- https://hub.docker.com/
- https://docs.docker.com/
