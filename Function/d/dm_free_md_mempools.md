# Function: <code>dm_free_md_mempools</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void dm_free_md_mempools(struct dm_md_mempools * pools)
```

```json
{
  "name": "dm_free_md_mempools",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585810928,
      "name": "dm_free_md_mempools",
      "external": true,
      "loc": "drivers/md/dm.c:3542",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm-table.c:dm_table_destroy",
        "drivers/md/dm-table.c:dm_table_free_md_mempools"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585810928,
      "name": "dm_free_md_mempools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void dm_free_md_mempools(struct dm_md_mempools * pools)
```

```json
{
  "name": "dm_free_md_mempools",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586204576,
      "name": "dm_free_md_mempools",
      "external": true,
      "loc": "drivers/md/dm.c:2543",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm-table.c:dm_table_free_md_mempools",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586204576,
      "name": "dm_free_md_mempools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void dm_free_md_mempools(struct dm_md_mempools * pools)
```

```json
{
  "name": "dm_free_md_mempools",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586409040,
      "name": "dm_free_md_mempools",
      "external": true,
      "loc": "drivers/md/dm.c:2603",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm-table.c:dm_table_free_md_mempools",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586409040,
      "name": "dm_free_md_mempools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void dm_free_md_mempools(struct dm_md_mempools * pools)
```

```json
{
  "name": "dm_free_md_mempools",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586512682,
      "name": "dm_free_md_mempools",
      "external": true,
      "loc": "drivers/md/dm.c:2804",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm-table.c:dm_table_free_md_mempools",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586505440,
      "name": "dm_free_md_mempools.part.33",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071586512800,
      "name": "dm_free_md_mempools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void dm_free_md_mempools(struct dm_md_mempools * pools)
```

```json
{
  "name": "dm_free_md_mempools",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586980103,
      "name": "dm_free_md_mempools",
      "external": true,
      "loc": "drivers/md/dm.c:2783",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm-table.c:dm_table_free_md_mempools",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586972432,
      "name": "dm_free_md_mempools.part.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071586980224,
      "name": "dm_free_md_mempools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dm_free_md_mempools(struct dm_md_mempools * pools)
```

```json
{
  "name": "dm_free_md_mempools",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587276992,
      "name": "dm_free_md_mempools",
      "external": true,
      "loc": "drivers/md/dm.c:2977",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_free_md_mempools",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587277136,
      "name": "dm_free_md_mempools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dm_free_md_mempools(struct dm_md_mempools * pools)
```

```json
{
  "name": "dm_free_md_mempools",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587457258,
      "name": "dm_free_md_mempools",
      "external": true,
      "loc": "drivers/md/dm.c:2999",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_free_md_mempools",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587457360,
      "name": "dm_free_md_mempools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void dm_free_md_mempools(struct dm_md_mempools * pools)
```

```json
{
  "name": "dm_free_md_mempools",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587730589,
      "name": "dm_free_md_mempools",
      "external": true,
      "loc": "drivers/md/dm.c:3030",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_free_md_mempools",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587730688,
      "name": "dm_free_md_mempools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void dm_free_md_mempools(struct dm_md_mempools * pools)
```

```json
{
  "name": "dm_free_md_mempools",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587934941,
      "name": "dm_free_md_mempools",
      "external": true,
      "loc": "drivers/md/dm.c:3035",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_free_md_mempools",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587935040,
      "name": "dm_free_md_mempools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void dm_free_md_mempools(struct dm_md_mempools * pools)
```

```json
{
  "name": "dm_free_md_mempools",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588787370,
      "name": "dm_free_md_mempools",
      "external": true,
      "loc": "drivers/md/dm.c:3098",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_free_md_mempools",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588787472,
      "name": "dm_free_md_mempools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void dm_free_md_mempools(struct dm_md_mempools * pools)
```

```json
{
  "name": "dm_free_md_mempools",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588805696,
      "name": "dm_free_md_mempools",
      "external": true,
      "loc": "drivers/md/dm.c:2944",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_free_md_mempools",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588805920,
      "name": "dm_free_md_mempools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void dm_free_md_mempools(struct dm_md_mempools * pools)
```

```json
{
  "name": "dm_free_md_mempools",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588691400,
      "name": "dm_free_md_mempools",
      "external": true,
      "loc": "drivers/md/dm.c:2963",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_free_md_mempools",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588691616,
      "name": "dm_free_md_mempools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void dm_free_md_mempools(struct dm_md_mempools * pools)
```

```json
{
  "name": "dm_free_md_mempools",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589379448,
      "name": "dm_free_md_mempools",
      "external": true,
      "loc": "drivers/md/dm.c:2852",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_free_md_mempools",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589379664,
      "name": "dm_free_md_mempools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dm_free_md_mempools(struct dm_md_mempools * pools)
```

```json
{
  "name": "dm_free_md_mempools",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590855419,
      "name": "dm_free_md_mempools",
      "external": true,
      "loc": "drivers/md/dm.c:3033",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:__bind",
        "drivers/md/dm.c:__bind",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:cleanup_mapped_device"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590855536,
      "name": "dm_free_md_mempools",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dm_free_md_mempools(struct dm_md_mempools * pools)
```

```json
{
  "name": "dm_free_md_mempools",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592530185,
      "name": "dm_free_md_mempools",
      "external": true,
      "loc": "drivers/md/dm.c:3090",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__bind",
        "drivers/md/dm.c:__bind",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:cleanup_mapped_device"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_alloc_md_mempools",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592546784,
      "name": "dm_free_md_mempools",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dm_free_md_mempools(struct dm_md_mempools * pools)
```

```json
{
  "name": "dm_free_md_mempools",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592959689,
      "name": "dm_free_md_mempools",
      "external": true,
      "loc": "drivers/md/dm.c:3133",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__bind",
        "drivers/md/dm.c:__bind",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:cleanup_mapped_device"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_alloc_md_mempools",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592978032,
      "name": "dm_free_md_mempools",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dm_free_md_mempools(struct dm_md_mempools * pools)
```

```json
{
  "name": "dm_free_md_mempools",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593709817,
      "name": "dm_free_md_mempools",
      "external": true,
      "loc": "drivers/md/dm.c:3141",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__bind",
        "drivers/md/dm.c:__bind",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:cleanup_mapped_device"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_alloc_md_mempools",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593728016,
      "name": "dm_free_md_mempools",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void dm_free_md_mempools(struct dm_md_mempools * pools)
```

```json
{
  "name": "dm_free_md_mempools",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501171676,
      "name": "dm_free_md_mempools",
      "external": true,
      "loc": "drivers/md/dm.c:3035",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_free_md_mempools",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501171808,
      "name": "dm_free_md_mempools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void dm_free_md_mempools(struct dm_md_mempools * pools)
```

```json
{
  "name": "dm_free_md_mempools",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233680668,
      "name": "dm_free_md_mempools",
      "external": true,
      "loc": "drivers/md/dm.c:3035",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_free_md_mempools",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233680764,
      "name": "dm_free_md_mempools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void dm_free_md_mempools(struct dm_md_mempools * pools)
```

```json
{
  "name": "dm_free_md_mempools",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294683520,
      "name": "dm_free_md_mempools",
      "external": true,
      "loc": "drivers/md/dm.c:3035",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_free_md_mempools",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294683696,
      "name": "dm_free_md_mempools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void dm_free_md_mempools(struct dm_md_mempools * pools)
```

```json
{
  "name": "dm_free_md_mempools",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277878134,
      "name": "dm_free_md_mempools",
      "external": true,
      "loc": "drivers/md/dm.c:3035",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_free_md_mempools",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277878222,
      "name": "dm_free_md_mempools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void dm_free_md_mempools(struct dm_md_mempools * pools)
```

```json
{
  "name": "dm_free_md_mempools",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587565917,
      "name": "dm_free_md_mempools",
      "external": true,
      "loc": "drivers/md/dm.c:3035",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_free_md_mempools",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587566016,
      "name": "dm_free_md_mempools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void dm_free_md_mempools(struct dm_md_mempools * pools)
```

```json
{
  "name": "dm_free_md_mempools",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587333997,
      "name": "dm_free_md_mempools",
      "external": true,
      "loc": "drivers/md/dm.c:3035",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_free_md_mempools",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587334096,
      "name": "dm_free_md_mempools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void dm_free_md_mempools(struct dm_md_mempools * pools)
```

```json
{
  "name": "dm_free_md_mempools",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587891085,
      "name": "dm_free_md_mempools",
      "external": true,
      "loc": "drivers/md/dm.c:3035",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_free_md_mempools",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587891184,
      "name": "dm_free_md_mempools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void dm_free_md_mempools(struct dm_md_mempools * pools)
```

```json
{
  "name": "dm_free_md_mempools",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588006349,
      "name": "dm_free_md_mempools",
      "external": true,
      "loc": "drivers/md/dm.c:3035",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_free_md_mempools",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588006448,
      "name": "dm_free_md_mempools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
