---
theme: penguin
favicon: https://koki.me/favicon.ico
title: 成長するための努力をやめたエンジニアのこれまでとこれから
drawings:
  persist: false
mdc: true
overviewSnapshots: true
hideInToc: true
layout: intro
---

# 成長するための努力をやめたエンジニアの<br/>これまでとこれから

オープンセミナー2024@岡山  
2024.10.19

---
layout: presenter
presenterImage: https://koki.me/images/profile.jpg
hideInToc: true
---

# 佐藤光輝

Koki Sato

Classi 株式会社  
学習 PMF 部ソフトウェアエンジニア

- 26 歳
- エンジニア 7 年目
- 1 児の父

<div class="flex flex-col gap-2 mt-4">
<span>
<a href="https://github.com/koki-develop" target="_blank">
  <carbon:logo-github /> koki-develop
</a>
</span>
<span>
<a href="https://x.com/koki_develop" target="_blank">
  <carbon:logo-x /> koki_develop
</a>
</span>
</div>

---
hideInToc: true
---

# Classi 株式会社について

TODO: 書く

---
hideInToc: true
---

# 話すこと

TODO: 書く

---
hideInToc: true
---

# 話さないこと

TODO: 書く

---
hideInToc: true
---

# 伝えたいこと

TODO: 書く

---
hideInToc: true
---

# アジェンダ

<Toc />

---
layout: new-section
---

# キャリアを振り返る

---
level: 2
hideInToc: true
---

<Header :page="$page" />

# 略歴 {.!mb-4}

<Timeline :items="[
{ date: '2018.03', description: '音楽系の専門学校を卒業' },
{ date: '2018.04 ~', description: '貴金属の買取業者' },
{ date: '2018.06 ~', description: 'SES 企業' },
{ date: '2019.07 ~', description: 'Web 系自社開発企業' },
{ date: '2022.06 ~', description: 'IT コンサル企業' },
{ date: '2023.09 ~', description: 'Classi 株式会社' },
]" />

---
level: 2
hideInToc: true
class: flex flex-col items-center justify-center
---

<Header :page="$page" />

<p class="fixed top-1/5 left-1/2 transform -translate-x-1/2">
僕のキャリアを 3 つの期間にわけると...
</p>

<ol class="flex flex-col gap-4">
  <li v-click class="!text-4xl">体を壊すまで</li>
  <li v-click class="!text-4xl">心が折れるまで</li>
  <li v-click class="!text-4xl">エンジョイ期</li>
</ol>

---
layout: new-section
level: 2
hideInToc: true
---

<Header :page="$page" />

# 1. 体を壊すまで

---
level: 3
---

<Header :page="$page" />

# エンジニアになったきっかけ

1. なんやかんやあって新卒で入社した会社から転職を決意 {v-click}
1. ハローワークで SES 企業の求人を見つける {v-click}
1. 「プログラマーってなんだかカッコイイ！！」 {v-click .!text-4xl.font-bold.my-4}
1. 応募 {v-click}
1. 入社 {v-click}

→ エンジニアとしてのキャリアスタート！🎉 {v-click .font-bold.text-center}

---
level: 3
---

<Header :page="$page" />

# エンジニアとしての勉強の日々

- とにかく楽しかった
- できるだけ**睡眠時間を削って勉強してた**
  - 夜 12 時まで勉強
  - 朝 3 時に起きて勉強

<v-click>

- これを **1 年以上続けた**
  - 多少疲れても気にしなかった
  - 若かった (当時 21 歳)

</v-click>

その結果！！ {v-click .!text-4xl.font-bold.!mt-12}

<div class="h-[380px] w-[380px] absolute top-1/2 right-4 transform -translate-y-1/2">

<div class="text-center text-xl">
平日の時間割はこんな感じ
</div>

<PieChart :data="[
  { label: '睡眠', value: 3, color: '#999999' },
  { label: '勉強', value: 4, color: '#36A2EB' },
  { label: '朝の準備', value: 0.5, color: '#FFA500' },
  { label: '通勤', value: 1.5, color: '#4BC0C0' },
  { label: '仕事', value: 9, color: '#9966FF' },
  { label: '帰宅', value: 1.5, color: '#4BC0C0' },
  { label: 'お風呂・ご飯など', value: 1, color: '#FFA500' },
  { label: '勉強', value: 3.5, color: '#36A2EB' },
]" />

</div>

---
level: 3
class: flex flex-col items-center justify-center
---

<Header :page="$page" />

# 体を壊しました {.!text-5xl}

---
level: 3
---

<Header :page="$page" />

# 難病の発覚

<span/>

ある日から唐突に体のあちこちがおかしくなり始める
<ul>
  <li>右足が痺れたり</li>
  <li>顔の右半分が痺れたり</li>
  <li>右目の視界が欠けたり</li>
  <li>etc.</li>
</ul>

<v-click>

検査入院の結果、<b>多発性硬化症</b> <small>(指定難病13)</small> と診断された
<ul>
  <li>神経系の疾患で、原因は不明</li>
  <li><b>完治しない</b></li>
  <li>現在も継続的に通院中</li>
</ul>

</v-click>

---
level: 3
---

<Header :page="$page" />

# 体を壊したあと

