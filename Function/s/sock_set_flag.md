# Function: <code>sock_set_flag</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_set_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585062493,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:751",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586167266,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:751",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586187017,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:751",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_set_memalloc",
        "net/core/sock.c:sock_init_data",
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_enable_timestamp",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586504483,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:751",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586590154,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:751",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586597060,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:751",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_child_forget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586601207,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:751",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_init_sock",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586623757,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:751",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586666240,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:751",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_trim_head",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586695527,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:751",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586766627,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:751",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_sk_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586971050,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:751",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587256923,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:751",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_set_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585451549,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:753",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586587714,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:753",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586622282,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:753",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_enable_timestamp",
        "net/core/sock.c:sock_init_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sk_set_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586947286,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:753",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587033462,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:753",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587041255,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:753",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587056067,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:753",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_init_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587097533,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:753",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587128926,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:753",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_trim_head"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587144300,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:753",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587187052,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:753",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587214586,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:753",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_sk_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587418554,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:753",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587718687,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:753",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_set_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585655645,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:774",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586772082,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:774",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586806890,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:774",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_enable_timestamp",
        "net/core/sock.c:sock_init_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sk_set_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587142392,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:774",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587229584,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:774",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587237543,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:774",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587251991,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:774",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_init_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587295131,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:774",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587327390,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:774",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_trim_head"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587334825,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:774",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587387964,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:774",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587414954,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:774",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_sk_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587622042,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:774",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587933082,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:774",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_set_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585742132,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:788",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586894834,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:788",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586928682,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:788",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_enable_timestamp",
        "net/core/sock.c:sock_init_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sk_set_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587272489,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:788",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587361336,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:788",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587367943,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:788",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587383687,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:788",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_init_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587426027,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:788",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587459107,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:788",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587467912,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:788",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587527385,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:788",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587551578,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:788",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587770156,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:788",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588091448,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:788",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_set_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586175844,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:788",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587386242,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:788",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587421427,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:788",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_enable_timestamp",
        "net/core/sock.c:sock_init_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sk_set_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587792508,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:788",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587881384,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:788",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587888125,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:788",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587915237,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:788",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_init_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587946251,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:788",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587980991,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:788",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587997004,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:788",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588050233,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:788",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588075164,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:788",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588301048,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:788",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588636049,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:788",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_set_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586430070,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:795",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587689266,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:795",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587725507,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:795",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_enable_timestamp",
        "net/core/sock.c:sock_init_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sk_set_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588135070,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:795",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588228043,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:795",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588236381,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:795",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588263557,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:795",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_init_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588296075,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:795",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588331263,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:795",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588343772,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:795",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588407089,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:795",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588428408,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:795",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588651303,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:795",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588937271,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:795",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589009871,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:795",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589117942,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:795",
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
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_set_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586575792,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:823",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_open",
        "drivers/net/tun.c:tun_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587821554,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:823",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587857827,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:823",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_enable_timestamp",
        "net/core/sock.c:sock_init_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sk_set_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588317803,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:823",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588415035,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:823",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588421981,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:823",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588451797,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:823",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_init_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588484827,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:823",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588520412,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:823",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588533260,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:823",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588599089,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:823",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588620392,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:823",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588867207,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:823",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589160654,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:823",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589236143,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:823",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589351678,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:823",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_create",
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
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_set_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586827750,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:826",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_open",
        "drivers/net/tun.c:tun_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588124750,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:826",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588162390,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:826",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_enable_timestamp",
        "net/core/sock.c:sock_init_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sk_set_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588716184,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:826",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588818800,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:826",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588827710,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:826",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588857093,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:826",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_init_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588892171,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:826",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588930692,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:826",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588943933,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:826",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589010685,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:826",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589032225,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:826",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589307049,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:826",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589616449,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:826",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589695721,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:826",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589807708,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:826",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_create",
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
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_set_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586973830,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_open",
        "drivers/net/tun.c:tun_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588329518,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588367670,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_enable_timestamp",
        "net/core/sock.c:sock_init_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sk_set_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588940040,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589042137,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589049134,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589080661,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_init_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589116251,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589154673,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589168365,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589235331,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589256737,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589531433,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589840689,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589917177,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590031340,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_create",
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
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_set_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587801446,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:873",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589190174,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:873",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589227734,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:873",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_init_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_set_keepalive",
        "net/core/sock.c:sock_enable_timestamps",
        "net/core/sock.c:sock_enable_timestamps",
        "net/core/sock.c:sock_no_linger",
        "net/core/sock.c:sk_set_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589830792,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:873",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590003499,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:873",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590011438,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:873",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590045033,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:873",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_init_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590086923,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:873",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590123915,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:873",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans",
        "net/ipv4/tcp_output.c:tcp_trim_head"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590136702,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:873",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590210874,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:873",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590231041,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:873",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590532712,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:873",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590867396,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:873",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590950383,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:873",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591063404,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:873",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_create",
        "net/xdp/xsk.c:xsk_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591075767,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:873",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_listen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591096104,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:873",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:mptcp_sock_destruct"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_set_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587859302,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:879",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_open",
        "drivers/net/tun.c:tun_xdp",
        "drivers/net/tun.c:tun_xdp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589188622,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:879",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589225734,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:879",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_init_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_set_keepalive",
        "net/core/sock.c:sock_enable_timestamps",
        "net/core/sock.c:sock_enable_timestamps",
        "net/core/sock.c:sock_no_linger",
        "net/core/sock.c:sk_set_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589506590,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:879",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:_bpf_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589867240,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:879",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590046059,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:879",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590054014,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:879",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590085421,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:879",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:tcp_init_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590132859,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:879",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590184206,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:879",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590261530,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:879",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590282737,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:879",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590592632,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:879",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590928288,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:879",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591011769,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:879",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591125676,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:879",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_create",
        "net/xdp/xsk.c:xsk_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591140853,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:879",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:__mptcp_close_ssk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591172801,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:879",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:mptcp_sock_destruct"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_set_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587738278,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:879",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_open",
        "drivers/net/tun.c:tun_xdp",
        "drivers/net/tun.c:tun_xdp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589082722,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:879",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589117750,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:879",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_init_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_set_keepalive",
        "net/core/sock.c:sock_enable_timestamps",
        "net/core/sock.c:sock_enable_timestamps",
        "net/core/sock.c:sock_no_linger",
        "net/core/sock.c:sk_set_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589404667,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:879",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:_bpf_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589773240,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:879",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589960427,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:879",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589968478,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:879",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590000167,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:879",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:tcp_init_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590047115,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:879",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590098510,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:879",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590158631,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:879",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_destroy_sock",
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590197377,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:879",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590517688,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:879",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590726725,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:879",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_destroy_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590857808,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:879",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590941992,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:879",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591061020,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:879",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_create",
        "net/xdp/xsk.c:xsk_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591072213,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:879",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:__mptcp_close_ssk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591109642,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:879",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:mptcp_sock_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591149673,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:879",
      "file": "net/mptcp/sockopt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/sockopt.c:sync_socket_options",
        "net/mptcp/sockopt.c:sync_socket_options",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_set_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588334246,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:891",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_open",
        "drivers/net/tun.c:tun_xdp",
        "drivers/net/tun.c:tun_xdp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589801714,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:891",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589836182,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:891",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_enable_timestamp",
        "net/core/sock.c:sock_init_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_set_keepalive",
        "net/core/sock.c:sock_set_timestamping",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_enable_timestamps",
        "net/core/sock.c:sock_enable_timestamps",
        "net/core/sock.c:sock_no_linger",
        "net/core/sock.c:sk_set_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590171500,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:891",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:_bpf_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590532550,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:891",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590727512,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:891",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590735998,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:891",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590770631,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:891",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:tcp_init_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590820459,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:891",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590873187,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:891",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590939047,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:891",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_destroy_sock",
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590978853,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:891",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591325928,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:891",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591539973,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:891",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_destroy_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591687516,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:891",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591777848,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:891",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591903596,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:891",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_create",
        "net/xdp/xsk.c:xsk_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591923253,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:891",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:__mptcp_close_ssk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591954030,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:891",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:mptcp_sock_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592000521,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:891",
      "file": "net/mptcp/sockopt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/sockopt.c:sync_socket_options",
        "net/mptcp/sockopt.c:sync_socket_options",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_set_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589729156,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:931",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_open",
        "drivers/net/tun.c:tun_xdp",
        "drivers/net/tun.c:tun_xdp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591319411,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:931",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591362179,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:931",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_gettstamp",
        "net/core/sock.c:sock_init_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_set_keepalive",
        "net/core/sock.c:sock_set_timestamping",
        "net/core/sock.c:sock_set_timestamping",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_enable_timestamps",
        "net/core/sock.c:sock_enable_timestamps",
        "net/core/sock.c:sock_enable_timestamps",
        "net/core/sock.c:sock_no_linger",
        "net/core/sock.c:sk_set_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591734399,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:931",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:_bpf_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592141037,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:931",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592356640,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:931",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592366061,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:931",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592403583,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:931",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:tcp_init_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592455131,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:931",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617430237,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:931",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592565110,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:931",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_hash_sk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592582759,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:931",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_destroy_sock",
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617431896,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:931",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592753620,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:931",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592994585,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:931",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593229364,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:931",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_destroy_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593384524,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:931",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593481160,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:931",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593622044,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:931",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_create",
        "net/xdp/xsk.c:xsk_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593646565,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:931",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:__mptcp_close_ssk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593681688,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:931",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:mptcp_sock_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593734796,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:931",
      "file": "net/mptcp/sockopt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/sockopt.c:sync_socket_options",
        "net/mptcp/sockopt.c:sync_socket_options",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593753145,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:931",
      "file": "net/mctp/af_mctp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mctp/af_mctp.c:mctp_pf_create"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void sock_set_flag(struct sock * sk, enum sock_flags flag)
