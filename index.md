# Javascript Bookmark Snippets

Snippets to use.

## Dark Dark Dark Mode

Make everything dark.
```
javascript:(function(){var link = document.createElement('link'); link.setAttribute('rel', 'stylesheet'); link.setAttribute('href', "https://squaredstudios-mc.github.io/JavascriptBookmarkSnippets/darkdarkdarkmode.css"); document.head.appendChild(link);})();
```

## Notepad

Open this bookmark on `about:blank` to create a notepad.

```
javascript:(function(){const textArea = document.createElement("textarea"); textArea.style.setProperty("position", "absolute"); textArea.style.setProperty("top", "0"); textArea.style.setProperty("left", "0"); textArea.style.setProperty("width", "100%"); textArea.style.setProperty("height", "100%"); textArea.style.setProperty("padding", "1rem"); textArea.value = "Notepad"; document.body.style.setProperty("padding", "0px"); document.body.style.setProperty("margin", "0px"); document.body.style.setProperty("height", "100%"); document.body.appendChild(textArea);})();
```
