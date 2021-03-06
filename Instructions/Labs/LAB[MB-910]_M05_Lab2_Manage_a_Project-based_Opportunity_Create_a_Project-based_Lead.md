---
lab:
    title: 'ラボ 5.2: プロジェクトベースの営業案件を管理する'
    module: 'モジュール 5: Dynamics 365 Project Operations の基礎を学ぶ'
---

モジュール 5: Dynamics 365 for Operations の基礎を学ぶ
========================

## 実践ラボ 5.2 - プロジェクトベースの営業案件を管理する

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

ABC 社の企業向け販売者は、セキュリティのニーズにより専門的で調整されたビジネス ソリューションを必要とする顧客に注意を向けています。このため、企業向け販売は通常、リンクされたコミュニケーションで複数の場所にまたがり、プロジェクトを完了するために複数のリソースを必要とすることがよくあります。ABC 社の企業向け販売サイクルには数か月かかる場合があり、実行するには複数の可動部分が必要です。 

企業顧客がシステムを販売すると、プロジェクトの実装に数か月かかる場合があります。各プロジェクトは、プロジェクトの計画と日常業務を監督するプロジェクト マネージャーに割り当てられます。これには、プロジェクト計画の作成、プロジェクト チームの定義、およびリソースのスケジュール設定が含まれます。 

企業向け販売者は、カスタマイズされたハイエンドのセキュリティ ソリューションを顧客に販売する責任があります。最近、Consolidated Sample という会社から電話がありました。彼らは、すべての場所にまたがる完全に統合されたセキュリティ ソリューションを望んでいます。Consolidated Sample をリードとしてシステムに入力し、プロジェクトの販売サイクルを進めて、対応するプロジェクトを作成します。 

ラボが完了すると、次のことが完了します。

- リードを見込み評価し、プロジェクトの営業案件に変換する。

## ラボのセットアップ

  - **推定時間**: 20 分
  
## 演習 1: プロジェクトベースの営業案件を管理する 

プロジェクトベースのリードに基づいてプロジェクトの営業案件を正常に作成したので、この営業案件を使用して、プロジェクトに関連する高レベルの詳細を定義します。これには、製品と作業項目の定義、および販売関連の見積もりの定義が含まれます。 

### タスク 1: 営業案件を管理する 

1. 画面の左側にあるナビゲーションを使用して、**「営業案件」** を選択します。 

2. 自分のオープンされているプロジェクトのサービス営業案件のリストから、以前にリードを評価したときに作成した **「完全なグローバルセキュリティの実装 - あなたのイニシャル」** の営業案件を開きます。レコードは、以前に評価されたリードから作成されたため、すでに**開発**フェーズにあることに注意してください。  

3. レコードの上部にある **「完全なグローバルセキュリティの実装 - あなたのイニシャル」** の営業案件ヘッダーで、所有者フィールドの横にある下矢印を選択します。 

4. 次のように完成させます。

	- **終了予定日:** 明日

	- **推定収益:** 250,000.00

5. リードから営業案件へのビジネス プロセス フローで、**開発**ステージを選択します。関係者と競合企業を特定する必要があることに注意してください。

6. ステージ ウィンドウの **「X」** をクリックして閉じ、作業を続行できるようにします。 

7. **関係者**サブグリッドで、**Jean** が関係者として既に定義されているのに注目してください。 

8. 営業チーム サブグリッドで、**「新しい接続」** を選択します。(**「新しい接続」** ボタンが表示されない場合は、**「垂直の省略記号」** を選択し、表示されるメニューから **「新しい接続」** を選択します。) 

9. the **「検索」**フィールドに**「システム」**というテキストを入力し、**「講師から提供されたユーザー レコード」** を選択します。完了したら、**「追加」** ボタンをクリックします。これで、システム管理者が営業チームに表示されます。コマンド バーで **「最新の情報に更新」** ボタンを選択します。 

10. 競合企業サブグリッドで、**垂直の省略記号**を選択します。表示されるメニューから **「既存の競合企業を追加」** を選択します。 

11. **「Coho Security」**を検索して選択します。(Coho Security が存在しない場合は、**「新しいレコード」** を選択してから、**「競合企業」** を選択します。それ以外の場合は、手順 15 に進みます **。**)  

12. 「簡易作成: **競合企業**」 画面で、**「名前」** フィールドを **Coho Security – 「あなたのイニシャル」** に設定します。

13. **「保存して閉じる」** ボタンを選択します。

14. 前の演習で作成した Coho Security レコードを選択し、**「追加」** ボタンを選択します。 

15. **リードから営業案件**ビジネス プロセス フローで**開発**ステージをクリックして選択し、**関係者の特定**ステップと**競合企業の特定**ステップを両方とも**完了**に設定します。 

16. ユーザーは、**「次のステージ」** ボタンをクリックして**提案**ステージに進みます。

17. **提案**ステージで、**営業チームの識別**を**完了**とマークします。

18. 提案ステージの **「X」** をクリックして、ステージ ウィンドウを閉じます。 

19. 営業案件レコードで、**「営業案件ライン」** タブを選択します。

20. プロジェクトベースのライン サブグリッドから、「新しい営業案件ラインの追加」 ボタンを選択します。新しい営業案件ライン アイテムを次のように構成します。

	- **製品の種類:** プロジェクト ベースのサービス

	- **営業案件:** 完全なグローバル セキュリティの実装 – あなたのイニシャル

	- **名前:** システム開発

	- **顧客の予算:** 25,000

	- **請求方法:** 固定価格

21. **「保存して閉じる」** を選択します

22. **プロジェクトベースのライン** サブグリッドから、**「新しい営業案件ラインの追加」** ボタンをもう一度選択して、別のライン アイテムを追加します。   
‎新しい営業案件ライン アイテムを次のように構成します。

	- **製品の種類:** プロジェクト ベースのサービス

	- **営業案件:** 完全なグローバル セキュリティの実装 – あなたのイニシャル

	- **名前:** システム実装 

	- **顧客の予算:** 100000 

	- **請求方法:** 時間/実費払い

23. **「保存して閉じる」** を選択します
