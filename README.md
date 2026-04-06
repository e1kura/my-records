# 概要
Linux（Ubuntu Server）上にnginxを構築し、Webページ公開を目指しています。

# 現在の進捗
- Ubuntu Server構築
- SSH接続設定
- nginxインストール
- デフォルトページ表示確認

# 今後の予定
- HTMLページ作成
- GitHub連携
- VPSで公開
- HTTPS化

# 学習ログ

## 2026-03-29
- Ubuntu Serverのインストール
- SSH接続設定（メインPCからリモート操作確認）
- nginxのインストール、デフォルトページ表示の確認

→ サーバー構築およびリモート操作が可能な環境を構築

## 2026-04-04
- GitHubリポジトリ作成
- README作成

→ 学習内容の記録・公開環境を構築

## 2026-04-04
- VSCodeからSSH接続し、サーバー上のファイル編集環境を構築
- ファイル保存時の権限エラーを解決
- VPSと自宅サーバーの違い、セキュリティリスクについて少し学習

→ ファイルの所有者がrootだったため書き込み不可。chownコマンドで所有者を変更し解決

## 2026-04-06
- GCPでのVPS構築とアクセス
- Nginxの導入とウェブサーバー公開
- certbotとpython3-certbot-nginxのインストールによるHTTPS（SSL/TLS）化
- OSLoginやセッション切れにより sudo が一時的に効かなくなる現象を確認

→ ユーザーとグループ管理（sudoグループ追加）で一時的な sudo 問題を回避 `sudo usermod -aG sudo`
