# OpenFinmods

Open financial models and public filing texts. One Excel model per company.
The project starts with Panama and aims to cover public companies across Latin America.
This collection also includes selected companies from other regions.

*En español más abajo.*

> These models can contain errors. Check the original filings before you rely on a number or assumption.
> This collection is not investment advice.

## Snapshot: October 29, 2026

- **48 companies and 48 Excel models:** 22 companies from Panama and 26 from other countries.
- **125 filing texts and 14 SEC filing indexes**, covering 33 companies. Coverage differs by company.
- Filing texts include annual and interim reports, prospectuses, and material-event notices.
- Meta, Anthropic, Cerebras, and SpaceX are included in this snapshot.
- A [dashboard](dashboard/README.md) is planned. This snapshot contains its description and license, not an application.

These files are a dated snapshot. Prices, exchange rates, forecasts, and filing lists do not update automatically.
A filing date in a filename identifies that document; it does not establish that the document is the latest available today.

## How to read a model

Start with the workbook's contents, assumptions, and source register where those sheets exist.
Sheet names and periods differ across templates. Most forecast models separate reported statements, assumptions, forecasts, and checks.

- Reported statements and notes preserve the published figures.
- Forecast cells use formulas and assumptions. Forecast periods vary by model; read the column headings.
- Some templates select Base, Bull, or Bear through `Supuestos!C5` or `Assumptions!C5`.
- Check sheets test specific relationships, such as balance-sheet equality and cash reconciliation.
- Source registers identify supporting documents where provided.

ETESA and G.B. Group contain historical statements only. They do not contain forecasts.
Banco Delta and Banco de Bogotá have no dedicated check sheet.
A model's own check result is not an audit, an independent review, or a guarantee of accuracy.

### Validation of this export

The 48 exported models were recalculated and compared with their source snapshots.
The comparison found no changes in the 54,939 formula cells outside the replaced internal audit history, and no material differences in 97,818 numeric cells.
Numeric comparisons allow for floating-point precision. No spreadsheet error values were found in either set.

The models' own registered check cells returned `PASS` or `OK` in 44 models.
Banco de Bogotá, Banco Delta, ETESA, and G.B. Group have no registered overall check cell.
The company table reports the result read during this export; [models.csv](models.csv) records each check cell and file hash.

These checks establish that the exported calculations match the source snapshots.
They do not independently validate source figures, forecast assumptions, valuations, or the coverage of a model's own checks.
This export is not an independent financial audit or a refresh of market data.

## Companies

The Filings column links to the available public texts. A dash means this snapshot has no filing text for that company.
SEC indexes list filing links; they are not additional filing texts.

