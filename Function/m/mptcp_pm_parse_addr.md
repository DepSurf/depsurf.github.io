# Function: <code>mptcp_pm_parse_addr</code>

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
int mptcp_pm_parse_addr(struct nlattr * attr, struct genl_info * info, bool require_family, struct mptcp_pm_addr_entry * entry)
```

```json
{
  "name": "mptcp_pm_parse_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591113008,
      "name": "mptcp_pm_parse_addr",
      "external": false,
      "loc": "net/mptcp/pm_netlink.c:410",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591113008,
      "name": "mptcp_pm_parse_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 445
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
int mptcp_pm_parse_addr(struct nlattr * attr, struct genl_info * info, bool require_family, struct mptcp_pm_addr_entry * entry)
```

```json
{
  "name": "mptcp_pm_parse_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591196112,
      "name": "mptcp_pm_parse_addr",
      "external": false,
      "loc": "net/mptcp/pm_netlink.c:671",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591196112,
      "name": "mptcp_pm_parse_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
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
int mptcp_pm_parse_addr(struct nlattr * attr, struct genl_info * info, bool require_family, struct mptcp_pm_addr_entry * entry)
```

```json
{
  "name": "mptcp_pm_parse_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591135840,
      "name": "mptcp_pm_parse_addr",
      "external": false,
      "loc": "net/mptcp/pm_netlink.c:911",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591135840,
      "name": "mptcp_pm_parse_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int mptcp_pm_parse_addr(struct nlattr * attr, struct genl_info * info, bool require_family, struct mptcp_pm_addr_entry * entry)
```

```json
{
  "name": "mptcp_pm_parse_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591985200,
      "name": "mptcp_pm_parse_addr",
      "external": false,
      "loc": "net/mptcp/pm_netlink.c:1078",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591985200,
      "name": "mptcp_pm_parse_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int mptcp_pm_parse_addr(struct nlattr * attr, struct genl_info * info, struct mptcp_addr_info * addr)
```

```json
{
  "name": "mptcp_pm_parse_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593727440,
      "name": "mptcp_pm_parse_addr",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:1217",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593727440,
      "name": "mptcp_pm_parse_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int mptcp_pm_parse_addr(struct nlattr * attr, struct genl_info * info, struct mptcp_addr_info * addr)
```

```json
{
  "name": "mptcp_pm_parse_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595662320,
      "name": "mptcp_pm_parse_addr",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:1232",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595662320,
      "name": "mptcp_pm_parse_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int mptcp_pm_parse_addr(struct nlattr * attr, struct genl_info * info, struct mptcp_addr_info * addr)
```

```json
{
  "name": "mptcp_pm_parse_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596171008,
      "name": "mptcp_pm_parse_addr",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:1236",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596171008,
      "name": "mptcp_pm_parse_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int mptcp_pm_parse_addr(struct nlattr * attr, struct genl_info * info, struct mptcp_addr_info * addr)
```

```json
{
  "name": "mptcp_pm_parse_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597043888,
      "name": "mptcp_pm_parse_addr",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:1223",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_destroy_doit",
        "net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_destroy_doit",
        "net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_create_doit",
        "net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_create_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597043888,
      "name": "mptcp_pm_parse_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int mptcp_pm_parse_addr(struct nlattr * attr, struct genl_info * info, bool require_family, struct mptcp_pm_addr_entry * entry)
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
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mptcp_addr_info * addr</code>
</li>
<li>
<b>Param removed. </b>
<code>bool require_family</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mptcp_pm_addr_entry * entry</code>
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
