# Overview
Place this in either your pom.xml or build.gradle (depending what build system you are using)
In the event that this does not work, it is reccomended to join discord and let us know it isn't working.
<br>

# Dependency Information
## Maven

```xml
<repository>
        <id>techscode</id>
        <url>https://repo.techscode.com/repository/maven-releases/</url>
    </repository>
<dependency>
    <groupId>me.TechsCode</groupId>
    <artifactId>UltraPermissionsAPI</artifactId>
    <version>uperms-get-latest-version</version>
</dependency>
```
<br>

## Gradle
```groovy
repositories {
    maven {
      name = 'TechsCodeAPI'
        url = 'https://repo.techscode.com/repository/maven-releases/'
    }
}
dependencies {
    compileOnly 'me.TechsCode:UltraPermissionsAPI:1.0.0'
}
```
<br>

## Obtaining the instance
Once you have imported the API (see [Dependency](./api/dependency)), you must gain an instance of the API. 
This can be done by using:
<br>

```java
UltraPermissionsAPI api = UltraPermissions.getAPI();
```
<br>

Note: It is recommended to add UltraPermissions to the softDepend or depend section in plugin.yml, depending on your use. 