<!-- ELUCENIA technical documentation · escala-de-katz · en · no clinical/professional/rights approval -->

# Katz Index (basic ADL)

[conditions, sources and permissions](https://elucenia.org/en/tools/escala-de-katz)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Bathing (independent: bathes unaided or needs help with only one body part)

`banho`

- `0` — Dependent
- `1` — Independent

### Dressing (independent: gets clothes and dresses unaided, except tying shoes)

`vestir`

- `0` — Dependent
- `1` — Independent

### Toileting (independent: goes to the toilet, cleans themselves and adjusts clothing unaided)

`higiene`

- `0` — Dependent
- `1` — Independent

### Transferring (independent: gets into and out of bed and a chair unaided)

`transf`

- `0` — Dependent
- `1` — Independent

### Continence (independent: complete bladder and bowel control)

`contin`

- `0` — Dependent
- `1` — Independent

### Feeding (independent: takes food from the plate to the mouth unaided)

`alim`

- `0` — Dependent
- `1` — Independent

## Method edition

Binary Katz ADL: 6 activities, total 0–6; HIGN 2019 form, slightly adapted from Katz et al. 1970; excludes the 1963 A–G categories

## Documented formula

1 point per independent activity (without another person’s supervision, guidance or help): bathing, dressing, toileting, transfer, continence and feeding. Total 0–6.

## Limits and population

Record the index version and the definitions of independence for each activity. The 2008 Brazilian adaptation was studied for cultural equivalence and reliability; this does not certify this binary implementation or its new translations. The local 0–6 total is not the historical A–G classification. The binary sum of 6 activities was checked against the HIGN 2019 form, which describes itself as slightly adapted from Katz et al. 1970. This source is not the 1963 A–G classification and does not certify the Brazilian 2008 adaptation or the current authored translations. Independence exceptions and the purpose of assessing basic activities in older people must follow the corresponding form.

## References

- [Katz S et al. Studies of illness in the aged. The index of ADL: a standardized measure of biological and psychosocial function. JAMA, 1963.](https://doi.org/10.1001/jama.1963.03060120024016)

- [Lino VTS et al. Adaptação transcultural da Escala de Independência em Atividades da Vida Diária (Escala de Katz). Cad Saude Publica, 2008.](https://doi.org/10.1590/S0102-311X2008000100010)

- [McCabe D. Katz Index of Independence in Activities of Daily Living. HIGN/NYU, Issue 2, revised 2019; slightly adapted from Katz et al. 1970.](https://hign.org/sites/default/files/2020-06/Try_This_General_Assessment_2.pdf)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
