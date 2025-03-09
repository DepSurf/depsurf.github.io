# Function: <code>iocg_activate</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iocg_activate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584167516,
      "name": "iocg_activate",
      "external": false,
      "loc": "block/blk-iocost.c:1027",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle"
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
bool iocg_activate(struct ioc_gq * iocg, struct ioc_now * now)
```

```json
{
  "name": "iocg_activate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584560592,
      "name": "iocg_activate",
      "external": false,
      "loc": "block/blk-iocost.c:1025",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584560592,
      "name": "iocg_activate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 791
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
bool iocg_activate(struct ioc_gq * iocg, struct ioc_now * now)
```

```json
{
  "name": "iocg_activate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584677760,
      "name": "iocg_activate",
      "external": false,
      "loc": "block/blk-iocost.c:1235",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584677760,
      "name": "iocg_activate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 754
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
bool iocg_activate(struct ioc_gq * iocg, struct ioc_now * now)
```

```json
{
  "name": "iocg_activate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584705840,
      "name": "iocg_activate",
      "external": false,
      "loc": "block/blk-iocost.c:1241",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584705840,
      "name": "iocg_activate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 754
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
bool iocg_activate(struct ioc_gq * iocg, struct ioc_now * now)
```

```json
{
  "name": "iocg_activate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585129328,
      "name": "iocg_activate",
      "external": false,
      "loc": "block/blk-iocost.c:1241",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585129328,
      "name": "iocg_activate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 714
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
bool iocg_activate(struct ioc_gq * iocg, struct ioc_now * now)
```

```json
{
  "name": "iocg_activate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585854800,
      "name": "iocg_activate",
      "external": false,
      "loc": "block/blk-iocost.c:1240",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585854800,
      "name": "iocg_activate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 687
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
bool iocg_activate(struct ioc_gq * iocg, struct ioc_now * now)
```

```json
{
  "name": "iocg_activate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586639312,
      "name": "iocg_activate",
      "external": false,
      "loc": "block/blk-iocost.c:1245",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586639312,
      "name": "iocg_activate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 687
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
bool iocg_activate(struct ioc_gq * iocg, struct ioc_now * now)
```

```json
{
  "name": "iocg_activate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586900304,
      "name": "iocg_activate",
      "external": false,
      "loc": "block/blk-iocost.c:1261",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586900304,
      "name": "iocg_activate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 687
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
bool iocg_activate(struct ioc_gq * iocg, struct ioc_now * now)
```

```json
{
  "name": "iocg_activate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587178336,
      "name": "iocg_activate",
      "external": false,
      "loc": "block/blk-iocost.c:1261",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587178336,
      "name": "iocg_activate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 687
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
  "name": "iocg_activate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496020192,
      "name": "iocg_activate",
      "external": false,
      "loc": "block/blk-iocost.c:1027",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
bool iocg_activate(struct ioc_gq * iocg, struct ioc_now * now)
```

```json
{
  "name": "iocg_activate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229362832,
      "name": "iocg_activate",
      "external": false,
      "loc": "block/blk-iocost.c:1027",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229362832,
      "name": "iocg_activate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1028
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "iocg_activate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290253824,
      "name": "iocg_activate",
      "external": false,
      "loc": "block/blk-iocost.c:1027",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle"
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
  "name": "iocg_activate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275112108,
      "name": "iocg_activate",
      "external": false,
      "loc": "block/blk-iocost.c:1027",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle"
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
  "name": "iocg_activate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584136252,
      "name": "iocg_activate",
      "external": false,
      "loc": "block/blk-iocost.c:1027",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle"
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
  "name": "iocg_activate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584071820,
      "name": "iocg_activate",
      "external": false,
      "loc": "block/blk-iocost.c:1027",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle"
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
  "name": "iocg_activate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584120012,
      "name": "iocg_activate",
      "external": false,
      "loc": "block/blk-iocost.c:1027",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle"
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
  "name": "iocg_activate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584214939,
      "name": "iocg_activate",
      "external": false,
      "loc": "block/blk-iocost.c:1027",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool iocg_activate(struct ioc_gq * iocg, struct ioc_now * now)
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
bool iocg_activate(struct ioc_gq * iocg, struct ioc_now * now)
```
</details>
</li>
</ul>
