# Function: <code>__xa_erase</code>

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
void * __xa_erase(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "__xa_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589431936,
      "name": "__xa_erase",
      "external": true,
      "loc": "lib/xarray.c:1305",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xa_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589431936,
      "name": "__xa_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void * __xa_erase(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "__xa_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589889936,
      "name": "__xa_erase",
      "external": true,
      "loc": "lib/xarray.c:1323",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xa_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589889936,
      "name": "__xa_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void * __xa_erase(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "__xa_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590115888,
      "name": "__xa_erase",
      "external": true,
      "loc": "lib/xarray.c:1334",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xa_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590115888,
      "name": "__xa_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void * __xa_erase(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "__xa_erase",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585121957,
      "name": "__xa_erase",
      "external": true,
      "loc": "lib/xarray.c:1336",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xa_erase"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585119520,
      "name": "__xa_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void * __xa_erase(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "__xa_erase",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585272517,
      "name": "__xa_erase",
      "external": true,
      "loc": "lib/xarray.c:1486",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xa_erase"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585269952,
      "name": "__xa_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void * __xa_erase(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "__xa_erase",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585154213,
      "name": "__xa_erase",
      "external": true,
      "loc": "lib/xarray.c:1487",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xa_erase"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585153184,
      "name": "__xa_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void * __xa_erase(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "__xa_erase",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585607061,
      "name": "__xa_erase",
      "external": true,
      "loc": "lib/xarray.c:1487",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xa_erase"
      ],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_uninit_group_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585605904,
      "name": "__xa_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void * __xa_erase(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "__xa_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586762976,
      "name": "__xa_erase",
      "external": true,
      "loc": "lib/xarray.c:1494",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/list_lru.c:memcg_reparent_list_lrus",
        "security/apparmor/secid.c:aa_free_secid",
        "lib/xarray.c:xa_erase",
        "drivers/vfio/vfio.c:vfio_uninit_group_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586762976,
      "name": "__xa_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void * __xa_erase(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "__xa_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595927296,
      "name": "__xa_erase",
      "external": true,
      "loc": "lib/xarray.c:1494",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/list_lru.c:memcg_reparent_list_lrus",
        "security/apparmor/secid.c:aa_free_secid",
        "net/core/devlink.c:__devlink_snapshot_id_decrement",
        "lib/xarray.c:xa_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595927296,
      "name": "__xa_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void * __xa_erase(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "__xa_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596445696,
      "name": "__xa_erase",
      "external": true,
      "loc": "lib/xarray.c:1492",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/list_lru.c:memcg_reparent_list_lrus",
        "security/apparmor/secid.c:aa_free_secid",
        "net/devlink/leftover.c:__devlink_snapshot_id_decrement",
        "lib/xarray.c:xa_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596445696,
      "name": "__xa_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void * __xa_erase(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "__xa_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597341056,
      "name": "__xa_erase",
      "external": true,
      "loc": "lib/xarray.c:1492",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/list_lru.c:memcg_reparent_list_lrus",
        "security/apparmor/secid.c:aa_free_secid",
        "net/devlink/region.c:__devlink_snapshot_id_decrement",
        "lib/xarray.c:xa_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597341056,
      "name": "__xa_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void * __xa_erase(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "__xa_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503896968,
      "name": "__xa_erase",
      "external": true,
      "loc": "lib/xarray.c:1334",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xa_erase",
        "lib/xarray.c:xa_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503896968,
      "name": "__xa_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void * __xa_erase(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "__xa_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236526456,
      "name": "__xa_erase",
      "external": true,
      "loc": "lib/xarray.c:1334",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xa_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236526456,
      "name": "__xa_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void * __xa_erase(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "__xa_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297766480,
      "name": "__xa_erase",
      "external": true,
      "loc": "lib/xarray.c:1334",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xa_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297766480,
      "name": "__xa_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
void * __xa_erase(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "__xa_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279785702,
      "name": "__xa_erase",
      "external": true,
      "loc": "lib/xarray.c:1334",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xa_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279785702,
      "name": "__xa_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void * __xa_erase(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "__xa_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589718144,
      "name": "__xa_erase",
      "external": true,
      "loc": "lib/xarray.c:1334",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xa_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589718144,
      "name": "__xa_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void * __xa_erase(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "__xa_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589443920,
      "name": "__xa_erase",
      "external": true,
      "loc": "lib/xarray.c:1334",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xa_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589443920,
      "name": "__xa_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void * __xa_erase(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "__xa_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590161520,
      "name": "__xa_erase",
      "external": true,
      "loc": "lib/xarray.c:1334",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xa_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590161520,
      "name": "__xa_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void * __xa_erase(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "__xa_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590212160,
      "name": "__xa_erase",
      "external": true,
      "loc": "lib/xarray.c:1334",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xa_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590212160,
      "name": "__xa_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void * __xa_erase(struct xarray * xa, long unsigned int index)
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
