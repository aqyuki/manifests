# README

このリポジトリでは、自宅鯖にホスティングしているアプリケーションの設定ファイルなどを管理しています。

## ⚙️ Deployment

> [!CAUTION]
> Docker compose v2は非推奨となっています。Docker compose v3を利用してください。

このリポジトリで管理されているアプリケーションは[Docker](https://docs.docker.com/)上にデプロイされます。
また、[Dokploy](https://dokploy.com/)を利用して自宅鯖にデプロイを行っています。
`master`ブランチに対してPushされるとDokployによってデプロイが実行されます。

## ⬆️ Update

[Renovate](https://www.mend.io/renovate/)経由でコンテナイメージのバージョンは更新されます。
バージョン更新時にはPull RequestがRenovateによって作成されるため、そのPRをマージすることでコンテナイメージが更新されます。

## ✨️ Applications

Not anything there.
