---

copyright:
  years: 2017, 2018
lastupdated: "2018-05-22"

---
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}

# メディア・データ転送サービスとは
 
データ転送サービスは、お客様から {{site.data.keyword.BluSoftlayer_full}} データ・センターに送付された USB 2.0 または 3.0 対応デバイス、CD、および DVD を、お客様のネットワークに直接接続するサービスです。デバイスは専用ラックに格納され、iSCSI ターゲットとしてマウントされます。アドバンスト・フォーマットのドライブもサポートされるようになりました。

## ハードウェア要件
1.    デバイスは、208v/220v 対応の電源を備えていなければなりません
2.    デバイスは、標準の 120v ソケット (NEMA 5-15P) に合う電源プラグを備えていなければなりません
3.    デバイスは USB 2.0 対応でなければなりません (3.0 も現在サポートされています)
4.    デバイスには、USB A タイプのオス・コネクター (ほとんどのコンピューターに適合する標準的なプラグ) を備えた USB ケーブルが付属していなければなりません
5.    CD / DVD
      1.    CD ブック、CD ケースなどの容器に入っていなければなりません。可能な限りすべての CD を 1 つの容器 (CD ブックなど) に収めてください。また、ディスクごとに固有のラベルを付ける必要があります。
      2.    ディスクは、チケットによるお客様の要請でローテーションされます

## 費用
1.    初回のサービス要求: $0
2.    データ転送の最初の 2 週間: $0
      **注**: 延長すると、1 週あたり $25 の料金が発生します。
3.    {{site.data.keyword.IBM}} データ・センターとの間の発送料 (各種税の支払いを含む)。

**注**: 以下については、お客様の責任で行ってください。  
- デバイスを {{site.data.keyword.IBM}} データ・センターに発送したりお客様に返却したりする (該当する場合) のに、輸入承認書や輸出承認書が不要なことを確認します。 
- コンテンツ内に含まれているデータの所有者であるお客様やお客様のユーザーに、米国での輸出特権の取り消しや否認を命じる米国政府命令が出ていないことを確認します。お客様またはお客様のユーザーがこのような命令を受けた場合はただちに {{site.data.keyword.IBM}} にお知らせください。  
- デバイスに関するすべてのライセンスの取得、配送、通関手続き。これには、関税、税金、{{site.data.keyword.IBM}} データ・センターへの配送料、データ・センターからの配送料 (該当する場合) の支払いが含まれます。   
- デバイスの送付と返却、{{site.data.keyword.IBM}} データ・センターへのコンテンツの転送に関連する、該当するすべての法律に従います。これには、プライバシーや輸出入に関する法律が含まれます。
- ハードウェアに転送するすべてのユーザー・データについて、ユーザーから適切な同意を得て、必要な許可をすべて取得します。

## 要求の作成
これを行うには、**「ストレージ」**>**「データ・マイグレーション」**>**「データ転送」**の順に進み、右上隅にある**「データ転送要求の注文」**をクリックします。

![データ転送要求の作成](/images/DTS.png)

デバイスに関する以下の情報をフォームに入力します。
1. シリアル番号
2. タイプ
3. デバイスの簡略説明
4. デバイスの送付先のデータ・センター
5. 配送の追跡に使用する追跡番号
6. 利用する配送業者サービス
7. 終了時にデバイスを返送してもらいたい返却先住所

この要求によってサポート・チケットが作成されるので、弊社技術員が、デバイスが配送中であることを知り、配送状況を追跡できるようになります。受け取ったデバイスは、専用ラックに接続されます。デバイスが接続されると、チケットが更新されて、iSCSI ターゲットへのログオン資格情報へのリンクが提供されます。

## 返却の要求
返却先住所を入力し、送料支払い済みの返送用ラベルを同梱した場合は、2 週間の転送期間中にいつでもデバイスの返送を要求できます。これは、[{{site.data.keyword.slportal}}](https://control.softlayer.com/){:new_window}を使用して行うことができます。**「ストレージ」**>**「データ・マイグレーション」**>**「データ転送」**を選択し、該当デバイスの**「アクション」**メニューから**「返却の要求」**を選択します。これにより、デバイスを切り離して返却してほしいということが技術員に知らされます。

## 延長の要求
2 週間の無料期間の後も、デバイスを使用し続ける必要がある場合は、延長を要求してください。これにより、デバイスの接続期間を延長したいということが技術員に知らされます。この要求は、デバイスの返却を要求する場合と同じ方法で行えます。**「ストレージ」**>**「データ・マイグレーション」**>**「データ転送」**を選択し、該当デバイスの**「アクション」**メニューで**「延長の要求」**を選択します。延長すると、1 週あたり $25 の料金が発生します。データ・センターの空き容量によっては、延長の要求をお断りする場合があります。要求が受諾されると、チケットがそれに応じて更新されます。

## 切断
2 週間後、デバイスは自動的にデータ・センターから切り離されます。返却を要求していた場合は、最初の要求に指定されていた配送業者を使用して返却先住所にデバイスが返却されます。チケットが更新されて、デバイスが切り離されたことが示されます。デバイスの返却を要求していなかった場合、デバイスはその場で破棄されます。
