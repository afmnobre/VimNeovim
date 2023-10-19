# Comandos Neovim



**Criação de Linha:**

Ctrl + o    - Cria uma nova linha ABAIXO
Crtl + O    - Cria uma nova Linha ACIMA



**Movimentação:**

i    - Modo de Inserção antes do cursor.

I    - Modo de Inserção no começo da linha.

a    - Modo de Inserção depois do cursor.

A    - Modo de inserção no Final da Linha.

gg    - inicio do arquivo.

G    - final do Arquivo.

Ctrl + u    - Move pagina acima.

Ctrl + d    - Mode pagina abaixo.

<num> + gg    - Navega até a linha especifica no arquivo.

<num> + %    - Navega até a posição em porcentagem do arquivo.

(     - Pula para a frase anterior.

)     - Pula para a proxima frase.

{     - Pula para o paragrafo anterior.

}     - Pula para o próximo paragrafo.

w    - Pula pra proxima palavra.

W    - Pula pra proxima palavra em "Programação." - (só considera espaços como quebra de plavras).

b    -  Pula pra palavra anterior.

B    - Pula pra palabra anterior em "Programação." - (só considera espaços como quebra de plavras).

e    - Pula pro final da palavra.

\$    - Pula pro Final da Linha(sem entrar no modo de edição).

^     - Pula pro começo da Linha (sem entrar no modo de edição).

0    - Vai pro inicio da Linha ABSOLUTO, incluindo espaços.

zz    - Centraliza a tela aonde o cursor esta.

zb    - Movimenta para cima.

zt    - Movimenta para baixo.

H    - Salta para o inicio da Tela.

M    - Salta para o meio da Tela.

L    - Salta para o final da Tela.

[m    - Salta para o proximo método.

]m    - Salta para o método anterior.

<num> [m    - Salta para o proximo método de acordo com o numero.

<num> ]m    - Salta para o método anterior de acordo com o numero.

[[    - salta para a proxima classe.

]]    - salta para a classe anterior.

%    - Vai para o começo ou o fim do entre pares: {} [] ()

gi    - Volta a tela para onde vc estava inserindo.

Ctrl + o    - Volta para o ultimo salto de linha.

Ctrl + i    - Avança um salto de linha ja feito.



**Manipulação:**

s    - Exclui o caracter que o cursor esta em cima e entra no modo de inserção.

S    - Exclui a linha que o cursor esta e entra no modo de inserção.

C    - Exclui o resto da linha a frente do curso e entra no modo de inserção.

dw -    Apaga Palavra.

<num>dw    - Apaga x palavras a frente do cursor.

di (     - Deleta tudo que esta dentro dos Parenteses.

cit    - Apaga o conteudo da TAG HTML e entra no modo de inserção dentro da TAG HTML.

cat    - Apaga a TAG HTML inteira.

dt<carater>    - Apaga tudo até o caracter especificado.

r    - replace de caracter.

R    - Entra no modo de REPLACE de catater para toda a linha a frente do Cursor.

yy    - Copia a linha inteira.

Y    - Copia o resto da linha inteira depois do cursor.

p    - Cola após o cursor.

P    - Cola depois do cursor.

u    - desfaz alterações.

J    - agrupa uma função mutilinha em uma unica linha.

x    - Deleta 1 caracter.

<num>x    - Deleta x caracteres a frente do cursor.

X    - Deleta 1 caracter anterior ao cursor.

<num>X    - Deleta x caracteres anteriores ao cursor.

n    - Proxima ocorrencia encontrada depois de fazer a BUSCA

N    - Ocorrencia anterior depois de fazer a BUSCA.

\#    - Realiza uma busca anterior da palavra que o cursor esta em cima.

\*    - Realiza uma busca a frente da palavra que o cursor esta em cima.

Ctrl + a    - Incremento numerico.

<num> Ctrl + a    - incrementa o numero pelo número especificado.

Ctrl + i     - Decremento numérico.

<num> Ctrl + i    - Decrementa o numero pelo número especificado.

Ctrl x + Ctrl n    - Autocompleta palavras de acordo com o arquivo que esta aberto.

Ctrl x + Ctrl l    - Mostra todas as incidencia de uma função e completa a linha inteira. (segurar o control e apertar o L para selecionar a que vc quer)



**Macro(passo a passo):**

q    - Começa a criar a macro

a    - Nomeia a macro

<faça o que a macro tem que fazer>

q    - Grave a macro.

@<nome da macro>    - Executa a macro.

<num>@<nome da macro>    - Executa a macro X vezes



**Seleção:**

v    - Entra no modo de seleção de caracter.

V    - Entra no modo de seleção de Linhas.




