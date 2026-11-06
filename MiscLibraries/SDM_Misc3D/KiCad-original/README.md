# Original KiCad model assets

This folder contains only 126 referenced original VRML models recovered from installed KiCad libraries: 125 from KiCad 9.0 and one from KiCad 7.0. Total model size: 10,631,998 bytes. The original `.3dshapes` subdirectory layout is retained. No whole standard library was copied.

Model files are byte-for-byte copies. All original copyright, author, license, and exception comments remain inside the files. Fifteen files carry GPL-3.0-or-later notices with an embedded exception; their individual headers govern those files. Other files carry CC-BY-SA-4.0 notices with the KiCad library exception, or are distributed under the KiCad library collection license. See the per-file license classifications and source hashes in [recovered-assets.json](../../validation/recovered-assets.json).

Included license documents:

- [KiCad library license and exception](LICENSE-KiCad.md), obtained from the [official KiCad model repository](https://raw.githubusercontent.com/KiCad/kicad-packages3D/master/LICENSE.md). The [9.0 release license](https://gitlab.com/kicad/libraries/kicad-packages3D/-/raw/9.0.0/LICENSE.md) describes the same library exception.
- [CC-BY-SA-4.0 legal text](CC-BY-SA-4.0.txt), obtained from [Creative Commons](https://creativecommons.org/licenses/by-sa/4.0/legalcode.txt).
- [GPL version 3 text](GPL-3.0.txt), obtained from the [official KiCad 9.0 source repository](https://raw.githubusercontent.com/KiCad/kicad/9.0/LICENSE.GPLv3).

Attribution: KiCad library contributors and the authors identified in each model, including kicad StepUp. Upstream model collection: [KiCad packages3D](https://gitlab.com/kicad/libraries/kicad-packages3D). Assets were copied unchanged on 2026-10-20; no model was converted to another format. The collection-license exception for electronic designs does not remove license requirements when redistributing the models as a library collection.

All 126 VRML files were checked for external texture, Inline, EXTERNPROTO, and URL dependencies; none were found. Footprint model offsets, rotations, and scale factors were retained. Use `${SDM_MISC_3D}/KiCad-original/<original-directory>/<original-filename>`.
