# Function: <code>mptcp_pm_del_add_timer</code>

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
struct mptcp_pm_add_entry * mptcp_pm_del_add_timer(struct mptcp_sock * msk, struct mptcp_addr_info * addr)
```

```json
{
  "name": "mptcp_pm_del_add_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591200272,
      "name": "mptcp_pm_del_add_timer",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:248",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_incoming_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591200272,
      "name": "mptcp_pm_del_add_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
struct mptcp_pm_add_entry * mptcp_pm_del_add_timer(struct mptcp_sock * msk, struct mptcp_addr_info * addr, bool check_id)
```

```json
{
  "name": "mptcp_pm_del_add_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591139680,
      "name": "mptcp_pm_del_add_timer",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:348",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_incoming_options",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_addrs_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591139680,
      "name": "mptcp_pm_del_add_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
struct mptcp_pm_add_entry * mptcp_pm_del_add_timer(struct mptcp_sock * msk, struct mptcp_addr_info * addr, bool check_id)
```

```json
{
  "name": "mptcp_pm_del_add_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591989872,
      "name": "mptcp_pm_del_add_timer",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:348",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_incoming_options",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_addrs_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591989872,
      "name": "mptcp_pm_del_add_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
struct mptcp_pm_add_entry * mptcp_pm_del_add_timer(struct mptcp_sock * msk, const struct mptcp_addr_info * addr, bool check_id)
```

```json
{
  "name": "mptcp_pm_del_add_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593720336,
      "name": "mptcp_pm_del_add_timer",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:337",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_incoming_options",
        "net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593720336,
      "name": "mptcp_pm_del_add_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct mptcp_pm_add_entry * mptcp_pm_del_add_timer(struct mptcp_sock * msk, const struct mptcp_addr_info * addr, bool check_id)
```

```json
{
  "name": "mptcp_pm_del_add_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595655584,
      "name": "mptcp_pm_del_add_timer",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:337",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_incoming_options",
        "net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595655584,
      "name": "mptcp_pm_del_add_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct mptcp_pm_add_entry * mptcp_pm_del_add_timer(struct mptcp_sock * msk, const struct mptcp_addr_info * addr, bool check_id)
```

```json
{
  "name": "mptcp_pm_del_add_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596164512,
      "name": "mptcp_pm_del_add_timer",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:325",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_incoming_options",
        "net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows",
        "net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596164512,
      "name": "mptcp_pm_del_add_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct mptcp_pm_add_entry * mptcp_pm_del_add_timer(struct mptcp_sock * msk, const struct mptcp_addr_info * addr, bool check_id)
```

```json
{
  "name": "mptcp_pm_del_add_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597038848,
      "name": "mptcp_pm_del_add_timer",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:326",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_incoming_options",
        "net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows",
        "net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597038848,
      "name": "mptcp_pm_del_add_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct mptcp_pm_add_entry * mptcp_pm_del_add_timer(struct mptcp_sock * msk, struct mptcp_addr_info * addr)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool check_id</code>
</li>
</ul>
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
