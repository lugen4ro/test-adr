# 通信方式にgrpc-gatewayを選定

## ステータス

Approved

## 背景

## 結論

grpc-gateway で良い

- grpc-gatewey を使用するデメリットは特にない
- 短期間での初期開発が求められるため、grpc-webを導入するコストが高い

## 論点

- server repo のスタック共有化
- Envoyプロキシの設定が不要
- 他サービスでも利用しているが特に問題なく利用できている(Cookieなど)

## 適用した結果

## 撤退条件
