# Function: <code>disk_events_poll_jiffies</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "disk_events_poll_jiffies",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582820432,
      "name": "disk_events_poll_jiffies",
      "external": false,
      "loc": "block/genhd.c:1426",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:__disk_unblock_events",
        "block/genhd.c:disk_check_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582820432,
      "name": "disk_events_poll_jiffies.isra.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "disk_events_poll_jiffies",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583099664,
      "name": "disk_events_poll_jiffies",
      "external": false,
      "loc": "block/genhd.c:1455",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:__disk_unblock_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583099664,
      "name": "disk_events_poll_jiffies.isra.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "disk_events_poll_jiffies",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583211184,
      "name": "disk_events_poll_jiffies",
      "external": false,
      "loc": "block/genhd.c:1455",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:__disk_unblock_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583211184,
      "name": "disk_events_poll_jiffies.isra.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
  "name": "disk_events_poll_jiffies",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583269312,
      "name": "disk_events_poll_jiffies",
      "external": false,
      "loc": "block/genhd.c:1478",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:__disk_unblock_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583269312,
      "name": "disk_events_poll_jiffies.isra.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
  "name": "disk_events_poll_jiffies",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583448320,
      "name": "disk_events_poll_jiffies",
      "external": false,
      "loc": "block/genhd.c:1562",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:__disk_unblock_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583448320,
      "name": "disk_events_poll_jiffies.isra.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
long unsigned int disk_events_poll_jiffies(struct gendisk * disk)
```

```json
{
  "name": "disk_events_poll_jiffies",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583657488,
      "name": "disk_events_poll_jiffies",
      "external": false,
      "loc": "block/genhd.c:1597",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:__disk_unblock_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583657488,
      "name": "disk_events_poll_jiffies",
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
long unsigned int disk_events_poll_jiffies(struct gendisk * disk)
```

```json
{
  "name": "disk_events_poll_jiffies",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583763760,
      "name": "disk_events_poll_jiffies",
      "external": false,
      "loc": "block/genhd.c:1622",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:__disk_unblock_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583763760,
      "name": "disk_events_poll_jiffies",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "disk_events_poll_jiffies",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583954576,
      "name": "disk_events_poll_jiffies",
      "external": false,
      "loc": "block/genhd.c:1643",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:__disk_unblock_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583954576,
      "name": "disk_events_poll_jiffies.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "disk_events_poll_jiffies",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584058048,
      "name": "disk_events_poll_jiffies",
      "external": false,
      "loc": "block/genhd.c:1652",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:__disk_unblock_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584058048,
      "name": "disk_events_poll_jiffies.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
  "name": "disk_events_poll_jiffies",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584458065,
      "name": "disk_events_poll_jiffies",
      "external": false,
      "loc": "block/genhd.c:1851",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:__disk_unblock_events"
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
  "name": "disk_events_poll_jiffies",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584574078,
      "name": "disk_events_poll_jiffies",
      "external": false,
      "loc": "block/genhd.c:1701",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:__disk_unblock_events"
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
  "name": "disk_events_poll_jiffies",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584606772,
      "name": "disk_events_poll_jiffies",
      "external": false,
      "loc": "block/genhd.c:1406",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:__disk_unblock_events"
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
  "name": "disk_events_poll_jiffies",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585066002,
      "name": "disk_events_poll_jiffies",
      "external": false,
      "loc": "block/disk-events.c:41",
      "file": "block/disk-events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/disk-events.c:disk_check_events",
        "block/disk-events.c:__disk_unblock_events"
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
  "name": "disk_events_poll_jiffies",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585789265,
      "name": "disk_events_poll_jiffies",
      "external": false,
      "loc": "block/disk-events.c:41",
      "file": "block/disk-events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/disk-events.c:disk_check_events",
        "block/disk-events.c:__disk_unblock_events"
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
  "name": "disk_events_poll_jiffies",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586569889,
      "name": "disk_events_poll_jiffies",
      "external": false,
      "loc": "block/disk-events.c:41",
      "file": "block/disk-events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/disk-events.c:disk_check_events",
        "block/disk-events.c:__disk_unblock_events"
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
  "name": "disk_events_poll_jiffies",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586827697,
      "name": "disk_events_poll_jiffies",
      "external": false,
      "loc": "block/disk-events.c:41",
      "file": "block/disk-events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/disk-events.c:disk_check_events",
        "block/disk-events.c:__disk_unblock_events"
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
  "name": "disk_events_poll_jiffies",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587104769,
      "name": "disk_events_poll_jiffies",
      "external": false,
      "loc": "block/disk-events.c:41",
      "file": "block/disk-events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/disk-events.c:disk_check_events",
        "block/disk-events.c:__disk_unblock_events"
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
  "name": "disk_events_poll_jiffies",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495898504,
      "name": "disk_events_poll_jiffies",
      "external": false,
      "loc": "block/genhd.c:1652",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:__disk_unblock_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495898504,
      "name": "disk_events_poll_jiffies.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
long unsigned int disk_events_poll_jiffies(struct gendisk * disk)
```

```json
{
  "name": "disk_events_poll_jiffies",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229239628,
      "name": "disk_events_poll_jiffies",
      "external": false,
      "loc": "block/genhd.c:1652",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:__disk_unblock_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229239628,
      "name": "disk_events_poll_jiffies",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long unsigned int disk_events_poll_jiffies(struct gendisk * disk)
```

```json
{
  "name": "disk_events_poll_jiffies",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290102320,
      "name": "disk_events_poll_jiffies",
      "external": false,
      "loc": "block/genhd.c:1652",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:__disk_unblock_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290102320,
      "name": "disk_events_poll_jiffies",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
long unsigned int disk_events_poll_jiffies(struct gendisk * disk)
```

```json
{
  "name": "disk_events_poll_jiffies",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275013572,
      "name": "disk_events_poll_jiffies",
      "external": false,
      "loc": "block/genhd.c:1652",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:__disk_unblock_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275013572,
      "name": "disk_events_poll_jiffies",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "disk_events_poll_jiffies",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584026784,
      "name": "disk_events_poll_jiffies",
      "external": false,
      "loc": "block/genhd.c:1652",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:__disk_unblock_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584026784,
      "name": "disk_events_poll_jiffies.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "disk_events_poll_jiffies",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583962592,
      "name": "disk_events_poll_jiffies",
      "external": false,
      "loc": "block/genhd.c:1652",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:__disk_unblock_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583962592,
      "name": "disk_events_poll_jiffies.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "disk_events_poll_jiffies",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584010544,
      "name": "disk_events_poll_jiffies",
      "external": false,
      "loc": "block/genhd.c:1652",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:__disk_unblock_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584010544,
      "name": "disk_events_poll_jiffies.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
  "name": "disk_events_poll_jiffies",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584113056,
      "name": "disk_events_poll_jiffies",
      "external": false,
      "loc": "block/genhd.c:1652",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:__disk_unblock_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584113056,
      "name": "disk_events_poll_jiffies.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
long unsigned int disk_events_poll_jiffies(struct gendisk * disk)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
long unsigned int disk_events_poll_jiffies(struct gendisk * disk)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
long unsigned int disk_events_poll_jiffies(struct gendisk * disk)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
long unsigned int disk_events_poll_jiffies(struct gendisk * disk)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
long unsigned int disk_events_poll_jiffies(struct gendisk * disk)
```
</details>
</li>
</ul>
