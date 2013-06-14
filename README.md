# To run

    sbt run

# To build a single jar (distribution)

    sbt lwjgl-manifest-natives
    sbt one-jar

And, you can run the jar like:

    cd target/scala-2.10/
    java -Djava.library.path=../lwgl-natives -jar simghetto_2.10-1.0-one-jar.jar 

# To generate Intellij IDEA project

    sbt gen-idea
    

   
