# NovaCorp Git Flow

Documentacion de flujo de trabajo remoto con git

## Organizacion

Se recomienda crear una organizacion que sea la propietaria del repositorio principal. A partir
de dicho repositorio los miembros o colaboradores pueden hacer un fork hacia sus cuentas
personales.

### Pasos para crear una organizacion

1. Click en la foto de perfil (Esquina superior derecha)
2. Click en settings
3. Click en organizaciones (Menu Izquierda)
4. Click en nueva organizacion
5. Elegir plan y llenar datos

## Creacion del fork

Para crear un fork debes iniciar sesion en GitHub y luego ingresar a la landing page del
proyecto del que quieras sacar tu fork.

## Como trabajar con dos o mas remotos

Listar remotos
`git remove -v`

Agregar remotos
`git remote add flujo-git git@github.com:novakcorporg/flujo-git.git`

Eliminar remotos
`git remote remove flujo-git`

## Creando etiquetas

Es necesario entender que las etiquetas (o releases) solo deben ser creados a partir
de la rama master como buena practica.

Para entender como llamar o categorizar a tus versiones te recomendamos un articulo en nuestro
blog: https://ed.team/blog/como-se-deciden-las-versiones-del-software