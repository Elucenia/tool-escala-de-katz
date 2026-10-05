<!-- ELUCENIA technical documentation · escala-de-katz · pt-BR · no clinical/professional/rights approval -->

# Índice de Katz (ABVD)

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/escala-de-katz)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Banho (independente: banha-se sozinho ou precisa de ajuda só para uma parte do corpo)

`banho`

- `0` — Dependente
- `1` — Independente

### Vestir-se (independente: pega as roupas e veste-se sem ajuda, exceto amarrar sapatos)

`vestir`

- `0` — Dependente
- `1` — Independente

### Uso do banheiro (independente: vai ao banheiro, higieniza-se e arruma as roupas sem ajuda)

`higiene`

- `0` — Dependente
- `1` — Independente

### Transferência (independente: deita e levanta da cama e da cadeira sem ajuda)

`transf`

- `0` — Dependente
- `1` — Independente

### Continência (independente: controle completo de urina e fezes)

`contin`

- `0` — Dependente
- `1` — Independente

### Alimentação (independente: leva a comida do prato à boca sem ajuda)

`alim`

- `0` — Dependente
- `1` — Independente

## Edição do método

Katz ADL binário: 6 atividades, total 0–6; formulário HIGN 2019, ligeiramente adaptado de Katz et al. 1970; sem categorias A–G de 1963

## Fórmula documentada

1 ponto para cada atividade realizada de forma independente (sem supervisão, orientação ou ajuda de outra pessoa): banho, vestir-se, uso do banheiro, transferência, continência e alimentação. Total de 0 a 6.

## Limites e população

Registre a versão do índice e as definições de independência em cada atividade. A adaptação brasileira de 2008 foi estudada quanto à equivalência cultural e confiabilidade; isso não certifica esta implementação binária nem suas novas traduções. O total local 0–6 não é a classificação histórica A–G. A soma binária de 6 atividades foi conferida contra o formulário HIGN de 2019, que se declara ligeiramente adaptado de Katz et al. 1970. Essa fonte não é a classificação A–G de 1963 nem certifica a adaptação brasileira de 2008 ou as traduções autorais atuais. As exceções de independência e a finalidade de avaliação de atividades básicas em pessoas idosas devem seguir o formulário correspondente.

## Referências

- [Katz S et al. Studies of illness in the aged. The index of ADL: a standardized measure of biological and psychosocial function. JAMA, 1963.](https://doi.org/10.1001/jama.1963.03060120024016)

- [Lino VTS et al. Adaptação transcultural da Escala de Independência em Atividades da Vida Diária (Escala de Katz). Cad Saude Publica, 2008.](https://doi.org/10.1590/S0102-311X2008000100010)

- [McCabe D. Katz Index of Independence in Activities of Daily Living. HIGN/NYU, Issue 2, revised 2019; slightly adapted from Katz et al. 1970.](https://hign.org/sites/default/files/2020-06/Try_This_General_Assessment_2.pdf)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
