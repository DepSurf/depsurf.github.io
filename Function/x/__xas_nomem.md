# Function: <code>__xas_nomem</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool __xas_nomem(struct xa_state * xas, gfp_t gfp)
```

```json
{
  "name": "__xas_nomem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589428384,
      "name": "__xas_nomem",
      "external": false,
      "loc": "lib/xarray.c:314",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_reserve",
        "lib/xarray.c:__xa_reserve",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:__xa_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589428384,
      "name": "__xas_nomem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
bool __xas_nomem(struct xa_state * xas, gfp_t gfp)
```

```json
{
  "name": "__xas_nomem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589882896,
      "name": "__xas_nomem",
      "external": false,
      "loc": "lib/xarray.c:321",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:__xa_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589882896,
      "name": "__xas_nomem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
bool __xas_nomem(struct xa_state * xas, gfp_t gfp)
```

```json
{
  "name": "__xas_nomem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590108800,
      "name": "__xas_nomem",
      "external": false,
      "loc": "lib/xarray.c:322",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:__xa_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590108800,
      "name": "__xas_nomem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
bool __xas_nomem(struct xa_state * xas, gfp_t gfp)
```

```json
{
  "name": "__xas_nomem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585118144,
      "name": "__xas_nomem",
      "external": false,
      "loc": "lib/xarray.c:322",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:__xa_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585118144,
      "name": "__xas_nomem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
bool __xas_nomem(struct xa_state * xas, gfp_t gfp)
```

```json
{
  "name": "__xas_nomem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585268528,
      "name": "__xas_nomem",
      "external": false,
      "loc": "lib/xarray.c:324",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:__xa_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585268528,
      "name": "__xas_nomem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
bool __xas_nomem(struct xa_state * xas, gfp_t gfp)
```

```json
{
  "name": "__xas_nomem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585154368,
      "name": "__xas_nomem",
      "external": false,
      "loc": "lib/xarray.c:324",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:__xa_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585154368,
      "name": "__xas_nomem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
bool __xas_nomem(struct xa_state * xas, gfp_t gfp)
```

```json
{
  "name": "__xas_nomem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585607216,
      "name": "__xas_nomem",
      "external": false,
      "loc": "lib/xarray.c:324",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:__xa_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585607216,
      "name": "__xas_nomem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
bool __xas_nomem(struct xa_state * xas, gfp_t gfp)
```

```json
{
  "name": "__xas_nomem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586759344,
      "name": "__xas_nomem",
      "external": false,
      "loc": "lib/xarray.c:327",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:__xa_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586759344,
      "name": "__xas_nomem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
bool __xas_nomem(struct xa_state * xas, gfp_t gfp)
```

```json
{
  "name": "__xas_nomem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595923760,
      "name": "__xas_nomem",
      "external": false,
      "loc": "lib/xarray.c:327",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:__xa_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595923760,
      "name": "__xas_nomem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
bool __xas_nomem(struct xa_state * xas, gfp_t gfp)
```

```json
{
  "name": "__xas_nomem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596442528,
      "name": "__xas_nomem",
      "external": false,
      "loc": "lib/xarray.c:325",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:__xa_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596442528,
      "name": "__xas_nomem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
bool __xas_nomem(struct xa_state * xas, gfp_t gfp)
```

```json
{
  "name": "__xas_nomem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597337888,
      "name": "__xas_nomem",
      "external": false,
      "loc": "lib/xarray.c:325",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:__xa_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597337888,
      "name": "__xas_nomem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
bool __xas_nomem(struct xa_state * xas, gfp_t gfp)
```

```json
{
  "name": "__xas_nomem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503898656,
      "name": "__xas_nomem",
      "external": false,
      "loc": "lib/xarray.c:322",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:__xa_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503898656,
      "name": "__xas_nomem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
bool __xas_nomem(struct xa_state * xas, gfp_t gfp)
```

```json
{
  "name": "__xas_nomem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236522720,
      "name": "__xas_nomem",
      "external": false,
      "loc": "lib/xarray.c:322",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236522720,
      "name": "__xas_nomem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
bool __xas_nomem(struct xa_state * xas, gfp_t gfp)
```

```json
{
  "name": "__xas_nomem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297756064,
      "name": "__xas_nomem",
      "external": false,
      "loc": "lib/xarray.c:322",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:__xa_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297756064,
      "name": "__xas_nomem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 592
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
bool __xas_nomem(struct xa_state * xas, gfp_t gfp)
```

```json
{
  "name": "__xas_nomem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279786862,
      "name": "__xas_nomem",
      "external": false,
      "loc": "lib/xarray.c:322",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:__xa_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279786862,
      "name": "__xas_nomem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
bool __xas_nomem(struct xa_state * xas, gfp_t gfp)
```

```json
{
  "name": "__xas_nomem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589711056,
      "name": "__xas_nomem",
      "external": false,
      "loc": "lib/xarray.c:322",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:__xa_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589711056,
      "name": "__xas_nomem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
bool __xas_nomem(struct xa_state * xas, gfp_t gfp)
```

```json
{
  "name": "__xas_nomem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589436848,
      "name": "__xas_nomem",
      "external": false,
      "loc": "lib/xarray.c:322",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:__xa_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589436848,
      "name": "__xas_nomem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
bool __xas_nomem(struct xa_state * xas, gfp_t gfp)
```

```json
{
  "name": "__xas_nomem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590154432,
      "name": "__xas_nomem",
      "external": false,
      "loc": "lib/xarray.c:322",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:__xa_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590154432,
      "name": "__xas_nomem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
bool __xas_nomem(struct xa_state * xas, gfp_t gfp)
```

```json
{
  "name": "__xas_nomem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590204832,
      "name": "__xas_nomem",
      "external": false,
      "loc": "lib/xarray.c:322",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:__xa_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590204832,
      "name": "__xas_nomem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
bool __xas_nomem(struct xa_state * xas, gfp_t gfp)
```
</details>
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
