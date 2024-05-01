# TFM

Para poder realizar los commits desde la carpeta local que he creado (apuntes para tener los comandos a mano), en la siguiente ruta C:\Users\Iker Nikolas\Desktop\TFM-24\Github>

1. Descargar Git, 

git --version --> Todo OK (Comprobación)


2. Clonar el repositorio en carpeta local  

git clone https://github.com/IkerNicolasGamiz/TFM.git Github --> Todo OK (Clonado)

3. Configurar variables globales para poder hacer commits con mi usuario

git config --global user.name "IkerNicolasGamiz" 
git config --global user.email "ikernicolasgamiz1516@gmail.com"

4. Hacer commit de los cambios en local a Github

git add . --> Añadir los archivos nuevos al repositorio
git commit -m "Comentario de explicación del commit" --> Commit de los cambios
git push origin main -->  Subir los cambios al repositorio

5. Para eliminar archivos de Github

git rm -f Notebooks/.ipynb_checkpoints/Untitled-checkpoint.ipynb
git rm -f Notebooks/Untitled.ipynb