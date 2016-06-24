# mnist-reader-scala
A reader for the MNIST data set using Scala and ND4J

##Dependencies

The only dependency is the ND4J library and a valid backend. The easiest way to do this is use the ND4J binary with the built in backend:

sbt:
```
classpathTypes += "maven-plugin"
libraryDependencies += "org.nd4j" % "nd4j-native" % "0.4-rc3.10" classifier "" classifier "<OS NAME>-x86_64"
```
Where `OS NAME` is the name of your operating system. For example `windows` or `linux`
