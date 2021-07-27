# GRID: ALINHAMENTO

---

Existem 6 rpriedades para alinhamento:
1. `justfy-content`
2. `aling-content`
3. `justify-items`
4. `aling-items`
5. `justify-self`
6. `aling-self`

Vamos separar 2 grupos:
1. `justify` e `aling`
2. `content` , `items` e `self`

---

## Justify e Aling

Sabendo que o grid é bidimensional, temos o eixo x e o y.

O **eixo x** é o posicionamento horizontal, da esquerda para direita.

O **eixo y** é o posicionamento vertical, de cima para baixo.

---

## Content, Items e Self

Juntando o `justify`, ou `aling`, com esses elementos: `content`, `items` e `self`; Observamos nossas propriedades

---

### Content

`justify-content` e `aling-content` nos permite alinhar o próprio grid, relativo ao espaço fora do grid.
Uso raro, pois só é aplicado caso o grid seja menor que a área definida.
(Por exemplo, quando usa em px o tamanho do grid, pode terminar com um grid pequeno, para o tamanho da área do grid)

Podemos usar **7 valores**:
1. start
2. end
3. center
4. stretch
5.space-between
6. space-around
7. space-evenly
---

### Items

`justify-items` e `aling-items` vai  permitir alinhar os itens do grid, em qualquer espaço disponível , na célula que estiver.

Podemos usar **4 valores**:
1. start
2. end
3. center
4. stretch
---

### Self

`justify-self`e `aling-items` vai nos permitir alinhar o item em si.

Faz  mesma coisa que o `justify-items` e o `aling-items`, porém, aplicado diretamente no item de um grid.