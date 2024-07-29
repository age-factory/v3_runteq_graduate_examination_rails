# v3_runteq_graduate_examination_rails

■サービス概要
どんなサービスなのかを３行で説明してください。
- 医薬品の供給不足が近年問題となっています。どの医薬品が限定出荷（出荷規制）なっているか、名前を検索すれば分かるページの作成。

■ このサービスへの思い・作りたい理由
このサービスの題材となるものに関してのエピソードがあれば詳しく教えてください。
このサービスを思いつくにあたって元となる思いがあれば詳しく教えてください。
- 現職では、製薬会社MR（営業職）として勤務しており、MRを含めた現場の医師・薬剤師・卸売の営業職はどの医薬品が限定出荷なのか調べることに多くの時間を割いています。そこで、該当の医薬品の名前を検索すれば、限定出荷かどうか検索できるページを作成したいです。

■ ユーザー層について
決めたユーザー層についてどうしてその層を対象にしたのかそれぞれ理由を教えてください。
- 薬剤師：医薬品を発注する際の業務負担軽減
　MR：得意先の対応の効率化
　卸売の営業職：得意先の対応の効率化と他社品への切り替えの提案

■サービスの利用イメージ
ユーザーがこのサービスをどのように利用できて、それによってどんな価値を得られるかを簡単に説明してください。
- 医薬品のワードを入力し、検索機能を用いて、規制のかかっていない医薬品を調べることができる。それによって、ユーザーの業務負担の軽減や供給不足の解消に繋げる。

■ ユーザーの獲得について
想定したユーザー層に対してそれぞれどのようにサービスを届けるのか現状考えていることがあれば教えてください。
- SNSで限定出荷医薬品を発信している薬剤師がいました。このアカウントはフォロワーが多く、一定数のMR・薬剤師・卸売の営業職が閲覧している可能性が高いと思われます。そこで、SNS（主にX）を用いて、サービスの普及を考えています。

■ サービスの差別化ポイント・推しポイント
似たようなサービスが存在する場合、そのサービスとの明確な差別化ポイントとその差別化ポイントのどこが優れているのか教えてください。
独自性の強いサービスの場合、このサービスの推しとなるポイントを教えてください。
現在、厚生労働省がエクセルファイルで一覧を作成しておりますが、スマホでは文字が小さい、PCではエクセルを使える環境でなければスプレッドシートなどに変換しなければ閲覧できない、検索機能はフィルターを自分でかけて検索する必要があるなどの手間があります。
そこで、見やすくかつ迅速に検索できるようにしたいです。また、同様のサービスがありますが、更新頻度が低いため、リアルタイムで厚労省のエクセルデータを反映させたいです。また、医薬品の数は膨大かつ名前も覚えにくいものも多いため、マルチ検索などを用いて実装したい

【厚生労働省 医薬品供給状況HP】
https://www.mhlw.go.jp/stf/seisakunitsuite/bunya/kenkou_iryou/iryou/kouhatu-iyaku/04_00003.html
【類似サービス】
https://drugshortage.jp/

■ 機能候補
現状作ろうと思っている機能、案段階の機能をしっかりと固まっていなくても構わないのでMVPリリース時に作っていたいもの、本リリースまでに作っていたいものをそれぞれ分けて教えてください。
- 検索機能
  データを表示させる機能
　マルチ検索・オートコンプリート
　手動で登録した医薬品の供給状況が正しく表示されるか
　厚生労働省が発信しているCSVファイル内の医薬品を登録する実装は後ほど実装していきたいです。

■ 機能の実装方針予定
一般的なCRUD以外の実装予定の機能についてそれぞれどのようなイメージ(使用するAPIや)で実装する予定なのか現状考えているもので良いので教えて下さい。
マルチ検索・オートコンプリート

■ 画面遷移図
https://www.figma.com/design/1vpHDBQSx6ViDcm8ZAWXYM/%E5%8D%92%E6%A5%AD%E5%88%B6%E4%BD%9C?node-id=6-15&t=FChgtyMosPRm1IqC-1
