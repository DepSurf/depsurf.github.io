# Function: <code>__mptcp_flush_join_list</code>

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
  "name": "__mptcp_flush_join_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591086535,
      "name": "__mptcp_flush_join_list",
      "external": false,
      "loc": "net/mptcp/protocol.c:322",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_shutdown",
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __mptcp_flush_join_list(struct mptcp_sock * msk)
```

```json
{
  "name": "__mptcp_flush_join_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591158805,
      "name": "__mptcp_flush_join_list",
      "external": true,
      "loc": "net/mptcp/protocol.c:731",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_disconnect",
        "net/mptcp/protocol.c:__mptcp_check_send_data_fin",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_move_skbs",
        "net/mptcp/protocol.c:__mptcp_push_pending"
      ],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591159424,
      "name": "__mptcp_flush_join_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void __mptcp_flush_join_list(struct mptcp_sock * msk)
```

```json
{
  "name": "__mptcp_flush_join_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591094208,
      "name": "__mptcp_flush_join_list",
      "external": true,
      "loc": "net/mptcp/protocol.c:753",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_addr_send_ack",
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591094208,
      "name": "__mptcp_flush_join_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
void __mptcp_flush_join_list(struct mptcp_sock * msk)
```

```json
{
  "name": "__mptcp_flush_join_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591934592,
      "name": "__mptcp_flush_join_list",
      "external": true,
      "loc": "net/mptcp/protocol.c:775",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_push_pending",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_addr_send_ack",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received",
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591934592,
      "name": "__mptcp_flush_join_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__mptcp_flush_join_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593668752,
      "name": "__mptcp_flush_join_list",
      "external": false,
      "loc": "net/mptcp/protocol.c:841",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_release_cb"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__mptcp_flush_join_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595597328,
      "name": "__mptcp_flush_join_list",
      "external": false,
      "loc": "net/mptcp/protocol.c:833",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_release_cb"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__mptcp_flush_join_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596107147,
      "name": "__mptcp_flush_join_list",
      "external": false,
      "loc": "net/mptcp/protocol.c:854",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_release_cb"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__mptcp_flush_join_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596977931,
      "name": "__mptcp_flush_join_list",
      "external": false,
      "loc": "net/mptcp/protocol.c:883",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_release_cb"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void __mptcp_flush_join_list(struct mptcp_sock * msk)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void __mptcp_flush_join_list(struct mptcp_sock * msk)
```
</details>
</li>
</ul>
