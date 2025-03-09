# Function: <code>memunmap_pages</code>

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
void memunmap_pages(struct dev_pagemap * pgmap)
```

```json
{
  "name": "memunmap_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581811792,
      "name": "memunmap_pages",
      "external": true,
      "loc": "mm/memremap.c:103",
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
      "addr": 18446744071581811792,
      "name": "memunmap_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 487
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
void memunmap_pages(struct dev_pagemap * pgmap)
```

```json
{
  "name": "memunmap_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582033680,
      "name": "memunmap_pages",
      "external": true,
      "loc": "mm/memremap.c:127",
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
      "addr": 18446744071582033680,
      "name": "memunmap_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 609
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
void memunmap_pages(struct dev_pagemap * pgmap)
```

```json
{
  "name": "memunmap_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582081840,
      "name": "memunmap_pages",
      "external": true,
      "loc": "mm/memremap.c:168",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:devm_memremap_pages",
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582081840,
      "name": "memunmap_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
void memunmap_pages(struct dev_pagemap * pgmap)
```

```json
{
  "name": "memunmap_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582106624,
      "name": "memunmap_pages",
      "external": true,
      "loc": "mm/memremap.c:168",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:devm_memremap_pages",
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582106624,
      "name": "memunmap_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 847
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
void memunmap_pages(struct dev_pagemap * pgmap)
```

```json
{
  "name": "memunmap_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memunmap_pages",
      "external": true,
      "loc": "mm/memremap.c:165",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:devm_memremap_pages",
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592228593,
      "name": "memunmap_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582422784,
      "name": "memunmap_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 911
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
void memunmap_pages(struct dev_pagemap * pgmap)
```

```json
{
  "name": "memunmap_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memunmap_pages",
      "external": true,
      "loc": "mm/memremap.c:136",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:devm_memremap_pages",
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594008014,
      "name": "memunmap_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582937408,
      "name": "memunmap_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 737
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
void memunmap_pages(struct dev_pagemap * pgmap)
```

```json
{
  "name": "memunmap_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memunmap_pages",
      "external": true,
      "loc": "mm/memremap.c:136",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:devm_memremap_pages",
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596049952,
      "name": "memunmap_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071583493536,
      "name": "memunmap_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 748
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
void memunmap_pages(struct dev_pagemap * pgmap)
```

```json
{
  "name": "memunmap_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memunmap_pages",
      "external": true,
      "loc": "mm/memremap.c:136",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:devm_memremap_pages",
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596572406,
      "name": "memunmap_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583708512,
      "name": "memunmap_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 771
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
void memunmap_pages(struct dev_pagemap * pgmap)
```

```json
{
  "name": "memunmap_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memunmap_pages",
      "external": true,
      "loc": "mm/memremap.c:137",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:devm_memremap_pages",
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597476917,
      "name": "memunmap_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583908864,
      "name": "memunmap_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 771
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
void memunmap_pages(struct dev_pagemap * pgmap)
```

```json
{
  "name": "memunmap_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286807472,
      "name": "memunmap_pages",
      "external": true,
      "loc": "mm/memremap.c:103",
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
      "addr": 13835058055286807472,
      "name": "memunmap_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 660
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
void memunmap_pages(struct dev_pagemap * pgmap)
```

```json
{
  "name": "memunmap_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581780528,
      "name": "memunmap_pages",
      "external": true,
      "loc": "mm/memremap.c:103",
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
      "addr": 18446744071581780528,
      "name": "memunmap_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 487
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
void memunmap_pages(struct dev_pagemap * pgmap)
```

```json
{
  "name": "memunmap_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581718688,
      "name": "memunmap_pages",
      "external": true,
      "loc": "mm/memremap.c:103",
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
      "addr": 18446744071581718688,
      "name": "memunmap_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 487
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
void memunmap_pages(struct dev_pagemap * pgmap)
```

```json
{
  "name": "memunmap_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581771840,
      "name": "memunmap_pages",
      "external": true,
      "loc": "mm/memremap.c:103",
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
      "addr": 18446744071581771840,
      "name": "memunmap_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 487
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
void memunmap_pages(struct dev_pagemap * pgmap)
```

```json
{
  "name": "memunmap_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581840752,
      "name": "memunmap_pages",
      "external": true,
      "loc": "mm/memremap.c:103",
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
      "addr": 18446744071581840752,
      "name": "memunmap_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
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
void memunmap_pages(struct dev_pagemap * pgmap)
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
void memunmap_pages(struct dev_pagemap * pgmap)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void memunmap_pages(struct dev_pagemap * pgmap)
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
void memunmap_pages(struct dev_pagemap * pgmap)
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
