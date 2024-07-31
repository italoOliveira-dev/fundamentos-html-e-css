Todo grid é composto de 2 principais grupos:
`container: o pai` e `itens: o(s) filhos`

---

### CONTAINER (pai)

- display: grid;
- grid-templates;
  - grid-template-columns;
  - grid-template-rows;
  - grid-template-area;
- gap;
  - row-gap;
  - column-gap;

---

### ITENS (filhos)

- grid-colum;
  - grid-colum-start;
  - grid-colum-end;
- grid-row;
  - grid-row-start;
  - grid-row-end;
- grid-area;

---

### PROPRIEDADES DE ALINHAMENTO

Existem 9 propriedades fundamentais

**6 aplicadas em container**
`align-content`
`justify-content`
`place-content`

`align-items`
`justify-items`
`place-items`

**3 aplicadas em items**
`align-self`
`justfy-self`
`place-self`

Então podemos separar em três grupos:
`align`, `justify`, `place`

E cada um deles irá observar ou o:

- conteúdo od elemento `content`
- itens do elemento `items`
- o próprio elemento `self`
