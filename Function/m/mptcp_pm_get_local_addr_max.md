# Function: <code>mptcp_pm_get_local_addr_max</code>

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
unsigned int mptcp_pm_get_local_addr_max(struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_pm_get_local_addr_max",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591146784,
      "name": "mptcp_pm_get_local_addr_max",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:249",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_data_init",
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591133200,
      "name": "mptcp_pm_get_local_addr_max",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
unsigned int mptcp_pm_get_local_addr_max(struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_pm_get_local_addr_max",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591997376,
      "name": "mptcp_pm_get_local_addr_max",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:249",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_data_init",
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591982736,
      "name": "mptcp_pm_get_local_addr_max",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
unsigned int mptcp_pm_get_local_addr_max(const struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_pm_get_local_addr_max",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593722336,
      "name": "mptcp_pm_get_local_addr_max",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:234",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr"
      ],
      "caller_func": [
        "net/mptcp/pm.c:mptcp_pm_data_reset",
        "net/mptcp/sockopt.c:mptcp_diag_fill_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593717264,
      "name": "mptcp_pm_get_local_addr_max",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
unsigned int mptcp_pm_get_local_addr_max(const struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_pm_get_local_addr_max",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595657618,
      "name": "mptcp_pm_get_local_addr_max",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:234",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr"
      ],
      "caller_func": [
        "net/mptcp/pm.c:mptcp_pm_data_reset",
        "net/mptcp/sockopt.c:mptcp_diag_fill_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595652368,
      "name": "mptcp_pm_get_local_addr_max",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
unsigned int mptcp_pm_get_local_addr_max(const struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_pm_get_local_addr_max",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596166674,
      "name": "mptcp_pm_get_local_addr_max",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:222",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr"
      ],
      "caller_func": [
        "net/mptcp/pm.c:mptcp_pm_data_reset",
        "net/mptcp/sockopt.c:mptcp_diag_fill_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596161120,
      "name": "mptcp_pm_get_local_addr_max",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
unsigned int mptcp_pm_get_local_addr_max(const struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_pm_get_local_addr_max",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597041106,
      "name": "mptcp_pm_get_local_addr_max",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:223",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr"
      ],
      "caller_func": [
        "net/mptcp/pm.c:mptcp_pm_data_reset",
        "net/mptcp/sockopt.c:mptcp_diag_fill_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597035584,
      "name": "mptcp_pm_get_local_addr_max",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
unsigned int mptcp_pm_get_local_addr_max(struct mptcp_sock * msk)
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
