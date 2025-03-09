# Function: <code>net_dm_hw_summary_report_fill</code>

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
  "name": "net_dm_hw_summary_report_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588763724,
      "name": "net_dm_hw_summary_report_fill",
      "external": false,
      "loc": "net/core/drop_monitor.c:370",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_summary_work"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "net_dm_hw_summary_report_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589635690,
      "name": "net_dm_hw_summary_report_fill",
      "external": false,
      "loc": "net/core/drop_monitor.c:374",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_summary_work"
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
  "name": "net_dm_hw_summary_report_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589659306,
      "name": "net_dm_hw_summary_report_fill",
      "external": false,
      "loc": "net/core/drop_monitor.c:376",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_summary_work"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int net_dm_hw_summary_report_fill(struct sk_buff * msg, const struct net_dm_hw_entries * hw_entries)
```

```json
{
  "name": "net_dm_hw_summary_report_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "net_dm_hw_summary_report_fill",
      "external": false,
      "loc": "net/core/drop_monitor.c:376",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_hw_summary_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589547984,
      "name": "net_dm_hw_summary_report_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 600
    },
    {
      "addr": 18446744071591575860,
      "name": "net_dm_hw_summary_report_fill.cold",
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
int net_dm_hw_summary_report_fill(struct sk_buff * msg, const struct net_dm_hw_entries * hw_entries)
```

```json
{
  "name": "net_dm_hw_summary_report_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "net_dm_hw_summary_report_fill",
      "external": false,
      "loc": "net/core/drop_monitor.c:380",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_hw_summary_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590292384,
      "name": "net_dm_hw_summary_report_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 600
    },
    {
      "addr": 18446744071592706472,
      "name": "net_dm_hw_summary_report_fill.cold",
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
int net_dm_hw_summary_report_fill(struct sk_buff * msg, const struct net_dm_hw_entries * hw_entries)
```

```json
{
  "name": "net_dm_hw_summary_report_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "net_dm_hw_summary_report_fill",
      "external": false,
      "loc": "net/core/drop_monitor.c:387",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_hw_summary_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591875520,
      "name": "net_dm_hw_summary_report_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 617
    },
    {
      "addr": 18446744071594593169,
      "name": "net_dm_hw_summary_report_fill.cold",
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
int net_dm_hw_summary_report_fill(struct sk_buff * msg, const struct net_dm_hw_entries * hw_entries)
```

```json
{
  "name": "net_dm_hw_summary_report_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593676752,
      "name": "net_dm_hw_summary_report_fill",
      "external": false,
      "loc": "net/core/drop_monitor.c:374",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_hw_summary_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593676752,
      "name": "net_dm_hw_summary_report_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
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
int net_dm_hw_summary_report_fill(struct sk_buff * msg, const struct net_dm_hw_entries * hw_entries)
```

```json
{
  "name": "net_dm_hw_summary_report_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594157328,
      "name": "net_dm_hw_summary_report_fill",
      "external": false,
      "loc": "net/core/drop_monitor.c:376",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_hw_summary_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594157328,
      "name": "net_dm_hw_summary_report_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
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
int net_dm_hw_summary_report_fill(struct sk_buff * msg, const struct net_dm_hw_entries * hw_entries)
```

```json
{
  "name": "net_dm_hw_summary_report_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594953792,
      "name": "net_dm_hw_summary_report_fill",
      "external": false,
      "loc": "net/core/drop_monitor.c:376",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_hw_summary_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594953792,
      "name": "net_dm_hw_summary_report_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
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
  "name": "net_dm_hw_summary_report_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502328376,
      "name": "net_dm_hw_summary_report_fill",
      "external": false,
      "loc": "net/core/drop_monitor.c:370",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_summary_work"
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
  "name": "net_dm_hw_summary_report_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235068572,
      "name": "net_dm_hw_summary_report_fill",
      "external": false,
      "loc": "net/core/drop_monitor.c:370",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_summary_work"
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
  "name": "net_dm_hw_summary_report_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295846448,
      "name": "net_dm_hw_summary_report_fill",
      "external": false,
      "loc": "net/core/drop_monitor.c:370",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_summary_work"
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
  "name": "net_dm_hw_summary_report_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278552148,
      "name": "net_dm_hw_summary_report_fill",
      "external": false,
      "loc": "net/core/drop_monitor.c:370",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_summary_work"
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
  "name": "net_dm_hw_summary_report_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588370460,
      "name": "net_dm_hw_summary_report_fill",
      "external": false,
      "loc": "net/core/drop_monitor.c:370",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_summary_work"
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
  "name": "net_dm_hw_summary_report_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588083148,
      "name": "net_dm_hw_summary_report_fill",
      "external": false,
      "loc": "net/core/drop_monitor.c:370",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_summary_work"
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
  "name": "net_dm_hw_summary_report_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588702284,
      "name": "net_dm_hw_summary_report_fill",
      "external": false,
      "loc": "net/core/drop_monitor.c:370",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_summary_work"
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
  "name": "net_dm_hw_summary_report_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588842204,
      "name": "net_dm_hw_summary_report_fill",
      "external": false,
      "loc": "net/core/drop_monitor.c:370",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_summary_work"
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int net_dm_hw_summary_report_fill(struct sk_buff * msg, const struct net_dm_hw_entries * hw_entries)
```
</details>
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
