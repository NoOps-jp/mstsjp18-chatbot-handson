# Tech Summit 2018 チャットボットハンズオン

## リポジトリの構成

ハンズオンマテリアルは開発環境別に用意しています。

```txt
.
├── csharp: ハンズオンマテリアル（C#, Visual Studio 使用）
│   ├── docs: 手順書
│   └── src: C# サンプルコード
└── nodejs: ハンズオンマテリアル（Node,js, VS Code 使用）
    ├── docs: 手順書
    └── src: Node.js サンプルコード
```

## ハンズオンのゴール

このハンズオンでは、以下を理解することをゴールとしています。

- Bot Service(Web App Bot) と Bot Builder V4 によるチャットボットの作り方を理解する
- Channel (Microsoft Teams, Slack) への接続方法を理解する

### プログラミング言語

以下の言語を用意しています。

- C#
- Node.js (Javascript)

### ハンズオンのシナリオ

以下の用意しています。リンクをクリックしてチャットボット開発を体験しましょう。

- **シナリオ1**: Azure上に、簡易なエコーを返すチャットボットを作成し、Microsoft Teams や Slack に接続して会話を行います。
  - [C# 版のハンズオンを開始する](./csharp/docs/01_EchoBot/01-01_create-webapp-bot.md)
  - [Node.js 版のハンズオンを開始する](./nodejs/docs/01_EchoBot/01-01_create-webapp-bot.md)

- **シナリオ2**: Azure 上に作成したチャットボットと、[QnA Maker](https://www.qnamaker.ai/) を接続して、Microsoft Teams や Slack に接続して会話を行います。
  - [C# 版のハンズオンを開始する](./csharp/docs/02_QnABot/02-01_create-webapp-bot.md)
  - [Node.js 版のハンズオンを開始する](./nodejs/docs/02_QnABot/02-01_create-webapp-bot.md)


> #　TODO add url link.
