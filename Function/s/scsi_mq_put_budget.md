# Function: <code>scsi_mq_put_budget</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void scsi_mq_put_budget(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "scsi_mq_put_budget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585866336,
      "name": "scsi_mq_put_budget",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1965",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585866336,
      "name": "scsi_mq_put_budget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void scsi_mq_put_budget(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "scsi_mq_put_budget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586112768,
      "name": "scsi_mq_put_budget",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:2001",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586112768,
      "name": "scsi_mq_put_budget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
void scsi_mq_put_budget(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "scsi_mq_put_budget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586259104,
      "name": "scsi_mq_put_budget",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1660",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586259104,
      "name": "scsi_mq_put_budget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_mq_put_budget(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "scsi_mq_put_budget",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586515113,
      "name": "scsi_mq_put_budget",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1611",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586503072,
      "name": "scsi_mq_put_budget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
void scsi_mq_put_budget(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "scsi_mq_put_budget",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586663116,
      "name": "scsi_mq_put_budget",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1623",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586650896,
      "name": "scsi_mq_put_budget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_mq_put_budget(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "scsi_mq_put_budget",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587462672,
      "name": "scsi_mq_put_budget",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1611",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587447632,
      "name": "scsi_mq_put_budget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_mq_put_budget(struct request_queue * q)
```

```json
{
  "name": "scsi_mq_put_budget",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587530635,
      "name": "scsi_mq_put_budget",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1607",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587515600,
      "name": "scsi_mq_put_budget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_mq_put_budget(struct request_queue * q, int budget_token)
```

```json
{
  "name": "scsi_mq_put_budget",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587412676,
      "name": "scsi_mq_put_budget",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1585",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587406832,
      "name": "scsi_mq_put_budget",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void scsi_mq_put_budget(struct request_queue * q, int budget_token)
```

```json
{
  "name": "scsi_mq_put_budget",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587984983,
      "name": "scsi_mq_put_budget",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1587",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587979264,
      "name": "scsi_mq_put_budget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    },
    {
      "addr": 18446744071592527127,
      "name": "scsi_mq_put_budget.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void scsi_mq_put_budget(struct request_queue * q, int budget_token)
```

```json
{
  "name": "scsi_mq_put_budget",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589342541,
      "name": "scsi_mq_put_budget",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1645",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589336384,
      "name": "scsi_mq_put_budget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    },
    {
      "addr": 18446744071594398839,
      "name": "scsi_mq_put_budget.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void scsi_mq_put_budget(struct request_queue * q, int budget_token)
```

```json
{
  "name": "scsi_mq_put_budget",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590909831,
      "name": "scsi_mq_put_budget",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1645",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590902640,
      "name": "scsi_mq_put_budget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    },
    {
      "addr": 18446744071596260002,
      "name": "scsi_mq_put_budget.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void scsi_mq_put_budget(struct request_queue * q, int budget_token)
```

```json
{
  "name": "scsi_mq_put_budget",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591253133,
      "name": "scsi_mq_put_budget",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1650",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591246480,
      "name": "scsi_mq_put_budget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071596788025,
      "name": "scsi_mq_put_budget.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void scsi_mq_put_budget(struct request_queue * q, int budget_token)
```

```json
{
  "name": "scsi_mq_put_budget",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591600357,
      "name": "scsi_mq_put_budget",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1647",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591593760,
      "name": "scsi_mq_put_budget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    },
    {
      "addr": 18446744071597697001,
      "name": "scsi_mq_put_budget.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void scsi_mq_put_budget(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "scsi_mq_put_budget",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499563296,
      "name": "scsi_mq_put_budget",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1623",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499556352,
      "name": "scsi_mq_put_budget",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void scsi_mq_put_budget(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "scsi_mq_put_budget",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232025340,
      "name": "scsi_mq_put_budget",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1623",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3232012320,
      "name": "scsi_mq_put_budget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void scsi_mq_put_budget(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "scsi_mq_put_budget",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292859068,
      "name": "scsi_mq_put_budget",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1623",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292841968,
      "name": "scsi_mq_put_budget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void scsi_mq_put_budget(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "scsi_mq_put_budget",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276759692,
      "name": "scsi_mq_put_budget",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1623",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276748452,
      "name": "scsi_mq_put_budget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
void scsi_mq_put_budget(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "scsi_mq_put_budget",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586353596,
      "name": "scsi_mq_put_budget",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1623",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586341376,
      "name": "scsi_mq_put_budget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
void scsi_mq_put_budget(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "scsi_mq_put_budget",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586194924,
      "name": "scsi_mq_put_budget",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1623",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586182704,
      "name": "scsi_mq_put_budget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
void scsi_mq_put_budget(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "scsi_mq_put_budget",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586611084,
      "name": "scsi_mq_put_budget",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1623",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586598864,
      "name": "scsi_mq_put_budget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_mq_put_budget(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "scsi_mq_put_budget",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586723529,
      "name": "scsi_mq_put_budget",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1623",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586711120,
      "name": "scsi_mq_put_budget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void scsi_mq_put_budget(struct blk_mq_hw_ctx * hctx)
```
</details>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct request_queue * q</code>
</li>
<li>
<b>Param removed. </b>
<code>struct blk_mq_hw_ctx * hctx</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int budget_token</code>
</li>
</ul>
</details>
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
