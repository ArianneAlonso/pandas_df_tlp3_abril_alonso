Este repositorio contiene un análisis de datos con **pandas** sobre un conjunto de datos de salarios de empleados. Se realizan consultas básicas de SQL utilizando dataframe.

## Autor

**Arianne Alonso**

## Descripción del proyecto

El objetivo de este proyecto es practicar consultas básicas con pandas simulando operaciones similares a SQL. Se utiliza un archivo Jupyter Notebook (`actividad_df.ipynb`) para mostrar los siguientes análisis:

- Top 10 empleados con mayor salario total (incluyendo beneficios).
- Empleados con más de $50,000 en horas extra.
- Cantidad de empleados únicos por año.
- Cantidad de cargos únicos (`JobTitle`) y los 5 más comunes.
- Salario total promedio (`TotalPay`) por año.
- Exportación de todos los datos a un archivo `.csv`.
- Visualización de los últimos 10 valores del dataframe.

## Instalación y uso

Sigue los siguientes pasos para clonar y ejecutar el proyecto correctamente en tu máquina local:

### 1. Clonar el repositorio

```bash
git clone https://github.com/ArianneAlonso/pandas_df_tlp3_abril_alonso.git
```

2. Ingresar a la carpeta del proyecto

```bash
cd pandas_df_tlp3_abril_alonso
```

3. Crear un entorno virtual (si no existe)

```bash
python -m venv df
```

4. Activar el entorno virtual

En Windows:

```bash
df\Scripts\activate
```

En MacOS/Linux:

```bash
source df/bin/activate
```

5. Instalar las dependencias
   
```bash
pip install -r requirements.txt
```

6. Seleccionar el entorno en Visual Studio Code

Abre el archivo actividad_df.ipynb en VSCode. En la esquina superior derecha, selecciona el entorno virtual df como kernel de Python. Esto permitirá ejecutar el notebook correctamente.
