# How to contribute

Thank you for helping. Every change must point to a public source.

## Report an error

Open an issue with:

1. The company and the model file.
2. The sheet and the cell (for example `EEFF!D14`).
3. The value in the model and the correct value.
4. The source: the document, the page and, if you have it, a link.

## Propose a different assumption

Assumptions are opinions. Different people can have good reasons for different values.

1. Open an issue or a pull request.
2. Give the assumption (sheet and cell), your value and your reason.
3. If a source supports it (a company guidance, a regulator, an industry report), give the link.

## Add a company

Open an issue with the company name, the exchange and links to its last five annual reports.

## Rules for changes to a model

- Do not change the published statements (`EEFF`, `Notas_EEFF`, historical columns). Those cells copy
  the filings. If a filing has an error, say so in a note; do not change the number.
- Keep projections as formulas. Do not type a number over a formula.
- Do not make a check weaker to make it pass.
- Tell what you changed in the pull request: sheet, cells, old value, new value, reason.

## License of your contribution

You give your change under the license of the thing you change: a model or a text under
[CC BY-SA 4.0](LICENSE), dashboard code under [MIT](dashboard/LICENSE). You keep your copyright.

---

## Cómo contribuir (español)

Gracias por ayudar. Todo cambio debe citar una fuente pública.

- **Error:** abre un issue con la empresa, la hoja y la celda, el valor del modelo, el valor correcto y
  la fuente (documento y página).
- **Supuesto distinto:** propón tu valor y tu razón en un issue o un pull request, con la fuente si la
  tienes.
- **Empresa nueva:** abre un issue con el nombre, la bolsa y los enlaces a sus últimos cinco informes
  anuales.
- No cambies los estados publicados, no escribas números encima de fórmulas y no aflojes un chequeo
  para que pase.
- Tu cambio queda bajo la licencia de lo que cambias: un modelo o un texto bajo CC BY-SA 4.0, código
  del dashboard bajo MIT. Conservas tu copyright.
