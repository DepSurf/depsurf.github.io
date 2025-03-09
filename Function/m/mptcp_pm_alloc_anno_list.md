# Function: <code>mptcp_pm_alloc_anno_list</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool mptcp_pm_alloc_anno_list(struct mptcp_sock * msk, struct mptcp_pm_addr_entry * entry)
```

```json
{
  "name": "mptcp_pm_alloc_anno_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591198416,
      "name": "mptcp_pm_alloc_anno_list",
      "external": false,
      "loc": "net/mptcp/pm_netlink.c:266",
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
      "addr": 18446744071591198416,
      "name": "mptcp_pm_alloc_anno_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
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
  "name": "mptcp_pm_alloc_anno_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591142832,
      "name": "mptcp_pm_alloc_anno_list",
      "external": false,
      "loc": "net/mptcp/pm_netlink.c:366",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr"
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
  "name": "mptcp_pm_alloc_anno_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591993092,
      "name": "mptcp_pm_alloc_anno_list",
      "external": false,
      "loc": "net/mptcp/pm_netlink.c:366",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool mptcp_pm_alloc_anno_list(struct mptcp_sock * msk, const struct mptcp_pm_addr_entry * entry)
```

```json
{
  "name": "mptcp_pm_alloc_anno_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593721376,
      "name": "mptcp_pm_alloc_anno_list",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:355",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593721376,
      "name": "mptcp_pm_alloc_anno_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
bool mptcp_pm_alloc_anno_list(struct mptcp_sock * msk, const struct mptcp_pm_addr_entry * entry)
```

```json
{
  "name": "mptcp_pm_alloc_anno_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595656672,
      "name": "mptcp_pm_alloc_anno_list",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:355",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595656672,
      "name": "mptcp_pm_alloc_anno_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
bool mptcp_pm_alloc_anno_list(struct mptcp_sock * msk, const struct mptcp_addr_info * addr)
```

```json
{
  "name": "mptcp_pm_alloc_anno_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596165744,
      "name": "mptcp_pm_alloc_anno_list",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:343",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596165744,
      "name": "mptcp_pm_alloc_anno_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
bool mptcp_pm_alloc_anno_list(struct mptcp_sock * msk, const struct mptcp_addr_info * addr)
```

```json
{
  "name": "mptcp_pm_alloc_anno_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597039072,
      "name": "mptcp_pm_alloc_anno_list",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:344",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr",
        "net/mptcp/pm_userspace.c:mptcp_pm_nl_announce_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597039072,
      "name": "mptcp_pm_alloc_anno_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
bool mptcp_pm_alloc_anno_list(struct mptcp_sock * msk, struct mptcp_pm_addr_entry * entry)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
bool mptcp_pm_alloc_anno_list(struct mptcp_sock * msk, struct mptcp_pm_addr_entry * entry)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
bool mptcp_pm_alloc_anno_list(struct mptcp_sock * msk, const struct mptcp_pm_addr_entry * entry)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct mptcp_addr_info * addr</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct mptcp_pm_addr_entry * entry</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
