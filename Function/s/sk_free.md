# Function: <code>sk_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void sk_free(struct sock * sk)
```

```json
{
  "name": "sk_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586200272,
      "name": "sk_free",
      "external": true,
      "loc": "net/core/sock.c:1478",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "net/core/sock.c:sk_receive_skb",
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:sk_common_release",
        "net/core/request_sock.c:reqsk_fastopen_remove",
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
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
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs",
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu",
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tasklet_func",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_minisocks.c:tcp_child_process",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv4/udp.c:__udp4_lib_lookup",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:flush_stack",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
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
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:flush_stack",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586200272,
      "name": "sk_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void sk_free(struct sock * sk)
```

```json
{
  "name": "sk_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586620784,
      "name": "sk_free",
      "external": true,
      "loc": "net/core/sock.c:1483",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/request_sock.c:reqsk_fastopen_remove",
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:deferred_put_nlk_sk",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs",
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tasklet_func",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_child_process",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
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
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586620784,
      "name": "sk_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void sk_free(struct sock * sk)
```

```json
{
  "name": "sk_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586805344,
      "name": "sk_free",
      "external": true,
      "loc": "net/core/sock.c:1476",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:auditd_reset",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/request_sock.c:reqsk_fastopen_remove",
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/netlink/af_netlink.c:netlink_sock_destruct_work",
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs",
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tasklet_func",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_child_process",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
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
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586805344,
      "name": "sk_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void sk_free(struct sock * sk)
```

```json
{
  "name": "sk_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586927136,
      "name": "sk_free",
      "external": true,
      "loc": "net/core/sock.c:1598",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:sk_free_unlock_clone",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/request_sock.c:reqsk_fastopen_remove",
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/netlink/af_netlink.c:netlink_sock_destruct_work",
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs",
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tasklet_func",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_child_process",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
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
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:reqsk_put",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586927136,
      "name": "sk_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void sk_free(struct sock * sk)
```

```json
{
  "name": "sk_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587419776,
      "name": "sk_free",
      "external": true,
      "loc": "net/core/sock.c:1604",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/sockmap.c:smap_gc_work",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:sk_free_unlock_clone",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/request_sock.c:reqsk_fastopen_remove",
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:sock_zerocopy_callback",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:deferred_put_nlk_sk",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/netlink/af_netlink.c:netlink_sock_destruct_work",
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs",
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tasklet_func",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_child_process",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
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
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:reqsk_put",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587419776,
      "name": "sk_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void sk_free(struct sock * sk)
```

```json
{
  "name": "sk_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587723840,
      "name": "sk_free",
      "external": true,
      "loc": "net/core/sock.c:1622",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:xsk_map_delete_elem",
        "kernel/bpf/xskmap.c:xsk_map_update_elem",
        "kernel/bpf/xskmap.c:xsk_map_free",
        "kernel/bpf/sockmap.c:smap_gc_work",
        "kernel/bpf/sockmap.c:smap_gc_work",
        "kernel/bpf/sockmap.c:bpf_exec_tx_verdict",
        "kernel/bpf/sockmap.c:bpf_exec_tx_verdict",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "drivers/net/tun.c:tun_chr_open",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/request_sock.c:reqsk_fastopen_remove",
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:sock_zerocopy_callback",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:deferred_put_nlk_sk",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/netlink/af_netlink.c:netlink_sock_destruct_work",
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tasklet_func",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_child_process",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
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
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587723840,
      "name": "sk_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void sk_free(struct sock * sk)
```

```json
{
  "name": "sk_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587856176,
      "name": "sk_free",
      "external": true,
      "loc": "net/core/sock.c:1618",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:xsk_map_delete_elem",
        "kernel/bpf/xskmap.c:xsk_map_update_elem",
        "kernel/bpf/xskmap.c:xsk_map_free",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "drivers/net/tun.c:tun_chr_open",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/request_sock.c:reqsk_fastopen_remove",
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:sock_zerocopy_callback",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:deferred_put_nlk_sk",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/netlink/af_netlink.c:netlink_sock_destruct_work",
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs",
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tasklet_func",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_child_process",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
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
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587856176,
      "name": "sk_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void sk_free(struct sock * sk)
```

```json
{
  "name": "sk_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588160672,
      "name": "sk_free",
      "external": true,
      "loc": "net/core/sock.c:1748",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:xsk_map_delete_elem",
        "kernel/bpf/xskmap.c:xsk_map_update_elem",
        "kernel/bpf/xskmap.c:xsk_map_free",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "drivers/net/tun.c:tun_chr_open",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/request_sock.c:reqsk_fastopen_remove",
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:sock_zerocopy_callback",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:deferred_put_nlk_sk",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/netlink/af_netlink.c:netlink_sock_destruct_work",
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs",
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tasklet_func",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_child_process",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
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
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588160672,
      "name": "sk_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void sk_free(struct sock * sk)
```

```json
{
  "name": "sk_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588365936,
      "name": "sk_free",
      "external": true,
      "loc": "net/core/sock.c:1755",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "drivers/net/tun.c:tun_chr_open",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/request_sock.c:reqsk_fastopen_remove",
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:sock_zerocopy_callback",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:deferred_put_nlk_sk",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/netlink/af_netlink.c:netlink_sock_destruct_work",
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs",
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tasklet_func",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_child_process",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
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
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588365936,
      "name": "sk_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sk_free(struct sock * sk)
```

```json
{
  "name": "sk_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589227843,
      "name": "sk_free",
      "external": true,
      "loc": "net/core/sock.c:1844",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:sk_free_unlock_clone"
      ],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "drivers/net/tun.c:tun_chr_open",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/request_sock.c:reqsk_fastopen_remove",
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:sock_zerocopy_callback",
        "net/core/filter.c:sk_select_reuseport",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/netlink/af_netlink.c:netlink_sock_destruct_work",
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs",
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:reqsk_queue_unlink",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tasklet_func",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_child_process",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_queue_check",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/xfrm/xfrm_state.c:__xfrm_state_delete",
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
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_release",
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_sk_clone",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_retransmit_timer",
        "net/mptcp/subflow.c:subflow_ulp_release",
        "net/mptcp/subflow.c:subflow_drop_ctx",
        "net/mptcp/subflow.c:subflow_req_destructor",
        "net/mptcp/pm.c:mptcp_pm_close",
        "net/mptcp/pm.c:pm_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589225840,
      "name": "sk_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sk_free(struct sock * sk)
```

```json
{
  "name": "sk_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589225843,
      "name": "sk_free",
      "external": true,
      "loc": "net/core/sock.c:1836",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:sk_free_unlock_clone"
      ],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "drivers/net/tun.c:tun_chr_open",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/request_sock.c:reqsk_fastopen_remove",
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:sock_zerocopy_callback",
        "net/core/filter.c:sk_select_reuseport",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/netlink/af_netlink.c:netlink_sock_destruct_work",
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs",
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:reqsk_queue_unlink",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tasklet_func",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_child_process",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_queue_check",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/xfrm/xfrm_state.c:__xfrm_state_delete",
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
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_release",
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:__mptcp_destroy_sock",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/protocol.c:mptcp_timeout_timer",
        "net/mptcp/protocol.c:mptcp_retransmit_timer",
        "net/mptcp/subflow.c:subflow_ulp_release",
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/subflow.c:subflow_drop_ctx",
        "net/mptcp/subflow.c:mptcp_subflow_reset",
        "net/mptcp/subflow.c:subflow_req_destructor",
        "net/mptcp/token.c:mptcp_token_iter_next",
        "net/mptcp/token.c:mptcp_token_get_sock",
        "net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589223824,
      "name": "sk_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sk_free(struct sock * sk)
```

```json
{
  "name": "sk_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589117991,
      "name": "sk_free",
      "external": true,
      "loc": "net/core/sock.c:1868",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:sk_free_unlock_clone"
      ],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "drivers/net/tun.c:tun_chr_open",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/request_sock.c:reqsk_fastopen_remove",
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:__msg_zerocopy_callback",
        "net/core/filter.c:sk_select_reuseport",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/netlink/af_netlink.c:netlink_sock_destruct_work",
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs",
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tasklet_func",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_child_process",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/xfrm/xfrm_state.c:__xfrm_state_delete",
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
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_release",
        "net/mptcp/protocol.c:mptcp_napi_poll",
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:__mptcp_destroy_sock",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/protocol.c:mptcp_timeout_timer",
        "net/mptcp/protocol.c:mptcp_retransmit_timer",
        "net/mptcp/subflow.c:subflow_ulp_release",
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/subflow.c:subflow_drop_ctx",
        "net/mptcp/subflow.c:mptcp_subflow_reset",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/subflow.c:subflow_req_destructor",
        "net/mptcp/token.c:mptcp_token_iter_next",
        "net/mptcp/token.c:mptcp_token_get_sock",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_addrs_list",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr",
        "net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589117616,
      "name": "sk_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void sk_free(struct sock * sk)
```

```json
{
  "name": "sk_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589836423,
      "name": "sk_free",
      "external": true,
      "loc": "net/core/sock.c:1992",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:sk_free_unlock_clone"
      ],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "drivers/net/tun.c:tun_chr_open",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/request_sock.c:reqsk_fastopen_remove",
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:msg_zerocopy_callback",
        "net/core/filter.c:sk_select_reuseport",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:deferred_put_nlk_sk",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/netlink/af_netlink.c:netlink_sock_destruct_work",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu",
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
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tasklet_func",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_stop",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_next",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_realloc_batch",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_child_process",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/xfrm/xfrm_state.c:__xfrm_state_delete",
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
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_release",
        "net/mptcp/protocol.c:mptcp_napi_poll",
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:__mptcp_destroy_sock",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/protocol.c:mptcp_timeout_timer",
        "net/mptcp/protocol.c:mptcp_retransmit_timer",
        "net/mptcp/subflow.c:subflow_ulp_release",
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/subflow.c:subflow_drop_ctx",
        "net/mptcp/subflow.c:mptcp_subflow_reset",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/subflow.c:subflow_req_destructor",
        "net/mptcp/token.c:mptcp_token_iter_next",
        "net/mptcp/token.c:mptcp_token_get_sock",
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
      "addr": 18446744071589836048,
      "name": "sk_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sk_free(struct sock * sk)
```

```json
{
  "name": "sk_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591362295,
      "name": "sk_free",
      "external": true,
      "loc": "net/core/sock.c:2126",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:sk_free_unlock_clone"
      ],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "drivers/net/tun.c:tun_chr_open",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/request_sock.c:reqsk_fastopen_remove",
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:__msg_zerocopy_callback",
        "net/core/filter.c:sk_select_reuseport",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:deferred_put_nlk_sk",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/netlink/af_netlink.c:netlink_sock_destruct_work",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu",
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
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tasklet_func",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_stop",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_next",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_realloc_batch",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_child_process",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/xfrm/xfrm_state.c:__xfrm_state_delete",
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
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_release",
        "net/mptcp/protocol.c:mptcp_napi_poll",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:__mptcp_destroy_sock",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/protocol.c:mptcp_timeout_timer",
        "net/mptcp/protocol.c:mptcp_retransmit_timer",
        "net/mptcp/subflow.c:subflow_ulp_release",
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/subflow.c:subflow_drop_ctx",
        "net/mptcp/subflow.c:mptcp_subflow_reset",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/subflow.c:subflow_req_destructor",
        "net/mptcp/token.c:mptcp_token_iter_next",
        "net/mptcp/token.c:mptcp_token_get_sock",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr",
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce",
        "net/mctp/af_mctp.c:mctp_pf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591359776,
      "name": "sk_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sk_free(struct sock * sk)
```

```json
{
  "name": "sk_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593118981,
      "name": "sk_free",
      "external": true,
      "loc": "net/core/sock.c:2197",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:sk_free_unlock_clone"
      ],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "drivers/net/tun.c:tun_chr_close",
        "drivers/net/tun.c:tun_chr_open",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/request_sock.c:reqsk_fastopen_remove",
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:__msg_zerocopy_callback",
        "net/core/filter.c:sk_select_reuseport",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:deferred_put_nlk_sk",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/netlink/af_netlink.c:netlink_sock_destruct_work",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu",
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
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tasklet_func",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_stop",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_next",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_realloc_batch",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_child_process",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/xfrm/xfrm_state.c:__xfrm_state_delete",
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
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_release",
        "net/mptcp/protocol.c:mptcp_napi_poll",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:__mptcp_destroy_sock",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/protocol.c:mptcp_timeout_timer",
        "net/mptcp/protocol.c:mptcp_retransmit_timer",
        "net/mptcp/subflow.c:subflow_ulp_release",
        "net/mptcp/subflow.c:mptcp_subflow_queue_clean",
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/subflow.c:subflow_drop_ctx",
        "net/mptcp/subflow.c:mptcp_subflow_reset",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/subflow.c:subflow_req_destructor",
        "net/mptcp/token.c:mptcp_token_iter_next",
        "net/mptcp/token.c:mptcp_token_get_sock",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr",
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce",
        "net/mctp/af_mctp.c:mctp_pf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593115936,
      "name": "sk_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sk_free(struct sock * sk)
```

```json
{
  "name": "sk_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593571669,
      "name": "sk_free",
      "external": true,
      "loc": "net/core/sock.c:2255",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:sk_free_unlock_clone"
      ],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "drivers/net/tun.c:tun_chr_close",
        "drivers/net/tun.c:tun_chr_open",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/request_sock.c:reqsk_fastopen_remove",
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:__msg_zerocopy_callback",
        "net/core/filter.c:sk_select_reuseport",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:deferred_put_nlk_sk",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/netlink/af_netlink.c:netlink_sock_destruct_work",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu",
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
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tasklet_func",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_child_process",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/udp.c:bpf_iter_udp_realloc_batch",
        "net/ipv4/udp.c:bpf_iter_udp_seq_stop",
        "net/ipv4/udp.c:bpf_iter_udp_seq_next",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/xfrm/xfrm_state.c:__xfrm_state_delete",
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
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_release",
        "net/mptcp/protocol.c:mptcp_napi_poll",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:__mptcp_destroy_sock",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/protocol.c:mptcp_timeout_timer",
        "net/mptcp/protocol.c:mptcp_retransmit_timer",
        "net/mptcp/subflow.c:subflow_ulp_release",
        "net/mptcp/subflow.c:mptcp_subflow_queue_clean",
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/subflow.c:mptcp_subflow_drop_ctx",
        "net/mptcp/subflow.c:mptcp_subflow_reset",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/subflow.c:subflow_req_destructor",
        "net/mptcp/token.c:mptcp_token_iter_next",
        "net/mptcp/token.c:mptcp_token_get_sock",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr",
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce",
        "net/mctp/af_mctp.c:mctp_pf_create",
        "net/handshake/request.c:handshake_req_cancel",
        "net/handshake/request.c:handshake_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593568608,
      "name": "sk_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sk_free(struct sock * sk)
```

```json
{
  "name": "sk_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594344261,
      "name": "sk_free",
      "external": true,
      "loc": "net/core/sock.c:2235",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:sk_free_unlock_clone"
      ],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "drivers/net/tun.c:tun_chr_close",
        "drivers/net/tun.c:tun_chr_open",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/request_sock.c:reqsk_fastopen_remove",
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:__msg_zerocopy_callback",
        "net/core/filter.c:sk_select_reuseport",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:deferred_put_nlk_sk",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/netlink/af_netlink.c:netlink_sock_destruct_work",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu",
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
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tasklet_func",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_child_process",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/udp.c:bpf_iter_udp_realloc_batch",
        "net/ipv4/udp.c:bpf_iter_udp_seq_stop",
        "net/ipv4/udp.c:bpf_iter_udp_seq_next",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/xfrm/xfrm_state.c:__xfrm_state_delete",
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
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_release",
        "net/mptcp/protocol.c:mptcp_napi_poll",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:__mptcp_destroy_sock",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/protocol.c:mptcp_tout_timer",
        "net/mptcp/protocol.c:mptcp_retransmit_timer",
        "net/mptcp/subflow.c:subflow_ulp_release",
        "net/mptcp/subflow.c:mptcp_subflow_queue_clean",
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/subflow.c:mptcp_subflow_drop_ctx",
        "net/mptcp/subflow.c:mptcp_subflow_reset",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/subflow.c:subflow_req_destructor",
        "net/mptcp/token.c:mptcp_token_iter_next",
        "net/mptcp/token.c:mptcp_token_get_sock",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_flush_addrs_doit",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_doit",
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags",
        "net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_destroy_doit",
        "net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_create_doit",
        "net/mptcp/pm_userspace.c:mptcp_pm_nl_remove_doit",
        "net/mptcp/pm_userspace.c:mptcp_pm_nl_announce_doit",
        "net/mctp/af_mctp.c:mctp_pf_create",
        "net/handshake/request.c:handshake_req_cancel",
        "net/handshake/request.c:handshake_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594341200,
      "name": "sk_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void sk_free(struct sock * sk)
```

```json
{
  "name": "sk_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501875656,
      "name": "sk_free",
      "external": true,
      "loc": "net/core/sock.c:1755",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "drivers/net/tun.c:tun_chr_open",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/request_sock.c:reqsk_fastopen_remove",
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:sock_zerocopy_callback",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/netlink/af_netlink.c:netlink_sock_destruct_work",
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs",
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tasklet_func",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_child_process",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
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
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501875656,
      "name": "sk_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void sk_free(struct sock * sk)
```

```json
{
  "name": "sk_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234639924,
      "name": "sk_free",
      "external": true,
      "loc": "net/core/sock.c:1755",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "drivers/net/tun.c:tun_chr_open",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:sk_free_unlock_clone",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/request_sock.c:reqsk_fastopen_remove",
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:sock_zerocopy_callback",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/netlink/af_netlink.c:netlink_sock_destruct_work",
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs",
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tasklet_func",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_child_process",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
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
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234639924,
      "name": "sk_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void sk_free(struct sock * sk)
```

```json
{
  "name": "sk_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295282224,
      "name": "sk_free",
      "external": true,
      "loc": "net/core/sock.c:1755",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "drivers/net/tun.c:tun_chr_open",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:sk_free_unlock_clone",
        "net/core/sock.c:sk_free_unlock_clone",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/request_sock.c:reqsk_fastopen_remove",
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:sock_zerocopy_callback",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/netlink/af_netlink.c:netlink_sock_destruct_work",
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs",
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tasklet_func",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_child_process",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
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
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295282224,
      "name": "sk_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void sk_free(struct sock * sk)
```

```json
{
  "name": "sk_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278199504,
      "name": "sk_free",
      "external": true,
      "loc": "net/core/sock.c:1755",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:sk_free_unlock_clone",
        "net/core/sock.c:__sk_receive_skb"
      ],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "drivers/net/tun.c:tun_chr_open",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "net/core/request_sock.c:reqsk_fastopen_remove",
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:sock_zerocopy_callback",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_sendskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/netlink/af_netlink.c:netlink_sock_destruct_work",
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs",
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop_and_put",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tasklet_func",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_child_process",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
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
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:reqsk_free",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278197822,
      "name": "sk_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void sk_free(struct sock * sk)
```

```json
{
  "name": "sk_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587972720,
      "name": "sk_free",
      "external": true,
      "loc": "net/core/sock.c:1755",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "drivers/net/tun.c:tun_chr_open",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/request_sock.c:reqsk_fastopen_remove",
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:sock_zerocopy_callback",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:deferred_put_nlk_sk",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/netlink/af_netlink.c:netlink_sock_destruct_work",
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs",
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tasklet_func",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_child_process",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
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
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587972720,
      "name": "sk_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void sk_free(struct sock * sk)
```

```json
{
  "name": "sk_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587685824,
      "name": "sk_free",
      "external": true,
      "loc": "net/core/sock.c:1755",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "drivers/net/tun.c:tun_chr_open",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/request_sock.c:reqsk_fastopen_remove",
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:sock_zerocopy_callback",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:deferred_put_nlk_sk",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/netlink/af_netlink.c:netlink_sock_destruct_work",
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs",
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tasklet_func",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_child_process",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
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
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587685824,
      "name": "sk_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void sk_free(struct sock * sk)
```

```json
{
  "name": "sk_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588304496,
      "name": "sk_free",
      "external": true,
      "loc": "net/core/sock.c:1755",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "drivers/net/tun.c:tun_chr_open",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/request_sock.c:reqsk_fastopen_remove",
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:sock_zerocopy_callback",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:deferred_put_nlk_sk",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/netlink/af_netlink.c:netlink_sock_destruct_work",
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs",
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tasklet_func",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_child_process",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
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
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588304496,
      "name": "sk_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void sk_free(struct sock * sk)
```

```json
{
  "name": "sk_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588439680,
      "name": "sk_free",
      "external": true,
      "loc": "net/core/sock.c:1755",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "drivers/net/tun.c:tun_chr_open",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_efree",
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/request_sock.c:reqsk_fastopen_remove",
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:sock_zerocopy_callback",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_detachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/netlink/af_netlink.c:deferred_put_nlk_sk",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/netlink/af_netlink.c:netlink_sock_destruct_work",
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs",
        "net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tasklet_func",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_child_process",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
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
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_create",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588439680,
      "name": "sk_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
