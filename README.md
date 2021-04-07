# VIM - Lista de Comandos

## Movimentação

`h` ou `←`

Move para a esquerda.

`j` ou `↓`

Move para baixo.

`k` ou `↑`

Move para cima.

`l` ou `→`

Move para a direita.

`w`

Avança para o início da próxima palavra.

`W`

Avança para o início da próxima palavra (incluindo pontuação).

`b`

Volta para o início da palavra anterior.

`B`

Volta para o início da palavra anterior (incluindo pontuação).

`e`

Avança para o fim da próxima palavra.

`E`

Avança para o fim da próxima palavra (incluindo pontuação).

`H`

Move para o topo da tela.

`M`

Move para o meio da tela.

`L`

Move para a base da tela.

`0`

Move para o início da linha.

`^` ou `_`

Move para o primeiro símbolo não vazio da linha.

`$`

Move para o fim da linha.

`%`

Alterna entre a abertura do símbolo e seu fechamento.

Exemplo: entre "_(_" e "_)_". Suportados: "()", "{}", "[]".

`{`

Volta um parágrafo/bloco.

`}`

Avança um parágrafo/bloco.

`gg`

Move para o início do documento.

`G`

Move para o fim do documento.

`:X` ou `Xgg` ou `XG`

Move para a linha X.

`zz`

Centraliza a tela na linha atual.

## Inserção

`i`

Insere antes do cursor.

`I`

Insere no início da linha.

`a`

Insere depois do cursor.

`A`

Insere no fim da linha.

`o`

Insere uma nova linha abaixo.

`O`

Insere uma nova linha acima.

`<esc>`

Sai do modo de edição.

## Edição

`r`

Substitui um único símbolo.

`cc`

Deleta o conteúdo da linha e entra no modo de inserção.

`C`

Deleta o conteúdo da linha a partir do cursor e entra no modo inserção.

`cw`

Modifica o conteúdo de uma palavra a partir do cursor.

`ciw`

Modifica o conteúdo de uma palavra a partir do início dela.

> `c` pode ser combinado com os comandos de movimentação.
> 
> Exemplo: `c$` modifica o conteúdo até o fim da linha.
> 
> Exemplo: `c0` modifica o conteúdo até o início da linha.

`ciX`

Modifica o conteúdo entre a abertura e o fechamento do símbolo X. 

Exemplo: `ci(`, `ci[`.

`u`

Desfaz o último comando.

`ctrl + r`

Refaz o último comando desfeito.

`.`

Repete o último comando.

