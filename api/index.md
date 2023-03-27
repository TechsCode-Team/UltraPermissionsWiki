# Overview
To use the api you will need to import it using either Maven or Gradle.
We do not offer a manual download of our API

<br>

# Dependency Information
By both importations you require to replace `{VERSION}` with the latest version number of our API. These can be found [**HERE**](https://repo.techscode.com/#browse/browse:maven-releases:me%2FTechsCode%2FUltraPermissionsAPI)

<br>

## Maven

```xml
<repository>
        <id>techscode</id>
        <url>https://repo.techscode.com/repository/maven-releases/</url>
</repository>

<dependency>
    <groupId>me.TechsCode</groupId>
    <artifactId>UltraPermissionsAPI</artifactId>
    <version>{VERSION}</version>
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
    compileOnly 'me.TechsCode:UltraPermissionsAPI:{VERSION}'
}
```

<br>

# Recomendation
When using methods of our API in the startup of your plugin you will need to add `UltraPermissions` to your softdepend or depend section in your plugin.yml

<br>

## Table of contents
- [Instance](./api/instance) - Getting the API instance
- [Groups](./api/groups) - Managing Groups (Ranks)
- [Permissions](./api/permissions) - Managing Permissions

<br>

[**Next part; Getting the API instance**](./api/instance)
