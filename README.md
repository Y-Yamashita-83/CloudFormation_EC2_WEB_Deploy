# CloudFormation_EC2_WEB_Deploy
CloudFormationで以下を作成します。<br>
- VPC
- ルートテーブル
- EC2インスタンス×2
- セキュリティグループ
- インターネットゲートウェイ
<br><br>

cfn-initで以下を実行します。<br>
- EC2にhttpdをインストール
- /var/www/html/index.htmlファイルを作成
- SSHのListenポートを22から51512に変更
