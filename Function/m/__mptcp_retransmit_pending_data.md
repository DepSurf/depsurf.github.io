# Function: <code>__mptcp_retransmit_pending_data</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool __mptcp_retransmit_pending_data(struct sock * sk)
```

```json
{
  "name": "__mptcp_retransmit_pending_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591938016,
      "name": "__mptcp_retransmit_pending_data",
      "external": true,
      "loc": "net/mptcp/protocol.c:2189",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591938016,
      "name": "__mptcp_retransmit_pending_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
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
bool __mptcp_retransmit_pending_data(struct sock * sk)
```

```json
{
  "name": "__mptcp_retransmit_pending_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593663328,
      "name": "__mptcp_retransmit_pending_data",
      "external": true,
      "loc": "net/mptcp/protocol.c:2252",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593663328,
      "name": "__mptcp_retransmit_pending_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
bool __mptcp_retransmit_pending_data(struct sock * sk)
```

```json
{
  "name": "__mptcp_retransmit_pending_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595593824,
      "name": "__mptcp_retransmit_pending_data",
      "external": true,
      "loc": "net/mptcp/protocol.c:2263",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595593824,
      "name": "__mptcp_retransmit_pending_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
bool __mptcp_retransmit_pending_data(struct sock * sk)
```

```json
{
  "name": "__mptcp_retransmit_pending_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596102992,
      "name": "__mptcp_retransmit_pending_data",
      "external": true,
      "loc": "net/mptcp/protocol.c:2254",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596102992,
      "name": "__mptcp_retransmit_pending_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
bool __mptcp_retransmit_pending_data(struct sock * sk)
```

```json
{
  "name": "__mptcp_retransmit_pending_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596973008,
      "name": "__mptcp_retransmit_pending_data",
      "external": true,
      "loc": "net/mptcp/protocol.c:2316",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596973008,
      "name": "__mptcp_retransmit_pending_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
bool __mptcp_retransmit_pending_data(struct sock * sk)
```
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