| Country | Company | Sector | Model | Filings | Own check at export |
|---|---|---|---|---|---|
| Panama | Banco Aliado, S.A. y Subsidiarias | banks | [banco-aliado.xlsx](companies/panama/banco-aliado/banco-aliado.xlsx) | [13 texts](companies/panama/banco-aliado/filings/) | PASS |
| Panama | Banco Delta, S.A. (BANDELTA) | banks | [banco-delta.xlsx](companies/panama/banco-delta/banco-delta.xlsx) | — | No registered check |
| Panama | Banco General, S.A. y Subsidiarias | banks | [banco-general.xlsx](companies/panama/banco-general/banco-general.xlsx) | [4 texts](companies/panama/banco-general/filings/) | PASS |
| Panama | Banco La Hipotecaria, S.A. | banks | [banco-la-hipotecaria.xlsx](companies/panama/banco-la-hipotecaria/banco-la-hipotecaria.xlsx) | — | PASS |
| Panama | Corporación de Finanzas del País, S.A. y Subsidiarias | non-bank-lenders | [panacredit.xlsx](companies/panama/panacredit/panacredit.xlsx) | [5 texts](companies/panama/panacredit/filings/) | PASS |
| Panama | Electron Investment, S.A. (EISA) | power-generation | [eisa.xlsx](companies/panama/eisa/eisa.xlsx) | [4 texts](companies/panama/eisa/filings/) | PASS |
| Panama | Elektra Noreste, S.A. (ENSA) | power-distribution | [ensa.xlsx](companies/panama/ensa/ensa.xlsx) | — | PASS |
| Panama | Empresa de Distribución Eléctrica Metro-Oeste, S.A. | power-distribution | [edemet.xlsx](companies/panama/edemet/edemet.xlsx) | — | PASS |
| Panama | Empresa de Transmisión Eléctrica, S.A. (ETESA) | power-transmission | [etesa.xlsx](companies/panama/etesa/etesa.xlsx) | — | No registered check |
| Panama | Empresa General de Inversiones, S.A. | banks | [empresa-general-de-inversiones.xlsx](companies/panama/empresa-general-de-inversiones/empresa-general-de-inversiones.xlsx) | — | PASS |
| Panama | Empresas Melo, S.A. | food-agriculture | [empresas-melo.xlsx](companies/panama/empresas-melo/empresas-melo.xlsx) | [4 texts](companies/panama/empresas-melo/filings/) | PASS |
| Panama | G.B. Group Corporation y Subsidiarias | banks | [gb-group-corporation.xlsx](companies/panama/gb-group-corporation/gb-group-corporation.xlsx) | — | No registered check |
| Panama | Generadora de Gatún, S.A. | power-generation | [gana-gatun.xlsx](companies/panama/gana-gatun/gana-gatun.xlsx) | [2 texts](companies/panama/gana-gatun/filings/) | PASS |
| Panama | Global Bank Corporation (GLOBAN) | banks | [global-bank.xlsx](companies/panama/global-bank/global-bank.xlsx) | [12 texts](companies/panama/global-bank/filings/) | PASS |
| Panama | Grupo Aliado, S.A. | banks | [grupo-aliado.xlsx](companies/panama/grupo-aliado/grupo-aliado.xlsx) | [7 texts](companies/panama/grupo-aliado/filings/) | PASS |
| Panama | Grupo ASSA, S.A. | insurance | [assa.xlsx](companies/panama/assa/assa.xlsx) | [5 texts](companies/panama/assa/filings/) | PASS |
| Panama | Grupo CALESA | food-agriculture | [calesa.xlsx](companies/panama/calesa/calesa.xlsx) | [24 texts](companies/panama/calesa/filings/) | PASS |
| Panama | Grupo Melo, S.A. | food-agriculture | [grupo-melo.xlsx](companies/panama/grupo-melo/grupo-melo.xlsx) | [4 texts](companies/panama/grupo-melo/filings/) | PASS |
| Panama | Panama Power Holdings, Inc. | power-generation | [pph.xlsx](companies/panama/pph/pph.xlsx) | [4 texts](companies/panama/pph/filings/) | PASS |
| Panama | Petróleos Delta, S.A. y Subsidiaria | oil-gas-fuels | [petroleos-delta.xlsx](companies/panama/petroleos-delta/petroleos-delta.xlsx) | [4 texts](companies/panama/petroleos-delta/filings/) | PASS |
| Panama | Tigo Panamá / Grupo de Comunicaciones Digitales | telecom | [tigo.xlsx](companies/panama/tigo/tigo.xlsx) | [6 texts](companies/panama/tigo/filings/) | PASS |
| Panama | UEP Penonomé II, S.A. | power-generation | [uepii-penonome.xlsx](companies/panama/uepii-penonome/uepii-penonome.xlsx) | [4 texts](companies/panama/uepii-penonome/filings/) | PASS |
| Colombia | Banco de Bogotá S.A. | banks | [banco-de-bogota.xlsx](companies/colombia/banco-de-bogota/banco-de-bogota.xlsx) | — | No registered check |
| Colombia | Banco de Occidente S.A. | banks | [banco-de-occidente.xlsx](companies/colombia/banco-de-occidente/banco-de-occidente.xlsx) | — | PASS |
| Colombia | Bancolombia S.A. | banks | [bancolombia.xlsx](companies/colombia/bancolombia/bancolombia.xlsx) | [1 text + SEC index](companies/colombia/bancolombia/filings/) | PASS |
| Colombia | Empresas Públicas de Medellín | power-generation | [epm.xlsx](companies/colombia/epm/epm.xlsx) | — | PASS |
| Colombia | Grupo Aval Acciones y Valores S.A. | banks | [grupo-aval.xlsx](companies/colombia/grupo-aval/grupo-aval.xlsx) | [1 text + SEC index](companies/colombia/grupo-aval/filings/) | PASS |
| Colombia | Grupo de Inversiones Suramericana S.A. | insurance | [grupo-sura.xlsx](companies/colombia/grupo-sura/grupo-sura.xlsx) | — | PASS |
| Germany | adidas AG | consumer-cyclical | [adidas.xlsx](companies/germany/adidas/adidas.xlsx) | — | PASS |
| Netherlands | ASML Holding N.V. | data-centers-ai-semiconductors | [asml.xlsx](companies/netherlands/asml/asml.xlsx) | [1 text + SEC index](companies/netherlands/asml/filings/) | PASS |
| South Korea | Samsung Electronics Co., Ltd. | data-centers-ai-semiconductors | [samsung.xlsx](companies/south-korea/samsung/samsung.xlsx) | — | PASS |
| South Korea | SK hynix Inc. | data-centers-ai-semiconductors | [sk-hynix.xlsx](companies/south-korea/sk-hynix/sk-hynix.xlsx) | — | PASS |
| Taiwan | Taiwan Semiconductor Manufacturing Company | data-centers-ai-semiconductors | [tsmc.xlsx](companies/taiwan/tsmc/tsmc.xlsx) | [1 text + SEC index](companies/taiwan/tsmc/filings/) | PASS |
| United States | Amazon.com, Inc. | retail-supermarkets | [amazon.xlsx](companies/united-states/amazon/amazon.xlsx) | [1 text + SEC index](companies/united-states/amazon/filings/) | OK |
| United States | Anthropic, PBC | data-centers-ai-semiconductors | [anthropic.xlsx](companies/united-states/anthropic/anthropic.xlsx) | [1 text](companies/united-states/anthropic/filings/) | OK |
| United States | Apple Inc. | consumer-cyclical | [apple.xlsx](companies/united-states/apple/apple.xlsx) | [1 text + SEC index](companies/united-states/apple/filings/) | OK |
| United States | Berkshire Hathaway Inc. | insurance | [berkshire-hathaway.xlsx](companies/united-states/berkshire-hathaway/berkshire-hathaway.xlsx) | [1 text + SEC index](companies/united-states/berkshire-hathaway/filings/) | PASS |
| United States | Cargill, Incorporated | food-agriculture | [cargill.xlsx](companies/united-states/cargill/cargill.xlsx) | — | PASS |
| United States | Cerebras Systems Inc. | data-centers-ai-semiconductors | [cerebras.xlsx](companies/united-states/cerebras/cerebras.xlsx) | [2 texts](companies/united-states/cerebras/filings/) | OK |
| United States | Liberty Latin America Ltd. | telecom | [liberty-latin-america.xlsx](companies/united-states/liberty-latin-america/liberty-latin-america.xlsx) | [1 text + SEC index](companies/united-states/liberty-latin-america/filings/) | PASS |
| United States | Meta Platforms, Inc. | communication-services | [meta.xlsx](companies/united-states/meta/meta.xlsx) | [2 texts](companies/united-states/meta/filings/) | OK |
| United States | NextEra Energy, Inc. | power-generation | [nextera.xlsx](companies/united-states/nextera/nextera.xlsx) | [1 text + SEC index](companies/united-states/nextera/filings/) | PASS |
| United States | NIKE, Inc. | consumer-cyclical | [nike.xlsx](companies/united-states/nike/nike.xlsx) | [1 text + SEC index](companies/united-states/nike/filings/) | OK |
| United States | NVIDIA Corporation | data-centers-ai-semiconductors | [nvidia.xlsx](companies/united-states/nvidia/nvidia.xlsx) | [1 text + SEC index](companies/united-states/nvidia/filings/) | PASS |
| United States | Space Exploration Technologies Corp. (SpaceX, con xAI, X y Cursor) | data-centers-ai-semiconductors | [spacex.xlsx](companies/united-states/spacex/spacex.xlsx) | [4 texts](companies/united-states/spacex/filings/) | OK |
| United States | T-Mobile US, Inc. | telecom | [t-mobile.xlsx](companies/united-states/t-mobile/t-mobile.xlsx) | [1 text + SEC index](companies/united-states/t-mobile/filings/) | PASS |
| United States | The Coca-Cola Company | consumer-non-cyclical | [coca-cola.xlsx](companies/united-states/coca-cola/coca-cola.xlsx) | [1 text + SEC index](companies/united-states/coca-cola/filings/) | OK |
| United States | Tyson Foods, Inc. | food-agriculture | [tyson.xlsx](companies/united-states/tyson/tyson.xlsx) | [1 text + SEC index](companies/united-states/tyson/filings/) | OK |

