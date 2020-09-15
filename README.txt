... o crea un nuevo repositorio en la línea de comandos
echo "# Androd1" >> README.md 
git init 
git agregar README.md 
git commit -m "primer compromiso" 
git branch -M master 
git remote agregar origen https://github.com/EnriqueRios/Androd1.git
 git push - u maestro de origen
                
... o enviar un repositorio existente desde la línea de comandos
git remoto agregar origen https://github.com/EnriqueRios/Androd1.git
 git branch -M master 
git push -u origin master
... o importar código de otro repositorio
Puede inicializar este repositorio con código de un proyecto de Subversion, Mercurial o TFS.