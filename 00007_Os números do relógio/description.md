_Você já sabe Kung Fu!_

Agora, precisa mostrar que você pode _desenhar um relógio_. O que faremos agora é somente colocar os números que aparecem em um típico relógio de agulhas:

* O 12 em cima,
* o 3 à direita,
* o 9 à esquerda, e
* o 6 embaixo.

> Fazer um procedimento `DesenharRelogio(raio)`, que coloque os números do relógio como se indica acima, **em volta da divisão atual**. O tamanho do relógio se indica com o `raio` que você recebe por parâmetro: quanto maior é o raio, mais longe os números estarão do centro.

Dado o seguiente `program`:

``` gobstones
program {
  DesenharRelogio(2)
}
```

O relógio resultante é assim:

<gs-board>
  GBB/1.0
    size 5 5
    cell 0 2 Rojo 9 
    cell 2 0 Rojo 6 
    cell 4 2 Rojo 3 
    cell 2 4 Rojo 12 
    head 2 2
</gs-board>