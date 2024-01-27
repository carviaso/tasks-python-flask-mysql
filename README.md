# Python Task

## Inicio

```
python -m venv env
.\env\Scripts\activate

python.exe -m pip install --upgrade pip

pip install --upgrade -r requirements.txt
```

## Update requirements.txt

```
powershell -Commnad "pip freeze  | %{$_.split('==')[0]} | %{$_}" > requirements.txt
```

## Libraryies

```
pip install pandas seaborn matplotlib
```

# Descripcion

---
Sistema que maneja Tareas y bases de datos en MySQL.

# Base de datos

La base de datos se almacena en [Free Mysql Hosting](*https://www.freemysqlhosting.net/)

## Tabla Users

_Contienen los datos de los usuarios_

# |campo|tipo|Descripcion|
-|-|-|-|
1|id|llave|
2|name|text|
3|surnames|text|
4|email|text|
5|password|text|

## Tabla Tasks

_Contienen los datos de las tasks_

# |campo|tipo|Descripcion|
-|-|-|-
1|id|llave|
2|title|text
3|description|text|
4|email|text|
5|date_task|text|
