# Function: <code>mptcp_subflow_shutdown</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mptcp_subflow_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591086676,
      "name": "mptcp_subflow_shutdown",
      "external": false,
      "loc": "net/mptcp/protocol.c:1314",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_shutdown"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void mptcp_subflow_shutdown(struct sock * sk, struct sock * ssk, int how)
```

```json
{
  "name": "mptcp_subflow_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591162288,
      "name": "mptcp_subflow_shutdown",
      "external": true,
      "loc": "net/mptcp/protocol.c:2433",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_check_send_data_fin",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_subflow_received",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_received"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591162288,
      "name": "mptcp_subflow_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
void mptcp_subflow_shutdown(struct sock * sk, struct sock * ssk, int how)
```

```json
{
  "name": "mptcp_subflow_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591095728,
      "name": "mptcp_subflow_shutdown",
      "external": true,
      "loc": "net/mptcp/protocol.c:2501",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_check_send_data_fin",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591095728,
      "name": "mptcp_subflow_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
void mptcp_subflow_shutdown(struct sock * sk, struct sock * ssk, int how)
```

```json
{
  "name": "mptcp_subflow_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591938480,
      "name": "mptcp_subflow_shutdown",
      "external": true,
      "loc": "net/mptcp/protocol.c:2559",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_check_send_data_fin",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591938480,
      "name": "mptcp_subflow_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void mptcp_subflow_shutdown(struct sock * sk, struct sock * ssk, int how)
```

```json
{
  "name": "mptcp_subflow_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593663888,
      "name": "mptcp_subflow_shutdown",
      "external": true,
      "loc": "net/mptcp/protocol.c:2703",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_check_send_data_fin",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593663888,
      "name": "mptcp_subflow_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
void mptcp_subflow_shutdown(struct sock * sk, struct sock * ssk, int how)
```

```json
{
  "name": "mptcp_subflow_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595594528,
      "name": "mptcp_subflow_shutdown",
      "external": true,
      "loc": "net/mptcp/protocol.c:2751",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_check_send_data_fin",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595594528,
      "name": "mptcp_subflow_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
void mptcp_subflow_shutdown(struct sock * sk, struct sock * ssk, int how)
```

```json
{
  "name": "mptcp_subflow_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596103696,
      "name": "mptcp_subflow_shutdown",
      "external": true,
      "loc": "net/mptcp/protocol.c:2756",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_check_send_data_fin",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596103696,
      "name": "mptcp_subflow_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
void mptcp_subflow_shutdown(struct sock * sk, struct sock * ssk, int how)
```

```json
{
  "name": "mptcp_subflow_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596973696,
      "name": "mptcp_subflow_shutdown",
      "external": true,
      "loc": "net/mptcp/protocol.c:2843",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_check_send_data_fin",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow",
        "net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_destroy_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596973696,
      "name": "mptcp_subflow_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
void mptcp_subflow_shutdown(struct sock * sk, struct sock * ssk, int how)
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
