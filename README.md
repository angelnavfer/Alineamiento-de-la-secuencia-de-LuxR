# Alineamiento-de-la-secuencia-de-LuxR
Alineamiento en Python de la secuencia de LuxR obtenido de iGEM (BBa_B0062) con la secuencia obtenida en UniProt (P35327) y la disponible por le grupo en Benchling. Código desarrollado en Google Colaboratory.

El código se divide en los siguientes puntos:
- Intalación del reposirotio PyRosetta + guardado de la información de las proteínas en un objeto _pose_ específico.
- Extracción de la secuencia de cada uno de los _pose_.
- Alineamiento de las secuencias entre sí mediante la función _pairwise2.align.globalxx_
