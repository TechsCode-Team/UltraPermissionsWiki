# How to import our API with Gradle
<br>

## Add this to your build.gradle
```groovy
repositories {
    maven {
        name = 'TechsCodeAPI'
        url = 'https://repo.techscode.com/repository/maven-releases/'
        }
}
dependencies {
    compileOnly 'me.TechsCode:UltraPermissionsAPI:5.5.2'
}
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
