# CraftsCore
![GitHub release (latest by date)](https://img.shields.io/github/v/release/CrAfTsArMy/CraftsCore)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/CrAfTsArMy/CraftsCore)
![GitHub](https://img.shields.io/github/license/CrAfTsArMy/CraftsCore)
![GitHub all releases](https://img.shields.io/github/downloads/CrAfTsArMy/CraftsCore/total)
![GitHub issues](https://img.shields.io/github/issues-raw/CrAfTsArMy/CraftsCore)

### Maven
```xml
<repositories>
  ...
  <repository>
    <id>craftsblock-releases</id>
    <name>CraftsBlock Repositories</name>
    <url>https://repo.craftsblock.de/releases</url>
  </repository>
  <repository> 
    <id>jcenter</id>
    <url>https://jcenter.bintray.com</url>
    <name>jcenter-bintray</name>
  </repository>
</repositories>
```
```xml
<dependencies>
  ...
  <dependency>
    <groupId>de.craftsblock.craftscore</groupId>
    <artifactId>CraftsCore</artifactId>
    <version>3.5.1-SNAPSHOT</version>
  </dependency>
  <dependency>
    <groupId>com.squareup.okhttp3</groupId>
    <artifactId>okhttp</artifactId>
    <version>4.10.0</version>
  </dependency>
  <dependency>
    <groupId>com.google.code.gson</groupId>
    <artifactId>gson</artifactId>
    <version>2.10</version>
  </dependency>
  <dependency>
    <groupId>mysql</groupId>
    <artifactId>mysql-connector-java</artifactId>
    <version>8.0.30</version>
  </dependency>
</dependencies>
```

### Gradle
```gradle
repositories {
  ...
  maven { url "https://repo.craftsblock.de/releases" }
  mavenCentral()
  jcenter()
}
```
```gradle
dependencies {
  ...
  implementation 'de.craftsblock.craftscore:CraftsCore:3.5.1-SNAPSHOT'
  implementation 'club.minnced:java-discord-rpc:2.0.2'
  implementation 'com.squareup.okhttp3:okhttp:4.10.0'
  implementation 'com.google.code.gson:gson:2.10'
  implementation 'mysql:mysql-connector-java:8.0.30'
}
```

## Issues
If you find any issues from the plugin or documentation please [open up issue](https://github.com/CrAfTsArMy/CraftsCore/issues)

## CraftsBlock
**Who or what is CraftsBlock?**
> CraftsBlock is a fairly new community server, which deals with the topic of programming. On our server you can ask questions about programming. But of course you can also just chill with the community.
>
> Also we are currently building our own small company, where you can ask certain questions for free, for your own app and or other programs.
>
> But we also offer you a free cloud where you get a storage limit of **momentarily** 500MB for free. (Later it will be 2.5GB!).

**Is everything really free?**
> CraftsBlock stands for implementing everything for free! That means you can get **all** services from CraftsBlock for free. However, we are currently working on a system where you can earn points by being active. With these points you can later buy more things, like the VIP rank.

**How do you find us?**
> We have a website where you can read more about it! https://craftsblock.de
>
> Of course you can also come to our Discord Server! https://discord.gg/craftsblock
>
> We are looking forward to you!
