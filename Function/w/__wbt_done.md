# Function: <code>__wbt_done</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __wbt_done(struct rq_wb * rwb, enum wbt_flags wb_acct)
```

```json
{
  "name": "__wbt_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583344601,
      "name": "__wbt_done",
      "external": true,
      "loc": "block/blk-wbt.c:121",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_done"
      ],
      "caller_func": [
        "block/blk-core.c:blk_queue_bio",
        "block/blk-mq.c:blk_sq_make_request",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-wbt.c:wbt_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583342208,
      "name": "__wbt_done.part.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    },
    {
      "addr": 18446744071583344464,
      "name": "__wbt_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __wbt_done(struct rq_wb * rwb, enum wbt_flags wb_acct)
```

```json
{
  "name": "__wbt_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583402615,
      "name": "__wbt_done",
      "external": true,
      "loc": "block/blk-wbt.c:121",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_done"
      ],
      "caller_func": [
        "block/blk-core.c:blk_queue_bio",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-wbt.c:wbt_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583400592,
      "name": "__wbt_done.part.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446744071583402544,
      "name": "__wbt_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __wbt_done(struct rq_wb * rwb, enum wbt_flags wb_acct)
```

```json
{
  "name": "__wbt_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583582187,
      "name": "__wbt_done",
      "external": true,
      "loc": "block/blk-wbt.c:121",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_done"
      ],
      "caller_func": [
        "block/blk-core.c:blk_queue_bio",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-wbt.c:wbt_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583580144,
      "name": "__wbt_done.part.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446744071583582112,
      "name": "__wbt_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __wbt_done(struct rq_wb * rwb, enum wbt_flags wb_acct)
```

```json
{
  "name": "__wbt_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583798828,
      "name": "__wbt_done",
      "external": true,
      "loc": "block/blk-wbt.c:147",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_done"
      ],
      "caller_func": [
        "block/blk-core.c:blk_queue_bio",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-wbt.c:wbt_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583796688,
      "name": "__wbt_done.part.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    },
    {
      "addr": 18446744071583798720,
      "name": "__wbt_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void __wbt_done(struct rq_qos * rqos, enum wbt_flags wb_acct)
```

```json
{
  "name": "__wbt_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583878384,
      "name": "__wbt_done",
      "external": false,
      "loc": "block/blk-wbt.c:168",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wbt_cleanup",
        "block/blk-wbt.c:wbt_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583878384,
      "name": "__wbt_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void __wbt_done(struct rq_qos * rqos, enum wbt_flags wb_acct)
```

```json
{
  "name": "__wbt_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584069488,
      "name": "__wbt_done",
      "external": false,
      "loc": "block/blk-wbt.c:169",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wbt_cleanup",
        "block/blk-wbt.c:wbt_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584069488,
      "name": "__wbt_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void __wbt_done(struct rq_qos * rqos, enum wbt_flags wb_acct)
```

```json
{
  "name": "__wbt_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584192192,
      "name": "__wbt_done",
      "external": false,
      "loc": "block/blk-wbt.c:169",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wbt_cleanup",
        "block/blk-wbt.c:wbt_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584192192,
      "name": "__wbt_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__wbt_done",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584587849,
      "name": "__wbt_done",
      "external": false,
      "loc": "block/blk-wbt.c:169",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_cleanup",
        "block/blk-wbt.c:wbt_done"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__wbt_done",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584706393,
      "name": "__wbt_done",
      "external": false,
      "loc": "block/blk-wbt.c:169",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_cleanup",
        "block/blk-wbt.c:wbt_done"
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
  "name": "__wbt_done",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584734891,
      "name": "__wbt_done",
      "external": false,
      "loc": "block/blk-wbt.c:170",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_cleanup",
        "block/blk-wbt.c:wbt_done"
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
  "name": "__wbt_done",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585162635,
      "name": "__wbt_done",
      "external": false,
      "loc": "block/blk-wbt.c:170",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_cleanup",
        "block/blk-wbt.c:wbt_done"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__wbt_done",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585900155,
      "name": "__wbt_done",
      "external": false,
      "loc": "block/blk-wbt.c:170",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_cleanup",
        "block/blk-wbt.c:wbt_done"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__wbt_done",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586688059,
      "name": "__wbt_done",
      "external": false,
      "loc": "block/blk-wbt.c:171",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_cleanup",
        "block/blk-wbt.c:wbt_done"
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
  "name": "__wbt_done",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586949067,
      "name": "__wbt_done",
      "external": false,
      "loc": "block/blk-wbt.c:229",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_cleanup",
        "block/blk-wbt.c:wbt_done"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__wbt_done",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587229499,
      "name": "__wbt_done",
      "external": false,
      "loc": "block/blk-wbt.c:228",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_cleanup",
        "block/blk-wbt.c:wbt_done"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void __wbt_done(struct rq_qos * rqos, enum wbt_flags wb_acct)
```

```json
{
  "name": "__wbt_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496058696,
      "name": "__wbt_done",
      "external": false,
      "loc": "block/blk-wbt.c:169",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wbt_cleanup",
        "block/blk-wbt.c:wbt_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496058696,
      "name": "__wbt_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void __wbt_done(struct rq_qos * rqos, enum wbt_flags wb_acct)
```

```json
{
  "name": "__wbt_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229387052,
      "name": "__wbt_done",
      "external": false,
      "loc": "block/blk-wbt.c:169",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wbt_cleanup",
        "block/blk-wbt.c:wbt_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229387052,
      "name": "__wbt_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void __wbt_done(struct rq_qos * rqos, enum wbt_flags wb_acct)
```

```json
{
  "name": "__wbt_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290294224,
      "name": "__wbt_done",
      "external": false,
      "loc": "block/blk-wbt.c:169",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wbt_cleanup",
        "block/blk-wbt.c:wbt_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290294224,
      "name": "__wbt_done",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void __wbt_done(struct rq_qos * rqos, enum wbt_flags wb_acct)
```

```json
{
  "name": "__wbt_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275133846,
      "name": "__wbt_done",
      "external": false,
      "loc": "block/blk-wbt.c:169",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wbt_cleanup",
        "block/blk-wbt.c:wbt_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275133846,
      "name": "__wbt_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void __wbt_done(struct rq_qos * rqos, enum wbt_flags wb_acct)
```

```json
{
  "name": "__wbt_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584160928,
      "name": "__wbt_done",
      "external": false,
      "loc": "block/blk-wbt.c:169",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wbt_cleanup",
        "block/blk-wbt.c:wbt_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584160928,
      "name": "__wbt_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void __wbt_done(struct rq_qos * rqos, enum wbt_flags wb_acct)
```

```json
{
  "name": "__wbt_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584096192,
      "name": "__wbt_done",
      "external": false,
      "loc": "block/blk-wbt.c:169",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wbt_cleanup",
        "block/blk-wbt.c:wbt_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584096192,
      "name": "__wbt_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void __wbt_done(struct rq_qos * rqos, enum wbt_flags wb_acct)
```

```json
{
  "name": "__wbt_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584144688,
      "name": "__wbt_done",
      "external": false,
      "loc": "block/blk-wbt.c:169",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wbt_cleanup",
        "block/blk-wbt.c:wbt_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584144688,
      "name": "__wbt_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void __wbt_done(struct rq_qos * rqos, enum wbt_flags wb_acct)
```

```json
{
  "name": "__wbt_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584248656,
      "name": "__wbt_done",
      "external": false,
      "loc": "block/blk-wbt.c:169",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wbt_cleanup",
        "block/blk-wbt.c:wbt_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584248656,
      "name": "__wbt_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void __wbt_done(struct rq_wb * rwb, enum wbt_flags wb_acct)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct rq_qos * rqos</code>
</li>
<li>
<b>Param removed. </b>
<code>struct rq_wb * rwb</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void __wbt_done(struct rq_qos * rqos, enum wbt_flags wb_acct)
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
