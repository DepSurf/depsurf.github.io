# Function: <code>md_bitmap_unplug</code>

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
void md_bitmap_unplug(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_unplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587425184,
      "name": "md_bitmap_unplug",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1008",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587425184,
      "name": "md_bitmap_unplug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
void md_bitmap_unplug(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_unplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587697072,
      "name": "md_bitmap_unplug",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1009",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587697072,
      "name": "md_bitmap_unplug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void md_bitmap_unplug(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_unplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587901344,
      "name": "md_bitmap_unplug",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1009",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587901344,
      "name": "md_bitmap_unplug",
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
void md_bitmap_unplug(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_unplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588759726,
      "name": "md_bitmap_unplug",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1005",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot"
      ],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588757824,
      "name": "md_bitmap_unplug.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
    },
    {
      "addr": 18446744071588758096,
      "name": "md_bitmap_unplug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void md_bitmap_unplug(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_unplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588779948,
      "name": "md_bitmap_unplug",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1006",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot"
      ],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588778048,
      "name": "md_bitmap_unplug.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
    },
    {
      "addr": 18446744071588778320,
      "name": "md_bitmap_unplug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void md_bitmap_unplug(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_unplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588666848,
      "name": "md_bitmap_unplug",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1006",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot"
      ],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588660080,
      "name": "md_bitmap_unplug.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
    },
    {
      "addr": 18446744071588660352,
      "name": "md_bitmap_unplug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void md_bitmap_unplug(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_unplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589345035,
      "name": "md_bitmap_unplug",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1006",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot"
      ],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589337984,
      "name": "md_bitmap_unplug.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
    },
    {
      "addr": 18446744071589338256,
      "name": "md_bitmap_unplug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void md_bitmap_unplug(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_unplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590818801,
      "name": "md_bitmap_unplug",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1007",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot"
      ],
      "caller_func": [
        "drivers/md/md.c:bitmap_store",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590812416,
      "name": "md_bitmap_unplug.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
    },
    {
      "addr": 18446744071590812704,
      "name": "md_bitmap_unplug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void md_bitmap_unplug(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_unplug",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592501408,
      "name": "md_bitmap_unplug",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1007",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:bitmap_store",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592501408,
      "name": "md_bitmap_unplug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
void md_bitmap_unplug(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_unplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592931520,
      "name": "md_bitmap_unplug",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1022",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:bitmap_store",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_unplug_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592931520,
      "name": "md_bitmap_unplug.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    },
    {
      "addr": 18446744071592931840,
      "name": "md_bitmap_unplug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void md_bitmap_unplug(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_unplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593681664,
      "name": "md_bitmap_unplug",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1028",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:bitmap_store",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_unplug_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593681664,
      "name": "md_bitmap_unplug.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
    },
    {
      "addr": 18446744071593682144,
      "name": "md_bitmap_unplug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void md_bitmap_unplug(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_unplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501136504,
      "name": "md_bitmap_unplug",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1009",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501136504,
      "name": "md_bitmap_unplug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
void md_bitmap_unplug(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_unplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233648364,
      "name": "md_bitmap_unplug",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1009",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233648364,
      "name": "md_bitmap_unplug",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void md_bitmap_unplug(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_unplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294634560,
      "name": "md_bitmap_unplug",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1009",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294634560,
      "name": "md_bitmap_unplug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 612
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
void md_bitmap_unplug(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_unplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277846424,
      "name": "md_bitmap_unplug",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1009",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277846424,
      "name": "md_bitmap_unplug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
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
void md_bitmap_unplug(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_unplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587532320,
      "name": "md_bitmap_unplug",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1009",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587532320,
      "name": "md_bitmap_unplug",
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
void md_bitmap_unplug(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_unplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587300480,
      "name": "md_bitmap_unplug",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1009",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587300480,
      "name": "md_bitmap_unplug",
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
void md_bitmap_unplug(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_unplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587857488,
      "name": "md_bitmap_unplug",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1009",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587857488,
      "name": "md_bitmap_unplug",
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
void md_bitmap_unplug(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_unplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587976624,
      "name": "md_bitmap_unplug",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1009",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587976624,
      "name": "md_bitmap_unplug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
void md_bitmap_unplug(struct bitmap * bitmap)
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
