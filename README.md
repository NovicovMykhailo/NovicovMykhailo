-Слова и сокращения в CSS-классах https://github.com/nicothin/idiomatic-pre-CSS/blob/gh-pages/words_and_abbreviations.md

-Словарь терминов по фронтенду https://github.com/web-standards-ru/dictionary/blob/main/dictionary.md

-Слова, часто используемые в CSS-классах https://github.com/yoksel/common-words

-Validator https://validator.w3.org/nu/#textarea

-Emmet cheat Sheet https://docs.emmet.io/cheat-sheet/

- ресурс для перевірки вкладеності тегів https://caninclude.glitch.me/

- Генератор HTML-дерева BEM https://yoksel.github.io/html-tree/

-  BEM - https://ru.bem.info/methodology/quick-start/#%D0%BC%D0%B8%D0%BA%D1%81


 - max height on mobile viewport trick makes a job -   height: calc(100vh - calc(100vh - 100%))
       



parcel build ./src/index.html --dist-dir dist



[
.visually-hidden {
	position: absolute;
	white-space: nowrap;
	width: 1px;
	height: 1px;
	overflow: hidden;
	border: 0;
	padding: 0;
	clip: rect(0 0 0 0);
	clip-path: inset(50%);
	margin: -1px;
}
]
LiveSassCompailer setings.json
{
  "liveSassCompile.settings.formats": [
    {
      "format": "expanded",
      "extensionName": ".css",
      "savePath": "/css"
    },
    {
      "format": "compressed",
      "extensionName": ".min.css",
      "savePath": "/css"
    }
  ],
  "liveSassCompile.settings.excludeList": ["/**/node_modules/**", "/.vscode/**"],
  "liveSassCompile.settings.generateMap": true,
  "liveSassCompile.settings.autoprefix": ["> 1%", "last 2 versions"]
}
