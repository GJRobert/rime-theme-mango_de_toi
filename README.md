# 「新鮮芒果感」Rime 配色主題/skin/theme

<img align=right src="https://raw.githubusercontent.com/GJRobert/rime-theme-mango_de_toi/master/screenshot.png">

## 發想
永康街，**冰館**，新鮮芒果冰，夏日限定。無奈「思慕昔」。有年紀的人就吃過「冰館」。吃盤暢快的冰，別太乾。

（其實我也是今天才知道「思慕昔」跟原本的老闆娘無關！！！☞ [【連鎖早餐王番外篇】冰館原址創立思慕昔　她被誤認是「前妻的復仇」](https://www.mirrormedia.mg/story/20171005bus023/)）

至於「Mango de toi」……是和大學的好友逛街時，總是聽到 Mango 專櫃半催眠般（意圖促進消費）播放的耳語，呵呵。

## 安裝

1) 執行 [東風破](https://github.com/rime/plum) 的 `rime-install` 命令安裝以下配方：

```bash
$ bash rime-install GJRobert/rime-theme-mango_de_toi
```

2a) 若為 Windows 小狼毫：

```bash
$ bash rime-install GJRobert/rime-theme-mango_de_toi:customize:frontend=weasel
```

2b) 若為 macOS 鼠鬚管：

```bash
$ bash rime-install GJRobert/rime-theme-mango_de_toi:customize:frontend=squirrel
```

3) 最後在 weasel.custom.yaml 或 squirrel.custom.yaml 中，將 `style/color_scheme:` 改為 `mango_de_toi`

## 相容性
鼠鬚管及小狼毫應該均可正常使用，但目前只有在鼠鬚管上測試過。

小狼毫好像有一些鼠鬚管所沒有的介面設定項目，該部分目前尚無研究，所以對於小狼毫而言可能還有可以再改進/細膩設定之處。歡迎 fork 自行設定/分享/回饋。

## 銘謝
* Rime 專案所有貢獻者
* 「Rime 西米」產生器（[小狼毫用](https://bennyyip.github.io/Rime-See-Me/)/[鼠鬚管用](https://gjrobert.github.io/Rime-See-Me-squirrel/)）加速調色過程
* 自動安裝部署之做法係參考 [lotem/rime-theme-windows10](https://github.com/lotem/rime-theme-windows10)，感謝 Lotem 弓辰
* MacDown
