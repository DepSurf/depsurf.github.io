# Function: <code>_regmap_raw_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int _regmap_raw_write(struct regmap * map, unsigned int reg, const void * val, size_t val_len)
```

```json
{
  "name": "_regmap_raw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584505280,
      "name": "_regmap_raw_write",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:1198",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_raw_write",
        "drivers/base/regmap/regmap.c:regmap_raw_write",
        "drivers/base/regmap/regmap.c:regmap_raw_write_async",
        "drivers/base/regmap/regmap.c:regmap_bulk_write",
        "drivers/base/regmap/regmap.c:regmap_bulk_write",
        "drivers/base/regmap/regmap.c:regmap_bulk_write",
        "drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584505280,
      "name": "_regmap_raw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1832
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int _regmap_raw_write(struct regmap * map, unsigned int reg, const void * val, size_t val_len)
```

```json
{
  "name": "_regmap_raw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584852080,
      "name": "_regmap_raw_write",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:1299",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_raw_write_async",
        "drivers/base/regmap/regmap.c:regmap_bulk_write",
        "drivers/base/regmap/regmap.c:regmap_bulk_write",
        "drivers/base/regmap/regmap.c:regmap_bulk_write",
        "drivers/base/regmap/regmap.c:regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584852080,
      "name": "_regmap_raw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2006
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int _regmap_raw_write(struct regmap * map, unsigned int reg, const void * val, size_t val_len)
```

```json
{
  "name": "_regmap_raw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585045616,
      "name": "_regmap_raw_write",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:1346",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_raw_write_async",
        "drivers/base/regmap/regmap.c:regmap_bulk_write",
        "drivers/base/regmap/regmap.c:regmap_bulk_write",
        "drivers/base/regmap/regmap.c:regmap_bulk_write",
        "drivers/base/regmap/regmap.c:regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585045616,
      "name": "_regmap_raw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2021
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int _regmap_raw_write(struct regmap * map, unsigned int reg, const void * val, size_t val_len)
```

```json
{
  "name": "_regmap_raw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585130048,
      "name": "_regmap_raw_write",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:1349",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_raw_write_async",
        "drivers/base/regmap/regmap.c:regmap_bulk_write",
        "drivers/base/regmap/regmap.c:regmap_bulk_write",
        "drivers/base/regmap/regmap.c:regmap_bulk_write",
        "drivers/base/regmap/regmap.c:regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585130048,
      "name": "_regmap_raw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1968
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int _regmap_raw_write(struct regmap * map, unsigned int reg, const void * val, size_t val_len)
```

```json
{
  "name": "_regmap_raw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585556608,
      "name": "_regmap_raw_write",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:1428",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_raw_write_async",
        "drivers/base/regmap/regmap.c:regmap_bulk_write",
        "drivers/base/regmap/regmap.c:regmap_bulk_write",
        "drivers/base/regmap/regmap.c:regmap_bulk_write",
        "drivers/base/regmap/regmap.c:regmap_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_raw_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write",
        "drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585556608,
      "name": "_regmap_raw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2024
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
int _regmap_raw_write(struct regmap * map, unsigned int reg, const void * val, size_t val_len)
```

```json
{
  "name": "_regmap_raw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585805008,
      "name": "_regmap_raw_write",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:1812",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_raw_write_async",
        "drivers/base/regmap/regmap.c:regmap_raw_write",
        "drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585805008,
      "name": "_regmap_raw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int _regmap_raw_write(struct regmap * map, unsigned int reg, const void * val, size_t val_len)
```

```json
{
  "name": "_regmap_raw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585938672,
      "name": "_regmap_raw_write",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:1848",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_raw_write_async",
        "drivers/base/regmap/regmap.c:regmap_noinc_write",
        "drivers/base/regmap/regmap.c:regmap_noinc_write",
        "drivers/base/regmap/regmap.c:regmap_raw_write",
        "drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585938672,
      "name": "_regmap_raw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int _regmap_raw_write(struct regmap * map, unsigned int reg, const void * val, size_t val_len)
```

```json
{
  "name": "_regmap_raw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586179984,
      "name": "_regmap_raw_write",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:1845",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_raw_write_async",
        "drivers/base/regmap/regmap.c:regmap_noinc_write",
        "drivers/base/regmap/regmap.c:regmap_noinc_write",
        "drivers/base/regmap/regmap.c:regmap_raw_write",
        "drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586179984,
      "name": "_regmap_raw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
int _regmap_raw_write(struct regmap * map, unsigned int reg, const void * val, size_t val_len)
```

```json
{
  "name": "_regmap_raw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586328496,
      "name": "_regmap_raw_write",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:1852",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_raw_write_async",
        "drivers/base/regmap/regmap.c:regmap_noinc_write",
        "drivers/base/regmap/regmap.c:regmap_noinc_write",
        "drivers/base/regmap/regmap.c:regmap_raw_write",
        "drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586328496,
      "name": "_regmap_raw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
int _regmap_raw_write(struct regmap * map, unsigned int reg, const void * val, size_t val_len, bool noinc)
```

```json
{
  "name": "_regmap_raw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587098960,
      "name": "_regmap_raw_write",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:1847",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_raw_write_async",
        "drivers/base/regmap/regmap.c:regmap_noinc_write",
        "drivers/base/regmap/regmap.c:regmap_noinc_write",
        "drivers/base/regmap/regmap.c:regmap_raw_write",
        "drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587098960,
      "name": "_regmap_raw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
int _regmap_raw_write(struct regmap * map, unsigned int reg, const void * val, size_t val_len, bool noinc)
```

```json
{
  "name": "_regmap_raw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587185184,
      "name": "_regmap_raw_write",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:1996",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_raw_write_async",
        "drivers/base/regmap/regmap.c:regmap_noinc_write",
        "drivers/base/regmap/regmap.c:regmap_noinc_write",
        "drivers/base/regmap/regmap.c:regmap_raw_write",
        "drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587185184,
      "name": "_regmap_raw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
int _regmap_raw_write(struct regmap * map, unsigned int reg, const void * val, size_t val_len, bool noinc)
```

```json
{
  "name": "_regmap_raw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587072656,
      "name": "_regmap_raw_write",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:1996",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_raw_write_async",
        "drivers/base/regmap/regmap.c:regmap_noinc_write",
        "drivers/base/regmap/regmap.c:regmap_noinc_write",
        "drivers/base/regmap/regmap.c:regmap_raw_write",
        "drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587072656,
      "name": "_regmap_raw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
int _regmap_raw_write(struct regmap * map, unsigned int reg, const void * val, size_t val_len, bool noinc)
```

```json
{
  "name": "_regmap_raw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regmap_raw_write",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2037",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_raw_write_async",
        "drivers/base/regmap/regmap.c:regmap_noinc_write",
        "drivers/base/regmap/regmap.c:regmap_noinc_write",
        "drivers/base/regmap/regmap.c:regmap_raw_write",
        "drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592496433,
      "name": "_regmap_raw_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071587643888,
      "name": "_regmap_raw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
int _regmap_raw_write(struct regmap * map, unsigned int reg, const void * val, size_t val_len, bool noinc)
```

```json
{
  "name": "_regmap_raw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regmap_raw_write",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2056",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_raw_write_async",
        "drivers/base/regmap/regmap.c:regmap_noinc_write",
        "drivers/base/regmap/regmap.c:regmap_raw_write",
        "drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594366825,
      "name": "_regmap_raw_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071588987984,
      "name": "_regmap_raw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
int _regmap_raw_write(struct regmap * map, unsigned int reg, const void * val, size_t val_len, bool noinc)
```

```json
{
  "name": "_regmap_raw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regmap_raw_write",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2060",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_raw_write_async",
        "drivers/base/regmap/regmap.c:regmap_noinc_write",
        "drivers/base/regmap/regmap.c:regmap_raw_write",
        "drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596250188,
      "name": "_regmap_raw_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071590509152,
      "name": "_regmap_raw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
int _regmap_raw_write(struct regmap * map, unsigned int reg, const void * val, size_t val_len, bool noinc)
```

```json
{
  "name": "_regmap_raw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regmap_raw_write",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2078",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_raw_write_async",
        "drivers/base/regmap/regmap.c:regmap_noinc_write",
        "drivers/base/regmap/regmap.c:regmap_raw_write",
        "drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush",
        "drivers/base/regmap/regcache-maple.c:regcache_maple_sync_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596778727,
      "name": "_regmap_raw_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071590833312,
      "name": "_regmap_raw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
int _regmap_raw_write(struct regmap * map, unsigned int reg, const void * val, size_t val_len, bool noinc)
```

```json
{
  "name": "_regmap_raw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regmap_raw_write",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:1986",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_raw_write_async",
        "drivers/base/regmap/regmap.c:regmap_noinc_write",
        "drivers/base/regmap/regmap.c:regmap_raw_write",
        "drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush",
        "drivers/base/regmap/regcache-maple.c:regcache_maple_sync_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597687662,
      "name": "_regmap_raw_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071591176352,
      "name": "_regmap_raw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
int _regmap_raw_write(struct regmap * map, unsigned int reg, const void * val, size_t val_len)
```

```json
{
  "name": "_regmap_raw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499165584,
      "name": "_regmap_raw_write",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:1852",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_raw_write_async",
        "drivers/base/regmap/regmap.c:regmap_noinc_write",
        "drivers/base/regmap/regmap.c:regmap_noinc_write",
        "drivers/base/regmap/regmap.c:regmap_raw_write",
        "drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499165584,
      "name": "_regmap_raw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int _regmap_raw_write(struct regmap * map, unsigned int reg, const void * val, size_t val_len)
```

```json
{
  "name": "_regmap_raw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231700984,
      "name": "_regmap_raw_write",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:1852",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_raw_write_async",
        "drivers/base/regmap/regmap.c:regmap_noinc_write",
        "drivers/base/regmap/regmap.c:regmap_noinc_write",
        "drivers/base/regmap/regmap.c:regmap_raw_write",
        "drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231700984,
      "name": "_regmap_raw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
int _regmap_raw_write(struct regmap * map, unsigned int reg, const void * val, size_t val_len)
```

```json
{
  "name": "_regmap_raw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292365504,
      "name": "_regmap_raw_write",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:1852",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_raw_write_async",
        "drivers/base/regmap/regmap.c:regmap_noinc_write",
        "drivers/base/regmap/regmap.c:regmap_noinc_write",
        "drivers/base/regmap/regmap.c:regmap_raw_write",
        "drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292365504,
      "name": "_regmap_raw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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
int _regmap_raw_write(struct regmap * map, unsigned int reg, const void * val, size_t val_len)
```

```json
{
  "name": "_regmap_raw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276463962,
      "name": "_regmap_raw_write",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:1852",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_raw_write_async",
        "drivers/base/regmap/regmap.c:regmap_noinc_write",
        "drivers/base/regmap/regmap.c:regmap_noinc_write",
        "drivers/base/regmap/regmap.c:regmap_raw_write",
        "drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276463962,
      "name": "_regmap_raw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int _regmap_raw_write(struct regmap * map, unsigned int reg, const void * val, size_t val_len)
```

```json
{
  "name": "_regmap_raw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586091744,
      "name": "_regmap_raw_write",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:1852",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_raw_write_async",
        "drivers/base/regmap/regmap.c:regmap_noinc_write",
        "drivers/base/regmap/regmap.c:regmap_noinc_write",
        "drivers/base/regmap/regmap.c:regmap_raw_write",
        "drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586091744,
      "name": "_regmap_raw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
int _regmap_raw_write(struct regmap * map, unsigned int reg, const void * val, size_t val_len)
```

```json
{
  "name": "_regmap_raw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585937696,
      "name": "_regmap_raw_write",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:1852",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_raw_write_async",
        "drivers/base/regmap/regmap.c:regmap_noinc_write",
        "drivers/base/regmap/regmap.c:regmap_noinc_write",
        "drivers/base/regmap/regmap.c:regmap_raw_write",
        "drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585937696,
      "name": "_regmap_raw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
int _regmap_raw_write(struct regmap * map, unsigned int reg, const void * val, size_t val_len)
```

```json
{
  "name": "_regmap_raw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586276464,
      "name": "_regmap_raw_write",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:1852",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_raw_write_async",
        "drivers/base/regmap/regmap.c:regmap_noinc_write",
        "drivers/base/regmap/regmap.c:regmap_noinc_write",
        "drivers/base/regmap/regmap.c:regmap_raw_write",
        "drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586276464,
      "name": "_regmap_raw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
int _regmap_raw_write(struct regmap * map, unsigned int reg, const void * val, size_t val_len)
```

```json
{
  "name": "_regmap_raw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586387728,
      "name": "_regmap_raw_write",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:1852",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_raw_write_async",
        "drivers/base/regmap/regmap.c:regmap_noinc_write",
        "drivers/base/regmap/regmap.c:regmap_noinc_write",
        "drivers/base/regmap/regmap.c:regmap_raw_write",
        "drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586387728,
      "name": "_regmap_raw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool noinc</code>
</li>
</ul>
</details>
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
