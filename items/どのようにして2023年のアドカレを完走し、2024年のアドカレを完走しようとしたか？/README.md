:::note warn
書き上がってから読み直したんですが、自分のまとめ記事化してます。
リンクメインのコンテンツであることはご容赦ください。
:::

## （2023年）どうやったか？
まずはどんな記事を書いたのか斜め読み＆当時を振り返っていく

https://qiita.com/advent-calendar/2023/nomuraya_oreno

### 記事を書くのがつらくなる
https://qiita.com/nomurasan/items/b27fcaca2bb28d428a5b

> （中略）
書き続けるとなると別の話だ。
どんどんネタがなくなってくるのはもちろん、25日分の記事を書く事自体も苦痛になる。
筆者のアドベントカレンダーに登録している記事も投稿日を見て貰えばわかるが、１日１記事かけているか？というと時間がなくて下書き保存になってしまったり、公開予定時間（毎日7時）まで間に合わなくて投稿自体ができない記事があった。
去年は執筆時の作戦を間違えてしまって書くネタを忘れてしまったりしたぐらいだ。

これは2022年の失敗からの知見。

:::note
- １日１記事書くのではなく、書ける日は書いて、書けない日はストックを使おう
- 書けた記事はどんどん予約投稿にしよう
:::

改めて思うに、（我ながら）これはとても深い言葉だと思う。

> 記事を書き続けると嘘が書けなくなる

### 攻略法
> 毎年コンスタントに25記事書く事を考えた場合、毎月2記事ずつ書けば最も無理なく続けられるのではなかろうか。

当時はアドベントカレンダーだけを焦点に充てており、6〜7月開催のQiitaエンジニアフェスタを全く考慮していないので、この通りにならなかった。

![image.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/122800/13563601-f393-9083-63e6-4533cfa379a7.png)

戒め。アドベントカレンダーが25記事なのですごく頑張った方だと思うのだが、当時も今も38記事に届かなかったのは悔しい思い出となった。

#### 今だからこそ、エンジニアフェスタの反省
:::note warn
Qiitaエンジニアフェスタを見越した執筆リズムのコントロールが必要
:::

まず、38記事を対象期間中に書かなければならず、**対象期間はQiitaエンジニアフェスタの期間より短いということを認識する。**
（一週間あるから10記事ぐらいいけるやろ、の慢心があった）
今年は「2024/6/10 ~ 2024/7/17」、１日１記事をコンスタントに書き続けられれば達成できた

:::note
- エンジニアフェスタ：1/1〜5/31までに20記事（4記事/月）
- アドベントカレンダー：8/1〜11/30までに15記事（5記事/月）
:::

開催期間中に38記事書いたり、25記事書いたりすることと比較するとだいぶ実現可能な気がする。（≒きつい）

### その他、補足
他にもいいことを書いているが、元記事の通りなので略。
以下に2024年の今だからこそ思った話を述べていく。

#### AIを使えば記事を書くのは簡単？
:::note alert
下手するとAIを入れない方が早い可能性がある
:::

この疑問は、本質的には「投稿するだけなら１文字だけ書いて投稿し、後から編集すればいいじゃん」と言っているのに等しいと考える。
１文字投稿よりマシだが、AIに書かせた記事の内容の正確性・妥当性まで確認したか？（＝品質）まで考えると結果的に自力で書いた方が早い可能性が高い。

AI時代にこのような発言をする事がやや後ろ向きだな、と思わないでもないが記事を書き慣れていないうちは

#### 記事を「書く」AIを作ればよくない？
:::note
良いと思う（記事を書くAIを作ったことを記事にできる）
:::

本項のポイントはカッコ書きの中身である
「記事を書いたのはAIかもしれないが、記事のアイデアは（誰かからインスピレーションを得たとしても）100%自分で考えたことだし、記事の内容（品質）も経験から担保できる」という保証があることだ。

#### 記事を「考えて書く」AIを作れば良くない？
:::note warn
品質をどう担保するか？が課題
:::

この「考える」部分の情報ソースが問題という話をしたい。
同じLLMでもChatGPTを使うと学習したデータに依存した回答を返すし、ネット検索に対応させるとどんどん情報ソースの信頼性は落ちる（それっぽい回答を返しやすくなる）
その点で言えばNotebookLMはソースを限定的にできるというメリットはあるが、インポートするソースの信頼性を担保する作業が必要なのは変わらない。

## （2024年）これからやること・今やっていること
### GitHubで環境を整える
なんにせよ、まずは見られている状態を作る。見ている人がいるかどうかはあまり重要ではない（今見ている人はいなくても、未来には見ている人が出てくるので気にすること自体が無意味）

https://github.com/users/shimajima-eiji/projects/8

### ルールを決める
プライベートリポジトリなのでスクショ

![image.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/122800/58b9290d-f14f-d7d9-2bc3-c74dd55752e7.png)

