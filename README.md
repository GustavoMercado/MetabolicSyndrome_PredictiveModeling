# MetabolicSyndrome_PredictiveModeling

En este repositorio se encuentra el código desarrollado para ayudar a identificar el síndrome metabólico en jóvenes mexicanos. El objetivo es detectar la probabilidad de que, con base en sus medidas antropométricas, una persona tenga el valor de los triglicéridos y/o colesterol HDL alterados y posteriormente pronosticarles un valor.

1. DataPrep - Carga y preparación de los datos
2. DataExplor - Análisis exploratorio de los datos 
3. DataModelHDLClass y DataModelTriCLass - Modelos de clasificación para determinar si el paciente tiene (o no) distorcionados sus valores de HDL y triglicéridos, respectivamente, usando árboles de decisión y ensambles y las variables crudas.  
4. DataModelHDLClass-Log y DataModelTriCLass-Log  -  Modelos de clasificación para determinar si el paciente tiene (o no) distorcionados sus valores de HDL y triglicéridos, respectivamente, usando regresión logística, árboles de decisión y ensambles y las variables con WOE.
5. DataModelHDLReg y DataModelTriReg - Modelos de regresión para determinar los valores de HDL y triglicéridos del paciente, respectivamente, usando árboles de decisión y ensambles y las variables crudas.
6. PENDIENTES: Modelos de regresión para determinar los valores de HDL y triglicéridos del paciente, respectivamente, usando redes neuronales y las variables con PCA. 
