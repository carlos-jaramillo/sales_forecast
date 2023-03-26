# sales_forecast
Sales prediction, for food products, sold in various stores.
Tipos de datos:

0   Item_Identifier            8523 non-null   object 
 1   Item_Weight                8523 non-null   float64
 2   Item_Fat_Content           8523 non-null   object 
 3   Item_Visibility            8523 non-null   float64
 4   Item_Type                  8523 non-null   object 
 5   Item_MRP                   8523 non-null   float64
 6   Outlet_Identifier          8523 non-null   object 
 7   Outlet_Establishment_Year  8523 non-null   int64  
 8   Outlet_Size                8523 non-null   object 
 9   Outlet_Location_Type       8523 non-null   object 
 10  Outlet_Type                8523 non-null   object 
 11  Item_Outlet_Sales          8523 non-null   float64
 
Relaciones entre variables vista en el heatmap:

De 1 a 0.7 se considera "fuerte".

Entre 0,5 y 0,7 se considera “moderado”.

Entre 0,3 y 0,5 se considera una correlación “baja”.

Visualizaciones:
1. #Análisis: Hay más productos "Low Fat", supongo que por el tema de que es mejor visto que lo regular en general.
2. #Análisis: Cantidad de tipos de alimentos vendidos
3. #Análisis: Peso de cada item, para ver que tan pesados son, nada importante al análisis.
4. #Análisis: Hacer algo más visible donde se encuentra ubicado el valor de la media de la columna "Item_MRP"

Resultados finales:
Uso de random forest para mejor resultados
Revisión básica de instalación de modelos.
Primer proyecto hecho solo
