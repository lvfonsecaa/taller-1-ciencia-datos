# Taller 1 · Ciencia de Datos Aplicada

## Integrantes

[Nombres y códigos pendientes.]

## Objetivo

[Pendiente.]

## Alcance

[Pendiente: fuente de datos, preguntas y límites del análisis.]

## Estructura del repositorio

```text
taller-1-ciencia-datos/
├── data/
├── notebooks/
│   ├── 01_entendimiento_datos.ipynb
│   ├── 02_estrategia_analisis.ipynb
│   └── 03_desarrollo_analisis.ipynb
├── src/
├── README.md
├── requirements.txt
└── .gitignore
```

`data/` contiene archivos locales y `src/` queda disponible para código reutilizable.

## Instrucciones de ejecución

Desde la raíz del proyecto después de clonarlo:

```bash
python -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
cd notebooks
jupyter lab
```

En Windows, activar el entorno con `.venv\Scripts\activate` en lugar de `source`.

Colocar el archivo Parquet en `data/` y reemplazar `archivo.parquet` en el primer notebook por su nombre real. Seleccionar el kernel del entorno virtual y ejecutar las celdas en orden. La ruta `../data/` es relativa a `notebooks/`.

[Pendiente: origen e instrucciones de acceso al dataset. Los datos no se incluyen en Git.]

El primer notebook contiene únicamente código de inspección sin resultados guardados ni limpieza automática. Los notebooks 02 y 03 son espacios iniciales pendientes de desarrollo.

## Dependencias

Definidas en `requirements.txt`: pandas, numpy, matplotlib, pyarrow, scipy, jupyterlab e ipykernel.

[Pendiente: documentar versiones del entorno utilizado.]

## Insights

[Pendiente: completar tras ejecutar e interpretar el análisis.]

## Conclusiones

[Pendiente.]
