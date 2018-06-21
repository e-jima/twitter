# twitter

### UserStream が廃止されるので、その代替

* POST statuses/filter を代替として使う
* https://developer.twitter.com/en/docs/tweets/filter-realtime/api-reference/post-statuses-filter


### 欠点
* 鍵垢のツイートが取得できない
* ツイートを取得する対象を 500人までしか選べない
* 対象のユーザのツイートが RT されたやつも取得される
* 対象のユーザと自分がフォローしてないユーザの会話も取得される


とりあえずタイムラインを取得し続ける関数とか実装。
