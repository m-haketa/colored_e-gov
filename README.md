# colored_e-gov

e-govの税法条文に色をつけます


# インストール

[Tampermonkey](http://tampermonkey.net/)を入れたブラウザで、

[colored_e-gov.js](https://m-haketa.github.io/colored_e-gov/colored_e-gov.js)

をクリックしてインストール。


# 注意事項

動作に、かなり時間がかかります。

私のほうでは、下記条文を試しています。

- [消費税法](http://elaws.e-gov.go.jp/search/elawsSearch/elaws_search/lsg0500/detail?lawId=363AC0000000108)
- [法人税法](http://elaws.e-gov.go.jp/search/elawsSearch/elaws_search/lsg0500/detail?lawId=340AC0000000034)
- [法人税法施行令](http://elaws.e-gov.go.jp/search/elawsSearch/elaws_search/lsg0500/detail?lawId=340CO0000000097&openerCode=1)

消費税法であれば、ほとんどタイムラグなく開くことができますが、法人税法施行令を開くと、処理が終わるまで私の手元（core i5-6600）で１分弱かかりました。

これよりも、ボリュームのある条文（地方税法や、租税特別措置法など）を開くと、さらに時間がかかることが予想されます。

今回のプログラムを試すときには、できるだけボリュームの小さい条文集でお試しください。
