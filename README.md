# kadai01
## じゃんけんに勝ってミステリーツアーに行こう！  <BR> 

**課題内容（どんな作品か）**  
-**コンセプト**
   じゃんけんに勝ったら、おみくじをひいて、ミステリーツアーに行こう！   
- 本来やりたいパン屋さんのサイトに何を搭載したいかそこにじゃんけんのゲーム性をどう入れるか？から考え、技術的、時間的な制約を踏まえてここにいたった作品。
- **構成**  
  - じゃんけんをして勝ったら画面遷移。あいこは結果が出るまでじゃんけん。負けたらリセットしてもう一度。  
  - 勝ったら「声の声援」国を選ぶおみくじ。その国の画像を「Pixabay」APIで取得。  
  - おみくじから画像APIを取得する流れの自動化が未達）  <BR>

**工夫した点・こだわった点**
  - いろいろな機能を試してみたいと思い、画像API、シャッフル、音声作成、GIFなどを取り入れた。

**質問・疑問（あれば）****
- シャッフル後の結果をフォームに飛ばして、自動で画像を選択させたかったができませんでした。


**その他（感想、シェアしたいことなんでも）**
- 挑戦はしましたが、欲張りすぎてはだめ。また広げすぎずにコードにこだわる姿勢も大切という反省あり。
でも楽しめました。
- Google画像API、InstagramのAPIを検討したが、コストや申請などで間に合わず、ハードルが低めだった「Pixabay」APIを実装。
- じゃんけんは別のプログラムを写経していたが、2次元配列によるジャッジから勝った場合のアクションを変えるやり方がわからず、ifによるプログラムに修正。
- ユーザー視点のUIについて考えるべきことはいろいろあるが（急に音が鳴るとか、わかりやすいとか、ＣＳＳ含め）、今回はやりたいことをとりあえず実装としたかたち。
