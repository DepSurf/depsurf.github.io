# Function: <code>memblock_insert_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void memblock_insert_region(struct memblock_type * type, int idx, phys_addr_t base, phys_addr_t size, int nid, long unsigned int flags)
```

```json
{
  "name": "memblock_insert_region",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587354894,
      "name": "memblock_insert_region",
      "external": false,
      "loc": "mm/memblock.c:491",
      "file": "mm/memblock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_add_range",
        "mm/memblock.c:memblock_add_range",
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_isolate_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587354894,
      "name": "memblock_insert_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void memblock_insert_region(struct memblock_type * type, int idx, phys_addr_t base, phys_addr_t size, int nid, long unsigned int flags)
```

```json
{
  "name": "memblock_insert_region",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587855674,
      "name": "memblock_insert_region",
      "external": false,
      "loc": "mm/memblock.c:487",
      "file": "mm/memblock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_add_range",
        "mm/memblock.c:memblock_add_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587855674,
      "name": "memblock_insert_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void memblock_insert_region(struct memblock_type * type, int idx, phys_addr_t base, phys_addr_t size, int nid, long unsigned int flags)
```

```json
{
  "name": "memblock_insert_region",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588070361,
      "name": "memblock_insert_region",
      "external": false,
      "loc": "mm/memblock.c:487",
      "file": "mm/memblock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_add_range",
        "mm/memblock.c:memblock_add_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588070361,
      "name": "memblock_insert_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void memblock_insert_region(struct memblock_type * type, int idx, phys_addr_t base, phys_addr_t size, int nid, long unsigned int flags)
```

```json
{
  "name": "memblock_insert_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588297112,
      "name": "memblock_insert_region",
      "external": false,
      "loc": "mm/memblock.c:471",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_add_range",
        "mm/memblock.c:memblock_add_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588297112,
      "name": "memblock_insert_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void memblock_insert_region(struct memblock_type * type, int idx, phys_addr_t base, phys_addr_t size, int nid, long unsigned int flags)
```

```json
{
  "name": "memblock_insert_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588862371,
      "name": "memblock_insert_region",
      "external": false,
      "loc": "mm/memblock.c:471",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_add_range",
        "mm/memblock.c:memblock_add_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588862371,
      "name": "memblock_insert_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void memblock_insert_region(struct memblock_type * type, int idx, phys_addr_t base, phys_addr_t size, int nid, long unsigned int flags)
```

```json
{
  "name": "memblock_insert_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589241437,
      "name": "memblock_insert_region",
      "external": false,
      "loc": "mm/memblock.c:474",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_add_range",
        "mm/memblock.c:memblock_add_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589241437,
      "name": "memblock_insert_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void memblock_insert_region(struct memblock_type * type, int idx, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags)
```

```json
{
  "name": "memblock_insert_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589483737,
      "name": "memblock_insert_region",
      "external": false,
      "loc": "mm/memblock.c:551",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_add_range",
        "mm/memblock.c:memblock_add_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589483737,
      "name": "memblock_insert_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void memblock_insert_region(struct memblock_type * type, int idx, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags)
```

```json
{
  "name": "memblock_insert_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589944340,
      "name": "memblock_insert_region",
      "external": false,
      "loc": "mm/memblock.c:548",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_add_range",
        "mm/memblock.c:memblock_add_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589944340,
      "name": "memblock_insert_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void memblock_insert_region(struct memblock_type * type, int idx, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags)
```

```json
{
  "name": "memblock_insert_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590171883,
      "name": "memblock_insert_region",
      "external": false,
      "loc": "mm/memblock.c:548",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_add_range",
        "mm/memblock.c:memblock_add_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590171883,
      "name": "memblock_insert_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void memblock_insert_region(struct memblock_type * type, int idx, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags)
```

```json
{
  "name": "memblock_insert_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591190304,
      "name": "memblock_insert_region",
      "external": false,
      "loc": "mm/memblock.c:544",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_isolate_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591190304,
      "name": "memblock_insert_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void memblock_insert_region(struct memblock_type * type, int idx, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags)
```

```json
{
  "name": "memblock_insert_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591685760,
      "name": "memblock_insert_region",
      "external": false,
      "loc": "mm/memblock.c:531",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_isolate_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591685760,
      "name": "memblock_insert_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void memblock_insert_region(struct memblock_type * type, int idx, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags)
```

```json
{
  "name": "memblock_insert_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591628623,
      "name": "memblock_insert_region",
      "external": false,
      "loc": "mm/memblock.c:531",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_isolate_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591628623,
      "name": "memblock_insert_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void memblock_insert_region(struct memblock_type * type, int idx, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags)
```

```json
{
  "name": "memblock_insert_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592802415,
      "name": "memblock_insert_region",
      "external": false,
      "loc": "mm/memblock.c:539",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_isolate_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592802415,
      "name": "memblock_insert_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void memblock_insert_region(struct memblock_type * type, int idx, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags)
```

```json
{
  "name": "memblock_insert_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594702718,
      "name": "memblock_insert_region",
      "external": false,
      "loc": "mm/memblock.c:539",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_add_range",
        "mm/memblock.c:memblock_add_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594702718,
      "name": "memblock_insert_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
void memblock_insert_region(struct memblock_type * type, int idx, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags)
```

```json
{
  "name": "memblock_insert_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596444368,
      "name": "memblock_insert_region",
      "external": false,
      "loc": "mm/memblock.c:543",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_add_range",
        "mm/memblock.c:memblock_add_range",
        "mm/memblock.c:memblock_add_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596444368,
      "name": "memblock_insert_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
void memblock_insert_region(struct memblock_type * type, int idx, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags)
```

```json
{
  "name": "memblock_insert_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596985680,
      "name": "memblock_insert_region",
      "external": false,
      "loc": "mm/memblock.c:548",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_add_range",
        "mm/memblock.c:memblock_add_range",
        "mm/memblock.c:memblock_add_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596985680,
      "name": "memblock_insert_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
void memblock_insert_region(struct memblock_type * type, int idx, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags)
```

```json
{
  "name": "memblock_insert_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597914208,
      "name": "memblock_insert_region",
      "external": false,
      "loc": "mm/memblock.c:554",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_add_range",
        "mm/memblock.c:memblock_add_range",
        "mm/memblock.c:memblock_add_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597914208,
      "name": "memblock_insert_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
void memblock_insert_region(struct memblock_type * type, int idx, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags)
```

```json
{
  "name": "memblock_insert_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492889144,
      "name": "memblock_insert_region",
      "external": false,
      "loc": "mm/memblock.c:548",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_add_range",
        "mm/memblock.c:memblock_add_range",
        "mm/memblock.c:memblock_add_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492889144,
      "name": "memblock_insert_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "memblock_insert_region",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226687024,
      "name": "memblock_insert_region",
      "external": false,
      "loc": "mm/memblock.c:548",
      "file": "mm/memblock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_add_range",
        "mm/memblock.c:memblock_add_range",
        "mm/memblock.c:memblock_add_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226687024,
      "name": "memblock_insert_region.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void memblock_insert_region(struct memblock_type * type, int idx, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags)
```

```json
{
  "name": "memblock_insert_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286287584,
      "name": "memblock_insert_region",
      "external": false,
      "loc": "mm/memblock.c:548",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_add_range",
        "mm/memblock.c:memblock_add_range",
        "mm/memblock.c:memblock_add_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286287584,
      "name": "memblock_insert_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
void memblock_insert_region(struct memblock_type * type, int idx, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags)
```

```json
{
  "name": "memblock_insert_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270891144,
      "name": "memblock_insert_region",
      "external": false,
      "loc": "mm/memblock.c:548",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_add_range",
        "mm/memblock.c:memblock_add_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270891144,
      "name": "memblock_insert_region",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 124
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
void memblock_insert_region(struct memblock_type * type, int idx, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags)
```

```json
{
  "name": "memblock_insert_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589774171,
      "name": "memblock_insert_region",
      "external": false,
      "loc": "mm/memblock.c:548",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_add_range",
        "mm/memblock.c:memblock_add_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589774171,
      "name": "memblock_insert_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void memblock_insert_region(struct memblock_type * type, int idx, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags)
```

```json
{
  "name": "memblock_insert_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589496994,
      "name": "memblock_insert_region",
      "external": false,
      "loc": "mm/memblock.c:548",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_add_range",
        "mm/memblock.c:memblock_add_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589496994,
      "name": "memblock_insert_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void memblock_insert_region(struct memblock_type * type, int idx, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags)
```

```json
{
  "name": "memblock_insert_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590217579,
      "name": "memblock_insert_region",
      "external": false,
      "loc": "mm/memblock.c:548",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_add_range",
        "mm/memblock.c:memblock_add_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590217579,
      "name": "memblock_insert_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void memblock_insert_region(struct memblock_type * type, int idx, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags)
```

```json
{
  "name": "memblock_insert_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590267937,
      "name": "memblock_insert_region",
      "external": false,
      "loc": "mm/memblock.c:548",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_isolate_range",
        "mm/memblock.c:memblock_add_range",
        "mm/memblock.c:memblock_add_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590267937,
      "name": "memblock_insert_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int flags</code> ➡️ <code>enum memblock_flags flags</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void memblock_insert_region(struct memblock_type * type, int idx, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags)
```
</details>
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
