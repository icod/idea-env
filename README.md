# Stuff for IntelliJ IDEA  

## Live Templates
A collection of [live templates](https://www.jetbrains.com/help/idea/using-live-templates.html) to be used in IntelliJ IDEA.

### [Java](https://github.com/icod/idea-env/blob/main/templates/java.xml)

#### `logger`
Generates an SLF4J logger instance declaration.
```java
private static final Logger LOGGER = LoggerFactory.getLogger($CLASS$.class); 
```
