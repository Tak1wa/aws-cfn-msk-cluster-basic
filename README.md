# aws-cfn-msk-cluster-basic

- [AWS::MSK::Cluster \- AWS CloudFormation](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-msk-cluster.html)
- [AWS::MSK::Configuration \- AWS CloudFormation](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-msk-configuration.html)
  - このMSK構成を使用できるApacheKafkaのバージョンのリスト。この構成は、クラスターに指定されたApacheKafkaバージョンがこのリストに表示されている場合にのみMSKクラスターに使用できます
  - server.propertiesファイルの内容。APIを使用するときは、ファイルのコンテンツがbase64でエンコードされていることを確認する必要があります。コンソール、SDK、またはCLIを使用する場合はプレーンテキストにすることができます。
- [AWS::MSK::BatchScramSecret \- AWS CloudFormation](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-msk-batchscramsecret.html)
  - ユーザー名とパスワードを使用してクラスターで認証するために使用できる、Amazon SecretsManagerに保存されているシークレットを表します。