# Function: <code>__block_write_begin_int</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int __block_write_begin_int(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block, struct iomap * iomap)
```

```json
{
  "name": "__block_write_begin_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581392112,
      "name": "__block_write_begin_int",
      "external": true,
      "loc": "fs/buffer.c:1950",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_write_begin",
        "fs/iomap.c:iomap_page_mkwrite_actor",
        "fs/iomap.c:iomap_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581392112,
      "name": "__block_write_begin_int",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1492
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
int __block_write_begin_int(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block, struct iomap * iomap)
```

```json
{
  "name": "__block_write_begin_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581470528,
      "name": "__block_write_begin_int",
      "external": true,
      "loc": "fs/buffer.c:1992",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_write_begin",
        "fs/iomap.c:iomap_page_mkwrite_actor",
        "fs/iomap.c:iomap_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581470528,
      "name": "__block_write_begin_int",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1470
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
int __block_write_begin_int(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block, struct iomap * iomap)
```

```json
{
  "name": "__block_write_begin_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581526064,
      "name": "__block_write_begin_int",
      "external": true,
      "loc": "fs/buffer.c:1989",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_write_begin",
        "fs/iomap.c:iomap_page_mkwrite_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581526064,
      "name": "__block_write_begin_int",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1299
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
int __block_write_begin_int(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block, struct iomap * iomap)
```

```json
{
  "name": "__block_write_begin_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581668384,
      "name": "__block_write_begin_int",
      "external": true,
      "loc": "fs/buffer.c:1949",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_write_begin",
        "fs/iomap.c:iomap_page_mkwrite_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581668384,
      "name": "__block_write_begin_int",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1268
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
int __block_write_begin_int(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block, struct iomap * iomap)
```

```json
{
  "name": "__block_write_begin_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581831808,
      "name": "__block_write_begin_int",
      "external": true,
      "loc": "fs/buffer.c:1920",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_write_begin",
        "fs/iomap.c:iomap_page_mkwrite_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581831808,
      "name": "__block_write_begin_int",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1471
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
int __block_write_begin_int(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block, struct iomap * iomap)
```

```json
{
  "name": "__block_write_begin_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581919056,
      "name": "__block_write_begin_int",
      "external": true,
      "loc": "fs/buffer.c:1929",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581919056,
      "name": "__block_write_begin_int",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1491
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int __block_write_begin_int(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block, struct iomap * iomap)
```

```json
{
  "name": "__block_write_begin_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__block_write_begin_int",
      "external": true,
      "loc": "fs/buffer.c:1930",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582063992,
      "name": "__block_write_begin_int.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071582056256,
      "name": "__block_write_begin_int",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1534
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
int __block_write_begin_int(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block, struct iomap * iomap)
```

```json
{
  "name": "__block_write_begin_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582134032,
      "name": "__block_write_begin_int",
      "external": true,
      "loc": "fs/buffer.c:1930",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582134032,
      "name": "__block_write_begin_int",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1545
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
int __block_write_begin_int(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block, struct iomap * iomap)
```

```json
{
  "name": "__block_write_begin_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582374656,
      "name": "__block_write_begin_int",
      "external": true,
      "loc": "fs/buffer.c:1974",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:cont_write_begin",
        "fs/iomap/buffered-io.c:iomap_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582374656,
      "name": "__block_write_begin_int",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1143
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
int __block_write_begin_int(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block, struct iomap * iomap)
```

```json
{
  "name": "__block_write_begin_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582430960,
      "name": "__block_write_begin_int",
      "external": true,
      "loc": "fs/buffer.c:1973",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:cont_write_begin",
        "fs/iomap/buffered-io.c:iomap_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582430960,
      "name": "__block_write_begin_int",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 931
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
int __block_write_begin_int(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block, struct iomap * iomap)
```

```json
{
  "name": "__block_write_begin_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582457856,
      "name": "__block_write_begin_int",
      "external": true,
      "loc": "fs/buffer.c:1993",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:cont_write_begin",
        "fs/iomap/buffered-io.c:iomap_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582457856,
      "name": "__block_write_begin_int",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 970
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
int __block_write_begin_int(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block, const struct iomap * iomap)
```

```json
{
  "name": "__block_write_begin_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__block_write_begin_int",
      "external": true,
      "loc": "fs/buffer.c:1972",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:cont_write_begin",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592233067,
      "name": "__block_write_begin_int.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071582781488,
      "name": "__block_write_begin_int",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 977
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
int __block_write_begin_int(struct folio * folio, loff_t pos, unsigned int len, get_block_t * get_block, const struct iomap * iomap)
```

```json
{
  "name": "__block_write_begin_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__block_write_begin_int",
      "external": true,
      "loc": "fs/buffer.c:1968",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_write_begin",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594013287,
      "name": "__block_write_begin_int.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071583333616,
      "name": "__block_write_begin_int",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 970
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
int __block_write_begin_int(struct folio * folio, loff_t pos, unsigned int len, get_block_t * get_block, const struct iomap * iomap)
```

```json
{
  "name": "__block_write_begin_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__block_write_begin_int",
      "external": true,
      "loc": "fs/buffer.c:1953",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_write_begin",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596053156,
      "name": "__block_write_begin_int.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071583918240,
      "name": "__block_write_begin_int",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 945
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
int __block_write_begin_int(struct folio * folio, loff_t pos, unsigned int len, get_block_t * get_block, const struct iomap * iomap)
```

```json
{
  "name": "__block_write_begin_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__block_write_begin_int",
      "external": true,
      "loc": "fs/buffer.c:2090",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_write_begin",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596575895,
      "name": "__block_write_begin_int.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071584140976,
      "name": "__block_write_begin_int",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1055
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
int __block_write_begin_int(struct folio * folio, loff_t pos, unsigned int len, get_block_t * get_block, const struct iomap * iomap)
```

```json
{
  "name": "__block_write_begin_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__block_write_begin_int",
      "external": true,
      "loc": "fs/buffer.c:2068",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_write_begin",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597480171,
      "name": "__block_write_begin_int.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071584357040,
      "name": "__block_write_begin_int",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 989
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
int __block_write_begin_int(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block, struct iomap * iomap)
```

```json
{
  "name": "__block_write_begin_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493678888,
      "name": "__block_write_begin_int",
      "external": true,
      "loc": "fs/buffer.c:1930",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493678888,
      "name": "__block_write_begin_int",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1852
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
int __block_write_begin_int(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block, struct iomap * iomap)
```

```json
{
  "name": "__block_write_begin_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227210792,
      "name": "__block_write_begin_int",
      "external": true,
      "loc": "fs/buffer.c:1930",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227210792,
      "name": "__block_write_begin_int",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2208
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
int __block_write_begin_int(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block, struct iomap * iomap)
```

```json
{
  "name": "__block_write_begin_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287280992,
      "name": "__block_write_begin_int",
      "external": true,
      "loc": "fs/buffer.c:1930",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287280992,
      "name": "__block_write_begin_int",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2032
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
int __block_write_begin_int(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block, struct iomap * iomap)
```

```json
{
  "name": "__block_write_begin_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273302958,
      "name": "__block_write_begin_int",
      "external": true,
      "loc": "fs/buffer.c:1930",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273302958,
      "name": "__block_write_begin_int",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1438
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
int __block_write_begin_int(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block, struct iomap * iomap)
```

```json
{
  "name": "__block_write_begin_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582102768,
      "name": "__block_write_begin_int",
      "external": true,
      "loc": "fs/buffer.c:1930",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582102768,
      "name": "__block_write_begin_int",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1545
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
int __block_write_begin_int(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block, struct iomap * iomap)
```

```json
{
  "name": "__block_write_begin_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582040208,
      "name": "__block_write_begin_int",
      "external": true,
      "loc": "fs/buffer.c:1930",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582040208,
      "name": "__block_write_begin_int",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1545
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
int __block_write_begin_int(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block, struct iomap * iomap)
```

```json
{
  "name": "__block_write_begin_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582093248,
      "name": "__block_write_begin_int",
      "external": true,
      "loc": "fs/buffer.c:1930",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582093248,
      "name": "__block_write_begin_int",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1545
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
int __block_write_begin_int(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block, struct iomap * iomap)
```

```json
{
  "name": "__block_write_begin_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582166000,
      "name": "__block_write_begin_int",
      "external": true,
      "loc": "fs/buffer.c:1930",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582166000,
      "name": "__block_write_begin_int",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1603
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int __block_write_begin_int(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block, struct iomap * iomap)
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct iomap * iomap</code> ➡️ <code>const struct iomap * iomap</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio * folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * page</code>
</li>
</ul>
</details>
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
