# Redash-SQL-Dashboards

Este repositorio contiene consultas SQL a la base de datos de una tienda de alimentacion online. 
Basado en estas consultas, se han creado paneles de control para una mejor visualización de datos 
para los empleados de la empresa. Los paneles están creados en Redash y, por lo tanto, se construyen
únicamente a través de consultas analíticas SQL.

1. [SQL new users por dia](https://github.com/elena210910/Redash-SQL-Dashboards/blob/main/SQL_new_users_por_dia)

En esta tarea, analizaremos el crecimiento de la audiencia de nuestro servicio y observaremos la dinámica del número de usuarios y repartidores. Utilizamos varias CTEs (Common Table Expressions) para:
  - Obtener la fecha mínima (primer acción) para cada usuario.
  - Obtener la fecha mínima (primer acción) para cada repartidor.
  - Contar el número de nuevos usuarios por día.
  - Contar el número de nuevos repartidores por día.
    
Finalmente, seleccionamos la fecha, el número de nuevos usuarios, el número de nuevos repartidores, el total acumulado de usuarios y el   total acumulado de repartidores para analizar cómo crece nuestra base de usuarios y repartidores a lo largo del tiempo.

