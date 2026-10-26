# Third-Party Notices — PythonExtra prebuilt binaries

The binaries in this repository (`PythonExtra.g3a`, `PythonExtra-201778.g3a`) are **prebuilt distributions** of open-source upstream projects:

## PythonExtra

- **Project:** PythonExtra — a MicroPython add-in built on `gint`, by **Lephenixnoir** and community maintainers **TheRainbowPhoenix**, **OffCamera-Civilman**, **SlyVTT** and contributors.
- **Upstream:** <https://git.planet-casio.com/Lephenixnoir/PythonExtra> (`pe-0.4.0-beta`) · mirrors: <https://github.com/TheRainbowPhoenix/PythonExtra> · <https://github.com/OffCamera-Civilman/PythonExtra-CG50>
- **License:** MIT.

## MicroPython

- **Project:** MicroPython — Python 3 implementation embedded in PythonExtra, by **Damien George** and the MicroPython team.
- **Upstream:** <https://github.com/micropython/micropython>
- **License:** MIT.

### MIT License (reproduced, governs the above projects)

```text
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```

### Build identification strings inside the binaries

- `PythonExtra.g3a` → `3.4.0; MicroPython 1ee197f on 2026-10-26` (base `pe-0.4.0-beta`, `gint@dev` Oct 2026, rebuilt for OS 3.81).
- `PythonExtra-201778.g3a` → `3.4.0; MicroPython v1.25.0-preview.602.gfca9b039f on 2026-02-22` (upstream CI build #201778).

> **Redistribution summary (MIT):** the binaries may be redistributed provided this attribution and the MIT permission notice are kept alongside them.
