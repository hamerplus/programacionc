---
layout:
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: false
  outline:
    visible: false
  pagination:
    visible: false
---

# programacionc

{% embed url="https://github.com/hamerplus/programacionc/blob/5302d6c96e596dcc61984817829477bb1c0b631f/consulta%20notas%20estudiantes" %}

Lo primero que hice fue hacer una estructura para representar un estudiantes con struct estudiante en donde con "char" para los nombre y "int" para las notas. supiendo que son 5. Luego con otra funcion que la de "void" para poder consultar las notas de un estudiante, dentro de esa funcion utilice "printf" para imprimkir el nombre del estudiante luego "for" junto con "int" y "printf" para mostrar todas las notas del estudiante, enumernado cada materia y su respectiva nota. Despues utilice la funcion float para calcular el promedio de notas de un estudiante, dentro de esa funcion utilicee "int" suma para almacenar la suma de las notas, luego "for" junto con "int" para utilizar un bucle for y sumar todas las notas del estudiante, luego "return" para devolver el promedio, dividiendo las sumas total de las notas entre la cantidad de las 5 materias. Despues utilice la funcion "int main" junto con "struct" para crear estudiantes de ejemplo donde cree 3 estudiantes con diferentes notas. por ultimo hice la consulta, donde la primera linea llama a la funcion "consultarNotas" para mostrar las notas del estudiante, luego "float promedio" calcula el promedio del estudiante y lo almacena en la variable promedio, luego "printf" imprime el nombre del estudiante junto con su promedio de notas y por ultimo "return" indica una terminacion exitosa del programa devolviendo el valor 0.
