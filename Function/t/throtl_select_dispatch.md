# Function: <code>throtl_select_dispatch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "throtl_select_dispatch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582889916,
      "name": "throtl_select_dispatch",
      "external": false,
      "loc": "block/blk-throttle.c:976",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_pending_timer_fn"
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
  "name": "throtl_select_dispatch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583175388,
      "name": "throtl_select_dispatch",
      "external": false,
      "loc": "block/blk-throttle.c:972",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_pending_timer_fn"
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
  "name": "throtl_select_dispatch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583286986,
      "name": "throtl_select_dispatch",
      "external": false,
      "loc": "block/blk-throttle.c:972",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_pending_timer_fn"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int throtl_select_dispatch(struct throtl_service_queue * parent_sq)
```

```json
{
  "name": "throtl_select_dispatch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583346736,
      "name": "throtl_select_dispatch",
      "external": false,
      "loc": "block/blk-throttle.c:1208",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_pending_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583346736,
      "name": "throtl_select_dispatch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
int throtl_select_dispatch(struct throtl_service_queue * parent_sq)
```

```json
{
  "name": "throtl_select_dispatch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583529056,
      "name": "throtl_select_dispatch",
      "external": false,
      "loc": "block/blk-throttle.c:1206",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_pending_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583529056,
      "name": "throtl_select_dispatch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
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
int throtl_select_dispatch(struct throtl_service_queue * parent_sq)
```

```json
{
  "name": "throtl_select_dispatch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583743696,
      "name": "throtl_select_dispatch",
      "external": false,
      "loc": "block/blk-throttle.c:1204",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_pending_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583743696,
      "name": "throtl_select_dispatch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
int throtl_select_dispatch(struct throtl_service_queue * parent_sq)
```

```json
{
  "name": "throtl_select_dispatch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583851184,
      "name": "throtl_select_dispatch",
      "external": false,
      "loc": "block/blk-throttle.c:1190",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_pending_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583851184,
      "name": "throtl_select_dispatch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
int throtl_select_dispatch(struct throtl_service_queue * parent_sq)
```

```json
{
  "name": "throtl_select_dispatch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584041728,
      "name": "throtl_select_dispatch",
      "external": false,
      "loc": "block/blk-throttle.c:1187",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_pending_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584041728,
      "name": "throtl_select_dispatch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
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
int throtl_select_dispatch(struct throtl_service_queue * parent_sq)
```

```json
{
  "name": "throtl_select_dispatch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584145664,
      "name": "throtl_select_dispatch",
      "external": false,
      "loc": "block/blk-throttle.c:1189",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_pending_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584145664,
      "name": "throtl_select_dispatch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
int throtl_select_dispatch(struct throtl_service_queue * parent_sq)
```

```json
{
  "name": "throtl_select_dispatch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584541792,
      "name": "throtl_select_dispatch",
      "external": false,
      "loc": "block/blk-throttle.c:1207",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_pending_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584541792,
      "name": "throtl_select_dispatch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
int throtl_select_dispatch(struct throtl_service_queue * parent_sq)
```

```json
{
  "name": "throtl_select_dispatch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584651792,
      "name": "throtl_select_dispatch",
      "external": false,
      "loc": "block/blk-throttle.c:1217",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_pending_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584651792,
      "name": "throtl_select_dispatch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
int throtl_select_dispatch(struct throtl_service_queue * parent_sq)
```

```json
{
  "name": "throtl_select_dispatch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584678688,
      "name": "throtl_select_dispatch",
      "external": false,
      "loc": "block/blk-throttle.c:1217",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_pending_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584678688,
      "name": "throtl_select_dispatch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int throtl_select_dispatch(struct throtl_service_queue * parent_sq)
```

```json
{
  "name": "throtl_select_dispatch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585100448,
      "name": "throtl_select_dispatch",
      "external": false,
      "loc": "block/blk-throttle.c:1228",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_pending_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585100448,
      "name": "throtl_select_dispatch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 449
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int throtl_select_dispatch(struct throtl_service_queue * parent_sq)
```

```json
{
  "name": "throtl_select_dispatch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585833008,
      "name": "throtl_select_dispatch",
      "external": false,
      "loc": "block/blk-throttle.c:1086",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_pending_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585833008,
      "name": "throtl_select_dispatch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 463
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
  "name": "throtl_select_dispatch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "throtl_select_dispatch",
      "external": false,
      "loc": "block/blk-throttle.c:1116",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_pending_timer_fn"
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
  "name": "throtl_select_dispatch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "throtl_select_dispatch",
      "external": false,
      "loc": "block/blk-throttle.c:1115",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_pending_timer_fn"
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
  "name": "throtl_select_dispatch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "throtl_select_dispatch",
      "external": false,
      "loc": "block/blk-throttle.c:1121",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_pending_timer_fn"
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
int throtl_select_dispatch(struct throtl_service_queue * parent_sq)
```

```json
{
  "name": "throtl_select_dispatch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495996192,
      "name": "throtl_select_dispatch",
      "external": false,
      "loc": "block/blk-throttle.c:1189",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_pending_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495996192,
      "name": "throtl_select_dispatch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
int throtl_select_dispatch(struct throtl_service_queue * parent_sq)
```

```json
{
  "name": "throtl_select_dispatch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229336920,
      "name": "throtl_select_dispatch",
      "external": false,
      "loc": "block/blk-throttle.c:1189",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_pending_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229336920,
      "name": "throtl_select_dispatch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
int throtl_select_dispatch(struct throtl_service_queue * parent_sq)
```

```json
{
  "name": "throtl_select_dispatch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290224224,
      "name": "throtl_select_dispatch",
      "external": false,
      "loc": "block/blk-throttle.c:1189",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_pending_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290224224,
      "name": "throtl_select_dispatch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 608
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
int throtl_select_dispatch(struct throtl_service_queue * parent_sq)
```

```json
{
  "name": "throtl_select_dispatch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275092806,
      "name": "throtl_select_dispatch",
      "external": false,
      "loc": "block/blk-throttle.c:1189",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_pending_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275092806,
      "name": "throtl_select_dispatch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
int throtl_select_dispatch(struct throtl_service_queue * parent_sq)
```

```json
{
  "name": "throtl_select_dispatch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584114400,
      "name": "throtl_select_dispatch",
      "external": false,
      "loc": "block/blk-throttle.c:1189",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_pending_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584114400,
      "name": "throtl_select_dispatch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
int throtl_select_dispatch(struct throtl_service_queue * parent_sq)
```

```json
{
  "name": "throtl_select_dispatch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584050080,
      "name": "throtl_select_dispatch",
      "external": false,
      "loc": "block/blk-throttle.c:1189",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_pending_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584050080,
      "name": "throtl_select_dispatch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
int throtl_select_dispatch(struct throtl_service_queue * parent_sq)
```

```json
{
  "name": "throtl_select_dispatch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584098160,
      "name": "throtl_select_dispatch",
      "external": false,
      "loc": "block/blk-throttle.c:1189",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_pending_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584098160,
      "name": "throtl_select_dispatch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
int throtl_select_dispatch(struct throtl_service_queue * parent_sq)
```

```json
{
  "name": "throtl_select_dispatch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584201600,
      "name": "throtl_select_dispatch",
      "external": false,
      "loc": "block/blk-throttle.c:1189",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_pending_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584201600,
      "name": "throtl_select_dispatch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
int throtl_select_dispatch(struct throtl_service_queue * parent_sq)
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
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int throtl_select_dispatch(struct throtl_service_queue * parent_sq)
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
