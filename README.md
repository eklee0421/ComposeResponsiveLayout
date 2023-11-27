# responsive-layout-grid-compose
compose용 responsive layout grid 입니다. 



# Material Guideline
[Google Material Guideline](https://m2.material.io/design/layout/responsive-layout-grid.html)을 따릅니다.



# Set up for use
현재 [최신버전](https://jitpack.io/#nyangzzi/responsive-layout-grid-compose)은 - 입니다.

1. Add the JitPack repository to your build file (settings.gradle)
>	* groovy
>	```groovy
>	dependencyResolutionManagement {
>		repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
>		repositories {
>			mavenCentral()
>			maven { url 'https://jitpack.io' }
>		}
>	}
>	```
>
>	* kotlin
>	```kotlin
>	dependencyResolutionManagement {
>		repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
>		repositories {
>			mavenCentral()
>			maven { url = uri("https://www.jitpack.io" ) }
>		}
>	}
>	```


2. Add the dependency
>	* groovy
>	```groovy
>	dependencies {
>	        implementation 'com.github.nyangzzi:responsive-layout-grid-compose:Tag'
>	}
>	```
>
>	* kotlin
>	```kotlin
>	dependencies {
>	        implementation("com.github.nyangzzi:responsive-layout-grid-compose:Tag")
>	}
>	```



# How to use
Row와 Column 2가지 버전을 제공합니다.

(업데이트 예정입니다.)




# File Structure
```
Core
│  ResponsiveConfig.kt
│  Util.kt
│  
├─column
│      ResponsiveColumn.kt
│      ResponsiveColumnScope.kt
│      
└─row
        ResponsiveRow.kt
        ResponsiveRowScope.kt
        RowBreakPoint.kt
```


