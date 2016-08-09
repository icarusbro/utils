# MongoDB Commands

autor: ícaro Costa

## 1\. START MONGO SERVICE

```
sudo systemctl start mongodb
```

## 2\. Distinct por `cuisine` na restaurantes

````
```

## 3\. Distinct por `types` na pokemons
````

```

## 4\. As primeiras 3 páginas com .limit() e com .skip() de pokemos (5 em 5)
```

```

## 5\. Group ou Aggregate contando a quantidade de pokemons de cada tipo
```

```

## 6\. Realizar 3 counts na pokemons

-> .count -- todos

-> .count -- só tipo fogo

-> .count -- só de quantos tem a defesa maior que 70
```

db.pokemons.count() 620

db.pokemons.count({ types: 'fire' }) 53

db.pokemons.count({ defense: {$gt: 70} }) 263 ```
