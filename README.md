## camel3-archetype-spring-boot

Generate project

```
mvn archetype:generate \
-DarchetypeGroupId=org.apache.camel.archetypes \
-DarchetypeArtifactId=camel3-archetype-spring-boot \
-DarchetypeVersion=1.0.0 \
-DgroupId=org.apache.camel.archetypes.archetypeIT.camel-archetype-spring-boot \
-DartifactId=build-it \
-Dversion=0.0.1 \
-Dpackage=org.apache.camel.archetypes.archetypeIT \
-Dmaven-compiler-plugin-version=3.8.1 \
-Dspring-boot-version=2.6.2 \
-Dcamel-version=3.14.0
```