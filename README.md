概要
-----
draw.ioをAlibaba Cloudに対応させたものです。  

ライセンス
-----
このツールは[draw.io](https://github.com/jgraph/drawio)を元に作成されています。  
ライセンスは[Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0)に準拠します。

使い方
-----
- [Github Page](https://satouruzg.github.io/src/main/webapp/index.html)にアクセス
- （初回アクセス時のみ）保存場所を聞かれるので、「Device」を選択
- 「Create New Diagram」を選択
- 「Cloud」カテゴリより、Alibaba Cloudのテンプレートを選択  
例）aliyun_basic_web.xml
- 「Create」ボタンを押下
- 左側のメニューにAlibaba Cloudのアイコンが表示されるので、Let's draw!!

注意点
-----
カスタムライブラリを読み込む方法を取っているので、「Open Existing Diagram」からではAlibaba Cloudのアイコンは出ません。  
また、「＋ More Shapes...」から読み込むことも出来ません。  
テンプレートを使用ない場合は、空のテンプレート（aliyun_blank_template.xml）を選択してください。

既知のバグ
-----
Shape（アイコン群）の順番が逆になる件
  - 初回のみ、正しい順番（General→Compute→...Management）になるが、2回目以降は逆順になる
  - ソースを逆順（Management→Bigdata→...General）に変更。2回目以降に正しい順番で表示されるように修正
  - 原因は不明。初回は我慢

参考
-----
- 元のソース（draw.io）:https://github.com/jgraph/drawio
- icon素材：https://www.iconfont.cn/plus/user/detail?&uid=41718
- 参考サイト：https://qiita.com/ohiro18/items/02c5da6d6590dfe3ed0d
