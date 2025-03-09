# Function: <code>l3mdev_master_ifindex_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int l3mdev_master_ifindex_rcu(struct net_device * dev)
```

```json
{
  "name": "l3mdev_master_ifindex_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587327632,
      "name": "l3mdev_master_ifindex_rcu",
      "external": true,
      "loc": "net/l3mdev/l3mdev.c:20",
      "file": "net/l3mdev/l3mdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/icmp.c:icmp_route_lookup",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/xfrm4_policy.c:_decode_session4",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_flow",
        "net/ipv6/route.c:ip6_route_input",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/xfrm6_policy.c:_decode_session6"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587327632,
      "name": "l3mdev_master_ifindex_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int l3mdev_master_ifindex_rcu(const struct net_device * dev)
```

```json
{
  "name": "l3mdev_master_ifindex_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587806080,
      "name": "l3mdev_master_ifindex_rcu",
      "external": true,
      "loc": "net/l3mdev/l3mdev.c:21",
      "file": "net/l3mdev/l3mdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__ip_route_output_key_hash",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/icmp.c:icmp_route_lookup",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/xfrm4_policy.c:_decode_session4",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_flow",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_route_input",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/xfrm6_policy.c:_decode_session6",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587806080,
      "name": "l3mdev_master_ifindex_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int l3mdev_master_ifindex_rcu(const struct net_device * dev)
```

```json
{
  "name": "l3mdev_master_ifindex_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588019504,
      "name": "l3mdev_master_ifindex_rcu",
      "external": true,
      "loc": "net/l3mdev/l3mdev.c:21",
      "file": "net/l3mdev/l3mdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/icmp.c:icmp_route_lookup",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588019504,
      "name": "l3mdev_master_ifindex_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int l3mdev_master_ifindex_rcu(const struct net_device * dev)
```

```json
{
  "name": "l3mdev_master_ifindex_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588177568,
      "name": "l3mdev_master_ifindex_rcu",
      "external": true,
      "loc": "net/l3mdev/l3mdev.c:21",
      "file": "net/l3mdev/l3mdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588177568,
      "name": "l3mdev_master_ifindex_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int l3mdev_master_ifindex_rcu(const struct net_device * dev)
```

```json
{
  "name": "l3mdev_master_ifindex_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588723520,
      "name": "l3mdev_master_ifindex_rcu",
      "external": true,
      "loc": "net/l3mdev/l3mdev.c:21",
      "file": "net/l3mdev/l3mdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_validate_source",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588723520,
      "name": "l3mdev_master_ifindex_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int l3mdev_master_ifindex_rcu(const struct net_device * dev)
```

```json
{
  "name": "l3mdev_master_ifindex_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589090768,
      "name": "l3mdev_master_ifindex_rcu",
      "external": true,
      "loc": "net/l3mdev/l3mdev.c:21",
      "file": "net/l3mdev/l3mdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589090768,
      "name": "l3mdev_master_ifindex_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int l3mdev_master_ifindex_rcu(const struct net_device * dev)
```

```json
{
  "name": "l3mdev_master_ifindex_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589317760,
      "name": "l3mdev_master_ifindex_rcu",
      "external": true,
      "loc": "net/l3mdev/l3mdev.c:21",
      "file": "net/l3mdev/l3mdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_info_nh_uses_dev",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589317760,
      "name": "l3mdev_master_ifindex_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int l3mdev_master_ifindex_rcu(const struct net_device * dev)
```

```json
{
  "name": "l3mdev_master_ifindex_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589773056,
      "name": "l3mdev_master_ifindex_rcu",
      "external": true,
      "loc": "net/l3mdev/l3mdev.c:17",
      "file": "net/l3mdev/l3mdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_info_nh_uses_dev",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589773056,
      "name": "l3mdev_master_ifindex_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int l3mdev_master_ifindex_rcu(const struct net_device * dev)
```

```json
{
  "name": "l3mdev_master_ifindex_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589996736,
      "name": "l3mdev_master_ifindex_rcu",
      "external": true,
      "loc": "net/l3mdev/l3mdev.c:17",
      "file": "net/l3mdev/l3mdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_info_nh_uses_dev",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589996736,
      "name": "l3mdev_master_ifindex_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int l3mdev_master_ifindex_rcu(const struct net_device * dev)
```

```json
{
  "name": "l3mdev_master_ifindex_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591027630,
      "name": "l3mdev_master_ifindex_rcu",
      "external": true,
      "loc": "net/l3mdev/l3mdev.c:17",
      "file": "net/l3mdev/l3mdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow"
      ],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_find_open_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_lookup",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591027360,
      "name": "l3mdev_master_ifindex_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int l3mdev_master_ifindex_rcu(const struct net_device * dev)
```

```json
{
  "name": "l3mdev_master_ifindex_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591091619,
      "name": "l3mdev_master_ifindex_rcu",
      "external": true,
      "loc": "net/l3mdev/l3mdev.c:110",
      "file": "net/l3mdev/l3mdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow"
      ],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_find_open_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591091056,
      "name": "l3mdev_master_ifindex_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int l3mdev_master_ifindex_rcu(const struct net_device * dev)
```

```json
{
  "name": "l3mdev_master_ifindex_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591022339,
      "name": "l3mdev_master_ifindex_rcu",
      "external": true,
      "loc": "net/l3mdev/l3mdev.c:110",
      "file": "net/l3mdev/l3mdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow"
      ],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_find_open_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_reply",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591021776,
      "name": "l3mdev_master_ifindex_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int l3mdev_master_ifindex_rcu(const struct net_device * dev)
```

```json
{
  "name": "l3mdev_master_ifindex_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591863331,
      "name": "l3mdev_master_ifindex_rcu",
      "external": true,
      "loc": "net/l3mdev/l3mdev.c:110",
      "file": "net/l3mdev/l3mdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow"
      ],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_find_open_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_reply",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591862768,
      "name": "l3mdev_master_ifindex_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int l3mdev_master_ifindex_rcu(const struct net_device * dev)
```

```json
{
  "name": "l3mdev_master_ifindex_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593581280,
      "name": "l3mdev_master_ifindex_rcu",
      "external": true,
      "loc": "net/l3mdev/l3mdev.c:110",
      "file": "net/l3mdev/l3mdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow"
      ],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_reply",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593580608,
      "name": "l3mdev_master_ifindex_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int l3mdev_master_ifindex_rcu(const struct net_device * dev)
```

```json
{
  "name": "l3mdev_master_ifindex_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595507216,
      "name": "l3mdev_master_ifindex_rcu",
      "external": true,
      "loc": "net/l3mdev/l3mdev.c:110",
      "file": "net/l3mdev/l3mdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow"
      ],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_reply",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_lookup",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595506464,
      "name": "l3mdev_master_ifindex_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int l3mdev_master_ifindex_rcu(const struct net_device * dev)
```

```json
{
  "name": "l3mdev_master_ifindex_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596015920,
      "name": "l3mdev_master_ifindex_rcu",
      "external": true,
      "loc": "net/l3mdev/l3mdev.c:110",
      "file": "net/l3mdev/l3mdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow"
      ],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_reply",
        "net/ipv4/icmp.c:icmpv4_xrlim_allow",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596015168,
      "name": "l3mdev_master_ifindex_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int l3mdev_master_ifindex_rcu(const struct net_device * dev)
```

```json
{
  "name": "l3mdev_master_ifindex_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596879953,
      "name": "l3mdev_master_ifindex_rcu",
      "external": true,
      "loc": "net/l3mdev/l3mdev.c:110",
      "file": "net/l3mdev/l3mdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow"
      ],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_reply",
        "net/ipv4/icmp.c:icmpv4_xrlim_allow",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup",
        "net/ipv4/tcp_ao.c:tcp_ao_copy_all_matching",
        "net/ipv4/tcp_ao.c:tcp_ao_connect_init",
        "net/ipv4/tcp_ao.c:tcp_ao_syncookie",
        "net/ipv4/tcp_ao.c:tcp_v4_ao_lookup",
        "net/ipv4/tcp_ao.c:tcp_v4_ao_lookup_rsk",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/ipv6/tcp_ao.c:tcp_v6_ao_lookup_rsk",
        "net/ipv6/tcp_ao.c:tcp_v6_ao_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596879232,
      "name": "l3mdev_master_ifindex_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int l3mdev_master_ifindex_rcu(const struct net_device * dev)
```

```json
{
  "name": "l3mdev_master_ifindex_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503739152,
      "name": "l3mdev_master_ifindex_rcu",
      "external": true,
      "loc": "net/l3mdev/l3mdev.c:17",
      "file": "net/l3mdev/l3mdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_info_nh_uses_dev",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503739152,
      "name": "l3mdev_master_ifindex_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int l3mdev_master_ifindex_rcu(const struct net_device * dev)
```

```json
{
  "name": "l3mdev_master_ifindex_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236368116,
      "name": "l3mdev_master_ifindex_rcu",
      "external": true,
      "loc": "net/l3mdev/l3mdev.c:17",
      "file": "net/l3mdev/l3mdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_info_nh_uses_dev",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236368116,
      "name": "l3mdev_master_ifindex_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int l3mdev_master_ifindex_rcu(const struct net_device * dev)
```

```json
{
  "name": "l3mdev_master_ifindex_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297579152,
      "name": "l3mdev_master_ifindex_rcu",
      "external": true,
      "loc": "net/l3mdev/l3mdev.c:17",
      "file": "net/l3mdev/l3mdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_info_nh_uses_dev",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297579152,
      "name": "l3mdev_master_ifindex_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int l3mdev_master_ifindex_rcu(const struct net_device * dev)
```

```json
{
  "name": "l3mdev_master_ifindex_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279659246,
      "name": "l3mdev_master_ifindex_rcu",
      "external": true,
      "loc": "net/l3mdev/l3mdev.c:17",
      "file": "net/l3mdev/l3mdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_info_nh_uses_dev",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279659246,
      "name": "l3mdev_master_ifindex_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int l3mdev_master_ifindex_rcu(const struct net_device * dev)
```

```json
{
  "name": "l3mdev_master_ifindex_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589600336,
      "name": "l3mdev_master_ifindex_rcu",
      "external": true,
      "loc": "net/l3mdev/l3mdev.c:17",
      "file": "net/l3mdev/l3mdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_info_nh_uses_dev",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589600336,
      "name": "l3mdev_master_ifindex_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int l3mdev_master_ifindex_rcu(const struct net_device * dev)
```

```json
{
  "name": "l3mdev_master_ifindex_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589324864,
      "name": "l3mdev_master_ifindex_rcu",
      "external": true,
      "loc": "net/l3mdev/l3mdev.c:17",
      "file": "net/l3mdev/l3mdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_info_nh_uses_dev",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589324864,
      "name": "l3mdev_master_ifindex_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int l3mdev_master_ifindex_rcu(const struct net_device * dev)
```

```json
{
  "name": "l3mdev_master_ifindex_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590042368,
      "name": "l3mdev_master_ifindex_rcu",
      "external": true,
      "loc": "net/l3mdev/l3mdev.c:17",
      "file": "net/l3mdev/l3mdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_info_nh_uses_dev",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590042368,
      "name": "l3mdev_master_ifindex_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int l3mdev_master_ifindex_rcu(const struct net_device * dev)
```

```json
{
  "name": "l3mdev_master_ifindex_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590092400,
      "name": "l3mdev_master_ifindex_rcu",
      "external": true,
      "loc": "net/l3mdev/l3mdev.c:17",
      "file": "net/l3mdev/l3mdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:fib_info_nh_uses_dev",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590092400,
      "name": "l3mdev_master_ifindex_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct net_device * dev</code> ➡️ <code>const struct net_device * dev</code>
</li>
</ul>
</details>
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
