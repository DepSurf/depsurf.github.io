# Function: <code>sgl_free</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sgl_free(struct scatterlist * sgl)
```

```json
{
  "name": "sgl_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583845218,
      "name": "sgl_free",
      "external": true,
      "loc": "lib/scatterlist.c:584",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_alloc_order"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583842544,
      "name": "sgl_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sgl_free(struct scatterlist * sgl)
```

```json
{
  "name": "sgl_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583928914,
      "name": "sgl_free",
      "external": true,
      "loc": "lib/scatterlist.c:584",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_alloc_order"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583926256,
      "name": "sgl_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sgl_free(struct scatterlist * sgl)
```

```json
{
  "name": "sgl_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584108788,
      "name": "sgl_free",
      "external": true,
      "loc": "lib/scatterlist.c:592",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_alloc_order"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584106320,
      "name": "sgl_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sgl_free(struct scatterlist * sgl)
```

```json
{
  "name": "sgl_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584230148,
      "name": "sgl_free",
      "external": true,
      "loc": "lib/scatterlist.c:592",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_alloc_order"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584229088,
      "name": "sgl_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sgl_free(struct scatterlist * sgl)
```

```json
{
  "name": "sgl_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584637216,
      "name": "sgl_free",
      "external": true,
      "loc": "lib/scatterlist.c:592",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_alloc_order"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584637216,
      "name": "sgl_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void sgl_free(struct scatterlist * sgl)
```

```json
{
  "name": "sgl_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584756224,
      "name": "sgl_free",
      "external": true,
      "loc": "lib/scatterlist.c:673",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584756224,
      "name": "sgl_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void sgl_free(struct scatterlist * sgl)
```

```json
{
  "name": "sgl_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584785856,
      "name": "sgl_free",
      "external": true,
      "loc": "lib/scatterlist.c:673",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584785856,
      "name": "sgl_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void sgl_free(struct scatterlist * sgl)
```

```json
{
  "name": "sgl_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585216592,
      "name": "sgl_free",
      "external": true,
      "loc": "lib/scatterlist.c:704",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585216592,
      "name": "sgl_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void sgl_free(struct scatterlist * sgl)
```

```json
{
  "name": "sgl_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586054416,
      "name": "sgl_free",
      "external": true,
      "loc": "lib/scatterlist.c:704",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586054416,
      "name": "sgl_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void sgl_free(struct scatterlist * sgl)
```

```json
{
  "name": "sgl_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587038032,
      "name": "sgl_free",
      "external": true,
      "loc": "lib/scatterlist.c:714",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587038032,
      "name": "sgl_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void sgl_free(struct scatterlist * sgl)
```

```json
{
  "name": "sgl_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587295136,
      "name": "sgl_free",
      "external": true,
      "loc": "lib/scatterlist.c:716",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587295136,
      "name": "sgl_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void sgl_free(struct scatterlist * sgl)
```

```json
{
  "name": "sgl_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587580960,
      "name": "sgl_free",
      "external": true,
      "loc": "lib/scatterlist.c:717",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587580960,
      "name": "sgl_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void sgl_free(struct scatterlist * sgl)
```

```json
{
  "name": "sgl_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496107108,
      "name": "sgl_free",
      "external": true,
      "loc": "lib/scatterlist.c:592",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_alloc_order"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496104320,
      "name": "sgl_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void sgl_free(struct scatterlist * sgl)
```

```json
{
  "name": "sgl_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229431576,
      "name": "sgl_free",
      "external": true,
      "loc": "lib/scatterlist.c:592",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_alloc_order"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3229429044,
      "name": "sgl_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void sgl_free(struct scatterlist * sgl)
```

```json
{
  "name": "sgl_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290354784,
      "name": "sgl_free",
      "external": true,
      "loc": "lib/scatterlist.c:592",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_alloc_order"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290351024,
      "name": "sgl_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void sgl_free(struct scatterlist * sgl)
```

```json
{
  "name": "sgl_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275172482,
      "name": "sgl_free",
      "external": true,
      "loc": "lib/scatterlist.c:592",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_alloc_order"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275170740,
      "name": "sgl_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void sgl_free(struct scatterlist * sgl)
```

```json
{
  "name": "sgl_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584198884,
      "name": "sgl_free",
      "external": true,
      "loc": "lib/scatterlist.c:592",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_alloc_order"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584197824,
      "name": "sgl_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void sgl_free(struct scatterlist * sgl)
```

```json
{
  "name": "sgl_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584134100,
      "name": "sgl_free",
      "external": true,
      "loc": "lib/scatterlist.c:592",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_alloc_order"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584133040,
      "name": "sgl_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void sgl_free(struct scatterlist * sgl)
```

```json
{
  "name": "sgl_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584182644,
      "name": "sgl_free",
      "external": true,
      "loc": "lib/scatterlist.c:592",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_alloc_order"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584181584,
      "name": "sgl_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void sgl_free(struct scatterlist * sgl)
```

```json
{
  "name": "sgl_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584286980,
      "name": "sgl_free",
      "external": true,
      "loc": "lib/scatterlist.c:592",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_alloc_order"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584285920,
      "name": "sgl_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void sgl_free(struct scatterlist * sgl)
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
