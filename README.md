# openapi-generator-maven-plugin-bug
A repository to reproduce a bug in openapi-generator-maven-plugin from version 5.3.1
```
mvn clean compile
```

will fail on branch `main` 
but will suceed on branch `feature/fix-code-generation-with-plugin-v5.2.1`
