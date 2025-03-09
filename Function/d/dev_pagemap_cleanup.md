# Function: <code>dev_pagemap_cleanup</code>

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
void dev_pagemap_cleanup(struct dev_pagemap * pgmap)
```

```json
{
  "name": "dev_pagemap_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581737744,
      "name": "dev_pagemap_cleanup",
      "external": false,
      "loc": "mm/memremap.c:86",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:devm_memremap_pages",
        "mm/memremap.c:devm_memremap_pages_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581737744,
      "name": "dev_pagemap_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void dev_pagemap_cleanup(struct dev_pagemap * pgmap)
```

```json
{
  "name": "dev_pagemap_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581811184,
      "name": "dev_pagemap_cleanup",
      "external": false,
      "loc": "mm/memremap.c:87",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581811184,
      "name": "dev_pagemap_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void dev_pagemap_cleanup(struct dev_pagemap * pgmap)
```

```json
{
  "name": "dev_pagemap_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582031760,
      "name": "dev_pagemap_cleanup",
      "external": false,
      "loc": "mm/memremap.c:111",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582031760,
      "name": "dev_pagemap_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
  "name": "dev_pagemap_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582082097,
      "name": "dev_pagemap_cleanup",
      "external": false,
      "loc": "mm/memremap.c:123",
      "file": "mm/memremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memremap.c:memunmap_pages"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_pagemap_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582106887,
      "name": "dev_pagemap_cleanup",
      "external": false,
      "loc": "mm/memremap.c:123",
      "file": "mm/memremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memremap.c:memunmap_pages"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_pagemap_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582423044,
      "name": "dev_pagemap_cleanup",
      "external": false,
      "loc": "mm/memremap.c:123",
      "file": "mm/memremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memremap.c:memunmap_pages"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
void dev_pagemap_cleanup(struct dev_pagemap * pgmap)
```

```json
{
  "name": "dev_pagemap_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286806192,
      "name": "dev_pagemap_cleanup",
      "external": false,
      "loc": "mm/memremap.c:87",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286806192,
      "name": "dev_pagemap_cleanup",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void dev_pagemap_cleanup(struct dev_pagemap * pgmap)
```

```json
{
  "name": "dev_pagemap_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581779920,
      "name": "dev_pagemap_cleanup",
      "external": false,
      "loc": "mm/memremap.c:87",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581779920,
      "name": "dev_pagemap_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void dev_pagemap_cleanup(struct dev_pagemap * pgmap)
```

```json
{
  "name": "dev_pagemap_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581718080,
      "name": "dev_pagemap_cleanup",
      "external": false,
      "loc": "mm/memremap.c:87",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581718080,
      "name": "dev_pagemap_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void dev_pagemap_cleanup(struct dev_pagemap * pgmap)
```

```json
{
  "name": "dev_pagemap_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581771232,
      "name": "dev_pagemap_cleanup",
      "external": false,
      "loc": "mm/memremap.c:87",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581771232,
      "name": "dev_pagemap_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void dev_pagemap_cleanup(struct dev_pagemap * pgmap)
```

```json
{
  "name": "dev_pagemap_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581840096,
      "name": "dev_pagemap_cleanup",
      "external": false,
      "loc": "mm/memremap.c:87",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581840096,
      "name": "dev_pagemap_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void dev_pagemap_cleanup(struct dev_pagemap * pgmap)
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void dev_pagemap_cleanup(struct dev_pagemap * pgmap)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void dev_pagemap_cleanup(struct dev_pagemap * pgmap)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void dev_pagemap_cleanup(struct dev_pagemap * pgmap)
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
void dev_pagemap_cleanup(struct dev_pagemap * pgmap)
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
