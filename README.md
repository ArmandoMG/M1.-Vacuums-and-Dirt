# M1.-Vacuums-and-Dirt
Actividad M1 de algoritmos avanzados

## Analisis
Al estar haciendo distintos casos de pruebas variando los distintos parametros (manualmente) como Tiempo maximo de ejecucion, # de aspiradoras, # de mugre, etc. Pude notar varias cosas, principalmente 4:
* Si el numero de aspiradoras es sumamente mayoritario al de piso sucio (naturalmente), tardará menos en acabar la simulacion en la mayoria de los casos, dado que hay un factor azar, siempre se puede dar el caso de que llegue al tiempo maximo, mientras el numero de aspiradoras sea menor a MxN
* No se detallo pero el numero de aspiradoras siempre debe ser mayor a 0, si no el programa nunca acabara satisfactoriamente
* A mayor numero de suciedad, menos será la probabilidad de que acabe el programa satisfactoriamente
* El tiempo normalmente no influye, a no ser que sea muy pequeño o muy grande
