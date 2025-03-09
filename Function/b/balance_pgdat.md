# Function: <code>balance_pgdat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "balance_pgdat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580572188,
      "name": "balance_pgdat",
      "external": false,
      "loc": "mm/vmscan.c:3156",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd"
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
  "name": "balance_pgdat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580664660,
      "name": "balance_pgdat",
      "external": false,
      "loc": "mm/vmscan.c:3191",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd"
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
  "name": "balance_pgdat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580731929,
      "name": "balance_pgdat",
      "external": false,
      "loc": "mm/vmscan.c:3202",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "balance_pgdat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580767953,
      "name": "balance_pgdat",
      "external": false,
      "loc": "mm/vmscan.c:3290",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "balance_pgdat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580855267,
      "name": "balance_pgdat",
      "external": false,
      "loc": "mm/vmscan.c:3314",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int balance_pgdat(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "balance_pgdat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580992288,
      "name": "balance_pgdat",
      "external": false,
      "loc": "mm/vmscan.c:3323",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580992288,
      "name": "balance_pgdat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 833
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
int balance_pgdat(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "balance_pgdat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581069216,
      "name": "balance_pgdat",
      "external": false,
      "loc": "mm/vmscan.c:3534",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581069216,
      "name": "balance_pgdat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1376
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
int balance_pgdat(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "balance_pgdat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581132640,
      "name": "balance_pgdat",
      "external": false,
      "loc": "mm/vmscan.c:3492",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581132640,
      "name": "balance_pgdat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1424
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
int balance_pgdat(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "balance_pgdat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581190384,
      "name": "balance_pgdat",
      "external": false,
      "loc": "mm/vmscan.c:3578",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581190384,
      "name": "balance_pgdat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1424
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
int balance_pgdat(pg_data_t * pgdat, int order, int highest_zoneidx)
```

```json
{
  "name": "balance_pgdat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581374304,
      "name": "balance_pgdat",
      "external": false,
      "loc": "mm/vmscan.c:3553",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581374304,
      "name": "balance_pgdat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1355
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
int balance_pgdat(pg_data_t * pgdat, int order, int highest_zoneidx)
```

```json
{
  "name": "balance_pgdat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581418064,
      "name": "balance_pgdat",
      "external": false,
      "loc": "mm/vmscan.c:3551",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581418064,
      "name": "balance_pgdat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1420
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
int balance_pgdat(pg_data_t * pgdat, int order, int highest_zoneidx)
```

```json
{
  "name": "balance_pgdat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581439104,
      "name": "balance_pgdat",
      "external": false,
      "loc": "mm/vmscan.c:3749",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581439104,
      "name": "balance_pgdat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1641
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
int balance_pgdat(pg_data_t * pgdat, int order, int highest_zoneidx)
```

```json
{
  "name": "balance_pgdat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "balance_pgdat",
      "external": false,
      "loc": "mm/vmscan.c:3938",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581692576,
      "name": "balance_pgdat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2031
    },
    {
      "addr": 18446744071592192161,
      "name": "balance_pgdat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
int balance_pgdat(pg_data_t * pgdat, int order, int highest_zoneidx)
```

```json
{
  "name": "balance_pgdat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "balance_pgdat",
      "external": false,
      "loc": "mm/vmscan.c:4084",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582064624,
      "name": "balance_pgdat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2173
    },
    {
      "addr": 18446744071593967937,
      "name": "balance_pgdat.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int balance_pgdat(pg_data_t * pgdat, int order, int highest_zoneidx)
```

```json
{
  "name": "balance_pgdat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "balance_pgdat",
      "external": false,
      "loc": "mm/vmscan.c:7025",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582536688,
      "name": "balance_pgdat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2210
    },
    {
      "addr": 18446744071596026837,
      "name": "balance_pgdat.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int balance_pgdat(pg_data_t * pgdat, int order, int highest_zoneidx)
```

```json
{
  "name": "balance_pgdat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "balance_pgdat",
      "external": false,
      "loc": "mm/vmscan.c:7389",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582746320,
      "name": "balance_pgdat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2187
    },
    {
      "addr": 18446744071596549001,
      "name": "balance_pgdat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
int balance_pgdat(pg_data_t * pgdat, int order, int highest_zoneidx)
```

```json
{
  "name": "balance_pgdat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "balance_pgdat",
      "external": false,
      "loc": "mm/vmscan.c:6756",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582914256,
      "name": "balance_pgdat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2187
    },
    {
      "addr": 18446744071597452595,
      "name": "balance_pgdat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
int balance_pgdat(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "balance_pgdat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492571584,
      "name": "balance_pgdat",
      "external": false,
      "loc": "mm/vmscan.c:3578",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492571584,
      "name": "balance_pgdat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1448
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
int balance_pgdat(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "balance_pgdat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226434092,
      "name": "balance_pgdat",
      "external": false,
      "loc": "mm/vmscan.c:3578",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226434092,
      "name": "balance_pgdat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1396
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
int balance_pgdat(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "balance_pgdat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285880656,
      "name": "balance_pgdat",
      "external": false,
      "loc": "mm/vmscan.c:3578",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285880656,
      "name": "balance_pgdat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1752
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
int balance_pgdat(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "balance_pgdat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272613218,
      "name": "balance_pgdat",
      "external": false,
      "loc": "mm/vmscan.c:3578",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272613218,
      "name": "balance_pgdat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1204
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
int balance_pgdat(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "balance_pgdat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581159232,
      "name": "balance_pgdat",
      "external": false,
      "loc": "mm/vmscan.c:3578",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581159232,
      "name": "balance_pgdat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1424
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
int balance_pgdat(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "balance_pgdat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581106096,
      "name": "balance_pgdat",
      "external": false,
      "loc": "mm/vmscan.c:3578",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581106096,
      "name": "balance_pgdat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1424
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
int balance_pgdat(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "balance_pgdat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581150432,
      "name": "balance_pgdat",
      "external": false,
      "loc": "mm/vmscan.c:3578",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581150432,
      "name": "balance_pgdat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1424
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
int balance_pgdat(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "balance_pgdat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581213168,
      "name": "balance_pgdat",
      "external": false,
      "loc": "mm/vmscan.c:3578",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581213168,
      "name": "balance_pgdat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1419
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int balance_pgdat(pg_data_t * pgdat, int order, int classzone_idx)
```
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int highest_zoneidx</code>
</li>
<li>
<b>Param removed. </b>
<code>int classzone_idx</code>
</li>
</ul>
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
