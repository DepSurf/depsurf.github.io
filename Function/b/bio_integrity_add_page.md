# Function: <code>bio_integrity_add_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int bio_integrity_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_integrity_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582937536,
      "name": "bio_integrity_add_page",
      "external": true,
      "loc": "block/bio-integrity.c:135",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio-integrity.c:bio_integrity_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582937536,
      "name": "bio_integrity_add_page",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int bio_integrity_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_integrity_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583224896,
      "name": "bio_integrity_add_page",
      "external": true,
      "loc": "block/bio-integrity.c:135",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio-integrity.c:bio_integrity_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583224896,
      "name": "bio_integrity_add_page",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int bio_integrity_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_integrity_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583330848,
      "name": "bio_integrity_add_page",
      "external": true,
      "loc": "block/bio-integrity.c:135",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio-integrity.c:bio_integrity_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583330848,
      "name": "bio_integrity_add_page",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int bio_integrity_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_integrity_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583389280,
      "name": "bio_integrity_add_page",
      "external": true,
      "loc": "block/bio-integrity.c:135",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio-integrity.c:bio_integrity_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583389280,
      "name": "bio_integrity_add_page",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int bio_integrity_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_integrity_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583568608,
      "name": "bio_integrity_add_page",
      "external": true,
      "loc": "block/bio-integrity.c:135",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio-integrity.c:bio_integrity_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583568608,
      "name": "bio_integrity_add_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int bio_integrity_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_integrity_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bio_integrity_add_page",
      "external": true,
      "loc": "block/bio-integrity.c:135",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio-integrity.c:bio_integrity_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583787148,
      "name": "bio_integrity_add_page.cold.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071583784704,
      "name": "bio_integrity_add_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int bio_integrity_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_integrity_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bio_integrity_add_page",
      "external": true,
      "loc": "block/bio-integrity.c:135",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio-integrity.c:bio_integrity_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583867032,
      "name": "bio_integrity_add_page.cold.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071583864768,
      "name": "bio_integrity_add_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int bio_integrity_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_integrity_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bio_integrity_add_page",
      "external": true,
      "loc": "block/bio-integrity.c:120",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio-integrity.c:bio_integrity_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584057688,
      "name": "bio_integrity_add_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071584054992,
      "name": "bio_integrity_add_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int bio_integrity_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_integrity_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bio_integrity_add_page",
      "external": true,
      "loc": "block/bio-integrity.c:120",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio-integrity.c:bio_integrity_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584180200,
      "name": "bio_integrity_add_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071584177504,
      "name": "bio_integrity_add_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int bio_integrity_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_integrity_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bio_integrity_add_page",
      "external": true,
      "loc": "block/bio-integrity.c:129",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio-integrity.c:bio_integrity_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584575323,
      "name": "bio_integrity_add_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071584572608,
      "name": "bio_integrity_add_page",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int bio_integrity_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_integrity_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bio_integrity_add_page",
      "external": true,
      "loc": "block/bio-integrity.c:129",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio-integrity.c:bio_integrity_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591378018,
      "name": "bio_integrity_add_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071584691200,
      "name": "bio_integrity_add_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int bio_integrity_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_integrity_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bio_integrity_add_page",
      "external": true,
      "loc": "block/bio-integrity.c:124",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio-integrity.c:bio_integrity_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591320260,
      "name": "bio_integrity_add_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071584719376,
      "name": "bio_integrity_add_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int bio_integrity_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_integrity_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bio_integrity_add_page",
      "external": true,
      "loc": "block/bio-integrity.c:123",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio-integrity.c:bio_integrity_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592320960,
      "name": "bio_integrity_add_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071585145248,
      "name": "bio_integrity_add_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int bio_integrity_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_integrity_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bio_integrity_add_page",
      "external": true,
      "loc": "block/bio-integrity.c:123",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio-integrity.c:bio_integrity_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594105514,
      "name": "bio_integrity_add_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585877312,
      "name": "bio_integrity_add_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int bio_integrity_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_integrity_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586662432,
      "name": "bio_integrity_add_page",
      "external": true,
      "loc": "block/bio-integrity.c:123",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio-integrity.c:bio_integrity_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586662432,
      "name": "bio_integrity_add_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int bio_integrity_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_integrity_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586923664,
      "name": "bio_integrity_add_page",
      "external": true,
      "loc": "block/bio-integrity.c:123",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio-integrity.c:bio_integrity_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586923664,
      "name": "bio_integrity_add_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
int bio_integrity_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_integrity_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587202784,
      "name": "bio_integrity_add_page",
      "external": true,
      "loc": "block/bio-integrity.c:166",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio-integrity.c:bio_integrity_prep",
        "block/bio-integrity.c:bio_integrity_copy_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587202784,
      "name": "bio_integrity_add_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
int bio_integrity_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_integrity_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496041672,
      "name": "bio_integrity_add_page",
      "external": true,
      "loc": "block/bio-integrity.c:120",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio-integrity.c:bio_integrity_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496041672,
      "name": "bio_integrity_add_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int bio_integrity_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_integrity_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229371176,
      "name": "bio_integrity_add_page",
      "external": true,
      "loc": "block/bio-integrity.c:120",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio-integrity.c:bio_integrity_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229371176,
      "name": "bio_integrity_add_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int bio_integrity_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_integrity_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290272496,
      "name": "bio_integrity_add_page",
      "external": true,
      "loc": "block/bio-integrity.c:120",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio-integrity.c:bio_integrity_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290272496,
      "name": "bio_integrity_add_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int bio_integrity_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_integrity_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275119522,
      "name": "bio_integrity_add_page",
      "external": true,
      "loc": "block/bio-integrity.c:120",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio-integrity.c:bio_integrity_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275119522,
      "name": "bio_integrity_add_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int bio_integrity_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_integrity_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bio_integrity_add_page",
      "external": true,
      "loc": "block/bio-integrity.c:120",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio-integrity.c:bio_integrity_prep",
        "drivers/nvme/host/core.c:nvme_submit_user_cmd",
        "drivers/nvme/host/core.c:nvme_submit_user_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584148936,
      "name": "bio_integrity_add_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071584146240,
      "name": "bio_integrity_add_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int bio_integrity_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_integrity_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bio_integrity_add_page",
      "external": true,
      "loc": "block/bio-integrity.c:120",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio-integrity.c:bio_integrity_prep",
        "drivers/nvme/host/core.c:nvme_submit_user_cmd",
        "drivers/nvme/host/core.c:nvme_submit_user_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584084472,
      "name": "bio_integrity_add_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071584081776,
      "name": "bio_integrity_add_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int bio_integrity_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_integrity_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bio_integrity_add_page",
      "external": true,
      "loc": "block/bio-integrity.c:120",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio-integrity.c:bio_integrity_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584132696,
      "name": "bio_integrity_add_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071584130000,
      "name": "bio_integrity_add_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int bio_integrity_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_integrity_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bio_integrity_add_page",
      "external": true,
      "loc": "block/bio-integrity.c:120",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio-integrity.c:bio_integrity_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584236792,
      "name": "bio_integrity_add_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071584234048,
      "name": "bio_integrity_add_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
