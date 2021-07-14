# InformeLaboratorio4

Integrantes: Jonathan Insuasti - Melany  Villa - César Garnica 

# 1. Objetivos 
      Objetivo General
     
    - Comprobar   el   teorema   de   superposición   mediante   la   resolución   de   un   ejercicio 
    y   su respectiva simulación en un software de diseño electrónico para comprabar que el método este bien utilizado
    
    Objetivos Específicos
     - Verificar experimentalmente en forma cualitativa la propiedad de Superposición.
     - Conocer los fundamentos básicos del teorema de superposición.
     - Comprobar las condiciones necesarias para que se cumpla el teorema de superposición.
     - Comprobar   los   resultados   obtenidos   teóricamente   mediante   una   simulación  
     de un diseño electrónico.

    
# 2. Marco Teórico

![](https://github.com/mjvilla1/ImagenesLab4/blob/main/Tabla%20de%20Materiales.PNG)


![](https://github.com/mjvilla1/ImagenesLab4/blob/main/Teorema%20de%20superposici%C3%B3n.PNG)

# 3. Explicación  del procedimiento


![](https://github.com/mjvilla1/ImagenesLab4/blob/main/Circuito.jpeg)

Realizamos el circuito mostrado en el grafico en un protoboard

![](https://github.com/mjvilla1/ImagenesLab4/blob/main/Eje%20t.jpeg)

Con este esquema hecho en protoboard podemos observar la medición del voltaje e intensidad en la resistencia 2 

![](https://github.com/mjvilla1/ImagenesLab4/blob/main/EJ%20V1%3D0.jpeg)

Para hacer el análisis de superposicion debemos eliminar la fuente de voltaje 1 y reemplazarla por un cortocircuito,realizar las conexiones necesarias de elementos de medición para cada elemento que se desee conocer los valores.

![](https://github.com/mjvilla1/ImagenesLab4/blob/main/EJ%20V2%3D0.jpeg)

Para hacer el análisis de superposicion debemos eliminar la fuente de voltaje 2 y reemplazarla por un cortocircuito,realizar las conexiones necesarias de elementos de medición para cada elemento que se desee conocer los valores.

#  4. Respuestas 

Para hacer el cálculo en el diagrama tenemos que redibujar tantas veces como sea necesario para encontrar los valores pedidos 

Necesitamos para el esquema encontrar el valor de la resistencia R2 y la intensidad que circula por R4.

Aplicando el metodo de superposicion analizamos quitando una V1 Y V2 en dos redibujos diferentes y asi encontramos los valores

Análisis del circuito con V2=0

![](https://github.com/mjvilla1/ImagenesLab4/blob/main/Eje%201.jpeg)

![](https://github.com/mjvilla1/ImagenesLab4/blob/main/Eje%202.jpeg)

![](https://github.com/mjvilla1/ImagenesLab4/blob/main/Eje%201%201.jpeg)

Análisis del circuito con V3=0

![](https://github.com/mjvilla1/ImagenesLab4/blob/main/Eje%203.jpeg)

![](https://github.com/mjvilla1/ImagenesLab4/blob/main/Eje%203%201.jpeg)

En este circuito el valor de IR4 es igual a cero ya que segun el procedimiento la corriente se dirige por  el cable vacio 

Los resultados obtenidos nos demuestra que restando el valor del voltaje que proporciona V1 a la resitencia R2 menos V2 el valor es igual al medido en el circuito por lo que el teorema de superposicion estaria comprobado 

![](https://github.com/mjvilla1/ImagenesLab4/blob/main/R%201.jpeg)

![](https://github.com/mjvilla1/ImagenesLab4/blob/main/R2.jpeg)


![](https://github.com/mjvilla1/ImagenesLab4/blob/main/Calculo%20del%20error%204.PNG)

![](https://github.com/mjvilla1/ImagenesLab4/blob/main/Calculo%20del%20error%204-.PNG)

# 5. Video

https://youtu.be/7LqhY4Y6EkY

# 6. Conclusiones

- El método o teorema de superposición es de gran utilidad para analizar circuitos quetengan dos o más fuentes, 
ya que al analizarlo fuente por fuente el análisis resultará mássencillo de realizar.
- Al resolver un circuito eléctrico por el método de superposición tendremos perdida dedecimales,
lo que causara que los resultados calculados varíen de los obtenidos en la simulación. 
- Se puede determinar que si la fuente no es la ideal esta se cortocircuita, pero se deja introducida
 en el circuito electrico.
 - De manera práctica aprendimos a implementar el teorema de supersición con la toma de medidas usando una sola 
 fuente de alimentación.


# 7. Bibliografía 

Khan Academy. (2021). Khanacademy.org. https://es.khanacademy.org/science/electrical-engineering/ee-circuit-analysis-topic/ee-dc-circuit-analysis/a/ee-superposition?modal=1


