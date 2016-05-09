# license-mapping
For the  Maven NOTICE Generation Plugin

# How To Use it

* Declare the `maven-notice-plugin` in pom.xml specifying `licenseMapping`

```
<plugin>
  <groupId>org.jasig.maven</groupId>
  <artifactId>maven-notice-plugin</artifactId>
  <version>1.0.6.1</version>
  <configuration>
    <licenseMapping>
      <param>https://raw.githubusercontent.com/cyrille-leclerc/license-mapping/master/license-mappings.xml</param>
    </licenseMapping>
  </configuration>
</plugin>

```

* Execute `org.jasig.maven:maven-notice-plugin:generate` and fix  license-mappings.xml
