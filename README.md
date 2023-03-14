# proyecto_x
## Pasos para la creacion de un nuevo proyecto:

```
1) Crear un nuevo repositorio en la web de github

2) Ejecutar los siguientes comandos:

git clone https://github.com/acafa85/template.git
mv template proyecto_x
cd proyecto_x 
rm -rf .git
git init
git remote add origin <url del nuevo repositorio>
git add . 
git commit -m "Initial Commit"
git push -u origin master

3) En caso de decidir clonar la rama especifica de master:

git clone --b master <url del nuevo repositorio>

```

