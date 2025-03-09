# Function: <code>memremap_pages</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void * memremap_pages(struct dev_pagemap * pgmap, int nid)
```

```json
{
  "name": "memremap_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581812304,
      "name": "memremap_pages",
      "external": true,
      "loc": "mm/memremap.c:157",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:devm_memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581812304,
      "name": "memremap_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1388
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
void * memremap_pages(struct dev_pagemap * pgmap, int nid)
```

```json
{
  "name": "memremap_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582032128,
      "name": "memremap_pages",
      "external": true,
      "loc": "mm/memremap.c:183",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:devm_memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582032128,
      "name": "memremap_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1542
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
void * memremap_pages(struct dev_pagemap * pgmap, int nid)
```

```json
{
  "name": "memremap_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582082320,
      "name": "memremap_pages",
      "external": true,
      "loc": "mm/memremap.c:314",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:devm_memremap_pages",
        "drivers/xen/unpopulated-alloc.c:fill_list",
        "drivers/xen/unpopulated-alloc.c:fill_list",
        "drivers/xen/unpopulated-alloc.c:fill_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582082320,
      "name": "memremap_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 745
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
void * memremap_pages(struct dev_pagemap * pgmap, int nid)
```

```json
{
  "name": "memremap_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582107488,
      "name": "memremap_pages",
      "external": true,
      "loc": "mm/memremap.c:320",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:devm_memremap_pages",
        "drivers/xen/unpopulated-alloc.c:fill_list",
        "drivers/xen/unpopulated-alloc.c:fill_list",
        "drivers/xen/unpopulated-alloc.c:fill_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582107488,
      "name": "memremap_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 745
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
void * memremap_pages(struct dev_pagemap * pgmap, int nid)
```

```json
{
  "name": "memremap_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memremap_pages",
      "external": true,
      "loc": "mm/memremap.c:317",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:devm_memremap_pages",
        "drivers/xen/unpopulated-alloc.c:fill_list",
        "drivers/xen/unpopulated-alloc.c:fill_list",
        "drivers/xen/unpopulated-alloc.c:fill_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592228614,
      "name": "memremap_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582423712,
      "name": "memremap_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 757
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
void * memremap_pages(struct dev_pagemap * pgmap, int nid)
```

```json
{
  "name": "memremap_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memremap_pages",
      "external": true,
      "loc": "mm/memremap.c:286",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:devm_memremap_pages",
        "drivers/xen/unpopulated-alloc.c:fill_list",
        "drivers/xen/unpopulated-alloc.c:fill_list",
        "drivers/xen/unpopulated-alloc.c:fill_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594008081,
      "name": "memremap_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582939232,
      "name": "memremap_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 567
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
void * memremap_pages(struct dev_pagemap * pgmap, int nid)
```

```json
{
  "name": "memremap_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memremap_pages",
      "external": true,
      "loc": "mm/memremap.c:291",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:devm_memremap_pages",
        "drivers/xen/unpopulated-alloc.c:fill_list",
        "drivers/xen/unpopulated-alloc.c:fill_list",
        "drivers/xen/unpopulated-alloc.c:fill_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596050019,
      "name": "memremap_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583495408,
      "name": "memremap_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
void * memremap_pages(struct dev_pagemap * pgmap, int nid)
```

```json
{
  "name": "memremap_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memremap_pages",
      "external": true,
      "loc": "mm/memremap.c:291",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:devm_memremap_pages",
        "drivers/xen/unpopulated-alloc.c:fill_list",
        "drivers/xen/unpopulated-alloc.c:fill_list",
        "drivers/xen/unpopulated-alloc.c:fill_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596572472,
      "name": "memremap_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583710432,
      "name": "memremap_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 656
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
void * memremap_pages(struct dev_pagemap * pgmap, int nid)
```

```json
{
  "name": "memremap_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memremap_pages",
      "external": true,
      "loc": "mm/memremap.c:292",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:devm_memremap_pages",
        "drivers/xen/unpopulated-alloc.c:fill_list",
        "drivers/xen/unpopulated-alloc.c:fill_list",
        "drivers/xen/unpopulated-alloc.c:fill_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597476983,
      "name": "memremap_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583910784,
      "name": "memremap_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 666
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void * memremap_pages(struct dev_pagemap * pgmap, int nid)
```

```json
{
  "name": "memremap_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286808176,
      "name": "memremap_pages",
      "external": true,
      "loc": "mm/memremap.c:157",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:devm_memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286808176,
      "name": "memremap_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1684
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void * memremap_pages(struct dev_pagemap * pgmap, int nid)
```

```json
{
  "name": "memremap_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581781040,
      "name": "memremap_pages",
      "external": true,
      "loc": "mm/memremap.c:157",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:devm_memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581781040,
      "name": "memremap_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1388
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
void * memremap_pages(struct dev_pagemap * pgmap, int nid)
```

```json
{
  "name": "memremap_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581719200,
      "name": "memremap_pages",
      "external": true,
      "loc": "mm/memremap.c:157",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:devm_memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581719200,
      "name": "memremap_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1388
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
void * memremap_pages(struct dev_pagemap * pgmap, int nid)
```

```json
{
  "name": "memremap_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581772352,
      "name": "memremap_pages",
      "external": true,
      "loc": "mm/memremap.c:157",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:devm_memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581772352,
      "name": "memremap_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1388
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
void * memremap_pages(struct dev_pagemap * pgmap, int nid)
```

```json
{
  "name": "memremap_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581841248,
      "name": "memremap_pages",
      "external": true,
      "loc": "mm/memremap.c:157",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:devm_memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581841248,
      "name": "memremap_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1441
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void * memremap_pages(struct dev_pagemap * pgmap, int nid)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void * memremap_pages(struct dev_pagemap * pgmap, int nid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void * memremap_pages(struct dev_pagemap * pgmap, int nid)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void * memremap_pages(struct dev_pagemap * pgmap, int nid)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
