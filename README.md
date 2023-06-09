# Modelo de classificação com Spark

### Dados de marketing

    - from pyspark.sql import SparkSession
    - from pyspark.sql import functions as f
    - from pyspark.ml.feature import VectorAssembler
    - from pyspark.ml.classification import LogisticRegression
    - from pyspark.ml.classification import DecisionTreeClassifier
    - from pyspark.ml.evaluation import MulticlassClassificationEvaluator
    - from pyspark.ml.classification import RandomForestClassifier
    - from pyspark.ml.tuning import CrossValidator, ParamGridBuilder