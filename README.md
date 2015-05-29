#Spark Streaming Example

## Run example

` 
mvn clean package
`

`
spark-submit --class examples.JavaNetworkWordCount target/spark-streaming-example-1.0-SNAPSHOT.jar localhost 9999
`

## Create new example
1. Add required dependencies into pom.xml
2. mvn package
3. spark-submit example
