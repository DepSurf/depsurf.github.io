# Function: <code>xas_get_mark</code>

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
bool xas_get_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589428640,
      "name": "xas_get_mark",
      "external": true,
      "loc": "lib/xarray.c:831",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "lib/xarray.c:xa_get_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589428640,
      "name": "xas_get_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
bool xas_get_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589886304,
      "name": "xas_get_mark",
      "external": true,
      "loc": "lib/xarray.c:850",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "lib/xarray.c:xa_get_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589886304,
      "name": "xas_get_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
bool xas_get_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590112256,
      "name": "xas_get_mark",
      "external": true,
      "loc": "lib/xarray.c:851",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "lib/xarray.c:xa_get_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590112256,
      "name": "xas_get_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
bool xas_get_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585116620,
      "name": "xas_get_mark",
      "external": true,
      "loc": "lib/xarray.c:851",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xa_get_mark",
        "lib/xarray.c:xa_get_mark"
      ],
      "caller_func": [
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:__dax_invalidate_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585111888,
      "name": "xas_get_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
bool xas_get_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585266988,
      "name": "xas_get_mark",
      "external": true,
      "loc": "lib/xarray.c:854",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xa_get_mark",
        "lib/xarray.c:xa_get_mark"
      ],
      "caller_func": [
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:__dax_invalidate_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585261392,
      "name": "xas_get_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
bool xas_get_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585150124,
      "name": "xas_get_mark",
      "external": true,
      "loc": "lib/xarray.c:854",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xa_get_mark",
        "lib/xarray.c:xa_get_mark"
      ],
      "caller_func": [
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:__dax_invalidate_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585144976,
      "name": "xas_get_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool xas_get_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585603139,
      "name": "xas_get_mark",
      "external": true,
      "loc": "lib/xarray.c:854",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xa_get_mark",
        "lib/xarray.c:xa_get_mark"
      ],
      "caller_func": [
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:__dax_invalidate_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592345213,
      "name": "xas_get_mark.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071585597920,
      "name": "xas_get_mark",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool xas_get_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586760161,
      "name": "xas_get_mark",
      "external": true,
      "loc": "lib/xarray.c:859",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xa_get_mark",
        "lib/xarray.c:xa_get_mark"
      ],
      "caller_func": [
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:__dax_invalidate_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594207108,
      "name": "xas_get_mark.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071586758416,
      "name": "xas_get_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool xas_get_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595924609,
      "name": "xas_get_mark",
      "external": true,
      "loc": "lib/xarray.c:859",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xa_get_mark",
        "lib/xarray.c:xa_get_mark"
      ],
      "caller_func": [
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:__dax_invalidate_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596376074,
      "name": "xas_get_mark.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071595923632,
      "name": "xas_get_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool xas_get_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596440993,
      "name": "xas_get_mark",
      "external": true,
      "loc": "lib/xarray.c:857",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xa_get_mark",
        "lib/xarray.c:xa_get_mark"
      ],
      "caller_func": [
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:__dax_invalidate_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596905503,
      "name": "xas_get_mark.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071596442384,
      "name": "xas_get_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool xas_get_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597336353,
      "name": "xas_get_mark",
      "external": true,
      "loc": "lib/xarray.c:857",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xa_get_mark",
        "lib/xarray.c:xa_get_mark"
      ],
      "caller_func": [
        "mm/filemap.c:filemap_cachestat",
        "mm/filemap.c:filemap_cachestat",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:__dax_invalidate_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597830596,
      "name": "xas_get_mark.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071597337744,
      "name": "xas_get_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
bool xas_get_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503890264,
      "name": "xas_get_mark",
      "external": true,
      "loc": "lib/xarray.c:851",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "lib/xarray.c:xa_get_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503890264,
      "name": "xas_get_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
bool xas_get_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236518796,
      "name": "xas_get_mark",
      "external": true,
      "loc": "lib/xarray.c:851",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xa_get_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236518796,
      "name": "xas_get_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
bool xas_get_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297756656,
      "name": "xas_get_mark",
      "external": true,
      "loc": "lib/xarray.c:851",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "lib/xarray.c:xa_get_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297756656,
      "name": "xas_get_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
bool xas_get_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279781822,
      "name": "xas_get_mark",
      "external": true,
      "loc": "lib/xarray.c:851",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "lib/xarray.c:xa_get_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279781822,
      "name": "xas_get_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
bool xas_get_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589714512,
      "name": "xas_get_mark",
      "external": true,
      "loc": "lib/xarray.c:851",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "lib/xarray.c:xa_get_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589714512,
      "name": "xas_get_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
bool xas_get_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589440288,
      "name": "xas_get_mark",
      "external": true,
      "loc": "lib/xarray.c:851",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "lib/xarray.c:xa_get_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589440288,
      "name": "xas_get_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
bool xas_get_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590157888,
      "name": "xas_get_mark",
      "external": true,
      "loc": "lib/xarray.c:851",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "lib/xarray.c:xa_get_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590157888,
      "name": "xas_get_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
bool xas_get_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_get_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590208432,
      "name": "xas_get_mark",
      "external": true,
      "loc": "lib/xarray.c:851",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "lib/xarray.c:xa_get_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590208432,
      "name": "xas_get_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
bool xas_get_mark(const struct xa_state * xas, xa_mark_t mark)
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
