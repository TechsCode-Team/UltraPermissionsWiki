# How to import our API with Maven
<br>

## Add this to your pom.xml
```xml
<repositories>
    <repository>
        <id>techscode</id>
        <url>https://repo.techscode.com/repository/techscode-apis/</url>
    </repository>
</repositories>

<dependency>
    <groupId>me.TechsCode</groupId>
    <artifactId>UltraPermissionsAPI</artifactId>
    <version>5.5.2</version>
    <scope>provided</scope>
</dependency>
```

Our `Repository Manager` houses all publicly available API versions, each of which
is linked to its corresponding, officially named release build of UltraPermissions.
**View all public available** [**versions**](https://repo.techscode.com/#browse/browse:maven-releases:me%2FTechsCode%2FUltraPermissionsAPI)

<br>

# Recomendation
When using methods of our API in the startup of your plugin you will need to add `UltraPermissions` to your softdepend or depend section in your plugin.yml

<br>

## Table of contents
- [Instance](./instance) - Getting the API instance

<br>
