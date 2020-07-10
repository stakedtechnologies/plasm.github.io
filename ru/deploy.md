# デプロイ

[Plasm Network](https://www.plasmnet.io/)のメインネットにデプロイする前に、自身のローカルチェーンとDusty Networkにデプロイすることがおすすめされています。これは安全な開発を行なうためであり、ローカル環境とDusty Network上でテストを行なうことでデプロイするスマートコントラクトの動作を確認することができます。

### ローカルチェーンへのデプロイ

ローカルノードへのデプロイをするためには、ローカルでノードを動かす必要があります。「ローカルでノードを動かす」のセクションに従ってノードを動かしてください。

{% page-ref page="run-node.md" %}

次に、[Plasm Network](https://www.plasmnet.io/)の[Plasm Network Portal](https://apps.plasmnet.io/)を開きましょう。

![](../.gitbook/assets/screen-shot-2020-07-09-at-12.25.16.png)

上部左のロゴをクリックすることで以下の画面に推移します。

![](../.gitbook/assets/screen-shot-2020-07-09-at-12.27.11.png)

今回はローカルチェーンにデプロイするため、"Local Node"を選択します。（※ Dusty Network、Plasm Networkにデプロイしたい場合はそれぞれのロゴをクリックします。）

![](../.gitbook/assets/upload.png)

続いて、画面左端の"Contracts"タブをクリックし "Upload WASM"を選択します。WASMとはWebAssemblyの略語であり、ink!などの言語で書かれたスマートコントラクトがコンパイルされた状態を指します。ここではMetadataもしくはWASMコードをアップロードすることができます。

（※ サンプルコードが必要な方は [ink! のサンプルコード](https://github.com/paritytech/ink/tree/v2.1.0/examples)をご利用ください。）

![](../.gitbook/assets/deploy.png)

ファイルをアップロードするためには、少額のトランザクションコストが必要となります。

![](../.gitbook/assets/uploaded.png)

コントラクトがアップデートできたことを確認したら実際にデプロイを行いインスタンスを作成しましょう。


