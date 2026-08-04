Clientes

Los valores nulos en email y ciudad fueron reemplazados por "Sin email" y "Sin datos". Estos campos no son claves del modelo y su ausencia no afecta las relaciones entre tablas. Se preserva así la información del cliente sin perder registros.

Productos

El registro con precio nulo fue eliminado porque el precio es un dato indispensable para calcular ingresos y márgenes. Asignar un valor arbitrario introduciría errores en los análisis. La categoría nula se reemplazó por "Sin Categoría" para conservar el producto y evitar valores faltantes en la dimensión.
