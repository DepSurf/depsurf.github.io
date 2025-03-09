# Function: <code>mptcp_token_iter_next</code>

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
struct mptcp_sock * mptcp_token_iter_next(const struct net * net, long int * s_slot, long int * s_num)
```

```json
{
  "name": "mptcp_token_iter_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591188992,
      "name": "mptcp_token_iter_next",
      "external": true,
      "loc": "net/mptcp/token.c:289",
      "file": "net/mptcp/token.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591188992,
      "name": "mptcp_token_iter_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 469
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
struct mptcp_sock * mptcp_token_iter_next(const struct net * net, long int * s_slot, long int * s_num)
```

```json
{
  "name": "mptcp_token_iter_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591126400,
      "name": "mptcp_token_iter_next",
      "external": true,
      "loc": "net/mptcp/token.c:289",
      "file": "net/mptcp/token.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_addrs_list",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591126400,
      "name": "mptcp_token_iter_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
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
struct mptcp_sock * mptcp_token_iter_next(const struct net * net, long int * s_slot, long int * s_num)
```

```json
{
  "name": "mptcp_token_iter_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591974288,
      "name": "mptcp_token_iter_next",
      "external": true,
      "loc": "net/mptcp/token.c:293",
      "file": "net/mptcp/token.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_addrs_list",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591974288,
      "name": "mptcp_token_iter_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
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
struct mptcp_sock * mptcp_token_iter_next(const struct net * net, long int * s_slot, long int * s_num)
```

```json
{
  "name": "mptcp_token_iter_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593703328,
      "name": "mptcp_token_iter_next",
      "external": true,
      "loc": "net/mptcp/token.c:293",
      "file": "net/mptcp/token.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593703328,
      "name": "mptcp_token_iter_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 501
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
struct mptcp_sock * mptcp_token_iter_next(const struct net * net, long int * s_slot, long int * s_num)
```

```json
{
  "name": "mptcp_token_iter_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595637104,
      "name": "mptcp_token_iter_next",
      "external": true,
      "loc": "net/mptcp/token.c:293",
      "file": "net/mptcp/token.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595637104,
      "name": "mptcp_token_iter_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 501
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
struct mptcp_sock * mptcp_token_iter_next(const struct net * net, long int * s_slot, long int * s_num)
```

```json
{
  "name": "mptcp_token_iter_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596145408,
      "name": "mptcp_token_iter_next",
      "external": true,
      "loc": "net/mptcp/token.c:297",
      "file": "net/mptcp/token.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596145408,
      "name": "mptcp_token_iter_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
struct mptcp_sock * mptcp_token_iter_next(const struct net * net, long int * s_slot, long int * s_num)
```

```json
{
  "name": "mptcp_token_iter_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597019120,
      "name": "mptcp_token_iter_next",
      "external": true,
      "loc": "net/mptcp/token.c:297",
      "file": "net/mptcp/token.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_flush_addrs_doit",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597019120,
      "name": "mptcp_token_iter_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
struct mptcp_sock * mptcp_token_iter_next(const struct net * net, long int * s_slot, long int * s_num)
```
</details>
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
