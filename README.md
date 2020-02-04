# VDM++仕様を対象としたテストケース自動生成ツールBWDMにおけるペアワイズ法とドメイン分析テストの適用のための機能拡張

俺の修論です。

- [修論本体](https://github.com/korosuke613/master-thesis/blob/master/2020_01_27_v2_T1803035_%E5%B9%B3%E6%9C%A8%E5%A0%B4%E9%A2%A8%E5%A4%AA_%E4%BF%AE%E8%AB%96.pdf)
- [発表スライド](https://www.slideshare.net/FutaHirakoba/vdmbwdm)


## build

```bash
latexmk
```

`MasterPaper.pdf`という実行ファイルができているはず。


## optional
VS Codeのremote container機能を使えば、楽楽執筆が可能です。

1. `git clone https://github.com/korosuke613/texlive-ja-devcontainer-template.git`
2. VS Codeで`texlive-ja-devcontainer-template`を開く。
3. 拡張機能[Remote Development](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack)を追加する。
4. 左下の`><`アイコンを押して、`Rebuild Container`を実行する。
5. 待つ。
6. ワークスペースが開いたら、terminalを開き、`latexmk`を実行する。もしくは、`Cmd + `
7. 上手くコンパイルできたらsetup完了！

