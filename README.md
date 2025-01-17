![ヘッダー画像](/assets/images/Logo.png)
# 手洗い促進アプリ 御手洗PLUS
京都大学大学院情報学研究科社会情報学専攻の実習クラスで作成したシステムです。  
当該授業で**最優秀賞**を受賞しました🎉🎉🎉

御手洗PLUSは手洗いの促進を目標としており、スマホアプリ（iOS, Androidに対応）とHandwash Evaluator(Jetson Nano)と使用したシステムです。
ユーザがHandwash Evaluatorが設置されている自宅、研究室や職場へ到着すると、アプリからプッシュ通知が届きます。Handwash Evaluatorはユーザの手洗い開始を検知し、ユーザの手洗いを評価します。手洗い評価はHandwash Evaluatorに繋がれたモニターに映し出されているアニメーションと連動し可視化されます。
手洗いの終了を検知するとモニターにQRが映し出され、ユーザはアプリでQRをスキャンすることでスコアを記録します。

Handwash Evaluatorのリポジトリのリンクは[こちら](https://github.com/is0392hr/handwash_evaluator)

**紹介動画は[こちら](https://www.youtube.com/watch?v=9nU7tt7SAoc&t=2s)**

**スライドは[こちら](https://docs.google.com/presentation/d/1fVfTtds5QCr5dvoYWCT9diF7SFI0JmmAsynQwNJ5s38/edit?usp=sharing)**

**技育展用のスライドは[こちら](https://docs.google.com/presentation/d/1Y1mNiNGpw-JUF-rjivxDG-eDxOnEd9h1sDW5kVuPOHs/edit?usp=sharing)**

## 開発体制
<table>
  <tr>
    <th>開発人数</th>
    <td>
      5人<br>
      <b><a href="https://github.com/koki-asami"><img src="https://github.com/koki-asami.png" width="50px;" /></b>
      <b><a href="https://github.com/chum0n"><img src="https://github.com/chum0n.png" width="50px;" /></b>
      <b><a href="https://github.com/tahaShaheen"><img src="https://github.com/tahaShaheen.png" width="50px;" /></b>
      <b><a href="https://github.com/yudai78"><img src="https://github.com/yudai78.png" width="50px;" /></b>
      <b><a href="https://github.com/SSPod29"><img src="https://github.com/SSPod29.png" width="50px;" /></b>
    </td>
  </tr>
  <tr>
    <th>担当</th>
    <td>
      <a href="https://github.com/koki-asami">@koki-asami</a>：Planner of this project, Developer of Handwash Evaluator, Main developer of QR scanner and more<br>
      <a href="https://github.com/chum0n">@chum0n</a> : Developer of Notification App, Main developer of database-related functions<br>
      <a href="https://github.com/tahaShaheen">@tahaShaheen</a> : Developer of animation used in Handwash Evaluator, Co-developer of functions related to geolocation information acquisition<br>
      <a href="https://github.com/yudai78">@yudai78</a> : Developer of Notification App, Main developer of functions related to geolocation information acquisition<br>
      <a href="https://github.com/SSPod29">@SSPod29</a> : UI designer of Notification App<br>
    </td>
  </tr>
  <tr>
    <th>開発期間</th>
    <td>1ヶ月</td>
  </tr>
  <tr>
    <th>使用技術</th>
    <td>Flutter(Dart)</td>
  </tr>
</table>
