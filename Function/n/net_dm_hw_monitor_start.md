# Function: <code>net_dm_hw_monitor_start</code>

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
  "name": "net_dm_hw_monitor_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588762217,
      "name": "net_dm_hw_monitor_start",
      "external": false,
      "loc": "net/core/drop_monitor.c:971",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_cmd_trace"
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
int net_dm_hw_monitor_start(struct netlink_ext_ack * extack)
```

```json
{
  "name": "net_dm_hw_monitor_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589630096,
      "name": "net_dm_hw_monitor_start",
      "external": false,
      "loc": "net/core/drop_monitor.c:1001",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_cmd_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589630096,
      "name": "net_dm_hw_monitor_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
int net_dm_hw_monitor_start(struct netlink_ext_ack * extack)
```

```json
{
  "name": "net_dm_hw_monitor_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589657328,
      "name": "net_dm_hw_monitor_start",
      "external": false,
      "loc": "net/core/drop_monitor.c:1018",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_cmd_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589657328,
      "name": "net_dm_hw_monitor_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 562
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
int net_dm_hw_monitor_start(struct netlink_ext_ack * extack)
```

```json
{
  "name": "net_dm_hw_monitor_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589546240,
      "name": "net_dm_hw_monitor_start",
      "external": false,
      "loc": "net/core/drop_monitor.c:1018",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_cmd_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589546240,
      "name": "net_dm_hw_monitor_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 611
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
int net_dm_hw_monitor_start(struct netlink_ext_ack * extack)
```

```json
{
  "name": "net_dm_hw_monitor_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "net_dm_hw_monitor_start",
      "external": false,
      "loc": "net/core/drop_monitor.c:1020",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_cmd_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590290928,
      "name": "net_dm_hw_monitor_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 720
    },
    {
      "addr": 18446744071592706452,
      "name": "net_dm_hw_monitor_start.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int net_dm_hw_monitor_start(struct netlink_ext_ack * extack)
```

```json
{
  "name": "net_dm_hw_monitor_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "net_dm_hw_monitor_start",
      "external": false,
      "loc": "net/core/drop_monitor.c:1043",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_cmd_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591874016,
      "name": "net_dm_hw_monitor_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 718
    },
    {
      "addr": 18446744071594593149,
      "name": "net_dm_hw_monitor_start.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int net_dm_hw_monitor_start(struct netlink_ext_ack * extack)
```

```json
{
  "name": "net_dm_hw_monitor_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "net_dm_hw_monitor_start",
      "external": false,
      "loc": "net/core/drop_monitor.c:1031",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_cmd_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593673968,
      "name": "net_dm_hw_monitor_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 726
    },
    {
      "addr": 18446744071596330069,
      "name": "net_dm_hw_monitor_start.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int net_dm_hw_monitor_start(struct netlink_ext_ack * extack)
```

```json
{
  "name": "net_dm_hw_monitor_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "net_dm_hw_monitor_start",
      "external": false,
      "loc": "net/core/drop_monitor.c:1046",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_cmd_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594155072,
      "name": "net_dm_hw_monitor_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 726
    },
    {
      "addr": 18446744071596860265,
      "name": "net_dm_hw_monitor_start.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int net_dm_hw_monitor_start(struct netlink_ext_ack * extack)
```

```json
{
  "name": "net_dm_hw_monitor_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "net_dm_hw_monitor_start",
      "external": false,
      "loc": "net/core/drop_monitor.c:1046",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_cmd_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594951536,
      "name": "net_dm_hw_monitor_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 726
    },
    {
      "addr": 18446744071597785416,
      "name": "net_dm_hw_monitor_start.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
  "name": "net_dm_hw_monitor_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502325288,
      "name": "net_dm_hw_monitor_start",
      "external": false,
      "loc": "net/core/drop_monitor.c:971",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_cmd_trace"
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
  "name": "net_dm_hw_monitor_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235066808,
      "name": "net_dm_hw_monitor_start",
      "external": false,
      "loc": "net/core/drop_monitor.c:971",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_cmd_trace"
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
  "name": "net_dm_hw_monitor_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295843920,
      "name": "net_dm_hw_monitor_start",
      "external": false,
      "loc": "net/core/drop_monitor.c:971",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_cmd_trace"
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
  "name": "net_dm_hw_monitor_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278550682,
      "name": "net_dm_hw_monitor_start",
      "external": false,
      "loc": "net/core/drop_monitor.c:971",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_cmd_trace"
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
  "name": "net_dm_hw_monitor_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588368953,
      "name": "net_dm_hw_monitor_start",
      "external": false,
      "loc": "net/core/drop_monitor.c:971",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_cmd_trace"
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
  "name": "net_dm_hw_monitor_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588081641,
      "name": "net_dm_hw_monitor_start",
      "external": false,
      "loc": "net/core/drop_monitor.c:971",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_cmd_trace"
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
  "name": "net_dm_hw_monitor_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588700777,
      "name": "net_dm_hw_monitor_start",
      "external": false,
      "loc": "net/core/drop_monitor.c:971",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_cmd_trace"
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
  "name": "net_dm_hw_monitor_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588840697,
      "name": "net_dm_hw_monitor_start",
      "external": false,
      "loc": "net/core/drop_monitor.c:971",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_cmd_trace"
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
int net_dm_hw_monitor_start(struct netlink_ext_ack * extack)
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
