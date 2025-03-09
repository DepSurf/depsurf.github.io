# Function: <code>throtl_start_new_slice</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void throtl_start_new_slice(struct throtl_grp * tg, bool rw)
```

```json
{
  "name": "throtl_start_new_slice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582884256,
      "name": "throtl_start_new_slice",
      "external": false,
      "loc": "block/blk-throttle.c:572",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582884256,
      "name": "throtl_start_new_slice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void throtl_start_new_slice(struct throtl_grp * tg, bool rw)
```

```json
{
  "name": "throtl_start_new_slice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583170160,
      "name": "throtl_start_new_slice",
      "external": false,
      "loc": "block/blk-throttle.c:566",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_may_dispatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583170160,
      "name": "throtl_start_new_slice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void throtl_start_new_slice(struct throtl_grp * tg, bool rw)
```

```json
{
  "name": "throtl_start_new_slice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583281120,
      "name": "throtl_start_new_slice",
      "external": false,
      "loc": "block/blk-throttle.c:566",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_may_dispatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583281120,
      "name": "throtl_start_new_slice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
void throtl_start_new_slice(struct throtl_grp * tg, bool rw)
```

```json
{
  "name": "throtl_start_new_slice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583338384,
      "name": "throtl_start_new_slice",
      "external": false,
      "loc": "block/blk-throttle.c:792",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_may_dispatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583338384,
      "name": "throtl_start_new_slice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 385
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
  "name": "throtl_start_new_slice",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583525284,
      "name": "throtl_start_new_slice",
      "external": false,
      "loc": "block/blk-throttle.c:790",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_may_dispatch"
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
  "name": "throtl_start_new_slice",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583739624,
      "name": "throtl_start_new_slice",
      "external": false,
      "loc": "block/blk-throttle.c:788",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_may_dispatch"
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
  "name": "throtl_start_new_slice",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583847139,
      "name": "throtl_start_new_slice",
      "external": false,
      "loc": "block/blk-throttle.c:779",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_may_dispatch"
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
  "name": "throtl_start_new_slice",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584037624,
      "name": "throtl_start_new_slice",
      "external": false,
      "loc": "block/blk-throttle.c:779",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_may_dispatch"
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
  "name": "throtl_start_new_slice",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584141769,
      "name": "throtl_start_new_slice",
      "external": false,
      "loc": "block/blk-throttle.c:781",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_may_dispatch"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void throtl_start_new_slice(struct throtl_grp * tg, bool rw)
```

```json
{
  "name": "throtl_start_new_slice",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584543817,
      "name": "throtl_start_new_slice",
      "external": false,
      "loc": "block/blk-throttle.c:799",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated"
      ],
      "caller_func": [
        "block/blk-throttle.c:tg_may_dispatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584532352,
      "name": "throtl_start_new_slice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
void throtl_start_new_slice(struct throtl_grp * tg, bool rw)
```

```json
{
  "name": "throtl_start_new_slice",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584653883,
      "name": "throtl_start_new_slice",
      "external": false,
      "loc": "block/blk-throttle.c:796",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated"
      ],
      "caller_func": [
        "block/blk-throttle.c:tg_may_dispatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584646832,
      "name": "throtl_start_new_slice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
void throtl_start_new_slice(struct throtl_grp * tg, bool rw)
```

```json
{
  "name": "throtl_start_new_slice",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584681273,
      "name": "throtl_start_new_slice",
      "external": false,
      "loc": "block/blk-throttle.c:796",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated"
      ],
      "caller_func": [
        "block/blk-throttle.c:tg_may_dispatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584674560,
      "name": "throtl_start_new_slice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void throtl_start_new_slice(struct throtl_grp * tg, bool rw)
```

```json
{
  "name": "throtl_start_new_slice",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585103182,
      "name": "throtl_start_new_slice",
      "external": false,
      "loc": "block/blk-throttle.c:801",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated"
      ],
      "caller_func": [
        "block/blk-throttle.c:tg_may_dispatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585093008,
      "name": "throtl_start_new_slice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 709
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void throtl_start_new_slice(struct throtl_grp * tg, bool rw)
```

```json
{
  "name": "throtl_start_new_slice",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585829659,
      "name": "throtl_start_new_slice",
      "external": false,
      "loc": "block/blk-throttle.c:659",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated"
      ],
      "caller_func": [
        "block/blk-throttle.c:tg_may_dispatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585819808,
      "name": "throtl_start_new_slice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 671
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void throtl_start_new_slice(struct throtl_grp * tg, bool rw, bool clear_carryover)
```

```json
{
  "name": "throtl_start_new_slice",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586612537,
      "name": "throtl_start_new_slice",
      "external": false,
      "loc": "block/blk-throttle.c:658",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated"
      ],
      "caller_func": [
        "block/blk-throttle.c:tg_may_dispatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586602144,
      "name": "throtl_start_new_slice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 782
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void throtl_start_new_slice(struct throtl_grp * tg, bool rw, bool clear_carryover)
```

```json
{
  "name": "throtl_start_new_slice",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586870940,
      "name": "throtl_start_new_slice",
      "external": false,
      "loc": "block/blk-throttle.c:657",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated"
      ],
      "caller_func": [
        "block/blk-throttle.c:tg_may_dispatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586860400,
      "name": "throtl_start_new_slice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 782
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void throtl_start_new_slice(struct throtl_grp * tg, bool rw, bool clear_carryover)
```

```json
{
  "name": "throtl_start_new_slice",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587148838,
      "name": "throtl_start_new_slice",
      "external": false,
      "loc": "block/blk-throttle.c:657",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated"
      ],
      "caller_func": [
        "block/blk-throttle.c:tg_may_dispatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587137856,
      "name": "throtl_start_new_slice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 782
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
  "name": "throtl_start_new_slice",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495992700,
      "name": "throtl_start_new_slice",
      "external": false,
      "loc": "block/blk-throttle.c:781",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_may_dispatch"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "throtl_start_new_slice",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229332916,
      "name": "throtl_start_new_slice",
      "external": false,
      "loc": "block/blk-throttle.c:781",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_may_dispatch"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "throtl_start_new_slice",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290219076,
      "name": "throtl_start_new_slice",
      "external": false,
      "loc": "block/blk-throttle.c:781",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_may_dispatch"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "throtl_start_new_slice",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275089728,
      "name": "throtl_start_new_slice",
      "external": false,
      "loc": "block/blk-throttle.c:781",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_may_dispatch"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "throtl_start_new_slice",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584110505,
      "name": "throtl_start_new_slice",
      "external": false,
      "loc": "block/blk-throttle.c:781",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_may_dispatch"
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
  "name": "throtl_start_new_slice",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584046185,
      "name": "throtl_start_new_slice",
      "external": false,
      "loc": "block/blk-throttle.c:781",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_may_dispatch"
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
  "name": "throtl_start_new_slice",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584094265,
      "name": "throtl_start_new_slice",
      "external": false,
      "loc": "block/blk-throttle.c:781",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_may_dispatch"
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
  "name": "throtl_start_new_slice",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584197326,
      "name": "throtl_start_new_slice",
      "external": false,
      "loc": "block/blk-throttle.c:781",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_may_dispatch"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void throtl_start_new_slice(struct throtl_grp * tg, bool rw)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void throtl_start_new_slice(struct throtl_grp * tg, bool rw)
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool clear_carryover</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