ディスカッションの作成日が2023/12/25。去年のアドカレ投稿が終わったその直後からこのプロジェクトは始まっている。

### 【アドカレ専用】下書き記事のタイトルで投稿ステータスを管理する
我ながらこの案はいいな、と思っている
一応、QiitaのWebエディタには公式で「未投稿の下書きのみ表示」機能はあるのだが、Qiitaにおいて下書きとは

- まだ書いてる
- `投稿日を反映させずに`記事を事実上の予約投稿状態にしたい（要件を満たすために限定公開は不可）
  - ただし、連続投稿Weekなどバッジの取得要件には抵触しないため、限定公開の記事を一般公開できるように書き直す方法はあり
  - とはいえ、更新履歴は見えそうなので、見られても良い履歴の記事であることが大前提！

というステータスがある。
これを踏まえて、「未投稿の下書きのみ表示」を使う前提で以下をタイトルのプレフィクスに入れる

- 未完成：プレフィクスなし
  - 特に理由がない場合は何も書かなくて良さそう
- 【保留】タイトル〜：記事としては完成済み、投稿時未定
  - 連続投稿バッジを狙う場合、投稿時は未定だが記事を書く、という事は案外ある
  - 特に理由がなければ保留もなし。即時投稿で良さそう
- 【YYYY/MM/DD】タイトル〜：日付があれば投稿時間は決まっている事がわかりやすい
  - 特にアドカレの前に記事をストックする時に使いたい（エンジニアフェスタは投稿日を考慮しないため）
  - アドカレ期間中は予約投稿機能がある
  - QiitaCLIを使う場合はcronと組み合わせれば良いので、本工程自体が不要

なお、これらの運用をする場合は投稿時にプレフィクスを削除するだけで良い。投稿ステータスに変えた瞬間から未投稿の下書きからは表示されなくなるためだ。
また、下書き中は誤って公開しないようにタグは常に未入力にしておこう。公開ボタンを押すとエラーになる事を利用すると安全だ。

### 書きにくい記事（タイトル・設計）は早々に捨てる・諦める
エンジニア気質が強いとウォーターフォールな、というか設計フェーズの差し戻しをやりたくない気持ちがどうしても強くなりがちだが、30分書いてみて難産になりそうなら記事を捨ててしまうというのも一案だ。
あるいは、書きたい内容を抜粋してAIに台本を書かせてみて、適宜加筆・修正するのはダメだとは思わない。執筆で手が止まるよりは、検証に時間をかけた方がネタの一つ一つを大事にできるからだ。
特に序中盤でネタを捨てると、後半書くネタがなくて苦しむ地獄を味わった身としては難産のネタであったとしても貴重に思えてくる。
書くことの手が止まるのと、書く内容が思い浮かばず手が止まるのでは全く意味が違うので、どちらを採用するかは状況を見ながら判断しよう。

### 記事のネタは投稿数＋10記事分作っておこう
先ほどの内容に関連するが、記事を捨てやすくするということは、記事を作りやすい環境が整っていてこそできる。
たとえば、DockerをはじめとしたIaCが整備されている環境での開発体験と、BYODなどで直接手元のマシンで環境構築をしている場合では環境構築の難度やインストールエラーや再インストールなどの差し戻し修正の作業コストを考えてみるのと本質的には同じである。
普段から記事ネタをストックしておき、書きたいときに書けるレベルまで噛み砕いてメモをしておくと案外ストックは増えていく。
また、１日中ストックが増えない時と、瞬間的に大量のストックが生まれる瞬間があるので、常にメモできる環境を作っておこう

### 考えなくても手っ取り早く記事のネタが生まれる仕組みを作ろう
更に難しいオーダーをするが、オンラインor首都圏へのアクセスが容易であれば実は難しくない。
誤解を恐れずに言えば毎日何かしらのエンジニア勉強会があり、それも１日１回ではない。
インプットとアウトプットの回転率を上げられるようになると、記事ネタは向こうからやってくる状態になるだろう。

だからこそ、というわけではないが、AIに依存しない執筆環境も整えておくと更に捗る。

## アドカレは連続投稿Daily25である
:::note alert
去年は遅れながらでも投稿を続けていたので、厳密に言えば違うはず
ただし、今年がどうなのかは不明
:::

見方を変えてみると、連続投稿Week50があるのだから連続投稿Dailyがあってもおかしくなさそうだ。
が、Botで投稿しているかどうかだけでこの辺りの評価は変わってくるし、そもそもデイリーで投稿される記事が設計コンセプトが優秀なBotでもない限り、品質の低い記事を量産するだけになるだろう。
そう考えると、Weeklyはあっても良いがDailyはなくても良いと思う。

が、ソロでアドカレ完走だけはそうはいかない。
定量的にアウトプットを出し続けられるかどうか、というスキルが試される期間だと考えるべきだろう。
