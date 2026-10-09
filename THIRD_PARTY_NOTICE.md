# THIRD-PARTY NOTICE // OOMOX / NUMIX THEME LINEAGE

This repository contains a Post-Apollo compatibility theme built from a pre-existing Oomox/Numix theme structure and assets.

It is **not** wholly original Post-Apollo theme source.

## INHERITED THEME MATERIAL

The repository contains a large toolkit/theme tree covering GTK, Cinnamon, Metacity, Openbox, Unity, XFWM, and related assets.

Several files identify their lineage directly. For example:

- `openbox-3/themerc` identifies itself as **"Oomox (Numix fork) Openbox theme"**, credits **Satyajit Sahoo**, and states **GPL-3.0+**
- `xfwm4/themerc` identifies itself as **"Numix xfwm4 theme"**, credits **Satyajit Sahoo**, and states **GPL-3.0+**
- `gtk-3.0/gtk.css` imports Numix GTK resources
- the package name and structure identify the live theme as `oomox-NeonRetro`

Relevant upstream projects include:

**Numix GTK Theme**  
https://github.com/numixproject/numix-gtk-theme  
License: **GPL-3.0**

**Oomox / Themix theme tooling and generated theme ecosystem**  
historically used to generate and transform Numix-derived themes.

Because the Oomox/Themix lineage spans generated output and historical tooling, this notice relies on the license statements embedded in the inherited theme files themselves rather than assigning a new license to the tooling.

## POST-APOLLO MODIFICATIONS

Post-Apollo changes include the Neon Retro palette, color substitutions, visual adjustments, compatibility tuning, packaging choices, and the surrounding Post-Apollo documentation/identity layer.

Those modifications do not erase the upstream provenance of the underlying theme files.

## LICENSE BOUNDARY

Files derived from Numix/Oomox material that carry or inherit GPL terms remain under the applicable **GPL-3.0 / GPL-3.0+** terms.

The repository's Post-Apollo PolyForm Noncommercial notice **does not apply to those GPL-covered files** and must not be read as adding a noncommercial restriction to rights granted by the GPL.

Original Post-Apollo documentation, branding, banners, and independently authored material remain under the licenses stated in `LICENSE.md`, where legally applicable.

## PROVENANCE RULE

Keep upstream author credits, embedded license headers, and this notice intact when redistributing the inherited theme material.

Future cleanup may identify more precise file-by-file origins. Until then, inherited toolkit theme files should be treated conservatively as upstream-derived rather than assumed to be original Post-Apollo work.
