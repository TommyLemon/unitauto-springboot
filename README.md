# unitauto-springboot  [![](https://jitpack.io/v/TommyLemon/unitauto-springboot.svg)](https://jitpack.io/#TommyLemon/unitauto-springboot)
UnitAuto SpringBoot 库，可通过 Maven, Gradle 等远程依赖。<br />
UnitAuto SpringBoot Library for remote dependencies with Maven, Gradle, etc.

### Maven
#### 1. 在 pom.xml 中添加 JitPack 仓库
#### 1. Add the JitPack repository to pom.xml
```xml
	<repositories>
		<repository>
		    <id>jitpack.io</id>
		    <url>https://jitpack.io</url>
		</repository>
	</repositories>
```
<br />

#### 2. 在 pom.xml 中添加 unitauto-springboot 依赖
#### 2. Add the unitauto-springboot dependency to pom.xml
```xml
	<dependency>
	    <groupId>com.github.TommyLemon</groupId>
	    <artifactId>unitauto-springboot</artifactId>
	    <version>LATEST</version>
	</dependency>
```

<br />
<br />
<br />

### Gradle
#### 1. 在项目根目录 build.gradle 中最后添加 JitPack 仓库
#### 1. Add the JitPack repository in your root build.gradle at the end of repositories
```gradle
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```
<br />

#### 2. 在项目某个 module 目录(例如 `app`) build.gradle 中添加 unitauto-springboot 依赖
#### 2. Add the unitauto-springboot dependency in one of your modules(such as `app`)
```gradle
	dependencies {
	        implementation 'com.github.TommyLemon:unitauto-springboot:latest'
	}
```
