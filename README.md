# docker_badr

## Instalación de Docker

En esta práctica voy a instalar Docker en Windows y crear una cuenta en Docker Hub.

### 1. Descargar Docker

Entramos en la página oficial:

https://www.docker.com/products/docker-desktop/

Descargamos Docker Desktop para Windows e instalamos el programa siguiendo los pasos del instalador.

### 2. Crear una cuenta en Docker Hub

Entramos en la siguiente página:

https://hub.docker.com/

Pulsamos en **Sign up**, introducimos nuestro correo electrónico, elegimos un nombre de usuario y creamos una contraseña.

Después verificamos el correo e iniciamos sesión.

### 3. Comprobar la instalación

Abrimos PowerShell y escribimos:

```bash
docker --version
```

Este comando sirve para comprobar la versión instalada.

Después ejecutamos:

```bash
docker run hello-world
```

Este comando descarga una imagen de prueba y ejecuta un contenedor para comprobar que Docker funciona.

### 4. Iniciar sesión en Docker

En PowerShell escribimos:

```bash
docker login
```

Seguimos las instrucciones para iniciar sesión con nuestra cuenta de Docker Hub.

### 5. Conclusión

Con esta práctica he aprendido a instalar Docker Desktop, crear una cuenta en Docker Hub y ejecutar un contenedor de prueba.

### Enlaces utilizados

- https://www.docker.com/
- https://hub.docker.com/
- https://docs.docker.com/
