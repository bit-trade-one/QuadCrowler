# QuadCrawler よくある質問

#### Q.I2C通信方式をとっているセンサーを取り付けたいのですが、可能でしょうか?

A.可能です。  
基板上J2のGROVEコネクタにI2Cバスが引き出されております。こちらをご利用ください。  
つくるっちはI2C非対応です、Arduinoでプログラミングして下さい。  
　  

#### Q.つくるっちのZiPファイルの展開に時間がかかった  
#### Q.つくるっちが実行できない  
#### Q.基板へのアップロード完了しない  

A. TuKuRutch.xx.zipを展開するのに通常のSSDやHDDを使用したパソコンの場合で5~10分、eMMCを使用した場合で最大１時間くらいかかります。  
しかも残り時間として「展開にあと30秒かかります」など実際よりも極端に短い時間が表示されます。  
この展開中にフォルダを移動したりつくるっちを起動すると上記のような現象が発生します。zip展開が完了するまでお待ち下さい。

A. (実行できないとき) [ダウンロードと実行](http://sohta02.web.fc2.com/familyday_app.html#download_esp32) のセキュリティ手順を確認して下さい。  
[つくるっち.exe] を右クリック - [プロパティ] - [セキュリティ - 許可する]  
また、関連ファイルの保存先の指定を間違えている場合に起動しないことがあります。

#### Q. COMポートを認識しない時がある

A.様々な理由によりCOMポートがPC上で認識されなくなることがあります。
USBの指し直しや再起動などで使用できる場合がほとんどです。

#### Q.PCモードにおいて、ダブルクリックして黄色く光らせも動かない  
#### Q.何度もプログラムを書き込み→動作を行っているうちに正常に動かなくなる  

A.つくるっちはAdobe AIR (Adove Flashのアプリ版) で動いており、不安定になる場合があります。[ロボット] - [アプリをリセットする] を試してみて下さい。

#### Q. 基板へのアップロードが完了しない

A.最新のアプリにて安定性が向上致しました。お試しください。

#### Q. リモコンの反応が悪い・機能しない

A.リモコンのボタンを押し続けてください。
機能しない場合は新品であれば電池の絶縁シートの除去、または電池の残量をお確かめください。
アプリ再起動でも動作することがあります。

#### Q. ロボットが滑って動作しない・うまく歩かない

A.最新ファームウェアにて歩行動作の改善が行われています。
また、ハードウェアの面では足の組付けに遊びがある場合地面に伝わる力が弱くなります。
アクリルの接合部などに紙を挟むなど、遊び部分を少なくすることで安定した動作が期待できます。
