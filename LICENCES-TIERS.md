# Licences des composants tiers

Le jeu est construit avec Unreal Engine 5.8, sous le
[contrat de licence d'Unreal Engine](https://www.unrealengine.com/eula/unreal).

CraftWorld uses the Unreal® Engine. Unreal® is a trademark or registered trademark
of Epic Games, Inc. in the United States of America and elsewhere.
Unreal® Engine, Copyright 1998-2026, Epic Games, Inc. All rights reserved.

Le moteur livre aussi des bibliothèques d'autres auteurs, sans modification :

| Fichier ou partie du jeu | Bibliothèque | Licence | Droits |
|---|---|---|---|
| `Engine\Binaries\ThirdParty\Ogg` | libogg | BSD 3 clauses | Copyright © 2002, Xiph.org Foundation |
| `Engine\Binaries\ThirdParty\Vorbis` | libvorbis, libvorbisfile | BSD 3 clauses | Copyright © 2002-2020 Xiph.org Foundation |
| `CraftWorld\Binaries\Win64\tbb12.dll`, `tbbmalloc.dll` | oneTBB | Apache 2.0 | Copyright © 2005-2023 Intel Corporation |
| `Engine\Binaries\ThirdParty\MsQuic` | MsQuic | MIT | Copyright © Microsoft Corporation |
| `Engine\Binaries\ThirdParty\Windows`, `DbgHelp` | XAudio2, DbgHelp | Composants redistribuables de Microsoft | © Microsoft Corporation |
| `Engine\Binaries\ThirdParty\NVIDIA` | NVIDIA Nsight Aftermath | Licence du SDK NVIDIA | © NVIDIA Corporation |
| Intégré au moteur | FreeType | FreeType License | Portions of this software are copyright © The FreeType Project (https://freetype.org). All rights reserved. |
| Intégré au moteur | zlib, libpng, ICU, HarfBuzz et autres | Leurs propres licences, distribuées par Epic Games avec le moteur | Leurs auteurs respectifs |

## Licence BSD de libogg et libvorbis

```
Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions
are met:

- Redistributions of source code must retain the above copyright
notice, this list of conditions and the following disclaimer.

- Redistributions in binary form must reproduce the above copyright
notice, this list of conditions and the following disclaimer in the
documentation and/or other materials provided with the distribution.

- Neither the name of the Xiph.org Foundation nor the names of its
contributors may be used to endorse or promote products derived from
this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
``AS IS'' AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR
A PARTICULAR PURPOSE ARE DISCLAIMED.  IN NO EVENT SHALL THE FOUNDATION
OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT
LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE,
DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY
THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
```

## Licence MIT de MsQuic

```
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
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## oneTBB

oneTBB est distribué sous la licence Apache 2.0 :
https://www.apache.org/licenses/LICENSE-2.0
