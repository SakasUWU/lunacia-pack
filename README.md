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
| **30%** | Empiezas a toser: lentitud y hambre |
| **60%** | Enfermas: veneno y debilidad |
| **90%** | Agonizas: marchitamiento y oscuridad |

La niebla se cierra sobre ti según avanza, hasta dejarte con unos pocos bloques
de visión.

**Cómo librarte:** baja por debajo de la altura 50 y el subsuelo te purga. Bajo
techo, la exposición se congela. Y **morir no te cura** — la enfermedad se queda
contigo. Solo bajar funciona.

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
- **Lunacia** — el mod propio del servidor (la Miasma y todo lo que viene después)
