# Function: <code>fw_map_paged_buf</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int fw_map_paged_buf(struct fw_priv * fw_priv)
```

```json
{
  "name": "fw_map_paged_buf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586141488,
      "name": "fw_map_paged_buf",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:319",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586141488,
      "name": "fw_map_paged_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int fw_map_paged_buf(struct fw_priv * fw_priv)
```

```json
{
  "name": "fw_map_paged_buf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586289968,
      "name": "fw_map_paged_buf",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:319",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586289968,
      "name": "fw_map_paged_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int fw_map_paged_buf(struct fw_priv * fw_priv)
```

```json
{
  "name": "fw_map_paged_buf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587060618,
      "name": "fw_map_paged_buf",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:328",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz_pages",
        "drivers/base/firmware_loader/main.c:fw_decompress_xz_pages"
      ],
      "caller_func": [
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587060928,
      "name": "fw_map_paged_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int fw_map_paged_buf(struct fw_priv * fw_priv)
```

```json
{
  "name": "fw_map_paged_buf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587145114,
      "name": "fw_map_paged_buf",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:349",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz_pages",
        "drivers/base/firmware_loader/main.c:fw_decompress_xz_pages"
      ],
      "caller_func": [
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587145424,
      "name": "fw_map_paged_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int fw_map_paged_buf(struct fw_priv * fw_priv)
```

```json
{
  "name": "fw_map_paged_buf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587032339,
      "name": "fw_map_paged_buf",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:350",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz",
        "drivers/base/firmware_loader/main.c:fw_decompress_xz"
      ],
      "caller_func": [
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587032432,
      "name": "fw_map_paged_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int fw_map_paged_buf(struct fw_priv * fw_priv)
```

```json
{
  "name": "fw_map_paged_buf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587599395,
      "name": "fw_map_paged_buf",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:351",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz",
        "drivers/base/firmware_loader/main.c:fw_decompress_xz"
      ],
      "caller_func": [
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587599488,
      "name": "fw_map_paged_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int fw_map_paged_buf(struct fw_priv * fw_priv)
```

```json
{
  "name": "fw_map_paged_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588937152,
      "name": "fw_map_paged_buf",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:290",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz",
        "drivers/base/firmware_loader/sysfs.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588937152,
      "name": "fw_map_paged_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int fw_map_paged_buf(struct fw_priv * fw_priv)
```

```json
{
  "name": "fw_map_paged_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590451392,
      "name": "fw_map_paged_buf",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:290",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz",
        "drivers/base/firmware_loader/sysfs.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590451392,
      "name": "fw_map_paged_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int fw_map_paged_buf(struct fw_priv * fw_priv)
```

```json
{
  "name": "fw_map_paged_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590771632,
      "name": "fw_map_paged_buf",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:290",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz",
        "drivers/base/firmware_loader/sysfs.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590771632,
      "name": "fw_map_paged_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int fw_map_paged_buf(struct fw_priv * fw_priv)
```

```json
{
  "name": "fw_map_paged_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591114176,
      "name": "fw_map_paged_buf",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:291",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz",
        "drivers/base/firmware_loader/sysfs.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591114176,
      "name": "fw_map_paged_buf",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int fw_map_paged_buf(struct fw_priv * fw_priv)
```

```json
{
  "name": "fw_map_paged_buf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499122032,
      "name": "fw_map_paged_buf",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:319",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499122032,
      "name": "fw_map_paged_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
int fw_map_paged_buf(struct fw_priv * fw_priv)
```

```json
{
  "name": "fw_map_paged_buf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231670404,
      "name": "fw_map_paged_buf",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:319",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231670404,
      "name": "fw_map_paged_buf",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int fw_map_paged_buf(struct fw_priv * fw_priv)
```

```json
{
  "name": "fw_map_paged_buf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292310080,
      "name": "fw_map_paged_buf",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:319",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292310080,
      "name": "fw_map_paged_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int fw_map_paged_buf(struct fw_priv * fw_priv)
```

```json
{
  "name": "fw_map_paged_buf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276438146,
      "name": "fw_map_paged_buf",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:319",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276438146,
      "name": "fw_map_paged_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int fw_map_paged_buf(struct fw_priv * fw_priv)
```

```json
{
  "name": "fw_map_paged_buf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586053216,
      "name": "fw_map_paged_buf",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:319",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586053216,
      "name": "fw_map_paged_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int fw_map_paged_buf(struct fw_priv * fw_priv)
```

```json
{
  "name": "fw_map_paged_buf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585899168,
      "name": "fw_map_paged_buf",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:319",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585899168,
      "name": "fw_map_paged_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int fw_map_paged_buf(struct fw_priv * fw_priv)
```

```json
{
  "name": "fw_map_paged_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586239360,
      "name": "fw_map_paged_buf",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:319",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586239360,
      "name": "fw_map_paged_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int fw_map_paged_buf(struct fw_priv * fw_priv)
```

```json
{
  "name": "fw_map_paged_buf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586348960,
      "name": "fw_map_paged_buf",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:319",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586348960,
      "name": "fw_map_paged_buf",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int fw_map_paged_buf(struct fw_priv * fw_priv)
```
</details>
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
