# 🌙 Lunacia

**El reino bajo la Miasma.** Servidor de Minecraft con mods — aventura, magia y
reliquias en un mundo donde la superficie te enferma.

```
IP: 194.126.174.194:50203     ·     Minecraft 1.21.1 (NeoForge)
```

---

## El mundo

Vivimos en Lunacia, un reino en decadencia. La **Miasma** —una niebla extraña que
provoca enfermedad progresiva— cubre la superficie, y **solo la superficie**.

Por eso la civilización vive bajo tierra. Subir es una **expedición**: te equipas
contra la niebla, aguantas lo que puedas, saqueas lo que encuentres y vuelves
antes de que tu cuerpo ceda. Porque arriba, dentro de la Miasma, es donde nacen
las **reliquias**: artefactos de poder variable que desafían a la física. O no.

---

## Cómo entrar

El servidor usa mods, así que **el launcher normal de Minecraft no sirve**. Hay
que instalar el modpack una vez. Son 5 minutos.

### Opción A — Prism Launcher (recomendada, funciona con cualquier cuenta)

1. Instala [Prism Launcher](https://prismlauncher.org) (gratis).
2. Descarga **[`Lunacia.mrpack`](../../releases/latest)** de la última release.
3. En Prism: `Add Instance` → `Import` → elige el archivo → `OK`.
4. Pulsa **Play**. Lunacia ya aparece en tu lista de servidores.

### Opción B — CurseForge (requiere cuenta de Microsoft)

1. Descarga **[`Lunacia-CurseForge.zip`](../../releases/latest)** de la última release.
2. En CurseForge: `Crear perfil personalizado` → pestaña `Importar` → elige el zip.
3. Pulsa **Jugar**.

> **Nota:** CurseForge exige cuenta de Microsoft. Si juegas sin cuenta premium,
> usa Prism con el `.mrpack`.

### Primera vez dentro

```
/register <contraseña> <contraseña>      ← solo la primera vez
/login <contraseña>                      ← las siguientes
```

---

## Lo que te vas a encontrar

### La Miasma

En cuanto salgas a la superficie empezarás a acumularla, y verás una barra sobre
tu barra de acción:

| Exposición | Qué te pasa |
|---|---|
| **25%** | Toses: la niebla se cierra un poco y **empiezas a oler** |
| **50%** | Enfermas: ves la mitad, hueles el doble, hambre |
| **75%** | Grave: casi no ves, lentitud |
| **90%** | Agonía: doce bloques de visión, debilidad, y te huelen desde muy lejos |

La Miasma **no te mata**. Te ciega, te quita reflejos y te hace oler — y eso es
lo que te pone en la boca de los **Remanentes**, las cosas que viven arriba y
cazan por el olfato. La Miasma no te mata: te entrega.

**Cómo librarte:** baja por debajo de la altura 50 y el subsuelo te purga. Bajo
techo, la exposición se congela. Y **morir no te cura** — la enfermedad se queda
contigo. Solo bajar funciona.

### Los Remanentes

Lo que vive arriba. Cazan por el olor y el ruido, estudian antes de atacar, cazan en manada
y **aprenden de ti**: por dónde sales, a qué hora, dónde has muerto. Desde la 0.10 **te
esperan agazapados junto a tu boca a tu hora**, se acercan por donde no los ves y por
detrás de tus antorchas, y **se cansan**: a uno solo se le puede correr quince segundos;
a tres no, porque se relevan.

### Los goblins

Lo que vive abajo, en las minas abandonadas y a la sombra de las aldeas subterráneas.
Pálidos, pequeños, débiles — y listos. **Minan y talan** lo que hay, lo guardan en el
**cofre de su campamento**, su artesano **fabrica herramientas** (piedra, luego hierro) que
verás en sus manos, y **construyen** su campamento con lo que sacan. Pelean en escuadra
después de contarte: si vas solo y flojo, van; si les matas a uno o vas armado, **se
retiran, llaman y vuelven más**. Abren puertas, ponen antorchas (su luz delata un
campamento cerca) y **nunca suben a la superficie**. No rompen nada tuyo: solo lo natural
o de mina, y jamás dentro de un reino reclamado.

### Máscaras

Tres niveles, cada una filtra más. Basta con llevarla en la mochila (cuenta la
mejor que tengas). Su **durabilidad es el filtro**, y solo se gasta cuando de
verdad te está protegiendo, así que no malgastas nada bajo tierra.

| Máscara | Filtra | Se craftea con |
|---|---|---|
| De tela | 50% | cuerda + cuero + lana |
| De cobre | 75% | máscara de tela + cobre + hierro |
| De oro lunar | 90% | máscara de cobre + oro + **esquirla lunar** + amatista |

La **esquirla lunar** solo se consigue arriba: para protegerte de la Miasma
tienes que exponerte a ella.

---

## Comandos útiles

| Comando | Qué hace |
|---|---|
| `/miasma` | Ver tu nivel de exposición |
| `/k` | KingdomsX — reinos, territorios y guerras |
| `/co inspect` | CoreProtect — ver quién puso o rompió un bloque |

---

## Problemas típicos

| Síntoma | Solución |
|---|---|
| `Connection refused` | El servidor está reiniciando; prueba en un minuto |
| `Channel of mod "Lunacia" failed to connect` | Tu modpack está desactualizado: reimporta la última release |
| No te puedes mover al entrar | Te falta hacer `/login` |
| CurseForge dice "0 mods" | Es normal: los mods van dentro del pack, no de su catálogo. Se cargan igual |

---

## Mods incluidos

Todos los créditos a sus autores:

- [Relics](https://modrinth.com/mod/relics-mod) · [Artifacts](https://modrinth.com/mod/artifacts) ·
  [Reliquified Artifacts](https://modrinth.com/mod/reliquified-artifacts) — reliquias y artefactos
- [Curios API](https://modrinth.com/mod/curios) · [GeckoLib](https://modrinth.com/mod/geckolib) ·
  [OctoLib](https://modrinth.com/mod/shatterbyte-lib) · [Architectury API](https://modrinth.com/mod/architectury-api) — librerías
- [The Roads More Travelled](https://modrinth.com/mod/the-roads-more-travelled) — los caminos se desgastan por donde pasa la gente (y los Remanentes)
- [Serene Seasons](https://modrinth.com/mod/serene-seasons) · [GlitchCore](https://modrinth.com/mod/glitchcore) — estaciones: el año empieza en otoño; bajo la altura 48 los cultivos crecen siempre
- [Corpse](https://modrinth.com/mod/corpse) — al morir dejas un cuerpo con tus cosas, y se queda ahí hasta que vuelvas (o hasta que alguien lo encuentre)
- [Sophisticated Backpacks](https://modrinth.com/mod/sophisticated-backpacks) · [Sophisticated Core](https://modrinth.com/mod/sophisticated-core) — mochilas
- [Player Animator](https://modrinth.com/mod/playeranimator) — librería de animaciones
- [Sodium](https://modrinth.com/mod/sodium) · [Sodium Dynamic Lights](https://modrinth.com/mod/sodium-dynamic-lights) · [Sodium Options API](https://modrinth.com/mod/sodium-options-api) ·
  [Lithium](https://modrinth.com/mod/lithium) · [FerriteCore](https://modrinth.com/mod/ferrite-core) · [ModernFix](https://modrinth.com/mod/modernfix) ·
  [Entity Culling](https://modrinth.com/mod/entityculling) · [ImmediatelyFast](https://modrinth.com/mod/immediatelyfast) · [Distant Horizons](https://modrinth.com/mod/distanthorizons) — rendimiento y distancia de visión
- [AmbientSounds](https://modrinth.com/mod/ambientsounds) · [CreativeCore](https://modrinth.com/mod/creativecore) ·
  [Sound Physics Remastered](https://modrinth.com/mod/sound-physics-remastered) — sonido y ambiente
- [Goblin Traders](https://www.curseforge.com/minecraft/mc-mods/goblin-traders) · [Framework](https://www.curseforge.com/minecraft/mc-mods/framework) — goblins comerciantes en las cuevas
- [YUNG's Cave Biomes](https://modrinth.com/mod/yungs-cave-biomes) · [YUNG's API](https://modrinth.com/mod/yungs-api) · [TerraBlender](https://modrinth.com/mod/terrablender) ·
  [YUNG's Better Mineshafts](https://modrinth.com/mod/yungs-better-mineshafts) · [Better Dungeons](https://modrinth.com/mod/yungs-better-dungeons) · [Better Strongholds](https://modrinth.com/mod/yungs-better-strongholds) ·
  [Underground Villages](https://modrinth.com/mod/underground-villages) — el subsuelo: biomas, minas, mazmorras, fortalezas y aldeas bajo tierra
- **Lunacia** — el mod propio del servidor (la ficha, la Miasma, los Remanentes y todo lo que viene después)
