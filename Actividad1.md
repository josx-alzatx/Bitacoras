# Entrega de Strudel

Composición original en [Strudel](https://strudel.cc/) inspirada en el estilo de "Billie Jean" de Michael Jackson. Recrea el groove, la instrumentación y la tonalidad características del tema, sin reproducir su melodía, bajo o progresión de acordes originales.

## 🎧 Inspiración

El punto de partida fue "Billie Jean", uno de los temas más reconocibles del funk-disco de los 80. La idea no era copiar la canción, sino capturar su *esencia rítmica y de producción*.

Analice los puntos mas importantes para que se sienta similar como el bajo y la bateria.

## Evolución del proyecto

| Etapa | Descripción |
|---|---|
| *1. Base rítmica* | Bombo, caja, hi-hats, bajo con saltos de octava y un motivo synth simple, todo en un solo bloque con stack(). |
| *2. Estructura de canción* | Separación en verse (estrofa) y chorus (estribillo) usando const, y ensamblado con arrange() para definir el orden de las secciones. |
| *3. Punto de inflexión* | Pregunta clave: ¿qué tan parecido puede sonar al original sin infringir derechos de autor? |
| *4. Ajuste de tonalidad* | Migración a *F# menor* (tonalidad real del tema), rediseño del groove del bajo y adición de cuerdas staccato. |

## 🧩 Estructura técnica

\\\`javascript
setcpm(117/4)

const verse  = stack(...)   // bombo, caja, hi-hats, bajo, cuerdas, synth
const chorus = stack(...)   // versión más intensa: acordes sostenidos, bajo activo, melodía synth aguda

arrange(
  [4, verse],
  [4, chorus],
  [4, verse],
  [4, chorus]
)
\\\`

- *Tonalidad:* F# menor
- *Tempo:* ~117 BPM
- *Patrones clave:* bombo four-on-the-floor, caja en 2 y 4, bajo con saltos de octava, cuerdas staccato


---

