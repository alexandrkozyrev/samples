{:title "About"
 :layout :page
 :page-index 0
 :klipse true
 :navbar? true}

## CLJS sample

```klipse-cljs
(map #(* % %) (range 10))
```

## JS sample 

```klipse-js
[1, 2, 3].map(function(x) { return x + 1; })
```

## SQL sample 

```klipse-sql
CREATE TABLE play (game, points, day)
```

## Python sample 

```klipse-python
print(1 + 2)
```

## Markdown sample 

```klipse-markdown
#### header 4
```

## Hiccup sample 

```klipse-hiccup
[:a {:href (to-uri "clojure.org")} "Clojure website"]
```


TBD later ....