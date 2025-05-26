# Proyecto de ejemplo de construcción de un *package* y su publicación en *GitHub packages*

Lo relevante de este proyecto se encuentra en el fichero **pom.xml**, concretamente en la sección:
```
<distributionManagement>
        <repository>
            <id>github</id>
            <name>GitHub OWNER Apache Maven Packages</name>
            <url>https://maven.pkg.github.com/fpaniaguajava/ifct0062_2025_github_packages</url>
        </repository>
</distributionManagement>
```

Las instrucciones de publicación de paquetes con **GitHub packages** se encuentran en [este enlace](https://docs.github.com/en/actions/use-cases-and-examples/publishing-packages/publishing-java-packages-with-maven)
