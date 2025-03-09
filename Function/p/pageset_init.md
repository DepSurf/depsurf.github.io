# Function: <code>pageset_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pageset_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587351823,
      "name": "pageset_init",
      "external": false,
      "loc": "mm/page_alloc.c:4617",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/page_alloc.c:__build_all_zonelists"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pageset_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587852071,
      "name": "pageset_init",
      "external": false,
      "loc": "mm/page_alloc.c:5153",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/page_alloc.c:__build_all_zonelists"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pageset_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588066927,
      "name": "pageset_init",
      "external": false,
      "loc": "mm/page_alloc.c:5236",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/page_alloc.c:__build_all_zonelists"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pageset_init(struct per_cpu_pageset * p)
```

```json
{
  "name": "pageset_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580674560,
      "name": "pageset_init",
      "external": false,
      "loc": "mm/page_alloc.c:5535",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/page_alloc.c:__build_all_zonelists"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580674560,
      "name": "pageset_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pageset_init(struct per_cpu_pageset * p)
```

```json
{
  "name": "pageset_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580787513,
      "name": "pageset_init",
      "external": false,
      "loc": "mm/page_alloc.c:5507",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/page_alloc.c:build_all_zonelists_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580787513,
      "name": "pageset_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void pageset_init(struct per_cpu_pageset * p)
```

```json
{
  "name": "pageset_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580921061,
      "name": "pageset_init",
      "external": false,
      "loc": "mm/page_alloc.c:5645",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/page_alloc.c:build_all_zonelists_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580921061,
      "name": "pageset_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void pageset_init(struct per_cpu_pageset * p)
```

```json
{
  "name": "pageset_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580997020,
      "name": "pageset_init",
      "external": false,
      "loc": "mm/page_alloc.c:5890",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/page_alloc.c:build_all_zonelists_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580997020,
      "name": "pageset_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void pageset_init(struct per_cpu_pageset * p)
```

```json
{
  "name": "pageset_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581415968,
      "name": "pageset_init",
      "external": false,
      "loc": "mm/page_alloc.c:6076",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/page_alloc.c:build_all_zonelists_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581415968,
      "name": "pageset_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void pageset_init(struct per_cpu_pageset * p)
```

```json
{
  "name": "pageset_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581477008,
      "name": "pageset_init",
      "external": false,
      "loc": "mm/page_alloc.c:6094",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/page_alloc.c:build_all_zonelists_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581477008,
      "name": "pageset_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void pageset_init(struct per_cpu_pageset * p)
```

```json
{
  "name": "pageset_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581681957,
      "name": "pageset_init",
      "external": false,
      "loc": "mm/page_alloc.c:6191",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/page_alloc.c:build_all_zonelists_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581681957,
      "name": "pageset_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void pageset_init(struct per_cpu_pageset * p)
```

```json
{
  "name": "pageset_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591328796,
      "name": "pageset_init",
      "external": false,
      "loc": "mm/page_alloc.c:6419",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/page_alloc.c:build_all_zonelists_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591328796,
      "name": "pageset_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
void pageset_init(struct per_cpu_pageset * p)
```

```json
{
  "name": "pageset_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591270907,
      "name": "pageset_init",
      "external": false,
      "loc": "mm/page_alloc.c:6640",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/page_alloc.c:build_all_zonelists_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591270907,
      "name": "pageset_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void pageset_init(struct per_cpu_pageset * p)
```

```json
{
  "name": "pageset_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492888340,
      "name": "pageset_init",
      "external": false,
      "loc": "mm/page_alloc.c:6094",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/page_alloc.c:build_all_zonelists_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492888340,
      "name": "pageset_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void pageset_init(struct per_cpu_pageset * p)
```

```json
{
  "name": "pageset_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226685636,
      "name": "pageset_init",
      "external": false,
      "loc": "mm/page_alloc.c:6094",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/page_alloc.c:build_all_zonelists_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226685636,
      "name": "pageset_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void pageset_init(struct per_cpu_pageset * p)
```

```json
{
  "name": "pageset_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286285836,
      "name": "pageset_init",
      "external": false,
      "loc": "mm/page_alloc.c:6094",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/page_alloc.c:build_all_zonelists_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286285836,
      "name": "pageset_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
  "name": "pageset_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270889642,
      "name": "pageset_init",
      "external": false,
      "loc": "mm/page_alloc.c:6094",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/page_alloc.c:build_all_zonelists_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void pageset_init(struct per_cpu_pageset * p)
```

```json
{
  "name": "pageset_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581445856,
      "name": "pageset_init",
      "external": false,
      "loc": "mm/page_alloc.c:6094",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/page_alloc.c:build_all_zonelists_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581445856,
      "name": "pageset_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void pageset_init(struct per_cpu_pageset * p)
```

```json
{
  "name": "pageset_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581388224,
      "name": "pageset_init",
      "external": false,
      "loc": "mm/page_alloc.c:6094",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/page_alloc.c:build_all_zonelists_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581388224,
      "name": "pageset_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void pageset_init(struct per_cpu_pageset * p)
```

```json
{
  "name": "pageset_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581437056,
      "name": "pageset_init",
      "external": false,
      "loc": "mm/page_alloc.c:6094",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/page_alloc.c:build_all_zonelists_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581437056,
      "name": "pageset_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void pageset_init(struct per_cpu_pageset * p)
```

```json
{
  "name": "pageset_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581501552,
      "name": "pageset_init",
      "external": false,
      "loc": "mm/page_alloc.c:6094",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/page_alloc.c:build_all_zonelists_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581501552,
      "name": "pageset_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void pageset_init(struct per_cpu_pageset * p)
```
</details>
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void pageset_init(struct per_cpu_pageset * p)
```
</details>
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
void pageset_init(struct per_cpu_pageset * p)
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
