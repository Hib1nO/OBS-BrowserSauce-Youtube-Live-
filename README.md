# OBS-BrowserSauce-Youtube-Live
## OBSでYoutubeLiveの配信映像をウィンドウキャプチャーではない方法で行う方法
YoutubeLiveの共有ではなくURLバーのURLをコピー  
OBSのソース追加でブラウザを選択  
ブラウザソースのYoutubeLiveURLを「**watch?v=**」→「**embed**」に変更（全画面表示）と最後に「**?autoplay=1**」を追加。
### 例
https://www.youtube.com/watch?v=gsc1GWBkMx4  
↓  
https://www.youtube.com/embed/gsc1GWBkMx4?autoplay=1

## 注意
配信者の設定によってはYoutube以外での再生を許可していない場合は使用できません
