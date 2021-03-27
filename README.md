# errors

org.springframework.beans.factory.UnsatisfiedDependencyException: Error creating bean with name 'org.springframework.boot.autoconfigure.orm.jpa.HibernateJpaConfiguration'

和 Apollo 配置有关系？
Spring Boot 整合 Apollo

https://www.cnblogs.com/qdhxhz/p/13449285.html
https://www.cnblogs.com/qdhxhz/p/13388054.html

Apollo 配置密码时进行加密？ENC(asfasdfdfasdfasdf)

https://juejin.cn/post/6844903877569937422

---
Spring 整合 MyBatis
```java
@Configuration
@MapperScan(basePackages = "com.dao.napafasdfl", sqlSessionTemplateRef  = "inaSFsdfgellSqlSessionTemplate")
@Profile({"prod","prod-schedule"})
public class InellConfig {
```

---
Plugin 'org.apache.maven.plugins:maven-project-info-reports-plugin:2.6' not found
Plugin 'org.apache.maven.plugins:maven-pmd-plugin:3.12.0' not found
Plugin 'org.codehaus.mojo:findbugs-maven-plugin:3.0.1' not found
Plugin 'org.jacoco:jacoco-maven-plugin:' not found
```xml

    <reporting>
        <plugins>
            <plugin>
                <groupId>org.apache.maven.plugins</groupId>
                <artifactId>maven-project-info-reports-plugin</artifactId>
                <version>2.6</version>
                <reportSets>
                    <reportSet>
                        <configuration>
                            <skip>true</skip>
                        </configuration>
                    </reportSet>
                </reportSets>
            </plugin>
            <plugin>
                <groupId>org.apache.maven.plugins</groupId>
                <artifactId>maven-pmd-plugin</artifactId>
                <version>3.12.0</version>
            </plugin>
            <plugin>
                <groupId>org.codehaus.mojo</groupId>
                <artifactId>findbugs-maven-plugin</artifactId>
                <version>3.0.1</version>
                <configuration>
                    <xmlOutput>true</xmlOutput>
                    <xmlOutputDirectory>target/site</xmlOutputDirectory>
                </configuration>
            </plugin>
            <plugin>
                <groupId>org.jacoco</groupId>
                <artifactId>jacoco-maven-plugin</artifactId>
                <reportSets>
                    <reportSet>
                        <reports>
                            <!-- select non-aggregate reports -->
                            <report>report</report>
                        </reports>
                    </reportSet>
                </reportSets>
            </plugin>
        </plugins>
    </reporting>
    
    ```
