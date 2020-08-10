## 目的
Fusekiのデータを可視化するテスト

## 可視化


## wip

testdata `バリィ.n3`

`curl http://localhost/ds?query=select+(count(*)+as+%3Fcount)+%7B%3Fs+%3Fp+%3Fo%7D&format=json`:

test  

```
SELECT ?s ?p ?o
WHERE {
?s ?p ?o
}
LIMIT 25
```

`http://localhost/ds` endpoint


`http://localhost/viz/index.html`