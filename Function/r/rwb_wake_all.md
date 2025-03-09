# Function: <code>rwb_wake_all</code>

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
void rwb_wake_all(struct rq_wb * rwb)
```

```json
{
  "name": "rwb_wake_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583341632,
      "name": "rwb_wake_all",
      "external": false,
      "loc": "block/blk-wbt.c:109",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wbt_init",
        "block/blk-wbt.c:wbt_disable_default",
        "block/blk-wbt.c:wbt_set_queue_depth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583341632,
      "name": "rwb_wake_all",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void rwb_wake_all(struct rq_wb * rwb)
```

```json
{
  "name": "rwb_wake_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583400128,
      "name": "rwb_wake_all",
      "external": false,
      "loc": "block/blk-wbt.c:109",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wbt_init",
        "block/blk-wbt.c:wbt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583400128,
      "name": "rwb_wake_all",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void rwb_wake_all(struct rq_wb * rwb)
```

```json
{
  "name": "rwb_wake_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583579680,
      "name": "rwb_wake_all",
      "external": false,
      "loc": "block/blk-wbt.c:109",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wbt_init",
        "block/blk-wbt.c:wbt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583579680,
      "name": "rwb_wake_all",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void rwb_wake_all(struct rq_wb * rwb)
```

```json
{
  "name": "rwb_wake_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583796240,
      "name": "rwb_wake_all",
      "external": false,
      "loc": "block/blk-wbt.c:135",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wbt_init",
        "block/blk-wbt.c:wbt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583796240,
      "name": "rwb_wake_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
void rwb_wake_all(struct rq_wb * rwb)
```

```json
{
  "name": "rwb_wake_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583878144,
      "name": "rwb_wake_all",
      "external": false,
      "loc": "block/blk-wbt.c:114",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:__wbt_update_limits",
        "block/blk-wbt.c:__wbt_update_limits",
        "block/blk-wbt.c:scale_up",
        "block/blk-wbt.c:wbt_rqw_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583878144,
      "name": "rwb_wake_all",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void rwb_wake_all(struct rq_wb * rwb)
```

```json
{
  "name": "rwb_wake_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584068688,
      "name": "rwb_wake_all",
      "external": false,
      "loc": "block/blk-wbt.c:115",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:__wbt_update_limits",
        "block/blk-wbt.c:__wbt_update_limits",
        "block/blk-wbt.c:scale_up",
        "block/blk-wbt.c:wbt_rqw_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584068688,
      "name": "rwb_wake_all",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void rwb_wake_all(struct rq_wb * rwb)
```

```json
{
  "name": "rwb_wake_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584191392,
      "name": "rwb_wake_all",
      "external": false,
      "loc": "block/blk-wbt.c:115",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:__wbt_update_limits",
        "block/blk-wbt.c:__wbt_update_limits",
        "block/blk-wbt.c:wbt_rqw_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584191392,
      "name": "rwb_wake_all",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rwb_wake_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584588644,
      "name": "rwb_wake_all",
      "external": false,
      "loc": "block/blk-wbt.c:115",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_update_limits",
        "block/blk-wbt.c:wbt_rqw_done"
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
  "name": "rwb_wake_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584707108,
      "name": "rwb_wake_all",
      "external": false,
      "loc": "block/blk-wbt.c:115",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_queue_depth_changed",
        "block/blk-wbt.c:wbt_set_min_lat",
        "block/blk-wbt.c:wbt_rqw_done"
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
  "name": "rwb_wake_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584735039,
      "name": "rwb_wake_all",
      "external": false,
      "loc": "block/blk-wbt.c:116",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_queue_depth_changed",
        "block/blk-wbt.c:wbt_set_min_lat",
        "block/blk-wbt.c:wbt_rqw_done"
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
  "name": "rwb_wake_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585162977,
      "name": "rwb_wake_all",
      "external": false,
      "loc": "block/blk-wbt.c:116",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_queue_depth_changed",
        "block/blk-wbt.c:wbt_set_min_lat",
        "block/blk-wbt.c:wbt_rqw_done"
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
  "name": "rwb_wake_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585900303,
      "name": "rwb_wake_all",
      "external": false,
      "loc": "block/blk-wbt.c:116",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_queue_depth_changed",
        "block/blk-wbt.c:wbt_set_min_lat",
        "block/blk-wbt.c:wbt_rqw_done"
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
  "name": "rwb_wake_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586688223,
      "name": "rwb_wake_all",
      "external": false,
      "loc": "block/blk-wbt.c:117",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_queue_depth_changed",
        "block/blk-wbt.c:wbt_set_min_lat",
        "block/blk-wbt.c:wbt_rqw_done"
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
  "name": "rwb_wake_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586948831,
      "name": "rwb_wake_all",
      "external": false,
      "loc": "block/blk-wbt.c:184",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_update_limits"
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
  "name": "rwb_wake_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587229263,
      "name": "rwb_wake_all",
      "external": false,
      "loc": "block/blk-wbt.c:182",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_update_limits"
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
void rwb_wake_all(struct rq_wb * rwb)
```

```json
{
  "name": "rwb_wake_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496056568,
      "name": "rwb_wake_all",
      "external": false,
      "loc": "block/blk-wbt.c:115",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:__wbt_update_limits",
        "block/blk-wbt.c:__wbt_update_limits",
        "block/blk-wbt.c:wbt_rqw_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496056568,
      "name": "rwb_wake_all",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void rwb_wake_all(struct rq_wb * rwb)
```

```json
{
  "name": "rwb_wake_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229386720,
      "name": "rwb_wake_all",
      "external": false,
      "loc": "block/blk-wbt.c:115",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:__wbt_update_limits",
        "block/blk-wbt.c:wbt_rqw_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229386720,
      "name": "rwb_wake_all",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void rwb_wake_all(struct rq_wb * rwb)
```

```json
{
  "name": "rwb_wake_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290292832,
      "name": "rwb_wake_all",
      "external": false,
      "loc": "block/blk-wbt.c:115",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:__wbt_update_limits",
        "block/blk-wbt.c:__wbt_update_limits",
        "block/blk-wbt.c:wbt_rqw_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290292832,
      "name": "rwb_wake_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
void rwb_wake_all(struct rq_wb * rwb)
```

```json
{
  "name": "rwb_wake_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275132882,
      "name": "rwb_wake_all",
      "external": false,
      "loc": "block/blk-wbt.c:115",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:__wbt_update_limits",
        "block/blk-wbt.c:__wbt_update_limits",
        "block/blk-wbt.c:wbt_rqw_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275132882,
      "name": "rwb_wake_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void rwb_wake_all(struct rq_wb * rwb)
```

```json
{
  "name": "rwb_wake_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584160128,
      "name": "rwb_wake_all",
      "external": false,
      "loc": "block/blk-wbt.c:115",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:__wbt_update_limits",
        "block/blk-wbt.c:__wbt_update_limits",
        "block/blk-wbt.c:wbt_rqw_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584160128,
      "name": "rwb_wake_all",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void rwb_wake_all(struct rq_wb * rwb)
```

```json
{
  "name": "rwb_wake_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584095392,
      "name": "rwb_wake_all",
      "external": false,
      "loc": "block/blk-wbt.c:115",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:__wbt_update_limits",
        "block/blk-wbt.c:__wbt_update_limits",
        "block/blk-wbt.c:wbt_rqw_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584095392,
      "name": "rwb_wake_all",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void rwb_wake_all(struct rq_wb * rwb)
```

```json
{
  "name": "rwb_wake_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584143888,
      "name": "rwb_wake_all",
      "external": false,
      "loc": "block/blk-wbt.c:115",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:__wbt_update_limits",
        "block/blk-wbt.c:__wbt_update_limits",
        "block/blk-wbt.c:wbt_rqw_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584143888,
      "name": "rwb_wake_all",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void rwb_wake_all(struct rq_wb * rwb)
```

```json
{
  "name": "rwb_wake_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584247856,
      "name": "rwb_wake_all",
      "external": false,
      "loc": "block/blk-wbt.c:115",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:__wbt_update_limits",
        "block/blk-wbt.c:__wbt_update_limits",
        "block/blk-wbt.c:wbt_rqw_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584247856,
      "name": "rwb_wake_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void rwb_wake_all(struct rq_wb * rwb)
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void rwb_wake_all(struct rq_wb * rwb)
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
