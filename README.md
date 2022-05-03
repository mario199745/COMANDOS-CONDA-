# COMANDOS-CONDA-
COMANDOS CONDA 
# Versión de CONDA 
```conda --version
```
# Actualizar la versión de CONDA 
conda update conda
# Ver todos los paquetes instalados
conda list
# Verifique los paquetes instalados en el entorno 
conda list -n tensorflow
# Paquete de instalación (como instalar numpy)
conda install numpy
# Paquete de actualización (actualice el número del entorno de tensorflow)
conda update -n tensorflow numpy
#  Elimine el paquete en el entorno actual (se pueden eliminar varios paquetes juntos)
conda remove scipy numpy


Usage Example
-------------

```bash
$ docker run --rm frolvlad/alpine-miniconda3 python -c 'print("Hello World")'
```

Once you have run this command you will get printed 'Hello World' from Python!

NOTE: `conda` and `pip` are also available in this image.
