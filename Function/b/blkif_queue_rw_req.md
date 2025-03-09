# Function: <code>blkif_queue_rw_req</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blkif_queue_rw_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584572496,
      "name": "blkif_queue_rw_req",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:569",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
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
  "name": "blkif_queue_rw_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584922833,
      "name": "blkif_queue_rw_req",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:688",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
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
  "name": "blkif_queue_rw_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585106126,
      "name": "blkif_queue_rw_req",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:688",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
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
  "name": "blkif_queue_rw_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585182136,
      "name": "blkif_queue_rw_req",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:692",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
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
  "name": "blkif_queue_rw_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585610376,
      "name": "blkif_queue_rw_req",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:692",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blkif_queue_rw_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585856147,
      "name": "blkif_queue_rw_req",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:692",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blkif_queue_rw_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585987552,
      "name": "blkif_queue_rw_req",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:691",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int blkif_queue_rw_req(struct request * req, struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "blkif_queue_rw_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586231616,
      "name": "blkif_queue_rw_req",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:691",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586231616,
      "name": "blkif_queue_rw_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1442
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
int blkif_queue_rw_req(struct request * req, struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "blkif_queue_rw_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586379840,
      "name": "blkif_queue_rw_req",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:691",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586379840,
      "name": "blkif_queue_rw_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1442
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
int blkif_queue_rw_req(struct request * req, struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "blkif_queue_rw_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587160864,
      "name": "blkif_queue_rw_req",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:702",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587160864,
      "name": "blkif_queue_rw_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1511
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
int blkif_queue_rw_req(struct request * req, struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "blkif_queue_rw_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587245088,
      "name": "blkif_queue_rw_req",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:702",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587245088,
      "name": "blkif_queue_rw_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1511
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
int blkif_queue_rw_req(struct request * req, struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "blkif_queue_rw_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587132064,
      "name": "blkif_queue_rw_req",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:702",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587132064,
      "name": "blkif_queue_rw_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1473
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
int blkif_queue_rw_req(struct request * req, struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "blkif_queue_rw_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blkif_queue_rw_req",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:694",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587705584,
      "name": "blkif_queue_rw_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1415
    },
    {
      "addr": 18446744071592499935,
      "name": "blkif_queue_rw_req.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
int blkif_queue_rw_req(struct request * req, struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "blkif_queue_rw_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blkif_queue_rw_req",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:699",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589057088,
      "name": "blkif_queue_rw_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1577
    },
    {
      "addr": 18446744071594370405,
      "name": "blkif_queue_rw_req.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
int blkif_queue_rw_req(struct request * req, struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "blkif_queue_rw_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blkif_queue_rw_req",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:702",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590586640,
      "name": "blkif_queue_rw_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1577
    },
    {
      "addr": 18446744071596252169,
      "name": "blkif_queue_rw_req.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
int blkif_queue_rw_req(struct request * req, struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "blkif_queue_rw_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blkif_queue_rw_req",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:702",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590927824,
      "name": "blkif_queue_rw_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1676
    },
    {
      "addr": 18446744071596780835,
      "name": "blkif_queue_rw_req.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
int blkif_queue_rw_req(struct request * req, struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "blkif_queue_rw_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blkif_queue_rw_req",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:702",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591271648,
      "name": "blkif_queue_rw_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1617
    },
    {
      "addr": 18446744071597689769,
      "name": "blkif_queue_rw_req.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
int blkif_queue_rw_req(struct request * req, struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "blkif_queue_rw_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499226008,
      "name": "blkif_queue_rw_req",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:691",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499226008,
      "name": "blkif_queue_rw_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1208
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
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
int blkif_queue_rw_req(struct request * req, struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "blkif_queue_rw_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586142128,
      "name": "blkif_queue_rw_req",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:706",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586142128,
      "name": "blkif_queue_rw_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1442
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int blkif_queue_rw_req(struct request * req, struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "blkif_queue_rw_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586327808,
      "name": "blkif_queue_rw_req",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:691",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586327808,
      "name": "blkif_queue_rw_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1442
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
int blkif_queue_rw_req(struct request * req, struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "blkif_queue_rw_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586439488,
      "name": "blkif_queue_rw_req",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:691",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586439488,
      "name": "blkif_queue_rw_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1498
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
int blkif_queue_rw_req(struct request * req, struct blkfront_ring_info * rinfo)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int blkif_queue_rw_req(struct request * req, struct blkfront_ring_info * rinfo)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int blkif_queue_rw_req(struct request * req, struct blkfront_ring_info * rinfo)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int blkif_queue_rw_req(struct request * req, struct blkfront_ring_info * rinfo)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int blkif_queue_rw_req(struct request * req, struct blkfront_ring_info * rinfo)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
