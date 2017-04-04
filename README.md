# font-jp-subset

オープンソース日本語フォントをサブセット化した内容と実体の記録。

## サブセットの内容

- [ALL](https://github.com/blivesta/font-jp-subset/blob/master/characters/all.txt)
  - [ASCII](https://github.com/blivesta/font-jp-subset/blob/master/characters/ASCII.txt)
  - [Geek Alfabet](https://github.com/blivesta/font-jp-subset/blob/master/characters/geek-alphabet.txt)
  - [Cyrullic Alfabet](https://github.com/blivesta/font-jp-subset/blob/master/characters/cyrillic-alphabet.txt)
  - [漢字JIS第1水準](https://github.com/blivesta/font-jp-subset/blob/master/characters/漢字JIS第一水準.txt)
  - [ひらがな](https://github.com/blivesta/font-jp-subset/blob/master/characters/ひらがな.txt)
  - [カタカナ](https://github.com/blivesta/font-jp-subset/blob/master/characters/カタカナ.txt)
  - [全角英数](https://github.com/blivesta/font-jp-subset/blob/master/characters/全角英数.txt)
  - [記号](https://github.com/blivesta/font-jp-subset/blob/master/characters/symbol.txt)

## Fonts

### [NotoSansCJKjp](https://github.com/googlei18n/noto-cjk)-Subset

| Weight     | otf         | woff2       |
|:-----------|:------------|:------------|
| Black      | `17.3 MB`   | `496 KB`    |
| Bold       | `17 MB`     | `504 KB`    |
| Medium     | `16.5 MB`   | `499 KB`    |
| Regular    | `16.4 MB`   | `497 KB`    |
| DemiLight  | `16.4 MB`   | `495 KB`    |
| Light      | `16.2 MB`   | `488 KB`    |
| Thin       | `15.2 MB`   | `462 KB`    |

### [NotoSansMonoCJKjp](https://github.com/googlei18n/noto-cjk)-Subset


| Weight     | otf         | woff2       |
|:-----------|:------------|:------------|
| Bold       | `17 MB`     | `505 KB`    |
| Regular    | `16.4 MB`   | `498 KB`    |

### [NotoSerifCJKjp](https://github.com/googlei18n/noto-cjk)-Subset

| Weight     | otf         | woff2       |
|:-----------|:------------|:------------|
| Black      | `22.9 MB`   | `639 KB`    |
| Bold       | `24.7 MB`   | `656 KB`    |
| SemiBold   | `23.9 MB`   | `640 KB`    |
| Medium     | `23.9 MB`   | `635 KB`    |
| Regular    | `23.6 MB`   | `626 KB`    |
| Light      | `23.5 MB`   | `615 KB`    |
| ExtraLight | `21.3 MB`   | `578 KB`    |

## CSS

```css
@font-face {
  font-family: "subsetFont";
  src: url("PATH/Font-Name-Regular.woff2") format('woff2'),
       url("PATH/Font-Name-Regular.woff") format('woff');
}
body {
  font-family: "subsetFont";
}
```

## サブセット化に使用したツール

- [サブセットフォントメーカー](http://opentype.jp/subsetfontmk.htm)
- [WOFFコンバータ](http://opentype.jp/woffconv.htm)
