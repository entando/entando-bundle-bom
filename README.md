# Instructions
- clone this project
- run the following command `./mvnw clean install -Dgpg.skip=true`
- Edit your pom.xml to add this one instead of the JHipster's one

```
    <dependencyManagement>
        <dependencies>
            <dependency>
                <groupId>org.entando</groupId>
                <artifactId>entando-bundle-bom</artifactId>
                <version>1.0.0-SNAPSHOT</version>
                <type>pom</type>
                <scope>import</scope>
            </dependency>
            <!-- jhipster-needle-maven-add-dependency-management -->
        </dependencies>
    </dependencyManagement>
```
