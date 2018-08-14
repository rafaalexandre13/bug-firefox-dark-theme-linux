## bug-firefox-dark-theme-linux

Para corrigir o bug no Mozilla Firefox 61.0.1 em que os input do tipo "text" e "checkbox" ficam com o thema dark definido no sistema operacional:

digitar na url -> about:config

mudar os valores das seguintes chaves:

```
widget.content.allow-gtk-dark-theme = true
widget.chrome.allow-gtk-dark-theme = true
```

