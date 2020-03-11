# Macの環境設定まとめ

Macで実施している個人的な環境設定集

以下、このリポジトリの方針

| 項目 | やるかやらないか | 備考 |
|:-:|:-:|:-:|
|使用ツールなどのまとめ| ● | webアプリからツールなど特に制限なし |
|設定ファイルの保管| ● | ツールごとにディレクトリ分け |
| 個別の導入手順[^１] | ▲ | 公式や記事のリンク参照しつつ一部書く |

[^１]: パスとか簡単な設定は書くかも

## 必須の初期設定

`setup.sh`で必要なアプリやツールをインストールする。

## Terminal関連

zshを使いやすくカスタマイズするために以下を導入した。
また、ターミナルアプリとしてHyperを利用

- Prezto
- Starship

### Prezto

昔のMacはoh-my-zshだったけど重かったため移行。

### Starship

Promptの装飾用プラグインStarship
採用理由 = 流行ってた & 見やすかった

- [公式ページ](https://starship.rs/)
- [githubのリポジトリ](https://github.com/starship/starship)

### Hyper

ちょいちょいバグる。
iTerm2でもいい気がしたけど軽量（という噂）さと設定ファイルがjsだったので採用してみた。

### vim

ターミナルのエディタはvimを使用。
採用理由 = 一番馴染みがあったから。

### others

#### Font

最初は[Ricity Font](https://rictyfonts.github.io/)を使っていたもののIconなどが豊富な[Nerd Fonts](https://github.com/ryanoasis/nerd-fonts#font-installation)に切り替え。

## 各ツール
