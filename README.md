# Documentación de Cirrus CRM.

## Cómo construir este proyecto

Para construir este proyecto usted necesita las siguientes herramientas:

1. Node 16
2. NPM 8.5.0

Debe instalar las dependencias (sólo la primera vez):

```
npm install
```

Luego corra los siguientes programas (No funciona si existen repositorios GIT remotos en el antora-playbook.yml)

```
npx antora --fetch antora-playbook.yml
```