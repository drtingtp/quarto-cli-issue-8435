Bug reproduction repo for https://github.com/quarto-dev/quarto-cli/issues/8435

Quarto CLI version: quarto-1.4.549-win
OS: Windows 10 x64

Tests:

|filter|expected|observed|assert|
|-|-|-|-|
|file 1|`file 1`|All|False|
|file-1|`file-1`|None|False|
|file#1|`file#1`|None|False|
