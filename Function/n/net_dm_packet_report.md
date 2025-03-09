# Function: <code>net_dm_packet_report</code>

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
  "name": "net_dm_packet_report",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588766453,
      "name": "net_dm_packet_report",
      "external": false,
      "loc": "net/core/drop_monitor.c:651",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_packet_work"
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
void net_dm_packet_report(struct sk_buff * skb)
```

```json
{
  "name": "net_dm_packet_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589637952,
      "name": "net_dm_packet_report",
      "external": false,
      "loc": "net/core/drop_monitor.c:655",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_packet_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589637952,
      "name": "net_dm_packet_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
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
void net_dm_packet_report(struct sk_buff * skb)
```

```json
{
  "name": "net_dm_packet_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589661568,
      "name": "net_dm_packet_report",
      "external": false,
      "loc": "net/core/drop_monitor.c:661",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_packet_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589661568,
      "name": "net_dm_packet_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
  "name": "net_dm_packet_report",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589551153,
      "name": "net_dm_packet_report",
      "external": false,
      "loc": "net/core/drop_monitor.c:661",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_packet_work"
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
  "name": "net_dm_packet_report",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590295553,
      "name": "net_dm_packet_report",
      "external": false,
      "loc": "net/core/drop_monitor.c:665",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_packet_work"
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
  "name": "net_dm_packet_report",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591878940,
      "name": "net_dm_packet_report",
      "external": false,
      "loc": "net/core/drop_monitor.c:686",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_packet_work"
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
  "name": "net_dm_packet_report",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593680285,
      "name": "net_dm_packet_report",
      "external": false,
      "loc": "net/core/drop_monitor.c:673",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_packet_work"
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
  "name": "net_dm_packet_report",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594160960,
      "name": "net_dm_packet_report",
      "external": false,
      "loc": "net/core/drop_monitor.c:690",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_packet_work"
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
  "name": "net_dm_packet_report",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594957482,
      "name": "net_dm_packet_report",
      "external": false,
      "loc": "net/core/drop_monitor.c:690",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_packet_work"
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
  "name": "net_dm_packet_report",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502330672,
      "name": "net_dm_packet_report",
      "external": false,
      "loc": "net/core/drop_monitor.c:651",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_packet_work"
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
  "name": "net_dm_packet_report",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235071532,
      "name": "net_dm_packet_report",
      "external": false,
      "loc": "net/core/drop_monitor.c:651",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_packet_work"
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
  "name": "net_dm_packet_report",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295849404,
      "name": "net_dm_packet_report",
      "external": false,
      "loc": "net/core/drop_monitor.c:651",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_packet_work"
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
  "name": "net_dm_packet_report",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278553826,
      "name": "net_dm_packet_report",
      "external": false,
      "loc": "net/core/drop_monitor.c:651",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_packet_work"
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
  "name": "net_dm_packet_report",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588373189,
      "name": "net_dm_packet_report",
      "external": false,
      "loc": "net/core/drop_monitor.c:651",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_packet_work"
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
  "name": "net_dm_packet_report",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588085877,
      "name": "net_dm_packet_report",
      "external": false,
      "loc": "net/core/drop_monitor.c:651",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_packet_work"
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
  "name": "net_dm_packet_report",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588705013,
      "name": "net_dm_packet_report",
      "external": false,
      "loc": "net/core/drop_monitor.c:651",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_packet_work"
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
  "name": "net_dm_packet_report",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588844933,
      "name": "net_dm_packet_report",
      "external": false,
      "loc": "net/core/drop_monitor.c:651",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_packet_work"
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
void net_dm_packet_report(struct sk_buff * skb)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void net_dm_packet_report(struct sk_buff * skb)
```
</details>
</li>
</ul>
