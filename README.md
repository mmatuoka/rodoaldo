
# Tutorial de criação de APIs em Python

## Criação de diretório e Inicialização do Git

``` bash
mkdir rodoaldo
cd rodoaldo
git init
``` 
## Criação da estrutura do projeto

``` bash
mkdir controllers
mkdir models
mkdir templates
mkdir static
mkdir static/js
mkdir static/css
```

## Criação dos arquivos essenciais ao projeto

``` bash
> README.md
> .gitignore
> .env
> app.py
```

## Criação do ambiente virtual

``` bash
# se não estiver instalado
sudo apt install virtualenv 

virtualenv --python=$(which python3) env

echo "env/" >> .gitignore

source env/bin/activate
```

## Instalação do Flask e outras libs terceiras

``` bash
pip install flask request pymongo

pip freeze > requirements.txt
```



