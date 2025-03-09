# Function: <code>md_bitmap_update_sb</code>

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
void md_bitmap_update_sb(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_update_sb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587423696,
      "name": "md_bitmap_update_sb",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:446",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587423696,
      "name": "md_bitmap_update_sb",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void md_bitmap_update_sb(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_update_sb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587695328,
      "name": "md_bitmap_update_sb",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:447",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587695328,
      "name": "md_bitmap_update_sb",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void md_bitmap_update_sb(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_update_sb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587899600,
      "name": "md_bitmap_update_sb",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:447",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587899600,
      "name": "md_bitmap_update_sb",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void md_bitmap_update_sb(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_update_sb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588757672,
      "name": "md_bitmap_update_sb",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:443",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_flush"
      ],
      "caller_func": [
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588757072,
      "name": "md_bitmap_update_sb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
    },
    {
      "addr": 18446744071588757328,
      "name": "md_bitmap_update_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void md_bitmap_update_sb(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_update_sb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588777896,
      "name": "md_bitmap_update_sb",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:444",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_flush"
      ],
      "caller_func": [
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588777296,
      "name": "md_bitmap_update_sb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
    },
    {
      "addr": 18446744071588777552,
      "name": "md_bitmap_update_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void md_bitmap_update_sb(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_update_sb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588660536,
      "name": "md_bitmap_update_sb",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:444",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_flush"
      ],
      "caller_func": [
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588659776,
      "name": "md_bitmap_update_sb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
    },
    {
      "addr": 18446744071588660032,
      "name": "md_bitmap_update_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void md_bitmap_update_sb(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_update_sb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589338440,
      "name": "md_bitmap_update_sb",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:444",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_flush"
      ],
      "caller_func": [
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589337680,
      "name": "md_bitmap_update_sb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
    },
    {
      "addr": 18446744071589337936,
      "name": "md_bitmap_update_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void md_bitmap_update_sb(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_update_sb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590814542,
      "name": "md_bitmap_update_sb",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:444",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_flush"
      ],
      "caller_func": [
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590812032,
      "name": "md_bitmap_update_sb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
    },
    {
      "addr": 18446744071590812352,
      "name": "md_bitmap_update_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void md_bitmap_update_sb(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_update_sb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592499854,
      "name": "md_bitmap_update_sb",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:444",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_flush"
      ],
      "caller_func": [
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592499248,
      "name": "md_bitmap_update_sb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
    },
    {
      "addr": 18446744071592499584,
      "name": "md_bitmap_update_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void md_bitmap_update_sb(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_update_sb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592934095,
      "name": "md_bitmap_update_sb",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:460",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_flush"
      ],
      "caller_func": [
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592929760,
      "name": "md_bitmap_update_sb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
    },
    {
      "addr": 18446744071592930096,
      "name": "md_bitmap_update_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void md_bitmap_update_sb(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_update_sb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593679607,
      "name": "md_bitmap_update_sb",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:474",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_flush"
      ],
      "caller_func": [
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593676960,
      "name": "md_bitmap_update_sb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
    },
    {
      "addr": 18446744071593677344,
      "name": "md_bitmap_update_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void md_bitmap_update_sb(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_update_sb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501135576,
      "name": "md_bitmap_update_sb",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:447",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501135576,
      "name": "md_bitmap_update_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void md_bitmap_update_sb(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_update_sb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233645388,
      "name": "md_bitmap_update_sb",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:447",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233645388,
      "name": "md_bitmap_update_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void md_bitmap_update_sb(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_update_sb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294632288,
      "name": "md_bitmap_update_sb",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:447",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294632288,
      "name": "md_bitmap_update_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
void md_bitmap_update_sb(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_update_sb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277845040,
      "name": "md_bitmap_update_sb",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:447",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277845040,
      "name": "md_bitmap_update_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void md_bitmap_update_sb(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_update_sb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587530576,
      "name": "md_bitmap_update_sb",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:447",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587530576,
      "name": "md_bitmap_update_sb",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void md_bitmap_update_sb(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_update_sb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587298736,
      "name": "md_bitmap_update_sb",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:447",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587298736,
      "name": "md_bitmap_update_sb",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void md_bitmap_update_sb(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_update_sb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587855744,
      "name": "md_bitmap_update_sb",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:447",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587855744,
      "name": "md_bitmap_update_sb",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void md_bitmap_update_sb(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_update_sb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587970896,
      "name": "md_bitmap_update_sb",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:447",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587970896,
      "name": "md_bitmap_update_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
void md_bitmap_update_sb(struct bitmap * bitmap)
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
