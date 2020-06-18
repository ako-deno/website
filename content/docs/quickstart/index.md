---
title: 'Quickstart'
date: 2020-06-18T19:27:37+10:00
weight: 6
---

A short example of Ako to get started with.

<!--more-->

```js
import {
  Application,
} from "https://deno.land/x/ako/mod.ts";

const app = new Application();
app.use((ctx) => {
  ctx.body = "Hello Ako!";
});

app.listen({ port: 3000 });
```
