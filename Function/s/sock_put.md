# Function: <code>sock_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void sock_put(struct sock * sk)
```

```json
{
  "name": "sock_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582597225,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1624",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585069384,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1624",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586200380,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1624",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_receive_skb",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:sk_common_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586204845,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1624",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586210907,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1624",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586493909,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1624",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:deferred_put_nlk_sk",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_skb_destructor",
        "net/netlink/af_netlink.c:netlink_getsockbyportid",
        "net/netlink/af_netlink.c:__netlink_alloc_skb",
        "net/netlink/af_netlink.c:__netlink_alloc_skb",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_detachskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586522972,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1624",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586577538,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1624",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586588482,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1624",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586597051,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1624",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586620416,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1624",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586635934,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1624",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586683493,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1624",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586687552,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1624",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071586706139,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1624",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_child_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586721290,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1624",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586746314,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1624",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv4/udp.c:__udp4_lib_lookup",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:flush_stack",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:udp_v4_early_demux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586852766,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1624",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/ping.c:ping_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586885944,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1624",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586962720,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1624",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_getname",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ],
      "caller_func": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    },
    {
      "addr": 18446744071587089911,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1624",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587117390,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1624",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:flush_stack",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587165152,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1624",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:reqsk_put",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    },
    {
      "addr": 18446744071587231719,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1624",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587242217,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1624",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587256997,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1624",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586687552,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586962720,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071587165152,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void sock_put(struct sock * sk)
```

```json
{
  "name": "sock_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582840906,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1579",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585457700,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1579",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586622414,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1579",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:__sk_receive_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586625684,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1579",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586637039,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1579",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586950450,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1579",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:deferred_put_nlk_sk",
        "net/netlink/af_netlink.c:netlink_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586965628,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1579",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587020594,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1579",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587030495,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1579",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587041845,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1579",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587065452,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1579",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587086982,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1579",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587130420,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1579",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587148182,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1579",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071587153883,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1579",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_child_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587168919,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1579",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587198017,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1579",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587307118,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1579",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587335677,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1579",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587419367,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1579",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_getname",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect"
      ]
    },
    {
      "addr": 18446744071587540375,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1579",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587630869,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1579",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:reqsk_put"
      ]
    },
    {
      "addr": 18446744071587688794,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1579",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587718761,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1579",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587134912,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071587409040,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071587620912,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void sock_put(struct sock * sk)
```

```json
{
  "name": "sock_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580111786,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1635",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:auditd_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582936874,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1635",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585661748,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1635",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586806956,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1635",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:__sk_receive_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586810212,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1635",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586822536,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1635",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587145426,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1635",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587160396,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1635",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587216418,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1635",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587226607,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1635",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587238133,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1635",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587262092,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1635",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587284761,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1635",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587328884,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1635",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587347174,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1635",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071587352779,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1635",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_child_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587368138,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1635",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587398499,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1635",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587509118,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1635",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587538525,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1635",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587622855,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1635",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_getname",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect"
      ]
    },
    {
      "addr": 18446744071587744823,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1635",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587835461,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1635",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:reqsk_put"
      ]
    },
    {
      "addr": 18446744071587897541,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1635",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587933156,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1635",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587333328,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071587612432,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071587826032,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void sock_put(struct sock * sk)
```

```json
{
  "name": "sock_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582989619,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1639",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585748879,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1639",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586928748,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1639",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:__sk_receive_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586934596,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1639",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586959569,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1639",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587276016,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1639",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587291740,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1639",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587348434,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1639",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587358663,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1639",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587368545,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1639",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587394929,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1639",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587415585,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1639",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587460892,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1639",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587479939,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1639",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071587485927,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1639",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_child_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587500807,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1639",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587534593,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1639",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587646327,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1639",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587684339,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1639",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587770967,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1639",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_getname",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect"
      ]
    },
    {
      "addr": 18446744071587899203,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1639",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587933143,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1639",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587992593,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1639",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:reqsk_put"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    },
    {
      "addr": 18446744071588054868,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1639",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588091522,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1639",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587465680,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071587761408,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071587983200,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void sock_put(struct sock * sk)
```

```json
{
  "name": "sock_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580617672,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1653",
      "file": "kernel/bpf/sockmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/sockmap.c:smap_gc_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583153945,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1653",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586188432,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1653",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587421493,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1653",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:__sk_receive_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587427648,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1653",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587445389,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1653",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:sock_zerocopy_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587788672,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1653",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587813228,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1653",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587868434,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1653",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587879329,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1653",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587889929,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1653",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587914636,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1653",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587935487,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1653",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587982924,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1653",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588001942,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1653",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071588007927,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1653",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_child_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588023012,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1653",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588057379,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1653",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588170967,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1653",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588211059,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1653",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588301884,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1653",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_getname",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect"
      ]
    },
    {
      "addr": 18446744071588434093,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1653",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588468229,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1653",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588529014,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1653",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:reqsk_put"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    },
    {
      "addr": 18446744071588592927,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1653",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588636123,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1653",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587987744,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071588290192,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071588519312,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void sock_put(struct sock * sk)
```

```json
{
  "name": "sock_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580725993,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1664",
      "file": "kernel/bpf/xskmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/xskmap.c:xsk_map_delete_elem",
        "kernel/bpf/xskmap.c:xsk_map_update_elem",
        "kernel/bpf/xskmap.c:xsk_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580745978,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1664",
      "file": "kernel/bpf/sockmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/sockmap.c:smap_gc_work",
        "kernel/bpf/sockmap.c:smap_gc_work",
        "kernel/bpf/sockmap.c:bpf_exec_tx_verdict",
        "kernel/bpf/sockmap.c:bpf_exec_tx_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583315520,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1664",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583359440,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1664",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586433977,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1664",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587725574,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1664",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:__sk_receive_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587731996,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1664",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587749644,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1664",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:sock_zerocopy_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588130386,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1664",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588156268,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1664",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588213842,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1664",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588222970,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1664",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588239492,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1664",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588262909,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1664",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588284719,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1664",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588329902,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1664",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_pace_kick"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588334308,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1664",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588356611,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1664",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071588359768,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1664",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_child_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588373892,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1664",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588409955,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1664",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588525582,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1664",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588567534,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1664",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588651031,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1664",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_getname",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    },
    {
      "addr": 18446744071588795388,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1664",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588831162,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1664",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588893142,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1664",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    },
    {
      "addr": 18446744071588958075,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1664",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589009946,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1664",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589117994,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1664",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588338656,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071588645296,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071588880448,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void sock_put(struct sock * sk)
```

```json
{
  "name": "sock_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580806131,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1710",
      "file": "kernel/bpf/xskmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/xskmap.c:xsk_map_delete_elem",
        "kernel/bpf/xskmap.c:xsk_map_update_elem",
        "kernel/bpf/xskmap.c:xsk_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583435051,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1710",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583478195,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1710",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586579849,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1710",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587857896,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1710",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:__sk_receive_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587866220,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1710",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587883740,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1710",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:sock_zerocopy_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588175241,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1710",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588312914,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1710",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588339452,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1710",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588399106,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1710",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588410202,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1710",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588424644,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1710",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588451145,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1710",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588473355,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1710",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588519038,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1710",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_pace_kick"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588523556,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1710",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588547040,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1710",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071588550165,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1710",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_child_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588564260,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1710",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588601553,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1710",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588721406,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1710",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588765018,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1710",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588770979,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1710",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588866935,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1710",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_getname",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589016268,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1710",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589054596,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1710",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589116604,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1710",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    },
    {
      "addr": 18446744071589182034,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1710",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589236220,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1710",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589352030,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1710",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588528080,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071589103792,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void sock_put(struct sock * sk)
```

```json
{
  "name": "sock_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580894543,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1722",
      "file": "kernel/bpf/xskmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/xskmap.c:xsk_map_delete_elem",
        "kernel/bpf/xskmap.c:xsk_map_update_elem",
        "kernel/bpf/xskmap.c:xsk_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583618667,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1722",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583662515,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1722",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586831925,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1722",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588162466,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1722",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:__sk_receive_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588171085,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1722",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588188998,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1722",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:sock_zerocopy_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588501239,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1722",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588624209,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1722",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588710916,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1722",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588739436,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1722",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588801379,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1722",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588813983,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1722",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588828089,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1722",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588856448,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1722",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588880361,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1722",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588929358,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1722",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_pace_kick"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588934052,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1722",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588958041,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1722",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071588961292,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1722",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_child_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588975621,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1722",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589013190,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1722",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589142476,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1722",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589198028,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1722",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589203928,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1722",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589307899,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1722",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_getname",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    },
    {
      "addr": 18446744071589468525,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1722",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589508043,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1722",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589569912,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1722",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    },
    {
      "addr": 18446744071589635828,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1722",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589695805,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1722",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589808288,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1722",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588938752,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071589301776,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071589554848,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void sock_put(struct sock * sk)
```

```json
{
  "name": "sock_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583724843,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583768803,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586977013,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588367746,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:__sk_receive_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588376285,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588394150,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:sock_zerocopy_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588709559,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588846321,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588934820,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588963404,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589024979,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589037295,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589051337,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589080016,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589105090,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589153294,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_pace_kick"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589158228,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589182553,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071589185996,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_child_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589200024,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589237862,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589366588,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589423400,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589429264,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589532283,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_getname",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    },
    {
      "addr": 18446744071589692381,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589732139,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589794073,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    },
    {
      "addr": 18446744071589860040,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589917261,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590032099,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589162944,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071589526112,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071589779024,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void sock_put(struct sock * sk)
```

```json
{
  "name": "sock_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584108953,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1782",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584158912,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1782",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587805509,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1782",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589227803,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1782",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:__sk_receive_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589238915,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1782",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589257976,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1782",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:sock_zerocopy_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589509664,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1782",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_select_reuseport"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589576428,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1782",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589652118,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1782",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589728726,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1782",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589824639,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1782",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589918300,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1782",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589988264,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1782",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589998793,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1782",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590012547,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1782",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:reqsk_queue_unlink",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590044008,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1782",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590069837,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1782",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590122414,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1782",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_pace_kick"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590126127,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1782",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590153728,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1782",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071590156960,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1782",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_child_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590171318,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1782",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_queue_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590213104,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1782",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590347646,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1782",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590410575,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1782",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590415779,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1782",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590478760,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1782",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:__xfrm_state_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590529842,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1782",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_getname",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    },
    {
      "addr": 18446744071590709421,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1782",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590751686,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1782",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590816189,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1782",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    },
    {
      "addr": 18446744071590887269,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1782",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590950456,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1782",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591065369,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1782",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591083934,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1782",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591094866,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1782",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_ulp_release",
        "net/mptcp/subflow.c:subflow_drop_ctx",
        "net/mptcp/subflow.c:subflow_req_destructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591111012,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1782",
      "file": "net/mptcp/pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm.c:mptcp_pm_close",
        "net/mptcp/pm.c:pm_worker"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590140224,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071590526656,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071590806496,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void sock_put(struct sock * sk)
```

```json
{
  "name": "sock_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584223319,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584277264,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587863509,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589225803,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:__sk_receive_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589238307,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589257112,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:sock_zerocopy_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589515184,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_select_reuseport"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589593047,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589676667,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589765154,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589862276,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589959244,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590026264,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590041081,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590055123,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:reqsk_queue_unlink",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590086205,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590113154,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590170142,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_pace_kick"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590173791,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590202784,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071590205936,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_child_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590220486,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_queue_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590263872,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590400478,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590468885,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590474947,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590538536,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:__xfrm_state_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590591426,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_getname",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    },
    {
      "addr": 18446744071590771565,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590810993,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590876299,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    },
    {
      "addr": 18446744071590948758,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591011842,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591126528,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591159004,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:__mptcp_destroy_sock",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/protocol.c:mptcp_timeout_timer",
        "net/mptcp/protocol.c:mptcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591171472,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_ulp_release",
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/subflow.c:subflow_drop_ctx",
        "net/mptcp/subflow.c:mptcp_subflow_reset",
        "net/mptcp/subflow.c:subflow_req_destructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591189208,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "net/mptcp/token.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/token.c:mptcp_token_iter_next",
        "net/mptcp/token.c:mptcp_token_get_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591200568,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591204205,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1794",
      "file": "net/mptcp/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590188464,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071590586544,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071590865840,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void sock_put(struct sock * sk)
```

```json
{
  "name": "sock_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584248598,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584302639,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587742597,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589117815,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:__sk_receive_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589132099,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589164889,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:__msg_zerocopy_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589412864,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_select_reuseport"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589652588,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589659799,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589668126,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589768300,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589874012,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589940712,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589955273,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589969279,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590000957,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590032310,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590084590,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_pace_kick"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590088655,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590116935,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071590120015,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_child_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590135602,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590178352,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590316539,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590394652,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590400160,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590463816,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:__xfrm_state_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590516483,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_getname",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    },
    {
      "addr": 18446744071590698573,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590738033,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590805460,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    },
    {
      "addr": 18446744071590878713,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590942065,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591056832,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591103165,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_napi_poll",
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:__mptcp_destroy_sock",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/protocol.c:mptcp_timeout_timer",
        "net/mptcp/protocol.c:mptcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591108104,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_ulp_release",
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/subflow.c:subflow_drop_ctx",
        "net/mptcp/subflow.c:mptcp_subflow_reset",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/subflow.c:subflow_req_destructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591126607,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "net/mptcp/token.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/token.c:mptcp_token_iter_next",
        "net/mptcp/token.c:mptcp_token_get_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591145577,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_addrs_list",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591153317,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1810",
      "file": "net/mptcp/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590102432,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071590511600,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071590794736,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void sock_put(struct sock * sk)
```

```json
{
  "name": "sock_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584634278,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1850",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584689071,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1850",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588337887,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1850",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589836247,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1850",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:__sk_receive_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589851779,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1850",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589879705,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1850",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:msg_zerocopy_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590174665,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1850",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_select_reuseport"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590400540,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1850",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590416535,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1850",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590426151,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1850",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590527610,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1850",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590707784,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1850",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590722473,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1850",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590737026,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1850",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance",
        "net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance",
        "net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_reqsk_clone"
      ]
    },
    {
      "addr": 18446744071590771437,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1850",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590802128,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1850",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590859182,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1850",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_pace_kick"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590863823,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1850",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590878526,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1850",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_stop",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_next",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_realloc_batch",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071590896655,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1850",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_child_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590915636,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1850",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590959116,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1850",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591102568,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1850",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591189961,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1850",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591196975,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1850",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591266681,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1850",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:__xfrm_state_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591323836,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1850",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_getname",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    },
    {
      "addr": 18446744071591514461,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1850",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591554673,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1850",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591623803,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1850",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    },
    {
      "addr": 18446744071591709361,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1850",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591777921,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1850",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591899464,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1850",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591947134,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1850",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_napi_poll",
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:__mptcp_destroy_sock",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/protocol.c:mptcp_timeout_timer",
        "net/mptcp/protocol.c:mptcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591952536,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1850",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_ulp_release",
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/subflow.c:subflow_drop_ctx",
        "net/mptcp/subflow.c:mptcp_subflow_reset",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/subflow.c:subflow_req_destructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591974495,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1850",
      "file": "net/mptcp/token.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/token.c:mptcp_token_iter_next",
        "net/mptcp/token.c:mptcp_token_get_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591996221,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1850",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_addrs_list",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590734528,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071590876864,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071591318256,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071591608720,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void sock_put(struct sock * sk)
```

```json
{
  "name": "sock_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585284398,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585352088,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589731421,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591362247,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:__sk_receive_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591376185,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591397423,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:__msg_zerocopy_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591738826,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_select_reuseport"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592006911,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592014054,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592025147,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592139682,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592339271,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592351390,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592367117,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance",
        "net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance",
        "net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_reqsk_clone"
      ]
    },
    {
      "addr": 18446744071592404380,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592437981,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592495518,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_pace_kick"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592500129,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592515546,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_stop",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_next",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_realloc_batch",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071592534925,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_child_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592555578,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592601960,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592749823,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_unhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592849501,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592857292,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592932516,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:__xfrm_state_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592991514,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:bpf_iter_unix_seq_stop",
        "net/unix/af_unix.c:bpf_iter_unix_seq_next",
        "net/unix/af_unix.c:bpf_iter_unix_realloc_batch",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_getname",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    },
    {
      "addr": 18446744071593199932,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593244413,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593316478,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    },
    {
      "addr": 18446744071593409202,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593481228,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593619114,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593673513,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_napi_poll",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:__mptcp_destroy_sock",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/protocol.c:mptcp_timeout_timer",
        "net/mptcp/protocol.c:mptcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593680120,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_ulp_release",
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/subflow.c:subflow_drop_ctx",
        "net/mptcp/subflow.c:mptcp_subflow_reset",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/subflow.c:subflow_req_destructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593703547,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "net/mptcp/token.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/token.c:mptcp_token_iter_next",
        "net/mptcp/token.c:mptcp_token_get_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593728507,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593746592,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "net/mptcp/pm_userspace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593753181,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1956",
      "file": "net/mctp/af_mctp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mctp/af_mctp.c:mctp_pf_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592364352,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071592515712,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071592987824,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071593302192,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void sock_put(struct sock * sk)
```

```json
{
  "name": "sock_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586029432,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586093279,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591356538,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_close",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593116771,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:__sk_receive_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593136793,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593162415,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:__msg_zerocopy_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593513180,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_select_reuseport"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593810751,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593829174,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593841163,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593963906,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594174039,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594190878,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594214909,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance",
        "net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance",
        "net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_reqsk_clone"
      ]
    },
    {
      "addr": 18446744071594252252,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594291949,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594350974,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_pace_kick"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594355953,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594373274,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_stop",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_next",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_realloc_batch",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071594393149,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_child_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594415018,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594465942,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594621391,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_unhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594726605,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594734663,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594814484,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:__xfrm_state_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594880106,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:bpf_iter_unix_seq_stop",
        "net/unix/af_unix.c:bpf_iter_unix_seq_next",
        "net/unix/af_unix.c:bpf_iter_unix_realloc_batch",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_getname",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    },
    {
      "addr": 18446744071595096284,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595145305,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595221356,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    },
    {
      "addr": 18446744071595319602,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595392396,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595550842,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595605513,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_napi_poll",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:__mptcp_destroy_sock",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/protocol.c:mptcp_timeout_timer",
        "net/mptcp/protocol.c:mptcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595612872,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_ulp_release",
        "net/mptcp/subflow.c:mptcp_subflow_queue_clean",
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/subflow.c:subflow_drop_ctx",
        "net/mptcp/subflow.c:mptcp_subflow_reset",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/subflow.c:subflow_req_destructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595637323,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "net/mptcp/token.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/token.c:mptcp_token_iter_next",
        "net/mptcp/token.c:mptcp_token_get_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595663424,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595683264,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "net/mptcp/pm_userspace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595691192,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "net/mctp/af_mctp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mctp/af_mctp.c:mctp_pf_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595701449,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1993",
      "file": "net/mctp/route.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594211392,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071594373456,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071594877472,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071595206720,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void sock_put(struct sock * sk)
```

```json
{
  "name": "sock_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586266248,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586328779,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591718314,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_close",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593569459,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:__sk_receive_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593589609,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593629515,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:__msg_zerocopy_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593973708,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_select_reuseport"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594185048,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594203718,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594215700,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594339514,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594561111,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594577982,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594602109,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance",
        "net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance",
        "net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_reqsk_clone"
      ]
    },
    {
      "addr": 18446744071594638956,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594676593,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594738894,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_pace_kick"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594743841,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594778807,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071594782257,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_child_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594804366,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594835413,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:bpf_iter_udp_realloc_batch",
        "net/ipv4/udp.c:bpf_iter_udp_seq_stop",
        "net/ipv4/udp.c:bpf_iter_udp_seq_next",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595118685,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595127029,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595206196,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:__xfrm_state_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595272474,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:bpf_iter_unix_seq_stop",
        "net/unix/af_unix.c:bpf_iter_unix_seq_next",
        "net/unix/af_unix.c:bpf_iter_unix_realloc_batch",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_getname",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    },
    {
      "addr": 18446744071595490108,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595540276,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595617241,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    },
    {
      "addr": 18446744071595714634,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595789616,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596059018,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596114393,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_napi_poll",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:__mptcp_destroy_sock",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/protocol.c:mptcp_timeout_timer",
        "net/mptcp/protocol.c:mptcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596121533,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_ulp_release",
        "net/mptcp/subflow.c:mptcp_subflow_queue_clean",
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/subflow.c:mptcp_subflow_drop_ctx",
        "net/mptcp/subflow.c:mptcp_subflow_reset",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/subflow.c:subflow_req_destructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596145619,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "net/mptcp/token.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/token.c:mptcp_token_iter_next",
        "net/mptcp/token.c:mptcp_token_get_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596174649,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596194224,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "net/mptcp/pm_userspace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596201256,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "net/mctp/af_mctp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mctp/af_mctp.c:mctp_pf_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596212969,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "net/mctp/route.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596226627,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1980",
      "file": "net/handshake/request.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/handshake/request.c:handshake_req_cancel",
        "net/handshake/request.c:handshake_complete"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594598384,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071594761744,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071595269808,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071595603216,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void sock_put(struct sock * sk)
```

```json
{
  "name": "sock_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586519835,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586585452,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592462026,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_close",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594342051,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:__sk_receive_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594362393,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594404763,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:__msg_zerocopy_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594758156,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_select_reuseport"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594981432,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595001094,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595013076,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595138867,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595363751,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595381662,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595405725,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance",
        "net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance",
        "net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_reqsk_clone"
      ]
    },
    {
      "addr": 18446744071595442284,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595481608,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595543998,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_pace_kick"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595549598,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595589803,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071595593601,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_child_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595615566,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595645589,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:bpf_iter_udp_realloc_batch",
        "net/ipv4/udp.c:bpf_iter_udp_seq_stop",
        "net/ipv4/udp.c:bpf_iter_udp_seq_next",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595931512,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595943743,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596046740,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:__xfrm_state_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596113162,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:bpf_iter_unix_seq_stop",
        "net/unix/af_unix.c:bpf_iter_unix_seq_next",
        "net/unix/af_unix.c:bpf_iter_unix_realloc_batch",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_getname",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    },
    {
      "addr": 18446744071596333388,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596383226,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596464456,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    },
    {
      "addr": 18446744071596562550,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596640117,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596926395,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596987280,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_napi_poll",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:__mptcp_destroy_sock",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/protocol.c:mptcp_tout_timer",
        "net/mptcp/protocol.c:mptcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596995101,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_ulp_release",
        "net/mptcp/subflow.c:mptcp_subflow_queue_clean",
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/subflow.c:mptcp_subflow_drop_ctx",
        "net/mptcp/subflow.c:mptcp_subflow_reset",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/subflow.c:subflow_req_destructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597019331,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "net/mptcp/token.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/token.c:mptcp_token_iter_next",
        "net/mptcp/token.c:mptcp_token_get_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597049065,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_flush_addrs_doit",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_doit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597070256,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "net/mptcp/pm_userspace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags",
        "net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_destroy_doit",
        "net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_create_doit",
        "net/mptcp/pm_userspace.c:mptcp_pm_nl_remove_doit",
        "net/mptcp/pm_userspace.c:mptcp_pm_nl_announce_doit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597079016,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "net/mctp/af_mctp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mctp/af_mctp.c:mctp_pf_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597090857,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "net/mctp/route.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071597105395,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1958",
      "file": "net/handshake/request.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/handshake/request.c:handshake_req_cancel",
        "net/handshake/request.c:handshake_complete"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595401632,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071595567552,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071596109456,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071596445008,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
void sock_put(struct sock * sk)
```

```json
{
  "name": "sock_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495523024,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495569164,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499968088,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501877428,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:__sk_receive_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501888160,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501909876,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:sock_zerocopy_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502272972,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502417552,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502530064,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502566068,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502631480,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502647228,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502664088,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502696420,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502716648,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502769132,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_pace_kick"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502773640,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502800232,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446603336502802740,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_child_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502819868,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502865200,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503008644,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503076156,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503081688,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503200888,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_getname",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503385400,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503422748,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503498080,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    },
    {
      "addr": 18446603336503577128,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503641200,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503784004,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502779832,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446603336503485736,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline ❓</summary>

```c
void sock_put(struct sock * sk)
```

```json
{
  "name": "sock_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228890180,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream"
      ],
      "caller_func": []
    },
    {
      "addr": 3228931944,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 3232512284,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 3234641460,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:__sk_receive_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 3234650132,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 3234671040,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:sock_zerocopy_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 3235014264,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 3235154988,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get"
      ],
      "caller_func": []
    },
    {
      "addr": 3235240192,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 3235272384,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 3235338300,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 3235351272,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235365248,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 3235397752,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_close"
      ],
      "caller_func": []
    },
    {
      "addr": 3235414792,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 3235473760,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_pace_kick"
      ],
      "caller_func": []
    },
    {
      "addr": 3235478532,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 3235503772,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 3235506688,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_child_process"
      ],
      "caller_func": []
    },
    {
      "addr": 3235521772,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 3235561376,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 3235697856,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash"
      ],
      "caller_func": []
    },
    {
      "addr": 3235759160,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 3235764684,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 3235875632,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_getname",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 3236045700,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control"
      ],
      "caller_func": []
    },
    {
      "addr": 3236085756,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 3236151428,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    },
    {
      "addr": 3236224292,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 3236283516,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 3236402044,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235483840,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 3236140116,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
void sock_put(struct sock * sk)
```

```json
{
  "name": "sock_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289591496,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289663328,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293304180,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295284188,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:__sk_receive_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295295188,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295323280,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:sock_zerocopy_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295769856,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295969796,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296106072,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296147960,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296230344,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296247732,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055296266544,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296307644,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_close"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296340804,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296401680,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_pace_kick"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296408384,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296441276,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 13835058055296444952,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_child_process"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296467412,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296521612,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296701228,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296780908,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296789916,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296936860,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_getname",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    },
    {
      "addr": 13835058055297154848,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297203472,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297289256,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    },
    {
      "addr": 13835058055297380864,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297466180,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297627240,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296415456,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 13835058055296925808,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 13835058055297272640,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "sock_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274701228,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274737744,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277047880,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278199474,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:__sk_receive_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278205144,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278223086,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:sock_zerocopy_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278506940,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278625098,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278699666,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_sendskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278724310,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278778632,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278787950,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278802134,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop_and_put",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278825854,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278848514,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278890928,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_pace_kick"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278895534,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278917416,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278920314,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_child_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278934118,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278968422,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279081862,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279132344,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279136720,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279236560,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_getname",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279382248,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279416432,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279472136,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:reqsk_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279533460,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279586308,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279692084,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_release"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void sock_put(struct sock * sk)
```

```json
{
  "name": "sock_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583693579,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583737539,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586734021,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587974530,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:__sk_receive_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587983069,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588000934,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:sock_zerocopy_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588316295,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588452705,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588541204,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588569788,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588631363,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588643679,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588657721,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588686400,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588711474,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588759678,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_pace_kick"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588764612,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588788937,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071588792380,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_child_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588806408,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588844246,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588972764,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589027768,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589033632,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589136651,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_getname",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    },
    {
      "addr": 18446744071589296749,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589336507,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589398441,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    },
    {
      "addr": 18446744071589464408,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589521629,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589635699,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588769328,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071589130480,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071589383392,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void sock_put(struct sock * sk)
```

```json
{
  "name": "sock_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583630635,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583674595,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586601237,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587687634,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:__sk_receive_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587696173,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587714022,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:sock_zerocopy_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588029079,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588165393,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588253204,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588281772,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588343347,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588355663,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588369705,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588398384,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588423458,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588471614,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_pace_kick"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588476548,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588500873,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071588504316,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_child_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588518344,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588556182,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588684700,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588752808,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588758672,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588861643,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_getname",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    },
    {
      "addr": 18446744071589021741,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589061499,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589123433,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    },
    {
      "addr": 18446744071589189400,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589247693,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589360227,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588481264,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071588855472,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071589108384,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void sock_put(struct sock * sk)
```

```json
{
  "name": "sock_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583677355,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583721315,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586931573,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588306306,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:__sk_receive_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588314845,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588332710,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:sock_zerocopy_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588648119,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588784881,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588873380,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588901964,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589067539,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589079855,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589093897,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589122576,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589147650,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589195854,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_pace_kick"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589200788,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589225113,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071589228556,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_child_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589242584,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589280422,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589409148,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589464152,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589470496,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589573515,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_getname",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    },
    {
      "addr": 18446744071589733613,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589773371,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589835305,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    },
    {
      "addr": 18446744071589901272,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589962893,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590077731,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589205504,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071589567344,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071589820256,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void sock_put(struct sock * sk)
```

```json
{
  "name": "sock_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583777030,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583821889,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587051269,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588441522,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:__sk_receive_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588450077,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588468182,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:sock_zerocopy_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588787695,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588925473,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589014884,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589044524,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589106915,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589119279,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589133846,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589162398,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589187496,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589235950,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_pace_kick"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589240914,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589265241,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071589268698,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_child_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589283140,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589321830,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589452620,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589510492,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589516464,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589628761,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_getname",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    },
    {
      "addr": 18446744071589784045,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589824075,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589886569,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    },
    {
      "addr": 18446744071589953516,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590015439,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590127171,
      "name": "sock_put",
      "external": false,
      "loc": "include/net/sock.h:1732",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589245744,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071589616288,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071589871312,
      "name": "sock_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void sock_put(struct sock * sk)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
