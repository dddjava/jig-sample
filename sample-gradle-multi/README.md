Gradleマルチプロジェクトサンプル
============================================================

Gradleマルチプロジェクト構成のサンプルです。
`modules/zulu` に `jig-gradle-plugin` を導入しています。

Gradleプラグインでは、適用したプロジェクト（今回は `zulu` ）と依存プロジェクト（ `alfa` および `bravo` ）が対象になります。

## 実行方法

```
./gradlew jig
```

[index.html](./modules/zulu/build/jig/index.html) を開いてください。

