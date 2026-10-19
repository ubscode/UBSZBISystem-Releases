# UBS ZBI System — Releases

Public Windows x64 downloads / Descargas públicas para Windows x64.

## Download / Descargar

[**Latest release / Última versión**](https://github.com/ubscode/UBSZBISystem-Releases/releases/latest)

**English:** Download the ZIP from Releases, extract all files and run `UBSZBISystem.exe`. The .NET runtime is included. The app supports English and Spanish, Zebra UDP/IMPR ZBI installation and removal, live UDP monitoring and printer diagnostics.

**Español:** Descarga el ZIP de Releases, descomprime todos los archivos y ejecuta `UBSZBISystem.exe`. Incluye .NET. Permite escoger español o inglés, instalar y desinstalar los ZBI UDP/IMPR, recibir señales UDP y consultar el diagnóstico de la Zebra.

## Versions / Versiones

The application, UDP ZBI and IMPR ZBI have independent versions. See the release notes or `version.json`.

La aplicación, el ZBI UDP y el ZBI IMPR tienen versiones independientes. Consulta las notas de la release o `version.json`.

## Verification / Verificación

Each release includes `SHA256SUMS.txt`. Verify the downloaded ZIP before extracting:

```powershell
Get-FileHash .\UBS-ZBI-System-*-win-x64.zip -Algorithm SHA256
```

This repository distributes compiled releases. The source repository remains private.
Este repositorio distribuye versiones compiladas. El repositorio de código fuente permanece privado.
