JIGサンプル
============================================================
[![badge](https://github.com/dddjava/jig-sample/actions/workflows/jig.yml/badge.svg)](https://github.com/dddjava/jig-sample/actions/workflows/jig.yml)

[JIG](https://github.com/dddjava/jig) のサンプルです。
GradleやMavenの基本的な構成でのJIGの設定を示します。

## 説明
- [sample-gradle](./sample-gradle) GradleのシンプルなプロジェクトでJIGドキュメントが出力できる
- [sample-gradle-multi](./sample-gradle-multi) Gradleのマルチプロジェクトですべてを包含したJIGドキュメントが出力できる
- [sample-maven](./sample-maven) MavenのシンプルなプロジェクトでJIGドキュメントが出力できる
- [sample-maven-multi](./sample-maven-multi) Mavenのマルチプロジェクトですべてを包含したJIGドキュメントが出力できる
- [.github/workflows/jig.yml](.github/workflows/jig.yml#L47) GitHub ActionsでJIGドキュメントが出力できる

## スコープ

### すること
- よくみる構成でJIGドキュメントが出力できる
- CIでJIGドキュメントを出力していつでも参照できる状態にする

### しないこと
- あまりみない構成
- Gradle/Maven以外のビルドツールプラグイン
- すべてのJIGドキュメントを網羅する

## 動かし方
各ディレクトリのREADMEを確認してください。

### 動作確認
[GitHub Pages](https://dddjava.github.io/jig-sample/) の結果と同じような感じで見えればOKです。

## 動作環境
[JIGの動作環境](https://github.com/dddjava/jig/wiki/Getting-Started#%E5%8B%95%E4%BD%9C%E7%92%B0%E5%A2%83)も参照ください。

- JDK（17以降）がインストールされていること
- （図を出力したい場合）Graphvizがインストールされていること

## LICENSE
[LICENSE](./LICENSE) 参照


