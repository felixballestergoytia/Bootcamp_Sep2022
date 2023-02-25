# Ejercicio Clustering. Detección de Anomalías

Uno de los usos de los algoritmos de clustering es la Detección de Anomalías, esto es, la detección de observaciones anómalas, aquellas que no siguen un comportamiento normal. Si el objetivo del clustering es encontrar grupos de elementos similares, aquellos elementos que no son similares a ningún grupo se pueden considerar como elementos anómalos.

Para este ejercicio vamos a usar un [Dataset de transacciones de tarjetas de crédito](https://www.kaggle.com/arjunbhasin2013/ccdata), donde cada observacion es un cliente distinto.

Nuestro objetivo es implementar un modelo que agrupa las transacciones apropiadamente y encontrar los potenciales outliers, es decir, aquellas transacciones que son sospechosas de ser un fraude o un error. Para resolver este ejercicio correctamente hay que investigar, en vez de simplemente seguir a rajatabla lo enseñado en el curso.
