+++
date = 2021-10-03
description = "A cool pastejacking demo"
title = "Standard Streams"
script = "/modules/paste.mjs"
summary = "Today I learned about standard streams. I now have a deeper understanding of computers than ever before."
+++

Today I learned about standard streams. I now have a deeper understanding of
computers than ever before.

For instance, I learned that `echo` writes to `stdout`, the standard output, by
default.

```shell
{{<code "paste" "echo 'This prints to stdout'">}}
```

You can even redirect it to `stderr`!

```shell
{{<code "paste" ">&2 echo 'This prints to stderr'">}}
```

Anyways, that's all I wanted to share.