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

# Descripcion:
---
Sistema que maneja archivos [CSV](https://docs.python.org/es/3/library/csv.html)  (Valores Separados por Comas) es el formato más común de importación, exportación de hojas de cálculo y bases de datos.
