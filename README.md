# Rotation-Bagged-Trees

Los ensamblajes de modelos predictivos son útiles para combinar modelos que, por separado, no tendrían un buen desempeño. Por ejemplo, se suelen utilizar diferentes técnicas de ensamblaje en árboles de decisión para que el modelo resultante tenga un gran poder predictivo, ya que los arboles de decisión por si solos presentan una gran varianza y en el caso de los árboles regresores, aumentan el MSE (Mean Square Error).

De esta manera, los algoritmos de ensamblaje (como bagging o boosting) se benefician de las diversas características que resultan de los modelos de árboles individualmente. Por lo anterior, la diversificación es un principio fundamental para mejorar el desempeño predictivo en el ensamblaje de modelos, por lo cual encontrar formas de diversificar los algoritmos predictivos se vuelve una tarea fundamental.

De esta manera, en este notebook se implementa un código que permita aplicar diversificación en el ensamblaje de árboles de decisión de una manera inédita: "Rotation Bagged Trees" y lo batimos en duelo contra los ensambles de árboles regresores normalmente usados : Bagging, Boosting y Random Forest.
