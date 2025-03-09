# Function: <code>mptcp_lookup_anno_list_by_saddr</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct mptcp_pm_add_entry * mptcp_lookup_anno_list_by_saddr(struct mptcp_sock * msk, struct mptcp_addr_info * addr)
```

```json
{
  "name": "mptcp_lookup_anno_list_by_saddr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591142853,
      "name": "mptcp_lookup_anno_list_by_saddr",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:267",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr",
        "net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer"
      ],
      "caller_func": [
        "net/mptcp/pm.c:mptcp_pm_add_addr_echoed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591139360,
      "name": "mptcp_lookup_anno_list_by_saddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct mptcp_pm_add_entry * mptcp_lookup_anno_list_by_saddr(struct mptcp_sock * msk, struct mptcp_addr_info * addr)
```

```json
{
  "name": "mptcp_lookup_anno_list_by_saddr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591993116,
      "name": "mptcp_lookup_anno_list_by_saddr",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:267",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr",
        "net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer"
      ],
      "caller_func": [
        "net/mptcp/pm.c:mptcp_pm_add_addr_echoed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591989552,
      "name": "mptcp_lookup_anno_list_by_saddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct mptcp_pm_add_entry * mptcp_lookup_anno_list_by_saddr(const struct mptcp_sock * msk, const struct mptcp_addr_info * addr)
```

```json
{
  "name": "mptcp_lookup_anno_list_by_saddr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593721426,
      "name": "mptcp_lookup_anno_list_by_saddr",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:256",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list",
        "net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer"
      ],
      "caller_func": [
        "net/mptcp/pm.c:mptcp_pm_add_addr_echoed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593719952,
      "name": "mptcp_lookup_anno_list_by_saddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
struct mptcp_pm_add_entry * mptcp_lookup_anno_list_by_saddr(const struct mptcp_sock * msk, const struct mptcp_addr_info * addr)
```

```json
{
  "name": "mptcp_lookup_anno_list_by_saddr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595656722,
      "name": "mptcp_lookup_anno_list_by_saddr",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:256",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list",
        "net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer"
      ],
      "caller_func": [
        "net/mptcp/pm.c:mptcp_pm_add_addr_echoed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595655168,
      "name": "mptcp_lookup_anno_list_by_saddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
struct mptcp_pm_add_entry * mptcp_lookup_anno_list_by_saddr(const struct mptcp_sock * msk, const struct mptcp_addr_info * addr)
```

```json
{
  "name": "mptcp_lookup_anno_list_by_saddr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596165786,
      "name": "mptcp_lookup_anno_list_by_saddr",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:244",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list",
        "net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer"
      ],
      "caller_func": [
        "net/mptcp/pm.c:mptcp_pm_add_addr_echoed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596164096,
      "name": "mptcp_lookup_anno_list_by_saddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
struct mptcp_pm_add_entry * mptcp_lookup_anno_list_by_saddr(const struct mptcp_sock * msk, const struct mptcp_addr_info * addr)
```

```json
{
  "name": "mptcp_lookup_anno_list_by_saddr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597039114,
      "name": "mptcp_lookup_anno_list_by_saddr",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:245",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list",
        "net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer"
      ],
      "caller_func": [
        "net/mptcp/pm.c:mptcp_pm_add_addr_echoed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597038432,
      "name": "mptcp_lookup_anno_list_by_saddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct mptcp_pm_add_entry * mptcp_lookup_anno_list_by_saddr(struct mptcp_sock * msk, struct mptcp_addr_info * addr)
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct mptcp_sock * msk</code> ➡️ <code>const struct mptcp_sock * msk</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct mptcp_addr_info * addr</code> ➡️ <code>const struct mptcp_addr_info * addr</code>
</li>
</ul>
</details>
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
