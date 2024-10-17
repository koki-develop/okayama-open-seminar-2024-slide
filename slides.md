---
theme: penguin
favicon: https://koki.me/favicon.ico
title: 成長するための努力をやめたエンジニアのこれまでとこれから
titleTemplate:  '%s - オープンセミナー2024@岡山'
mdc: true
overviewSnapshots: true
colorSchema: light

presenter: true
record: false
drawings:
  enabled: false

layout: intro
hideInToc: true
---

# 成長するための努力をやめたエンジニアの<br/>これまでとこれから

オープンセミナー2024@岡山  
2024.10.19

---
layout: presenter
presenterImage: https://koki.me/images/profile.jpg
hideInToc: true
---

# 佐藤光輝 {.!mb-0}

Koki Sato {.!mt-2}

Classi 株式会社  
学習 PMF 部ソフトウェアエンジニア

- 26 歳 (1998 年 1 月生まれ)
- エンジニア 7 年目
- 1 児の父

<div class="flex flex-col gap-2 mt-4">
<span>
<a href="https://github.com/koki-develop" target="_blank" rel="noopener">
  <carbon:logo-github /> koki-develop
</a>
</span>
<span>
<a href="https://x.com/koki_develop" target="_blank" rel="noopener">
  <carbon:logo-x /> koki_develop
</a>
</span>
</div>

---
hideInToc: true
---

<div class="flex gap-6 items-center">
<img src="/classi.svg" class="h-18" alt="Classi">
<p class="font-bold !my-0">
Classiはさまざまな機能で、生徒の可能性をひきだし、<br/>理想の指導の実現をサポートします
</p>
</div>

Classiとは、コミュニケーション、探究学習、学習動画、日々の学習記録などを通じて、「先生方の授業・生徒指導」「生徒の学び・成長」をサポートするオールインワンのプラットフォームです。  
さらに、各分野のパートナーが提供する教育コンテンツとも多数連携し、学校の状況に応じて幅広いラインナップからお選びいただける連携サービスも用意しています。

![](/classi_cycle.png) {.h-54.fixed.bottom-4.left-1/2.-translate-x-1/2}

<Skip />

---
hideInToc: true
---

# 話すこと

- 僕がどのように考えながらエンジニアとしてのキャリアを歩んできたか
- それを踏まえて今はどのように考えているか

---
hideInToc: true
---

# 話さないこと

- エンジニアとしてキャリアを歩む上で「こうするべき」という話
- 「こうしておけばよかった」「あれはやめておけばよかった」という話

---
hideInToc: true
---

# 伝えたいこと

- のびしろを「**引き出さない**」という選択肢もある

---
hideInToc: true
---

# 前置き

- この発表内での「エンジニア」という単語は「IT エンジニア」を指します
- この発表内容はあくまで僕が個人としてどのように考えているかという話であり、所属する組織とは関係ありません
- 異なる考え方を否定する意図はありません

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
{ date: '2018.06 ~', description: 'SES 企業', highlight: true },
{ date: '2019.07 ~', description: 'Web 系自社開発企業', highlight: true },
{ date: '2022.06 ~', description: 'IT コンサル企業', highlight: true },
{ date: '2023.09 ~', description: 'Classi 株式会社', highlight: true },
]" />

<Arrow v-click="1" x1="400" y1="160" x2="290" y2="210" />

<p v-click="1" class="!text-3xl font-bold fixed left-[470px] top-[160px]">
エンジニアとしてのキャリア
</p>

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
  <li v-click class="!text-4xl font-bold">体を壊すまで</li>
  <li v-click class="!text-4xl font-bold">心が折れるまで</li>
  <li v-click class="!text-4xl font-bold relative">
    エンジョイ期
    <span class="mt-1 ml-4 !text-2xl font-normal absolute whitespace-nowrap">←イマココ</span>
  </li>
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

- めちゃくちゃ楽しかった
  - めちゃくちゃ勉強してた

<v-click>

- できるだけ**睡眠時間を削って勉強してた**
  - 朝 3 時に起きて勉強
  - 夜 12 時まで勉強

</v-click>

<v-click>

- これを **1 年以上続けた**
  - 多少疲れても気にしなかった
  - 若かった (当時 21 歳)

</v-click>

その結果！！ {v-click .!text-4xl.font-bold.!mt-12}

<div class="h-[380px] w-[380px] absolute top-1/2 right-4 transform -translate-y-1/2">

<div v-click="1" class="text-center text-xl">
平日の時間割はこんな感じ
</div>

<PieChart v-click="1" :data="[
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

- ちゃんと寝るようにした
- **健康は大事**
  - マジで大事
  - 若くても油断しちゃダメ
    - 僕が難病にかかったのは **21 歳**
    - それまでは健康そのもので、大きな病気にかかったこともなかった

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

