# XENO MARINE · Defensa de la Tierra

## ▶ [Jugar ahora: https://malbot042.github.io/alien/](https://malbot042.github.io/alien/)

Shooter retro en vista cenital en un único `index.html` (sin dependencias). Eres un marine que frena una invasión alienígena en un recorrido **infinito** de sectores: sobrevive a las oleadas y alcanza la escotilla de extracción de cada uno.

## Ambientes
Cada sector tiene su propio escenario, con mapa, obstáculos, peligros y clima distintos. El ciclo se repite cada vez más difícil:

| Sector | Ambiente | Mapa | Peligro | Ambiente |
|---|---|---|---|---|
| 1 | Base en ruinas | Edificios derruidos | Ácido | Ceniza |
| 2 | Selva | Jungla orgánica, árboles | Pantano tóxico | Lluvia y relámpagos |
| 3 | Búnker militar | Salas y pasillos | Residuo radiactivo | Alarma roja |
| 4 | Interior de la montaña | Cuevas y cristales | Lava | Polvo |
| 5 | Casco de la nave nodriza | Placas alienígenas, huevos | Ácido | Esporas |
| 6 | Entrañas de la nave | Salas orgánicas, más nidos | Ácido alienígena | Esporas |

Cada sector superado sube la dificultad: más enemigos, más resistentes y más rápidos. Los mapas se generan proceduralmente en cada partida.

## Dificultad
Se elige en la pantalla de título (clic, ←/→ o 1/2/3). Cada dificultad guarda su propio récord.

| | Fácil | Medio | Difícil |
|---|---|---|---|
| Daño recibido | 55 % | 100 % | 145 % |
| Vida de los enemigos | 75 % | 100 % | 130 % |
| Oleadas | Menos frecuentes | Normales | Más frecuentes |
| Granadas iniciales | 6 | 4 | 3 |
| Objetos que sueltan los enemigos | Más | Normal | Menos |
| Puntos | ×0,75 | ×1 | ×1,5 |

## Lectura del terreno
- **Muros y obstáculos** (árboles, roca, hormigón…): contorno negro y sombra proyectada; no se pueden atravesar.
- **Suelo peligroso** (ácido, pantano, radiación, lava): borde luminoso que parpadea y señales de aviso amarillas. Quita vida mientras lo pisas y aparece un aviso en pantalla.
- **Baba alienígena** (manchas moradas): solo decorativa, se puede pisar sin daño.

## Armas
- **Fusil M41** (principal): cargador de 40, se mejora hasta MK3 (doble y triple disparo) con los chips azules.
- **Lanzallamas**: daño continuo y quema a los enemigos; el combustible se recarga despacio o con bidones.
- **Granadas**: rebotan, destruyen cajas y nidos.

## Enemigos
Rastreros, escupidores de ácido, brutos que embisten y nidos que generan crías.

## Controles
| Tecla | Acción |
|---|---|
| WASD | Moverse |
| Ratón + clic izquierdo | Apuntar y disparar |
| Flechas | Apuntar y disparar (sin ratón, ideal con touchpad) |
| Clic derecho / G | Granada |
| 1 / 2 / Q / rueda | Cambiar arma |
| R | Recargar |
| P / Esc | Pausa |
| M | Sonido |

**Mando (gamepad):** stick izquierdo / cruceta mover · stick derecho apuntar · RT/RB disparar · LT/Y granada · B/LB cambiar arma · X recargar · Start pausa.

> **¿Usas touchpad?** Muchos portátiles desactivan el touchpad mientras se pulsan teclas ("rechazo de palma"), así que no podrás mover el puntero y caminar a la vez. Usa las **flechas** para apuntar/disparar, un ratón externo o un mando, o desactiva esa opción en los ajustes del touchpad del sistema.

## Jugar
- **Online (GitHub Pages):** https://malbot042.github.io/alien/
- **Local:** descarga el repositorio y abre `index.html` en el navegador.

> Para que la URL funcione, GitHub Pages debe estar activado en Settings → Pages → *Deploy from a branch* → rama `main`, carpeta `/ (root)`.

Pantalla CRT plana: scanlines, rejilla RGB, aberración cromática, bloom y ruido, sin curvatura.
