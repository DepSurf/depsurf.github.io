# Function: <code>mptcp_pm_schedule_work</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool mptcp_pm_schedule_work(struct mptcp_sock * msk, enum mptcp_pm_status new_status)
```

```json
{
  "name": "mptcp_pm_schedule_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591109184,
      "name": "mptcp_pm_schedule_work",
      "external": false,
      "loc": "net/mptcp/pm.c:72",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm.c:mptcp_pm_add_addr_received",
        "net/mptcp/pm.c:mptcp_pm_subflow_established",
        "net/mptcp/pm.c:mptcp_pm_fully_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591109184,
      "name": "mptcp_pm_schedule_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool mptcp_pm_schedule_work(struct mptcp_sock * msk, enum mptcp_pm_status new_status)
```

```json
{
  "name": "mptcp_pm_schedule_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591191936,
      "name": "mptcp_pm_schedule_work",
      "external": false,
      "loc": "net/mptcp/pm.c:106",
      "file": "net/mptcp/pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm.c:mptcp_pm_rm_addr_received",
        "net/mptcp/pm.c:mptcp_pm_add_addr_received",
        "net/mptcp/pm.c:mptcp_pm_add_addr_received",
        "net/mptcp/pm.c:mptcp_pm_subflow_established",
        "net/mptcp/pm.c:mptcp_pm_fully_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591191936,
      "name": "mptcp_pm_schedule_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool mptcp_pm_schedule_work(struct mptcp_sock * msk, enum mptcp_pm_status new_status)
```

```json
{
  "name": "mptcp_pm_schedule_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591129312,
      "name": "mptcp_pm_schedule_work",
      "external": false,
      "loc": "net/mptcp/pm.c:111",
      "file": "net/mptcp/pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm.c:mptcp_pm_rm_addr_received",
        "net/mptcp/pm.c:mptcp_pm_add_addr_echoed",
        "net/mptcp/pm.c:mptcp_pm_add_addr_received",
        "net/mptcp/pm.c:mptcp_pm_add_addr_received",
        "net/mptcp/pm.c:mptcp_pm_subflow_established",
        "net/mptcp/pm.c:mptcp_pm_fully_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591129312,
      "name": "mptcp_pm_schedule_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool mptcp_pm_schedule_work(struct mptcp_sock * msk, enum mptcp_pm_status new_status)
```

```json
{
  "name": "mptcp_pm_schedule_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591977984,
      "name": "mptcp_pm_schedule_work",
      "external": false,
      "loc": "net/mptcp/pm.c:113",
      "file": "net/mptcp/pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm.c:mptcp_pm_rm_addr_received",
        "net/mptcp/pm.c:mptcp_pm_add_addr_echoed",
        "net/mptcp/pm.c:mptcp_pm_add_addr_received",
        "net/mptcp/pm.c:mptcp_pm_add_addr_received",
        "net/mptcp/pm.c:mptcp_pm_subflow_established",
        "net/mptcp/pm.c:mptcp_pm_fully_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591977984,
      "name": "mptcp_pm_schedule_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool mptcp_pm_schedule_work(struct mptcp_sock * msk, enum mptcp_pm_status new_status)
```

```json
{
  "name": "mptcp_pm_schedule_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593707568,
      "name": "mptcp_pm_schedule_work",
      "external": false,
      "loc": "net/mptcp/pm.c:116",
      "file": "net/mptcp/pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm.c:mptcp_pm_rm_addr_received",
        "net/mptcp/pm.c:mptcp_pm_add_addr_echoed",
        "net/mptcp/pm.c:mptcp_pm_add_addr_received",
        "net/mptcp/pm.c:mptcp_pm_add_addr_received",
        "net/mptcp/pm.c:mptcp_pm_subflow_check_next",
        "net/mptcp/pm.c:mptcp_pm_subflow_established",
        "net/mptcp/pm.c:mptcp_pm_fully_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593707568,
      "name": "mptcp_pm_schedule_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool mptcp_pm_schedule_work(struct mptcp_sock * msk, enum mptcp_pm_status new_status)
```

```json
{
  "name": "mptcp_pm_schedule_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595641648,
      "name": "mptcp_pm_schedule_work",
      "external": false,
      "loc": "net/mptcp/pm.c:116",
      "file": "net/mptcp/pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm.c:mptcp_pm_rm_addr_received",
        "net/mptcp/pm.c:mptcp_pm_add_addr_echoed",
        "net/mptcp/pm.c:mptcp_pm_add_addr_received",
        "net/mptcp/pm.c:mptcp_pm_add_addr_received",
        "net/mptcp/pm.c:mptcp_pm_subflow_check_next",
        "net/mptcp/pm.c:mptcp_pm_subflow_established",
        "net/mptcp/pm.c:mptcp_pm_fully_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595641648,
      "name": "mptcp_pm_schedule_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool mptcp_pm_schedule_work(struct mptcp_sock * msk, enum mptcp_pm_status new_status)
```

```json
{
  "name": "mptcp_pm_schedule_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596149968,
      "name": "mptcp_pm_schedule_work",
      "external": false,
      "loc": "net/mptcp/pm.c:125",
      "file": "net/mptcp/pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm.c:mptcp_pm_rm_addr_received",
        "net/mptcp/pm.c:mptcp_pm_add_addr_echoed",
        "net/mptcp/pm.c:mptcp_pm_add_addr_received",
        "net/mptcp/pm.c:mptcp_pm_add_addr_received",
        "net/mptcp/pm.c:mptcp_pm_subflow_check_next",
        "net/mptcp/pm.c:mptcp_pm_subflow_established",
        "net/mptcp/pm.c:mptcp_pm_fully_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596149968,
      "name": "mptcp_pm_schedule_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool mptcp_pm_schedule_work(struct mptcp_sock * msk, enum mptcp_pm_status new_status)
```

```json
{
  "name": "mptcp_pm_schedule_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597023984,
      "name": "mptcp_pm_schedule_work",
      "external": false,
      "loc": "net/mptcp/pm.c:125",
      "file": "net/mptcp/pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm.c:mptcp_pm_rm_addr_received",
        "net/mptcp/pm.c:mptcp_pm_add_addr_echoed",
        "net/mptcp/pm.c:mptcp_pm_add_addr_received",
        "net/mptcp/pm.c:mptcp_pm_add_addr_received",
        "net/mptcp/pm.c:mptcp_pm_subflow_check_next",
        "net/mptcp/pm.c:mptcp_pm_subflow_established",
        "net/mptcp/pm.c:mptcp_pm_fully_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597023984,
      "name": "mptcp_pm_schedule_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool mptcp_pm_schedule_work(struct mptcp_sock * msk, enum mptcp_pm_status new_status)
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
