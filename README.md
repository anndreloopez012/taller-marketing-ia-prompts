# Taller de Marketing con IA · Biblioteca de prompts

Biblioteca de **18 prompts profesionales** del Taller de Marketing con IA (Clases 1 a 4), lista para copiar y pegar en cualquier asistente de IA del mercado. Cada prompt entrevista a la persona paso a paso, trabaja con la marca real de su empresa y entrega piezas de texto o de imagen listas para aprobar.

**Página publicada:** https://anndreloopez012.github.io/taller-marketing-ia-prompts/

---

## Para qué sirve

El taller deja a cada alumno herramientas para el día a día de su empresa. Esta página reúne los prompts de cada ejercicio en su versión corporativa:

- **Se copian con un clic.** Cada prompt tiene su botón «Copiar prompt».
- **Preguntan en lugar de pedir que se rellenen plantillas.** La IA hace un máximo de 3 preguntas por mensaje, propone opciones cuando la persona no sabe y muestra un resumen del brief antes de producir.
- **Trabajan con la marca.** El prompt 02 construye la *Ficha Maestra de Marca*; al pegarla en cualquier otro prompt, la IA se salta las preguntas de marca.
- **Sirven para texto e imagen.** Las piezas de contenido salen con su prompt de imagen alineado a la identidad visual de la marca.
- **Están pensados para empresa.** No inventan datos, marcan lo pendiente con `[POR CONFIRMAR]` y las afirmaciones delicadas con `[REVISIÓN LEGAL]`, y no piden datos personales de clientes.

Cuando un prompt hace lo que la empresa necesita, se convierte en **skill**. Cada ficha explica su objetivo y qué se gana al convertirlo.

## Contenido

| Clase | # | Prompt | Qué entrega |
|---|---|---|---|
| 1 · Análisis de marca | 01 | Optimizador de prompts | Convierte un pedido vago en un prompt profesional para texto o imagen |
| | 02 | Ficha Maestra de Marca | Contexto permanente de la empresa: voz, cliente, identidad visual y límites |
| | 03 | Diagnóstico de marca | Auditoría con evidencia y plan a 7, 30 y 90 días |
| | 04 | Buyer personas | 3 perfiles accionables con plan de validación |
| | 05 | Matriz competitiva | Comparación con evidencia y espacios para diferenciarse |
| 2 · Contenido | 06 | Banco de 40 ideas | Ideas por función, con gancho, CTA y visuales del Top 10 |
| | 07 | Taller de ganchos | 30 ganchos por intención y portadas |
| | 08 | Copies AIDA | 5 copies listos con su imagen |
| | 09 | Guiones de video corto | 5 guiones grabables con storyboard |
| | 10 | Calendario de 30 días | Mes ejecutable con métricas por semana |
| 3 · Campañas y ventas | 11 | Oferta y propuesta de valor | Oferta clara, creíble y mejorada sin bajar el precio |
| | 12 | Embudo de ventas | Etapas, CTA, métricas y plan de 4 semanas |
| | 13 | Laboratorio de anuncios | 10 anuncios por ángulo y plan de prueba |
| | 14 | Ventas por WhatsApp y DM | Secuencia completa y respuestas rápidas |
| | 15 | Campaña de 7 días | Campaña integrada con decisiones por métrica |
| 4 · Sistema diario | 16 | Multiplicador de contenido | 1 idea convertida en 7 piezas nativas por canal |
| | 17 | Análisis semanal de métricas | Hallazgos, patrones y pruebas para la próxima semana |
| | 18 | Biblioteca de prompts del equipo | Biblioteca con códigos, versiones y ruta a skills |

## Cómo usar un prompt

1. Abre la página y elige el prompt.
2. Pulsa **Copiar prompt** y pégalo en un chat nuevo de tu asistente de IA.
3. Responde las preguntas. Si ya tienes la Ficha Maestra de Marca, pégala cuando te la pida. Escribe `MODO RÁPIDO` para recibir todas las preguntas juntas.
4. Confirma el brief y revisa la «Revisión final» y los `[POR CONFIRMAR]` antes de publicar.

**Ruta recomendada en la empresa:** 02 → 03 → 04 → 05 → 06 a 10 → 11 a 15 → 16 a 18. El 01 se usa en cualquier momento.

## Estructura del repositorio

```
taller-marketing-ia-prompts/
├── index.html   # La página completa: estilos, prompts y botón de copiar en un solo archivo
├── .nojekyll    # Publica el sitio tal cual, sin procesarlo
└── README.md
```

La página no necesita compilación ni dependencias: es HTML, CSS y JavaScript en un solo archivo. Funciona en modo claro y oscuro y en celular.

## Ver la página en local

Abre `index.html` con doble clic en cualquier navegador, o sirve la carpeta:

```bash
python3 -m http.server 8000
```

y entra a http://localhost:8000.

## Publicación

El sitio se publica con **GitHub Pages** desde la rama `main`, carpeta raíz. Cada cambio que llega a `main` se publica solo en unos minutos.

## Cómo contribuir

El trabajo se hace por ramas y luego se sincroniza con `dev` y `main`:

```bash
git checkout dev
git checkout -b feat/nombre-del-cambio
# ...cambios en index.html o README.md...
git commit -m "feat: describe el cambio"
git checkout dev  && git merge --no-ff feat/nombre-del-cambio
git checkout main && git merge --no-ff dev
git push origin dev main
```

Convención de ramas: `feat/…` para contenido nuevo (por ejemplo, una clase nueva) y `fix/…` para correcciones.

## Autor

Andre López · Taller de Marketing con IA
