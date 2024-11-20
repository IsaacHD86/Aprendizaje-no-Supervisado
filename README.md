# Aprendizaje-no-Supervisado.
## Segmentación de Clientes con RFM y k-Means.

### Objetivo:
Realizar segmentación de clientes utilizando la metodología RFM (Recency, Frequency, Monetary).                                                                    
Identificar patrones de compra para ofrecer mejores estrategias de marketing.            

### 1. Aplicaciones del análisis de clientes:                                                                                                           
Estadística Descriptiva: Resumir y entender el comportamiento de los clientes.                                                                                 
Predicción de Abandono: Identificar clientes que podrían dejar de comprar.                                                                                       
Customer Lifetime Value (CLTV): Estimar el valor de los clientes a lo largo del tiempo.                                                                                          

### 2. Metodología RFM.
Indicadores:                                                                                                                                                           
Recency: Tiempo desde la última compra de un cliente.                                                                                                  
Frequency: Número de compras realizadas en un periodo definido.                                                                            
Monetary: Gasto total acumulado de un cliente.                                                                                            

Visualización:                                                                                                                                             
Se crean histogramas para cada indicador (Recency, Frequency, Monetary) para analizar su distribución.                                                      

### 3. Algoritmo k-Means.                                                                  
Descripción:                                                                                                                                                     
Algoritmo de aprendizaje no supervisado utilizado para agrupar clientes en clústeres basados en sus métricas RFM.                                                            

Método del Codo (Elbow Method):                                                                                                                                      
Se utiliza para determinar el número óptimo de clústeres analizando la suma de los errores cuadráticos (SSE).                                                                   
Creación de un gráfico para visualizar el punto de inflexión.                                                                                                    

### 4. Personalización del Modelo.
Score de Segmentación:                                                                                                                          
Asignación de una puntuación a cada clúster basada en el valor de sus características RFM.                                                          
Esta métrica permite una mejor interpretación y personalización de los resultados.                                                                            

Gráfico de Dispersión 3D:                                                                                                                          
Visualización de los clústeres en un espacio tridimensional con las variables:                                                                                        
Ejes X: Frequency                                                                                                 
Ejes Y: Monetary                                                                                                                     
Ejes Z: Recency                                                                                                                         
Uso de matplotlib con el módulo Axes3D para la creación del gráfico.                                                                                                       

### 5. Resultados y Conclusiones
Segmentación.                                                                                                                                                    
Los clientes fueron agrupados en diferentes clústeres, cada uno representando un perfil de comportamiento.                                                                   
Interpretación:                                                                                                  
Los clústeres de mayor valor son aquellos con:                                                                                 
Baja recencia (compra reciente).                                                                                 
Alta frecuencia (compras frecuentes).                                                                                          
Alto valor monetario (gasto acumulado significativo).                           

## Autor
Isaac Heredia Diaz
[GitHub](https://github.com/IsaacHD86)
