## 外部APIの呼び出しのミニレポート
### Q3-1. 郵便番号APIについて説明せよ。
* エンドポイントと機能
   エンドポイントは https://zipcloud.ibsnet.co.jp/api/search。郵便番号を指定すると対応する住所を返すオープンAPI。
* リクエストとレスポンスのフォーマット
   リクエストはGET形式でzipcodeパラメータを渡す。レスポンスはJSON形式で、都道府県・市区町村・町域などの住所情報。   
### Q3-2. 各自で調査したAPIについて説明せよ。
* APIの名称と参照URL
  APIの名称は、OpenWeatherMap。参照URLは https://openweathermap.org/api で、天気情報を提供する。
* エンドポイントと機能
  エンドポイントは https://api.openweathermap.org/data/2.5/weather。都市名を指定して現在の天気や気温を取得できる。
* リクエストとレスポンスのフォーマット
  GETでq（都市名）とappid（APIキー）を指定。レスポンスはJSON形式で、天気、気温、湿度などのデータ。
### Q3-3. 感想
* 今回の課題で苦労したこと
  APIの呼び出しで非同期処理を使う方法に慣れるのが難しかった。
* 演習を通して理解できたこと
  fetchとasync・awaitを使ったAPI通信の流れや、JSONデータの構造と扱い方を実践的に学び理解を深めることができた。
* Web APIの利便性や課題など
  Web APIを使うとリアルタイムな情報取得が簡単にできるが、APIキー管理や通信エラー処理の重要性も同時に感じた。
  
