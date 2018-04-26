# shellscriptx.github.io

![shellscriptx](shellx.png)


## DICAS

#### ÍNDICE

1. [Capturando somente os números pares contidos em um texto.](https://shellscriptx.github.io/#capturando-somente-os-n%C3%BAmeros-pares-contidos-em-um-texto)

2. [Capturando somente os números impares contidos em um texto.](https://shellscriptx.github.io/#capturando-somente-os-n%C3%BAmeros-%C3%ADmpares-contidos-em-um-texto)

**

#### 1. Capturando somente os números pares contidos em um texto.
```bash
grep -Eo '[0-9]+[02468]'
```

#### 2. Capturando somente os números ímpares contidos em um texto.
```bash
grep -Eo '[0-9]+[13579]'
```
