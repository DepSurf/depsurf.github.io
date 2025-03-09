# Function: <code>__mptcp_subflow_connect</code>

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
int __mptcp_subflow_connect(struct sock * sk, int ifindex, const struct mptcp_addr_info * loc, const struct mptcp_addr_info * remote)
```

```json
{
  "name": "__mptcp_subflow_connect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591099648,
      "name": "__mptcp_subflow_connect",
      "external": true,
      "loc": "net/mptcp/subflow.c:970",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received",
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591099648,
      "name": "__mptcp_subflow_connect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 636
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
int __mptcp_subflow_connect(struct sock * sk, const struct mptcp_addr_info * loc, const struct mptcp_addr_info * remote)
```

```json
{
  "name": "__mptcp_subflow_connect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591180304,
      "name": "__mptcp_subflow_connect",
      "external": true,
      "loc": "net/mptcp/subflow.c:1140",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received",
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591180304,
      "name": "__mptcp_subflow_connect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1036
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int __mptcp_subflow_connect(struct sock * sk, const struct mptcp_addr_info * loc, const struct mptcp_addr_info * remote, u8 flags, int ifindex)
```

```json
{
  "name": "__mptcp_subflow_connect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591116464,
      "name": "__mptcp_subflow_connect",
      "external": true,
      "loc": "net/mptcp/subflow.c:1252",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received",
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591116464,
      "name": "__mptcp_subflow_connect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 961
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
int __mptcp_subflow_connect(struct sock * sk, const struct mptcp_addr_info * loc, const struct mptcp_addr_info * remote)
```

```json
{
  "name": "__mptcp_subflow_connect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mptcp_subflow_connect",
      "external": true,
      "loc": "net/mptcp/subflow.c:1379",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received",
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592754065,
      "name": "__mptcp_subflow_connect.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071591962096,
      "name": "__mptcp_subflow_connect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1009
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
int __mptcp_subflow_connect(struct sock * sk, const struct mptcp_addr_info * loc, const struct mptcp_addr_info * remote)
```

```json
{
  "name": "__mptcp_subflow_connect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mptcp_subflow_connect",
      "external": true,
      "loc": "net/mptcp/subflow.c:1467",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received",
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594641138,
      "name": "__mptcp_subflow_connect.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071593689872,
      "name": "__mptcp_subflow_connect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1045
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int __mptcp_subflow_connect(struct sock * sk, const struct mptcp_addr_info * loc, const struct mptcp_addr_info * remote)
```

```json
{
  "name": "__mptcp_subflow_connect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mptcp_subflow_connect",
      "external": true,
      "loc": "net/mptcp/subflow.c:1539",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received",
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596370561,
      "name": "__mptcp_subflow_connect.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071595623040,
      "name": "__mptcp_subflow_connect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1056
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int __mptcp_subflow_connect(struct sock * sk, const struct mptcp_addr_info * loc, const struct mptcp_addr_info * remote)
```

```json
{
  "name": "__mptcp_subflow_connect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mptcp_subflow_connect",
      "external": true,
      "loc": "net/mptcp/subflow.c:1519",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received",
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596899822,
      "name": "__mptcp_subflow_connect.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071596131408,
      "name": "__mptcp_subflow_connect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1080
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int __mptcp_subflow_connect(struct sock * sk, const struct mptcp_addr_info * loc, const struct mptcp_addr_info * remote)
```

```json
{
  "name": "__mptcp_subflow_connect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mptcp_subflow_connect",
      "external": true,
      "loc": "net/mptcp/subflow.c:1516",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received",
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr",
        "net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_create_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597825123,
      "name": "__mptcp_subflow_connect.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071597005104,
      "name": "__mptcp_subflow_connect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1115
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
int __mptcp_subflow_connect(struct sock * sk, int ifindex, const struct mptcp_addr_info * loc, const struct mptcp_addr_info * remote)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int ifindex</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, ifindex, loc, remote</code> ➡️ <code>sk, loc, remote</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 flags</code>
</li>
<li>
<b>Param added. </b>
<code>int ifindex</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u8 flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int ifindex</code>
</li>
</ul>
</details>
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
