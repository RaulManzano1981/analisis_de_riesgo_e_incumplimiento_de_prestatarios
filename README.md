# analisis_de_riesgo_e_incumplimiento_de_prestatarios
Este notebook analisa el riesgo de incumplimiento de un prestamo dependiendo de una serie de caracteristicas de posee el cliente solicitante del prestamo, entre ellas se consideran el estado civil, nivel de educación, tipo de ingreso.

Los objetivos a lo largo del proyeto serán los siguientes:
Encontrar y calcular el porcentaje que representan los valores faltantes y determinar si la cantidad es significativa sobre el total de datos.

Realizar la comparación de las columnas y encontrar un patrones entre ellos.

Reemplazar los valores faltantes en la columna "total_income" e "income_type" utilizando la mediana.

Encontrar y eliminar los valores duplicados

Clasificar los datos

Comprobar las hipótesis planteadas

Dataset:
data_customer = pd.read_csv("/datasets/credit_scoring_eng.csv")

Descripción de los datos

* children - el número de hijos en la familia
  
* days_employed - experiencia laboral en días
  
* dob_years - la edad del cliente en años

* education - la educación del cliente

* education_id - identificador de educación

* family_status - estado civil

* family_status_id - identificador de estado civil

* gender - género del cliente

* income_type - tipo de empleo

* debt - ¿había alguna deuda en el pago de un préstamo?

* total_income - ingreso mensual

* purpose - el propósito de obtener un préstamo
