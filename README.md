# Predicción de Resistencia a Penicilina usando Machine Learning y Bioinformática



Este proyecto aplica técnicas de **machine learning** y **bioinformática** para predecir la resistencia bacteriana a la penicilina a partir de secuencias genómicas. La resistencia a antibióticos representa una grave amenaza para la salud global, y este trabajo busca contribuir a su detección temprana mediante análisis computacional.

**Problema científico**: Las bacterias han desarrollado mecanismos de resistencia, principalmente mediante β-lactamasas (TEM, SHV), que inactivan la penicilina hidrolizando su anillo β-lactámico.

## Lo que buscamos es:

- **Predecir resistencia** a penicilina y otros usando características genómicas
- **Comparar algoritmos** de ML: Random Forest, MLP y Decision Trees
- **Analizar patrones** genómicos asociados a mecanismos de resistencia
- **Proporcionar herramienta** computacional para investigación en resistencia antibiótica

#

### Fuentes de Datos
- **`aro_index.tsv`**: Metadatos y etiquetas de resistencia desde [CARD Database](https://card.mcmaster.ca/)
- **`nucleotide_fasta_protein_homolog_model.fasta`**: Secuencias de nucleótidos para entrenamiento

### Estadísticas del Dataset
- **+2,000 genes** de resistencia analizados
- **20 clases principales** de antibióticos identificadas
- **Distribución balanceada** entre resistentes y no resistentes a penicilina
