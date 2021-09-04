# CloudFormation_EC2_WEB_Deploy
CloudFormationで以下を作成します。
　・VPC
　・ルートテーブル
　・EC2インスタンス×2
　・セキュリティグループ
  ・インターネットゲートウェイ

cfn-initで以下を実行します。
　・EC2にhttpdをインストールします。
　・/var/www/html/index.htmlファイルを作成します。
　・SSHのListenポートを22から51512に変更します。
