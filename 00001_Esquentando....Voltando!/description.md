Na unidade anterior, vimos que podemos usar `repeat` para fazer algo muitas vezes. Fizemos um exemplo que se chamava `Diagonal4Azul`, que era mais ou menos asim:

``` gobstones
procedure Diagonal4Azul(){
    repeat(4){
        Colocar(Azul)
        Mover(Leste)
        Mover(Norte)
    }
}
```

Você se anima a definir o procedimento `Diagonal4AzulVoltando`? Este procedimento deveria _fazer o mesmo_ que `Diagonal4Azul`, mas precisa deixar a garra **na posição inicial**.

**Fique de olho!** Não vale escrever de novo o código que você já escreveu na unidade passada. Não precisa repetir o código! Então, pode usar `Diagonal4Azul()` sem que o defina. :wink: