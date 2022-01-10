# School_District_Analysis

## Purpose
    - Obtener metricas claras para asi tener una vision del estado
    en el cual se encuentran las instituciones educativas en cuanto a 
    porcentaje de alumnos aprobados y presupuesto.
    - Mostrar mediante tablas toda la informacion de manera resumida y clara.
    - Extraer del analisis cierta informacion de Thomas High School’s y revisar
    como afecta esto al panorama entero del analisis
    
## Results

#### How is the district summary affected?
    - El Average Math Score se ve afectado por que hay valores altos que ya no se consideran la diferencia es 0.1 (images A-1, A-2).
    - Por lo anterior la columna % Passing Math tambien se ve afectada por 0.2% (images A-1, A-2).
    - Por solo un 0.01% el % Passing Reading se ve afectado hay muchos valores altos que no se estan tomando en cuenta(images A-1, A-2).
    - Por por todo lo anterior el % Overall Passing muestra una disminucion del 0.3% (images A-1, A-2).

#### How is the school summary affected?
    - Los valores afectados serian solo los de Thomas High School
    - El valor Average Math Score es menor por 0,067412 (images B-1, B-2).
    - El Average Reading Score subio por 0,047152 (images B-1, B-2).
    - El % Passing Math disminuyo en 26,360856% se debe a los valores faltantes (images B-1, B-2).
    - El % Passing Reading disminuyo en 27,64526% se debe a los valores faltantes (images B-1, B-2).
    - Finalmente el % Overrall Passing disminuyo en 0,317688% (images B-1, B-2).
    - Considero que la razon por la cual el Average Reading Score aumento y el % Passing Reading
    disminuyo se deba a que los valores eliminados contribuian mas para el promedio de 
    alumnos aprobados.

#### How does replacing the ninth graders’ math and reading scores 
#### affect Thomas High School’s performance relative to the other schools?
    - Si hacemos el calculo tomando los valores vacios Thomas High School quedaria de septimo
    lugar en % Overall Passing (image C-1).
    - Sin embargo si no tomamos en cuenta en el analisis the ninth graders’ math and reading scores 
    sube hasta el segundo puesto (image D-1).
    - Lo cual considerarlos o no los valores afecta fuertemente la calificacion del instituto.

#### How does replacing the ninth-grade scores affect the following:

##### Math and reading scores by grade
    - Como se agrupan por grados simplemente tanto los valores de math and reading
    estaran ausentes (images E-1, F-1)

##### Scores by school spending
    - No hay ningun tipo de afectacion en este aspecto ya que los valores afectados
    solo fueron de las calificaciones.

##### Scores by school size
    - De manera contraintuitiva este resultado no se ve afectado, probablemente sea
    por que la diferencia de Thomas High School no tiene el peso suficiente para 
    cambiar las cifras.
    - Otro punto que pudo afectar a que no se viera reflejado la variacion es por el tipo
    de formato que se configuro, si tuviesemos uno con mas decimales tal vez se pueda
    ver la diferencia

##### Scores by school type
    - Pasa lo mismo que en el anterior punto, no se ve afectado los valores.

## Summary

    - Como se menciono en "How is the district summary affected?" hubo cuatro
    valores que precisamente tuvieron cierta afectacion por los valores nan
    que serian: Average Math Score, % Passing Math, % Passing Reading and % Overall Passing
    algunos valores tuvieron mayor afectacion de otros y eso depende de como estaban
    distribuidos los valores que se sustituyeron.