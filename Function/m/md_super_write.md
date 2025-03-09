# Function: <code>md_super_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void md_super_write(struct mddev * mddev, struct md_rdev * rdev, sector_t sector, int size, struct page * page)
```

```json
{
  "name": "md_super_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585749056,
      "name": "md_super_write",
      "external": true,
      "loc": "drivers/md/md.c:733",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change",
        "drivers/md/bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585749056,
      "name": "md_super_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void md_super_write(struct mddev * mddev, struct md_rdev * rdev, sector_t sector, int size, struct page * page)
```

```json
{
  "name": "md_super_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586146192,
      "name": "md_super_write",
      "external": true,
      "loc": "drivers/md/md.c:728",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change",
        "drivers/md/bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586146192,
      "name": "md_super_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void md_super_write(struct mddev * mddev, struct md_rdev * rdev, sector_t sector, int size, struct page * page)
```

```json
{
  "name": "md_super_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586356317,
      "name": "md_super_write",
      "external": true,
      "loc": "drivers/md/md.c:744",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:super_1_rdev_size_change"
      ],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586339872,
      "name": "md_super_write.part.53",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    },
    {
      "addr": 18446744071586349008,
      "name": "md_super_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void md_super_write(struct mddev * mddev, struct md_rdev * rdev, sector_t sector, int size, struct page * page)
```

```json
{
  "name": "md_super_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586456767,
      "name": "md_super_write",
      "external": true,
      "loc": "drivers/md/md.c:756",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:super_1_rdev_size_change"
      ],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586438592,
      "name": "md_super_write.part.55",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071586449424,
      "name": "md_super_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void md_super_write(struct mddev * mddev, struct md_rdev * rdev, sector_t sector, int size, struct page * page)
```

```json
{
  "name": "md_super_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586923983,
      "name": "md_super_write",
      "external": true,
      "loc": "drivers/md/md.c:791",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:super_1_rdev_size_change"
      ],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586904496,
      "name": "md_super_write.part.58",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
    },
    {
      "addr": 18446744071586916576,
      "name": "md_super_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void md_super_write(struct mddev * mddev, struct md_rdev * rdev, sector_t sector, int size, struct page * page)
```

```json
{
  "name": "md_super_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587208327,
      "name": "md_super_write",
      "external": true,
      "loc": "drivers/md/md.c:803",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:super_1_rdev_size_change"
      ],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587185184,
      "name": "md_super_write.part.62",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
    },
    {
      "addr": 18446744071587207840,
      "name": "md_super_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void md_super_write(struct mddev * mddev, struct md_rdev * rdev, sector_t sector, int size, struct page * page)
```

```json
{
  "name": "md_super_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587388663,
      "name": "md_super_write",
      "external": true,
      "loc": "drivers/md/md.c:796",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:super_1_rdev_size_change"
      ],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587365376,
      "name": "md_super_write.part.62",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
    },
    {
      "addr": 18446744071587388176,
      "name": "md_super_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void md_super_write(struct mddev * mddev, struct md_rdev * rdev, sector_t sector, int size, struct page * page)
```

```json
{
  "name": "md_super_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587660058,
      "name": "md_super_write",
      "external": true,
      "loc": "drivers/md/md.c:857",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change"
      ],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587636928,
      "name": "md_super_write.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    },
    {
      "addr": 18446744071587659568,
      "name": "md_super_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void md_super_write(struct mddev * mddev, struct md_rdev * rdev, sector_t sector, int size, struct page * page)
```

```json
{
  "name": "md_super_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587864234,
      "name": "md_super_write",
      "external": true,
      "loc": "drivers/md/md.c:869",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change"
      ],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587840752,
      "name": "md_super_write.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    },
    {
      "addr": 18446744071587863744,
      "name": "md_super_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void md_super_write(struct mddev * mddev, struct md_rdev * rdev, sector_t sector, int size, struct page * page)
```

```json
{
  "name": "md_super_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588715325,
      "name": "md_super_write",
      "external": true,
      "loc": "drivers/md/md.c:995",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change"
      ],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change",
        "drivers/md/md-bitmap.c:write_sb_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588686304,
      "name": "md_super_write.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    },
    {
      "addr": 18446744071588714832,
      "name": "md_super_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void md_super_write(struct mddev * mddev, struct md_rdev * rdev, sector_t sector, int size, struct page * page)
```

```json
{
  "name": "md_super_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588742842,
      "name": "md_super_write",
      "external": true,
      "loc": "drivers/md/md.c:984",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change"
      ],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change",
        "drivers/md/md-bitmap.c:write_sb_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588713056,
      "name": "md_super_write.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
    },
    {
      "addr": 18446744071588742352,
      "name": "md_super_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void md_super_write(struct mddev * mddev, struct md_rdev * rdev, sector_t sector, int size, struct page * page)
```

```json
{
  "name": "md_super_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588627988,
      "name": "md_super_write",
      "external": true,
      "loc": "drivers/md/md.c:943",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change"
      ],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change",
        "drivers/md/md-bitmap.c:write_sb_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588594368,
      "name": "md_super_write.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
    },
    {
      "addr": 18446744071588627488,
      "name": "md_super_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void md_super_write(struct mddev * mddev, struct md_rdev * rdev, sector_t sector, int size, struct page * page)
```

```json
{
  "name": "md_super_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589305359,
      "name": "md_super_write",
      "external": true,
      "loc": "drivers/md/md.c:944",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change"
      ],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change",
        "drivers/md/md-bitmap.c:write_sb_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589271136,
      "name": "md_super_write.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
    },
    {
      "addr": 18446744071589304864,
      "name": "md_super_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void md_super_write(struct mddev * mddev, struct md_rdev * rdev, sector_t sector, int size, struct page * page)
```

```json
{
  "name": "md_super_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590777239,
      "name": "md_super_write",
      "external": true,
      "loc": "drivers/md/md.c:948",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change"
      ],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change",
        "drivers/md/md-bitmap.c:write_sb_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590752944,
      "name": "md_super_write.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    },
    {
      "addr": 18446744071590776672,
      "name": "md_super_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void md_super_write(struct mddev * mddev, struct md_rdev * rdev, sector_t sector, int size, struct page * page)
```

```json
{
  "name": "md_super_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592457280,
      "name": "md_super_write",
      "external": true,
      "loc": "drivers/md/md.c:939",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change",
        "drivers/md/md-bitmap.c:write_sb_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592457280,
      "name": "md_super_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
void md_super_write(struct mddev * mddev, struct md_rdev * rdev, sector_t sector, int size, struct page * page)
```

```json
{
  "name": "md_super_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592879616,
      "name": "md_super_write",
      "external": true,
      "loc": "drivers/md/md.c:915",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change",
        "drivers/md/md-bitmap.c:__write_sb_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592879616,
      "name": "md_super_write",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void md_super_write(struct mddev * mddev, struct md_rdev * rdev, sector_t sector, int size, struct page * page)
```

```json
{
  "name": "md_super_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593629008,
      "name": "md_super_write",
      "external": true,
      "loc": "drivers/md/md.c:1026",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change",
        "drivers/md/md-bitmap.c:__write_sb_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593629008,
      "name": "md_super_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void md_super_write(struct mddev * mddev, struct md_rdev * rdev, sector_t sector, int size, struct page * page)
```

```json
{
  "name": "md_super_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501092812,
      "name": "md_super_write",
      "external": true,
      "loc": "drivers/md/md.c:869",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change"
      ],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501073456,
      "name": "md_super_write.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
    },
    {
      "addr": 18446603336501092160,
      "name": "md_super_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void md_super_write(struct mddev * mddev, struct md_rdev * rdev, sector_t sector, int size, struct page * page)
```

```json
{
  "name": "md_super_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233608788,
      "name": "md_super_write",
      "external": true,
      "loc": "drivers/md/md.c:869",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:super_1_rdev_size_change"
      ],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233586816,
      "name": "md_super_write.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
    },
    {
      "addr": 3233608100,
      "name": "md_super_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void md_super_write(struct mddev * mddev, struct md_rdev * rdev, sector_t sector, int size, struct page * page)
```

```json
{
  "name": "md_super_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294588148,
      "name": "md_super_write",
      "external": true,
      "loc": "drivers/md/md.c:869",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change"
      ],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294567808,
      "name": "md_super_write.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
    },
    {
      "addr": 13835058055294587456,
      "name": "md_super_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void md_super_write(struct mddev * mddev, struct md_rdev * rdev, sector_t sector, int size, struct page * page)
```

```json
{
  "name": "md_super_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277817496,
      "name": "md_super_write",
      "external": true,
      "loc": "drivers/md/md.c:869",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change"
      ],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277793346,
      "name": "md_super_write.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
    },
    {
      "addr": 18446743936277817062,
      "name": "md_super_write",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void md_super_write(struct mddev * mddev, struct md_rdev * rdev, sector_t sector, int size, struct page * page)
```

```json
{
  "name": "md_super_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587495210,
      "name": "md_super_write",
      "external": true,
      "loc": "drivers/md/md.c:869",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change"
      ],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587471728,
      "name": "md_super_write.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    },
    {
      "addr": 18446744071587494720,
      "name": "md_super_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void md_super_write(struct mddev * mddev, struct md_rdev * rdev, sector_t sector, int size, struct page * page)
```

```json
{
  "name": "md_super_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587263370,
      "name": "md_super_write",
      "external": true,
      "loc": "drivers/md/md.c:869",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change"
      ],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587239904,
      "name": "md_super_write.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    },
    {
      "addr": 18446744071587262880,
      "name": "md_super_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void md_super_write(struct mddev * mddev, struct md_rdev * rdev, sector_t sector, int size, struct page * page)
```

```json
{
  "name": "md_super_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587820378,
      "name": "md_super_write",
      "external": true,
      "loc": "drivers/md/md.c:869",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change"
      ],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587796896,
      "name": "md_super_write.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    },
    {
      "addr": 18446744071587819888,
      "name": "md_super_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void md_super_write(struct mddev * mddev, struct md_rdev * rdev, sector_t sector, int size, struct page * page)
```

```json
{
  "name": "md_super_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587934026,
      "name": "md_super_write",
      "external": true,
      "loc": "drivers/md/md.c:869",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change"
      ],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587921904,
      "name": "md_super_write.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    },
    {
      "addr": 18446744071587933552,
      "name": "md_super_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
