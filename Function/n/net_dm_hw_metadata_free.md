# Function: <code>net_dm_hw_metadata_free</code>

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
void net_dm_hw_metadata_free(const struct net_dm_hw_metadata * hw_metadata)
```

```json
{
  "name": "net_dm_hw_metadata_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588759200,
      "name": "net_dm_hw_metadata_free",
      "external": false,
      "loc": "net/core/drop_monitor.c:833",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_hw_packet_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588759200,
      "name": "net_dm_hw_metadata_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
  "name": "net_dm_hw_metadata_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589633884,
      "name": "net_dm_hw_metadata_free",
      "external": false,
      "loc": "net/core/drop_monitor.c:862",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_hw_packet_report"
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
  "name": "net_dm_hw_metadata_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589657208,
      "name": "net_dm_hw_metadata_free",
      "external": false,
      "loc": "net/core/drop_monitor.c:868",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop",
        "net/core/drop_monitor.c:net_dm_hw_monitor_start",
        "net/core/drop_monitor.c:net_dm_hw_trap_packet_probe",
        "net/core/drop_monitor.c:net_dm_hw_packet_report"
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
  "name": "net_dm_hw_metadata_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589547168,
      "name": "net_dm_hw_metadata_free",
      "external": false,
      "loc": "net/core/drop_monitor.c:868",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_hw_monitor_start",
        "net/core/drop_monitor.c:net_dm_hw_trap_packet_probe",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "net_dm_hw_metadata_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590290727,
      "name": "net_dm_hw_metadata_free",
      "external": false,
      "loc": "net/core/drop_monitor.c:871",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop",
        "net/core/drop_monitor.c:net_dm_hw_monitor_start",
        "net/core/drop_monitor.c:net_dm_hw_trap_packet_probe",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "net_dm_hw_metadata_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591873794,
      "name": "net_dm_hw_metadata_free",
      "external": false,
      "loc": "net/core/drop_monitor.c:894",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop",
        "net/core/drop_monitor.c:net_dm_hw_monitor_start",
        "net/core/drop_monitor.c:net_dm_hw_trap_packet_probe",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "net_dm_hw_metadata_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593675001,
      "name": "net_dm_hw_metadata_free",
      "external": false,
      "loc": "net/core/drop_monitor.c:882",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop",
        "net/core/drop_monitor.c:net_dm_hw_monitor_start",
        "net/core/drop_monitor.c:net_dm_hw_trap_packet_probe",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "net_dm_hw_metadata_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594154825,
      "name": "net_dm_hw_metadata_free",
      "external": false,
      "loc": "net/core/drop_monitor.c:897",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop",
        "net/core/drop_monitor.c:net_dm_hw_monitor_start",
        "net/core/drop_monitor.c:net_dm_hw_trap_packet_probe",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "net_dm_hw_metadata_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594951289,
      "name": "net_dm_hw_metadata_free",
      "external": false,
      "loc": "net/core/drop_monitor.c:897",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop",
        "net/core/drop_monitor.c:net_dm_hw_monitor_start",
        "net/core/drop_monitor.c:net_dm_hw_trap_packet_probe",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void net_dm_hw_metadata_free(const struct net_dm_hw_metadata * hw_metadata)
```

```json
{
  "name": "net_dm_hw_metadata_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502323848,
      "name": "net_dm_hw_metadata_free",
      "external": false,
      "loc": "net/core/drop_monitor.c:833",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_hw_packet_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502323848,
      "name": "net_dm_hw_metadata_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void net_dm_hw_metadata_free(const struct net_dm_hw_metadata * hw_metadata)
```

```json
{
  "name": "net_dm_hw_metadata_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235063356,
      "name": "net_dm_hw_metadata_free",
      "external": false,
      "loc": "net/core/drop_monitor.c:833",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_hw_packet_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235063356,
      "name": "net_dm_hw_metadata_free",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void net_dm_hw_metadata_free(const struct net_dm_hw_metadata * hw_metadata)
```

```json
{
  "name": "net_dm_hw_metadata_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295838736,
      "name": "net_dm_hw_metadata_free",
      "external": false,
      "loc": "net/core/drop_monitor.c:833",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_hw_packet_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295838736,
      "name": "net_dm_hw_metadata_free",
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
void net_dm_hw_metadata_free(const struct net_dm_hw_metadata * hw_metadata)
```

```json
{
  "name": "net_dm_hw_metadata_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278547214,
      "name": "net_dm_hw_metadata_free",
      "external": false,
      "loc": "net/core/drop_monitor.c:833",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_hw_packet_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278547214,
      "name": "net_dm_hw_metadata_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void net_dm_hw_metadata_free(const struct net_dm_hw_metadata * hw_metadata)
```

```json
{
  "name": "net_dm_hw_metadata_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588365936,
      "name": "net_dm_hw_metadata_free",
      "external": false,
      "loc": "net/core/drop_monitor.c:833",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_hw_packet_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588365936,
      "name": "net_dm_hw_metadata_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
void net_dm_hw_metadata_free(const struct net_dm_hw_metadata * hw_metadata)
```

```json
{
  "name": "net_dm_hw_metadata_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588078640,
      "name": "net_dm_hw_metadata_free",
      "external": false,
      "loc": "net/core/drop_monitor.c:833",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_hw_packet_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588078640,
      "name": "net_dm_hw_metadata_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
void net_dm_hw_metadata_free(const struct net_dm_hw_metadata * hw_metadata)
```

```json
{
  "name": "net_dm_hw_metadata_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588697760,
      "name": "net_dm_hw_metadata_free",
      "external": false,
      "loc": "net/core/drop_monitor.c:833",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_hw_packet_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588697760,
      "name": "net_dm_hw_metadata_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
void net_dm_hw_metadata_free(const struct net_dm_hw_metadata * hw_metadata)
```

```json
{
  "name": "net_dm_hw_metadata_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588837600,
      "name": "net_dm_hw_metadata_free",
      "external": false,
      "loc": "net/core/drop_monitor.c:833",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_hw_packet_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588837600,
      "name": "net_dm_hw_metadata_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
void net_dm_hw_metadata_free(const struct net_dm_hw_metadata * hw_metadata)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void net_dm_hw_metadata_free(const struct net_dm_hw_metadata * hw_metadata)
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
