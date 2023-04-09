# GeemapCurso
## Manejo de imágenes satelitales con Geemap (python)

Geemap es un paquete de Python para mapas interactivos con **Google Earth Engine (GEE)**, que es una plataforma de computación en la nube con un catálogo de varios petabytes de imágenes satelitales y conjuntos de datos geoespaciales (https://earthengine.google.com/).<br>

La plataforma de GEE proporciona una API para JavaScript y Python con el propósito de realizar solicitudes computacionales a los servidores de Earth Engine. En comparación con la documentación y el IDE interactivo de la API de JavaScript en GEE, la API de Python de GEE (geemap) tiene relativamente poca documentación y una funcionalidad limitada para visualizar los resultados de forma interactiva. Sin embargo, podemos hacer trabajos en los cuales podemos emplear librerías de Python para implementar funciones que comunmente no están incluidas en la API de JavaScript.<br>

Para usar geemap, primero debe registrarse para obtener una cuenta de Google Earth Engine (<a href="https://code.earthengine.google.com/register">Registro GEE</a>). No puede usar Google Earth Engine a menos que su solicitud haya sido aprobada. Una vez que reciba el correo electrónico de aprobación de la solicitud, puede iniciar sesión en el editor de código de Earth Engine para familiarizarse con la API de JavaScript.<br>

Para <a href="https://geemap.org/installation/#install-from-pypi"> instalar </a> geemap en la plataforma de Anaconda debes instalar:<br>

```
conda install geemap -c conda-forge
```

Opcionalmente puede crear un entorno de conda nuevo para instalar geemap:

```
conda install -n base mamba -c conda-forge
mamba create -n gee geemap geopandas localtileserver python -c conda-forge
```

Por último, puedes instalar las siguientes dependencias (opcionales):

```
pip install geemap[all]
```
