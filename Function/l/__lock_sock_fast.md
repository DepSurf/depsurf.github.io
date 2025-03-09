# Function: <code>__lock_sock_fast</code>

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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
bool __lock_sock_fast(struct sock * sk)
```

```json
{
  "name": "__lock_sock_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589843904,
      "name": "__lock_sock_fast",
      "external": true,
      "loc": "net/core/sock.c:3235",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_ioctl",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show",
        "net/ipv4/udp.c:udp_destroy_sock",
        "net/ipv4/udp.c:skb_consume_udp",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:__mptcp_move_skbs",
        "net/mptcp/protocol.c:mptcp_rcv_space_adjust",
        "net/mptcp/protocol.c:mptcp_subflow_send_ack",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale",
        "net/mptcp/sockopt.c:mptcp_sockopt_sync_all",
        "net/mptcp/sockopt.c:mptcp_sockopt_sync",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589843904,
      "name": "__lock_sock_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
bool __lock_sock_fast(struct sock * sk)
```

```json
{
  "name": "__lock_sock_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591365136,
      "name": "__lock_sock_fast",
      "external": true,
      "loc": "net/core/sock.c:3421",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_ioctl",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show",
        "net/ipv4/udp.c:udp_destroy_sock",
        "net/ipv4/udp.c:skb_consume_udp",
        "net/unix/af_unix.c:bpf_iter_unix_seq_show",
        "net/mptcp/protocol.c:mptcp_ioctl",
        "net/mptcp/protocol.c:mptcp_ioctl",
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:__mptcp_move_skbs",
        "net/mptcp/protocol.c:mptcp_rcv_space_adjust",
        "net/mptcp/subflow.c:mptcp_subflow_queue_clean",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack",
        "net/mptcp/sockopt.c:mptcp_sockopt_sync",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591365136,
      "name": "__lock_sock_fast",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
bool __lock_sock_fast(struct sock * sk)
```

```json
{
  "name": "__lock_sock_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593119728,
      "name": "__lock_sock_fast",
      "external": true,
      "loc": "net/core/sock.c:3510",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_ioctl",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show",
        "net/ipv4/udp.c:udp_destroy_sock",
        "net/ipv4/udp.c:skb_consume_udp",
        "net/unix/af_unix.c:bpf_iter_unix_seq_show",
        "net/mptcp/protocol.c:mptcp_ioctl",
        "net/mptcp/protocol.c:mptcp_ioctl",
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:__mptcp_close",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:__mptcp_move_skbs",
        "net/mptcp/protocol.c:mptcp_rcv_space_adjust",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale",
        "net/mptcp/pm_netlink.c:__mptcp_pm_send_ack",
        "net/mptcp/pm_netlink.c:__mptcp_pm_send_ack",
        "net/mptcp/pm_netlink.c:__mptcp_pm_send_ack",
        "net/mptcp/sockopt.c:mptcp_sockopt_sync",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593119728,
      "name": "__lock_sock_fast",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
bool __lock_sock_fast(struct sock * sk)
```

```json
{
  "name": "__lock_sock_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593572416,
      "name": "__lock_sock_fast",
      "external": true,
      "loc": "net/core/sock.c:3543",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_ioctl",
        "net/ipv4/udp.c:udp_destroy_sock",
        "net/ipv4/udp.c:skb_consume_udp",
        "net/unix/af_unix.c:bpf_iter_unix_seq_show",
        "net/mptcp/protocol.c:mptcp_ioctl",
        "net/mptcp/protocol.c:mptcp_ioctl",
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:__mptcp_close",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:__mptcp_move_skbs",
        "net/mptcp/protocol.c:mptcp_rcv_space_adjust",
        "net/mptcp/protocol.c:mptcp_send_ack",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale",
        "net/mptcp/pm_netlink.c:__mptcp_pm_send_ack",
        "net/mptcp/pm_netlink.c:__mptcp_pm_send_ack",
        "net/mptcp/pm_netlink.c:__mptcp_pm_send_ack",
        "net/mptcp/sockopt.c:mptcp_sockopt_sync",
        "net/mptcp/sockopt.c:mptcp_diag_fill_info",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593572416,
      "name": "__lock_sock_fast",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
bool __lock_sock_fast(struct sock * sk)
```

```json
{
  "name": "__lock_sock_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594345008,
      "name": "__lock_sock_fast",
      "external": true,
      "loc": "net/core/sock.c:3551",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_ioctl",
        "net/ipv4/udp.c:udp_destroy_sock",
        "net/unix/af_unix.c:bpf_iter_unix_seq_show",
        "net/mptcp/protocol.c:mptcp_ioctl",
        "net/mptcp/protocol.c:mptcp_ioctl",
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:__mptcp_close",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:__mptcp_move_skbs",
        "net/mptcp/protocol.c:mptcp_rcv_space_adjust",
        "net/mptcp/protocol.c:mptcp_send_ack",
        "net/mptcp/diag.c:subflow_get_info",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale",
        "net/mptcp/pm_netlink.c:__mptcp_pm_send_ack",
        "net/mptcp/pm_netlink.c:__mptcp_pm_send_ack",
        "net/mptcp/pm_netlink.c:__mptcp_pm_send_ack",
        "net/mptcp/sockopt.c:mptcp_set_rcvlowat",
        "net/mptcp/sockopt.c:mptcp_diag_fill_info",
        "net/mptcp/sockopt.c:mptcp_setsockopt",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594345008,
      "name": "__lock_sock_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
bool __lock_sock_fast(struct sock * sk)
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
