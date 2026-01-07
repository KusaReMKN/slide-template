# スライドテンプレート

YYYY-mm-dd の ○○ 集会で発表した際のスライド資料のソースです。

## コンパイル方法

[matze/mtheme](https://github.com/matze/mtheme) で公開されている Metropolis を使っているため、予めインストールしておく必要があります。

```console
$ latexmk -lualatex
```

## 最適化

出力される PDF がかなり大きいため、必要であれば最適化します。

```console
$ ./optimize.sh
```
