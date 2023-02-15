# リンク  
Github
https://suzuki-ryusuke.github.io/  
AWS
http://54.178.240.153/ 
# 概要
日程調整に使用するアプリです。  
名前、メールアドレス、日付を記載し「次へ」のボタンを押すことで、完了画面へと遷移します。  
記載したメールアドレス宛に確認メールが届く仕様になっています。   
<br>
# 制作目的
社内における業務効率改善を目的にテーマを考えました。  
転職活動の経験から、面接の日程調整をよりスムーズに行えるアプリがあれば、人事と求職者のコミュニケーションコストを軽減できると思い、本アプリの開発に着手しました。  
<br>
# 今後の改善点や実装させたい機能
・他者が選択済みの日付をプラックアウトさせる  
⇒DBとの紐づけが必要  
・トップ画面と完了画面の間に確認画面をはさむ  
⇒入力情報を複数ページに反映させられるようにしたい（Javascriptを用いればできる？）  
・人事側のホスト画面を作る  
⇒カレンダーのようなページで、日付と予約者の情報を一覧で見られるページがあれば利便性向上につながる  
・他のサーバーへのデプロイ  
⇒GithubだとPHPが反映されない？AWS、Nginxの使い方を現在学習中  
2/15 AWSでのデプロイに成功(一部のPHPが動かないため原因究明中)⇒nginxとPHPの紐づけがなされていなかった
2/16 PHPの読み込みは成功（メール送信が実行されないため原因究明中）
