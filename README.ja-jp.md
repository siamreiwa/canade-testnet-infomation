# CANADE network infomation [TestNET]

## 概要
CANADEネットワークは、Symbolベースのブロックチェーンです。
農作物や加工製品のトレーサビリティと証明をオンチェーンで実現し、産地偽装や模造品、模倣品から消費者を守り、安全と安心を確保するために活用されます。


## 情報

### 基軸通貨
- canade.cbdp

### 関連サービス

- [Explorer](https://explorer.test.siamreiwa.com/)
- [Faucet](https://faucet.test.siamreiwa.com/)
- [Wallet](https://wallet.test.siamreiwa.com/)
- [Node list](https://explorer.test.siamreiwa.com/nodes)

※テストネットに限り、Symbolロゴを利用する許諾をコアデベロッパーから得ています。

### ノードを建てる

```bash
# ノードの設定ファイルをサーバにダウンロードします
wget https://raw.githubusercontent.com/siamreiwa/canade-cbdp-community-test/main/preset/custom-preset.tar.gz

# 圧縮ファイルを展開します
tar -xvf custom-preset.tar.gz

# 必要に応じてSymbolノードと同じようにmy-preset.ymlファイルを編集します

# 以下のコマンドでノードを起動します。
symbol-bootstrap start -p custom-network-preset.yml -a dual -c custom-preset.yml -d
```