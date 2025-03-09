# Function: <code>scale_down</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void scale_down(struct rq_wb * rwb, bool hard_throttle)
```

```json
{
  "name": "scale_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583342032,
      "name": "scale_down",
      "external": false,
      "loc": "block/blk-wbt.c:371",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583342032,
      "name": "scale_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
  "name": "scale_down",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583401283,
      "name": "scale_down",
      "external": false,
      "loc": "block/blk-wbt.c:362",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn"
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
  "name": "scale_down",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583580867,
      "name": "scale_down",
      "external": false,
      "loc": "block/blk-wbt.c:361",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn"
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
  "name": "scale_down",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583798298,
      "name": "scale_down",
      "external": false,
      "loc": "block/blk-wbt.c:390",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void scale_down(struct rq_wb * rwb, bool hard_throttle)
```

```json
{
  "name": "scale_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583879680,
      "name": "scale_down",
      "external": false,
      "loc": "block/blk-wbt.c:317",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583879680,
      "name": "scale_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
void scale_down(struct rq_wb * rwb, bool hard_throttle)
```

```json
{
  "name": "scale_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584070272,
      "name": "scale_down",
      "external": false,
      "loc": "block/blk-wbt.c:318",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584070272,
      "name": "scale_down",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scale_down(struct rq_wb * rwb, bool hard_throttle)
```

```json
{
  "name": "scale_down",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584193456,
      "name": "scale_down",
      "external": false,
      "loc": "block/blk-wbt.c:319",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584193456,
      "name": "scale_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
  "name": "scale_down",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584590337,
      "name": "scale_down",
      "external": false,
      "loc": "block/blk-wbt.c:319",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn"
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
  "name": "scale_down",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584707907,
      "name": "scale_down",
      "external": false,
      "loc": "block/blk-wbt.c:319",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn"
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
  "name": "scale_down",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584737196,
      "name": "scale_down",
      "external": false,
      "loc": "block/blk-wbt.c:320",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn"
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
  "name": "scale_down",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585165075,
      "name": "scale_down",
      "external": false,
      "loc": "block/blk-wbt.c:320",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn"
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
  "name": "scale_down",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585901213,
      "name": "scale_down",
      "external": false,
      "loc": "block/blk-wbt.c:320",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn"
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
  "name": "scale_down",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586689086,
      "name": "scale_down",
      "external": false,
      "loc": "block/blk-wbt.c:321",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn"
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
  "name": "scale_down",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586949984,
      "name": "scale_down",
      "external": false,
      "loc": "block/blk-wbt.c:389",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn"
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
  "name": "scale_down",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587230413,
      "name": "scale_down",
      "external": false,
      "loc": "block/blk-wbt.c:388",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "scale_down",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496062464,
      "name": "scale_down",
      "external": false,
      "loc": "block/blk-wbt.c:319",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn"
      ],
      "caller_func": [
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496060160,
      "name": "scale_down.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
void scale_down(struct rq_wb * rwb, bool hard_throttle)
```

```json
{
  "name": "scale_down",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229389164,
      "name": "scale_down",
      "external": false,
      "loc": "block/blk-wbt.c:319",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229389164,
      "name": "scale_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void scale_down(struct rq_wb * rwb, bool hard_throttle)
```

```json
{
  "name": "scale_down",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290296256,
      "name": "scale_down",
      "external": false,
      "loc": "block/blk-wbt.c:319",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290296256,
      "name": "scale_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
void scale_down(struct rq_wb * rwb, bool hard_throttle)
```

```json
{
  "name": "scale_down",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275135366,
      "name": "scale_down",
      "external": false,
      "loc": "block/blk-wbt.c:319",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275135366,
      "name": "scale_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void scale_down(struct rq_wb * rwb, bool hard_throttle)
```

```json
{
  "name": "scale_down",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584162192,
      "name": "scale_down",
      "external": false,
      "loc": "block/blk-wbt.c:319",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584162192,
      "name": "scale_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void scale_down(struct rq_wb * rwb, bool hard_throttle)
```

```json
{
  "name": "scale_down",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584097456,
      "name": "scale_down",
      "external": false,
      "loc": "block/blk-wbt.c:319",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584097456,
      "name": "scale_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void scale_down(struct rq_wb * rwb, bool hard_throttle)
```

```json
{
  "name": "scale_down",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584145952,
      "name": "scale_down",
      "external": false,
      "loc": "block/blk-wbt.c:319",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584145952,
      "name": "scale_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scale_down",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584251907,
      "name": "scale_down",
      "external": false,
      "loc": "block/blk-wbt.c:319",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn"
      ],
      "caller_func": [
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584250096,
      "name": "scale_down.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
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
void scale_down(struct rq_wb * rwb, bool hard_throttle)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void scale_down(struct rq_wb * rwb, bool hard_throttle)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void scale_down(struct rq_wb * rwb, bool hard_throttle)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void scale_down(struct rq_wb * rwb, bool hard_throttle)
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
void scale_down(struct rq_wb * rwb, bool hard_throttle)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ➖</summary>

```c
void scale_down(struct rq_wb * rwb, bool hard_throttle)
```
</details>
</li>
</ul>
