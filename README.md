In order to use CSE SDK, which is based on ServiceComb-java-chassis, you need to use the following maven mirrors. Or you can download 
maven artifacts and import it to your local maven repository.

```xml
  <mirrors>
    <mirror>
      <id>mirrorId</id>
      <mirrorOf>*</mirrorOf>
      <name>Mirror of central repository.</name>
      <url>http://maven.huaweicse.com/nexus/content/groups/public</url>
    </mirror>
 </mirrors>
```