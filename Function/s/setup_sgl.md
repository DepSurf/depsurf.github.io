# Function: <code>setup_sgl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "setup_sgl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583034496,
      "name": "setup_sgl",
      "external": false,
      "loc": "lib/kfifo.c:347",
      "file": "lib/kfifo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_dma_in_prepare",
        "lib/kfifo.c:__kfifo_dma_out_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583034496,
      "name": "setup_sgl.isra.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "setup_sgl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583325920,
      "name": "setup_sgl",
      "external": false,
      "loc": "lib/kfifo.c:347",
      "file": "lib/kfifo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_dma_out_prepare",
        "lib/kfifo.c:__kfifo_dma_in_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583325920,
      "name": "setup_sgl.isra.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "setup_sgl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583450832,
      "name": "setup_sgl",
      "external": false,
      "loc": "lib/kfifo.c:347",
      "file": "lib/kfifo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_dma_out_prepare",
        "lib/kfifo.c:__kfifo_dma_in_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583450832,
      "name": "setup_sgl.isra.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "setup_sgl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583471424,
      "name": "setup_sgl",
      "external": false,
      "loc": "lib/kfifo.c:347",
      "file": "lib/kfifo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_dma_out_prepare",
        "lib/kfifo.c:__kfifo_dma_in_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583471424,
      "name": "setup_sgl.isra.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "setup_sgl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583652368,
      "name": "setup_sgl",
      "external": false,
      "loc": "lib/kfifo.c:347",
      "file": "lib/kfifo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_dma_out_prepare",
        "lib/kfifo.c:__kfifo_dma_in_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583652368,
      "name": "setup_sgl.isra.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
