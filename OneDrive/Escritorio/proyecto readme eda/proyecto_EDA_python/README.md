Proyecto EDA - Campaña de Marketing y Clientes del Banco.

Los datos provienen de:
- Un archivo CSV con informacion sobre campañas de marketing (`bank-additional.csv`).
- Un archivo Excel con detalles demograficos de los clientes (`customer-details.xlsx`).

he usado:
- Python 
- pandas
- matplotlib
- seaborn

1. Estructura del proyecto

- `archivos/bank-additional.csv` - Datos de campañas.
- `archivos/customer-details.xlsx` - Detalles de clientes.
- Código principal para carga, limpieza, analisis y visualizacion de datos.

2. Pasos realizados en el analisis

1. Carga y union de datos:
   - Se importan los datasets CSV y Excel.  
   - Se concatenan hojas del Excel y se unifican ambos datasets por la columna `id_`.

2. Limpieza y preprocesamiento:
   - Renombrado de columnas para unificacion.  
   - Conversion de tipos de datos para facilitar el merge.

3. Analisis descriptivo 
   - Estadisticas bsaicas y conteo de variables importantes (`y`, `job`, `marital`).  
   - Identificacion de valores nulos.

4. Visualización de datos: 
   - Graficos de barras para variables categóricas.  
   - Histogramas para distribucion de edad.  
   - Boxplots para comparar ingresos segun respuesta del cliente.  
   - Heatmap para analizar correlaciones numericas.

5. conclusiones:  
   - La mayoria de los clientes no suscribieron un producto.  
   - Las profesiones mas comunes son "admin" y "blue-collar".  
   - Los clientes que suscribieron tienen ingresos ligeramente mayores.  
   - Los patrones identificados pueden ayudar a futuras campañas y modelos predictivos.


Autor: David Rull Lopez 
Fecha: 23/09/2025