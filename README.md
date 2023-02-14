# NIFCLOUD Mobile Backend Push Notification Plugin for Unity

---
## 動作環境

- Unity 2021.x
- Android 8.x〜12.x, API level 26.0〜31.0
- iOS 13.x〜16.x
(※2023年XX月時点)

※ 併せて、[Monaca 対応環境](https://ja.docs.monaca.io/environment)をご確認ください。（NIFCLOUDMB (ncmb-push-monaca-plugin)の保証動作環境ではありません。）

### テクニカルサポート窓口対応バージョン

テクニカルサポート窓口では、1年半以内にリリースされたSDKに対してのみサポート対応させていただきます。
定期的なバージョンのアップデートにご協力ください。  
※なお、mobile backend にて大規模な改修が行われた際は、1年半以内のSDKであっても対応出来ない場合がございます。  
その際は[informationブログ](https://mbaas.nifcloud.com/info/)にてお知らせいたします。予めご了承ください。  

- vx.x.x ～ (※2022年12月時点)

[開発ガイドライン](https://mbaas.nifcloud.com/doc/current/common/dev_guide.html#SDK%E3%81%AB%E3%81%A4%E3%81%84%E3%81%A6)をご覧ください。


## 初期設定

* 詳細については[ドキュメント](https://mbaas.nifcloud.com/doc/current/push/basic_usage_javascript.html#%E3%83%97%E3%83%83%E3%82%B7%E3%83%A5%E9%80%9A%E7%9F%A5%E3%81%AE%E5%8F%97%E4%BF%A1(Monaca))を併せてご確認ください.
* Android端末での利用には、ご自身のFirebase設定ファイルgoogle-services.jsonをダウンロードして、Cordovaプロジェクトのルートディレクトリに置く必要があります。設定ファイルのダウンロードについては[こちらのFirebaseサポートページ](https://support.google.com/firebase/answer/7015592)にて詳細をご覧ください。

```
- Your_monaca_project/
    platforms/
    plugins/
    www/
    config.xml
    google-services.json       <--
    ...
```

## ライセンス

LICENSEファイルをご覧ください。
