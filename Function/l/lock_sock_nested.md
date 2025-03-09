# Function: <code>lock_sock_nested</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void lock_sock_nested(struct sock * sk, int subclass)
```

```json
{
  "name": "lock_sock_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586189280,
      "name": "lock_sock_nested",
      "external": true,
      "loc": "net/core/sock.c:2431",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt",
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect",
        "net/socket.c:sock_fasync",
        "net/core/sock.c:sk_wait_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/skbuff.c:skb_socket_splice",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/filter.c:sk_get_filter",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/datagram.c:ip4_datagram_connect",
        "net/ipv4/raw.c:raw_destroy",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendpage",
        "net/ipv4/devinet.c:ip_mc_config",
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_shutdown",
        "net/ipv4/af_inet.c:inet_bind",
        "net/ipv4/af_inet.c:inet_autobind",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:inet_stream_connect",
        "net/ipv4/af_inet.c:inet_accept",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/addrconf.c:ipv6_mc_config",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_destroy_sock",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/raw.c:raw6_destroy",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_connect",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586189280,
      "name": "lock_sock_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void lock_sock_nested(struct sock * sk, int subclass)
```

```json
{
  "name": "lock_sock_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586610016,
      "name": "lock_sock_nested",
      "external": true,
      "loc": "net/core/sock.c:2504",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect",
        "security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:tun_detach_filter",
        "drivers/net/tun.c:tun_attach",
        "net/socket.c:sock_fasync",
        "net/core/sock.c:sk_wait_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/skbuff.c:skb_socket_splice",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/filter.c:sk_get_filter",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/datagram.c:ip4_datagram_connect",
        "net/ipv4/raw.c:raw_destroy",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_sendpage",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/devinet.c:ip_mc_config",
        "net/ipv4/af_inet.c:inet_shutdown",
        "net/ipv4/af_inet.c:inet_accept",
        "net/ipv4/af_inet.c:inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:inet_bind",
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_autobind",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/addrconf.c:ipv6_mc_config",
        "net/ipv6/udp.c:udpv6_destroy_sock",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:raw6_destroy",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_connect",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586610016,
      "name": "lock_sock_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void lock_sock_nested(struct sock * sk, int subclass)
```

```json
{
  "name": "lock_sock_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586794368,
      "name": "lock_sock_nested",
      "external": true,
      "loc": "net/core/sock.c:2531",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect",
        "security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:tun_detach_filter",
        "drivers/net/tun.c:tun_attach",
        "net/socket.c:sock_fasync",
        "net/core/sock.c:sk_wait_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/filter.c:sk_get_filter",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/datagram.c:ip4_datagram_connect",
        "net/ipv4/raw.c:raw_abort",
        "net/ipv4/raw.c:raw_destroy",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_abort",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_disconnect",
        "net/ipv4/udp.c:udp_sendpage",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/devinet.c:ip_mc_config",
        "net/ipv4/af_inet.c:inet_shutdown",
        "net/ipv4/af_inet.c:inet_accept",
        "net/ipv4/af_inet.c:inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:inet_bind",
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_autobind",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/addrconf.c:ipv6_mc_config",
        "net/ipv6/udp.c:udpv6_destroy_sock",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:raw6_destroy",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_connect",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586794368,
      "name": "lock_sock_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void lock_sock_nested(struct sock * sk, int subclass)
```

```json
{
  "name": "lock_sock_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586917744,
      "name": "lock_sock_nested",
      "external": true,
      "loc": "net/core/sock.c:2695",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect",
        "security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:tun_detach_filter",
        "drivers/net/tun.c:tun_attach",
        "net/socket.c:sock_fasync",
        "net/core/sock.c:sk_wait_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/filter.c:sk_get_filter",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/datagram.c:ip4_datagram_connect",
        "net/ipv4/raw.c:raw_abort",
        "net/ipv4/raw.c:raw_destroy",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_abort",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_disconnect",
        "net/ipv4/udp.c:udp_sendpage",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/devinet.c:ip_mc_config",
        "net/ipv4/af_inet.c:inet_shutdown",
        "net/ipv4/af_inet.c:inet_accept",
        "net/ipv4/af_inet.c:inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:inet_bind",
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_autobind",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/addrconf.c:ipv6_mc_config",
        "net/ipv6/udp.c:udpv6_destroy_sock",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:raw6_destroy",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_connect",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_do_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586917744,
      "name": "lock_sock_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void lock_sock_nested(struct sock * sk, int subclass)
```

```json
{
  "name": "lock_sock_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587410016,
      "name": "lock_sock_nested",
      "external": true,
      "loc": "net/core/sock.c:2756",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/sockmap.c:smap_tx_work",
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect",
        "security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:tun_detach_filter",
        "drivers/net/tun.c:tun_attach",
        "net/socket.c:sock_fasync",
        "net/core/sock.c:sk_wait_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/skbuff.c:skb_send_sock",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/filter.c:sk_get_filter",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_sendpage",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/datagram.c:ip4_datagram_connect",
        "net/ipv4/raw.c:raw_abort",
        "net/ipv4/raw.c:raw_destroy",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_abort",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_disconnect",
        "net/ipv4/udp.c:udp_sendpage",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/devinet.c:ip_mc_config",
        "net/ipv4/af_inet.c:inet_shutdown",
        "net/ipv4/af_inet.c:inet_accept",
        "net/ipv4/af_inet.c:inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:inet_bind",
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_autobind",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/addrconf.c:ipv6_mc_config",
        "net/ipv6/udp.c:udpv6_destroy_sock",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:raw6_destroy",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_connect",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/strparser/strparser.c:strp_sock_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587410016,
      "name": "lock_sock_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void lock_sock_nested(struct sock * sk, int subclass)
```

```json
{
  "name": "lock_sock_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587723056,
      "name": "lock_sock_nested",
      "external": true,
      "loc": "net/core/sock.c:2831",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/sockmap.c:sock_hash_update_elem",
        "kernel/bpf/sockmap.c:sock_map_update_elem",
        "kernel/bpf/sockmap.c:smap_tx_work",
        "kernel/bpf/sockmap.c:bpf_tcp_sendpage",
        "kernel/bpf/sockmap.c:bpf_tcp_sendmsg",
        "kernel/bpf/sockmap.c:bpf_tcp_recvmsg",
        "kernel/bpf/sockmap.c:bpf_tcp_recvmsg",
        "kernel/bpf/sockmap.c:bpf_exec_tx_verdict",
        "kernel/bpf/sockmap.c:bpf_exec_tx_verdict",
        "kernel/bpf/sockmap.c:bpf_exec_tx_verdict",
        "kernel/bpf/sockmap.c:bpf_exec_tx_verdict",
        "kernel/bpf/sockmap.c:bpf_exec_tx_verdict",
        "kernel/bpf/sockmap.c:bpf_tcp_close",
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect",
        "security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:tun_detach_filter",
        "drivers/net/tun.c:tun_attach",
        "net/socket.c:sock_fasync",
        "net/core/sock.c:sk_wait_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/skbuff.c:skb_send_sock",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/filter.c:sk_get_filter",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_sendpage",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/datagram.c:ip4_datagram_connect",
        "net/ipv4/raw.c:raw_abort",
        "net/ipv4/raw.c:raw_destroy",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_abort",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_disconnect",
        "net/ipv4/udp.c:udp_sendpage",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/devinet.c:ip_mc_config",
        "net/ipv4/af_inet.c:inet_shutdown",
        "net/ipv4/af_inet.c:inet_accept",
        "net/ipv4/af_inet.c:inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_bind",
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_autobind",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/addrconf.c:ipv6_mc_config",
        "net/ipv6/udp.c:udpv6_destroy_sock",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:raw6_destroy",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_connect",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release",
        "net/strparser/strparser.c:strp_sock_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587723056,
      "name": "lock_sock_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void lock_sock_nested(struct sock * sk, int subclass)
```

```json
{
  "name": "lock_sock_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587855712,
      "name": "lock_sock_nested",
      "external": true,
      "loc": "net/core/sock.c:2780",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect",
        "security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:tun_detach_filter",
        "drivers/net/tun.c:tun_attach",
        "net/socket.c:sock_fasync",
        "net/core/sock.c:sk_wait_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/filter.c:sk_get_filter",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/sock_map.c:sock_hash_update_elem",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_sendpage",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/datagram.c:ip4_datagram_connect",
        "net/ipv4/raw.c:raw_abort",
        "net/ipv4/raw.c:raw_destroy",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_abort",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_disconnect",
        "net/ipv4/udp.c:udp_sendpage",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/devinet.c:ip_mc_config",
        "net/ipv4/af_inet.c:inet_shutdown",
        "net/ipv4/af_inet.c:inet_accept",
        "net/ipv4/af_inet.c:inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_bind",
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_autobind",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/addrconf.c:ipv6_mc_config",
        "net/ipv6/udp.c:udpv6_destroy_sock",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:raw6_destroy",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_connect",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release",
        "net/strparser/strparser.c:strp_sock_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587855712,
      "name": "lock_sock_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void lock_sock_nested(struct sock * sk, int subclass)
```

```json
{
  "name": "lock_sock_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588160128,
      "name": "lock_sock_nested",
      "external": true,
      "loc": "net/core/sock.c:2923",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect",
        "security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:tun_detach_filter",
        "drivers/net/tun.c:tun_attach",
        "net/socket.c:sock_fasync",
        "net/core/sock.c:sk_wait_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/filter.c:sk_get_filter",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/sock_map.c:sock_hash_update_elem",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_sendpage",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/datagram.c:ip4_datagram_connect",
        "net/ipv4/raw.c:raw_abort",
        "net/ipv4/raw.c:raw_destroy",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_abort",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_disconnect",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_sendpage",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/devinet.c:ip_mc_config",
        "net/ipv4/af_inet.c:inet_shutdown",
        "net/ipv4/af_inet.c:inet_accept",
        "net/ipv4/af_inet.c:inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_bind",
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_autobind",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/addrconf.c:ipv6_mc_config",
        "net/ipv6/udp.c:udpv6_destroy_sock",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:raw6_destroy",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_connect",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release",
        "net/strparser/strparser.c:strp_sock_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588160128,
      "name": "lock_sock_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void lock_sock_nested(struct sock * sk, int subclass)
```

```json
{
  "name": "lock_sock_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588365360,
      "name": "lock_sock_nested",
      "external": true,
      "loc": "net/core/sock.c:2938",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect",
        "security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:tun_detach_filter",
        "drivers/net/tun.c:tun_attach",
        "net/socket.c:sock_fasync",
        "net/core/sock.c:sk_wait_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/filter.c:sk_get_filter",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_update_elem",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/sock_map.c:sock_map_free",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_sendpage",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/datagram.c:ip4_datagram_connect",
        "net/ipv4/raw.c:raw_abort",
        "net/ipv4/raw.c:raw_destroy",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_abort",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_disconnect",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_sendpage",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/devinet.c:ip_mc_config",
        "net/ipv4/af_inet.c:inet_shutdown",
        "net/ipv4/af_inet.c:inet_accept",
        "net/ipv4/af_inet.c:inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_bind",
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_autobind",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/addrconf.c:ipv6_mc_config",
        "net/ipv6/udp.c:udpv6_destroy_sock",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:raw6_destroy",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_connect",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release",
        "net/strparser/strparser.c:strp_sock_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588365360,
      "name": "lock_sock_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void lock_sock_nested(struct sock * sk, int subclass)
```

```json
{
  "name": "lock_sock_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589222272,
      "name": "lock_sock_nested",
      "external": true,
      "loc": "net/core/sock.c:3067",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect",
        "security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt",
        "drivers/net/tun.c:tun_attach_filter",
        "drivers/net/tun.c:tun_attach_filter",
        "net/socket.c:sock_fasync",
        "net/core/sock.c:sk_wait_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_set_rcvbuf",
        "net/core/sock.c:sock_set_keepalive",
        "net/core/sock.c:sock_enable_timestamps",
        "net/core/sock.c:sock_set_sndtimeo",
        "net/core/sock.c:sock_set_priority",
        "net/core/sock.c:sock_no_linger",
        "net/core/sock.c:sock_set_reuseport",
        "net/core/sock.c:sock_set_reuseaddr",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/filter.c:sk_get_filter",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/sock_map.c:sock_map_close",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_update_elem",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/sock_map.c:sock_map_free",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/ipv4/ip_sockglue.c:compat_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:compat_ip_setsockopt",
        "net/ipv4/ip_sockglue.c:compat_ip_setsockopt",
        "net/ipv4/ip_sockglue.c:compat_ip_setsockopt",
        "net/ipv4/ip_sockglue.c:ip_sock_set_pktinfo",
        "net/ipv4/ip_sockglue.c:ip_sock_set_mtu_discover",
        "net/ipv4/ip_sockglue.c:ip_sock_set_recverr",
        "net/ipv4/ip_sockglue.c:ip_sock_set_freebind",
        "net/ipv4/ip_sockglue.c:ip_sock_set_tos",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_wait_for_connect",
        "net/ipv4/tcp.c:tcp_sock_set_keepcnt",
        "net/ipv4/tcp.c:tcp_sock_set_keepintvl",
        "net/ipv4/tcp.c:tcp_sock_set_keepidle",
        "net/ipv4/tcp.c:tcp_sock_set_user_timeout",
        "net/ipv4/tcp.c:tcp_sock_set_syncnt",
        "net/ipv4/tcp.c:tcp_sock_set_quickack",
        "net/ipv4/tcp.c:tcp_sock_set_nodelay",
        "net/ipv4/tcp.c:tcp_sock_set_cork",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_sendpage",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/datagram.c:ip4_datagram_connect",
        "net/ipv4/raw.c:raw_abort",
        "net/ipv4/raw.c:raw_destroy",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_abort",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_disconnect",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_sendpage",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/af_inet.c:inet_shutdown",
        "net/ipv4/af_inet.c:inet_getname",
        "net/ipv4/af_inet.c:inet_accept",
        "net/ipv4/af_inet.c:inet_stream_connect",
        "net/ipv4/af_inet.c:inet_wait_for_connect",
        "net/ipv4/af_inet.c:__inet_bind",
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_autobind",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/xfrm/espintcp.c:espintcp_tx_work",
        "net/xfrm/espintcp.c:espintcp_sendmsg",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/addrconf.c:ipv6_mc_config",
        "net/ipv6/ipv6_sockglue.c:compat_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:compat_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:compat_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:compat_ipv6_setsockopt",
        "net/ipv6/udp.c:udpv6_destroy_sock",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:raw6_destroy",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_connect_v6_only",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release",
        "net/strparser/strparser.c:strp_sock_lock",
        "net/mptcp/protocol.c:mptcp_shutdown",
        "net/mptcp/protocol.c:mptcp_shutdown",
        "net/mptcp/protocol.c:mptcp_poll",
        "net/mptcp/protocol.c:mptcp_poll",
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_stream_connect",
        "net/mptcp/protocol.c:mptcp_bind",
        "net/mptcp/protocol.c:mptcp_getsockopt",
        "net/mptcp/protocol.c:mptcp_setsockopt",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:__mptcp_move_skbs",
        "net/mptcp/protocol.c:mptcp_wait_data",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/subflow.c:mptcp_subflow_create_socket",
        "net/mptcp/pm.c:pm_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589222272,
      "name": "lock_sock_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void lock_sock_nested(struct sock * sk, int subclass)
```

```json
{
  "name": "lock_sock_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589231504,
      "name": "lock_sock_nested",
      "external": true,
      "loc": "net/core/sock.c:3046",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect",
        "security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt",
        "drivers/net/tun.c:tun_attach_filter",
        "drivers/net/tun.c:tun_attach_filter",
        "net/socket.c:sock_fasync",
        "net/core/sock.c:sk_wait_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_set_mark",
        "net/core/sock.c:sock_set_rcvbuf",
        "net/core/sock.c:sock_set_keepalive",
        "net/core/sock.c:sock_enable_timestamps",
        "net/core/sock.c:sock_set_sndtimeo",
        "net/core/sock.c:sock_set_priority",
        "net/core/sock.c:sock_no_linger",
        "net/core/sock.c:sock_set_reuseport",
        "net/core/sock.c:sock_set_reuseaddr",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/filter.c:sk_get_filter",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/sock_map.c:sock_map_close",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_update_elem_sys",
        "net/core/sock_map.c:sock_map_free",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:ip_sock_set_pktinfo",
        "net/ipv4/ip_sockglue.c:ip_sock_set_mtu_discover",
        "net/ipv4/ip_sockglue.c:ip_sock_set_recverr",
        "net/ipv4/ip_sockglue.c:ip_sock_set_freebind",
        "net/ipv4/ip_sockglue.c:ip_sock_set_tos",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_wait_for_connect",
        "net/ipv4/tcp.c:tcp_sock_set_keepcnt",
        "net/ipv4/tcp.c:tcp_sock_set_keepintvl",
        "net/ipv4/tcp.c:tcp_sock_set_keepidle",
        "net/ipv4/tcp.c:tcp_sock_set_user_timeout",
        "net/ipv4/tcp.c:tcp_sock_set_syncnt",
        "net/ipv4/tcp.c:tcp_sock_set_quickack",
        "net/ipv4/tcp.c:tcp_sock_set_nodelay",
        "net/ipv4/tcp.c:tcp_sock_set_cork",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_sendpage",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/datagram.c:ip4_datagram_connect",
        "net/ipv4/raw.c:raw_abort",
        "net/ipv4/raw.c:raw_destroy",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_abort",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_disconnect",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_sendpage",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/af_inet.c:inet_shutdown",
        "net/ipv4/af_inet.c:inet_getname",
        "net/ipv4/af_inet.c:inet_accept",
        "net/ipv4/af_inet.c:inet_stream_connect",
        "net/ipv4/af_inet.c:inet_wait_for_connect",
        "net/ipv4/af_inet.c:__inet_bind",
        "net/ipv4/af_inet.c:inet_bind",
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_autobind",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/xfrm/espintcp.c:espintcp_tx_work",
        "net/xfrm/espintcp.c:espintcp_sendmsg",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/addrconf.c:ipv6_mc_config",
        "net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter",
        "net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter",
        "net/ipv6/udp.c:udpv6_destroy_sock",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:raw6_destroy",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_connect_v6_only",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release",
        "net/strparser/strparser.c:strp_sock_lock",
        "net/mptcp/protocol.c:mptcp6_release",
        "net/mptcp/protocol.c:mptcp_release",
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_stream_connect",
        "net/mptcp/protocol.c:mptcp_bind",
        "net/mptcp/protocol.c:mptcp_getsockopt",
        "net/mptcp/protocol.c:mptcp_setsockopt",
        "net/mptcp/protocol.c:mptcp_setsockopt",
        "net/mptcp/protocol.c:mptcp_setsockopt",
        "net/mptcp/protocol.c:mptcp_disconnect",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:mptcp_subflow_shutdown",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_check_fastclose",
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_wait_data",
        "net/mptcp/protocol.c:__mptcp_push_pending",
        "net/mptcp/subflow.c:mptcp_subflow_create_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589231504,
      "name": "lock_sock_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void lock_sock_nested(struct sock * sk, int subclass)
```

```json
{
  "name": "lock_sock_nested",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589126064,
      "name": "lock_sock_nested",
      "external": true,
      "loc": "net/core/sock.c:3069",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_set_priority",
        "net/core/sock.c:sock_no_linger",
        "net/core/sock.c:sock_set_reuseport",
        "net/core/sock.c:sock_set_reuseaddr"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect",
        "security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/socket.c:sock_fasync",
        "net/core/sock.c:sk_wait_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_set_mark",
        "net/core/sock.c:sock_set_rcvbuf",
        "net/core/sock.c:sock_set_keepalive",
        "net/core/sock.c:sock_enable_timestamps",
        "net/core/sock.c:sock_set_sndtimeo",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/filter.c:sk_get_filter",
        "net/core/skmsg.c:sk_msg_wait_data",
        "net/core/sock_map.c:sock_map_close",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_update_elem_sys",
        "net/core/sock_map.c:sock_map_free",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:ip_sock_set_pktinfo",
        "net/ipv4/ip_sockglue.c:ip_sock_set_mtu_discover",
        "net/ipv4/ip_sockglue.c:ip_sock_set_recverr",
        "net/ipv4/ip_sockglue.c:ip_sock_set_freebind",
        "net/ipv4/ip_sockglue.c:ip_sock_set_tos",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_sock_set_keepcnt",
        "net/ipv4/tcp.c:tcp_sock_set_keepintvl",
        "net/ipv4/tcp.c:tcp_sock_set_keepidle",
        "net/ipv4/tcp.c:tcp_sock_set_user_timeout",
        "net/ipv4/tcp.c:tcp_sock_set_syncnt",
        "net/ipv4/tcp.c:tcp_sock_set_quickack",
        "net/ipv4/tcp.c:tcp_sock_set_nodelay",
        "net/ipv4/tcp.c:tcp_sock_set_cork",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_sendpage",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/datagram.c:ip4_datagram_connect",
        "net/ipv4/raw.c:raw_abort",
        "net/ipv4/raw.c:raw_destroy",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_abort",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_disconnect",
        "net/ipv4/udp.c:udp_pre_connect",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_sendpage",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/af_inet.c:inet_shutdown",
        "net/ipv4/af_inet.c:inet_getname",
        "net/ipv4/af_inet.c:inet_getname",
        "net/ipv4/af_inet.c:inet_accept",
        "net/ipv4/af_inet.c:inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_bind",
        "net/ipv4/af_inet.c:inet_bind",
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_autobind",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/udp_bpf.c:udp_bpf_recvmsg",
        "net/xfrm/espintcp.c:espintcp_tx_work",
        "net/xfrm/espintcp.c:espintcp_sendmsg",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/addrconf.c:ipv6_mc_config",
        "net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter",
        "net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter",
        "net/ipv6/udp.c:udpv6_destroy_sock",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:raw6_destroy",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/mcast.c:ipv6_sock_mc_close",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_connect_v6_only",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release",
        "net/strparser/strparser.c:strp_sock_lock",
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_stream_connect",
        "net/mptcp/protocol.c:mptcp_bind",
        "net/mptcp/protocol.c:mptcp_disconnect",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:mptcp_subflow_shutdown",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/protocol.c:mptcp_wait_data",
        "net/mptcp/protocol.c:__mptcp_push_pending",
        "net/mptcp/subflow.c:mptcp_subflow_create_socket",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_addrs_list",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr",
        "net/mptcp/sockopt.c:mptcp_getsockopt",
        "net/mptcp/sockopt.c:mptcp_getsockopt",
        "net/mptcp/sockopt.c:mptcp_setsockopt",
        "net/mptcp/sockopt.c:mptcp_setsockopt",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589124960,
      "name": "lock_sock_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void lock_sock_nested(struct sock * sk, int subclass)
```

```json
{
  "name": "lock_sock_nested",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589845719,
      "name": "lock_sock_nested",
      "external": true,
      "loc": "net/core/sock.c:3202",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_wait_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_set_mark",
        "net/core/sock.c:sock_set_rcvbuf",
        "net/core/sock.c:sock_set_keepalive",
        "net/core/sock.c:sock_enable_timestamps",
        "net/core/sock.c:sock_set_sndtimeo",
        "net/core/sock.c:sock_set_priority",
        "net/core/sock.c:sock_no_linger",
        "net/core/sock.c:sock_set_reuseport",
        "net/core/sock.c:sock_set_reuseaddr"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect",
        "security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/socket.c:sock_fasync",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/filter.c:sk_get_filter",
        "net/core/sock_map.c:sock_map_close",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_update_elem_sys",
        "net/core/sock_map.c:sock_map_free",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:ip_sock_set_pktinfo",
        "net/ipv4/ip_sockglue.c:ip_sock_set_mtu_discover",
        "net/ipv4/ip_sockglue.c:ip_sock_set_recverr",
        "net/ipv4/ip_sockglue.c:ip_sock_set_freebind",
        "net/ipv4/ip_sockglue.c:ip_sock_set_tos",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_sock_set_keepcnt",
        "net/ipv4/tcp.c:tcp_sock_set_keepintvl",
        "net/ipv4/tcp.c:tcp_sock_set_keepidle",
        "net/ipv4/tcp.c:tcp_sock_set_user_timeout",
        "net/ipv4/tcp.c:tcp_sock_set_syncnt",
        "net/ipv4/tcp.c:tcp_sock_set_quickack",
        "net/ipv4/tcp.c:tcp_sock_set_nodelay",
        "net/ipv4/tcp.c:tcp_sock_set_cork",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_sendpage",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/datagram.c:ip4_datagram_connect",
        "net/ipv4/raw.c:raw_abort",
        "net/ipv4/raw.c:raw_bind",
        "net/ipv4/raw.c:raw_destroy",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_abort",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_disconnect",
        "net/ipv4/udp.c:udp_pre_connect",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_sendpage",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/af_inet.c:inet_shutdown",
        "net/ipv4/af_inet.c:inet_getname",
        "net/ipv4/af_inet.c:inet_accept",
        "net/ipv4/af_inet.c:inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_bind",
        "net/ipv4/af_inet.c:inet_bind",
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_autobind",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser",
        "net/ipv4/tcp_bpf.c:tcp_msg_wait_data",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/xfrm/espintcp.c:espintcp_tx_work",
        "net/xfrm/espintcp.c:espintcp_sendmsg",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/addrconf.c:ipv6_mc_config",
        "net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter",
        "net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter",
        "net/ipv6/udp.c:udpv6_destroy_sock",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:raw6_destroy",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/mcast.c:ipv6_sock_mc_close",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_connect_v6_only",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release",
        "net/strparser/strparser.c:strp_sock_lock",
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_stream_connect",
        "net/mptcp/protocol.c:mptcp_bind",
        "net/mptcp/protocol.c:mptcp_disconnect",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:mptcp_subflow_shutdown",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/protocol.c:__mptcp_push_pending",
        "net/mptcp/subflow.c:mptcp_subflow_create_socket",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_addrs_list",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr",
        "net/mptcp/sockopt.c:mptcp_getsockopt",
        "net/mptcp/sockopt.c:mptcp_getsockopt",
        "net/mptcp/sockopt.c:mptcp_setsockopt",
        "net/mptcp/sockopt.c:mptcp_setsockopt",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589843824,
      "name": "lock_sock_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void lock_sock_nested(struct sock * sk, int subclass)
```

```json
{
  "name": "lock_sock_nested",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591367031,
      "name": "lock_sock_nested",
      "external": true,
      "loc": "net/core/sock.c:3388",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_wait_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_set_mark",
        "net/core/sock.c:sock_set_rcvbuf",
        "net/core/sock.c:sock_set_keepalive",
        "net/core/sock.c:sock_enable_timestamps",
        "net/core/sock.c:sock_set_sndtimeo",
        "net/core/sock.c:sock_set_priority",
        "net/core/sock.c:sock_no_linger",
        "net/core/sock.c:sock_set_reuseport",
        "net/core/sock.c:sock_set_reuseaddr"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect",
        "security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/socket.c:sock_fasync",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/filter.c:sk_get_filter",
        "net/core/sock_map.c:sock_map_close",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_update_elem_sys",
        "net/core/sock_map.c:sock_map_free",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:ip_sock_set_pktinfo",
        "net/ipv4/ip_sockglue.c:ip_sock_set_mtu_discover",
        "net/ipv4/ip_sockglue.c:ip_sock_set_recverr",
        "net/ipv4/ip_sockglue.c:ip_sock_set_freebind",
        "net/ipv4/ip_sockglue.c:ip_sock_set_tos",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_abort",
        "net/ipv4/tcp.c:tcp_sock_set_keepcnt",
        "net/ipv4/tcp.c:tcp_sock_set_keepintvl",
        "net/ipv4/tcp.c:tcp_sock_set_keepidle",
        "net/ipv4/tcp.c:tcp_sock_set_user_timeout",
        "net/ipv4/tcp.c:tcp_sock_set_syncnt",
        "net/ipv4/tcp.c:tcp_sock_set_quickack",
        "net/ipv4/tcp.c:tcp_sock_set_nodelay",
        "net/ipv4/tcp.c:tcp_sock_set_cork",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_sendpage",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/datagram.c:ip4_datagram_connect",
        "net/ipv4/raw.c:raw_abort",
        "net/ipv4/raw.c:raw_bind",
        "net/ipv4/raw.c:raw_destroy",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_abort",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_disconnect",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_sendpage",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/af_inet.c:inet_shutdown",
        "net/ipv4/af_inet.c:inet_getname",
        "net/ipv4/af_inet.c:inet_accept",
        "net/ipv4/af_inet.c:inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_bind",
        "net/ipv4/af_inet.c:inet_bind",
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_autobind",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser",
        "net/ipv4/tcp_bpf.c:tcp_msg_wait_data",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/xfrm/espintcp.c:espintcp_tx_work",
        "net/xfrm/espintcp.c:espintcp_sendmsg",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/addrconf.c:ipv6_mc_config",
        "net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter",
        "net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter",
        "net/ipv6/udp.c:udpv6_destroy_sock",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:raw6_destroy",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/mcast.c:ipv6_sock_mc_close",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_connect_v6_only",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release",
        "net/strparser/strparser.c:strp_sock_lock",
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_stream_connect",
        "net/mptcp/protocol.c:mptcp_bind",
        "net/mptcp/protocol.c:mptcp_ioctl",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:mptcp_subflow_shutdown",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:__mptcp_push_pending",
        "net/mptcp/subflow.c:mptcp_subflow_queue_clean",
        "net/mptcp/subflow.c:mptcp_subflow_create_socket",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr",
        "net/mptcp/sockopt.c:mptcp_getsockopt",
        "net/mptcp/sockopt.c:mptcp_getsockopt",
        "net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs",
        "net/mptcp/sockopt.c:mptcp_getsockopt_tcpinfo",
        "net/mptcp/sockopt.c:mptcp_setsockopt",
        "net/mptcp/sockopt.c:mptcp_setsockopt",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_v4",
        "net/mptcp/sockopt.c:mptcp_setsockopt_v4",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval",
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce",
        "net/mctp/af_mctp.c:mctp_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591365040,
      "name": "lock_sock_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void lock_sock_nested(struct sock * sk, int subclass)
```

```json
{
  "name": "lock_sock_nested",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593122103,
      "name": "lock_sock_nested",
      "external": true,
      "loc": "net/core/sock.c:3477",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_wait_data",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sock_set_mark",
        "net/core/sock.c:sock_set_rcvbuf",
        "net/core/sock.c:sock_set_keepalive",
        "net/core/sock.c:sock_enable_timestamps",
        "net/core/sock.c:sock_set_sndtimeo",
        "net/core/sock.c:sock_set_priority",
        "net/core/sock.c:sock_no_linger",
        "net/core/sock.c:sock_set_reuseport",
        "net/core/sock.c:sock_set_reuseaddr",
        "net/core/sock.c:sock_bindtoindex"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect",
        "security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/socket.c:sock_fasync",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/sock_map.c:sock_map_close",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_update_elem_sys",
        "net/core/sock_map.c:sock_map_free",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/ipv4/ip_sockglue.c:ip_sock_set_pktinfo",
        "net/ipv4/ip_sockglue.c:ip_sock_set_mtu_discover",
        "net/ipv4/ip_sockglue.c:ip_sock_set_recverr",
        "net/ipv4/ip_sockglue.c:ip_sock_set_freebind",
        "net/ipv4/ip_sockglue.c:ip_sock_set_tos",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_abort",
        "net/ipv4/tcp.c:tcp_sock_set_keepcnt",
        "net/ipv4/tcp.c:tcp_sock_set_keepintvl",
        "net/ipv4/tcp.c:tcp_sock_set_keepidle",
        "net/ipv4/tcp.c:tcp_sock_set_user_timeout",
        "net/ipv4/tcp.c:tcp_sock_set_syncnt",
        "net/ipv4/tcp.c:tcp_sock_set_quickack",
        "net/ipv4/tcp.c:tcp_sock_set_nodelay",
        "net/ipv4/tcp.c:tcp_sock_set_cork",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_sendpage",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/datagram.c:ip4_datagram_connect",
        "net/ipv4/raw.c:raw_abort",
        "net/ipv4/raw.c:raw_bind",
        "net/ipv4/raw.c:raw_destroy",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_abort",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_disconnect",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_sendpage",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/af_inet.c:inet_shutdown",
        "net/ipv4/af_inet.c:inet_getname",
        "net/ipv4/af_inet.c:inet_accept",
        "net/ipv4/af_inet.c:inet_stream_connect",
        "net/ipv4/af_inet.c:inet_wait_for_connect",
        "net/ipv4/af_inet.c:__inet_bind",
        "net/ipv4/af_inet.c:inet_bind",
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_autobind",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser",
        "net/ipv4/tcp_bpf.c:tcp_msg_wait_data",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/xfrm/espintcp.c:espintcp_tx_work",
        "net/xfrm/espintcp.c:espintcp_sendmsg",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/addrconf.c:ipv6_mc_config",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:raw6_destroy",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/mcast.c:ipv6_sock_mc_close",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_connect_v6_only",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release",
        "net/strparser/strparser.c:strp_sock_lock",
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_stream_connect",
        "net/mptcp/protocol.c:mptcp_bind",
        "net/mptcp/protocol.c:mptcp_ioctl",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:mptcp_subflow_shutdown",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:__mptcp_push_pending",
        "net/mptcp/subflow.c:mptcp_subflow_queue_clean",
        "net/mptcp/subflow.c:mptcp_subflow_queue_clean",
        "net/mptcp/subflow.c:mptcp_subflow_create_socket",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket",
        "net/mptcp/sockopt.c:mptcp_getsockopt",
        "net/mptcp/sockopt.c:mptcp_getsockopt",
        "net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs",
        "net/mptcp/sockopt.c:mptcp_getsockopt_tcpinfo",
        "net/mptcp/sockopt.c:mptcp_setsockopt",
        "net/mptcp/sockopt.c:mptcp_setsockopt",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_v4",
        "net/mptcp/sockopt.c:mptcp_setsockopt_v4",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval",
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce",
        "net/mctp/af_mctp.c:mctp_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593119616,
      "name": "lock_sock_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void lock_sock_nested(struct sock * sk, int subclass)
```

```json
{
  "name": "lock_sock_nested",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593574830,
      "name": "lock_sock_nested",
      "external": true,
      "loc": "net/core/sock.c:3510",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_wait_data",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sock_set_mark",
        "net/core/sock.c:sock_set_rcvbuf",
        "net/core/sock.c:sock_set_keepalive",
        "net/core/sock.c:sock_enable_timestamps",
        "net/core/sock.c:sock_set_sndtimeo",
        "net/core/sock.c:sock_set_priority",
        "net/core/sock.c:sock_no_linger",
        "net/core/sock.c:sock_set_reuseport",
        "net/core/sock.c:sock_set_reuseaddr",
        "net/core/sock.c:sock_bindtoindex"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect",
        "security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/socket.c:sock_fasync",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/sock_map.c:sock_map_close",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_update_elem_sys",
        "net/core/sock_map.c:sock_map_free",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/ipv4/ip_sockglue.c:ip_sock_set_pktinfo",
        "net/ipv4/ip_sockglue.c:ip_sock_set_mtu_discover",
        "net/ipv4/ip_sockglue.c:ip_sock_set_recverr",
        "net/ipv4/ip_sockglue.c:ip_sock_set_freebind",
        "net/ipv4/ip_sockglue.c:ip_sock_set_tos",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_abort",
        "net/ipv4/tcp.c:tcp_sock_set_keepcnt",
        "net/ipv4/tcp.c:tcp_sock_set_keepintvl",
        "net/ipv4/tcp.c:tcp_sock_set_keepidle",
        "net/ipv4/tcp.c:tcp_sock_set_user_timeout",
        "net/ipv4/tcp.c:tcp_sock_set_syncnt",
        "net/ipv4/tcp.c:tcp_sock_set_quickack",
        "net/ipv4/tcp.c:tcp_sock_set_nodelay",
        "net/ipv4/tcp.c:tcp_sock_set_cork",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_splice_eof",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show",
        "net/ipv4/datagram.c:ip4_datagram_connect",
        "net/ipv4/raw.c:raw_abort",
        "net/ipv4/raw.c:raw_bind",
        "net/ipv4/raw.c:raw_destroy",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:bpf_iter_udp_seq_show",
        "net/ipv4/udp.c:udp_abort",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_disconnect",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_splice_eof",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/af_inet.c:inet_shutdown",
        "net/ipv4/af_inet.c:inet_getname",
        "net/ipv4/af_inet.c:inet_accept",
        "net/ipv4/af_inet.c:inet_stream_connect",
        "net/ipv4/af_inet.c:inet_wait_for_connect",
        "net/ipv4/af_inet.c:__inet_bind",
        "net/ipv4/af_inet.c:inet_bind",
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_autobind",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser",
        "net/ipv4/tcp_bpf.c:tcp_msg_wait_data",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/xfrm/espintcp.c:espintcp_tx_work",
        "net/xfrm/espintcp.c:espintcp_sendmsg",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/addrconf.c:ipv6_mc_config",
        "net/ipv6/udp.c:udpv6_splice_eof",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:raw6_destroy",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/mcast.c:ipv6_sock_mc_close",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_connect_v6_only",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release",
        "net/strparser/strparser.c:strp_sock_lock",
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_bind",
        "net/mptcp/protocol.c:mptcp_ioctl",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:mptcp_subflow_shutdown",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:__mptcp_push_pending",
        "net/mptcp/subflow.c:mptcp_subflow_queue_clean",
        "net/mptcp/subflow.c:mptcp_subflow_queue_clean",
        "net/mptcp/subflow.c:mptcp_subflow_create_socket",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket",
        "net/mptcp/sockopt.c:mptcp_getsockopt",
        "net/mptcp/sockopt.c:mptcp_getsockopt",
        "net/mptcp/sockopt.c:mptcp_getsockopt_full_info",
        "net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs",
        "net/mptcp/sockopt.c:mptcp_getsockopt_tcpinfo",
        "net/mptcp/sockopt.c:mptcp_setsockopt",
        "net/mptcp/sockopt.c:mptcp_setsockopt",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_v4",
        "net/mptcp/sockopt.c:mptcp_setsockopt_v4",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval",
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce",
        "net/mctp/af_mctp.c:mctp_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593572304,
      "name": "lock_sock_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void lock_sock_nested(struct sock * sk, int subclass)
```

```json
{
  "name": "lock_sock_nested",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594347344,
      "name": "lock_sock_nested",
      "external": true,
      "loc": "net/core/sock.c:3520",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_wait_data",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sock_set_mark",
        "net/core/sock.c:sock_set_rcvbuf",
        "net/core/sock.c:sock_set_keepalive",
        "net/core/sock.c:sock_enable_timestamps",
        "net/core/sock.c:sock_set_sndtimeo",
        "net/core/sock.c:sock_no_linger",
        "net/core/sock.c:sock_set_reuseport",
        "net/core/sock.c:sock_set_reuseaddr",
        "net/core/sock.c:sock_bindtoindex"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect",
        "security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/socket.c:sock_fasync",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/sock_map.c:sock_map_close",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_update_elem_sys",
        "net/core/sock_map.c:sock_map_free",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_abort",
        "net/ipv4/tcp.c:tcp_sock_set_keepidle",
        "net/ipv4/tcp.c:tcp_sock_set_quickack",
        "net/ipv4/tcp.c:tcp_sock_set_nodelay",
        "net/ipv4/tcp.c:tcp_sock_set_cork",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_splice_eof",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show",
        "net/ipv4/datagram.c:ip4_datagram_connect",
        "net/ipv4/raw.c:raw_abort",
        "net/ipv4/raw.c:raw_bind",
        "net/ipv4/raw.c:raw_destroy",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:bpf_iter_udp_seq_show",
        "net/ipv4/udp.c:udp_abort",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_disconnect",
        "net/ipv4/udp.c:udp_pre_connect",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_splice_eof",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/af_inet.c:inet_shutdown",
        "net/ipv4/af_inet.c:inet_getname",
        "net/ipv4/af_inet.c:inet_accept",
        "net/ipv4/af_inet.c:inet_stream_connect",
        "net/ipv4/af_inet.c:inet_wait_for_connect",
        "net/ipv4/af_inet.c:__inet_bind",
        "net/ipv4/af_inet.c:inet_bind_sk",
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_autobind",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ping.c:ping_pre_connect",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser",
        "net/ipv4/tcp_bpf.c:tcp_msg_wait_data",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/xfrm/espintcp.c:espintcp_tx_work",
        "net/xfrm/espintcp.c:espintcp_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:__unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_bind_sk",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/addrconf.c:ipv6_mc_config",
        "net/ipv6/udp.c:udpv6_splice_eof",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_pre_connect",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:raw6_destroy",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/mcast.c:ipv6_sock_mc_close",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_pre_connect",
        "net/ipv6/datagram.c:ip6_datagram_connect_v6_only",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release",
        "net/strparser/strparser.c:strp_sock_lock",
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_bind",
        "net/mptcp/protocol.c:mptcp_connect",
        "net/mptcp/protocol.c:mptcp_ioctl",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:mptcp_subflow_shutdown",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:__mptcp_push_pending",
        "net/mptcp/subflow.c:mptcp_subflow_queue_clean",
        "net/mptcp/subflow.c:mptcp_subflow_queue_clean",
        "net/mptcp/subflow.c:mptcp_subflow_create_socket",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_flush_addrs_doit",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit",
        "net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_doit",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket",
        "net/mptcp/sockopt.c:mptcp_getsockopt",
        "net/mptcp/sockopt.c:mptcp_getsockopt",
        "net/mptcp/sockopt.c:mptcp_getsockopt_full_info",
        "net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs",
        "net/mptcp/sockopt.c:mptcp_getsockopt_tcpinfo",
        "net/mptcp/sockopt.c:mptcp_setsockopt",
        "net/mptcp/sockopt.c:mptcp_setsockopt",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_ip_set",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion",
        "net/mptcp/sockopt.c:mptcp_setsockopt_v6",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval",
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags",
        "net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_destroy_doit",
        "net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_create_doit",
        "net/mptcp/pm_userspace.c:mptcp_pm_nl_remove_doit",
        "net/mptcp/pm_userspace.c:mptcp_pm_nl_remove_doit",
        "net/mptcp/pm_userspace.c:mptcp_pm_nl_announce_doit",
        "net/mctp/af_mctp.c:mctp_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594344896,
      "name": "lock_sock_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void lock_sock_nested(struct sock * sk, int subclass)
```

```json
{
  "name": "lock_sock_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501869176,
      "name": "lock_sock_nested",
      "external": true,
      "loc": "net/core/sock.c:2938",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect",
        "security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:tun_detach_filter",
        "net/socket.c:sock_fasync",
        "net/core/sock.c:sk_wait_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/filter.c:sk_get_filter",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_update_elem",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/sock_map.c:sock_map_free",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_sendpage",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/datagram.c:ip4_datagram_connect",
        "net/ipv4/raw.c:raw_abort",
        "net/ipv4/raw.c:raw_destroy",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_abort",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_disconnect",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_sendpage",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/af_inet.c:inet_shutdown",
        "net/ipv4/af_inet.c:inet_accept",
        "net/ipv4/af_inet.c:inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_bind",
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_autobind",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/addrconf.c:ipv6_mc_config",
        "net/ipv6/udp.c:udpv6_destroy_sock",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:raw6_destroy",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_connect",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release",
        "net/strparser/strparser.c:strp_sock_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501869176,
      "name": "lock_sock_nested",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void lock_sock_nested(struct sock * sk, int subclass)
```

```json
{
  "name": "lock_sock_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234628028,
      "name": "lock_sock_nested",
      "external": true,
      "loc": "net/core/sock.c:2938",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect",
        "security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt",
        "drivers/net/tun.c:tun_detach_filter",
        "drivers/net/tun.c:tun_attach",
        "net/socket.c:sock_fasync",
        "net/core/sock.c:sk_wait_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/filter.c:sk_get_filter",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_update_elem",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/sock_map.c:sock_map_free",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_sendpage",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/datagram.c:ip4_datagram_connect",
        "net/ipv4/raw.c:raw_abort",
        "net/ipv4/raw.c:raw_destroy",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_abort",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_disconnect",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_sendpage",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/devinet.c:ip_mc_config",
        "net/ipv4/af_inet.c:inet_shutdown",
        "net/ipv4/af_inet.c:inet_accept",
        "net/ipv4/af_inet.c:inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_bind",
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_autobind",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/addrconf.c:ipv6_mc_config",
        "net/ipv6/udp.c:udpv6_destroy_sock",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:raw6_destroy",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_connect",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release",
        "net/strparser/strparser.c:strp_sock_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234628028,
      "name": "lock_sock_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void lock_sock_nested(struct sock * sk, int subclass)
```

```json
{
  "name": "lock_sock_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295267168,
      "name": "lock_sock_nested",
      "external": true,
      "loc": "net/core/sock.c:2938",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect",
        "security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:tun_detach_filter",
        "drivers/net/tun.c:tun_attach",
        "net/socket.c:sock_fasync",
        "net/core/sock.c:sk_wait_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/filter.c:sk_get_filter",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_update_elem",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/sock_map.c:sock_map_free",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_sendpage",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/datagram.c:ip4_datagram_connect",
        "net/ipv4/raw.c:raw_abort",
        "net/ipv4/raw.c:raw_destroy",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_abort",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_disconnect",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_sendpage",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/af_inet.c:inet_shutdown",
        "net/ipv4/af_inet.c:inet_accept",
        "net/ipv4/af_inet.c:inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_bind",
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_autobind",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/addrconf.c:ipv6_mc_config",
        "net/ipv6/udp.c:udpv6_destroy_sock",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:raw6_destroy",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_connect",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release",
        "net/strparser/strparser.c:strp_sock_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295267168,
      "name": "lock_sock_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void lock_sock_nested(struct sock * sk, int subclass)
```

```json
{
  "name": "lock_sock_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278197160,
      "name": "lock_sock_nested",
      "external": true,
      "loc": "net/core/sock.c:2938",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect",
        "security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt",
        "drivers/net/tun.c:tun_detach_filter",
        "drivers/net/tun.c:tun_attach",
        "net/socket.c:sock_fasync",
        "net/core/sock.c:sk_wait_data",
        "net/core/sock.c:sk_wait_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/filter.c:sk_get_filter",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_update_elem",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/sock_map.c:sock_map_free",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_sendpage",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/datagram.c:ip4_datagram_connect",
        "net/ipv4/raw.c:raw_abort",
        "net/ipv4/raw.c:raw_destroy",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_abort",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_disconnect",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_sendpage",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/af_inet.c:inet_shutdown",
        "net/ipv4/af_inet.c:inet_accept",
        "net/ipv4/af_inet.c:inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_bind",
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_autobind",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/addrconf.c:ipv6_mc_config",
        "net/ipv6/udp.c:udpv6_destroy_sock",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:raw6_destroy",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_connect",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release",
        "net/strparser/strparser.c:strp_sock_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278197160,
      "name": "lock_sock_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void lock_sock_nested(struct sock * sk, int subclass)
```

```json
{
  "name": "lock_sock_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587972144,
      "name": "lock_sock_nested",
      "external": true,
      "loc": "net/core/sock.c:2938",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect",
        "security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:tun_detach_filter",
        "drivers/net/tun.c:tun_attach",
        "net/socket.c:sock_fasync",
        "net/core/sock.c:sk_wait_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/filter.c:sk_get_filter",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_update_elem",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/sock_map.c:sock_map_free",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_sendpage",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/datagram.c:ip4_datagram_connect",
        "net/ipv4/raw.c:raw_abort",
        "net/ipv4/raw.c:raw_destroy",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_abort",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_disconnect",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_sendpage",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/devinet.c:ip_mc_config",
        "net/ipv4/af_inet.c:inet_shutdown",
        "net/ipv4/af_inet.c:inet_accept",
        "net/ipv4/af_inet.c:inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_bind",
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_autobind",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/addrconf.c:ipv6_mc_config",
        "net/ipv6/udp.c:udpv6_destroy_sock",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:raw6_destroy",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_connect",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release",
        "net/strparser/strparser.c:strp_sock_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587972144,
      "name": "lock_sock_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void lock_sock_nested(struct sock * sk, int subclass)
```

```json
{
  "name": "lock_sock_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587685248,
      "name": "lock_sock_nested",
      "external": true,
      "loc": "net/core/sock.c:2938",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect",
        "security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:tun_detach_filter",
        "drivers/net/tun.c:tun_attach",
        "drivers/net/vxlan.c:vxlan_stop",
        "drivers/net/vxlan.c:vxlan_stop",
        "drivers/net/vxlan.c:vxlan_open",
        "drivers/net/vxlan.c:vxlan_open",
        "net/socket.c:sock_fasync",
        "net/core/sock.c:sk_wait_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/filter.c:sk_get_filter",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_update_elem",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/sock_map.c:sock_map_free",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_sendpage",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/datagram.c:ip4_datagram_connect",
        "net/ipv4/raw.c:raw_abort",
        "net/ipv4/raw.c:raw_destroy",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_abort",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_disconnect",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_sendpage",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/devinet.c:ip_mc_config",
        "net/ipv4/af_inet.c:inet_shutdown",
        "net/ipv4/af_inet.c:inet_accept",
        "net/ipv4/af_inet.c:inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_bind",
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_autobind",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/addrconf.c:ipv6_mc_config",
        "net/ipv6/udp.c:udpv6_destroy_sock",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:raw6_destroy",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_connect",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release",
        "net/strparser/strparser.c:strp_sock_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587685248,
      "name": "lock_sock_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void lock_sock_nested(struct sock * sk, int subclass)
```

```json
{
  "name": "lock_sock_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588303920,
      "name": "lock_sock_nested",
      "external": true,
      "loc": "net/core/sock.c:2938",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect",
        "security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:tun_detach_filter",
        "drivers/net/tun.c:tun_attach",
        "net/socket.c:sock_fasync",
        "net/core/sock.c:sk_wait_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/filter.c:sk_get_filter",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_update_elem",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/sock_map.c:sock_map_free",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/netfilter/nf_conntrack_proto.c:ipv6_getorigdst",
        "net/netfilter/nf_conntrack_proto.c:getorigdst",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_sendpage",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/datagram.c:ip4_datagram_connect",
        "net/ipv4/raw.c:raw_abort",
        "net/ipv4/raw.c:raw_destroy",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_abort",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_disconnect",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_sendpage",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/devinet.c:ip_mc_config",
        "net/ipv4/af_inet.c:inet_shutdown",
        "net/ipv4/af_inet.c:inet_accept",
        "net/ipv4/af_inet.c:inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_bind",
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_autobind",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/addrconf.c:ipv6_mc_config",
        "net/ipv6/udp.c:udpv6_destroy_sock",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:raw6_destroy",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_connect",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release",
        "net/strparser/strparser.c:strp_sock_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588303920,
      "name": "lock_sock_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void lock_sock_nested(struct sock * sk, int subclass)
```

```json
{
  "name": "lock_sock_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588429936,
      "name": "lock_sock_nested",
      "external": true,
      "loc": "net/core/sock.c:2938",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect",
        "security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:tun_detach_filter",
        "drivers/net/tun.c:tun_attach",
        "net/socket.c:sock_fasync",
        "net/core/sock.c:sk_wait_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/filter.c:sk_get_filter",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_update_elem",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/sock_map.c:sock_map_free",
        "net/netlink/af_netlink.c:netlink_insert",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_sendpage",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/datagram.c:ip4_datagram_connect",
        "net/ipv4/raw.c:raw_abort",
        "net/ipv4/raw.c:raw_destroy",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_abort",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_disconnect",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_sendpage",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/devinet.c:ip_mc_config",
        "net/ipv4/af_inet.c:inet_shutdown",
        "net/ipv4/af_inet.c:inet_accept",
        "net/ipv4/af_inet.c:inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_bind",
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_autobind",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/addrconf.c:ipv6_mc_config",
        "net/ipv6/udp.c:udpv6_destroy_sock",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:raw6_destroy",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_connect",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release",
        "net/strparser/strparser.c:strp_sock_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588429936,
      "name": "lock_sock_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
