# Steps-to-configure-Pyspark
!pip install pyspark
!pip install -q findspark
import findspark 
findspark.init()
from pyspark.context import SparkContext,SparkConf
print(sc)
