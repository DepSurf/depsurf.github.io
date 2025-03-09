# Function: <code>mptcp_pm_remove_subflow</code>

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
int mptcp_pm_remove_subflow(struct mptcp_sock * msk, u8 remote_id)
```

```json
{
  "name": "mptcp_pm_remove_subflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_pm_remove_subflow",
      "external": true,
      "loc": "net/mptcp/pm.c:32",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591109808,
      "name": "mptcp_pm_remove_subflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int mptcp_pm_remove_subflow(struct mptcp_sock * msk, u8 local_id)
```

```json
{
  "name": "mptcp_pm_remove_subflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591192368,
      "name": "mptcp_pm_remove_subflow",
      "external": true,
      "loc": "net/mptcp/pm.c:59",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591192368,
      "name": "mptcp_pm_remove_subflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int mptcp_pm_remove_subflow(struct mptcp_sock * msk, const struct mptcp_rm_list * rm_list)
```

```json
{
  "name": "mptcp_pm_remove_subflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591129760,
      "name": "mptcp_pm_remove_subflow",
      "external": true,
      "loc": "net/mptcp/pm.c:60",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_addrs_list",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591129760,
      "name": "mptcp_pm_remove_subflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int mptcp_pm_remove_subflow(struct mptcp_sock * msk, const struct mptcp_rm_list * rm_list)
```

```json
{
  "name": "mptcp_pm_remove_subflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591978448,
      "name": "mptcp_pm_remove_subflow",
      "external": true,
      "loc": "net/mptcp/pm.c:62",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_addrs_list",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591978448,
      "name": "mptcp_pm_remove_subflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int mptcp_pm_remove_subflow(struct mptcp_sock * msk, const struct mptcp_rm_list * rm_list)
```

```json
{
  "name": "mptcp_pm_remove_subflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593708064,
      "name": "mptcp_pm_remove_subflow",
      "external": true,
      "loc": "net/mptcp/pm.c:62",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593708064,
      "name": "mptcp_pm_remove_subflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int mptcp_pm_remove_subflow(struct mptcp_sock * msk, const struct mptcp_rm_list * rm_list)
```

```json
{
  "name": "mptcp_pm_remove_subflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595642240,
      "name": "mptcp_pm_remove_subflow",
      "external": true,
      "loc": "net/mptcp/pm.c:62",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595642240,
      "name": "mptcp_pm_remove_subflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int mptcp_pm_remove_subflow(struct mptcp_sock * msk, const struct mptcp_rm_list * rm_list)
```

```json
{
  "name": "mptcp_pm_remove_subflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596150576,
      "name": "mptcp_pm_remove_subflow",
      "external": true,
      "loc": "net/mptcp/pm.c:64",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596150576,
      "name": "mptcp_pm_remove_subflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int mptcp_pm_remove_subflow(struct mptcp_sock * msk, const struct mptcp_rm_list * rm_list)
```

```json
{
  "name": "mptcp_pm_remove_subflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597024592,
      "name": "mptcp_pm_remove_subflow",
      "external": true,
      "loc": "net/mptcp/pm.c:64",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597024592,
      "name": "mptcp_pm_remove_subflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int mptcp_pm_remove_subflow(struct mptcp_sock * msk, u8 remote_id)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 local_id</code>
</li>
<li>
<b>Param removed. </b>
<code>u8 remote_id</code>
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
<code>const struct mptcp_rm_list * rm_list</code>
</li>
<li>
<b>Param removed. </b>
<code>u8 local_id</code>
</li>
</ul>
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
