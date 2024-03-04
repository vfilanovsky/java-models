# Build
```
cd tensorflow-examples
mvn clean package
```

# Run
```
java -cp target/tensorflow-examples-0.3.1-SNAPSHOT-jar-with-dependencies.jar org.tensorflow.model.examples.cnn.lenet.CnnMnist 15 128 adam
```
