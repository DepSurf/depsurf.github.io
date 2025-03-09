# Function: <code>ioc_refresh_params</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
bool ioc_refresh_params(struct ioc * ioc, bool force)
```

```json
{
  "name": "ioc_refresh_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584155088,
      "name": "ioc_refresh_params",
      "external": false,
      "loc": "block/blk-iocost.c:816",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-iocost.c:ioc_rqos_queue_depth_changed",
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584155088,
      "name": "ioc_refresh_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 909
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
  "name": "ioc_refresh_params",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584553920,
      "name": "ioc_refresh_params",
      "external": false,
      "loc": "block/blk-iocost.c:814",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-iocost.c:ioc_rqos_queue_depth_changed",
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584553920,
      "name": "ioc_refresh_params.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 908
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ioc_refresh_params",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584665104,
      "name": "ioc_refresh_params",
      "external": false,
      "loc": "block/blk-iocost.c:901",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-iocost.c:ioc_rqos_queue_depth_changed",
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584665104,
      "name": "ioc_refresh_params.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 971
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ioc_refresh_params",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584693088,
      "name": "ioc_refresh_params",
      "external": false,
      "loc": "block/blk-iocost.c:901",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-iocost.c:ioc_rqos_queue_depth_changed",
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584693088,
      "name": "ioc_refresh_params.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 969
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ioc_refresh_params",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585116128,
      "name": "ioc_refresh_params",
      "external": false,
      "loc": "block/blk-iocost.c:901",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-iocost.c:ioc_rqos_queue_depth_changed",
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585116128,
      "name": "ioc_refresh_params.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1038
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ioc_refresh_params",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585849344,
      "name": "ioc_refresh_params",
      "external": false,
      "loc": "block/blk-iocost.c:900",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-iocost.c:ioc_rqos_queue_depth_changed",
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585849344,
      "name": "ioc_refresh_params.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1076
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
  "name": "ioc_refresh_params",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586630864,
      "name": "ioc_refresh_params",
      "external": false,
      "loc": "block/blk-iocost.c:902",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-iocost.c:ioc_rqos_queue_depth_changed",
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586630864,
      "name": "ioc_refresh_params.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1087
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ioc_refresh_params",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586894480,
      "name": "ioc_refresh_params",
      "external": false,
      "loc": "block/blk-iocost.c:951",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-iocost.c:ioc_rqos_queue_depth_changed",
        "block/blk-iocost.c:ioc_timer_fn"
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
  "name": "ioc_refresh_params",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587172502,
      "name": "ioc_refresh_params",
      "external": false,
      "loc": "block/blk-iocost.c:951",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-iocost.c:ioc_rqos_queue_depth_changed",
        "block/blk-iocost.c:ioc_timer_fn"
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
bool ioc_refresh_params(struct ioc * ioc, bool force)
```

```json
{
  "name": "ioc_refresh_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496005152,
      "name": "ioc_refresh_params",
      "external": false,
      "loc": "block/blk-iocost.c:816",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-iocost.c:ioc_rqos_queue_depth_changed",
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496005152,
      "name": "ioc_refresh_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 848
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
bool ioc_refresh_params(struct ioc * ioc, bool force)
```

```json
{
  "name": "ioc_refresh_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229346580,
      "name": "ioc_refresh_params",
      "external": false,
      "loc": "block/blk-iocost.c:816",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-iocost.c:ioc_rqos_queue_depth_changed",
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229346580,
      "name": "ioc_refresh_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1100
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
bool ioc_refresh_params(struct ioc * ioc, bool force)
```

```json
{
  "name": "ioc_refresh_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290238064,
      "name": "ioc_refresh_params",
      "external": false,
      "loc": "block/blk-iocost.c:816",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-iocost.c:ioc_rqos_queue_depth_changed",
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290238064,
      "name": "ioc_refresh_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1108
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
bool ioc_refresh_params(struct ioc * ioc, bool force)
```

```json
{
  "name": "ioc_refresh_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275101598,
      "name": "ioc_refresh_params",
      "external": false,
      "loc": "block/blk-iocost.c:816",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-iocost.c:ioc_rqos_queue_depth_changed",
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275101598,
      "name": "ioc_refresh_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 688
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
bool ioc_refresh_params(struct ioc * ioc, bool force)
```

```json
{
  "name": "ioc_refresh_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584123824,
      "name": "ioc_refresh_params",
      "external": false,
      "loc": "block/blk-iocost.c:816",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-iocost.c:ioc_rqos_queue_depth_changed",
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584123824,
      "name": "ioc_refresh_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 909
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
bool ioc_refresh_params(struct ioc * ioc, bool force)
```

```json
{
  "name": "ioc_refresh_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584059488,
      "name": "ioc_refresh_params",
      "external": false,
      "loc": "block/blk-iocost.c:816",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-iocost.c:ioc_rqos_queue_depth_changed",
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584059488,
      "name": "ioc_refresh_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 909
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
bool ioc_refresh_params(struct ioc * ioc, bool force)
```

```json
{
  "name": "ioc_refresh_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584107584,
      "name": "ioc_refresh_params",
      "external": false,
      "loc": "block/blk-iocost.c:816",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-iocost.c:ioc_rqos_queue_depth_changed",
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584107584,
      "name": "ioc_refresh_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 909
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
bool ioc_refresh_params(struct ioc * ioc, bool force)
```

```json
{
  "name": "ioc_refresh_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584211552,
      "name": "ioc_refresh_params",
      "external": false,
      "loc": "block/blk-iocost.c:816",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-iocost.c:ioc_rqos_queue_depth_changed",
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584211552,
      "name": "ioc_refresh_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 909
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
bool ioc_refresh_params(struct ioc * ioc, bool force)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
bool ioc_refresh_params(struct ioc * ioc, bool force)
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
