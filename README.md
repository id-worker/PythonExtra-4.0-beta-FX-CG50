# PythonExtra for Casio fx-CG50 — prebuilt `.g3a` (pe-0.4.0-beta)

Prebuilt **PythonExtra** add-in binaries for the **CASIO fx-CG50** graphing calculator, verified on real hardware with **OS 3.81** (`03.81.0202`).

PythonExtra is an extended **MicroPython** interpreter add-in built on the [`gint`](https://git.planet-casio.com/Lephenixnoir/gint) unikernel. **All rights belong to the upstream authors** — this repository only redistributes prebuilt binaries as a convenience for users.

## Files

| File | Size | Base | Description |
| :--- | ---: | :---: | :--- |
| **`PythonExtra.g3a`** | 313,100 B | Banner: `3.4.0; MicroPython 1ee197f on 2026-10-26`; beta 0.4 lineage indicated | Tested on a real fx-CG50 with OS 3.81; exact build provenance and toolchain have not been independently verified |
| **`PythonExtra-201778.g3a`** | 314,116 B | `pe-0.4.0-beta` + MicroPython `v1.25.0-preview` (CI build #201778, 2026-02-22) | Upstream CI build kept for reference / rollback |

The string `3.4.0` occurs in the banner, but is **not** the MicroPython
version. The examined source lineage uses a MicroPython 1.25.0 prerelease;
without the original build log this does not prove the exact source, compiler
or configuration used for the distributed binary.

## Installation

1. Connect the calculator via USB and press **`F1`** (*USB Flash*).
2. Copy the chosen `.g3a` to the root of the drive.
3. Eject safely — the icon appears in the Casio **Main Menu**.

## Upstream projects & license (MIT)

- **PythonExtra** — by **Lephenixnoir** and community maintainers **TheRainbowPhoenix**, **OffCamera-Civilman**, **SlyVTT** and contributors:
  - <https://git.planet-casio.com/Lephenixnoir/PythonExtra> (canonical upstream, release `pe-0.4.0-beta`)
  - <https://github.com/TheRainbowPhoenix/PythonExtra> · <https://github.com/OffCamera-Civilman/PythonExtra-CG50>
- **MicroPython** — by **Damien George** and the MicroPython team: <https://github.com/micropython/micropython> (MIT).
- **gint** — by **Lephenixnoir**: <https://git.planet-casio.com/Lephenixnoir/gint>.

The PythonExtra/MicroPython upstream license is MIT for the parts it covers; individual files and linked components can have additional notices. See [`THIRD_PARTY_NOTICES.md`](THIRD_PARTY_NOTICES.md) and the verbatim upstream [`LICENSE`](licenses/PythonExtra_upstream_LICENSE.txt). Exact binary build provenance and the completeness of binary dependency notices remain to be checked.

*CASIO, PRIZM and fx-CG50 are trademarks of CASIO COMPUTER CO., LTD. Unofficial third-party software; not affiliated with CASIO.*

---

## Русский

Предсобранные бинарники **PythonExtra** (полноценный Python-IDE-аддин на MicroPython) для Casio fx-CG50 — проверены на реальном калькуляторе с OS 3.81. Правообладатели — авторы апстрима (**Lephenixnoir**, **TheRainbowPhoenix**, **OffCamera-Civilman**, **SlyVTT**, **Damien George** и команда MicroPython); здесь только распространение готовых сборок под MIT (текст — в `THIRD_PARTY_NOTICES.md`).
