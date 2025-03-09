# Function: <code>kfifo_copy_out</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kfifo_copy_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583032592,
      "name": "kfifo_copy_out",
      "external": false,
      "loc": "lib/kfifo.c:141",
      "file": "lib/kfifo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_out",
        "lib/kfifo.c:kfifo_out_copy_r"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583032592,
      "name": "kfifo_copy_out.isra.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
  "name": "kfifo_copy_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583325056,
      "name": "kfifo_copy_out",
      "external": false,
      "loc": "lib/kfifo.c:141",
      "file": "lib/kfifo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:kfifo_out_copy_r",
        "lib/kfifo.c:__kfifo_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583325056,
      "name": "kfifo_copy_out.isra.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
  "name": "kfifo_copy_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583449968,
      "name": "kfifo_copy_out",
      "external": false,
      "loc": "lib/kfifo.c:141",
      "file": "lib/kfifo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:kfifo_out_copy_r",
        "lib/kfifo.c:__kfifo_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583449968,
      "name": "kfifo_copy_out.isra.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
  "name": "kfifo_copy_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583470416,
      "name": "kfifo_copy_out",
      "external": false,
      "loc": "lib/kfifo.c:141",
      "file": "lib/kfifo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:kfifo_out_copy_r",
        "lib/kfifo.c:__kfifo_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583470416,
      "name": "kfifo_copy_out.isra.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
  "name": "kfifo_copy_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583651360,
      "name": "kfifo_copy_out",
      "external": false,
      "loc": "lib/kfifo.c:141",
      "file": "lib/kfifo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:kfifo_out_copy_r",
        "lib/kfifo.c:__kfifo_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583651360,
      "name": "kfifo_copy_out.isra.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void kfifo_copy_out(struct __kfifo * fifo, void * dst, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583869376,
      "name": "kfifo_copy_out",
      "external": false,
      "loc": "lib/kfifo.c:141",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:kfifo_out_copy_r",
        "lib/kfifo.c:__kfifo_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583869376,
      "name": "kfifo_copy_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void kfifo_copy_out(struct __kfifo * fifo, void * dst, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583954672,
      "name": "kfifo_copy_out",
      "external": false,
      "loc": "lib/kfifo.c:141",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:kfifo_out_copy_r",
        "lib/kfifo.c:__kfifo_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583954672,
      "name": "kfifo_copy_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void kfifo_copy_out(struct __kfifo * fifo, void * dst, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584134544,
      "name": "kfifo_copy_out",
      "external": false,
      "loc": "lib/kfifo.c:128",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:kfifo_out_copy_r",
        "lib/kfifo.c:__kfifo_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584134544,
      "name": "kfifo_copy_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void kfifo_copy_out(struct __kfifo * fifo, void * dst, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584256944,
      "name": "kfifo_copy_out",
      "external": false,
      "loc": "lib/kfifo.c:128",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:kfifo_out_copy_r",
        "lib/kfifo.c:__kfifo_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584256944,
      "name": "kfifo_copy_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void kfifo_copy_out(struct __kfifo * fifo, void * dst, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584664448,
      "name": "kfifo_copy_out",
      "external": false,
      "loc": "lib/kfifo.c:128",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584664448,
      "name": "kfifo_copy_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
void kfifo_copy_out(struct __kfifo * fifo, void * dst, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584781776,
      "name": "kfifo_copy_out",
      "external": false,
      "loc": "lib/kfifo.c:128",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584781776,
      "name": "kfifo_copy_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
void kfifo_copy_out(struct __kfifo * fifo, void * dst, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584825792,
      "name": "kfifo_copy_out",
      "external": false,
      "loc": "lib/kfifo.c:128",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584825792,
      "name": "kfifo_copy_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
void kfifo_copy_out(struct __kfifo * fifo, void * dst, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585244192,
      "name": "kfifo_copy_out",
      "external": false,
      "loc": "lib/kfifo.c:128",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585244192,
      "name": "kfifo_copy_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
void kfifo_copy_out(struct __kfifo * fifo, void * dst, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586085472,
      "name": "kfifo_copy_out",
      "external": false,
      "loc": "lib/kfifo.c:128",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586085472,
      "name": "kfifo_copy_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
void kfifo_copy_out(struct __kfifo * fifo, void * dst, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587068160,
      "name": "kfifo_copy_out",
      "external": false,
      "loc": "lib/kfifo.c:128",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587068160,
      "name": "kfifo_copy_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
void kfifo_copy_out(struct __kfifo * fifo, void * dst, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587326736,
      "name": "kfifo_copy_out",
      "external": false,
      "loc": "lib/kfifo.c:128",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587326736,
      "name": "kfifo_copy_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
void kfifo_copy_out(struct __kfifo * fifo, void * dst, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587610096,
      "name": "kfifo_copy_out",
      "external": false,
      "loc": "lib/kfifo.c:128",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587610096,
      "name": "kfifo_copy_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
void kfifo_copy_out(struct __kfifo * fifo, void * dst, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496135608,
      "name": "kfifo_copy_out",
      "external": false,
      "loc": "lib/kfifo.c:128",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:kfifo_out_copy_r",
        "lib/kfifo.c:__kfifo_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496135608,
      "name": "kfifo_copy_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void kfifo_copy_out(struct __kfifo * fifo, void * dst, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229458816,
      "name": "kfifo_copy_out",
      "external": false,
      "loc": "lib/kfifo.c:128",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:kfifo_out_copy_r",
        "lib/kfifo.c:__kfifo_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229458816,
      "name": "kfifo_copy_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void kfifo_copy_out(struct __kfifo * fifo, void * dst, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290393376,
      "name": "kfifo_copy_out",
      "external": false,
      "loc": "lib/kfifo.c:128",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:kfifo_out_copy_r",
        "lib/kfifo.c:__kfifo_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290393376,
      "name": "kfifo_copy_out",
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
void kfifo_copy_out(struct __kfifo * fifo, void * dst, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275193182,
      "name": "kfifo_copy_out",
      "external": false,
      "loc": "lib/kfifo.c:128",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:kfifo_out_copy_r",
        "lib/kfifo.c:__kfifo_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275193182,
      "name": "kfifo_copy_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void kfifo_copy_out(struct __kfifo * fifo, void * dst, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584225680,
      "name": "kfifo_copy_out",
      "external": false,
      "loc": "lib/kfifo.c:128",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:kfifo_out_copy_r",
        "lib/kfifo.c:__kfifo_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584225680,
      "name": "kfifo_copy_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void kfifo_copy_out(struct __kfifo * fifo, void * dst, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584160896,
      "name": "kfifo_copy_out",
      "external": false,
      "loc": "lib/kfifo.c:128",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:kfifo_out_copy_r",
        "lib/kfifo.c:__kfifo_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584160896,
      "name": "kfifo_copy_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void kfifo_copy_out(struct __kfifo * fifo, void * dst, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584209440,
      "name": "kfifo_copy_out",
      "external": false,
      "loc": "lib/kfifo.c:128",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:kfifo_out_copy_r",
        "lib/kfifo.c:__kfifo_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584209440,
      "name": "kfifo_copy_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void kfifo_copy_out(struct __kfifo * fifo, void * dst, unsigned int len, unsigned int off)
```

```json
{
  "name": "kfifo_copy_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584314000,
      "name": "kfifo_copy_out",
      "external": false,
      "loc": "lib/kfifo.c:128",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:kfifo_out_copy_r",
        "lib/kfifo.c:__kfifo_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584314000,
      "name": "kfifo_copy_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void kfifo_copy_out(struct __kfifo * fifo, void * dst, unsigned int len, unsigned int off)
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
