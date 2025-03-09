# Function: <code>mptcp_pm_announce_addr</code>

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
int mptcp_pm_announce_addr(struct mptcp_sock * msk, const struct mptcp_addr_info * addr)
```

```json
{
  "name": "mptcp_pm_announce_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591109680,
      "name": "mptcp_pm_announce_addr",
      "external": true,
      "loc": "net/mptcp/pm.c:17",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591109680,
      "name": "mptcp_pm_announce_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int mptcp_pm_announce_addr(struct mptcp_sock * msk, const struct mptcp_addr_info * addr, bool echo, bool port)
```

```json
{
  "name": "mptcp_pm_announce_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_pm_announce_addr",
      "external": true,
      "loc": "net/mptcp/pm.c:15",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm.c:mptcp_pm_add_addr_received",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received",
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr",
        "net/mptcp/pm_netlink.c:mptcp_pm_add_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591640944,
      "name": "mptcp_pm_announce_addr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071591192080,
      "name": "mptcp_pm_announce_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int mptcp_pm_announce_addr(struct mptcp_sock * msk, const struct mptcp_addr_info * addr, bool echo)
```

```json
{
  "name": "mptcp_pm_announce_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_pm_announce_addr",
      "external": true,
      "loc": "net/mptcp/pm.c:15",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm.c:mptcp_pm_add_addr_received",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received",
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr",
        "net/mptcp/pm_netlink.c:mptcp_pm_add_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591584439,
      "name": "mptcp_pm_announce_addr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071591129456,
      "name": "mptcp_pm_announce_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int mptcp_pm_announce_addr(struct mptcp_sock * msk, const struct mptcp_addr_info * addr, bool echo)
```

```json
{
  "name": "mptcp_pm_announce_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_pm_announce_addr",
      "external": true,
      "loc": "net/mptcp/pm.c:17",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm.c:mptcp_pm_add_addr_received",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received",
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr",
        "net/mptcp/pm_netlink.c:mptcp_pm_add_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592754760,
      "name": "mptcp_pm_announce_addr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071591978112,
      "name": "mptcp_pm_announce_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int mptcp_pm_announce_addr(struct mptcp_sock * msk, const struct mptcp_addr_info * addr, bool echo)
```

```json
{
  "name": "mptcp_pm_announce_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_pm_announce_addr",
      "external": true,
      "loc": "net/mptcp/pm.c:17",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm.c:mptcp_pm_add_addr_received",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received",
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr",
        "net/mptcp/pm_netlink.c:mptcp_pm_add_timer",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594641786,
      "name": "mptcp_pm_announce_addr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071593707712,
      "name": "mptcp_pm_announce_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
int mptcp_pm_announce_addr(struct mptcp_sock * msk, const struct mptcp_addr_info * addr, bool echo)
```

```json
{
  "name": "mptcp_pm_announce_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595641808,
      "name": "mptcp_pm_announce_addr",
      "external": true,
      "loc": "net/mptcp/pm.c:17",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm.c:mptcp_pm_add_addr_received",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received",
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr",
        "net/mptcp/pm_netlink.c:mptcp_pm_add_timer",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595641808,
      "name": "mptcp_pm_announce_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int mptcp_pm_announce_addr(struct mptcp_sock * msk, const struct mptcp_addr_info * addr, bool echo)
```

```json
{
  "name": "mptcp_pm_announce_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596150128,
      "name": "mptcp_pm_announce_addr",
      "external": true,
      "loc": "net/mptcp/pm.c:17",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm.c:mptcp_pm_add_addr_received",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received",
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr",
        "net/mptcp/pm_netlink.c:mptcp_pm_add_timer",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596150128,
      "name": "mptcp_pm_announce_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
int mptcp_pm_announce_addr(struct mptcp_sock * msk, const struct mptcp_addr_info * addr, bool echo)
```

```json
{
  "name": "mptcp_pm_announce_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597024144,
      "name": "mptcp_pm_announce_addr",
      "external": true,
      "loc": "net/mptcp/pm.c:17",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm.c:mptcp_pm_add_addr_received",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received",
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr",
        "net/mptcp/pm_netlink.c:mptcp_pm_add_timer",
        "net/mptcp/pm_userspace.c:mptcp_pm_nl_announce_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597024144,
      "name": "mptcp_pm_announce_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
int mptcp_pm_announce_addr(struct mptcp_sock * msk, const struct mptcp_addr_info * addr)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool echo</code>
</li>
<li>
<b>Param added. </b>
<code>bool port</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool port</code>
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
