# Function: <code>obj_malloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int obj_malloc(struct page * first_page, struct size_class * class, long unsigned int handle)
```

```json
{
  "name": "obj_malloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580965168,
      "name": "obj_malloc",
      "external": false,
      "loc": "mm/zsmalloc.c:1350",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_compact"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580965168,
      "name": "obj_malloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "obj_malloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581117744,
      "name": "obj_malloc",
      "external": false,
      "loc": "mm/zsmalloc.c:1487",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_malloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581117744,
      "name": "obj_malloc.isra.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "obj_malloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581192848,
      "name": "obj_malloc",
      "external": false,
      "loc": "mm/zsmalloc.c:1447",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_malloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581192848,
      "name": "obj_malloc.isra.30",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "obj_malloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581240416,
      "name": "obj_malloc",
      "external": false,
      "loc": "mm/zsmalloc.c:1426",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_malloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581240416,
      "name": "obj_malloc.isra.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "obj_malloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581372048,
      "name": "obj_malloc",
      "external": false,
      "loc": "mm/zsmalloc.c:1430",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_malloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581372048,
      "name": "obj_malloc.isra.30",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "obj_malloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581520368,
      "name": "obj_malloc",
      "external": false,
      "loc": "mm/zsmalloc.c:1433",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_malloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581520368,
      "name": "obj_malloc.isra.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "obj_malloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581605760,
      "name": "obj_malloc",
      "external": false,
      "loc": "mm/zsmalloc.c:1420",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_malloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581605760,
      "name": "obj_malloc.isra.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "obj_malloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581718336,
      "name": "obj_malloc",
      "external": false,
      "loc": "mm/zsmalloc.c:1410",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_malloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581718336,
      "name": "obj_malloc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "obj_malloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581791792,
      "name": "obj_malloc",
      "external": false,
      "loc": "mm/zsmalloc.c:1407",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_malloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581791792,
      "name": "obj_malloc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
long unsigned int obj_malloc(struct size_class * class, struct zspage * zspage, long unsigned int handle)
```

```json
{
  "name": "obj_malloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582014400,
      "name": "obj_malloc",
      "external": false,
      "loc": "mm/zsmalloc.c:1409",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_malloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582014400,
      "name": "obj_malloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
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
long unsigned int obj_malloc(struct size_class * class, struct zspage * zspage, long unsigned int handle)
```

```json
{
  "name": "obj_malloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582062880,
      "name": "obj_malloc",
      "external": false,
      "loc": "mm/zsmalloc.c:1358",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_malloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582062880,
      "name": "obj_malloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
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
long unsigned int obj_malloc(struct size_class * class, struct zspage * zspage, long unsigned int handle)
```

```json
{
  "name": "obj_malloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582087440,
      "name": "obj_malloc",
      "external": false,
      "loc": "mm/zsmalloc.c:1357",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_malloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582087440,
      "name": "obj_malloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
long unsigned int obj_malloc(struct size_class * class, struct zspage * zspage, long unsigned int handle)
```

```json
{
  "name": "obj_malloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582400640,
      "name": "obj_malloc",
      "external": false,
      "loc": "mm/zsmalloc.c:1357",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_malloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582400640,
      "name": "obj_malloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
long unsigned int obj_malloc(struct zs_pool * pool, struct zspage * zspage, long unsigned int handle)
```

```json
{
  "name": "obj_malloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582912480,
      "name": "obj_malloc",
      "external": false,
      "loc": "mm/zsmalloc.c:1353",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_malloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582912480,
      "name": "obj_malloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
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
long unsigned int obj_malloc(struct zs_pool * pool, struct zspage * zspage, long unsigned int handle)
```

```json
{
  "name": "obj_malloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583466640,
      "name": "obj_malloc",
      "external": false,
      "loc": "mm/zsmalloc.c:1507",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_malloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583466640,
      "name": "obj_malloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
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
long unsigned int obj_malloc(struct zs_pool * pool, struct zspage * zspage, long unsigned int handle)
```

```json
{
  "name": "obj_malloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583683696,
      "name": "obj_malloc",
      "external": false,
      "loc": "mm/zsmalloc.c:1307",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_malloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583683696,
      "name": "obj_malloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
long unsigned int obj_malloc(struct zs_pool * pool, struct zspage * zspage, long unsigned int handle)
```

```json
{
  "name": "obj_malloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583878192,
      "name": "obj_malloc",
      "external": false,
      "loc": "mm/zsmalloc.c:1307",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:migrate_zspage",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_malloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583878192,
      "name": "obj_malloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "obj_malloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493252040,
      "name": "obj_malloc",
      "external": false,
      "loc": "mm/zsmalloc.c:1407",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_malloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493252040,
      "name": "obj_malloc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
long unsigned int obj_malloc(struct size_class * class, struct zspage * zspage, long unsigned int handle)
```

```json
{
  "name": "obj_malloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226861884,
      "name": "obj_malloc",
      "external": false,
      "loc": "mm/zsmalloc.c:1407",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_malloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226861884,
      "name": "obj_malloc",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long unsigned int obj_malloc(struct size_class * class, struct zspage * zspage, long unsigned int handle)
```

```json
{
  "name": "obj_malloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286774800,
      "name": "obj_malloc",
      "external": false,
      "loc": "mm/zsmalloc.c:1407",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_malloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286774800,
      "name": "obj_malloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
long unsigned int obj_malloc(struct size_class * class, struct zspage * zspage, long unsigned int handle)
```

```json
{
  "name": "obj_malloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273008808,
      "name": "obj_malloc",
      "external": false,
      "loc": "mm/zsmalloc.c:1407",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_malloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273008808,
      "name": "obj_malloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "obj_malloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581760528,
      "name": "obj_malloc",
      "external": false,
      "loc": "mm/zsmalloc.c:1407",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_malloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581760528,
      "name": "obj_malloc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "obj_malloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581699152,
      "name": "obj_malloc",
      "external": false,
      "loc": "mm/zsmalloc.c:1407",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_malloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581699152,
      "name": "obj_malloc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "obj_malloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581751840,
      "name": "obj_malloc",
      "external": false,
      "loc": "mm/zsmalloc.c:1407",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_malloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581751840,
      "name": "obj_malloc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "obj_malloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581820768,
      "name": "obj_malloc",
      "external": false,
      "loc": "mm/zsmalloc.c:1407",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_malloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581820768,
      "name": "obj_malloc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
long unsigned int obj_malloc(struct page * first_page, struct size_class * class, long unsigned int handle)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
long unsigned int obj_malloc(struct size_class * class, struct zspage * zspage, long unsigned int handle)
```
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct zs_pool * pool</code>
</li>
<li>
<b>Param removed. </b>
<code>struct size_class * class</code>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
long unsigned int obj_malloc(struct size_class * class, struct zspage * zspage, long unsigned int handle)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
long unsigned int obj_malloc(struct size_class * class, struct zspage * zspage, long unsigned int handle)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
long unsigned int obj_malloc(struct size_class * class, struct zspage * zspage, long unsigned int handle)
```
</details>
</li>
</ul>
