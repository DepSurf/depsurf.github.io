# Function: <code>memblock_remove_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void memblock_remove_region(struct memblock_type * type, long unsigned int r)
```

```json
{
  "name": "memblock_remove_region",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587355149,
      "name": "memblock_remove_region",
      "external": false,
      "loc": "mm/memblock.c:285",
      "file": "mm/memblock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_remove_range",
        "mm/memblock.c:memblock_trim_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587355149,
      "name": "memblock_remove_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void memblock_remove_region(struct memblock_type * type, long unsigned int r)
```

```json
{
  "name": "memblock_remove_region",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587855929,
      "name": "memblock_remove_region",
      "external": false,
      "loc": "mm/memblock.c:281",
      "file": "mm/memblock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_trim_memory",
        "mm/memblock.c:memblock_mem_limit_remove_map",
        "mm/memblock.c:memblock_remove_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587855929,
      "name": "memblock_remove_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void memblock_remove_region(struct memblock_type * type, long unsigned int r)
```

```json
{
  "name": "memblock_remove_region",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588070616,
      "name": "memblock_remove_region",
      "external": false,
      "loc": "mm/memblock.c:281",
      "file": "mm/memblock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_trim_memory",
        "mm/memblock.c:memblock_mem_limit_remove_map",
        "mm/memblock.c:memblock_remove_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588070616,
      "name": "memblock_remove_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void memblock_remove_region(struct memblock_type * type, long unsigned int r)
```

```json
{
  "name": "memblock_remove_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588296987,
      "name": "memblock_remove_region",
      "external": false,
      "loc": "mm/memblock.c:269",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_trim_memory",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_remove_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588296987,
      "name": "memblock_remove_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
void memblock_remove_region(struct memblock_type * type, long unsigned int r)
```

```json
{
  "name": "memblock_remove_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588862246,
      "name": "memblock_remove_region",
      "external": false,
      "loc": "mm/memblock.c:269",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_trim_memory",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_remove_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588862246,
      "name": "memblock_remove_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
void memblock_remove_region(struct memblock_type * type, long unsigned int r)
```

```json
{
  "name": "memblock_remove_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589241312,
      "name": "memblock_remove_region",
      "external": false,
      "loc": "mm/memblock.c:272",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_trim_memory",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_remove_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589241312,
      "name": "memblock_remove_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
void memblock_remove_region(struct memblock_type * type, long unsigned int r)
```

```json
{
  "name": "memblock_remove_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589483616,
      "name": "memblock_remove_region",
      "external": false,
      "loc": "mm/memblock.c:349",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_trim_memory",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_remove_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589483616,
      "name": "memblock_remove_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void memblock_remove_region(struct memblock_type * type, long unsigned int r)
```

```json
{
  "name": "memblock_remove_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589944207,
      "name": "memblock_remove_region",
      "external": false,
      "loc": "mm/memblock.c:356",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_trim_memory",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_remove_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589944207,
      "name": "memblock_remove_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void memblock_remove_region(struct memblock_type * type, long unsigned int r)
```

```json
{
  "name": "memblock_remove_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590171762,
      "name": "memblock_remove_region",
      "external": false,
      "loc": "mm/memblock.c:356",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_trim_memory",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_remove_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590171762,
      "name": "memblock_remove_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void memblock_remove_region(struct memblock_type * type, long unsigned int r)
```

```json
{
  "name": "memblock_remove_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591190183,
      "name": "memblock_remove_region",
      "external": false,
      "loc": "mm/memblock.c:352",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_trim_memory",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_remove_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591190183,
      "name": "memblock_remove_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void memblock_remove_region(struct memblock_type * type, long unsigned int r)
```

```json
{
  "name": "memblock_remove_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591685639,
      "name": "memblock_remove_region",
      "external": false,
      "loc": "mm/memblock.c:337",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_trim_memory",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_remove_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591685639,
      "name": "memblock_remove_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void memblock_remove_region(struct memblock_type * type, long unsigned int r)
```

```json
{
  "name": "memblock_remove_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591628502,
      "name": "memblock_remove_region",
      "external": false,
      "loc": "mm/memblock.c:337",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_trim_memory",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_remove_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591628502,
      "name": "memblock_remove_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void memblock_remove_region(struct memblock_type * type, long unsigned int r)
```

```json
{
  "name": "memblock_remove_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592802294,
      "name": "memblock_remove_region",
      "external": false,
      "loc": "mm/memblock.c:339",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_trim_memory",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_remove_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592802294,
      "name": "memblock_remove_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void memblock_remove_region(struct memblock_type * type, long unsigned int r)
```

```json
{
  "name": "memblock_remove_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594703023,
      "name": "memblock_remove_region",
      "external": false,
      "loc": "mm/memblock.c:339",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_trim_memory",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_remove_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594703023,
      "name": "memblock_remove_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void memblock_remove_region(struct memblock_type * type, long unsigned int r)
```

```json
{
  "name": "memblock_remove_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596444800,
      "name": "memblock_remove_region",
      "external": false,
      "loc": "mm/memblock.c:343",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_trim_memory",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_phys_free",
        "mm/memblock.c:memblock_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596444800,
      "name": "memblock_remove_region",
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
void memblock_remove_region(struct memblock_type * type, long unsigned int r)
```

```json
{
  "name": "memblock_remove_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596986096,
      "name": "memblock_remove_region",
      "external": false,
      "loc": "mm/memblock.c:343",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_trim_memory",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_phys_free",
        "mm/memblock.c:memblock_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596986096,
      "name": "memblock_remove_region",
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
void memblock_remove_region(struct memblock_type * type, long unsigned int r)
```

```json
{
  "name": "memblock_remove_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597914624,
      "name": "memblock_remove_region",
      "external": false,
      "loc": "mm/memblock.c:349",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_trim_memory",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_phys_free",
        "mm/memblock.c:memblock_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597914624,
      "name": "memblock_remove_region",
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
void memblock_remove_region(struct memblock_type * type, long unsigned int r)
```

```json
{
  "name": "memblock_remove_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492888968,
      "name": "memblock_remove_region",
      "external": false,
      "loc": "mm/memblock.c:356",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_trim_memory",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_remove_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492888968,
      "name": "memblock_remove_region",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void memblock_remove_region(struct memblock_type * type, long unsigned int r)
```

```json
{
  "name": "memblock_remove_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226686300,
      "name": "memblock_remove_region",
      "external": false,
      "loc": "mm/memblock.c:356",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_trim_memory",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_remove_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226686300,
      "name": "memblock_remove_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
void memblock_remove_region(struct memblock_type * type, long unsigned int r)
```

```json
{
  "name": "memblock_remove_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286287376,
      "name": "memblock_remove_region",
      "external": false,
      "loc": "mm/memblock.c:356",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_trim_memory",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_remove_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286287376,
      "name": "memblock_remove_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
void memblock_remove_region(struct memblock_type * type, long unsigned int r)
```

```json
{
  "name": "memblock_remove_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270891268,
      "name": "memblock_remove_region",
      "external": false,
      "loc": "mm/memblock.c:356",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_trim_memory",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_remove_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270891268,
      "name": "memblock_remove_region",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 110
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
void memblock_remove_region(struct memblock_type * type, long unsigned int r)
```

```json
{
  "name": "memblock_remove_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589774050,
      "name": "memblock_remove_region",
      "external": false,
      "loc": "mm/memblock.c:356",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_trim_memory",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_remove_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589774050,
      "name": "memblock_remove_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void memblock_remove_region(struct memblock_type * type, long unsigned int r)
```

```json
{
  "name": "memblock_remove_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589496873,
      "name": "memblock_remove_region",
      "external": false,
      "loc": "mm/memblock.c:356",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_trim_memory",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_remove_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589496873,
      "name": "memblock_remove_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void memblock_remove_region(struct memblock_type * type, long unsigned int r)
```

```json
{
  "name": "memblock_remove_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590217458,
      "name": "memblock_remove_region",
      "external": false,
      "loc": "mm/memblock.c:356",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_trim_memory",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_remove_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590217458,
      "name": "memblock_remove_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void memblock_remove_region(struct memblock_type * type, long unsigned int r)
```

```json
{
  "name": "memblock_remove_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590267816,
      "name": "memblock_remove_region",
      "external": false,
      "loc": "mm/memblock.c:356",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_trim_memory",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_cap_memory_range",
        "mm/memblock.c:memblock_remove_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590267816,
      "name": "memblock_remove_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
