Demo project that provides a minimal implementation of an annotation processor
that prints elements annotated by @PrintMe during compilation.

To build it:

```
mvn package
```

To test it:

1、if you run as java file alone, you can execute: 

```
javac -cp /path/to/aptdemo-1.0-SNAPSHOT.jar SomeTestClass.java
```

2、if you run gradle project, you can execute:
(1)、add dependencies: `compile files('jarFileLocation')` to your build.gradle file  
(2)、run `gradle clean build`

then you will see some infos in your console.

