# Proyecto Aprendizaje estadístico-automático
Los niveles de obesidad de la población son cada vez más preocupantes, sobre todo en países latinoamericanos. Por lo mismo, científicos de la Universidad de la Costa en Colombia se dieron a la tarea de recolectar información relacionada a este tema para individuos de Colombia, Perú, y México. La base de datos original se encuentra en [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/544/estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition), pero una versión simplificada con el nombre “A1.1 Obesidad.csv” fue usada para este proyecto en el enlace.
La base de datos cuenta con la siguiente información:

1. **“Sexo”**. Se describe como femenino (Female) o masculino (Male).

2.  **“Edad”**. Se describe como un número entre 14 y 61.
3. **“Estatura”**. Se describe como un número, en metros.

4. **“Peso”**. Se describe como un número, en kilogramos.

5. **“FamiliarConSobrepeso”**. Describe si algún familiar ha sufrido sobrepeso (yes) o no
(no).

6. **“ComeMuchasCalorias”**. Describe si el individuo come comidas con alto contenido
calórico de forma frecuente (yes) o no (no)

7. **“ComeVegetales”**. Indica si el individuo nunca come vegetales en sus comidas (1), si lo
hace algunas veces (2), o si lo hace siempre (3)

8. **“Fumador”**. Indica si la persona es fumadora activa (yes) o no (no)

9. **“ConsumoDeAgua”**. Indica si la persona toma menos de un litro de agua al día (1), entre
uno y dos litros de agua al día (2), o más de dos litros de agua al día (3)

10.  **“NivelDeObesidad”**. Se calcula a partir del índice de masa corporal (peso dividido entre
estatura al cuadrado), y se categoriza como:
**bajo peso** (Insufficient_Weight) para valores
menores a 18.5, **peso normal** (Normal_Weight) para valores entre 18.5 y 24.9, **sobrepeso
tipo I** (Overweight_Level_I) y **sobrepeso tipo II** (Overweight_Level_II) para valores entre
25.0 y 29.9, **obesidad tipo I** (Obesity_Type_I) para valores entre 30.00 y 34.9, **obesidad
tipo II** (Obesity_Type_II) para valores entre 35.0 y 39.9, y **obesidad tipo III**
(Obesity_Type_III) para valores superiores a 40.0
