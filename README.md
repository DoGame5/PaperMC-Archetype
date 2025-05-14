PaperMC - Archetype [![](https://jitpack.io/v/DoGame5/PaperMC-Archetype.svg)](https://jitpack.io/#DoGame5/PaperMC-Archetype)
===========
This is a simple Archetype made for programming plugins for Minecraft using PaperMC

How To (Plugin Developers)
------
#### Repository (for papermc-archetype)
##### Maven

```xml
	<repositories>
		<repository>
		    <id>jitpack.io</id>
		    <url>https://jitpack.io</url>
		</repository>
	</repositories>
```

```xml
	<dependency>
	    <groupId>com.github.DoGame5</groupId>
	    <artifactId>PaperMC-Archetype</artifactId>
	    <version>PaperMC-1.20.4</version>
	</dependency>
```
##### Gradle (settings.gradle)
```kotlin
	dependencyResolutionManagement {
		repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
		repositories {
			mavenCentral()
			maven { url 'https://jitpack.io' }
		}
	}

	dependencies {
	        implementation 'com.github.DoGame5:PaperMC-Archetype:PaperMC-1.20.4'
	}
```
##### Gradle (settings.gradle.kts)
```kotlin
	dependencyResolutionManagement {
		repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
		repositories {
			mavenCentral()
			maven { url = uri("https://jitpack.io") }
		}
	}

	dependencies {
	        implementation("com.github.DoGame5:PaperMC-Archetype:PaperMC-1.20.4")
	}
```
