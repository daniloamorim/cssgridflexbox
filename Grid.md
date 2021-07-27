# CSS GRID

## GRID

 -  Bidimensional
 - Divisão de toda página em linhas e colunas
 - Colocar os elementos onde quiser nessa divisão

---

## GRID OU FLEXBOX

 - Grid: Duas dimensões (colunas e linhas)
 - Flexbox: Uma dimensão (ou coluna ou linha)
 - Um complementa o trabalho do outro
 - Verificar quais navegadores ainda estão aceitando o Grid

---

 ## PROPRIEDADES

 Separado em 2 grupos:
 `container` e `item(s)`

---

 ### CONTAINER

 - display: grid; <!-- inicia dizendo que é um grid-->
 - grid-template-columns; <!-- fatia o template em colunas -->
 - grid-template-rows; <!-- fatia o template em linhas -->
 - grid-gap <!-- sobre os espaçamentos podendo ser por linha ou coluna -->
    - grid-row-gap
    - grid-column-gap
 - grid-template-areas; <!-- delimita as áreas -->

 ...e mais 4 propriedades e **alinhamento**

 ---

 ## ITEM(s)

 - grid-column  <!-- determina onde vai ficar o item conforme seu fatiamento-->
    - grid-column-start
    - grid-column-end
- grid-row <!--  determina onde vai ficar o item na linha conforme fatiamento-->
    - grid-row-start
    - grid-row-end
- grid-area <!-- diz onde vai ficar na área conforme  a escolha no container-->

... mais 2 propriedades de **alinhamento**