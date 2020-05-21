# Identifica palavras mais frequentes

Um arquivo contém um texto, e desejam-se identificar as palavras que mais aparecem nesse texto. O objetivo é mostrar as palavras com frequência maior que uma dada quantidade, ordenadas de forma decrescente pelas quantidades de ocorrências. Apenas palavras com 3 ou mais caracteres devem ser apresentadas. As palavras ocom mesma frequência devem ser apresentadas em ordem alfabética.

Por exemplo, se o arquivo contiver este conteúdo:
 
_"E assim todos viviam em concórdia e sem se lastimarem, pois um roubava o outro, e este, um terceiro, e assim por diante, até que se chegava ao último que roubava o primeiro. O comércio naquele país só era praticado como trapaça, tanto por quem vendia como por quem comprava. O governo era uma associação de delinquentes vivendo à custa dos súbditos, e os súbditos por sua vez só se preocupavam em fraudar o governo. Assim a vida prosseguia sem tropeços, e não havia nem ricos nem pobres."_

... seu programa poderia apresentar o seguinte, se fosse mostrar as palavras que aparecem 2 ou mais vezes:

```
por 4
assim 2
como 2
era 2
nem 2
que 2
quem 2
roubava 2
sem 2
```

O nome do arquivo de texto é informado como primeiro argumento de linha de comando, e a quantidade mínima de ocorrências desejada é passada no segundo argumento.

**Dicas**:
* A contagem das palavras pode ser feita facilmente com uma tabela hash
* Para ordenar uma lista de uma forma específica, pode-se definir o operador< para o tipo dos dados contidos na lista. Mas também é possível definir uma função de comparação, e passá-la como parâmetro ao chamar a operação [sort](http://www.cplusplus.com/reference/list/list/sort/). Veja uma descrição na [wiki sobre listas](https://wiki.sj.ifsc.edu.br/index.php/PRG29003:_Introdu%C3%A7%C3%A3o_a_Listas#Ordenamento_de_uma_lista_com_valores_de_um_tipo_definido_pelo_programador).