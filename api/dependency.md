# Overview
Place this in either your pom.xml or build.gradle (depending what build system you are using)
In the event that this does not work, it is reccomended to join discord and let us know it isn't working.

# Dependency Information
## Maven
Repository: 
```
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

## Gradle
```
repositories {
    maven {
      name = 'TechsCodeAPI'
        url = 'https://repo.techscode.com/repository/maven-releases/'
    }
}
dependencies {
    compileOnly 'me.TechsCode:UltraPermissionsAPI:uperms-get-latest-version'
}
```

## Obtaining the instance
Once you have imported the API (see [Dependency](./api/dependency)), you must gain an instance of the API. 
This can be done by using:
```
UltraPermissionsAPI api = UltraPermissions.getAPI();
```

Note: It is reccomended to add UltraPermissions to the softdepend or depend section in plugin.yml, depending on your use. 