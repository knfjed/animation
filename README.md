https://knfjed.github.io/animation/

# メニューを横にスライド表示させる

参考：https://techblog.raccoon.ne.jp/archives/1572506557.html

### menu をスライド時に透過させる

→ メニュー要素に対して opacity を指定します。
デフォルトは完全透過の`opacity: 0;`を指定、またチェックされたときは透過なしの`opacity: 1`;を指定し、transition プロパティに opacity を追加します。
