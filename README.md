# AdptCore.TestData

Real documentation files used by the manual end-to-end tests of [AdptCore](https://github.com/C-Sharp-V/AdptCore). The tests read them over HTTP, from a URL pinned to a commit, and compare their hash: the files must not be modified, and are stored without line ending conversion (see `.gitattributes`).

## Third-party files

### Microsoft.NETCore.App.Ref/10.0.13

`System.Collections.xml` is taken unmodified from `ref/net10.0` in the [Microsoft.NETCore.App.Ref 10.0.13](https://www.nuget.org/packages/Microsoft.NETCore.App.Ref/10.0.13) package.

It is licensed under the MIT license, Copyright (c) .NET Foundation and Contributors. The license file distributed with the package is included unmodified as `Microsoft.NETCore.App.Ref/10.0.13/LICENSE.TXT`.

## Other files

The other files of this repository are licensed under the terms of [LICENSE](LICENSE).
