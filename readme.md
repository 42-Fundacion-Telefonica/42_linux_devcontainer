# Configuración del Contenedor de Desarrollo

Este repositorio contiene una carpeta `.devcontainer` que te permite configurar un entorno de desarrollo utilizando la extensión Remote - Containers de Visual Studio Code.

## Prerrequisitos

Antes de comenzar, asegúrate de tener instalado lo siguiente en tu sistema:

- [Visual Studio Code](https://code.visualstudio.com/)
- [Docker](https://www.docker.com/products/docker-desktop)

## Empezar

Para utilizar este contenedor de desarrollo en tu propio repositorio, sigue estos pasos:

1. Clona este repositorio:

    ```bash
    git clone <repository-url>
    ```

2. Copia la carpeta `.devcontainer` a la raíz de tu repositorio de proyecto.

3. Abre tu proyecto en Visual Studio Code.

4. Visual Studio Code debería detectar la configuración del contenedor de desarrollo en tu proyecto y te pedirá que vuelvas a abrir el proyecto en un contenedor. Alternativamente, puedes abrir la Paleta de Comandos (Ctrl+Shift+P) y seleccionar `Remote-Containers: Reopen in Container`.

5. Espera a que Visual Studio Code construya el contenedor de Docker y configure el entorno de desarrollo.

6. Una vez que el contenedor esté construido y el entorno esté configurado, puedes empezar a codificar dentro del contenedor de desarrollo.

## Configuración Adicional (Opcional)

- Puedes personalizar el contenedor de desarrollo modificando el archivo `devcontainer.json` dentro de la carpeta `.devcontainer`. Consulta la [documentación oficial](https://code.visualstudio.com/docs/remote/containers#_devcontainerjson-reference) para obtener más información sobre las opciones de configuración disponibles.

## Retroalimentación

Si encuentras algún problema o tienes sugerencias para mejorar, por favor [abre un issue](<link-to-issues-page>) en este repositorio.

¡A pasarlo bien programando!



# Dev Container Setup

This repository contains a `.devcontainer` folder which allows you to set up a development environment using Visual Studio Code's Remote - Containers extension.

## Prerequisites

Before you begin, make sure you have the following installed on your system:

- [Visual Studio Code](https://code.visualstudio.com/)
- [Docker](https://www.docker.com/products/docker-desktop)

## Getting Started

To use this dev container in your own repository, follow these steps:

1. Clone this repository:

    ```bash
    git clone https://github.com/42-Madrid-Fundacion-Telefonica/42_linux_devcontainer.git
    ```

2. Copy the `.devcontainer` folder to the root of your project repository.

3. Open your project in Visual Studio Code.

4. Visual Studio Code should detect the dev container configuration in your project and prompt you to reopen the project in a container. Alternatively, you can open the Command Palette (Ctrl+Shift+P) and select `Remote-Containers: Reopen in Container`.

5. Wait for Visual Studio Code to build the Docker container and set up the development environment.

6. Once the container is built and the environment is set up, you can start coding inside the dev container.

## Additional Configuration (Optional)

- You can customize the dev container by modifying the `devcontainer.json` file inside the `.devcontainer` folder. Refer to the [official documentation](https://code.visualstudio.com/docs/remote/containers#_devcontainerjson-reference) for more information on available configuration options.

## Feedback

If you encounter any issues or have suggestions for improvement, please [open an issue](https://github.com/42-Madrid-Fundacion-Telefonica/42_linux_devcontainer/issues) on this repository.

Happy coding!
