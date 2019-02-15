# Instrucciones

Paso 1: Instalar Anaconda

(conda install ....)

Crear ENTORNO de Python

```{bash}
~$ virtualenv -p python3 entorno_wids
Already using interpreter /usr/bin/python3
Using base prefix '/usr'
New python executable in /home/inigogonzalez/entorno_wids/bin/python3
Also creating executable in /home/inigogonzalez/entorno_wids/bin/python
Installing setuptools, pkg_resources, pip, wheel...done.
```
Despues ACTIVAMOS EL ENTORNO:

```{bash}
nigogonzalez@TIN20180831076:~$ . entorno_wids/bin/activate
(entorno_wids) inigogonzalez@TIN20180831076:~$ 

```

En el PROMPT aparece el entorno en el que estamos.

Después hay que cargar los ficheros de dependencias

```{bash}
cd DIRECTORIO_EN_EL_QUE_ESTA_ESTE_REPO
pip install -r requirements.txt


(saldra mucha mierda por aqui abajo. Es normal)
```

Y ya podemos abrir jupyter
```{bash}
jupyter notebook
```