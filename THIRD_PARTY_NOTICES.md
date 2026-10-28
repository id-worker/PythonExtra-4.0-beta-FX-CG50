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

### MIT permission text

The exact upstream license, including the original copyright line and the
third-party-components note, is preserved separately in
[`licenses/PythonExtra_upstream_LICENSE.txt`](licenses/PythonExtra_upstream_LICENSE.txt).
Individual source files can contain additional notices.

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

- `PythonExtra.g3a` → `3.4.0; MicroPython 1ee197f on 2026-10-26`. Source comparisons indicate beta 0.4 lineage; the original build log, compiler and exact configuration are not available.
- `PythonExtra-201778.g3a` → `3.4.0; MicroPython v1.25.0-preview.602.gfca9b039f on 2026-02-22` (upstream CI build #201778).

> **Redistribution review:** retain the applicable upstream copyright and permission notices, and verify the notices/terms of actually linked third-party components. The incomplete build provenance prevents certifying that this list is exhaustive.