# ( より一層 ) 勉強の日々

- エンジニアになって 4 年ほど経った頃、 IT コンサル企業に入社した
  - SRE 兼インフラエンジニアとして顧客のプロジェクト支援
  - 当時 24 歳
- より**高度な専門性**を求められる環境
  - 周囲は超つよつよエンジニアばかり
  - 追いつくために必死に勉強する日々

---
level: 3
---

<Header :page="$page" />

# 焦りと不安

- 勉強すればするほど知らないことが増えていく感覚
  - 「もっとたくさん勉強しなければ」
  - 「もっと技術力を身につけなければ」
  - 「周囲の期待に応えなければ」
- この頃には楽しさよりも**義務感**で勉強していた

---
level: 3
---

<Header :page="$page" />

# 焦りと不安

- これまで以上に**プライベートのほぼ全ての時間を勉強に充てる**日々
  - 睡眠時間は削れないので、他の時間をギリギリまで勉強に費やす
  - **家族と過ごす時間すらももったいない**と感じてしまう
    - そんな自分に対する自己嫌悪
- **終わりが見えない**
- 普通にしんどい

<v-click>

最終的には**なんのために頑張っているのかもわからなくなった**

</v-click>

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

# ※補足

- 当時の会社は非常に親身に相談に乗ってくれた & 業務量や人員の調整などの具体的なサポートもしてくれた
  - 人間関係も良好だったし居心地もめちゃくちゃ良かった
- そのうえで最後まで自分の中でうまく仕事 ( 勉強 ) とプライベートのバランスを取ることができなかった

---
level: 3
---

<Header :page="$page" />

# 心が折れたあと - 人生の目的の再考

- 自分にとっての**人生の目的**を真剣に考えてみた
  - 自分はなんのために生きているのか？
  - 自分は何がしたいのか？
  - 自分にとって大切なものは何か？
- 少なくとも、家族をないがしろにしてまで仕事を頑張るためではない

考え抜いた結論 {v-click .text-center.font-bold.!mb-2.!mt-8}

楽しく生きていきたい！ {v-click .text-center.!text-4xl.font-bold.!mt-0}

---
level: 3
---

<Header :page="$page" />

# 心が折れたあと - 人生の目的の再考

- 「**楽しく生きていく**」という目的を踏まえたうえで、自分はまだ努力を続ける必要があるだろうか？

<v-click>

- 技術者として、一流ではなくともそれなりに優秀だという自負はあった

</v-click>

<v-click>

- **じゃあもういっか！**

</v-click>

→ 「楽しさ至上主義」への移行 {v-click .text-center.!text-4xl.font-bold}

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

- 「**楽しいかどうか**」「**やってみたいかどうか**」が全て
- やってみたいと思ったら**即実行**
- 「やる意味」は**一切考えない**

<v-click :at="1">

思考回路の Before / After {.text-center.!text-xl.font-bold.!mb-0.!mt-4}

| | 以前 | **楽しさ至上主義** |
| :---: | :---: | :---: |
| 行動前の思考 | [「これをやる意味はあるだろうか？」]{v-click="2"}<br/>[「キャリアの役に立つだろうか？」]{v-click="2"} | [「楽しそう！！」]{v-click="4" .font-bold} |
| 行動後の思考 | [「あまり意味はなかったな...」]{v-click="3"}<br/>[「この時間があれば他に勉強できたな... 」]{v-click="3"} | [「楽しかった！！」]{v-click="5" .font-bold} |

</v-click>

<style>
table {
  @apply text-xl mx-auto max-w-18/20;
}
</style>

---
level: 3
---

<Header :page="$page" />

# 新たな行動基準：楽しさ至上主義

**最近やってること**

<ul>
  <li v-click>IME 開発 (興味本位で)</li>
  <li v-click>3D モデリング (おもしろそうだったので)</li>
  <li v-click>そろばん (やったことなかったので)</li>
  <li v-click>ジム通い (運動したかったので)</li>
</ul>

<br/>

<p v-click class="text-center">エンジニアとしてのキャリアに直接的には役立ってない</p>
<p v-click class="text-center font-bold !text-3xl">でも楽しいのでよし！！</p>

---
level: 3
---

<Header :page="$page" />

# 仕事に対する考え方

- 仕事においても**楽しさ**を重視することに変わりはない
- 人生で仕事に費やされる時間は多い
  - 睡眠時間を除くと 1 週間のうち仕事に費やされる時間は**約 3 割**

<div class="!ml-16 mb-2 mt-1">

