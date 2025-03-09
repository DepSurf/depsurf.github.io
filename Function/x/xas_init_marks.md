# Function: <code>xas_init_marks</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void xas_init_marks(const struct xa_state * xas)
```

```json
{
  "name": "xas_init_marks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589429040,
      "name": "xas_init_marks",
      "external": true,
      "loc": "lib/xarray.c:913",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__delete_from_page_cache",
        "lib/xarray.c:xa_destroy",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589429040,
      "name": "xas_init_marks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void xas_init_marks(const struct xa_state * xas)
```

```json
{
  "name": "xas_init_marks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589886688,
      "name": "xas_init_marks",
      "external": true,
      "loc": "lib/xarray.c:932",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__delete_from_page_cache",
        "lib/xarray.c:xa_destroy",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589886688,
      "name": "xas_init_marks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void xas_init_marks(const struct xa_state * xas)
```

```json
{
  "name": "xas_init_marks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590112640,
      "name": "xas_init_marks",
      "external": true,
      "loc": "lib/xarray.c:933",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__delete_from_page_cache",
        "lib/xarray.c:xa_destroy",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590112640,
      "name": "xas_init_marks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void xas_init_marks(const struct xa_state * xas)
```

```json
{
  "name": "xas_init_marks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585117967,
      "name": "xas_init_marks",
      "external": true,
      "loc": "lib/xarray.c:933",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xa_destroy",
        "lib/xarray.c:xas_store"
      ],
      "caller_func": [
        "mm/filemap.c:page_cache_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585112048,
      "name": "xas_init_marks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void xas_init_marks(const struct xa_state * xas)
```

```json
{
  "name": "xas_init_marks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585268351,
      "name": "xas_init_marks",
      "external": true,
      "loc": "lib/xarray.c:936",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xa_destroy",
        "lib/xarray.c:xas_store"
      ],
      "caller_func": [
        "mm/filemap.c:page_cache_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585261552,
      "name": "xas_init_marks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void xas_init_marks(const struct xa_state * xas)
```

```json
{
  "name": "xas_init_marks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585151167,
      "name": "xas_init_marks",
      "external": true,
      "loc": "lib/xarray.c:936",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xa_destroy",
        "lib/xarray.c:xas_store"
      ],
      "caller_func": [
        "mm/filemap.c:__delete_from_page_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585145120,
      "name": "xas_init_marks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void xas_init_marks(const struct xa_state * xas)
```

```json
{
  "name": "xas_init_marks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585603572,
      "name": "xas_init_marks",
      "external": true,
      "loc": "lib/xarray.c:936",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xa_destroy",
        "lib/xarray.c:xas_store"
      ],
      "caller_func": [
        "mm/filemap.c:__delete_from_page_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585597840,
      "name": "xas_init_marks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void xas_init_marks(const struct xa_state * xas)
```

```json
{
  "name": "xas_init_marks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586760620,
      "name": "xas_init_marks",
      "external": true,
      "loc": "lib/xarray.c:941",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xa_destroy",
        "lib/xarray.c:xas_store"
      ],
      "caller_func": [
        "mm/filemap.c:__filemap_remove_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586756112,
      "name": "xas_init_marks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void xas_init_marks(const struct xa_state * xas)
```

```json
{
  "name": "xas_init_marks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595925084,
      "name": "xas_init_marks",
      "external": true,
      "loc": "lib/xarray.c:941",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xa_destroy",
        "lib/xarray.c:xas_store"
      ],
      "caller_func": [
        "mm/filemap.c:__filemap_remove_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595922752,
      "name": "xas_init_marks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void xas_init_marks(const struct xa_state * xas)
```

```json
{
  "name": "xas_init_marks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596443396,
      "name": "xas_init_marks",
      "external": true,
      "loc": "lib/xarray.c:939",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xa_destroy",
        "lib/xarray.c:xas_store"
      ],
      "caller_func": [
        "mm/filemap.c:__filemap_remove_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596441520,
      "name": "xas_init_marks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void xas_init_marks(const struct xa_state * xas)
```

```json
{
  "name": "xas_init_marks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597338756,
      "name": "xas_init_marks",
      "external": true,
      "loc": "lib/xarray.c:939",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xa_destroy",
        "lib/xarray.c:xas_store"
      ],
      "caller_func": [
        "mm/filemap.c:__filemap_remove_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597336880,
      "name": "xas_init_marks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void xas_init_marks(const struct xa_state * xas)
```

```json
{
  "name": "xas_init_marks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503894088,
      "name": "xas_init_marks",
      "external": true,
      "loc": "lib/xarray.c:933",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__delete_from_page_cache",
        "lib/xarray.c:xa_destroy",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503894088,
      "name": "xas_init_marks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void xas_init_marks(const struct xa_state * xas)
```

```json
{
  "name": "xas_init_marks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236523276,
      "name": "xas_init_marks",
      "external": true,
      "loc": "lib/xarray.c:933",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__delete_from_page_cache",
        "lib/xarray.c:xa_destroy",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236523276,
      "name": "xas_init_marks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void xas_init_marks(const struct xa_state * xas)
```

```json
{
  "name": "xas_init_marks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297761808,
      "name": "xas_init_marks",
      "external": true,
      "loc": "lib/xarray.c:933",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__delete_from_page_cache",
        "lib/xarray.c:xa_destroy",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297761808,
      "name": "xas_init_marks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void xas_init_marks(const struct xa_state * xas)
```

```json
{
  "name": "xas_init_marks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279784308,
      "name": "xas_init_marks",
      "external": true,
      "loc": "lib/xarray.c:933",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__delete_from_page_cache",
        "lib/xarray.c:xa_destroy",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279784308,
      "name": "xas_init_marks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void xas_init_marks(const struct xa_state * xas)
```

```json
{
  "name": "xas_init_marks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589714896,
      "name": "xas_init_marks",
      "external": true,
      "loc": "lib/xarray.c:933",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__delete_from_page_cache",
        "lib/xarray.c:xa_destroy",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589714896,
      "name": "xas_init_marks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void xas_init_marks(const struct xa_state * xas)
```

```json
{
  "name": "xas_init_marks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589440672,
      "name": "xas_init_marks",
      "external": true,
      "loc": "lib/xarray.c:933",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__delete_from_page_cache",
        "lib/xarray.c:xa_destroy",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589440672,
      "name": "xas_init_marks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void xas_init_marks(const struct xa_state * xas)
```

```json
{
  "name": "xas_init_marks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590158272,
      "name": "xas_init_marks",
      "external": true,
      "loc": "lib/xarray.c:933",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__delete_from_page_cache",
        "lib/xarray.c:xa_destroy",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590158272,
      "name": "xas_init_marks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void xas_init_marks(const struct xa_state * xas)
```

```json
{
  "name": "xas_init_marks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590208848,
      "name": "xas_init_marks",
      "external": true,
      "loc": "lib/xarray.c:933",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__delete_from_page_cache",
        "lib/xarray.c:xa_destroy",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590208848,
      "name": "xas_init_marks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void xas_init_marks(const struct xa_state * xas)
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
