---
title: Разное
---


### `<noscript>`

Если вы используете теги `<noscript>` в компоненте, Svelte будет отображать их только в режиме SSR. А клиентский DOM-компилятор удалит их, так как вы не сможете создать компонент без JavaScript на клиенте, а `<noscript>` не имеет никакого эффекта, если JavaScript выключен.