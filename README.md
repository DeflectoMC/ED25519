A fast and small Ed25519 Java implementation by k3d3 and Mick Michalski

Built using Gradle and GitHub Workflow

### Original text:

```
This is the original Ed25519 implementation sped up a bit.
I unrolled some code, used built in functions to replace java
methods, and converted a recursive call into a loop.

I tested it alongside the original implementation to make sure
the functionality didn't change.

Mick Michalski
```

## Using as a dependency


### Maven

```
<repository>
   <id>jitpack.io</id>
   <url>https://jitpack.io</url>
</repository>

<dependency>
   <groupId>com.github.DeflectoMC</groupId>
   <artifactId>ED25519</artifactId>
   <version>v1.0.0</version>
</dependency>
```

### Gradle
```
repositories {
  maven { url 'https://jitpack.io' }
}

dependencies {
  implementation("com.github.DeflectoMC:ED25519:v1.0.0")
}
```
