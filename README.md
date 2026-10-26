# PythonExtra for Casio fx-CG50 — prebuilt `.g3a` (pe-0.4.0-beta)

Prebuilt **PythonExtra** add-in binaries for the **CASIO fx-CG50** graphing calculator, verified on real hardware with **OS 3.81** (`03.81.0202`).

PythonExtra is an extended **MicroPython** interpreter add-in built on the [`gint`](https://git.planet-casio.com/Lephenixnoir/gint) unikernel. **All rights belong to the upstream authors** — this repository only redistributes prebuilt binaries as a convenience for users.

## Files

| File | Size | Base | Description |
| :--- | ---: | :---: | :--- |
| **`PythonExtra.g3a`** | 313,100 B | `pe-0.4.0-beta` + MicroPython `3.4.0` (2026-10-26) + `gint@dev` (Oct 2026) | **Recommended** — clean Release rebuilt from source for OS 3.81, verified on real fx-CG50 |
| **`PythonExtra-201778.g3a`** | 314,116 B | `pe-0.4.0-beta` + MicroPython `v1.25.0-preview` (CI build #201778, 2026-02-22) | Upstream CI build kept for reference / rollback |

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

Both projects are licensed under the **MIT License** — see [`THIRD_PARTY_NOTICES.md`](THIRD_PARTY_NOTICES.md) for the reproduced permission notice and full attribution. Keep this notice alongside the binaries when redistributing.

*CASIO, PRIZM and fx-CG50 are trademarks of CASIO COMPUTER CO., LTD. Unofficial third-party software; not affiliated with CASIO.*

---

## Русский

Предсобранные бинарники **PythonExtra** (полноценный Python-IDE-аддин на MicroPython) для Casio fx-CG50 — проверены на реальном калькуляторе с OS 3.81. Правообладатели — авторы апстрима (**Lephenixnoir**, **TheRainbowPhoenix**, **OffCamera-Civilman**, **SlyVTT**, **Damien George** и команда MicroPython); здесь только распространение готовых сборок под MIT (текст — в `THIRD_PARTY_NOTICES.md`).
