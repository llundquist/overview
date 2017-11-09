---


copyright:
  years: 2016, 2017
lastupdated: "2017-05-23"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# {{site.data.keyword.Bluemix_notm}} コンソールの機能
{: #bluemixoverviewui}

{{site.data.keyword.Bluemix_notm}} コンソールにアクセスすると、メニュー・バーに、登録、ログイン、資料へのアクセス、およびカタログへのアクセスのためのリンクやボタンが表示されます。ログイン後、メニュー・バーには、アカウント・タイプに応じて、メニュー・アイコン ![メニュー・アイコン ](../icons/icon_hamburger.svg) と追加リンクが含まれています。

## コンソールの使用
{: #consoleoptions}

メニュー・バーから、以下のオプションが使用可能です。

* 新規 {{site.data.keyword.Bluemix_notm}} ユーザーの場合、メニュー・アイコン ![メニュー・アイコン](../icons/icon_hamburger.svg) を使用して、「アプリ」、「サービス」、および「インフラストラクチャー」の各ダッシュボード間で切り替えることができます。**「カタログ」**リンクを使用して、プラットフォームおよびインフラストラクチャーのサービスにアクセスできます。サポートおよびアカウント、請求および使用量、セキュリティー管理の各オプションへのリンクも表示されます。
* {{site.data.keyword.Bluemix_notm}} アカウントを使用している既存のユーザーの場合、メニュー・アイコン ![メニュー・アイコン](../icons/icon_hamburger.svg) を使用して、「アプリ」ダッシュボードおよび「サービス」ダッシュボード間で切り替えることができます。**「カタログ」**リンクを使用して、プラットフォームおよびインフラストラクチャーのサービスにアクセスできます。プラットフォーム・レベルのサポートおよびアカウント、請求および使用量、セキュリティー管理の各オプションへのリンクが表示されます。
* 既存のユーザーで、{{site.data.keyword.Bluemix_notm}} と {{site.data.keyword.BluSoftlayer}} アカウントをリンクしている場合、メニュー・アイコン ![メニュー・アイコン](../icons/icon_hamburger.svg) を使用して、「アプリ」、「サービス」、および「インフラストラクチャー」の各ダッシュボード間で切り替えることができます。また、**「カタログ」**リンクを使用して、プラットフォームおよびインフラストラクチャーのサービスにアクセスできます。
  * 「アプリ」と「サービス」のダッシュボードでは、{{site.data.keyword.Bluemix_notm}} 資料、サポート、アカウント、セキュリティー管理の各オプションなど、プラットフォーム・レベルのリソースへのリンクがメニュー・バーに含まれています。また、インフラストラクチャー・レベルの請求処理オプションへのリンクにもアクセスできます。
  * 「インフラストラクチャー」のダッシュボードでは、KnowledgeLayer ヘルプ、連絡オプション、通知、オープン・チケット、サポートおよびアカウント管理の各オプションなど、インフラストラクチャー・レベルのリソースへのリンクがメニュー・バーに表示されます。
* {{site.data.keyword.Bluemix_notm}} にリンクされていない {{site.data.keyword.BluSoftlayer}} アカウントを使用している既存のユーザーの場合、メニュー・アイコン ![メニュー・アイコン](../icons/icon_hamburger.svg) を使用して「インフラストラクチャー」ダッシュボードに、**「カタログ」**リンクを使用してインフラストラクチャー・サービスにアクセスすることができます。このメニュー・バーには、KnowledgeLayer ヘルプ、連絡オプション、通知、オープン・チケット、サポートおよびアカウントの各オプションへのリンクも含まれています。

## 地域の切り替え 
{: #regionselector}

{{site.data.keyword.Bluemix_notm}} コンソールを使用している場合、正常に稼働している最も近い地域の情報が自動的に表示されます。コンソールのグローバル・ロード・バランシング機能により、何らかの理由で最も近い地域がダウンしている場合には、コンソールは次に近い地域の情報を表示します。このように、必要な情報にアクセスするためにアクションを取る必要はなく、常にコンソールにアクセスできます。

コンソールで地域セレクターを使用して、ビューをフィルター操作します。例えば、米国ダラス地域のアプリとサービスにアクセス中に、ロンドン地域のアプリとサービスを表示したい場合、地域セレクターを使用してビューを変更できます。

1. ユーザー・アカウント設定リンクをクリックします。
2. **「地域」**メニューを展開します。
3. リストから必要な地域を選択します。

地域ごとにビューをフィルター操作することで、ビューを素早く切り替え、異なる地域に割り当てられている組織、スペース、およびユーザーと連携して作業することも可能になります。

地域についての詳細、および CLI を使用して特定の地域に接続する方法については、『[地域](/docs/overview/cf.html#ov_intro_reg)』参照してください。  

## カタログでの作業

コンソールでは、地域を選択してダッシュボードをフィルター操作し、アカウント内に作成済みのインフラストラクチャー、アプリ、およびサービスを表示できます。しかし、カタログからは、現在コンソールで選択されている地域に関係なく、使用可能なすべてのオプションを確認できます。メニュー・バーで**「カタログ」**リンクをクリックして、使用可能なインフラストラクチャー、アプリ、およびサービスを確認します。

カタログからタイルを選択すると、そのリソースが使用可能な場所を確認できます。カタログ内のすべてのリソースがすべての地域で使用可能というわけではありません。カタログのタイルをクリックした後、作成の前に、デプロイする地域と割り当て先の組織およびスペースをすぐに選択できます。デプロイメントのオプションを選択して**「作成」**をクリックすると、デプロイしたコンソール内の地域、組織、およびスペースに自動的に切り替えられます。

