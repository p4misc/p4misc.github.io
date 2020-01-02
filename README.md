# 本サイトについて
本サイトではHelix Core(旧称Perforce)に関する参考情報の入手先や各コンテンツの概要を紹介していきます。
整理整頓をし終えるまでは乱雑にまとめていく形になりますが、ご了承ください。

## p4miscのリソース
- [GitHub](https://github.com/p4misc)

  | リポジトリ名/コンテンツ名&nbsp;&nbsp; | 概要 |
  | --- | --- |
  |[p4misc/main](https://github.com/p4misc/main)|未整理ですがHelix Coreサーバを構築するためのDockerfileなどを配置しています。|
  |[p4misc/p4prometheus](https://github.com/p4misc/main)|Helix Coreのモニタリング環境を構築するためのDockerfileなどを配置しています。| 
  |[p4misc/memo](https://github.com/p4misc/memo)<br />[UnrealGameSyncビルドメモ](https://github.com/p4misc/memo/blob/master/UnrealGameSyncMemo.md)|UnrealGameSyncのビルド方法に関するメモです。|
  |[p4misc/memo](https://github.com/p4misc/memo)<br />[MetadataServer構築メモ](https://github.com/p4misc/memo/blob/master/MetadataServerMemo.md)|UnrealGameSync MetadataServerの構築方法に関するメモです。|

<br />
- [DockerHub](https://hub.docker.com/u/p4misc)

  | リポジトリ名:タグ名&nbsp;&nbsp; | 概要 |
  | --- | --- |
  |[p4misc/psla:latest](https://hub.docker.com/repository/docker/p4misc/psla)|Perforce Server Log Analyzer (PSLA)のDockerイメージ(和訳版)|
  |[p4misc/psla:english](https://hub.docker.com/repository/docker/p4misc/psla)|Perforce Server Log Analyzer (PSLA)のDockerイメージ(英語版)|
  |[p4misc/p4prometheus:latest](https://hub.docker.com/repository/docker/p4misc/p4prometheus)|Helix Coreのモニタリング環境(p4prometheus付き)のDockerイメージ|

<br />
- [Twitter](https://twitter.com/p4misc)
- [Twilog](https://twilog.org/p4misc)


## Perforce Softwareのリソース
- What's New

  | コンテンツ名　　　　　　　　　　　　| 概要 |
  | --- | --- |
  |[(英語)What's New in Helix Core](https://www.perforce.com/products/helix-core/whats-new-helix-core)|Helix Coreの新機能ハイライト|

<br />
- [(英語)P4VとP4のチートシート](https://www.perforce.com/pdf/perforce-helix-cheatsheet.pdf)
- [(和訳)P4VとP4のチートシート](https://kb.toyo.co.jp/wiki/pages/viewpage.action?pageId=17472962)
- [(英語)Perforce Software社のベストプラクティスに基づいてサーバのセットアップを行うパッケージ](https://swarm.workshop.perforce.com/projects/perforce-software-sdp)

- [ナレッジベース](https://community.perforce.com)

  ナレッジベースにはHelix Coreに関する各種ナレッジが登録されています。Articles by ProductでHelix Coreを選択すると、Helix Coreに関する記事に絞り込むことができます。

  | コンテンツ名　　　　　　　　　　　　| 概要 |
  | --- | --- |
  |[(英語)Upgrading a Helix Server](https://community.perforce.com/s/article/2467)|Helix Coreサーバのアップグレード方法を紹介した記事です。|
  |[(英語)Using the Spec Depot](https://community.perforce.com/s/article/2445)|スペックディポの使用方法を紹介した記事です。|
  |[(英語)Autotune - Improved performance over long latency TCP connections](https://community.perforce.com/s/article/15368)|高レイテンシのNW環境向けのチューニング方法を紹介した記事です。|
  |[(英語)p4 reconcile -m - Speeding up the Client Reconcile Command](https://community.perforce.com/s/article/15133)|p4 reconcileを高速化する方法を紹介した記事です。|
  |[(英語)External Archive Transfer using pull-archive and edge-content triggers](https://community.perforce.com/s/article/15337)|レプリカ構成/コミット・エッジ構成でサードパーティ製のファイル転送処理を使用する方法を紹介した記事です。|
  |[(英語)The Perforce Sample Depot](https://community.perforce.com/s/article/2439)|サンプルディポの入手と配置について説明している記事|
  |[(英語)Formatting p4 command output using the -F global option with examples](https://community.perforce.com/s/article/15148)|P4コマンドのフォーマットオプションに関する記事|
  |[(英語)Inconsistent Icon Overlays with P4EXP](https://community.perforce.com/s/article/2771)|オーバーレイアイコンの有効化に関する記事|

<br />
- [ブログ](https://perforce.com/blog)
  - Helix Coreに関するブログ記事が登録されています。  
    TOPICSでVersion Controlを選択します。
- [フォーラム](https://twitter.com/perforce)
  - Helix Coreに関するユーザフォーラムです。
- [Workshop](https://swarm.workshop.perforce.com/)
  - Helix Coreのコミュニティメンバが作成したコンテンツが登録されています。
- [Youtube](https://m.youtube.com/user/perforcesoftware)

  | コンテンツ名　　　　　　　　　　　　| 概要 |
  | --- | --- |
  |[(英語)What Is Version Control?](https://www.youtube.com/watch?v=X2W1dUM3bu8)|Helix Coreにおけるバージョン管理のコンセプト動画|
  |[(英語)Setting up a Workspace in P4V](https://www.youtube.com/watch?v=-nlpBSLBjDs)|Helix Coreのワークスペースの概要とP4Vでワークスペースを作成・編集する方法(Classic Depot用)|
  |[(英語)Setting up a Workspace in P4V](https://www.youtube.com/watch?v=-nlpBSLBjDs)|Helix Coreのワークスペースの概要とP4Vでワークスペースを作成・編集する方法(Classic Depot用)|
  |[(英語)Helix Core Basic Workflow](https://www.youtube.com/watch?v=m4E3xp8ypLw)|Perforceを利用する際の基本ワークフロー(概念説明)<br />・ファイル同期<br />・チェックアウト<br />・サブミット(チェックイン)<br />・チェンジリストとその履歴<br />・ファイルの変更履歴<br />・他ユーザのチェックアウト中ファイルの特定<br />・複数ユーザの同時編集の防止<br />・複数ユーザの同時編集結果のマージ)|
  |[(英語)Helix MFA Overview](https://www.youtube.com/watch?v=XPH6qXf9Unss)|Helix Coreに多要素認証を設定する方法|

<br />
- 動画コンテンツ

  | コンテンツ名　　　　　　　　　　　　| 概要 |
  | --- | --- |
  |[(英語)What Is Perforce Streams?](https://www.perforce.com/solutions/version-control/branching-brains)|Stream機能のクイックイントロダクション|
  |[(英語)Using the Image Diff Tool](https://www.perforce.com/video-tutorials/vcs/using-image-diff-tool)|画像の差分表示デモ|
  |[(英語)Switching Streams Workspaces](https://www.perforce.com/video-tutorials/switching-streams-workspaces)|1つのワークスペースを複数のストリームで共有する方法の解説動画|
  |[(英語)Helix Plugin for File Explorer](https://www.perforce.com/video-tutorials/vcs/helix-plugin-file-explorer)|P4EXP(Perforce Helix CoreのWindowsエクスプローラ連携)の解説動画|
  |[(英語)Using the Revision Graph](https://www.perforce.com/video-tutorials/using-revision-graph)|リビジョングラフの簡易解説動画|
  |[(英語)Using Time-lapse View](https://www.perforce.com/video-tutorials/using-time-lapse-view)|Timelapse Viewの解説動画||[(英語)Setting Up Helix Core Proxy Servers](https://www.perforce.com/video-tutorials/vcs/setting-helix-core-proxy-servers)|Perforce Proxyの解説とセットアップの実演動画|
  |[(英語)Perforce in the Cloud: Go Global With Helix Core on AWS](https://www.perforce.com/webinars/vcs/perforce-cloud-go-global-helix-core-aws)|AWS上でPerforceを使用する際のトポロジーの紹介Webinar|
  |[(英語)Best Practices for Game Development Using Streams](https://www.perforce.com/webinars/vcs/best-practices-game-development-using-streams)|英国Sumo Digitalにおけるストリーム運用のWebinar|

<br />
- [SlideShare](https://www.slideshare.net/perforce)
  - [(英語)Perforce Helix Core 2017.xの新機能説明スライド](https://www.slideshare.net/perforce/whats-new-in-helix-vcs-fall-releases-2017)

- [Twitter](https://twitter.com/perforce)
- [Facebook](https://twitter.com/perforce)
- [インストーラ(英語版)のダウンロード](https://www.perforce.com/downloads)
  - Helix Coreのインストーラ(英語版)を入手することができます。
  - P4EXPに関しては日本語リソースを含むインストーラを入手することができます。
- [FTPサイト](http://ftp.perforce.com/perforce/)
  - Helix Coreの旧バージョンから最新バージョンまでのバイナリやドキュメントを入手することができます。


## 東陽テクニカのリソース
- [ナレッジベース](https://kb.toyo.co.jp/wiki/)
  - Helix Coreに関する各種ナレッジが登録されています。  
- [インストーラ(日本語リソース付き)のダウンロード](https://www.toyo.co.jp/ss/download/detail/hc_products.html)
  - Helix Coreのインストーラ(日本語リソース付き)を入手することができます。
- [日本語マニュアル](https://www.toyo.co.jp/ss/download/detail/hc_manuals.html)
  - Helix Coreの日本語マニュアルを閲覧することができます。
- [Perforce Helixを用いた分散バージョン管理環境（DVCS）の構築手順](http://www.toyo.co.jp/files/user/img/product/ss/files/perforce/dvcs/dvcs_startguide.pdf)

## UE4関連
 - [情報共有: ソースの変更がどのChangelistで行われたのかをPerforceから確認する方法](https://answers.unrealengine.com/questions/841384/view.html)
