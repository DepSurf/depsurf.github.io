# Function: <code>__node_reclaim</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__node_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580663760,
      "name": "__node_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:3710",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
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
  "name": "__node_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580731040,
      "name": "__node_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:3721",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
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
  "name": "__node_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580766919,
      "name": "__node_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:3824",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
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
  "name": "__node_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580854263,
      "name": "__node_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:3847",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
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
int __node_reclaim(struct pglist_data * pgdat, gfp_t gfp_mask, unsigned int order)
```

```json
{
  "name": "__node_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580991280,
      "name": "__node_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:3876",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:node_reclaim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580991280,
      "name": "__node_reclaim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
  "name": "__node_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581068392,
      "name": "__node_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:4169",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__node_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581131589,
      "name": "__node_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:4123",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__node_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581189333,
      "name": "__node_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:4209",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __node_reclaim(struct pglist_data * pgdat, gfp_t gfp_mask, unsigned int order)
```

```json
{
  "name": "__node_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581373472,
      "name": "__node_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:4167",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:node_reclaim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581373472,
      "name": "__node_reclaim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 579
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
int __node_reclaim(struct pglist_data * pgdat, gfp_t gfp_mask, unsigned int order)
```

```json
{
  "name": "__node_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581417296,
      "name": "__node_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:4170",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:node_reclaim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581417296,
      "name": "__node_reclaim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
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
int __node_reclaim(struct pglist_data * pgdat, gfp_t gfp_mask, unsigned int order)
```

```json
{
  "name": "__node_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581437328,
      "name": "__node_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:4360",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:node_reclaim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581437328,
      "name": "__node_reclaim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 534
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
int __node_reclaim(struct pglist_data * pgdat, gfp_t gfp_mask, unsigned int order)
```

```json
{
  "name": "__node_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__node_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:4549",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:node_reclaim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581690720,
      "name": "__node_reclaim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 621
    },
    {
      "addr": 18446744071592192099,
      "name": "__node_reclaim.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int __node_reclaim(struct pglist_data * pgdat, gfp_t gfp_mask, unsigned int order)
```

```json
{
  "name": "__node_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__node_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:4695",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:node_reclaim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582067296,
      "name": "__node_reclaim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 709
    },
    {
      "addr": 18446744071593968021,
      "name": "__node_reclaim.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int __node_reclaim(struct pglist_data * pgdat, gfp_t gfp_mask, unsigned int order)
```

```json
{
  "name": "__node_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__node_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:7640",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:node_reclaim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582539424,
      "name": "__node_reclaim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 718
    },
    {
      "addr": 18446744071596026921,
      "name": "__node_reclaim.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int __node_reclaim(struct pglist_data * pgdat, gfp_t gfp_mask, unsigned int order)
```

```json
{
  "name": "__node_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__node_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:8004",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:node_reclaim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582749040,
      "name": "__node_reclaim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 715
    },
    {
      "addr": 18446744071596549058,
      "name": "__node_reclaim.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int __node_reclaim(struct pglist_data * pgdat, gfp_t gfp_mask, unsigned int order)
```

```json
{
  "name": "__node_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__node_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:7372",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:node_reclaim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582916976,
      "name": "__node_reclaim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 798
    },
    {
      "addr": 18446744071597452652,
      "name": "__node_reclaim.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
  "name": "__node_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492570340,
      "name": "__node_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:4209",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__node_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285879080,
      "name": "__node_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:4209",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__node_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581158181,
      "name": "__node_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:4209",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__node_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581105045,
      "name": "__node_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:4209",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__node_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581149381,
      "name": "__node_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:4209",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__node_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581212037,
      "name": "__node_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:4209",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int __node_reclaim(struct pglist_data * pgdat, gfp_t gfp_mask, unsigned int order)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
int __node_reclaim(struct pglist_data * pgdat, gfp_t gfp_mask, unsigned int order)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int __node_reclaim(struct pglist_data * pgdat, gfp_t gfp_mask, unsigned int order)
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
