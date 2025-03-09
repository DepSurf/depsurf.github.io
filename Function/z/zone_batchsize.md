# Function: <code>zone_batchsize</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zone_batchsize",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580490816,
      "name": "zone_batchsize",
      "external": false,
      "loc": "mm/page_alloc.c:4534",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580490816,
      "name": "zone_batchsize.isra.62",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
  "name": "zone_batchsize",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580575760,
      "name": "zone_batchsize",
      "external": false,
      "loc": "mm/page_alloc.c:5070",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580575760,
      "name": "zone_batchsize.isra.68",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
  "name": "zone_batchsize",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580642128,
      "name": "zone_batchsize",
      "external": false,
      "loc": "mm/page_alloc.c:5153",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580642128,
      "name": "zone_batchsize.isra.70",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
  "name": "zone_batchsize",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580674704,
      "name": "zone_batchsize",
      "external": false,
      "loc": "mm/page_alloc.c:5452",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580674704,
      "name": "zone_batchsize.isra.73",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
  "name": "zone_batchsize",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580760080,
      "name": "zone_batchsize",
      "external": false,
      "loc": "mm/page_alloc.c:5424",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580760080,
      "name": "zone_batchsize.isra.74",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
  "name": "zone_batchsize",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580895952,
      "name": "zone_batchsize",
      "external": false,
      "loc": "mm/page_alloc.c:5562",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580895952,
      "name": "zone_batchsize.isra.80",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
int zone_batchsize(struct zone * zone)
```

```json
{
  "name": "zone_batchsize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580968736,
      "name": "zone_batchsize",
      "external": false,
      "loc": "mm/page_alloc.c:5808",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:zone_pcp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580968736,
      "name": "zone_batchsize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
int zone_batchsize(struct zone * zone)
```

```json
{
  "name": "zone_batchsize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581386448,
      "name": "zone_batchsize",
      "external": false,
      "loc": "mm/page_alloc.c:5994",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:zone_pcp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581386448,
      "name": "zone_batchsize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
int zone_batchsize(struct zone * zone)
```

```json
{
  "name": "zone_batchsize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581447392,
      "name": "zone_batchsize",
      "external": false,
      "loc": "mm/page_alloc.c:6012",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:zone_pcp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581447392,
      "name": "zone_batchsize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
int zone_batchsize(struct zone * zone)
```

```json
{
  "name": "zone_batchsize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581652560,
      "name": "zone_batchsize",
      "external": false,
      "loc": "mm/page_alloc.c:6109",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:zone_pcp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581652560,
      "name": "zone_batchsize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
int zone_batchsize(struct zone * zone)
```

```json
{
  "name": "zone_batchsize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581700144,
      "name": "zone_batchsize",
      "external": false,
      "loc": "mm/page_alloc.c:6347",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:zone_pcp_init",
        "mm/page_alloc.c:zone_set_pageset_high_and_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581700144,
      "name": "zone_batchsize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
int zone_batchsize(struct zone * zone)
```

```json
{
  "name": "zone_batchsize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581721856,
      "name": "zone_batchsize",
      "external": false,
      "loc": "mm/page_alloc.c:6568",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:zone_pcp_init",
        "mm/page_alloc.c:zone_set_pageset_high_and_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581721856,
      "name": "zone_batchsize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
int zone_batchsize(struct zone * zone)
```

```json
{
  "name": "zone_batchsize",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581996661,
      "name": "zone_batchsize",
      "external": false,
      "loc": "mm/page_alloc.c:6764",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:zone_set_pageset_high_and_batch"
      ],
      "caller_func": [
        "mm/page_alloc.c:zone_init_internals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581994080,
      "name": "zone_batchsize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071592202319,
      "name": "zone_batchsize.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
int zone_batchsize(struct zone * zone)
```

```json
{
  "name": "zone_batchsize",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582420869,
      "name": "zone_batchsize",
      "external": false,
      "loc": "mm/page_alloc.c:6885",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:zone_set_pageset_high_and_batch"
      ],
      "caller_func": [
        "mm/page_alloc.c:zone_init_internals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582417328,
      "name": "zone_batchsize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071593979573,
      "name": "zone_batchsize.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zone_batchsize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596440731,
      "name": "zone_batchsize",
      "external": false,
      "loc": "mm/page_alloc.c:7057",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:zone_pcp_init",
        "mm/page_alloc.c:zone_set_pageset_high_and_batch"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zone_batchsize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596984091,
      "name": "zone_batchsize",
      "external": false,
      "loc": "mm/page_alloc.c:5262",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:zone_pcp_init",
        "mm/page_alloc.c:zone_set_pageset_high_and_batch"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int zone_batchsize(struct zone * zone)
```

```json
{
  "name": "zone_batchsize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "zone_batchsize",
      "external": false,
      "loc": "mm/page_alloc.c:5351",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:zone_pcp_init",
        "mm/page_alloc.c:zone_set_pageset_high_and_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583324864,
      "name": "zone_batchsize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071597461739,
      "name": "zone_batchsize.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
int zone_batchsize(struct zone * zone)
```

```json
{
  "name": "zone_batchsize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492853880,
      "name": "zone_batchsize",
      "external": false,
      "loc": "mm/page_alloc.c:6012",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:zone_pcp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492853880,
      "name": "zone_batchsize",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int zone_batchsize(struct zone * zone)
```

```json
{
  "name": "zone_batchsize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226654600,
      "name": "zone_batchsize",
      "external": false,
      "loc": "mm/page_alloc.c:6012",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226654600,
      "name": "zone_batchsize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
int zone_batchsize(struct zone * zone)
```

```json
{
  "name": "zone_batchsize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286242032,
      "name": "zone_batchsize",
      "external": false,
      "loc": "mm/page_alloc.c:6012",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:zone_init_internals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286242032,
      "name": "zone_batchsize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
int zone_batchsize(struct zone * zone)
```

```json
{
  "name": "zone_batchsize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272804140,
      "name": "zone_batchsize",
      "external": false,
      "loc": "mm/page_alloc.c:6012",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272804140,
      "name": "zone_batchsize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
int zone_batchsize(struct zone * zone)
```

```json
{
  "name": "zone_batchsize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581416240,
      "name": "zone_batchsize",
      "external": false,
      "loc": "mm/page_alloc.c:6012",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:zone_pcp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581416240,
      "name": "zone_batchsize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
int zone_batchsize(struct zone * zone)
```

```json
{
  "name": "zone_batchsize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581358752,
      "name": "zone_batchsize",
      "external": false,
      "loc": "mm/page_alloc.c:6012",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:zone_pcp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581358752,
      "name": "zone_batchsize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
int zone_batchsize(struct zone * zone)
```

```json
{
  "name": "zone_batchsize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581407440,
      "name": "zone_batchsize",
      "external": false,
      "loc": "mm/page_alloc.c:6012",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:zone_pcp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581407440,
      "name": "zone_batchsize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
int zone_batchsize(struct zone * zone)
```

```json
{
  "name": "zone_batchsize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581471536,
      "name": "zone_batchsize",
      "external": false,
      "loc": "mm/page_alloc.c:6012",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:zone_pcp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581471536,
      "name": "zone_batchsize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int zone_batchsize(struct zone * zone)
```
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int zone_batchsize(struct zone * zone)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
int zone_batchsize(struct zone * zone)
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
