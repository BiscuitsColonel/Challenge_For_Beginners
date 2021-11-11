# 初心者向け課題
URLとかは貼りません!  
エンジニアは自分でググってなんぼです(とは言え軽く手順は記載します)。  
この課題がクリアできればエンジニア向きだと思いますので頑張ってください:thumbsup:

## 1. VirtualBoxのインストール
VirtualBoxをOracleのページからダウンロードしてインストールしてください。  
特にバージョンは指定しないです。

## 2. VMの作成とCentOSのインストール
VMを2つ作成する。

### 2-1. インストール用ISOイメージをダウンロード
CentOSのインストール用ISOイメージをダウンロードしてください。
バージョンは **CentOS7.9.2009** でお願いします。

### 2-2. VirtualBox上に新規仮想マシンを作成
以下の要件で作成する。
 - VM名：centos01
 - メモリ：1024MB
 - ディスク名：centos01
 - ディスクサイズ： 5GB
 - ハードディスクのファイルタイプ：VDI
 - 可変or固定：可変サイズ

### 2-3. CentOSのインストール
以下の要件でインストールする。
 - OSバージョン：CentOS7.9.2009
 - タイムゾーン：東京
 - キーボード：日本語
 - ソフトウェアの選択：最小限のインストール
 - インストール先：パーティションを自動動構成する
 - kdump：有効にする
 - ホスト名：ホスト名 centos01
 - ROOTパスワード：Testpass89
 - ユーザーの作成：しない

### 2-4. VirtualBox上に新規仮想マシンを作成
以下の要件で作成する。
 - VM名：centos02
 - メモリ：1024MB
 - ディスク名：centos02
 - ディスクサイズ： 5GB
 - ハードディスクのファイルタイプ：VDI
 - 可変or固定：可変サイズ

### 2-5. CentOSのインストール
以下の要件でインストールする。
 - OSバージョン：CentOS7.9.2009
 - タイムゾーン：東京
 - キーボード：日本語
 - ソフトウェアの選択：最小限のインストール
 - インストール先：パーティションを自動動構成する
 - kdump：有効にする
 - ホスト名：ホスト名 centos02
 - ROOTパスワード：Testpass89
 - ユーザーの作成：しない
