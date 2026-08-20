# スライドテンプレート

YYYY-mm-dd の ○○ 集会で発表した際のスライド資料のソースです。

## コンパイル方法

TeX Live に同梱されている [moloch](https://github.com/jolars/moloch) を利用します。

```console
$ latexmk -lualatex
```

## 最適化

出力される PDF がかなり大きいため、必要であれば最適化します。

```console
$ ./optimize.sh
```
