# Grupo9DataScienceYPF
Curso Data Science a cargo de YPF, repositorio donde se lleva a cabo el PROYECTO FINAL del Grupo 9
Integrantes : Gabriel Ollier - Augusto Rosso - Oscar Gallardo


Durante el desarrollo del proyecto, quisimos destacar un hallazgo metodologico fundamental obtenido al aplicar la validacion temporal estricta (TimeSeriesSplit y corte cronologico Ene-Abr vs. May-Jun): el modelo de regresion arrojo un R2 negativo en el conjunto de prueba debido al cambio drastico de regimen termico entre verano/otonio e invierno (no estacionabilidad climatica). Lejos de ocultar esta limitacion, el comportamiento fue debidamente documentado y justificado en el notebook como una restriccion natural al extrapolar datos meteorologicos estacionales fuera de su rango de entrenamiento original.
