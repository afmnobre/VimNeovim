# Comandos Neovim

**Criação de Linha:**

| Comando  | Descrição                   |
| -------- | --------------------------- |
| Ctrl + o | Cria uma nova linha ABAIXO. |
| Crtl + O | Cria uma nova Linha ACIMA.  |

**Movimentação:**

| Comando      | Descrição                                                                                  |
|:------------:| ------------------------------------------------------------------------------------------ |
| i            | Modo de Inserção antes do cursor.                                                          |
| I            | Modo de Inserção no começo da linha.                                                       |
| a            | Modo de Inserção depois do cursor.                                                         |
| A            | Modo de inserção no Final da Linha.                                                        |
| gg           | Inicio do arquivo.                                                                         |
| G            | Final do Arquivo.                                                                          |
| Ctrl + u     | Move pagina acima.                                                                         |
| Ctrl + d     | Mode pagina abaixo.                                                                        |
| \<num\> + gg | Navega até a linha especifica no arquivo.                                                  |
| \<num\> + %  | Navega até a posição em porcentagem do arquivo.                                            |
| (            | Pula para a frase anterior.                                                                |
| )            | Pula para a proxima frase.                                                                 |
| {            | Pula para o paragrafo anterior.                                                            |
| }            | Pula para o próximo paragrafo.                                                             |
| w            | Pula pra proxima palavra.                                                                  |
| W            | Pula pra proxima palavra em "Programação." (só considera espaços como quebra de plavras).  |
| b            | Pula pra palavra anterior.                                                                 |
| B            | Pula pra palabra anterior em "Programação." (só considera espaços como quebra de plavras). |
| e            | Pula pro final da palavra.                                                                 |
| \$           | Pula pro Final da Linha(sem entrar no modo de edição).                                     |
| ^            | Pula pro começo da Linha (sem entrar no modo de edição).                                   |
| 0            | Vai pro inicio da Linha ABSOLUTO, incluindo espaços.                                       |
| zz           | Centraliza a tela aonde o cursor esta.                                                     |
| zb           | Movimenta para cima.                                                                       |
| zt           | Movimenta para baixo.                                                                      |
| H            | Salta para o inicio da Tela.                                                               |
| M            | Salta para o meio da Tela.                                                                 |
| L            | Salta para o final da Tela.                                                                |
| [m           | Salta para o proximo método.                                                               |
| ]m           | Salta para o método anterior.                                                              |
| \<num\> [m   | Salta para o proximo método de acordo com o numero.                                        |
| \<num\> ]m   | Salta para o método anterior de acordo com o numero.                                       |
| [[           | salta para a proxima classe.                                                               |
| ]]           | salta para a classe anterior.                                                              |
| %            | Vai para o começo ou o fim do entre pares: {} [] ()                                        |
| gi           | Volta a tela para onde vc estava inserindo.                                                |
| Ctrl + o     | Volta para o ultimo salto de linha.                                                        |
| Ctrl + i     | Avança um salto de linha ja feito.                                                         |
|              |                                                                                            |
|              |                                                                                            |
|              |                                                                                            |
|              |                                                                                            |

**Buffers:**

| Comando                | Descrição                                                                                    |
| ---------------------- | -------------------------------------------------------------------------------------------- |
| :ls                    | Lista todos os Buffers abertos                                                               |
| :b\<num\>              | Vai para o Buffer definido.                                                                  |
| :bn                    | Vai para o próximo Buffer.                                                                   |
| :bp                    | Vai para o Buffer anterior.                                                                  |
| :bufdo                 | Fazer um comando em todos os buffers.                                                        |
| Ctrl + w + v           | Split de Tela Vertical                                                                       |
| Ctrl + w + s           | Split de Tela Horizontal                                                                     |
| Ctrl + w + q           | Fecha o Buffer                                                                               |
| Ctrl + w + (hjkl)      | Faz a movimentação entre os SPLITS.                                                          |
| :Tabnew                | Criando uma Tab                                                                              |
| :Tabs                  | Listando as Tabs                                                                             |
| :set foldmethod=indent | Miniza Classes e Funções para "melhorar" a visualizaçao do código (za = Abre e fecha a FOLD) |
| za                     | Abre e fecha a estrutura fold.                                                               |
| zr                     | Abre todas as Estruturas  Fold                                                               |
| zm                     | Fecha todas as Estrutura Fold                                                                |
|                        |                                                                                              |

**Manipulação:**

