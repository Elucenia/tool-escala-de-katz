<!-- ELUCENIA technical documentation · escala-de-katz · es · no clinical/professional/rights approval -->

# Índice de Katz (ABVD)

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/escala-de-katz)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Baño (independiente: se baña sin ayuda o solo necesita ayuda para una parte del cuerpo)

`banho`

- `0` — Dependiente
- `1` — Independiente

### Vestirse (independiente: toma la ropa y se viste sin ayuda, excepto para atarse los zapatos)

`vestir`

- `0` — Dependiente
- `1` — Independiente

### Uso del baño (independiente: va al baño, se limpia y se arregla la ropa sin ayuda)

`higiene`

- `0` — Dependiente
- `1` — Independiente

### Transferencia (independiente: se acuesta y se levanta de la cama y de la silla sin ayuda)

`transf`

- `0` — Dependiente
- `1` — Independiente

### Continencia (independiente: control completo de orina y heces)

`contin`

- `0` — Dependiente
- `1` — Independiente

### Alimentación (independiente: lleva la comida del plato a la boca sin ayuda)

`alim`

- `0` — Dependiente
- `1` — Independiente

## Edición del método

Katz ADL binario: 6 actividades, total 0–6; formulario HIGN 2019, ligeramente adaptado de Katz et al. 1970; no incluye las categorías A–G de 1963

## Fórmula documentada

1 punto por actividad independiente (sin supervisión, orientación ni ayuda de otra persona): baño, vestido, retrete, traslado, continencia y alimentación. Total 0–6.

## Límites y población

Registre la versión del índice y las definiciones de independencia en cada actividad. La adaptación brasileña de 2008 se estudió en cuanto a equivalencia cultural y fiabilidad; esto no certifica esta implementación binaria ni sus nuevas traducciones. El total local 0–6 no es la clasificación histórica A–G. La suma binaria de 6 actividades se comprobó con el formulario HIGN de 2019, que se declara ligeramente adaptado de Katz et al. 1970. Esta fuente no es la clasificación A–G de 1963 ni certifica la adaptación brasileña de 2008 o las traducciones autorales actuales. Las excepciones de independencia y la finalidad de evaluar actividades básicas en personas mayores deben seguir el formulario correspondiente.

## Referencias

- [Katz S et al. Studies of illness in the aged. The index of ADL: a standardized measure of biological and psychosocial function. JAMA, 1963.](https://doi.org/10.1001/jama.1963.03060120024016)

- [Lino VTS et al. Adaptação transcultural da Escala de Independência em Atividades da Vida Diária (Escala de Katz). Cad Saude Publica, 2008.](https://doi.org/10.1590/S0102-311X2008000100010)

- [McCabe D. Katz Index of Independence in Activities of Daily Living. HIGN/NYU, Issue 2, revised 2019; slightly adapted from Katz et al. 1970.](https://hign.org/sites/default/files/2020-06/Try_This_General_Assessment_2.pdf)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
