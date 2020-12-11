# あまと[[fab fa-slideshare]]<<.title.blur>>
by amATO<<.blur>>

---
# 突然ですがみなさん[[far fa-angry]]<<.title>>

---
# スライド作るのめんどない？[[far fa-grimace]]<<.title>>

---
# なにがめんどいって<<.headline>>
- スライドのデザインをGUIでぽちぽち整理するのめんどくせぇ。。。
    - → そんな暇あったら話す内容に集中したい

---
# **その悩み、解決してみせます** [[fas fa-blind]]<<.title>>

---
# そう、 amATOならね [[fab fa-apple]]<<.blur.title>>

---
# amATOを推させてください！！<<.title>>
~~10分で終わるので許して...~~

---
# は？[[far fa-eye]]<<.headline>>

- amATO / あまと
- 自作のプレゼンテーションツール
- <u>マークダウン資料をお手軽にリッチなスライドへ</u>

---
# 要は[[fas fa-thumbtack]]<<.headline>>
- **マークダウンで資料を書く**
- **→ amATOがデザインをよろしくやってくれる**
- **→ 速攻でリッチなスライドが完成**
# ...が実現できる（実はこのスライドもamATO製）

---
# こんな感じ[[fas fa-hand-holding fa-rotate]]<<.headline>>

1. マークダウンで資料を書く

```markdown:markdown.md
# This is sample
## slide1 :)
---
## slide2 :X
---
## slide3 :D
```

2. amATOに渡す

```bash
$ amato-cli markdown.md -o artifact
```

3. ブラウザで成果物(html)を開く

```bash
$ open artifact/markdown.html
```

## ...だけ

---
# なにが嬉しい？[[fas fa-baby]]<<.headline>>
# 勝手にスライドデザインを最適化してくれるので、
# <u>プレゼン内容に集中できる</u>

---
# だれ向け？[[fas fa-baby]]<<.headline>>
- デザインに自信がない...
- デザインに時間をかけずさくっとプレゼン資料を作りたい
- 好みのエディタでプレゼン資料作りたいんじゃ！！
- Gitでバージョン管理させてくれ...

<br>

## そんな人におすすめ

---
# さらに<<.title>>

---
# さらに① <<.headline>>
# 成果物がHTMLだから、
# <u>webの膨大な資産を使える</u>

---
# さらに① - こんなことや...<<.headline>>

<div class="video">
    <iframe src="https://www.youtube.com/embed/Y9qlMc8fcXQ" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

---
# さらに① - こんなことも...!<<.headline>>
<br>
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3241.6804959267747!2d139.72788801555043!3d35.660242738729664!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x60188b771049dc33%3A0x5bfe0248594cc802!2z5YWt5pys5pyo44OS44Or44K6!5e0!3m2!1sja!2sjp!4v1607612234431!5m2!1sja!2sjp" width="65%" height="70%" frameborder="0" style="border:0;" allowfullscreen="" aria-hidden="false" tabindex="0"></iframe>

---
# さらに① - 種明かし<<.headline>>

```markdown:web.md
---
# さらに① - こんなことや...<<.headline>>
iframe src="https://www.youtube.com/embed/Y9qlMc8fcXQ" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen</iframe>

---
# さらに① - こんなことも...!<<.headline>>
iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3241.6804959267747!2d139.72788801555043!3d35.660242738729664!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x60188b771049dc33%3A0x5bfe0248594cc802!2z5YWt5pys5pyo44OS44Or44K6!5e0!3m2!1sja!2sjp!4v1607612234431!5m2!1sja!2sjp" width="65%" height="70%" frameborder="0" style="border:0;" allowfullscreen="" aria-hidden="false" tabindex="0"</iframe>
```
<br>

## <u>各種サービスの埋め込みタグが使える</u>

---
# さらに②<<.headline>>
# 飽き性のための、カスタムスタイル
### ( ~~そろそろお題回収します~~ )

---
# あまと[[fab fa-canadian-maple-leaf]]<<.title.blur>>
## style: aki<<.blur>>

---
# あまと[[fas fa-snowman]]<<.title.blur>>
## style: fuyu<<.blur>>

---
# さらに② - 種明かし<<.headline>>

# 秋スタイル [[fab fa-canadian-maple-leaf]]

```bash
$ amato-cli main.md --style aki
```

<br>

# 冬スタイル [[fas fa-snowman]]

```bash
$ amato-cli main.md --style fuyu
```
<br>

## <u>Oneコマンドでデザインテンプレートを切り替え</u>

---
# さらに③ - [[fab fa-npm]]<<.headline>>
# npm installであなたもすぐ使えます！！！！
```bash
$ npm install amato-cli -g
```

---
# さらに③<<.headline>>
# **Let's enjoy amATO life!!**

---
# まとめ<<.headline>>
- **amATO** / **あまと**
- マークダウン資料をお手軽にリッチなスライドへ
    - プレゼン内容にだけ集中できる
- さらに
    - 各種サービスの埋め込みタグが使える
    - Oneコマンドでデザインテンプレートを切り替え
    - npm installであなたもすぐ使える！！！！
- Repository: [github/amato-cli](https://github.com/uehr/amato-cli)

<br>

## 以上、布教でした。