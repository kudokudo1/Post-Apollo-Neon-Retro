✦︎✦︎✦︎ Meta Apollo Logos //

# ✮˙๋࣭⭑ POST-APOLLO // NEON RETRO

![](BUILD/assets/design/chassis/focus-rail.svg)

![Post-Apollo // Neon Retro](./BUILD/assets/design/neon-retro-banner.svg)

> **STATE //** active \~\~ **VIEW //** compatibility theme

The visual compatibility layer of the Post-Apollo Family — shaping the relationship between operator, applications, visual language, continuity, environment, and expression, bringing third-party software into a shared visual identity without requiring each application to abandon its native interface.

**FAMILY //** [META APOLLO LOGOS](https://github.com/kudokudo1/Meta-Apollo-Logos) · [DEV EXP](https://github.com/kudokudo1/The-Post-Apollo-Dev-Exp) · [FOREST](https://github.com/kudokudo1/The-Post-Apollo-Forest-Project) · [POST-APOLLO PROJECT](https://github.com/kudokudo1/The-Post-Apollo-Project)

### 🧭 MAP // REPOSITORY

![](BUILD/assets/design/chassis/nav-rail.svg)

// [🧭 ATLAS](./ATLAS/) \~\~ // [✮˙๋࣭⭑ MODEL](./MODEL/) \~\~ // [🖨 BUILD](./BUILD/) \~\~ // [⚒ DEV](./DEV/) \~\~ // [🖳 OPERATE](./OPERATE/) \~\~ // [⊹ ࣪ℼ˖ EVIDENCE](./EVIDENCE/) \~\~ // [࣪⋅˚🕮‧₊˚ ARCHIVE](./ARCHIVE/)

---

### ★⋆˙ CORE // COMPATIBILITY LAYER

NeonRetro keeps toolkit-native directories because those paths are part of the theme package itself. Meta Apollo rooms describe the package without flattening it into a new filesystem.

---

NeonRetro compatibility theme used by the Post-Apollo desktop.

This repository preserves the current known-working theme package exactly as
used on the system.

## Role

NeonRetro is not the primary Post-Apollo UI layer.

Post-Apollo's custom shell and purpose-built interfaces are rendered through
Quickshell/QML where full visual control is desired.

NeonRetro exists as a reusable compatibility theme for third-party
applications that retain their native GTK or desktop-toolkit interface.

Current real-world use includes Brave and other applications that benefit from
matching the Post-Apollo visual language without being rebuilt as custom
Quickshell interfaces.

## Included theme targets

The current package contains support/assets for:

- GTK 2
- GTK 3
- GTK 3.20
- GTK 4
- Cinnamon
- Metacity
- Openbox
- Unity
- XFWM

Some of these targets may be generated or legacy compatibility outputs.

The initial Git baseline intentionally preserves all of them unchanged.

## Upstream provenance

Neon Retro is built from an **Oomox/Numix-derived theme package**, then recolored and adapted into the Post-Apollo visual language. Large parts of the toolkit theme tree are inherited material rather than wholly original Post-Apollo source.

Some inherited files explicitly carry **GPL-3.0+** terms, which remain in force.

See [THIRD_PARTY_NOTICE.md](./THIRD_PARTY_NOTICE.md) for the upstream lineage and licensing boundary.

## Theme location

Current live installation:

    ~/.themes/oomox-NeonRetro

## Development policy

Preserve first, clean later.

Future commits may:

- identify generated versus authored files
- reduce legacy desktop-environment outputs
- improve GTK4 support
- extract shared Post-Apollo design tokens
- make NeonRetro more reusable across third-party applications
