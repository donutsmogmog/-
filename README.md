### ER図
[![Image from Gyazo](https://i.gyazo.com/1d0fd9323b9b3f937afa29aa05236384.png)](https://gyazo.com/1d0fd9323b9b3f937afa29aa05236384)

### サービス概要

K-POPアイドルを全力で応援したい！そんなファンに役立つスケジュール管理ツールです。

- ライブやミート&グリート、CDリリース（カムバック）など、「推しグループ」のスケジュールを登録できます。
- 複数グループのスケジュールひとつのページで管理し、検索できます。
- 音楽番組ランキングの投票スケジュールなど、K-POP独自の情報を確認できます。

### このサービスへの思い・作りたい理由

私自身、コロナ禍でK-POP音楽を聴く様になり、K-POPアイドルグループを応援する様になりました。  
グループの活動スケジュールを把握する手段は主にオフィシャルサイトやX（旧Twitter）ですが、重要な情報を見落したり、情報を検索するのに苦労したりと困難を感じる場面が多々あります。特に複数のグループを応援しているとその困難さはさらに高まります。

そこで、自分の「推し」グループの活動スケジュールを一元化し、より一層「推し活」を楽しむことができるようにしたい、と思ったのがこのサービスを作ろうと思ったきっかけです。


### ユーザー層について

- K-POPアイドルオタク・ライト層（初心者）

  K-POP初心者にとってわかりづらい膨大で複雑なスケジュールを管理し、推し活を楽しんでもらいたい。

- K-POPアイドルオタク・ヘビー層（上級者）

  K-POPアイドルを推す人にとって大切な音楽番組ランキング投票などを理解し、推し活をさらに楽しんでもらいたい。


### サービスの利用イメージ

ユーザーは事務所からの公式のライブ・オフライン/オンラインのイベント・CD発売スケジュール・キャンペーン応募期間などをイベントとして登録することができます。イベント登録をすると、時系列にイベントを閲覧することができ、情報を把握しやすくなります。応援するグループやその所属する事務所が異なると、それぞれ情報を調べ、取得しなければなりません。サービスを利用することで複数のグループの情報をひとつのページで管理することができます。さらに検索機能を用いることで必要な情報をすぐに取得できます。


### ユーザーの獲得について

自分自身が応援用のXアカウントを所持しており、宣伝・告知する予定です。また、RUNTEQ用のXアカウントやイベントにて発信したいと考えています。


### サービスの差別化ポイント・推しポイント

類似サービスとしてモバイルアプリ「 [blip](https://blip.kr/jp) 」というアプリがあります。すでにアプリ側がアーティストのスケジュールだけでなく、SNS投稿情報など登録しており、記録・ログとしての意味合いが強いです。また、チケットの申し込みの締め切りなど、自分自身でイベントを登録することができません。「推し活において自分に必要な情報だけをカスタマイズし管理できる」という点においてサービスの差別化ができると考えます。

また、モバイルアプリとしてダウンロードをしなければならず、ユーザーの利用ハードルが高いと予想されるため、Webアプリとしての利用のしやすさを推しポイントとしていきたいです。加えて、音楽番組投票に関するスケジュールや特定のイベントまでのカウントダウン機能がないため、その機能を実装することで、差別化を図りたいと考えています。

### 機能候補


■ MVP

  - K-POP推し活紹介ページ（簡単な用語説明、音楽番組ランキングへの投票ガイド）
  - 会員登録
  - ログイン
  - イベント登録/詳細/編集/削除
  - イベント検索

■ 本リリース

  - LINEログイン機能
  - LINEでのイベント（申込み締切など）プッシュ通知
  - パスワードリセット機能
  - 対象イベント当日までのカウントダウン機能（カウントダウンを表示）
  - 公開イベントスケジュールページ
  - 公開イベントスケジュールからのコピー機能

### 機能の実装方針予定

- LINEログイン機能はDeviseを使用予定
- LINEのプッシュ通知はLINE Messaging APIを使用予定
- 公開イベントスケジュール（管理者が登録したスケジュール）のコピー機能はdupメゾットを使用予定

### 画面遷移図
Figma：https://www.figma.com/design/FRgf2nNpLLaUfKEzKbyTTf/%E5%8D%92%E6%A5%AD%E5%88%B6%E4%BD%9C_%E7%94%BB%E9%9D%A2%E9%81%B7%E7%A7%BB%E5%9B%B31?node-id=5-60&node-type=canvas&t=ujLmajIis78UabRD-0
