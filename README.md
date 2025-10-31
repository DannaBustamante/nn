# Preguntas de análisis

1. ¿Cuál es el promedio, mínimo y máximo de los atributos base (HP,
Attack, Defense, Speed) de todos los Pokémon?

<img width="435" height="106" alt="image" src="https://github.com/user-attachments/assets/61062fef-b544-4851-b700-42ac82681d18" />

los Pokémon presentan valores equilibrados entre ataque, defensa y velocidad, aunque el ataque suele destacar ligeramente.
Esto sugiere que el Attack Base es el atributo con mayor influencia promedio dentro de las estadísticas base.

2. Cree un histograma para visualizar la distribución de los valores de
Base Exp.
Interprete si la distribución es simétrica o sesgada.

<img width="573" height="456" alt="image" src="https://github.com/user-attachments/assets/b5ad5f6c-0b59-41bc-b572-f70b08ade50c" />

La distribución de los valores de Base Exp no es simétrica; se observa una mayor concentración de datos entre los valores 100 y 250, mientras que hay pocos Pokémon con valores superiores a 400.Esto indica que la distribución está sesgada. 

3. Análisis gráfico
Realice un boxplot comparando los valores de Attack Base entre los
tipos principales (Type1).
Identifique qué tipo tiene Pokémon con ataques más altos en promedio.
<img width="912" height="528" alt="image" src="https://github.com/user-attachments/assets/4e35308c-5958-4965-a5bc-7ad54024e5b1" />


Los tipos de Pokémon con valores más altos de Attack Base en promedio son:
-Dragon y Fighting, ya que sus cajas (y medianas) están situadas en niveles más altos del eje “Attack Base”.

4. Análisis estadístico
¿Cuál es el top 5 de especies (Species) más frecuentes en el dataset?

<img width="348" height="160" alt="image" src="https://github.com/user-attachments/assets/4912aa31-718b-4db5-8da5-6d8890defee2" />

El análisis muestra que las especies con mayor presencia en el dataset son:
1.	Paradox Pokémon (22 registros)
2.	Mouse Pokémon (14 registros)
3.	Fox Pokémon (9 registros)
4.	Dragon Pokémon (9 registros)
5.	Pumpkin Pokémon (8 registros)

Esto indica que la categoría Paradox Pokémon es la más común dentro del conjunto de datos, destacándose ampliamente frente a las demás especies.


5. Análisis gráfico
Genere un gráfico de barras que muestre la cantidad de Pokémon por
tipo principal (Type1).
¿Qué tipo es el más común?
<img width="847" height="576" alt="image" src="https://github.com/user-attachments/assets/46a569ed-b310-4cb6-8f29-6e1abcb93400" />


Se observa que el tipo Water (Agua) es el más común, con alrededor de 150 Pokémon, seguido por Normal y Grass (Planta).
Esto indica que los Pokémon de tipo Agua tienen una representación significativamente mayor en el dataset, lo que puede deberse a su gran variedad en las distintas generaciones del juego.

6. Análisis estadístico
Calcule la correlación entre los atributos HP Base, Attack Base,
Defense Base y Speed Base.
¿Qué atributos están más correlacionados entre sí?


<img width="483" height="110" alt="image" src="https://github.com/user-attachments/assets/7300bc1c-591d-41bd-9cdf-4676ab63a4e9" />

Los atributos más correlacionados entre sí son:
Attack Base y Defense Base.
Esto sugiere que los Pokémon con mayor ataque tienden a tener también una defensa relativamente alta, lo cual podría flejar un equilibrio en sus estadísticas de combate.

7. Análisis gráfico
Cree un heatmap (mapa de calor) con la matriz de correlaciones
obtenida en el punto anterior.
Interprete los resultados.

<img width="625" height="525" alt="image" src="https://github.com/user-attachments/assets/d91bb4e5-c509-4bcf-985e-1d6d7acfa2a0" />


Attack Base y Defense Base muestran el color más intenso: Son los atributos más correlacionados, lo que sugiere que Pokémon con alto ataque tienden también a tener buena defensa.

HP Base y Attack Base también tienen una correlación moderada: Pokémon con más puntos de vida suelen tener ataques algo mayores.

Speed Base tiene correlaciones más débiles con los demás atributos: Indica que la velocidad no depende mucho del HP, ataque o defensa.

8. Análisis gráfico
Realice un diagrama de dispersión (scatter plot) entre Weight_kg y
Attack Base.
¿Existe relación entre el peso de un Pokémon y su capacidad de ataque?

<img width="690" height="545" alt="image" src="https://github.com/user-attachments/assets/389527a8-82dd-47bc-ac00-80ee0cacf3d7" />

No parece existir una relación directa o fuerte entre el peso de un Pokémon y su capacidad de ataque.
El ataque base depende más de otros factores (como el tipo o la especie) que del peso corporal.


9. Análisis estadístico
Determine el promedio de altura y peso por tipo principal (Type1).
Interprete cuál tipo tiende a tener Pokémon más grandes.

<img width="350" height="397" alt="image" src="https://github.com/user-attachments/assets/3274a7a9-dcda-4e85-af38-b5e3bdcee500" />

Los Pokémon de tipo Steel son, en promedio, los más grandes y pesados, mientras que los de tipo Bug y Fairy son los más pequeños y livianos.

10. Análisis gráfico
Construya un gráfico de violín o boxplot múltiple comparando el
atributo Speed Base entre los tipos Flying, Electric y Ground.
¿Qué tipo de Pokémon tiende a ser más rápido?

<img width="693" height="543" alt="image" src="https://github.com/user-attachments/assets/87f7b4b3-6e69-4286-8aa9-f5f705327f02" />

Los Pokémon eléctricos son, en promedio, los más rápidos entre los tres tipos comparados, seguidos de los Flying y, finalmente, los Ground, que son los más lentos.



# Conclusion

los factores que más influyen en las estadísticas base de los Pokémon son su tipo y especie, ya que determinan si un Pokémon se enfoca en el ataque, la defensa o la velocidad, mientras que características físicas como el peso o la altura no muestran una relación significativa con el rendimiento en combate. Los tipos como Electric y Flying tienden a presentar mayores valores de velocidad, mientras que otros como Ground o Fighting destacan en fuerza o defensa, lo que indica que las diferencias en las estadísticas base se deben principalmente a la naturaleza y tipo del Pokémon, más que a su tamaño físico.




