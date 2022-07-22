# testing-plant-uml

Repo for first tests with PlantUML.

## Notes 2022 07 21

Enable to preview the diagram in VCS using a PLANT-UML plugin for VCS. But could note generate anything using the command line.

Got error `Unable to access jar file plantuml.jar`, to be investigated.

## Notes 2002 07 22

Figured out how to run plant uml from a CMD terminal using an environment variable called PLANTUML_JAR that points to the downloaded jar file.

```txt
java -jar %PLANTUML_JAR% sequence-diagram.plantuml
```

This same command does not seem to work in powershell. But can at least generate a UML diagram PNG version now from the command line.
