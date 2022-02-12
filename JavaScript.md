# JavaScript

### camelCase

Forma de nomear variáveis, em que 1ª letra da 1ª palavra é minúscula e as palavras subsequentes possuem a 1ª letra em maiúscula. 

```javascript
var camelCase;
```

### variáveis var let const

As variavéis **var** podem ser sobrescritas, podendo gerar bugs de sobrescrita indesejada. 

Enquanto **let** são variáveis que só podem ser declaras uma vez, ou seja, não é possível sobrescrever.

**const** são somente leitura. Eles são um valor constante, o que significa que uma vez que uma variável é atribuída com const, ela não pode ser reatribuída. Uma prática comum ao nomear constantes é usar todas as letras maiúsculas, com palavras separadas por um sublinhado.

```javascript
const FAV_GAME = "Far Cry 3";
```

É comum que os desenvolvedores usem identificadores de variáveis em: 

**maiúsculas** para valores **imutáveis** 

**minúsculas ou camelCase** para valores **mutáveis**