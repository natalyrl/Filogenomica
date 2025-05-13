# Filogenómica
Se evaluó la filogenia de 23 especies de vertebrados a partir de enfoques coalescentes y concatenados, como se muestra a continuación:

## Árboles de máxima verosimilitud
### Considerando el alineamiento cocanteando como un solo locus 
![ArbolUnP](https://github.com/natalyrl/Filogenomica/blob/main/unpartitioned.jpg)

### Considerando el modelo a partir de la longitud de los genes
![ArbolP](https://github.com/natalyrl/Filogenomica/blob/main/partitioned.jpg)

En ambos árboles, las 23 especies se agrupan a acuerdo al grupo de vertebrados al que pertenecen:
* **Osteoíctios:** azul claro. Las especies forman un grupo monofilético.
* **Condrictios:** morado claro, solo la especie *Callorhinchus milii*.
* **Sarcopterigios:** rojo. *Latimeria chalumnae* es el único celacanto, por ende, está por fuera del grupo de los peces pulmonados, clado Dipnotetrapodomorpha: ((*Lepidosiren paradoxa*, *Protopterus annectens*), *Neoceratodus forsteri* ).
* **Tetrápodos**: verde. Forman un grupo monofilético, incluyendo **anfibios** (*Silurana tropicalis*) y **amniotas**.

Dentro de los amniotas:
* **Mamíferos:** comprendidos por **monotremas** (morado oscuro) como *Ornithorhynchus anatinus*; **marsupiales** (azul osrcuro) como *Macropus eugenii* y *Monodelphis domestica*; y **placentarios** (rosado) como *Mus musculus*, *Homo sapiens*, *Canis lupus familiaris*, *Dasypus novemcinctus* y *Loxodonta africana*.
* **Saurópsidos:** (naranja) comprendidos por **reptiles** como *Anolis carolinensis* y *Pelodiscus sinensis*, y **aves** como *Taeniopygia guttata*, *Gallus gallus* y *Meleagris gallopavo*.

Se logra apreciar que cuando se particiona el alineamiento y se considera la longitud de cada gen por separado (segundo árbol), el bootstrap aumenta para ciertos clados, como: *Loxodonta africana* y *Dasypus novemcinctus*; *Homo sapiens* y *Mus musculus*; y el grupo de saurópsidos comprendido por (*Anolis carolinensis*,(*Taeniopygia guttata*,(*Gallus gallus*,*Meleagris gallopavo*))). Entonces, aunque las longitudes de las ramas sean muy similares, el modelo estadístico aplicado en el segundo árbol proporcionó un mayor soporte a la filogenia de las especies.
