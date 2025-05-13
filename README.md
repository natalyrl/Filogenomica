# Filogenómica
Se evaluó la filogenia de 23 especies de vertebrados a partir de enfoques coalescentes y concatenados, como se muestra a continuación:

## Árboles de máxima verosimilitud
### Considerando el alineamiento cocanteando como un solo locus 
![ArbolUnP](https://github.com/natalyrl/Filogenomica/blob/main/unpartitioned.jpg)

### Considerando el modelo a partir de la longitud de los genes
![ArbolP](https://github.com/natalyrl/Filogenomica/blob/main/partitioned.jpg)

En ambos árboles, las 23 especies se agrupan a acuerdo al grupo de vertebrados al que pertenecen:
* **Osteoíctios:** azul claro. Las especies forman un grupo monofilético.
* **Condrictios:** morado claro. Solo la especie *Callorhinchus milii*.
* **Sarcopterigios:** rojo. *Latimeria chalumnae* es el único celacanto, por ende, está por fuera del grupo de los peces pulmonados, clado Dipnotetrapodomorpha: ((*Lepidosiren paradoxa*, *Protopterus annectens*), *Neoceratodus forsteri* ).
* **Tetrápodos**: verde. Forman un grupo monofilético, incluyendo **anfibios** (*Silurana tropicalis*) y **amniotas**.

Dentro de los amniotas:
* **Mamíferos:** comprendidos por **monotremas** (morado oscuro) como *Ornithorhynchus anatinus*; **metaterios** (azul osrcuro) como *Macropus eugenii* y *Monodelphis domestica*; y **euterios** (rosado) como *Mus musculus*, *Homo sapiens*, *Canis lupus familiaris*, *Dasypus novemcinctus* y *Loxodonta africana*.
* **Saurópsidos:** naraja. Comprendidos por **reptiles** como *Anolis carolinensis* y *Pelodiscus sinensis*, y **aves** como *Taeniopygia guttata*, *Gallus gallus* y *Meleagris gallopavo*.

Se logra apreciar que cuando se particiona el alineamiento y se considera la longitud de cada gen por separado (segundo árbol), el bootstrap aumenta para ciertos clados, como: (*Loxodonta africana*, *Dasypus novemcinctus*); (*Canis lupus familiaris*, (*Homo sapiens*, *Mus musculus*)); y el grupo de saurópsidos comprendido por (*Anolis carolinensis*, (*Taeniopygia guttata*, (*Gallus gallus*, *Meleagris gallopavo*))). Entonces, aunque las longitudes de las ramas sean muy similares, el modelo estadístico aplicado en el segundo árbol proporcionó un mayor soporte a la filogenia de las especies.


## Árbol de coalescencia
![ArbolC](https://github.com/natalyrl/Filogenomica/blob/main/species_tree_ASTRAL.tre.jpg)

Al comparar el árbol de coalescencia con los dos árboles de máxima verosimilitud, se observa que los grandes clados de vertebrados se mantienen en todas las filogenias reconstruidas: Osteíctios, Tetrápodos, Amniotas, Mamíferos (monotremas, metaterios y euterios) y Saurópsidos. Algunos clados tienen un soporte muy elevado en los tres árboles, por ejemplo:
* **Osteoíctios:** (((*Takifugu rubripes*, *Oreochromis niloticus*), *Danio rerio*), *Lepisosteus oculatus*)
* **Peces pulmonados:** (*Neoceratodus forsteri*, (*Protopterus annectens*, *Lepidosiren paradoxa*))
* **Aves:** (*Taeniopygia guttata*, (*Gallus gallus*, *Meleagris gallopavo*))
* **Metaterios:** (*Macropus eugenii*, *Monodelphis domestica*)
  
Sin embargo, se logran identificar algunas diferencias:
* *Callorhinchus milii* y *Latimeria chalumnae* intercambian posiciones: la primera aparece como hermana de los pulmonados y la segunda como hermana de todo ese clado (soporte bajo: 0.60/0.58).
* Aunque la separación Monotrema vs. Theria sigue bien respaldada, dentro de Theria el apoyo de metaterios vs. euterios baja a ~0.78, y en euterios la posición de *Canis lupus familiaris* resulta más cercana a *Homo sapiens* (en lugar de a *Mus musculus*).

También, se logra apreciar que aquellas ramas más largas reflejan separaciones con muchas más generaciones y se apoyan casi al 100%, como en los osteoíctios. Mientras que en ramas más cortas, como por ejemplo dentro de los metaterios, hay divergencias más rápidas en un menor número de generaciones, lo que podría explicar también el soporte más moderado o bajo para estos taxones.
