# Nombre del Proyecto

## Descripción
Taller de practica para aprender el flujo de trabajo de gitflow.

## Instalación
1. Clona el repositorio:
    git clone https://github.com/johansoriano63-ux/TallerGitflow.git
2. Entra a la carpeta:
   cd TallerGitflow
3. Instala las dependencias:
   npm install

## Uso
Para ejecutar el proyecto se usa:
   npm start

Para validar el README:
   npm run validate:readme

## Autores
Johan Soriano

## Flujo de trabajo Git
Este proyecto usa GitFlow:
- main: rama estable y de produccion
- develop: integracion de cambios antes de liberar
- feature/*: desarrollo de nuevas funcionalidades
- release/*: preparacion y ajuste de versiones
- hotfix/*: correcciones urgentes sobre main

## Evidencias
Repositorio: https://github.com/johansoriano63-ux/TallerGitflow.git
Pull Request feature/readme-base → develop: https://github.com/johansoriano63-ux/TallerGitflow/pull/5
Pull Request feature/documentacion-extra → develop: https://github.com/johansoriano63-ux/TallerGitflow/pull/9
- Issues cerrados: https://github.com/johansoriano63-ux/TallerGitflow/issues
- Ramas creadas: develop, feature/readme-base, feature/documentacion-extra, release/v1.0.0