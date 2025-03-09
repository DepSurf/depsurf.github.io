# Function: <code>net_dm_hw_entries_put</code>

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
  "name": "net_dm_hw_entries_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588763802,
      "name": "net_dm_hw_entries_put",
      "external": false,
      "loc": "net/core/drop_monitor.c:342",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int net_dm_hw_entries_put(struct sk_buff * msg, const struct net_dm_hw_entries * hw_entries)
```

```json
{
  "name": "net_dm_hw_entries_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589634704,
      "name": "net_dm_hw_entries_put",
      "external": false,
      "loc": "net/core/drop_monitor.c:346",
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
      "addr": 18446744071589634704,
      "name": "net_dm_hw_entries_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
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
int net_dm_hw_entries_put(struct sk_buff * msg, const struct net_dm_hw_entries * hw_entries)
```

```json
{
  "name": "net_dm_hw_entries_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "net_dm_hw_entries_put",
      "external": false,
      "loc": "net/core/drop_monitor.c:348",
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
      "addr": 18446744071589658320,
      "name": "net_dm_hw_entries_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    },
    {
      "addr": 18446744071591632491,
      "name": "net_dm_hw_entries_put.cold",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "net_dm_hw_entries_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589548102,
      "name": "net_dm_hw_entries_put",
      "external": false,
      "loc": "net/core/drop_monitor.c:348",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_summary_report_fill"
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
  "name": "net_dm_hw_entries_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590292502,
      "name": "net_dm_hw_entries_put",
      "external": false,
      "loc": "net/core/drop_monitor.c:352",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_summary_report_fill"
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
  "name": "net_dm_hw_entries_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591875638,
      "name": "net_dm_hw_entries_put",
      "external": false,
      "loc": "net/core/drop_monitor.c:359",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_summary_report_fill"
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
  "name": "net_dm_hw_entries_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593676870,
      "name": "net_dm_hw_entries_put",
      "external": false,
      "loc": "net/core/drop_monitor.c:346",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_summary_report_fill"
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
  "name": "net_dm_hw_entries_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594157446,
      "name": "net_dm_hw_entries_put",
      "external": false,
      "loc": "net/core/drop_monitor.c:348",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_summary_report_fill"
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
  "name": "net_dm_hw_entries_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594953910,
      "name": "net_dm_hw_entries_put",
      "external": false,
      "loc": "net/core/drop_monitor.c:348",
      "file": "net/core/drop_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_summary_report_fill"
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
  "name": "net_dm_hw_entries_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502328456,
      "name": "net_dm_hw_entries_put",
      "external": false,
      "loc": "net/core/drop_monitor.c:342",
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
  "name": "net_dm_hw_entries_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235068648,
      "name": "net_dm_hw_entries_put",
      "external": false,
      "loc": "net/core/drop_monitor.c:342",
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
  "name": "net_dm_hw_entries_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295846536,
      "name": "net_dm_hw_entries_put",
      "external": false,
      "loc": "net/core/drop_monitor.c:342",
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
  "name": "net_dm_hw_entries_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278552204,
      "name": "net_dm_hw_entries_put",
      "external": false,
      "loc": "net/core/drop_monitor.c:342",
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
  "name": "net_dm_hw_entries_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588370538,
      "name": "net_dm_hw_entries_put",
      "external": false,
      "loc": "net/core/drop_monitor.c:342",
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
  "name": "net_dm_hw_entries_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588083226,
      "name": "net_dm_hw_entries_put",
      "external": false,
      "loc": "net/core/drop_monitor.c:342",
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
  "name": "net_dm_hw_entries_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588702362,
      "name": "net_dm_hw_entries_put",
      "external": false,
      "loc": "net/core/drop_monitor.c:342",
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
  "name": "net_dm_hw_entries_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588842282,
      "name": "net_dm_hw_entries_put",
      "external": false,
      "loc": "net/core/drop_monitor.c:342",
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int net_dm_hw_entries_put(struct sk_buff * msg, const struct net_dm_hw_entries * hw_entries)
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
int net_dm_hw_entries_put(struct sk_buff * msg, const struct net_dm_hw_entries * hw_entries)
```
</details>
</li>
</ul>
