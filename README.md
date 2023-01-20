# Game Project

To play the game, you have to follow the next steps in the terminal:

```sh
cd game
python3 python main.py 
```


# App Project

```sh
git clone
cd app
python3 -m venv env
source env/bin/activate
pip3 install -r requirements.txt
python3 main.py
```


- Verificar donde esta python y pip

which python3

which pip3

- Si estas en linus o wsl debes instalar

sudo apt install -y python3-venv

- Poner cada proyecto en su propio ambiente, entrar en cada carpeta.

python3 -m venv env

- Activar el ambiente

source env/bin/activate

- Salir del ambiente virtual

deactivate

- Podemos instalar las librerias necesarias en el ambiente virtual como por ejemplo

pip3 install matplotlib==3.5.0

- Verificar las instalaciones

pip3 freeze

- Ver que hay dentro del archivo en el cual se evidencia que no hay pandas

cat reqruirements.txt

- Actualizar el documento que contiene las librerias

pip3 freeze > requirements.txt