- とにかくちゃんと寝るようにした
- **健康は大事**
  - マジで大事
  - 若くても油断しちゃダメ
    - 僕が難病にかかったのは **21 歳**
    - それまでは健康そのもので、大きな病気にかかったこともなかった

<br/>

---
layout: new-section
level: 2
hideInToc: true
---

<Header :page="$page" />

# 2. 心が折れるまで

---
level: 3
---

<Header :page="$page" />

# ( より一層 ) エンジニアとしての勉強の日々

TODO: まとめる

- エンジニアになって 4 年ほど経った頃、 IT コンサル企業に入社した
  - SRE 兼インフラエンジニアとして顧客のプロジェクト支援
- より高度な専門性を求められる環境
- 周囲は超つよつよエンジニアばかり

---
level: 3
---

<Header :page="$page" />

# 焦りと不安

TODO: まとめる

- 学べば学ぶほど知らないことが増えていく感覚
  - 「周囲の期待に応えなければ」
  - 「もっと技術力を身につけなければ」
  - 「もっとたくさん勉強しなければ」
- この頃には楽しさよりも義務感で勉強していた

---
level: 3
---

<Header :page="$page" />

# 焦りと不安

TODO: まとめる

- これまで以上にプライベートのほぼ全ての時間を勉強に充てる日々
  - 家族と過ごす時間すらももったいないと感じてしまう
  - そんな自身に対する自己嫌悪
- 終わりの見えない勉強の日々
- なんのために頑張っているのかもわからなくなった

その結果！！ {v-click .!text-4xl.font-bold.!mt-12}

---
level: 3
class: flex flex-col items-center justify-center
---

<Header :page="$page" />

# 心が折れました {.!text-5xl}

---
level: 3
---

<Header :page="$page" />

# 心が折れたあと

TODO: 書く

---
layout: new-section
level: 2
hideInToc: true
---

<Header :page="$page" />

# 3. エンジョイ期

---
level: 3
---

<Header :page="$page" />

# 新たな行動基準：楽しさ至上主義

TODO: 書く

---
level: 3
---

<Header :page="$page" />

# 仕事に対する考え方

TODO: 書く

---
level: 3
---

<Header :page="$page" />

# やらないこと

TODO: まとめる

- ポジティブなモチベーションが存在しなければ絶対にやらない
  - 「この技術、流行ってるからキャッチアップしないとな」 → やらない！
  - 「そろそろこういうスキルも身につけないといけないな」 → やらない！
- 楽しそうであればやる、そうでないことはやらない

<small>※ 納税とかはしてる</small>

---
layout: new-section
level: 1
---

# キャリアを振り返ってみて

---
level: 2
hideInToc: true
---

<Header :page="$page" />

# 「楽しさ至上主義」の前提条件

- 「最初から実践しておけばよかった」とは思っていない
- **自身の技術力に対する自信** と **経済的安定** の上に成り立っているもの
  - これらを得ることができたのは当時の**努力の結果**

→ キャリア初期の頃に実践することは不可能だった {v-click .font-bold.text-center.!text-3xl.!mt-12}

---
level: 2
hideInToc: true
---

<Header :page="$page" />

# 自分にとっての「楽しいこと」とは？

TODO: まとめる

- 楽しく生きていくためには自分にとっての楽しいことを見極める必要がある
- かつて僕は自分のことを「技術が好きな人間」だと思っていた
- 自分が何をしているときに楽しいと感じているか？
  - 技術を使って「動くものを作ること」が好き
- 技術そのものに対しては全く興味が持てない
  - 今もそう

---
level: 2
hideInToc: true
---

<Header :page="$page" />

# 成長するための努力をやめること<br/>≠ 成長をやめること

TODO: まとめる

- 努力をやめたあとも成長は続いている
  - 日々いろいろなところで新しい学びはある
  - 仕事を通じて or 趣味を通じて
- 成長曲線は緩やかかもしれないが、成長すること自体は目的ではないのでそれでいい
  - 仮に全く成長していないとしても全く問題ない

---
level: 2
hideInToc: true
---

<Header :page="$page" />

# 健康とキャリア

- **健康は大事。すごく大事。**
  - キャリアのために体を壊してしまったら元も子もない

<v-click>

- **キャリアも大事。すごく大事。**
  - 健康のためにキャリアをないがしろにしていいわけがない
  - 現実的な問題として、**お金**にも直結してくる
    - お金も大事

</v-click>

<v-click>

- **どちらも大事。すごく大事。**
  - 完全に両立できるに越したことはないが、それができれば苦労はしない
  - 要はバランスおじさん「要はバランス」

</v-click>

---
layout: new-section
---

# 今後のキャリアについて

---
hideInToc: true
---

# 今後のキャリアについて

- なにも考えてない
- なるようになる

---
layout: new-section
---

# まとめ

---
hideInToc: true
---

# まとめ

TODO: 書く

---
hideInToc: true
---

# おまけ

TODO: 書く

- スライドの作成には [Slidev](https://sli.dev/) を使用しました
- スライドのソースコードは GitHub で公開しています
  - [koki-develop/okayama-open-seminar-2024-slide](https://github.com/koki-develop/okayama-open-seminar-2024-slide)

---
layout: new-section
hideInToc: true
---

# ご清聴ありがとうございました
