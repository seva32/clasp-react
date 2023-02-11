habia que mover .clasp.json al root pa poder pushear a google

despues de un deploy en consola google hace falta hacer pull en el repo vscode

tengo que usar el mismo nombre para el .html de apps-cript (google) y src (parcel)

al usar parcel comentar el contenido de .babelrc

para iniciar el dev:

`yarn run parcel`
`yarn run gstart` en otra terminal

Para production 

`yarn run parcelbuild`
`yarn run gpush`

Todo lo que es backend va en apps-script/main y el fron en src

si voy a https://script.google.com/home/usersettings puedo poner on la api de scripts

Puedo usar gcreate para crear el proyecto desde vscode o clonar un proyecto que ya tengo en gcpS