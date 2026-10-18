# 🎮 Sala de Repeticiones · StarCraft II

**Tu coach personal de StarCraft II, en español.** Lee tus repeticiones y te dice qué cambiar en la próxima partida.

### ▶ [Abrir la app](https://crism0r.github.io/sala-sc2/) · 📘 [Manual de uso (PDF)](Manual_Sala_de_Repeticiones.pdf)

Funciona en **Chrome o Edge**, sin cuenta y sin internet. Tus partidas nunca salen de tu computador.

---

## ¿Qué hace?

| | |
|---|---|
| 🎯 **Recomendaciones** | Tus errores ordenados por prioridad: qué pasó, por qué importa y qué practicar. |
| ⚔️ **Estrategia** | Cómo jugó tu rival, el momento decisivo y qué unidades usar contra cada una de las suyas. |
| 📈 **Ejército en el tiempo** | Tus unidades y las del rival minuto a minuto, con cada ataque marcado. |
| 🏗️ **Tu build vs profesionales** | Tu apertura paso a paso contra builds de jugadores pro. |
| 🏆 **Progreso e historial** | Mapas mejores y peores, errores repetidos y tu camino por las ligas. |

---

## 🌱 ¿Es para mí?

Sí, si estás empezando o quieres subir de liga. La app no te llena de números: te dice **qué 3 cosas trabajar** en tu próxima partida, en español y con palabras simples.

- **Juegas Zerg:** tienes todo, incluidos consejos de creep, inyecciones y reinas, y builds de profesionales para copiar.
- **Juegas Terran o Protoss:** también te sirve (resumen, recomendaciones, estrategia, gráficos e historial), pero aún no tiene builds pro ni consejos propios de tu raza.

**Consejo para empezar:** después de cada partida mira solo **Resumen** y **Recomendaciones**. Trabaja la prioridad número 1 durante varias partidas antes de pasar a la siguiente.

---

## 🔌 Cómo conectar tu carpeta de repeticiones

Hazlo **una sola vez**. Desde ahí la app analiza sola cada partida nueva.

**1. Abre la app** en **Chrome o Edge**: https://crism0r.github.io/sala-sc2/
Espera a que arriba diga **Lector listo** (unos 3 segundos).

**2. Haz clic en `Conectar carpeta`.**

**3. Busca tu carpeta de repeticiones.** StarCraft II la guarda aquí:

```
Documentos\StarCraft II\Accounts\<número>\<región-S2-número>\Replays\Multiplayer
```

Ejemplo: `C:\Users\TuUsuario\Documents\StarCraft II\Accounts\12345678\1-S2-1-987654\Replays\Multiplayer`

- Entra **hasta la carpeta `Multiplayer`** y pulsa **Seleccionar carpeta**.
- Si tienes varias cuentas o regiones, elige la de tu cuenta de ladder.
- Truco: en StarCraft II ve a **Repeticiones**, pulsa **Mostrar carpeta** y copia la ruta de la barra del Explorador.

**4. Da permiso.** Cuando Chrome pregunte, elige **Ver archivos** / **Permitir**.

**5. Listo.** La app revisa todas tus partidas y muestra *Carpeta conectada*. Deja marcado **Revisar sola cada 30 s**.

### Cada vez que juegues
- **Con la pestaña abierta:** al terminar la partida, el análisis aparece solo en segundos.
- **Si la cerraste:** al abrirla de nuevo, pulsa **Dar permiso a la carpeta** (Chrome lo pide por seguridad) y analiza todas las partidas que jugaste mientras estaba cerrada.

> **¿Sin conectar carpeta?** También puedes usar **Elegir repeticiones** y seleccionar archivos `.SC2Replay` a mano.

---

## ❓ Problemas comunes

| Si pasa esto… | …haz esto |
|---|---|
| No aparece **Conectar carpeta** o no hace nada | Usa Chrome o Edge; Firefox y Safari no pueden leer carpetas. |
| Conecté la carpeta pero hay 0 repeticiones | Entra hasta la carpeta **Multiplayer** y selecciona esa. |
| Una partida dice *No analizable* | Es contra la IA, de más de 2 jugadores o de una versión muy antigua. |
| Me muestra como si fuera el rival | Usa **Analizar como** y elige tu nombre. |
| Cambié de PC o navegador y no está mi historial | En el anterior: **Historial → Guardar respaldo**. En el nuevo: **Cargar respaldo**. |

---

## 🔒 Privacidad

Tus repeticiones e historial **nunca salen de tu computador**: la app no tiene servidor, no pide cuenta y no envía datos. Cada persona que usa el link ve solo sus propias partidas.

## ⭐ ¿Te sirve?

Deja una **estrella** en este repositorio o cuéntame en **Issues** qué mejorarías.

## Créditos

- [s2protocol](https://github.com/Blizzard/s2protocol) (Blizzard, MIT) y mpyq (BSD): lectura de repeticiones.
- [Pyodide](https://pyodide.org) (MPL 2.0): Python en el navegador.
- [d3](https://d3js.org) (ISC): gráficos.
- Fuentes Saira Condensed, Source Sans 3 y JetBrains Mono (OFL).
- Builds de profesionales: [Spawning Tool](https://lotv.spawningtool.com) y [Liquipedia](https://liquipedia.net/starcraft2).

StarCraft II, sus unidades, estructuras e insignias de liga son © Blizzard Entertainment. Herramienta gratuita y no oficial, sin relación con Blizzard.
