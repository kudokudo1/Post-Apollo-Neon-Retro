✦︎✦︎✦︎ Meta Apollo Logos //

# ✮˙๋࣭⭑ POST-APOLLO // NEON RETRO

![](BUILD/assets/design/chassis/focus-rail.svg)

> **STATE //** active \~\~ **VIEW //** compatibility theme

> **NeonRetro is the Post-Apollo compatibility theme for GTK and related desktop toolkits.**

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
