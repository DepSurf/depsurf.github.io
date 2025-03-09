# Function: <code>net_dm_hw_packet_report_size</code>

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
  "name": "net_dm_hw_packet_report_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588764827,
      "name": "net_dm_hw_packet_report_size",
      "external": false,
      "loc": "net/core/drop_monitor.c:704",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_packet_work"
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
size_t net_dm_hw_packet_report_size(size_t payload_len, const struct net_dm_hw_metadata * hw_metadata)
```

```json
{
  "name": "net_dm_hw_packet_report_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589630416,
      "name": "net_dm_hw_packet_report_size",
      "external": false,
      "loc": "net/core/drop_monitor.c:715",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_hw_packet_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589630416,
      "name": "net_dm_hw_packet_report_size",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
size_t net_dm_hw_packet_report_size(size_t payload_len, const struct devlink_trap_metadata * hw_metadata)
```

```json
{
  "name": "net_dm_hw_packet_report_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589652928,
      "name": "net_dm_hw_packet_report_size",
      "external": false,
      "loc": "net/core/drop_monitor.c:721",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_hw_packet_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589652928,
      "name": "net_dm_hw_packet_report_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
size_t net_dm_hw_packet_report_size(size_t payload_len, const struct devlink_trap_metadata * hw_metadata)
```

```json
{
  "name": "net_dm_hw_packet_report_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589542368,
      "name": "net_dm_hw_packet_report_size",
      "external": false,
      "loc": "net/core/drop_monitor.c:721",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_hw_packet_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589542368,
      "name": "net_dm_hw_packet_report_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
size_t net_dm_hw_packet_report_size(size_t payload_len, const struct devlink_trap_metadata * hw_metadata)
```

```json
{
  "name": "net_dm_hw_packet_report_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590286288,
      "name": "net_dm_hw_packet_report_size",
      "external": false,
      "loc": "net/core/drop_monitor.c:725",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_hw_packet_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590286288,
      "name": "net_dm_hw_packet_report_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
size_t net_dm_hw_packet_report_size(size_t payload_len, const struct devlink_trap_metadata * hw_metadata)
```

```json
{
  "name": "net_dm_hw_packet_report_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591869328,
      "name": "net_dm_hw_packet_report_size",
      "external": false,
      "loc": "net/core/drop_monitor.c:748",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_hw_packet_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591869328,
      "name": "net_dm_hw_packet_report_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
size_t net_dm_hw_packet_report_size(size_t payload_len, const struct devlink_trap_metadata * hw_metadata)
```

```json
{
  "name": "net_dm_hw_packet_report_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593670208,
      "name": "net_dm_hw_packet_report_size",
      "external": false,
      "loc": "net/core/drop_monitor.c:735",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_hw_packet_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593670208,
      "name": "net_dm_hw_packet_report_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
size_t net_dm_hw_packet_report_size(size_t payload_len, const struct devlink_trap_metadata * hw_metadata)
```

```json
{
  "name": "net_dm_hw_packet_report_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594150784,
      "name": "net_dm_hw_packet_report_size",
      "external": false,
      "loc": "net/core/drop_monitor.c:750",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_hw_packet_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594150784,
      "name": "net_dm_hw_packet_report_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
size_t net_dm_hw_packet_report_size(size_t payload_len, const struct devlink_trap_metadata * hw_metadata)
```

```json
{
  "name": "net_dm_hw_packet_report_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594947088,
      "name": "net_dm_hw_packet_report_size",
      "external": false,
      "loc": "net/core/drop_monitor.c:750",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_hw_packet_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594947088,
      "name": "net_dm_hw_packet_report_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
  "name": "net_dm_hw_packet_report_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502329672,
      "name": "net_dm_hw_packet_report_size",
      "external": false,
      "loc": "net/core/drop_monitor.c:704",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_packet_work"
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
  "name": "net_dm_hw_packet_report_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235069828,
      "name": "net_dm_hw_packet_report_size",
      "external": false,
      "loc": "net/core/drop_monitor.c:704",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_packet_work"
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
  "name": "net_dm_hw_packet_report_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295848080,
      "name": "net_dm_hw_packet_report_size",
      "external": false,
      "loc": "net/core/drop_monitor.c:704",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_packet_work"
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
  "name": "net_dm_hw_packet_report_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278552962,
      "name": "net_dm_hw_packet_report_size",
      "external": false,
      "loc": "net/core/drop_monitor.c:704",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_packet_work"
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
  "name": "net_dm_hw_packet_report_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588371563,
      "name": "net_dm_hw_packet_report_size",
      "external": false,
      "loc": "net/core/drop_monitor.c:704",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_packet_work"
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
  "name": "net_dm_hw_packet_report_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588084251,
      "name": "net_dm_hw_packet_report_size",
      "external": false,
      "loc": "net/core/drop_monitor.c:704",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_packet_work"
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
  "name": "net_dm_hw_packet_report_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588703387,
      "name": "net_dm_hw_packet_report_size",
      "external": false,
      "loc": "net/core/drop_monitor.c:704",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_packet_work"
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
  "name": "net_dm_hw_packet_report_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588843307,
      "name": "net_dm_hw_packet_report_size",
      "external": false,
      "loc": "net/core/drop_monitor.c:704",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_packet_work"
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
size_t net_dm_hw_packet_report_size(size_t payload_len, const struct net_dm_hw_metadata * hw_metadata)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct net_dm_hw_metadata * hw_metadata</code> ➡️ <code>const struct devlink_trap_metadata * hw_metadata</code>
</li>
</ul>
</details>
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
