# Function: <code>__free_pages_core</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void __free_pages_core(struct page * page, unsigned int order)
```

```json
{
  "name": "__free_pages_core",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581402288,
      "name": "__free_pages_core",
      "external": true,
      "loc": "mm/page_alloc.c:1430",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memblock_free_pages",
        "mm/memory_hotplug.c:generic_online_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581402288,
      "name": "__free_pages_core",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void __free_pages_core(struct page * page, unsigned int order)
```

```json
{
  "name": "__free_pages_core",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581463280,
      "name": "__free_pages_core",
      "external": true,
      "loc": "mm/page_alloc.c:1417",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memblock_free_pages",
        "mm/memory_hotplug.c:generic_online_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581463280,
      "name": "__free_pages_core",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void __free_pages_core(struct page * page, unsigned int order)
```

```json
{
  "name": "__free_pages_core",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581668832,
      "name": "__free_pages_core",
      "external": true,
      "loc": "mm/page_alloc.c:1472",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memblock_free_pages",
        "mm/memory_hotplug.c:generic_online_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581668832,
      "name": "__free_pages_core",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void __free_pages_core(struct page * page, unsigned int order)
```

```json
{
  "name": "__free_pages_core",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581709280,
      "name": "__free_pages_core",
      "external": true,
      "loc": "mm/page_alloc.c:1538",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memblock_free_pages",
        "mm/memory_hotplug.c:generic_online_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581709280,
      "name": "__free_pages_core",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void __free_pages_core(struct page * page, unsigned int order)
```

```json
{
  "name": "__free_pages_core",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581730128,
      "name": "__free_pages_core",
      "external": true,
      "loc": "mm/page_alloc.c:1573",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memblock_free_pages",
        "mm/memory_hotplug.c:generic_online_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581730128,
      "name": "__free_pages_core",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void __free_pages_core(struct page * page, unsigned int order)
```

```json
{
  "name": "__free_pages_core",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__free_pages_core",
      "external": true,
      "loc": "mm/page_alloc.c:1659",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memblock_free_pages",
        "mm/memory_hotplug.c:generic_online_page",
        "mm/memory_hotplug.c:generic_online_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592203377,
      "name": "__free_pages_core.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582004032,
      "name": "__free_pages_core",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
void __free_pages_core(struct page * page, unsigned int order)
```

```json
{
  "name": "__free_pages_core",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__free_pages_core",
      "external": true,
      "loc": "mm/page_alloc.c:1642",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memblock_free_pages",
        "mm/memory_hotplug.c:generic_online_page",
        "mm/memory_hotplug.c:generic_online_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593981007,
      "name": "__free_pages_core.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071582429360,
      "name": "__free_pages_core",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
void __free_pages_core(struct page * page, unsigned int order)
```

```json
{
  "name": "__free_pages_core",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__free_pages_core",
      "external": true,
      "loc": "mm/page_alloc.c:1723",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memblock_free_pages",
        "mm/memory_hotplug.c:generic_online_page",
        "mm/memory_hotplug.c:generic_online_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596036593,
      "name": "__free_pages_core.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071582938032,
      "name": "__free_pages_core",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
void __free_pages_core(struct page * page, unsigned int order)
```

```json
{
  "name": "__free_pages_core",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__free_pages_core",
      "external": true,
      "loc": "mm/page_alloc.c:1321",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mm_init.c:memblock_free_pages",
        "mm/memory_hotplug.c:generic_online_page",
        "mm/memory_hotplug.c:generic_online_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596558691,
      "name": "__free_pages_core.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    },
    {
      "addr": 18446744071583155392,
      "name": "__free_pages_core",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 603
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
void __free_pages_core(struct page * page, unsigned int order)
```

```json
{
  "name": "__free_pages_core",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__free_pages_core",
      "external": true,
      "loc": "mm/page_alloc.c:1284",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mm_init.c:memblock_free_pages",
        "mm/memory_hotplug.c:generic_online_page",
        "mm/memory_hotplug.c:generic_online_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597463038,
      "name": "__free_pages_core.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    },
    {
      "addr": 18446744071583338336,
      "name": "__free_pages_core",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 603
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
void __free_pages_core(struct page * page, unsigned int order)
```

```json
{
  "name": "__free_pages_core",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492871216,
      "name": "__free_pages_core",
      "external": true,
      "loc": "mm/page_alloc.c:1417",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memblock_free_pages",
        "mm/memory_hotplug.c:generic_online_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492871216,
      "name": "__free_pages_core",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void __free_pages_core(struct page * page, unsigned int order)
```

```json
{
  "name": "__free_pages_core",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226670724,
      "name": "__free_pages_core",
      "external": true,
      "loc": "mm/page_alloc.c:1417",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memblock_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226670724,
      "name": "__free_pages_core",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void __free_pages_core(struct page * page, unsigned int order)
```

```json
{
  "name": "__free_pages_core",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286264224,
      "name": "__free_pages_core",
      "external": true,
      "loc": "mm/page_alloc.c:1417",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memblock_free_pages",
        "mm/memory_hotplug.c:generic_online_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286264224,
      "name": "__free_pages_core",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void __free_pages_core(struct page * page, unsigned int order)
```

```json
{
  "name": "__free_pages_core",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272814538,
      "name": "__free_pages_core",
      "external": true,
      "loc": "mm/page_alloc.c:1417",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memblock_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272814538,
      "name": "__free_pages_core",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void __free_pages_core(struct page * page, unsigned int order)
```

```json
{
  "name": "__free_pages_core",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581432128,
      "name": "__free_pages_core",
      "external": true,
      "loc": "mm/page_alloc.c:1417",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memblock_free_pages",
        "mm/memory_hotplug.c:generic_online_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581432128,
      "name": "__free_pages_core",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void __free_pages_core(struct page * page, unsigned int order)
```

```json
{
  "name": "__free_pages_core",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581374544,
      "name": "__free_pages_core",
      "external": true,
      "loc": "mm/page_alloc.c:1417",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memblock_free_pages",
        "mm/memory_hotplug.c:generic_online_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581374544,
      "name": "__free_pages_core",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void __free_pages_core(struct page * page, unsigned int order)
```

```json
{
  "name": "__free_pages_core",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581423328,
      "name": "__free_pages_core",
      "external": true,
      "loc": "mm/page_alloc.c:1417",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memblock_free_pages",
        "mm/memory_hotplug.c:generic_online_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581423328,
      "name": "__free_pages_core",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void __free_pages_core(struct page * page, unsigned int order)
```

```json
{
  "name": "__free_pages_core",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581487776,
      "name": "__free_pages_core",
      "external": true,
      "loc": "mm/page_alloc.c:1417",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memblock_free_pages",
        "mm/memory_hotplug.c:generic_online_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581487776,
      "name": "__free_pages_core",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void __free_pages_core(struct page * page, unsigned int order)
```
</details>
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
