# Prezto

zshのカスタマイズや管理のためのツールPreztoを導入する。
昔のMacはoh-my-zshだったけど重かったため移行。

## 導入

以下実行。

```shell
git clone --recursive https://github.com/sorin-ionescu/prezto.git "${ZDOTDIR:-$HOME}/.zprezto"
setopt EXTENDED_GLOB
for rcfile in "${ZDOTDIR:-$HOME}"/.zprezto/runcoms/^README.md(.N); do
  ln -s "$rcfile" "${ZDOTDIR:-$HOME}/.${rcfile:t}"
done
source ~/.zpreztorc
```

## 参考

- [preztoでzsh構築した時のメモ](https://qiita.com/Angelan1720/items/60431c85592fe90fcdd5)
