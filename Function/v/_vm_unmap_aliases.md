# Function: <code>_vm_unmap_aliases</code>

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
void _vm_unmap_aliases(long unsigned int start, long unsigned int end, int flush)
```

```json
{
  "name": "_vm_unmap_aliases",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581373408,
      "name": "_vm_unmap_aliases",
      "external": false,
      "loc": "mm/vmalloc.c:1661",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vunmap",
        "mm/vmalloc.c:__vunmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581373408,
      "name": "_vm_unmap_aliases",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
void _vm_unmap_aliases(long unsigned int start, long unsigned int end, int flush)
```

```json
{
  "name": "_vm_unmap_aliases",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581434656,
      "name": "_vm_unmap_aliases",
      "external": false,
      "loc": "mm/vmalloc.c:1669",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vunmap",
        "mm/vmalloc.c:__vunmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581434656,
      "name": "_vm_unmap_aliases",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_vm_unmap_aliases",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581646486,
      "name": "_vm_unmap_aliases",
      "external": false,
      "loc": "mm/vmalloc.c:1768",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vunmap",
        "mm/vmalloc.c:__vunmap"
      ],
      "caller_func": [
        "mm/vmalloc.c:__vunmap",
        "mm/vmalloc.c:__vunmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581634448,
      "name": "_vm_unmap_aliases.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_vm_unmap_aliases",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581692854,
      "name": "_vm_unmap_aliases",
      "external": false,
      "loc": "mm/vmalloc.c:1750",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vunmap",
        "mm/vmalloc.c:__vunmap"
      ],
      "caller_func": [
        "mm/vmalloc.c:__vunmap",
        "mm/vmalloc.c:__vunmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581680608,
      "name": "_vm_unmap_aliases.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_vm_unmap_aliases",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581715590,
      "name": "_vm_unmap_aliases",
      "external": false,
      "loc": "mm/vmalloc.c:2020",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vunmap",
        "mm/vmalloc.c:__vunmap"
      ],
      "caller_func": [
        "mm/vmalloc.c:__vunmap",
        "mm/vmalloc.c:__vunmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581702848,
      "name": "_vm_unmap_aliases.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
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
void _vm_unmap_aliases(long unsigned int start, long unsigned int end, int flush)
```

```json
{
  "name": "_vm_unmap_aliases",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581974717,
      "name": "_vm_unmap_aliases",
      "external": false,
      "loc": "mm/vmalloc.c:2072",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vunmap",
        "mm/vmalloc.c:__vunmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581974656,
      "name": "_vm_unmap_aliases",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
    },
    {
      "addr": 18446744071592201940,
      "name": "_vm_unmap_aliases.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void _vm_unmap_aliases(long unsigned int start, long unsigned int end, int flush)
```

```json
{
  "name": "_vm_unmap_aliases",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582397085,
      "name": "_vm_unmap_aliases",
      "external": false,
      "loc": "mm/vmalloc.c:2090",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vunmap",
        "mm/vmalloc.c:__vunmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582397024,
      "name": "_vm_unmap_aliases",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
    },
    {
      "addr": 18446744071593978751,
      "name": "_vm_unmap_aliases.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void _vm_unmap_aliases(long unsigned int start, long unsigned int end, int flush)
```

```json
{
  "name": "_vm_unmap_aliases",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582903597,
      "name": "_vm_unmap_aliases",
      "external": false,
      "loc": "mm/vmalloc.c:2152",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vunmap",
        "mm/vmalloc.c:__vunmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582903536,
      "name": "_vm_unmap_aliases",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
    },
    {
      "addr": 18446744071596034701,
      "name": "_vm_unmap_aliases.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void _vm_unmap_aliases(long unsigned int start, long unsigned int end, int flush)
```

```json
{
  "name": "_vm_unmap_aliases",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_vm_unmap_aliases",
      "external": false,
      "loc": "mm/vmalloc.c:2259",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vfree",
        "mm/vmalloc.c:vm_unmap_aliases"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583119776,
      "name": "_vm_unmap_aliases",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 773
    },
    {
      "addr": 18446744071596556690,
      "name": "_vm_unmap_aliases.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void _vm_unmap_aliases(long unsigned int start, long unsigned int end, int flush)
```

```json
{
  "name": "_vm_unmap_aliases",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_vm_unmap_aliases",
      "external": false,
      "loc": "mm/vmalloc.c:2259",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vm_unmap_aliases"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583302672,
      "name": "_vm_unmap_aliases",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 773
    },
    {
      "addr": 18446744071597460934,
      "name": "_vm_unmap_aliases.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void _vm_unmap_aliases(long unsigned int start, long unsigned int end, int flush)
```

```json
{
  "name": "_vm_unmap_aliases",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492837592,
      "name": "_vm_unmap_aliases",
      "external": false,
      "loc": "mm/vmalloc.c:1669",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vunmap",
        "mm/vmalloc.c:__vunmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492837592,
      "name": "_vm_unmap_aliases",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 528
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
void _vm_unmap_aliases(long unsigned int start, long unsigned int end, int flush)
```

```json
{
  "name": "_vm_unmap_aliases",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226641452,
      "name": "_vm_unmap_aliases",
      "external": false,
      "loc": "mm/vmalloc.c:1669",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vunmap",
        "mm/vmalloc.c:__vunmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226641452,
      "name": "_vm_unmap_aliases",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
void _vm_unmap_aliases(long unsigned int start, long unsigned int end, int flush)
```

```json
{
  "name": "_vm_unmap_aliases",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286225616,
      "name": "_vm_unmap_aliases",
      "external": false,
      "loc": "mm/vmalloc.c:1669",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vunmap",
        "mm/vmalloc.c:__vunmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286225616,
      "name": "_vm_unmap_aliases",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 564
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "_vm_unmap_aliases",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272790670,
      "name": "_vm_unmap_aliases",
      "external": false,
      "loc": "mm/vmalloc.c:1669",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vunmap",
        "mm/vmalloc.c:__vunmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272790670,
      "name": "_vm_unmap_aliases.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
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
void _vm_unmap_aliases(long unsigned int start, long unsigned int end, int flush)
```

```json
{
  "name": "_vm_unmap_aliases",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581403504,
      "name": "_vm_unmap_aliases",
      "external": false,
      "loc": "mm/vmalloc.c:1669",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vunmap",
        "mm/vmalloc.c:__vunmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581403504,
      "name": "_vm_unmap_aliases",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
void _vm_unmap_aliases(long unsigned int start, long unsigned int end, int flush)
```

```json
{
  "name": "_vm_unmap_aliases",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581346016,
      "name": "_vm_unmap_aliases",
      "external": false,
      "loc": "mm/vmalloc.c:1669",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vunmap",
        "mm/vmalloc.c:__vunmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581346016,
      "name": "_vm_unmap_aliases",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
void _vm_unmap_aliases(long unsigned int start, long unsigned int end, int flush)
```

```json
{
  "name": "_vm_unmap_aliases",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581394704,
      "name": "_vm_unmap_aliases",
      "external": false,
      "loc": "mm/vmalloc.c:1669",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vunmap",
        "mm/vmalloc.c:__vunmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581394704,
      "name": "_vm_unmap_aliases",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
  "name": "_vm_unmap_aliases",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581459279,
      "name": "_vm_unmap_aliases",
      "external": false,
      "loc": "mm/vmalloc.c:1669",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vunmap",
        "mm/vmalloc.c:__vunmap"
      ],
      "caller_func": [
        "mm/vmalloc.c:__vunmap",
        "mm/vmalloc.c:__vunmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581458656,
      "name": "_vm_unmap_aliases.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
void _vm_unmap_aliases(long unsigned int start, long unsigned int end, int flush)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void _vm_unmap_aliases(long unsigned int start, long unsigned int end, int flush)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void _vm_unmap_aliases(long unsigned int start, long unsigned int end, int flush)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void _vm_unmap_aliases(long unsigned int start, long unsigned int end, int flush)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ➖</summary>

```c
void _vm_unmap_aliases(long unsigned int start, long unsigned int end, int flush)
```
</details>
</li>
</ul>
