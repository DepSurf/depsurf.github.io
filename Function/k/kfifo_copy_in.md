# Function: <code>kfifo_copy_in</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kfifo_copy_in",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583032256,
      "name": "kfifo_copy_in",
      "external": false,
      "loc": "lib/kfifo.c:102",
      "file": "lib/kfifo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583032256,
      "name": "kfifo_copy_in.isra.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
  "name": "kfifo_copy_in",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583324720,
      "name": "kfifo_copy_in",
      "external": false,
      "loc": "lib/kfifo.c:102",
      "file": "lib/kfifo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583324720,
      "name": "kfifo_copy_in.isra.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
  "name": "kfifo_copy_in",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583449632,
      "name": "kfifo_copy_in",
      "external": false,
      "loc": "lib/kfifo.c:102",
      "file": "lib/kfifo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583449632,
      "name": "kfifo_copy_in.isra.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
  "name": "kfifo_copy_in",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583470224,
      "name": "kfifo_copy_in",
      "external": false,
      "loc": "lib/kfifo.c:102",
      "file": "lib/kfifo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583470224,
      "name": "kfifo_copy_in.isra.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
  "name": "kfifo_copy_in",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583651168,
      "name": "kfifo_copy_in",
      "external": false,
      "loc": "lib/kfifo.c:102",
      "file": "lib/kfifo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583651168,
      "name": "kfifo_copy_in.isra.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void kfifo_copy_in(struct __kfifo * fifo, const void * src, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583869216,
      "name": "kfifo_copy_in",
      "external": false,
      "loc": "lib/kfifo.c:102",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583869216,
      "name": "kfifo_copy_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void kfifo_copy_in(struct __kfifo * fifo, const void * src, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583954512,
      "name": "kfifo_copy_in",
      "external": false,
      "loc": "lib/kfifo.c:102",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583954512,
      "name": "kfifo_copy_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void kfifo_copy_in(struct __kfifo * fifo, const void * src, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584134368,
      "name": "kfifo_copy_in",
      "external": false,
      "loc": "lib/kfifo.c:89",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584134368,
      "name": "kfifo_copy_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
void kfifo_copy_in(struct __kfifo * fifo, const void * src, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584256768,
      "name": "kfifo_copy_in",
      "external": false,
      "loc": "lib/kfifo.c:89",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584256768,
      "name": "kfifo_copy_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
void kfifo_copy_in(struct __kfifo * fifo, const void * src, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584664272,
      "name": "kfifo_copy_in",
      "external": false,
      "loc": "lib/kfifo.c:89",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584664272,
      "name": "kfifo_copy_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void kfifo_copy_in(struct __kfifo * fifo, const void * src, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584781600,
      "name": "kfifo_copy_in",
      "external": false,
      "loc": "lib/kfifo.c:89",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584781600,
      "name": "kfifo_copy_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void kfifo_copy_in(struct __kfifo * fifo, const void * src, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584825616,
      "name": "kfifo_copy_in",
      "external": false,
      "loc": "lib/kfifo.c:89",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584825616,
      "name": "kfifo_copy_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void kfifo_copy_in(struct __kfifo * fifo, const void * src, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585244016,
      "name": "kfifo_copy_in",
      "external": false,
      "loc": "lib/kfifo.c:89",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585244016,
      "name": "kfifo_copy_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void kfifo_copy_in(struct __kfifo * fifo, const void * src, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586085280,
      "name": "kfifo_copy_in",
      "external": false,
      "loc": "lib/kfifo.c:89",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586085280,
      "name": "kfifo_copy_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void kfifo_copy_in(struct __kfifo * fifo, const void * src, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587067936,
      "name": "kfifo_copy_in",
      "external": false,
      "loc": "lib/kfifo.c:89",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587067936,
      "name": "kfifo_copy_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void kfifo_copy_in(struct __kfifo * fifo, const void * src, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587326512,
      "name": "kfifo_copy_in",
      "external": false,
      "loc": "lib/kfifo.c:89",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587326512,
      "name": "kfifo_copy_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void kfifo_copy_in(struct __kfifo * fifo, const void * src, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587609872,
      "name": "kfifo_copy_in",
      "external": false,
      "loc": "lib/kfifo.c:89",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587609872,
      "name": "kfifo_copy_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void kfifo_copy_in(struct __kfifo * fifo, const void * src, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496135384,
      "name": "kfifo_copy_in",
      "external": false,
      "loc": "lib/kfifo.c:89",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496135384,
      "name": "kfifo_copy_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void kfifo_copy_in(struct __kfifo * fifo, const void * src, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229458496,
      "name": "kfifo_copy_in",
      "external": false,
      "loc": "lib/kfifo.c:89",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_in_r",
        "lib/kfifo.c:__kfifo_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229458496,
      "name": "kfifo_copy_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void kfifo_copy_in(struct __kfifo * fifo, const void * src, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290393008,
      "name": "kfifo_copy_in",
      "external": false,
      "loc": "lib/kfifo.c:89",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290393008,
      "name": "kfifo_copy_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
void kfifo_copy_in(struct __kfifo * fifo, const void * src, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275192956,
      "name": "kfifo_copy_in",
      "external": false,
      "loc": "lib/kfifo.c:89",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275192956,
      "name": "kfifo_copy_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
void kfifo_copy_in(struct __kfifo * fifo, const void * src, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584225504,
      "name": "kfifo_copy_in",
      "external": false,
      "loc": "lib/kfifo.c:89",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584225504,
      "name": "kfifo_copy_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
void kfifo_copy_in(struct __kfifo * fifo, const void * src, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584160720,
      "name": "kfifo_copy_in",
      "external": false,
      "loc": "lib/kfifo.c:89",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584160720,
      "name": "kfifo_copy_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
void kfifo_copy_in(struct __kfifo * fifo, const void * src, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584209264,
      "name": "kfifo_copy_in",
      "external": false,
      "loc": "lib/kfifo.c:89",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584209264,
      "name": "kfifo_copy_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
void kfifo_copy_in(struct __kfifo * fifo, const void * src, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_in",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584313824,
      "name": "kfifo_copy_in",
      "external": false,
      "loc": "lib/kfifo.c:89",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584313824,
      "name": "kfifo_copy_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
void kfifo_copy_in(struct __kfifo * fifo, const void * src, unsigned int len, unsigned int off)
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
