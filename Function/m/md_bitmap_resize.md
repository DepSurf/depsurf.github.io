# Function: <code>md_bitmap_resize</code>

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
int md_bitmap_resize(struct bitmap * bitmap, sector_t blocks, int chunksize, int init)
```

```json
{
  "name": "md_bitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587431040,
      "name": "md_bitmap_resize",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:2046",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587431040,
      "name": "md_bitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2201
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
int md_bitmap_resize(struct bitmap * bitmap, sector_t blocks, int chunksize, int init)
```

```json
{
  "name": "md_bitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_resize",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:2053",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587711567,
      "name": "md_bitmap_resize.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071587703184,
      "name": "md_bitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2207
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int md_bitmap_resize(struct bitmap * bitmap, sector_t blocks, int chunksize, int init)
```

```json
{
  "name": "md_bitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_resize",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:2053",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587915871,
      "name": "md_bitmap_resize.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071587907472,
      "name": "md_bitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2207
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int md_bitmap_resize(struct bitmap * bitmap, sector_t blocks, int chunksize, int init)
```

```json
{
  "name": "md_bitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_resize",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:2048",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588767157,
      "name": "md_bitmap_resize.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071588758144,
      "name": "md_bitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1837
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int md_bitmap_resize(struct bitmap * bitmap, sector_t blocks, int chunksize, int init)
```

```json
{
  "name": "md_bitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_resize",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:2051",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591591056,
      "name": "md_bitmap_resize.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071588778368,
      "name": "md_bitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1835
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int md_bitmap_resize(struct bitmap * bitmap, sector_t blocks, int chunksize, int init)
```

```json
{
  "name": "md_bitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_resize",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:2053",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591534450,
      "name": "md_bitmap_resize.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071588664880,
      "name": "md_bitmap_resize",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int md_bitmap_resize(struct bitmap * bitmap, sector_t blocks, int chunksize, int init)
```

```json
{
  "name": "md_bitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_resize",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:2053",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592646653,
      "name": "md_bitmap_resize.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 563
    },
    {
      "addr": 18446744071589342880,
      "name": "md_bitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2370
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
int md_bitmap_resize(struct bitmap * bitmap, sector_t blocks, int chunksize, int init)
```

```json
{
  "name": "md_bitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_resize",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:2054",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594531155,
      "name": "md_bitmap_resize.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 955
    },
    {
      "addr": 18446744071590816416,
      "name": "md_bitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2963
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
int md_bitmap_resize(struct bitmap * bitmap, sector_t blocks, int chunksize, int init)
```

```json
{
  "name": "md_bitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_resize",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:2054",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596310841,
      "name": "md_bitmap_resize.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 880
    },
    {
      "addr": 18446744071592503568,
      "name": "md_bitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3063
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
int md_bitmap_resize(struct bitmap * bitmap, sector_t blocks, int chunksize, int init)
```

```json
{
  "name": "md_bitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_resize",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:2120",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596840208,
      "name": "md_bitmap_resize.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
    },
    {
      "addr": 18446744071592934368,
      "name": "md_bitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2752
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
int md_bitmap_resize(struct bitmap * bitmap, sector_t blocks, int chunksize, int init)
```

```json
{
  "name": "md_bitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_resize",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:2124",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597764326,
      "name": "md_bitmap_resize.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    },
    {
      "addr": 18446744071593684192,
      "name": "md_bitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2635
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
int md_bitmap_resize(struct bitmap * bitmap, sector_t blocks, int chunksize, int init)
```

```json
{
  "name": "md_bitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501137032,
      "name": "md_bitmap_resize",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:2053",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501137032,
      "name": "md_bitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1900
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
int md_bitmap_resize(struct bitmap * bitmap, sector_t blocks, int chunksize, int init)
```

```json
{
  "name": "md_bitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233652000,
      "name": "md_bitmap_resize",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:2053",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233652000,
      "name": "md_bitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2464
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
int md_bitmap_resize(struct bitmap * bitmap, sector_t blocks, int chunksize, int init)
```

```json
{
  "name": "md_bitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294644048,
      "name": "md_bitmap_resize",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:2053",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294644048,
      "name": "md_bitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2488
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
int md_bitmap_resize(struct bitmap * bitmap, sector_t blocks, int chunksize, int init)
```

```json
{
  "name": "md_bitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277852378,
      "name": "md_bitmap_resize",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:2053",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277852378,
      "name": "md_bitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1712
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int md_bitmap_resize(struct bitmap * bitmap, sector_t blocks, int chunksize, int init)
```

```json
{
  "name": "md_bitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_resize",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:2053",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587546847,
      "name": "md_bitmap_resize.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071587538448,
      "name": "md_bitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2207
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int md_bitmap_resize(struct bitmap * bitmap, sector_t blocks, int chunksize, int init)
```

```json
{
  "name": "md_bitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_resize",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:2053",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587314943,
      "name": "md_bitmap_resize.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071587306560,
      "name": "md_bitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2201
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int md_bitmap_resize(struct bitmap * bitmap, sector_t blocks, int chunksize, int init)
```

```json
{
  "name": "md_bitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_resize",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:2053",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587872015,
      "name": "md_bitmap_resize.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071587863616,
      "name": "md_bitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2207
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int md_bitmap_resize(struct bitmap * bitmap, sector_t blocks, int chunksize, int init)
```

```json
{
  "name": "md_bitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_resize",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:2053",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587987127,
      "name": "md_bitmap_resize.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071587978672,
      "name": "md_bitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2168
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
int md_bitmap_resize(struct bitmap * bitmap, sector_t blocks, int chunksize, int init)
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
