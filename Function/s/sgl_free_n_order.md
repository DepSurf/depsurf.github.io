# Function: <code>sgl_free_n_order</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void sgl_free_n_order(struct scatterlist * sgl, int nents, int order)
```

```json
{
  "name": "sgl_free_n_order",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583842384,
      "name": "sgl_free_n_order",
      "external": true,
      "loc": "lib/scatterlist.c:552",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sgl_alloc_order"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583842384,
      "name": "sgl_free_n_order",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void sgl_free_n_order(struct scatterlist * sgl, int nents, int order)
```

```json
{
  "name": "sgl_free_n_order",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583926096,
      "name": "sgl_free_n_order",
      "external": true,
      "loc": "lib/scatterlist.c:552",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sgl_alloc_order"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583926096,
      "name": "sgl_free_n_order",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void sgl_free_n_order(struct scatterlist * sgl, int nents, int order)
```

```json
{
  "name": "sgl_free_n_order",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584106160,
      "name": "sgl_free_n_order",
      "external": true,
      "loc": "lib/scatterlist.c:560",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sgl_alloc_order"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584106160,
      "name": "sgl_free_n_order",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void sgl_free_n_order(struct scatterlist * sgl, int nents, int order)
```

```json
{
  "name": "sgl_free_n_order",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584228928,
      "name": "sgl_free_n_order",
      "external": true,
      "loc": "lib/scatterlist.c:560",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sgl_alloc_order"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584228928,
      "name": "sgl_free_n_order",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void sgl_free_n_order(struct scatterlist * sgl, int nents, int order)
```

```json
{
  "name": "sgl_free_n_order",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584635248,
      "name": "sgl_free_n_order",
      "external": true,
      "loc": "lib/scatterlist.c:560",
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
      "addr": 18446744071584635248,
      "name": "sgl_free_n_order",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sgl_free_n_order(struct scatterlist * sgl, int nents, int order)
```

```json
{
  "name": "sgl_free_n_order",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584756224,
      "name": "sgl_free_n_order",
      "external": true,
      "loc": "lib/scatterlist.c:641",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_free",
        "lib/scatterlist.c:sgl_alloc_order"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584754256,
      "name": "sgl_free_n_order",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sgl_free_n_order(struct scatterlist * sgl, int nents, int order)
```

```json
{
  "name": "sgl_free_n_order",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584785856,
      "name": "sgl_free_n_order",
      "external": true,
      "loc": "lib/scatterlist.c:641",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_free",
        "lib/scatterlist.c:sgl_alloc_order"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584782720,
      "name": "sgl_free_n_order",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sgl_free_n_order(struct scatterlist * sgl, int nents, int order)
```

```json
{
  "name": "sgl_free_n_order",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585216592,
      "name": "sgl_free_n_order",
      "external": true,
      "loc": "lib/scatterlist.c:672",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_free",
        "lib/scatterlist.c:sgl_alloc_order"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585213376,
      "name": "sgl_free_n_order",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sgl_free_n_order(struct scatterlist * sgl, int nents, int order)
```

```json
{
  "name": "sgl_free_n_order",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586054416,
      "name": "sgl_free_n_order",
      "external": true,
      "loc": "lib/scatterlist.c:672",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_free",
        "lib/scatterlist.c:sgl_alloc_order"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586050816,
      "name": "sgl_free_n_order",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sgl_free_n_order(struct scatterlist * sgl, int nents, int order)
```

```json
{
  "name": "sgl_free_n_order",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587038032,
      "name": "sgl_free_n_order",
      "external": true,
      "loc": "lib/scatterlist.c:682",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_free",
        "lib/scatterlist.c:sgl_alloc_order"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587034384,
      "name": "sgl_free_n_order",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sgl_free_n_order(struct scatterlist * sgl, int nents, int order)
```

```json
{
  "name": "sgl_free_n_order",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587295136,
      "name": "sgl_free_n_order",
      "external": true,
      "loc": "lib/scatterlist.c:684",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_free",
        "lib/scatterlist.c:sgl_alloc_order"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587289536,
      "name": "sgl_free_n_order",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sgl_free_n_order(struct scatterlist * sgl, int nents, int order)
```

```json
{
  "name": "sgl_free_n_order",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587580960,
      "name": "sgl_free_n_order",
      "external": true,
      "loc": "lib/scatterlist.c:685",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_free",
        "lib/scatterlist.c:sgl_alloc_order"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587575408,
      "name": "sgl_free_n_order",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void sgl_free_n_order(struct scatterlist * sgl, int nents, int order)
```

```json
{
  "name": "sgl_free_n_order",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496104136,
      "name": "sgl_free_n_order",
      "external": true,
      "loc": "lib/scatterlist.c:560",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sgl_alloc_order"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496104136,
      "name": "sgl_free_n_order",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void sgl_free_n_order(struct scatterlist * sgl, int nents, int order)
```

```json
{
  "name": "sgl_free_n_order",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229428880,
      "name": "sgl_free_n_order",
      "external": true,
      "loc": "lib/scatterlist.c:560",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sgl_alloc_order"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229428880,
      "name": "sgl_free_n_order",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void sgl_free_n_order(struct scatterlist * sgl, int nents, int order)
```

```json
{
  "name": "sgl_free_n_order",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290350752,
      "name": "sgl_free_n_order",
      "external": true,
      "loc": "lib/scatterlist.c:560",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sgl_alloc_order"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290350752,
      "name": "sgl_free_n_order",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void sgl_free_n_order(struct scatterlist * sgl, int nents, int order)
```

```json
{
  "name": "sgl_free_n_order",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275170592,
      "name": "sgl_free_n_order",
      "external": true,
      "loc": "lib/scatterlist.c:560",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sgl_alloc_order"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275170592,
      "name": "sgl_free_n_order",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void sgl_free_n_order(struct scatterlist * sgl, int nents, int order)
```

```json
{
  "name": "sgl_free_n_order",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584197664,
      "name": "sgl_free_n_order",
      "external": true,
      "loc": "lib/scatterlist.c:560",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sgl_alloc_order"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584197664,
      "name": "sgl_free_n_order",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void sgl_free_n_order(struct scatterlist * sgl, int nents, int order)
```

```json
{
  "name": "sgl_free_n_order",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584132880,
      "name": "sgl_free_n_order",
      "external": true,
      "loc": "lib/scatterlist.c:560",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sgl_alloc_order"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584132880,
      "name": "sgl_free_n_order",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void sgl_free_n_order(struct scatterlist * sgl, int nents, int order)
```

```json
{
  "name": "sgl_free_n_order",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584181424,
      "name": "sgl_free_n_order",
      "external": true,
      "loc": "lib/scatterlist.c:560",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sgl_alloc_order"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584181424,
      "name": "sgl_free_n_order",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void sgl_free_n_order(struct scatterlist * sgl, int nents, int order)
```

```json
{
  "name": "sgl_free_n_order",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584285760,
      "name": "sgl_free_n_order",
      "external": true,
      "loc": "lib/scatterlist.c:560",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sgl_alloc_order"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584285760,
      "name": "sgl_free_n_order",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void sgl_free_n_order(struct scatterlist * sgl, int nents, int order)
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