## How to download

- **One model:** select its link above, then use the download button on the file page.
- **The collection:** use **Code → Download ZIP** on the repository page, or clone the repository.

## Public filing texts

The Panama texts were extracted from public filings using optical character recognition (OCR).
SEC annual-report texts and filing indexes are retained from the earlier snapshot.
The added Meta, Anthropic, Cerebras, and SpaceX texts were converted from saved HTML documents.
Tables retain their source values. OCR and HTML conversion can introduce errors or affect layout.
Compare a disputed figure with the original document.

Original source links appear where retained metadata supplied them.
A missing link means this snapshot did not retain the original URL; it does not establish the document's absence.
Original PDFs and images are not included.

## How to contribute

- **Report an error:** give the company, sheet, cell, proposed correction, and source document and page.
- **Propose an assumption:** explain the value and the reason. Cite a public source when one supports the proposal.
- **Request a company:** provide its name and links to its public filings.

See [CONTRIBUTING.md](CONTRIBUTING.md). Published statements must remain faithful to their sources.
Do not replace forecast formulas with fixed values or weaken checks to make them pass.

## License

The models and original project text use [CC BY-SA 4.0](LICENSE).
Credit OpenFinmods when required by the license, identify changes, and share adaptations under the same license.
See the license for the complete terms.
The planned dashboard has a separate [MIT license](dashboard/LICENSE).