```

```json
{
  "name": "sock_set_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591347917,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:969",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_open",
        "drivers/net/tun.c:tun_xdp",
        "drivers/net/tun.c:tun_xdp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593078323,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:969",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593116707,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:969",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_init_data_uid",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sock_set_keepalive",
        "net/core/sock.c:sock_set_timestamping",
        "net/core/sock.c:sock_no_linger",
        "net/core/sock.c:sk_set_memalloc"
      ],
      "caller_func": [
        "net/core/sock.c:sk_setsockopt"
      ]
    },
    {
      "addr": 18446744071593965245,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:969",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594197001,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:969",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594212413,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:969",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594251487,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:969",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:tcp_init_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594309403,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:969",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071628188573,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:969",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594428806,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:969",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_hash_sk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594445383,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:969",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_destroy_sock",
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071628190705,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:969",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594625556,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:969",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594883093,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:969",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595129940,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:969",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595293692,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:969",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595392328,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:969",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595551180,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:969",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_create",
        "net/xdp/xsk.c:xsk_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595600709,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:969",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:__mptcp_close",
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/protocol.c:__mptcp_close_ssk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595619613,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:969",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595673996,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:969",
      "file": "net/mptcp/sockopt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/sockopt.c:sync_socket_options",
        "net/mptcp/sockopt.c:sync_socket_options",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595691156,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:969",
      "file": "net/mctp/af_mctp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mctp/af_mctp.c:mctp_pf_create",
        "net/mctp/af_mctp.c:mctp_sk_unhash"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593101104,
      "name": "sock_set_flag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
void sock_set_flag(struct sock * sk, enum sock_flags flag)
```

```json
{
  "name": "sock_set_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591709360,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:971",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_open",
        "drivers/net/tun.c:tun_xdp",
        "drivers/net/tun.c:tun_xdp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593529902,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:971",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593569395,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:971",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_init_data_uid",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sock_set_keepalive",
        "net/core/sock.c:sock_set_timestamping",
        "net/core/sock.c:sock_no_linger",
        "net/core/sock.c:sk_set_memalloc"
      ],
      "caller_func": [
        "net/core/sock.c:sk_setsockopt"
      ]
    },
    {
      "addr": 18446744071594342141,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:971",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594584153,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:971",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594599549,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:971",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594638191,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:971",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:tcp_init_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594695668,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:971",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619957165,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:971",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594818669,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:971",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_hash_sk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594835143,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:971",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_destroy_sock",
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619959297,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:971",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595017633,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:971",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595275708,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:971",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595524356,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:971",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595688532,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:971",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595789548,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:971",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596059388,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:971",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_create",
        "net/xdp/xsk.c:xsk_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596092300,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:971",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:__mptcp_close",
        "net/mptcp/protocol.c:__mptcp_unaccepted_force_close",
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/protocol.c:__mptcp_close_ssk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596127800,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:971",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596184289,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:971",
      "file": "net/mptcp/sockopt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/sockopt.c:sync_socket_options",
        "net/mptcp/sockopt.c:sync_socket_options",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596201220,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:971",
      "file": "net/mctp/af_mctp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mctp/af_mctp.c:mctp_pf_create",
        "net/mctp/af_mctp.c:mctp_sk_unhash"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593553312,
      "name": "sock_set_flag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
void sock_set_flag(struct sock * sk, enum sock_flags flag)
```

```json
{
  "name": "sock_set_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592453648,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:942",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_open",
        "drivers/net/tun.c:tun_xdp",
        "drivers/net/tun.c:tun_xdp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594301742,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:942",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594341987,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:942",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_init_data_uid",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sock_set_keepalive",
        "net/core/sock.c:sock_set_timestamping",
        "net/core/sock.c:sock_no_linger",
        "net/core/sock.c:sk_set_memalloc"
      ],
      "caller_func": [
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt"
      ]
    },
    {
      "addr": 18446744071595141693,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:942",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595388078,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:942",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595403117,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:942",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595441503,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:942",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:tcp_init_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595500228,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:942",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622268781,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:942",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595629965,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:942",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_hash_sk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595645319,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:942",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_destroy_sock",
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622271089,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:942",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595830513,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:942",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596116396,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:942",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596368708,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:942",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596536292,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:942",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596640044,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:942",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596925452,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:942",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_create",
        "net/xdp/xsk.c:xsk_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596980384,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:942",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:__mptcp_close",
        "net/mptcp/protocol.c:__mptcp_unaccepted_force_close",
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/protocol.c:__mptcp_close_ssk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597001737,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:942",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597060193,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:942",
      "file": "net/mptcp/sockopt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597078980,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:942",
      "file": "net/mctp/af_mctp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mctp/af_mctp.c:mctp_pf_create",
        "net/mctp/af_mctp.c:mctp_sk_unhash"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594325648,
      "name": "sock_set_flag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "sock_set_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499965316,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501824964,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501877360,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_enable_timestamp",
        "net/core/sock.c:sock_init_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sk_set_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502538352,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502652772,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502659372,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502697052,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_init_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502732124,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502770664,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502784068,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502853576,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502884780,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503202180,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503551988,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503641128,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503781036,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_create",
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
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "sock_set_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232505000,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_open",
        "drivers/net/tun.c:tun_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 3234607352,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 3234641400,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_enable_timestamp",
        "net/core/sock.c:sock_init_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sk_set_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3235246544,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_release"
      ],
      "caller_func": []
    },
    {
      "addr": 3235356716,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 3235364400,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close"
      ],
      "caller_func": []
    },
    {
      "addr": 3235398388,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_init_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 3235435904,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 3235475256,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3235492584,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235546864,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 3235579472,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235873340,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 3236204384,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 3236283460,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 3236401328,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_create",
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
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "sock_set_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293293288,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_open",
        "drivers/net/tun.c:tun_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295225236,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295284124,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_enable_timestamp",
        "net/core/sock.c:sock_init_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sk_set_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296112500,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_release"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296254772,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296265248,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296308484,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_init_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296354252,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296403664,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296425128,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055296507964,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296545432,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055296934192,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297352984,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297466112,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297623736,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_create",
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
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "sock_set_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277044446,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_open",
        "drivers/net/tun.c:tun_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278170408,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278199430,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_enable_timestamp",
        "net/core/sock.c:sock_init_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sk_set_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278703384,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278793300,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278798980,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278826568,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_init_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278858004,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278892266,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278908038,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278966306,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278984630,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279237646,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279516110,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279586248,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279691410,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_create",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_set_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586730838,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_open",
        "drivers/net/tun.c:tun_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587936302,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587974454,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_enable_timestamp",
        "net/core/sock.c:sock_init_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sk_set_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588546424,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588648521,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588655518,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588687045,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_init_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588722635,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588761057,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588774749,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588841715,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588862913,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589135801,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589445057,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589521545,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589634940,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_create",
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
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_set_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586598054,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_open",
        "drivers/net/tun.c:tun_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587649406,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587687558,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_enable_timestamp",
        "net/core/sock.c:sock_init_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sk_set_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588258408,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588360505,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588367502,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588399029,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_init_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588434619,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588472993,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588486685,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588553651,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588574849,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588860793,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589170049,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589247609,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589359468,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_create",
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
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_set_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586928390,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_open",
        "drivers/net/tun.c:tun_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588268078,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588306230,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_enable_timestamp",
        "net/core/sock.c:sock_init_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sk_set_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588878600,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589084697,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589091694,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589123221,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_init_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589158811,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589197233,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589210925,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589277891,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589299297,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589572665,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589881921,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589962809,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590076972,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_create",
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
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_set_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587035366,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_open",
        "drivers/net/tun.c:tun_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588403246,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_fasync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588441446,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:sock_enable_timestamp",
        "net/core/sock.c:sock_init_data",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sk_set_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589020664,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589124207,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589131342,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589163045,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_init_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589198747,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589237345,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589252173,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589312910,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589341057,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589627927,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_release_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589934081,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590015355,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590126412,
      "name": "sock_set_flag",
      "external": false,
      "loc": "include/net/sock.h:831",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_create",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void sock_set_flag(struct sock * sk, enum sock_flags flag)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
