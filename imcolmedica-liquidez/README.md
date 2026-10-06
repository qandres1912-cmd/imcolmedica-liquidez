# Herramienta de liquidez y flujo de caja — Imcolmedica S.A.

Aplicación web desarrollada para el trabajo de grado sobre la gestión del capital de trabajo, la liquidez y el flujo de caja de Imcolmedica S.A. (años 2024 y 2025).

La herramienta es un único archivo (`index.html`): no requiere instalación, servidor ni base de datos. Funciona en cualquier navegador moderno.

## Qué hace

| Pestaña | Objetivo específico |
|---|---|
| Datos | Captura de estados de resultados, balance y flujo de efectivo 2024-2025, con verificaciones de coherencia |
| 1 · Horizontal y vertical | Análisis horizontal y vertical de los tres estados |
| 2 · Impulsores | Márgenes, efecto volumen y efecto margen en la utilidad bruta, puente de la utilidad neta |
| 3 · Liquidez y ciclo de efectivo | Razón corriente, prueba ácida, KTNO, DSO, DIO, DPO y ciclo de conversión de efectivo |
| 4 · Riesgos | Semáforo de liquidez, cartera y endeudamiento de corto plazo |
| 5 · Mejoramiento y valoración | Escenario actual vs. mejorado, caja liberada, WACC, flujo de caja libre a 5 años, valor intrínseco y sensibilidad |

Todas las cifras se manejan en millones de pesos colombianos (MM COP).

## Cómo usarla

1. Abra `index.html` en el navegador (o la página publicada en GitHub Pages).
2. En la pestaña **Datos**, pulse «Vaciar todo» e ingrese los estados financieros reales (a mano, o pegando una tabla `Concepto; 2024; 2025` con «Importar datos»).
3. Revise que las verificaciones de coherencia no muestren alertas.
4. Recorra las pestañas 1 a 5. En la pestaña 5 ajuste las metas y los supuestos de valoración.

## Privacidad de los datos

Las cifras que se ingresan se guardan únicamente en el navegador de quien usa la página (almacenamiento local). **No se envían a ningún servidor ni se guardan en este repositorio.** No suba a este repositorio los estados financieros ni documentos del trabajo de grado: el archivo `.gitignore` ya excluye los formatos más comunes.

## Aviso importante

Al abrirla por primera vez, la herramienta trae **datos de demostración** ilustrativos que no corresponden a la empresa. Deben reemplazarse por los estados financieros reales antes de interpretar cualquier resultado. Los supuestos de valoración (beta, prima de mercado, riesgo país, metas de días, crecimiento) son valores de partida y deben sustentarse con fuentes citables.

## Publicación

Este repositorio está preparado para publicarse con GitHub Pages (rama `main`, carpeta raíz).

## Autor

Andrés Quintero Villegas — Trabajo de grado.

## Licencia

Por definir por el autor.
