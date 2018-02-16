# UVa 352 - La guerra de la temporada

Los habitantes de *Trigrécuaro* y *Elefantitlán* se encuentran enmedio de una guerra. El mes pasado, *Elefantitlán* puso en órbita de manera exitosa un telescopio satelital espía con el nombre de **Fallascopio**. El propósito del **Fallascopio** era contar el número de *Águilas de Batalla* en *Tigrécuaro*. Sin embargo, el **Fallascopio**, desarrolló dos problemas a causa de un bajo control de calidad en su producción. Su lente primario estaba contaminado con bichos que bloqueaban parte de cada imagen, y su mecanismo de enfoque dejó de funcionar, por lo que las imágenes varían en tamaño y definición.

Los programadores del **Fallascopio** que deben rectificarlo están cautivos en un hotel de **Concurso de Programación** en *Alalandia* y sus captores son elefantes disfrazados de tigres. Las imágenes del **Fallascopio** se guardan pixel por pixel. Cada imagen es un cuadrado de pixeles, y cada pixel es un *1*, si parte o toda un águila está presente, o un *0* si cualquier otro objeto, incluído un bicho, es visible. Los programadores deben asumir lo siguiente:


  1. Un *Águila de Batalla* se representa con por lo menos un *1*.  
  2. Celdas con lados adyacentes a vértices en común, que contengan un *1*, representan la misma águila. Una gran imagen compuesta de puros *1*'s representa sólo un águila.
  3. *Águilas de Batalla* diferentes no se tocan entre sí. Aunque esta suposición probablemente sea falsa, los programadores deben seguirla por su desesperación para resolver el problema.
  4. La imagen representa un plano. Los pixeles de hasta abajo no son adyacentes a los de hasta arriba, ni los de la izquierda, adyacentes a los de la derecha (a menos, por supuesto, que la imagen sea de *2x2*)
  
## input / output

Escribe un programa que lea las imágenes de pixeles, correctamente cuente el número de *Águilas de Batalla* en la imágen e imprima el número de águilas en esa imagen como una línea de salida.

Usa el formato especificado en el ejemplo. Haz esto para cada imagen especificada. Cada imagen estará precedida por un número que indica la medida de sus dimensiones. Ninguna dimensión puede exceder las 25 unidades.

## Ejemplo

### Entrada
```
6
100100
001010
000000
110000
111000
010100
8
01100101
01000001
00011000
00000010
11000011
10100010
10000001
01100000
```  

### Salida
```
Image number 1 contains 3 war eagles.
Image number 2 contains 6 war eagles.
```

## Referencia y Juez


![UVa Logo](https://uva.onlinejudge.org/templates/hm_yaml_2_5/img/onlinejudgelogo2.png)  
[352 - The Seasonal War](https://uva.onlinejudge.org/index.php?option=onlinejudge&page=show_problem&problem=288)