仕事の時間を 8 時間 / 日、睡眠時間を 8 時間 / 日とした場合... {.!text-sm.!mt-0.!mb-1}

$$
(8 \text{時間} \times 5 \text{日}) \div ((24 \text{時間} - 8 \text{時間}) \times 7 \text{日}) \fallingdotseq 0.36
$$

</div>

- 「**楽しく生きていく**」という目的を達成するためには、<br/>これだけ多くの時間を「仕事だから」と割り切ることは**できない**

<style>
.slidev-katex-wrapper {
  p {
    margin: 0;
  }
  .katex-display {
    margin: 0;
  }
  .katex-html {
    @apply !text-2xl;
    text-align: left;
  }
}
</style>

---
level: 3
---

<Header :page="$page" />

# やらないこと

- ポジティブなモチベーションが存在しなければ**やらない**
  - 「この技術、流行ってるからキャッチアップしないとな」 → **やらない！**
  - 「そろそろこういうスキルも身につけないといけないな」 → **やらない！**
- 楽しそうであればやるが、そうでないことは**やらない！！**

<small>※ 本当にやらなきゃいけないことはしてる。納税とか。</small>

---
level: 3
---

<Header :page="$page" />

# 楽しさ至上主義を実践してみて

- 1 年以上この行動基準で過ごしているが、今のところは**特に困ってない**
- 後先を考えずに好きなことばかりやるの**超楽しい**
- 躊躇なく**新しいことへのチャレンジ**をすることができるようになった
- **家族との時間**も大切にできている
  - 家族と過ごすのは楽しい

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

- 「最初から実践しておけばよかった」とは**全く思っていない**
- **自身の技術力に対する自信** と **経済的安定** の上に成り立っているもの
  - これらを得ることができたのは当時の**努力の結果**

→ キャリア初期の頃に実践することは不可能だった {v-click .font-bold.text-center.!text-3xl.!mt-12}

---
level: 2
hideInToc: true
---

<Header :page="$page" />

# 自分にとっての「楽しいこと」とは？

- 「楽しく生きていく」ためには自分にとっての楽しいことを知る必要がある
- 自分が何をしているときに楽しいと感じているか？

<v-click>

僕の場合：

- 技術を使って「**動くものを作ること**」が一番楽しい
- **技術そのもの**に対しては**全く興味を持っていない**ということに初めて気づいた
  - ずっと自分は技術が好きな人間だと思っていたが、そうではなかった

</v-click>

---
level: 2
hideInToc: true
---

<Header :page="$page" />

# 成長するための努力をやめること<br/>≠ 成長をやめること

- 努力をやめたあとも**成長は続いている**
  - 日々楽しく過ごしてるだけでも色々なところで新しい学びはある
  - 仕事を通じて or 趣味を通じて
- 成長曲線は緩やかかもしれないが、**成長すること自体は目的ではない**ので OK

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
  - キャリアをないがしろにしていいわけがない
  - 現実的な問題として、**お金**にも直結してくる
    - お金も大事

</v-click>

<v-click>

- **どちらも大事。すごく大事。**
  - 完全に両立できるに越したことはないが、それができれば苦労はしない
  - 要はバランスおじさん「**要はバランス**」

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
- 将来のことは将来の自分が考えてくれる

---
layout: new-section
---

# まとめ

---
hideInToc: true
---

# まとめ

- あまり目指すべきエンジニア像ではない
- ポジティブに努力し続けられるのに越したことはない

<v-click>

- それでも**努力が辛くなってしまったとき**は一度見直してみるのはアリ
  - 「辛い努力はやめるべき」という話ではない
  - 「辛くても努力するべき」という話でもない
  - 何が目的なのか、どんな選択肢があるのかを正しく認識することは大事

</v-click>

<v-click>

- 一度努力をやめたら**二度と努力できなくなるわけでもない**
  - 僕もしばらくしたらまた努力を再開しているかもしれない
  - ライフステージや環境によって**常に目的や考え方は変わるもの**

</v-click>

---
hideInToc: true
---

# まとめ

- きっと僕の「**のびしろ**」はたくさん残ってる
- それでも「**のびしろ**」は必ずしも**引き出さなければいけないものではない**

---
hideInToc: true
---

# おまけ

- この発表資料は GitHub Pages でホスティングしています
  <ul>
    <li>ソースコードは GitHub で公開しています<br/>
    <carbon:logo-github /> <a href="https://github.com/koki-develop/okayama-open-seminar-2024-slide" target="_blank" rel="noopener">koki-develop/okayama-open-seminar-2024-slide</a></li>
  </ul>
- スライドの作成には [Slidev](https://sli.dev/) を使用しました
  - 超便利

---
layout: new-section
hideInToc: true
---

# ご清聴ありがとうございました