| Comando             | Descrição                                                                                                                             |
|:-------------------:| ------------------------------------------------------------------------------------------------------------------------------------- |
| s                   | Exclui o caracter que o cursor esta em cima e entra no modo de inserção.                                                              |
| S                   | Exclui a linha que o cursor esta e entra no modo de inserção.                                                                         |
| C                   | Exclui o resto da linha a frente do curso e entra no modo de inserção.                                                                |
| dw                  | Apaga Palavra.                                                                                                                        |
| \<num\>dw           | Apaga x palavras a frente do cursor.                                                                                                  |
| di (                | Deleta tudo que esta dentro dos Parenteses.                                                                                           |
| cit                 | Apaga o conteudo da TAG HTML e entra no modo de inserção dentro da TAG HTML.                                                          |
| cat                 | Apaga a TAG HTML inteira.                                                                                                             |
| dt\<carater\>       | Apaga tudo até o caracter especificado.                                                                                               |
| r                   | replace de caracter.                                                                                                                  |
| R                   | Entra no modo de REPLACE de catater para toda a linha a frente do Cursor.                                                             |
| yy                  | Copia a linha inteira.                                                                                                                |
| Y                   | Copia o resto da linha inteira depois do cursor.                                                                                      |
| p                   | Cola após o cursor.                                                                                                                   |
| P                   | Cola antes do cursor.                                                                                                                 |
| u                   | desfaz alterações.                                                                                                                    |
| J                   | agrupa uma função mutilinha em uma unica linha.                                                                                       |
| x                   | Deleta 1 caracter.                                                                                                                    |
| \<num\>x            | Deleta x caracteres a frente do cursor.                                                                                               |
| X                   | Deleta 1 caracter anterior ao cursor.                                                                                                 |
| \<num\>X            | Deleta x caracteres anteriores ao cursor.                                                                                             |
| n                   | Proxima ocorrencia encontrada depois de fazer a BUSCA                                                                                 |
| N                   | Ocorrencia anterior depois de fazer a BUSCA.                                                                                          |
| \#                  | Realiza uma busca anterior da palavra que o cursor esta em cima.                                                                      |
| \*                  | Realiza uma busca a frente da palavra que o cursor esta em cima.                                                                      |
| Ctrl + a            | Incremento numerico.                                                                                                                  |
| \<num\> Ctrl + a    | incrementa o numero pelo número especificado.                                                                                         |
| Ctrl + i            | Decremento numérico.                                                                                                                  |
| \<num\> Ctrl + i    | Decrementa o numero pelo número especificado.                                                                                         |
| Ctrl x + Ctrl n     | Autocompleta palavras de acordo com o arquivo que esta aberto.                                                                        |
| Ctrl x + Ctrl l     | Mostra todas as incidencia de uma função e completa a linha inteira. (segurar o control e apertar o L para selecionar a que vc quer). |
| .                   | Quando vc faz qualquer alteração vc pode entrar no modo normal e digitar (.) ponto que a alteração sera repetida.                     |
| ~                   | Transforma o caracter MAIÚSCULO ou MINÚSCULO.                                                                                         |
| \<num\>~            | Transforma os proximos X caracteres em MAIÚSCULOS ou MINÚSCULOS.                                                                      |
| retab               | retabula todos os arquivos de acordo com sua configuração de TAB.                                                                     |
| :g/\<palavra\>/d    | Deleta a linha que possui a palabra procurada.                                                                                        |
| :normal + comandos  | Faz o comando como se fosse no modo normal em 1 linha.                                                                                |
| :%normal + comandos | Faz o comando no modo normal no arquivo inteiro.                                                                                      |
|                     |                                                                                                                                       |
| $                   |                                                                                                                                       |

**Macro(passo a passo):**

| Comando                   | Descrição                                                    |
|:-------------------------:| ------------------------------------------------------------ |
| q                         | Começa a criar a macro.                                      |
| a                         | Nomeia a macro, pode ser qualquer letra, no caso aqui é "a". |
| \<comandos\>              | Faça o que a macro tem que fazer.                            |
| q                         | Grave a macro.                                               |
| @\<nome da macro\>        | Executa a macro.                                             |
| \<num\>@\<nome da macro\> | Executa a macro X vezes.                                     |

**Dicionário:**

| Comando | Descrição                                                                   |
|:-------:| --------------------------------------------------------------------------- |
|         | :set spelllang=pt_br                                                        |
| [s      | Proximo erro de português.                                                  |
| ]s      | Erro de porguês anterior.                                                   |
| z=      | Com o cursor em cima da palavra errada ele mostra as sugestões de correção. |

**Seleção:**

| Comando  | Descrição                             |
|:--------:| ------------------------------------- |
| v        | Entra no modo de seleção de Caracter. |
| V        | Entra no modo de seleção de Linhas.   |
| Ctrl + V | Entra no modo de seleção em Bloco.    |

**Integração com Bash:**

| Comando          | Descrição                                                 |
| ---------------- | --------------------------------------------------------- |
| :r!sudo ifconfig | Pega o resultado do comando ifconfig e coloca no arquivo. |
| :!sudo infconfig | Só mostra a saida do comando mas não coloca no arquivo.   |
|                  |                                                           |
|                  |                                                           |
|                  |                                                           |