The source documents remain subject to their original rights.
Their inclusion here does not change the rights held by their publishers.

---

# OpenFinmods (español)

Modelos financieros abiertos y textos de documentos públicos. Un modelo de Excel por empresa.
El proyecto empieza con Panamá y busca cubrir las empresas públicas de Latinoamérica.
También incluye empresas seleccionadas de otras regiones.

> Los modelos pueden contener errores. Comprueba las cifras y los supuestos contra los documentos originales.
> Esta colección no es una recomendación de inversión.

## Copia del 29 de octubre de 2026

- **48 empresas y 48 modelos:** 22 empresas de Panamá y 26 de otros países.
- **125 textos de documentos y 14 índices de documentos de la SEC.** La cobertura varía por empresa.
- Esta copia incluye Meta, Anthropic, Cerebras y SpaceX.
- El [dashboard](dashboard/README.md) está previsto. Esta copia contiene su descripción y licencia, no una aplicación.

Los precios, tipos de cambio, proyecciones e índices de documentos no se actualizan automáticamente.
Los periodos y las hojas cambian según la plantilla. Lee los encabezados de cada modelo.
ETESA y G.B. Group solo contienen estados históricos. Banco Delta y Banco de Bogotá no tienen una hoja específica de chequeos.
El resultado de un chequeo propio no equivale a una auditoría ni a una revisión independiente.
Los 48 modelos exportados se recalcularon y compararon con sus copias fuente.
No hubo cambios en las 54,939 celdas con fórmulas fuera del historial interno de auditoría reemplazado, ni diferencias materiales en 97,818 celdas numéricas.
La comparación numérica permite diferencias de precisión de cálculo. No se encontraron valores de error de Excel.
Los chequeos generales registrados de 44 modelos devolvieron `PASS` u `OK`.
Banco de Bogotá, Banco Delta, ETESA y G.B. Group no tienen una celda de chequeo general registrada.

Estas pruebas verifican que los cálculos exportados coinciden con la copia fuente.
No validan de forma independiente los datos, supuestos, valoraciones ni el alcance de los chequeos de cada modelo.
Esta copia no es una auditoría financiera independiente ni una actualización de datos de mercado.

## Documentos públicos

Los textos panameños proceden de una extracción OCR. Los textos nuevos se convirtieron desde documentos HTML guardados.
Ambos procesos pueden contener errores. Revisa el documento original cuando una cifra esté en duda.
Los enlaces originales aparecen cuando se conservaron en la información de la fuente.
No se incluyen los PDF ni las imágenes originales.

## Cómo descargar y contribuir

La tabla de arriba enlaza cada modelo y sus documentos disponibles.
Para descargar todo, usa **Code → Download ZIP** en la página del repositorio.

Consulta [CONTRIBUTING.md](CONTRIBUTING.md).
Para informar un error, indica la empresa, hoja, celda, corrección propuesta y fuente con su página.
Para proponer un supuesto, explica el valor y su razón.
No cambies cifras publicadas para que cuadren, no reemplaces fórmulas con valores fijos y no debilites los chequeos.

## Licencia

Los modelos y los textos originales del proyecto usan [CC BY-SA 4.0](LICENSE).
La licencia exige atribución, identificación de cambios y la misma licencia para las adaptaciones, cuando corresponda.
El dashboard previsto tiene una [licencia MIT](dashboard/LICENSE) separada.
Los documentos fuente conservan los derechos de sus titulares.
