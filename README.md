# README 

![Image](https://github.com/Abdallah4021/JetpackDemo/blob/master/blur-close-up-code-computer-546819.jpg)

JetpackDemo is a demo application to learn how to create an Android 3'rd party.

## Including in your project

Add jitpack.io to your project's repositories:

```groovy
    allProjects {
      repositories {
        google() 
        // required to find the project's artifacts
        // place last
        maven { url "https://www.jitpack.io" }
      }
    }
```


Add artifacts to your project:

```groovy

    dependencies {
        ...
	implementation 'com.github.Abdallah4021:JetpackDemo:v1.0.1'
    }
```


## Yeeeh log out your string 

```java

    Print.printOnLog("Hello")
```

