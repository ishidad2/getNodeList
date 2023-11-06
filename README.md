# 使い方

## モジュールインストール

```
$ npm install
```

## 実行

```
$ node inde.js
```

実行するとjp_nodes.jsというファイルが生成されます。

# 設定値

## メインネット・テストネットの切り替え

```
// メインネット設定
const _peer_url = "https://symbol.services/nodes?filter=suggested&ssl=true&limit=2000";
const NETWORK_IDENTIFIER = 104;

//テストネット設定
// const _peer_url = "https://testnet.symbol.services/nodes?filter=suggested&ssl=true&limit=2000";
// const NETWORK_IDENTIFIER = 152;
```

# RESTバージョン指定

```
const REST_VERSION = "2.4.3";
```

# ノードのリージョン指定

```
const COUNTRY = "Japan";
```