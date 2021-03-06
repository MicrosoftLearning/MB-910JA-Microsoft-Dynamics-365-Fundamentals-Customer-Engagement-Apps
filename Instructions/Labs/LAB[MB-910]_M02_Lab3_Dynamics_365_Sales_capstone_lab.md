---
lab:
    title: 'ラボ 2.3: Dynamics 365 Sales キャップストーン ラボ'
    module: 'モジュール 2: Dynamics 365 Sales の基礎を学ぶ'
---

モジュール 2: Dynamics 365 Sales の基礎を学ぶ
========================

## 実践ラボ 2.3 - Dynamics 365 Sales キャップストーン ラボ

## ラボ シナリオ

ABC 社はセキュリティ機器の製造、販売、設置、サービスを専門としています。彼らの製品には、屋内と屋外の両方のセキュリティカメラ、湿気と火災のセンサー、監視サービスなどが含まれます。 

ABC 社は、Dynamics 365 アプリケーションを使用して、販売からサービスまで、組織のさまざまな領域にわたるすべての顧客と関わりを持っています。 

**営業とマーケティング**

ABC 社は、ターゲットを絞ったマーケティング キャンペーンを通じて、住宅の顧客に直接マーケティングを行っています。顧客は、都市やその他の要因に基づいてターゲットにされます。マーケティング資料は電子メールで送信され、電子メールでのやり取りに基づいてガイドされます。 

小さな製品の中には小売業者を通じて販売されているものもありますが、ほとんどの製品は社内の販売スタッフによって消費者に直接販売されています。

内部的には、2 つの重要な領域に焦点を当てています。 

- **住宅の顧客:** 住宅の顧客は通常、個々のコンポーネントを探しているか、家庭用ソリューション全体を購入しています。これらの販売サイクルは通常短く、ソーシャル メディア、Web サイト、紹介、または見込顧客からの直接の連絡から発生します。住宅の顧客は通常、特定の製品または小規模な設置に重点を置いているため、販売サイクルは通常、数日または数週間続きます。 

- **企業顧客:** 企業向け販売者は、より専門的で調整されたビジネス ソリューションを必要とする顧客に焦点を合わせています。企業向け販売は通常、リンクされたコミュニケーションで複数の場所にまたがり、プロジェクトを完了するために複数のリソースを必要とすることがよくあります。これらの販売サイクルは通常、より長く、より多くの可動部品があります。 

ABC 社のすべての販売者が、顧客に販売する際に、重点分野に関係なく必要なツール、リソース、およびガイダンスを持っていることが重要です。 

**システムの設置:**

購入したセキュリティ機器の設置プロセスは、販売した顧客の種類によって異なります。 

- **住宅の顧客:** 住宅への設置は通常 1 日もかからないため、社内の従業員が行います。販売が行われた後、作業指示書が作成され、資格のある技術者が特定され、設置を実行するようにスケジュール設定されます。 

- **企業顧客:** 企業への展開には数か月かかる場合があり、プロジェクト マネージャーが日常業務を監督する必要があります。これには、プロジェクト計画の作成、プロジェクト チームの定義、およびリソースのスケジュール設定が含まれます。 

**サービスおよびサポート:**

システムが設置されると、ABC 社は販売後サポートを提供します。顧客は問題がある場合は、カスタマー サポートに連絡できます。エージェントは、顧客とリモートで協力して問題を解決しようとします。問題をリモートで解決できない場合、サポート エージェントは、資格のあるフィールド技術者がスケジュールして作業する作業指示書に問題をエスカレーションできます。  

## 目的

あなたは ABC 社の住宅販売側の営業担当者として働いています。あなたのリードの多くは会社主催のイベント、マーケティング キャンペーン、購入リストからのものですが、それでも顧客から直接問い合わせを受けることがよくあります。これらの問い合わせを受けたら、販売ライフサイクルを通じてそれらのリードを手動で入力して処理する必要があります。 

最近、Piper Smithという名前の人から電話がありました。彼女の近所では一連の盗難事件があり、彼女はいくつかのホーム セキュリティ機器を購入したいと考えています。Piperをシステムにリードとして入力し、彼女を見込み評価して、販売サイクルを進めます。 

ラボが完了すると、次のことが完了します。

