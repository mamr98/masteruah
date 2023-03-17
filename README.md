# Masteruah
Tarea de clase
git clone https://github.com/mamr98/masteruah
echo >1.txt
git add 1.txt
git commit -m "Creamos el fichero 1.txt"
git tag v0.1
git push --tags
git branch v0.2
git checkout v0.2
echo "contenido del fichero 2" > 2.txt
git add 2.txt
git commit -m "AÃ±adir fichero 2.txt a la rama v0.2"
git push -u origin v0.2
git checkout main
git merge v0.2
echo "Hola" > 1.txt
git add 1.txt
git commit -m " Agregado hola en fichero 1.txt en la rama main"
git checkout v0.2
echo "Adios" > 1.txt
git add 1.txt
git commit -m "Agregado adios en fichero 1.txt en la rama v0.2"
git checkout main
git merge v0.2
git branch --merge
git branch --no-merge
git status
vim 1.txt
git add 1.txt
git commit -m "resulto conflicto fichero 1.txt"
git status
git tag v0.2
git branch -D v0.2
cd ~/.ssh
ls
ssh-keygen
cat clave.pub
