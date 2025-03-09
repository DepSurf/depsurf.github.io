# Function: <code>lookup_subflow_by_saddr</code>

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
bool lookup_subflow_by_saddr(const struct list_head * list, struct mptcp_addr_info * saddr)
```

```json
{
  "name": "lookup_subflow_by_saddr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591115104,
      "name": "lookup_subflow_by_saddr",
      "external": false,
      "loc": "net/mptcp/pm_netlink.c:95",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr",
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591115104,
      "name": "lookup_subflow_by_saddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
bool lookup_subflow_by_saddr(const struct list_head * list, struct mptcp_addr_info * saddr)
```

```json
{
  "name": "lookup_subflow_by_saddr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591198208,
      "name": "lookup_subflow_by_saddr",
      "external": false,
      "loc": "net/mptcp/pm_netlink.c:113",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591198208,
      "name": "lookup_subflow_by_saddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
bool lookup_subflow_by_saddr(const struct list_head * list, struct mptcp_addr_info * saddr)
```

```json
{
  "name": "lookup_subflow_by_saddr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591141018,
      "name": "lookup_subflow_by_saddr",
      "external": false,
      "loc": "net/mptcp/pm_netlink.c:125",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_addrs_list"
      ],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr",
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591137168,
      "name": "lookup_subflow_by_saddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
bool lookup_subflow_by_saddr(const struct list_head * list, struct mptcp_addr_info * saddr)
```

```json
{
  "name": "lookup_subflow_by_saddr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591991244,
      "name": "lookup_subflow_by_saddr",
      "external": false,
      "loc": "net/mptcp/pm_netlink.c:125",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_addrs_list"
      ],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr",
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591987168,
      "name": "lookup_subflow_by_saddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lookup_subflow_by_saddr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593730823,
      "name": "lookup_subflow_by_saddr",
      "external": false,
      "loc": "net/mptcp/pm_netlink.c:115",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows"
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
  "name": "lookup_subflow_by_saddr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595664967,
      "name": "lookup_subflow_by_saddr",
      "external": false,
      "loc": "net/mptcp/pm_netlink.c:115",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows"
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
  "name": "lookup_subflow_by_saddr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596173223,
      "name": "lookup_subflow_by_saddr",
      "external": false,
      "loc": "net/mptcp/pm_netlink.c:114",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool lookup_subflow_by_saddr(const struct list_head * list, const struct mptcp_addr_info * saddr)
```

```json
{
  "name": "lookup_subflow_by_saddr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597046055,
      "name": "lookup_subflow_by_saddr",
      "external": false,
      "loc": "net/mptcp/pm_netlink.c:115",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows"
      ],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597037344,
      "name": "lookup_subflow_by_saddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
bool lookup_subflow_by_saddr(const struct list_head * list, struct mptcp_addr_info * saddr)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
bool lookup_subflow_by_saddr(const struct list_head * list, struct mptcp_addr_info * saddr)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
bool lookup_subflow_by_saddr(const struct list_head * list, const struct mptcp_addr_info * saddr)
```
</details>
</li>
</ul>
