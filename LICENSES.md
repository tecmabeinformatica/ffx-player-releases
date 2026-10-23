# Licenças e avisos legais do FFX Player

## FFX Player

Copyright (c) 2026 Tecmabe Informática. Todos os direitos reservados.

O FFX Player e seu código próprio são software proprietário. O código-fonte não
é distribuído publicamente. O aviso completo do aplicativo está disponível em
[`licenses/FFXPLAYER-LICENSE.txt`](licenses/FFXPLAYER-LICENSE.txt).

As licenças abaixo aplicam-se somente aos respectivos componentes de terceiros
e não se estendem ao código próprio do FFX Player.

## libmpv e FFmpeg

O FFX Player utiliza `libmpv-2.dll` por vinculação dinâmica. A DLL permanece
separada e pode ser substituída pelo usuário por uma versão compatível.

- Build: `mpv-dev-lgpl-x86_64-20260829-git-e8673660ab.7z`
- Build original: <https://github.com/zhongfly/mpv-winbuild/releases/tag/2026-08-29-e8673660ab>
- Revisão mpv: `e8673660ab7ee5d4ea8f93e4bf3a6e170ab2a19a`
- Revisão FFmpeg: `1ae40482188283a7f955d001abb08c5d865cdae0`
- SHA-256 do pacote original: `78260166265FBC09B3BEE75EE3464EB0F6BBAA8ECD172786E33C22BBF8A3CB47`
- SHA-256 da DLL: `92CA673870C425E0A539B854231F75E71BF7FB6E72FE86A6CE315CDF57DC0F16`
- Variante declarada pelo distribuidor: libmpv LGPLv2.1+ com FFmpeg LGPLv3.

Fontes correspondentes:

- [mpv na revisão utilizada](https://github.com/mpv-player/mpv/archive/e8673660ab7ee5d4ea8f93e4bf3a6e170ab2a19a.tar.gz)
- [FFmpeg na revisão utilizada](https://github.com/FFmpeg/FFmpeg/archive/1ae40482188283a7f955d001abb08c5d865cdae0.tar.gz)
- [Receitas de compilação da build distribuída](https://github.com/zhongfly/mpv-winbuild/archive/refs/tags/2026-08-29-e8673660ab.tar.gz)

Textos integrais: [LGPL 2.1](licenses/LGPL-2.1.txt) e
[LGPL 3.0](licenses/LGPL-3.0.txt).

O FFX Player não impõe restrições à engenharia reversa necessária para depurar
modificações realizadas nas bibliotecas LGPL.

## Microsoft .NET

O instalador contém o runtime autônomo Microsoft .NET 8.0.30 e WPF 8.0.30 para
Windows x64. Os pacotes são distribuídos sob a Licença MIT e acompanhados pelos
avisos de seus componentes de terceiros.

- [Código-fonte do .NET Runtime 8.0.30](https://github.com/dotnet/runtime/tree/v8.0.30)
- [Código-fonte do WPF 8.0.30](https://github.com/dotnet/wpf/tree/v8.0.30)
- [Licença do .NET Runtime](licenses/DOTNET-LICENSE.txt)
- [Avisos de terceiros do .NET Runtime](licenses/DOTNET-THIRD-PARTY-NOTICES.txt)
- [Licença do WPF](licenses/DOTNET-WPF-LICENSE.txt)
- [Avisos de terceiros do WPF](licenses/DOTNET-WPF-THIRD-PARTY-NOTICES.txt)

Este documento é informativo. Em caso de divergência, prevalecem os textos
integrais das licenças correspondentes.
