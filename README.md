# Detección de zonas tumorales en resonancia magnética

Las imágenes de resonancia magnética (IRM) son una técnica de diagnóstico médico que permite obtener imágenes detalladas del interior del cuerpo humano. Utiliza campos magnéticos y ondas de radio para generar imágenes de alta resolución de los tejidos blandos, los órganos y las estructuras anatómicas.

La resonancia magnética se basa en la interacción entre los átomos de hidrógeno presentes en el cuerpo y los campos magnéticos. Durante el procedimiento, el paciente se coloca en un escáner de resonancia magnética, el cual contiene contiene un imán potente. Este imán produce un campo magnético uniforme en el área a examinar. Cuando se aplica un pulso de radiofrecuencia al cuerpo, los átomos de hidrógeno se alinean con el campo magnético y emite señales que son captadas por antenas, especiales en el escáner. Estas señales se procesan mediante algoritmos para generar imágenes bidimensionales o tridimensionales de la zona de interés.

Las IRM son muy utilizadas para visualizar tejidos blandos, como el cerebro, el corazón, los músculos o los órganos abdominales. Permiten detectar anomalías, como tumores, lesiones, inflamación o problemas estructurales, y proporcionan información detallada sobre la anatomía y la función de los tejidos.

La resonancia magnética es una técnica no invasiva y no utiliza radiación ionizante, lo que la convierte en una opción segura para la mayoría de los pacientes. Sin embargo, hay ciertas contraindicaciones, como la presencia de dispositivos médicos implantados o claustrofobia en algunos casos.

En el presente trabajo disponemos de imágenes IRM de perfusión. Este tipo de imágenes estudia como las moléculas de un contraste, inyectadas en el paciente, se difunden en el tejido estudiado a lo largo de una secuencia temporal, en nuestro caso 6 instantes.

Cada una de las 6 imágenes están formadas por matrices de 432x432 píxeles, representados en cada columna de la base de datos, es decir, cada columna contiene un total de 186.624 observaciones (píxeles) de la imagen en un instante de tiempo determinado. Según expertos, en el segundo instante de tiempo, se deben eliminar aquellos píxeles que presenten intensidades menores a 50, por lo que se han eliminado un total de 106.815 píxeles, quedando por tanto, 79.809 píxeles, de los cuales, 62 píxeles son de la zona con presencia tumor y 79.747 píxeles de la zona de no-tumor (sano).
