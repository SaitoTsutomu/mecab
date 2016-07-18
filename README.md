Mecab & NEologd
========
See http://qiita.com/nownabe/items/4171776aec1f05de9f28

```
echo "10日放送の「中居正広のミになる図書館」（テレビ朝日系）で、SMAPの中居正広が、篠原信一の過去の勘違いを明かす一幕があった。" | \
  docker run -i -a STDIN -a STDOUT tsutomu7/mecab
```
