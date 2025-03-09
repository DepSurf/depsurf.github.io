# Function: <code>xa_get_order</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int xa_get_order(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_get_order",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585266704,
      "name": "xa_get_order",
      "external": true,
      "loc": "lib/xarray.c:1753",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:__add_to_page_cache_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585266704,
      "name": "xa_get_order",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
int xa_get_order(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_get_order",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585149840,
      "name": "xa_get_order",
      "external": true,
      "loc": "lib/xarray.c:1754",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:__add_to_page_cache_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585149840,
      "name": "xa_get_order",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int xa_get_order(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_get_order",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xa_get_order",
      "external": true,
      "loc": "lib/xarray.c:1754",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:__add_to_page_cache_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592345527,
      "name": "xa_get_order.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071585601840,
      "name": "xa_get_order",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int xa_get_order(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_get_order",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xa_get_order",
      "external": true,
      "loc": "lib/xarray.c:1761",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:__filemap_add_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594206540,
      "name": "xa_get_order.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071586754496,
      "name": "xa_get_order",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int xa_get_order(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_get_order",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xa_get_order",
      "external": true,
      "loc": "lib/xarray.c:1761",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:__filemap_add_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596375506,
      "name": "xa_get_order.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071595919456,
      "name": "xa_get_order",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int xa_get_order(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_get_order",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xa_get_order",
      "external": true,
      "loc": "lib/xarray.c:1759",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_cachestat",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:__filemap_add_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596905022,
      "name": "xa_get_order.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071596437760,
      "name": "xa_get_order",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int xa_get_order(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_get_order",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xa_get_order",
      "external": true,
      "loc": "lib/xarray.c:1759",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_cachestat",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:__filemap_add_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597830115,
      "name": "xa_get_order.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071597333120,
      "name": "xa_get_order",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int xa_get_order(struct xarray * xa, long unsigned int index)
```
</details>
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
