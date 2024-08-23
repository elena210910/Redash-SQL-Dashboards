# Redash-SQL-Dashboards

Este repositorio contiene consultas SQL a la base de datos de una tienda de alimentacion online. 
Basado en estas consultas, se han creado paneles de control para una mejor visualización de datos 
para los empleados de la empresa. Los paneles están creados en Redash y, por lo tanto, se construyen
únicamente a través de consultas analíticas SQL.

1. [SQL new users por dia](https://github.com/elena210910/Redash-SQL-Dashboards/blob/main/SQL_new_users_por_dia)

En esta tarea, analizaremos el crecimiento de la audiencia de nuestro servicio y observaremos la dinámica del número de usuarios. 
Utilizamos varias CTEs (Common Table Expressions) para:
  - Obtener la fecha mínima como primera acción para cada usuario.
  - Contar el número de nuevos usuarios por día.
  
    
Finalmente, seleccionamos la fecha, el cambio en el número de nuevos usuarios y el crecimiento total de usuarios para analizar cómo crece nuestra base de usuarios a lo largo del tiempo. Calculamos los siguientes indicadores:

**new_users_change:** El porcentaje de cambio en el número de nuevos usuarios en comparación con el día anterior.
**total_users_growth:** El porcentaje de crecimiento total de usuarios en comparación con el día anterior.

Estos indicadores nos permiten entender mejor la dinámica de crecimiento de nuestra base de usuarios y tomar decisiones informadas para mejorar nuestro servicio.

