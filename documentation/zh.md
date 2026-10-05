<!-- ELUCENIA technical documentation · escala-de-katz · zh · no clinical/professional/rights approval -->

# Katz 指数（基本日常生活活动）

[条件、来源与许可](https://elucenia.org/zh/tools/escala-de-katz)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 洗澡（独立：自行洗澡或仅一个部位需帮助）

`banho`

- `0` — 依赖他人
- `1` — 独立

### 穿衣（独立：自行取衣并穿好，系鞋带除外）

`vestir`

- `0` — 依赖他人
- `1` — 独立

### 如厕（独立：自行去厕所、清洁及整理衣物）

`higiene`

- `0` — 依赖他人
- `1` — 独立

### 转移（独立：自行上下床及坐起离椅）

`transf`

- `0` — 依赖他人
- `1` — 独立

### 控便（独立：完全控制尿液及粪便）

`contin`

- `0` — 依赖他人
- `1` — 独立

### 进食（独立：自行将盘中食物送入口）

`alim`

- `0` — 依赖他人
- `1` — 独立

## 方法版本

二分计分Katz ADL：6项活动，总分0–6；HIGN 2019表格，略改编自Katz等1970年版本；不采用1963年的A–G分类

## 已记录的公式

每项独立完成活动1分（无需他人监督、指导、帮助）：洗澡、穿衣、如厕、转移、控制大小便、进食。总分0–6。

## 限制与适用人群

应记录指数版本及每项活动中独立性的定义。2008年巴西改编版研究了文化等效性和可靠性；这并不认证此二元实现及其新翻译。本地0–6总分不是历史上的A–G分类。 6项活动的二分计分总和已与HIGN 2019表格核对，该表声明略改编自Katz等1970年版本。这不是1963年的A–G分类，也不认证2008年巴西改编版或当前自行撰写的译文。独立性例外及评估老年人基本日常活动的目的应遵循相应表格。

## 参考文献

- [Katz S et al. Studies of illness in the aged. The index of ADL: a standardized measure of biological and psychosocial function. JAMA, 1963.](https://doi.org/10.1001/jama.1963.03060120024016)

- [Lino VTS et al. Adaptação transcultural da Escala de Independência em Atividades da Vida Diária (Escala de Katz). Cad Saude Publica, 2008.](https://doi.org/10.1590/S0102-311X2008000100010)

- [McCabe D. Katz Index of Independence in Activities of Daily Living. HIGN/NYU, Issue 2, revised 2019; slightly adapted from Katz et al. 1970.](https://hign.org/sites/default/files/2020-06/Try_This_General_Assessment_2.pdf)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026
