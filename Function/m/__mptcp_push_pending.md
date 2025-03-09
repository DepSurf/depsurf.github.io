# Function: <code>__mptcp_push_pending</code>

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
void __mptcp_push_pending(struct sock * sk, unsigned int flags)
```

```json
{
  "name": "__mptcp_push_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591163008,
      "name": "__mptcp_push_pending",
      "external": false,
      "loc": "net/mptcp/protocol.c:1445",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591163008,
      "name": "__mptcp_push_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 695
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
void __mptcp_push_pending(struct sock * sk, unsigned int flags)
```

```json
{
  "name": "__mptcp_push_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591096320,
      "name": "__mptcp_push_pending",
      "external": false,
      "loc": "net/mptcp/protocol.c:1486",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591096320,
      "name": "__mptcp_push_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 586
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
void __mptcp_push_pending(struct sock * sk, unsigned int flags)
```

```json
{
  "name": "__mptcp_push_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591939360,
      "name": "__mptcp_push_pending",
      "external": true,
      "loc": "net/mptcp/protocol.c:1537",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591939360,
      "name": "__mptcp_push_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 550
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
void __mptcp_push_pending(struct sock * sk, unsigned int flags)
```

```json
{
  "name": "__mptcp_push_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593665776,
      "name": "__mptcp_push_pending",
      "external": true,
      "loc": "net/mptcp/protocol.c:1570",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593665776,
      "name": "__mptcp_push_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 682
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
void __mptcp_push_pending(struct sock * sk, unsigned int flags)
```

```json
{
  "name": "__mptcp_push_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595595536,
      "name": "__mptcp_push_pending",
      "external": true,
      "loc": "net/mptcp/protocol.c:1531",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595595536,
      "name": "__mptcp_push_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 683
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
void __mptcp_push_pending(struct sock * sk, unsigned int flags)
```

```json
{
  "name": "__mptcp_push_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596104688,
      "name": "__mptcp_push_pending",
      "external": true,
      "loc": "net/mptcp/protocol.c:1504",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596104688,
      "name": "__mptcp_push_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 708
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
void __mptcp_push_pending(struct sock * sk, unsigned int flags)
```

```json
{
  "name": "__mptcp_push_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mptcp_push_pending",
      "external": true,
      "loc": "net/mptcp/protocol.c:1558",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597824201,
      "name": "__mptcp_push_pending.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071596974512,
      "name": "__mptcp_push_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 667
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
void __mptcp_push_pending(struct sock * sk, unsigned int flags)
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
