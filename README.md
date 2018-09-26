TDDBC for Java with JUnit
====================================

これは、TDDBCのJava向けJUnitプロジェクトです。

## gradleを使う場合

### gradleのインストール(wrapperを使わない場合)

```bash
# Mac
$ brew install gradle
または、
$ sdk install gradle

# Unix
$ sdk install gradle
```
sdkについては、以下のURLを参考にしてインストールしてください

http://sdkman.io/

#### Windows
以下のURLを参考にしてインストールしてください。

http://gradle.monochromeroad.com/docs/userguide/installation.html

### gradle wrapperの準備

gradleをインストールしない場合は、このプロジェクトをcloneしてから以下のコマンドを実行してください。

```bash
# Mac, Unix
$ chmod +x gradlew
$ ./gradlew -v

# Windows
$ gradlew.bat -v
```

wrapperを利用する際は、以下のgradleコマンドを **./gradlew** または **gradlew.bat** に置き換えて利用してください。

### プロジェクトの変換

```bash
# for. IntelliJ IDEA
$ gradle idea

# for. Eclipse
$ gradle eclipse
```

### テストの実行

```bash
$ gradle test
```

### gradleによるJava Projectの作成(gradle 1.9以降)

gradleがインストールされている環境では、以下のコマンドを実行することで、Javaのプロジェクトを作成することが出来ます。

```bash
$ mkdir tddbc-java
$ cd tddbc-java
$ gradle init --type java-library
```

## mavenを使う場合
### インストール
```bash
# Mac
brew install maven
```
#### Windows, Unix
以下のURLを参考にしてインストールしてください。

http://maven.apache.org/download.cgi#Installation

### プロジェクトの変換
```bash
# for. IntelliJ IDEA
mvn idea:idea

# for. Eclipse
mvn eclipse:eclipse
```

### テストの実行
```bash
mvn test
```

## その他

動作環境、IDE等については[Wiki](https://github.com/tddbc/java_junit/wiki)を参照してください。

## ライセンス
Apache License, Version 2.0です (詳しくはプロジェクト直下の LICENSE-2.0.txt をご覧ください)
