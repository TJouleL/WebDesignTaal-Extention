# WebDesignTaal Extensie
![](https://img.shields.io/github/stars/TJouleL/WebDesignTaal-Extension) ![](https://img.shields.io/github/forks/TJouleL/WebDesignTaal-Extension) ![](https://img.shields.io/github/tag/TJouleL/WebDesignTaal-Extension) ![](https://img.shields.io/github/release/TJouleL/WebDesignTaal-Extension) ![](https://img.shields.io/github/issues/TJouleL/WebDesignTaal-Extension)

Deze Visual Studio Code extensie biedt syntax highlighting voor WebDesignTaal (`.wdt`) bestanden, waardoor je code gemakkelijker te lezen en te schrijven is. Voor meer informatie over WebDesignTaal, bezoek de officiële GitHub repository: [TJouleL/WebDesignTaal](https://github.com/TJouleL/WebDesignTaal). 

### Het .vsix bestand voor de huidige versie is te vinden bij releases. 

De versie van de extensie is gebaseerd op de versie's van WebDesignTaal. De Extensie met de versie `1.1.2` zal werken voor WebDesignTaal versie `1.1.2` en lager (`1.1.1`, `1.1.0`, etc) behalve bij verschil in major versie's (`1.0.0` -> `2.0.0`). Het beste is om dezelfde versie Extensie te hebben als WebDesignTaal.

## Installatie

1.  Ga naar de [Releases pagina](https://github.com/TJouleL/WebDesignTaal-Extension/releases) op GitHub.
2.  Download het meest recente `.vsix` bestand van de nieuwste release.
3.  Open Visual Studio Code.
4.  Navigeer naar de **Extensions** weergave (Ctrl+Shift+X).
5.  Klik op de drie puntjes (...) in de rechterbovenhoek van de Extensions weergave.
6.  Selecteer **Install from VSIX...** en kies het `.vsix` bestand dat je zojuist hebt gedownload.

Als je zelf van source wil compilen installeer dan `node` en gebruik `npx @vscode/vsce package` in dezelfde map als package.json

WebDesignTaal is een programmeertaal die is ontworpen om het schrijven van webpagina's te vereenvoudigen met een intuïtieve Nederlandse syntax. Het compileert je code naar gestructureerde HTML.
