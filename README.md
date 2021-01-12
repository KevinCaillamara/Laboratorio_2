# Laboratorio 2: Análisis de mallas
**Integrantes:** Caillamara Leonardo, González Ariel
## 1. OBJETIVOS

### Objetivo general:
* Justificar el uso de leyes de Kirchhoff para el análisis de mallas.

### Objetivos específicos:
* Encontrar los valores de corriente en cada malla mediante el uso de leyes de Kirchhoff y el uso del simulador TinkerCad.
* Comparar los valores obtenidos en una tabla y calcular los errores respectivos.

## 2. MARCO TEÓRICO

El circuito eléctrico es denominado el camino por donde circula corriente eléctrica que a su vez contiene elementos pasivos y activos por los cuales también circula dicha corriente. A lo largo del tiempo el circuito eléctrico ha ido evolucionando, desde ser únicamente cables unidos a elementos simples como bombillas o motores rudimentarios, pasando a ser un diagrama complejo con diferentes funcionalidades.

Un circuito eléctrico no es solo un lazo, al contrariom es la unión de lazos y a cada uno de estos se los denomina mallas, las cuales serás el objeto de estudio de esta práctica. En el análisis de circuitos eléctricos es importante saber cómo tratar este tipo de circuitos.

![](https://github.com/KevinCaillamara/Laboratorio_2/blob/main/Im%C3%A1genes/diagrama_circuito.png)

Para la solución de este tipo de circuitos existen dos métodos muy diferenciados  dependiendo de los datos proporcionados por el circuito. Estos métodos se basan en el uso de las leyes de Kirchhoff , utilizando la ley de corrientes (LCK) o la ley de voltajes (LVK). Naturalmente el uso de estas leyes nos obliga a utilizar conceptos previamente adquiridos como son: Las leyes de Ohm, conceptos de nodos y ramas y las correspondientes leyes de Kirchhoff.

## 3. EQUIPOS Y MATERIALES

* **TinkerCad:** Programa online que tiene la capacidad de simular circuitos eléctricos.
* **Protoboard:** Es una placa de pruebas en la que se puede insertar elementos eléctricos y electrónicos, así como cables con los que se arman circuitos sin la necesidad de soldar ninguno de los componentes.
* **Resistencias eléctricas:** Eleménto eléctrico que se opone al paso de corriente.
* **Cables puente:** Cables de ayuda para realizar conexiones provisionales.
* **Multímetro:** Es un instrumento analógico o digital portátil que se usa para medir directamente magnitudes eléctricas.
* **Batería o fuente energética:** Dispositivo que provee energía a un circuitp al cual es conectada.

## 4. PROCEDIMIENTO
* Entramos a la plataforma de TinkerCad y creamos un nuevo circuito.
* Utilizando las distintas herramientas de dicho simulador representamos el circuito del diagrama presentado en la guía de laboratorio.
* Conectamos los multímetros necesarios en el circuito teniendo en cuenta que deben estar configurados para medir corrientes, se deben colocar correctamente (en serie) para medir las corrientes de cada malla.
* Iniciar la simulación, tomar datos y llenar la tabla proporcionada.
* Realizar los cálculos respectivos en la tabulación.

![](https://github.com/KevinCaillamara/Laboratorio_2/blob/main/Im%C3%A1genes/simulacion_tinkercad.png)

## 5. TABLAS DE MEDICIÓN Y CÁLCULOS
### 2.1 Resultados obtenidos para el circuito

![](https://github.com/KevinCaillamara/Laboratorio_2/blob/main/Im%C3%A1genes/tabla_valores_y_error.png)

Los cálculos respectivos están en la carpeta denominada Cálculos y para el cálculo del error en cada malla se usa la siguiente fórmula en los tres casos:

![](https://github.com/KevinCaillamara/Laboratorio_2/blob/main/Im%C3%A1genes/formula_error.png)

## 6. ANÁLISIS DE RESULTADOS

En la tabla podemos observar que el error en cada malla no supera el 0.3% esto se justifica ya que las mediciones son realizadas en un programa de simulación, por lo que los valores únicamente variarían en decimales a causa de aproximaciones, tanto del programa como de los cálculos realizados analíticamente.

En un caso práctico las resistencias utilizadas tienen un valor mayor o cercano al orden de los kOhm, caso contrario, si en el circuito fueran utiizadas resistencias de un valor pequeño, la propia resistencia interna del multímetro interferiría en las mediciones de las corrientes y provocaría una variación considerable.

En la tabla también podemos observar que en la malla con mayor potencial eléctrico es en la malla 1, mientras que la de menor potencial eléctrico es la malla 2 ya que la correitne en cada malla es mayor y menor respectivamente a causa de las resistencias por las que la corriente ha pasado, dejando la malla 2 en medio. También es posible deducir que a mayor corriente de malla, mator es el error de meduda pero como se dijo antes, las variaciones producidas en la tabla son a causa de redondeos.

## 7. CONCLUSIONES

Efectivamente, el uso de las leyes de Kirchhoff son de gran utilidad para realizar un análisis teórico de las mallas de un circuito ya que por resultados de la tabla realizada podemos darnos cuenta que al momento de comparar valores simulados con calculados el error producido es cercano a cero, lo que nos indica la confiabilidad del método utilizado.

## 8. BIBLIOGRAFÍA

* Durán, J. (2012). *Electrotecnia*. Barcelona: Editorial Lexus.
* Thomas, L. (2007). *Principios de circuitos eléctricos*. México: Editorial Pearson.
* Maldonado, A. (2016). *Tecnología eléctrica*. Quito: Poli Ediciones.
* Fraile, J. (2012). *Circuitos eléctricos*. Madrid: Editorial Pearson.
