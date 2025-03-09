# Function: <code>sk_error_report</code>

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
void sk_error_report(struct sock * sk)
```

```json
{
  "name": "sk_error_report",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589829696,
      "name": "sk_error_report",
      "external": true,
      "loc": "net/core/sock.c:337",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_dequeue_err_skb",
        "net/core/skbuff.c:sock_queue_err_skb",
        "net/core/skbuff.c:msg_zerocopy_callback",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_set_err",
        "net/netlink/af_netlink.c:netlink_overrun",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_input.c:tcp_reset",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/raw.c:raw_abort",
        "net/ipv4/raw.c:raw_icmp_error",
        "net/ipv4/udp.c:udp_abort",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/ping.c:ping_err",
        "net/unix/af_unix.c:unix_dgram_disconnected",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_do_bind",
        "net/xdp/xsk.c:xsk_notifier",
        "net/mptcp/subflow.c:__mptcp_error_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589829696,
      "name": "sk_error_report",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void sk_error_report(struct sock * sk)
```

```json
{
  "name": "sk_error_report",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591353616,
      "name": "sk_error_report",
      "external": true,
      "loc": "net/core/sock.c:343",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_dequeue_err_skb",
        "net/core/skbuff.c:sock_queue_err_skb",
        "net/core/skbuff.c:__msg_zerocopy_callback",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_set_err",
        "net/netlink/af_netlink.c:netlink_overrun",
        "net/ipv4/tcp.c:tcp_abort",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_input.c:tcp_reset",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/raw.c:raw_abort",
        "net/ipv4/raw.c:raw_icmp_error",
        "net/ipv4/udp.c:udp_abort",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/ping.c:ping_err",
        "net/unix/af_unix.c:unix_dgram_disconnected",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_do_bind",
        "net/xdp/xsk.c:xsk_notifier",
        "net/mptcp/protocol.c:mptcp_disconnect",
        "net/mptcp/subflow.c:__mptcp_error_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591353616,
      "name": "sk_error_report",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void sk_error_report(struct sock * sk)
```

```json
{
  "name": "sk_error_report",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593108048,
      "name": "sk_error_report",
      "external": true,
      "loc": "net/core/sock.c:343",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_dequeue_err_skb",
        "net/core/skbuff.c:sock_queue_err_skb",
        "net/core/skbuff.c:__msg_zerocopy_callback",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_set_err",
        "net/netlink/af_netlink.c:netlink_overrun",
        "net/ipv4/tcp.c:tcp_abort",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_input.c:tcp_reset",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/raw.c:raw_abort",
        "net/ipv4/raw.c:raw_icmp_error",
        "net/ipv4/udp.c:udp_abort",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/ping.c:ping_err",
        "net/unix/af_unix.c:unix_dgram_disconnected",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_do_bind",
        "net/xdp/xsk.c:xsk_notifier",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/subflow.c:__mptcp_error_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593108048,
      "name": "sk_error_report",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void sk_error_report(struct sock * sk)
```

```json
{
  "name": "sk_error_report",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593560816,
      "name": "sk_error_report",
      "external": true,
      "loc": "net/core/sock.c:347",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_dequeue_err_skb",
        "net/core/skbuff.c:sock_queue_err_skb",
        "net/core/skbuff.c:__msg_zerocopy_callback",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_set_err",
        "net/netlink/af_netlink.c:netlink_overrun",
        "net/ipv4/tcp.c:tcp_abort",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_input.c:tcp_reset",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/raw.c:raw_abort",
        "net/ipv4/raw.c:raw_icmp_error",
        "net/ipv4/udp.c:udp_abort",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/ping.c:ping_err",
        "net/unix/af_unix.c:unix_dgram_disconnected",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_do_bind",
        "net/xdp/xsk.c:xsk_notifier",
        "net/mptcp/protocol.c:mptcp_disconnect",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/subflow.c:__mptcp_error_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593560816,
      "name": "sk_error_report",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void sk_error_report(struct sock * sk)
```

```json
{
  "name": "sk_error_report",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594333536,
      "name": "sk_error_report",
      "external": true,
      "loc": "net/core/sock.c:344",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:sock_dequeue_err_skb",
        "net/core/skbuff.c:sock_queue_err_skb",
        "net/core/skbuff.c:__msg_zerocopy_callback",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_set_err",
        "net/netlink/af_netlink.c:netlink_overrun",
        "net/ipv4/tcp.c:tcp_abort",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_input.c:tcp_reset",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/raw.c:raw_abort",
        "net/ipv4/raw.c:raw_icmp_error",
        "net/ipv4/udp.c:udp_abort",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/ping.c:ping_err",
        "net/unix/af_unix.c:unix_dgram_disconnected",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_do_bind",
        "net/xdp/xsk.c:xsk_notifier",
        "net/mptcp/protocol.c:mptcp_disconnect",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/protocol.c:__mptcp_error_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594333536,
      "name": "sk_error_report",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void sk_error_report(struct sock * sk)
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
