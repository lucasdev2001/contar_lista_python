# Como achar o tamanho de uma lista em python

Você pode criar listas em python utilizando colchetes:

```
listaItems = ["python", True, [50, 30], 80]
```

## forma ineficiente

```
size = 0
for value in listaItems:
    size = size + 1

print(size)

#4
```

## forma eficiente

```
listaItemsLengt = len(listaItems)
print(listaItemsLengt)

#4
```

A funação len() também funciona para dicionários e strings, observe:

```
dicionario = {
    "nome": "Lucas",
    "profissao": "arquiteto de software",
    "idade": 21,
    "emojiFavorito": "🦁",
    "animalFavorito": "🐜"
}


frase = "Se as coisas são verdadeiras, estão sempre onde devem estar. -C. S. Lewis"

print(len(dicionario))

#5

print(len(frase))

#73
```
