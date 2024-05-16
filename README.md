## Getting Started

Welcome to the VS Code Java world. Here is a guideline to help you get started to write Java code in Visual Studio Code.

## Folder Structure

The workspace contains two folders by default, where:

- `src`: the folder to maintain sources
- `lib`: the folder to maintain dependencies

Meanwhile, the compiled output files will be generated in the `bin` folder by default.

> If you want to customize the folder structure, open `.vscode/settings.json` and update the related settings there.

## Dependency Management

The `JAVA PROJECTS` view allows you to manage your dependencies. More details can be found [here](https://github.com/microsoft/vscode-java-dependency#manage-dependencies).

## 動作内容とその結果

今回の課題で作成したコードはnumber.java,plusServer.java,plusTCPClient.javaの三つである。
これらのコードでやり取りできるのは足し算である。
clientが入れた2つの数字をserverが足し算して返すといったやり取りが行われる。
次はその実行結果である。

plusServer.java:
ポートを入力してください(5000など) → 4000
localhostの4000番ポートで待機します
接続しました。相手の入力を待っています......
足し算は765+346
答えは1111

plusTCPClient.java:
ポートを入力してください(5000など) → 4000
localhostの4000番ポートに接続を要求します
接続されました
足し算を送ります
一つ目の整数を入力してください ↓
765
二つ目の整数を入力してください ↓
346
サーバからのメッセージは...サーバーです。その足し算の答えは1111です