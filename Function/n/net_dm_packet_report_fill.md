# Function: <code>net_dm_packet_report_fill</code>

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
  "name": "net_dm_packet_report_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588765898,
      "name": "net_dm_packet_report_fill",
      "external": false,
      "loc": "net/core/drop_monitor.c:592",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int net_dm_packet_report_fill(struct sk_buff * msg, struct sk_buff * skb, size_t payload_len)
```

```json
{
  "name": "net_dm_packet_report_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "net_dm_packet_report_fill",
      "external": false,
      "loc": "net/core/drop_monitor.c:596",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_packet_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589637376,
      "name": "net_dm_packet_report_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 573
    },
    {
      "addr": 18446744071589639045,
      "name": "net_dm_packet_report_fill.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int net_dm_packet_report_fill(struct sk_buff * msg, struct sk_buff * skb, size_t payload_len)
```

```json
{
  "name": "net_dm_packet_report_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "net_dm_packet_report_fill",
      "external": false,
      "loc": "net/core/drop_monitor.c:602",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_packet_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589660992,
      "name": "net_dm_packet_report_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 573
    },
    {
      "addr": 18446744071591632515,
      "name": "net_dm_packet_report_fill.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int net_dm_packet_report_fill(struct sk_buff * msg, struct sk_buff * skb, size_t payload_len)
```

```json
{
  "name": "net_dm_packet_report_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "net_dm_packet_report_fill",
      "external": false,
      "loc": "net/core/drop_monitor.c:602",
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
      "addr": 18446744071589550160,
      "name": "net_dm_packet_report_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 577
    },
    {
      "addr": 18446744071591575884,
      "name": "net_dm_packet_report_fill.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int net_dm_packet_report_fill(struct sk_buff * msg, struct sk_buff * skb, size_t payload_len)
```

```json
{
  "name": "net_dm_packet_report_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "net_dm_packet_report_fill",
      "external": false,
      "loc": "net/core/drop_monitor.c:606",
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
      "addr": 18446744071590294560,
      "name": "net_dm_packet_report_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 577
    },
    {
      "addr": 18446744071592706496,
      "name": "net_dm_packet_report_fill.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int net_dm_packet_report_fill(struct sk_buff * msg, struct sk_buff * skb, size_t payload_len)
```

```json
{
  "name": "net_dm_packet_report_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "net_dm_packet_report_fill",
      "external": false,
      "loc": "net/core/drop_monitor.c:622",
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
      "addr": 18446744071591877776,
      "name": "net_dm_packet_report_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 717
    },
    {
      "addr": 18446744071594593193,
      "name": "net_dm_packet_report_fill.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int net_dm_packet_report_fill(struct sk_buff * msg, struct sk_buff * skb, size_t payload_len)
```

```json
{
  "name": "net_dm_packet_report_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593679120,
      "name": "net_dm_packet_report_fill",
      "external": false,
      "loc": "net/core/drop_monitor.c:609",
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
      "addr": 18446744071593679120,
      "name": "net_dm_packet_report_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 711
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
int net_dm_packet_report_fill(struct sk_buff * msg, struct sk_buff * skb, size_t payload_len)
```

```json
{
  "name": "net_dm_packet_report_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594159696,
      "name": "net_dm_packet_report_fill",
      "external": false,
      "loc": "net/core/drop_monitor.c:609",
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
      "addr": 18446744071594159696,
      "name": "net_dm_packet_report_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 846
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
int net_dm_packet_report_fill(struct sk_buff * msg, struct sk_buff * skb, size_t payload_len)
```

```json
{
  "name": "net_dm_packet_report_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594956208,
      "name": "net_dm_packet_report_fill",
      "external": false,
      "loc": "net/core/drop_monitor.c:609",
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
      "addr": 18446744071594956208,
      "name": "net_dm_packet_report_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 846
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
  "name": "net_dm_packet_report_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502330796,
      "name": "net_dm_packet_report_fill",
      "external": false,
      "loc": "net/core/drop_monitor.c:592",
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
  "name": "net_dm_packet_report_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235070988,
      "name": "net_dm_packet_report_fill",
      "external": false,
      "loc": "net/core/drop_monitor.c:592",
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
  "name": "net_dm_packet_report_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295849556,
      "name": "net_dm_packet_report_fill",
      "external": false,
      "loc": "net/core/drop_monitor.c:592",
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
  "name": "net_dm_packet_report_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278553994,
      "name": "net_dm_packet_report_fill",
      "external": false,
      "loc": "net/core/drop_monitor.c:592",
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
  "name": "net_dm_packet_report_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588372634,
      "name": "net_dm_packet_report_fill",
      "external": false,
      "loc": "net/core/drop_monitor.c:592",
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
  "name": "net_dm_packet_report_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588085322,
      "name": "net_dm_packet_report_fill",
      "external": false,
      "loc": "net/core/drop_monitor.c:592",
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
  "name": "net_dm_packet_report_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588704458,
      "name": "net_dm_packet_report_fill",
      "external": false,
      "loc": "net/core/drop_monitor.c:592",
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
  "name": "net_dm_packet_report_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588844378,
      "name": "net_dm_packet_report_fill",
      "external": false,
      "loc": "net/core/drop_monitor.c:592",
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
int net_dm_packet_report_fill(struct sk_buff * msg, struct sk_buff * skb, size_t payload_len)
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