- リードを Dynamics 365 Sales に入力する

- リードを見込み評価し、営業案件に変換する。

- 営業案件に関連する日常の活動を管理する。 

- 営業案件に見積もりを追加する。 

- 営業案件を閉じる。 

- 請求書を生成する。 

## ラボのセットアップ

  - **推定時間**: 30 分

## 手順
  
## 演習 1: Dynamics 365 Sales のリードの作成と見込み評価


### タスク 1: 新しいリードの作成

1. 必要に応じて、InPrivate ブラウザーを開き、[https://home.Dynamics.com](https://home.dynamics.com/) に移動します。 

2. プロンプトが表示されたら、講師から提供されたユーザー資格情報を使用してログインします。 

3. 表示されるアプリケーションのリストから、**「営業ハブ」** を選択します。

4. 画面の左側にあるナビゲーションを使用して、**「リード」** を選択します。 

5. システム内の現在のすべての販売リードを表示するには、**「自分のオープンしているリード」** の横にある下向き矢印を選択し、表示されるメニューから **「アクティブなリード」** を選択します。 

6. リードのリストに戻るには、「アクティブなリード」 の横にある下矢印を選択し、表示されるメニューから **「自分のオープンしているリード」** を選択します。 

7. 次に、**「自分のオープンしているリード」** ビューから、コマンド バーの **「新規」** ボタンを選択して、Piper Smith の新しいリードを作成します。

8. 新しいリード レコードを次のように入力します。

	- **トピック:** セキュリティ機器を探しています – 「あなたの名前」

	- **名:** Piper

	- **姓:** Smith – あなたのイニシャル

	- **携帯電話:** 888 555-1762

	- **電子メール:** piper@sample.com

	- **番地 1:** 1989 191<sup data-htmlnode="">st</sup> Ave N

	- **市区町村:** シアトル

	- **都道府県:** ワシントン州

	- **郵便番号:** 98001 

9. コマンド バーの **「保存」** ボタンを選択して、新しいリードを保存し、開いたままにします。

10. レコードの上部に**リードから営業案件**のビジネス プロセス フローが表示されます。**「見込み評価ステージ」** をクリックして選択します。次のように入力して、ステージを完成させます。

	- **購入期間:** 今四半期

	- **推定予算:** 10000 

	- **購入プロセス:** 個人

	- **意思決定者の特定:** 完了

11. ステージ ウィンドウの **「X」** をクリックしてウィンドウを閉じます。 

12. 画面の中央にある **「タイムライン」** に移動して、**「プラス記号アイコン」** をクリックし、新しい活動を追加します。 

13. 表示されるメニューで、**「電話」** を選択します。

14. 「電話の簡易作成」 画面で、次のように電話を完了します。

	- **件名:** ホーム セキュリティ機器を探しています

	- **電話番号:** 888 555-1762

	- **方向:** 受信

	- **説明:** 彼女の近所でいくつかの事件の後、彼女はセキュリティ システムを購入しようとしています。 

15. **「保存して閉じる」** ボタンをクリックします。

16. **「ホーム セキュリティ機器を探しています」**アクティビティがレコードの**タイムライン**に表示されていることに注意してください。活動の上にカーソルを移動し、活動の完了の**チェック マーク アイコン**を選択して、電話を完了としてマークします。 

17. **「電話を閉じる」** ウィンドウで、状態が **「完了」** に設定されていることを確認し、**「閉じる」** ボタンを選択します。

 

**重要:** リード レコードを閉じないでください。次のタスクで使用するため、開いたままにしておきます。 

 

### タスク 2: 営業案件としてリードを見込み評価する

Piper を訪問した後、あなたは彼女の側に前に進めるための十分な関心があり、彼女に利益をもたらす製品とサービスを持っていることを確認します。次に、リード レコードを見込み評価します。これにより、関連する営業案件レコードが作成され、リードから営業案件への営業プロセス ステージに移動します。 

1. **コマンド バー**で、**「見込み評価」** ボタンを選択します。 

2. システムによってリードが見込み評価された後、新しい営業案件レコードが作成され、ビジネス プロセスは**開発**ステージに進みます。元のリード レコードを表示するには、**見込み評価**ステージを選択します。 

3. 営業案件に戻るには、**開発**ステージを選択します。

4. **「保存して閉じる」** ボタンをクリックして、作成された営業案件レコードを閉じます。 

 

 

## 演習 2: Dynamics 365 Sales で営業案件を管理する

リードを営業案件として評価することに成功したので、今度はそのライフサイクルを通じて営業案件を処理します。

### タスク 1: 営業案件を管理し、見積もりを作成する 

1. 画面の左側にあるナビゲーションを使用して、**「営業案件」** を選択します。 

2. **「自分のオープンされている営業案件」** ビューの横にあるドロップダウン矢印を選択し、表示されるメニューから **「オープンされている営業案件」** を選択します。

3. コマンド バーで、「グラフの表示」 を選択します。営業案件テーブルに基づいて、上位の顧客グラフが表示されることに注意してください。 

4. 「上位の顧客」 の横にあるドロップダウン矢印を選択し、表示されるメニューから **「営業パイプライン」** を選択します。

5. フィルターの見込み評価部分を選択します。営業案件のリストが変更され、見込み評価ステージにある営業案件に表示されることに注意してください。 

6. グラフの空白部分の任意の場所をクリックして、オープンされているすべての営業案件を再度表示します。 

7. **「オープンされている営業案件」** ビューの横にあるドロップダウン矢印を選択し、表示されるメニューから **「自分のオープンされている営業案件」** を選択します。 **「セキュリティ機器を探しています - あなたのイニシャル」** が表示される唯一の項目である可能性が高く、グラフはこれを反映している必要があります。 

8. **コマンド バー**で、**「グラフの非表示」** ボタンを選択します。 

9. 以前にリードを評価したときに作成された **「セキュリティ機器を探しています – あなたのイニシャル」** を開きます。レコードは、以前に評価されたリードから作成されたため、すでに**開発**フェーズにあることに注意してください。  

10. レコードの上部にある **「セキュリティ機器を探しています – あなたのイニシャル」** の営業案件ヘッダーで、所有者フィールドの横にある下矢印を選択します。 

11. 次のように完成させます。

	- **終了予定日:** 明日

	- **推定収益:** 12,500.00

12. 画面の中央にある**レコード タイムライン**に移動して、**プラス記号アイコン**をクリックし、新しい活動を追加します。 

13. 表示されるメニューから **「予定」** を選択します。

14. **「簡易作成: 予定」** 画面で、次のように完成させます。

	- **件名:** 簡易会議 – 「あなたのイニシャル」

	- **場所:** オンライン

	- **開始時間**: 明日の午前 10 時

	- **終了時間:** 明日の午前 10 時 30 分

15. コマンド バーで、**「保存して閉じる」** を選択します。

16. リードから営業案件へのビジネス プロセス フローで、**開発**ステージを選択します。関係者と競合企業を特定する必要があることに注意してください。

17. ステージ ウィンドウの **「X」** をクリックして閉じ、作業を続行できるようにします。 

18. **関係者**サブグリッドで、**Piper** が関係者として既に定義されているのに注目してください。 

19. 営業チーム サブグリッドで、**垂直の省略記号**を選択します。表示されるメニューから **「新しい接続」** を選択します。 

20. **「検索」** フィールドに **「システム」** というテキストを入力し、**「システム管理者」** レコードを選択します。完了したら、**「追加」** ボタンをクリックします。これで、システム管理者が営業チームに表示されます。コマンド バーで **「最新の情報に更新」** ボタンを選択します。 

21. 競合企業サブグリッドで、**垂直の省略記号**を選択します。表示されるメニューから **「既存の競合企業を追加」** を選択します。 

22. **「レコードの検索」** 画面で、**「新しいレコード」** を選択し、**「競合企業」** を選択します。

23. 「簡易作成:**競合企業**」 画面で、**「名前」** フィールドを **Coho Security – 「あなたのイニシャル」** に設定します。

24. **「保存して閉じる」** ボタンを選択します。

25. 作成した Coho Security レコードが選択されていることを確認し、**「追加」** ボタンを選択します。 

26. **リードから営業案件**ビジネス プロセス フローで**開発**ステージをクリックして選択し、**関係者の特定**ステップと**競合企業の特定**ステップを両方とも**完了**に設定します。 

27. ユーザーは、**「次のステージ」** ボタンをクリックして**提案**ステージに進みます。

28. **提案**ステージで、**営業チームの識別**を**完了**とマークします。

29. 提案ステージの **「X」** をクリックして、ステージ ウィンドウを閉じます。 

30. 営業案件レコードで、**「見積もり」** タブを選択します。 

31. 見積もりサブグリッドで、**「新しい見積もり」** ボタンをクリックします。

 

**重要:** これらの環境には複数のファースト パーティ アプリがデプロイされているため、現在表示されている見積もりフォームが販売関連機能の正しいフォームではない可能性があります。**「セキュリティ機器を探しています - あなたのイニシャル」** という見積もり名の下のテキストが次のようになっている場合は、**見積もりを読み取ります。見積もり**、正しいフォームが読み込まれます。その場合は、**見積もり**を読み取ります。**フィールド サービス情報**、それを切り替える必要があります。変更する必要がある場合は、**見積もり**の横にあるドロップダウン矢印を選択します。**フィールド サービス情報**。表示されるメニューから **「見積もり」** を選択します。 

 

### タスク 2: 見積もりを管理する

関連する見積もりができたので、顧客に提示するための見積もりを準備します。通常の状況では、顧客に納品される前に、見積もりレコードに製品を追加する可能性があります。共有環境で作業しているため、見積もり行の追加をスキップして、見積もりの配信について説明します。 

1. **コマンド バー**で、**「見積もりのアクティブ化」** ボタンを選択して、見積もりをアクティブ化します。 

2. 次に、営業案件に添付する価格表を選択する必要があります。  左側のペインの **「価格表」** で、「検索」 アイコンを選択し、オプションから **「既定の価格表」** を選択します。

3. 見積もりが作成されたので、新しいデータを反映するように営業案件レコードを更新しましょう。見積もりレコードで、**「販売情報」** セクションの **「営業案件」** フィールドで、 「**セキュリティ機器を探しています **– **「あなたの名前」**」 営業案件を選択します。営業案件レコードが画面に表示されます。 

3. 営業案件レコードで、**提案**ステージを選択します。 

4. **「プロポーザルの作成」**、**「内部レビューの完了」**、**「提案の提示」**を **「完了」** としてマークし、**「次のステージ」** ボタンをクリックして、**クローズ** ステージに進みます。 

5. **クローズ** ステージで、**「最終提案の完成」**、**「最終提案の表示」**、**「礼状の送信」**、および **「報告の保存」** のステップを **「完了」** としてマークします。 

6. **決定日の確認**を**今日の日付**に設定します。 

7. **「完了」** ボタンをクリックします。 

8. クローズ ウィンドウの **「X」** を選択してウィンドウを閉じます。 

9. **「見積もり」** タブを選択します。 

10. **「セキュリティ機器を探しています - あなたのイニシャル」**の見積もりを開きます。 

11. **コマンド バー**で、 **「注文の作成」** ボタンを選択します。

12. 「注文の作成」 ウィンドウで、次のように入力します。

	- **状態の理由:** 受注

	- **受注日:** 今日の日付

	- **営業案件のクローズ:** はい

	- **見積もりから実際の収益を計算する:** いいえ

	- **実売上:** $12,500

13. **「OK」** ボタンを選択する 

システムは、項目に関連する新しい販売注文を作成します。さらに、見積もりレコードと関連する営業案件レコードの両方を閉じます。すべてが完了すると、注文が画面に表示されます。注文は開いたままにします。 

###  

### タスク 3: 注文と請求書を管理する

これで販売注文が作成されたので、注文を閉じて請求書を生成します。通常の状況では、見積もりレコードの製品が販売注文に追加されます。共有環境で作業しているので、あたかも付属品のように進めていきます。 

 

1. **コマンド バー**で、**「注文の処理」** ボタンを選択します。 

2. 「注文の処理」 画面で、次のように入力します。

	- **状態の理由:** 完了

	- **処理日:** 今日の日付

3. **「処理」** ボタンを選択します。 

4. 注文の**コマンド バー**で **「請求書の作成」** ボタンを選択します。 

5. 請求書レコードが開いたら、**請求書の支払い完了** を選択します。