unsigned int setup_sgl(struct __kfifo * fifo, struct scatterlist * sgl, int nents, unsigned int len, unsigned int off)
```

```json
{
  "name": "setup_sgl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583870304,
      "name": "setup_sgl",
      "external": false,
      "loc": "lib/kfifo.c:347",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_dma_out_prepare",
        "lib/kfifo.c:__kfifo_dma_in_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583870304,
      "name": "setup_sgl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
unsigned int setup_sgl(struct __kfifo * fifo, struct scatterlist * sgl, int nents, unsigned int len, unsigned int off)
```

```json
{
  "name": "setup_sgl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583955600,
      "name": "setup_sgl",
      "external": false,
      "loc": "lib/kfifo.c:347",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_dma_out_prepare",
        "lib/kfifo.c:__kfifo_dma_in_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583955600,
      "name": "setup_sgl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
unsigned int setup_sgl(struct __kfifo * fifo, struct scatterlist * sgl, int nents, unsigned int len, unsigned int off)
```

```json
{
  "name": "setup_sgl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584135600,
      "name": "setup_sgl",
      "external": false,
      "loc": "lib/kfifo.c:334",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_dma_out_prepare",
        "lib/kfifo.c:__kfifo_dma_in_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584135600,
      "name": "setup_sgl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
unsigned int setup_sgl(struct __kfifo * fifo, struct scatterlist * sgl, int nents, unsigned int len, unsigned int off)
```

```json
{
  "name": "setup_sgl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584258000,
      "name": "setup_sgl",
      "external": false,
      "loc": "lib/kfifo.c:334",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_dma_out_prepare",
        "lib/kfifo.c:__kfifo_dma_in_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584258000,
      "name": "setup_sgl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
unsigned int setup_sgl(struct __kfifo * fifo, struct scatterlist * sgl, int nents, unsigned int len, unsigned int off)
```

```json
{
  "name": "setup_sgl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584665152,
      "name": "setup_sgl",
      "external": false,
      "loc": "lib/kfifo.c:334",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_dma_in_prepare_r",
        "lib/kfifo.c:__kfifo_dma_out_prepare",
        "lib/kfifo.c:__kfifo_dma_in_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584665152,
      "name": "setup_sgl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
unsigned int setup_sgl(struct __kfifo * fifo, struct scatterlist * sgl, int nents, unsigned int len, unsigned int off)
```

```json
{
  "name": "setup_sgl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584782416,
      "name": "setup_sgl",
      "external": false,
      "loc": "lib/kfifo.c:334",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_dma_in_prepare_r",
        "lib/kfifo.c:__kfifo_dma_out_prepare",
        "lib/kfifo.c:__kfifo_dma_in_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584782416,
      "name": "setup_sgl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
unsigned int setup_sgl(struct __kfifo * fifo, struct scatterlist * sgl, int nents, unsigned int len, unsigned int off)
```

```json
{
  "name": "setup_sgl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584826448,
      "name": "setup_sgl",
      "external": false,
      "loc": "lib/kfifo.c:334",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_dma_in_prepare_r",
        "lib/kfifo.c:__kfifo_dma_out_prepare",
        "lib/kfifo.c:__kfifo_dma_in_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584826448,
      "name": "setup_sgl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
unsigned int setup_sgl(struct __kfifo * fifo, struct scatterlist * sgl, int nents, unsigned int len, unsigned int off)
```

```json
{
  "name": "setup_sgl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585244864,
      "name": "setup_sgl",
      "external": false,
      "loc": "lib/kfifo.c:334",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_dma_out_prepare_r",
        "lib/kfifo.c:__kfifo_dma_in_prepare_r",
        "lib/kfifo.c:__kfifo_dma_out_prepare",
        "lib/kfifo.c:__kfifo_dma_in_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585244864,
      "name": "setup_sgl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned int setup_sgl(struct __kfifo * fifo, struct scatterlist * sgl, int nents, unsigned int len, unsigned int off)
```

```json
{
  "name": "setup_sgl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586087248,
      "name": "setup_sgl",
      "external": false,
      "loc": "lib/kfifo.c:334",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_dma_out_prepare_r",
        "lib/kfifo.c:__kfifo_dma_in_prepare_r",
        "lib/kfifo.c:__kfifo_dma_out_prepare",
        "lib/kfifo.c:__kfifo_dma_in_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586087248,
      "name": "setup_sgl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
unsigned int setup_sgl(struct __kfifo * fifo, struct scatterlist * sgl, int nents, unsigned int len, unsigned int off)
```

```json
{
  "name": "setup_sgl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587070080,
      "name": "setup_sgl",
      "external": false,
      "loc": "lib/kfifo.c:334",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_dma_out_prepare_r",
        "lib/kfifo.c:__kfifo_dma_in_prepare_r",
        "lib/kfifo.c:__kfifo_dma_out_prepare",
        "lib/kfifo.c:__kfifo_dma_in_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587070080,
      "name": "setup_sgl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
unsigned int setup_sgl(struct __kfifo * fifo, struct scatterlist * sgl, int nents, unsigned int len, unsigned int off)
```

```json
{
  "name": "setup_sgl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587328656,
      "name": "setup_sgl",
      "external": false,
      "loc": "lib/kfifo.c:334",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_dma_out_prepare_r",
        "lib/kfifo.c:__kfifo_dma_in_prepare_r",
        "lib/kfifo.c:__kfifo_dma_out_prepare",
        "lib/kfifo.c:__kfifo_dma_in_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587328656,
      "name": "setup_sgl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
unsigned int setup_sgl(struct __kfifo * fifo, struct scatterlist * sgl, int nents, unsigned int len, unsigned int off)
```

```json
{
  "name": "setup_sgl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587612016,
      "name": "setup_sgl",
      "external": false,
      "loc": "lib/kfifo.c:334",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_dma_out_prepare_r",
        "lib/kfifo.c:__kfifo_dma_in_prepare_r",
        "lib/kfifo.c:__kfifo_dma_out_prepare",
        "lib/kfifo.c:__kfifo_dma_in_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587612016,
      "name": "setup_sgl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
unsigned int setup_sgl(struct __kfifo * fifo, struct scatterlist * sgl, int nents, unsigned int len, unsigned int off)
```

```json
{
  "name": "setup_sgl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496136776,
      "name": "setup_sgl",
      "external": false,
      "loc": "lib/kfifo.c:334",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_dma_out_prepare",
        "lib/kfifo.c:__kfifo_dma_in_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496136776,
      "name": "setup_sgl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
unsigned int setup_sgl(struct __kfifo * fifo, struct scatterlist * sgl, int nents, unsigned int len, unsigned int off)
```

```json
{
  "name": "setup_sgl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229459824,
      "name": "setup_sgl",
      "external": false,
      "loc": "lib/kfifo.c:334",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_dma_out_prepare",
        "lib/kfifo.c:__kfifo_dma_in_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229459824,
      "name": "setup_sgl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
unsigned int setup_sgl(struct __kfifo * fifo, struct scatterlist * sgl, int nents, unsigned int len, unsigned int off)
```

```json
{
  "name": "setup_sgl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290395040,
      "name": "setup_sgl",
      "external": false,
      "loc": "lib/kfifo.c:334",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_dma_out_prepare_r",
        "lib/kfifo.c:__kfifo_dma_in_prepare_r",
        "lib/kfifo.c:__kfifo_dma_out_prepare",
        "lib/kfifo.c:__kfifo_dma_in_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290395040,
      "name": "setup_sgl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
unsigned int setup_sgl(struct __kfifo * fifo, struct scatterlist * sgl, int nents, unsigned int len, unsigned int off)
```

```json
{
  "name": "setup_sgl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275194152,
      "name": "setup_sgl",
      "external": false,
      "loc": "lib/kfifo.c:334",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_dma_out_prepare",
        "lib/kfifo.c:__kfifo_dma_in_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275194152,
      "name": "setup_sgl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
unsigned int setup_sgl(struct __kfifo * fifo, struct scatterlist * sgl, int nents, unsigned int len, unsigned int off)
```

```json
{
  "name": "setup_sgl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584226736,
      "name": "setup_sgl",
      "external": false,
      "loc": "lib/kfifo.c:334",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_dma_out_prepare",
        "lib/kfifo.c:__kfifo_dma_in_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584226736,
      "name": "setup_sgl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
unsigned int setup_sgl(struct __kfifo * fifo, struct scatterlist * sgl, int nents, unsigned int len, unsigned int off)
```

```json
{
  "name": "setup_sgl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584161952,
      "name": "setup_sgl",
      "external": false,
      "loc": "lib/kfifo.c:334",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_dma_out_prepare",
        "lib/kfifo.c:__kfifo_dma_in_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584161952,
      "name": "setup_sgl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
unsigned int setup_sgl(struct __kfifo * fifo, struct scatterlist * sgl, int nents, unsigned int len, unsigned int off)
```

```json
{
  "name": "setup_sgl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584210496,
      "name": "setup_sgl",
      "external": false,
      "loc": "lib/kfifo.c:334",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_dma_out_prepare",
        "lib/kfifo.c:__kfifo_dma_in_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584210496,
      "name": "setup_sgl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
unsigned int setup_sgl(struct __kfifo * fifo, struct scatterlist * sgl, int nents, unsigned int len, unsigned int off)
```

```json
{
  "name": "setup_sgl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584315056,
      "name": "setup_sgl",
      "external": false,
      "loc": "lib/kfifo.c:334",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_dma_out_prepare",
        "lib/kfifo.c:__kfifo_dma_in_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584315056,
      "name": "setup_sgl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
unsigned int setup_sgl(struct __kfifo * fifo, struct scatterlist * sgl, int nents, unsigned int len, unsigned int off)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
