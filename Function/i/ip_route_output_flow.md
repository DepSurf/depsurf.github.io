# Function: <code>ip_route_output_flow</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct rtable * ip_route_output_flow(struct net * net, struct flowi4 * flp4, const struct sock * sk)
```

```json
{
  "name": "ip_route_output_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586541072,
      "name": "ip_route_output_flow",
      "external": true,
      "loc": "net/ipv4/route.c:2382",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/ip_output.c:ip_queue_xmit",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_req",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_route_lookup",
        "net/ipv4/igmp.c:ip_mc_find_dev",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:nf_ip_route",
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586541072,
      "name": "ip_route_output_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
struct rtable * ip_route_output_flow(struct net * net, struct flowi4 * flp4, const struct sock * sk)
```

```json
{
  "name": "ip_route_output_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586984112,
      "name": "ip_route_output_flow",
      "external": true,
      "loc": "net/ipv4/route.c:2405",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/ip_output.c:ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_req",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_route_lookup",
        "net/ipv4/igmp.c:ip_mc_find_dev",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:nf_ip_route",
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586984112,
      "name": "ip_route_output_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
struct rtable * ip_route_output_flow(struct net * net, struct flowi4 * flp4, const struct sock * sk)
```

```json
{
  "name": "ip_route_output_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587174448,
      "name": "ip_route_output_flow",
      "external": true,
      "loc": "net/ipv4/route.c:2440",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/ip_output.c:ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_req",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_route_lookup",
        "net/ipv4/igmp.c:ip_mc_find_dev",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:nf_ip_route",
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587174448,
      "name": "ip_route_output_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
struct rtable * ip_route_output_flow(struct net * net, struct flowi4 * flp4, const struct sock * sk)
```

```json
{
  "name": "ip_route_output_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587311808,
      "name": "ip_route_output_flow",
      "external": true,
      "loc": "net/ipv4/route.c:2534",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/ip_output.c:ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_req",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/igmp.c:ip_mc_find_dev",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:nf_ip_route",
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587311808,
      "name": "ip_route_output_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
struct rtable * ip_route_output_flow(struct net * net, struct flowi4 * flp4, const struct sock * sk)
```

```json
{
  "name": "ip_route_output_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587833600,
      "name": "ip_route_output_flow",
      "external": true,
      "loc": "net/ipv4/route.c:2555",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/ip_output.c:ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_req",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/igmp.c:ip_mc_find_dev",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:nf_ip_route",
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587833600,
      "name": "ip_route_output_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
struct rtable * ip_route_output_flow(struct net * net, struct flowi4 * flp4, const struct sock * sk)
```

```json
{
  "name": "ip_route_output_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588177600,
      "name": "ip_route_output_flow",
      "external": true,
      "loc": "net/ipv4/route.c:2579",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/ip_output.c:ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_req",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/igmp.c:ip_mc_find_dev",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:nf_ip_route",
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588177600,
      "name": "ip_route_output_flow",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct rtable * ip_route_output_flow(struct net * net, struct flowi4 * flp4, const struct sock * sk)
```

```json
{
  "name": "ip_route_output_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588361488,
      "name": "ip_route_output_flow",
      "external": true,
      "loc": "net/ipv4/route.c:2581",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_req",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/igmp.c:ip_mc_find_dev",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:nf_ip_route",
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588361488,
      "name": "ip_route_output_flow",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct rtable * ip_route_output_flow(struct net * net, struct flowi4 * flp4, const struct sock * sk)
```

```json
{
  "name": "ip_route_output_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588764496,
      "name": "ip_route_output_flow",
      "external": true,
      "loc": "net/ipv4/route.c:2711",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_req",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/igmp.c:ip_mc_find_dev",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:nf_ip_route",
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588764496,
      "name": "ip_route_output_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct rtable * ip_route_output_flow(struct net * net, struct flowi4 * flp4, const struct sock * sk)
```

```json
{
  "name": "ip_route_output_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588988256,
      "name": "ip_route_output_flow",
      "external": true,
      "loc": "net/ipv4/route.c:2720",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_req",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/igmp.c:ip_mc_find_dev",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:nf_ip_route",
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588988256,
      "name": "ip_route_output_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct rtable * ip_route_output_flow(struct net * net, struct flowi4 * flp4, const struct sock * sk)
```

```json
{
  "name": "ip_route_output_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589947888,
      "name": "ip_route_output_flow",
      "external": true,
      "loc": "net/ipv4/route.c:2759",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/ipv4/route.c:ip_route_output_tunnel",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_req",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/af_inet.c:inet_sk_reselect_saddr",
        "net/ipv4/igmp.c:ip_mc_find_dev",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:nf_ip_route",
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589947888,
      "name": "ip_route_output_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
struct rtable * ip_route_output_flow(struct net * net, struct flowi4 * flp4, const struct sock * sk)
```

```json
{
  "name": "ip_route_output_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589989024,
      "name": "ip_route_output_flow",
      "external": true,
      "loc": "net/ipv4/route.c:2736",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_redirect_neigh",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/ipv4/route.c:ip_route_output_tunnel",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_req",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/af_inet.c:inet_sk_reselect_saddr",
        "net/ipv4/igmp.c:ip_mc_find_dev",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:nf_ip_route",
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589989024,
      "name": "ip_route_output_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
struct rtable * ip_route_output_flow(struct net * net, struct flowi4 * flp4, const struct sock * sk)
```

```json
{
  "name": "ip_route_output_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589902800,
      "name": "ip_route_output_flow",
      "external": true,
      "loc": "net/ipv4/route.c:2737",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_redirect_neigh",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/ipv4/route.c:ip_route_output_tunnel",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_req",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_reply",
        "net/ipv4/igmp.c:ip_mc_find_dev",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:nf_ip_route",
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589902800,
      "name": "ip_route_output_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
struct rtable * ip_route_output_flow(struct net * net, struct flowi4 * flp4, const struct sock * sk)
```

```json
{
  "name": "ip_route_output_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590668640,
      "name": "ip_route_output_flow",
      "external": true,
      "loc": "net/ipv4/route.c:2855",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_redirect_neigh",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/ipv4/route.c:ip_route_output_tunnel",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_req",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_reply",
        "net/ipv4/igmp.c:ip_mc_find_dev",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:nf_ip_route",
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590668640,
      "name": "ip_route_output_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
struct rtable * ip_route_output_flow(struct net * net, struct flowi4 * flp4, const struct sock * sk)
```

```json
{
  "name": "ip_route_output_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592294864,
      "name": "ip_route_output_flow",
      "external": true,
      "loc": "net/ipv4/route.c:2879",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_redirect_neigh",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/ipv4/route.c:ip_route_output_tunnel",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_req",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_reply",
        "net/ipv4/af_inet.c:inet_sk_rebuild_header",
        "net/ipv4/igmp.c:ip_mc_find_dev",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:nf_ip_route",
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592294864,
      "name": "ip_route_output_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
struct rtable * ip_route_output_flow(struct net * net, struct flowi4 * flp4, const struct sock * sk)
```

```json
{
  "name": "ip_route_output_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594130416,
      "name": "ip_route_output_flow",
      "external": true,
      "loc": "net/ipv4/route.c:2870",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_redirect_neigh",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/ipv4/route.c:ip_route_output_tunnel",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_req",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_reply",
        "net/ipv4/af_inet.c:inet_sk_rebuild_header",
        "net/ipv4/igmp.c:ip_mc_find_dev",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:nf_ip_route",
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594130416,
      "name": "ip_route_output_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
struct rtable * ip_route_output_flow(struct net * net, struct flowi4 * flp4, const struct sock * sk)
```

```json
{
  "name": "ip_route_output_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594517408,
      "name": "ip_route_output_flow",
      "external": true,
      "loc": "net/ipv4/route.c:2866",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_redirect_neigh",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/ipv4/route.c:ip_route_output_tunnel",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_req",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_reply",
        "net/ipv4/af_inet.c:inet_sk_rebuild_header",
        "net/ipv4/igmp.c:ip_mc_find_dev",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:nf_ip_route",
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594517408,
      "name": "ip_route_output_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
struct rtable * ip_route_output_flow(struct net * net, struct flowi4 * flp4, const struct sock * sk)
```

```json
{
  "name": "ip_route_output_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595320576,
      "name": "ip_route_output_flow",
      "external": true,
      "loc": "net/ipv4/route.c:2869",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_redirect_neigh",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_req",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_reply",
        "net/ipv4/af_inet.c:inet_sk_rebuild_header",
        "net/ipv4/igmp.c:ip_mc_find_dev",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:nf_ip_route",
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595320576,
      "name": "ip_route_output_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
struct rtable * ip_route_output_flow(struct net * net, struct flowi4 * flp4, const struct sock * sk)
```

```json
{
  "name": "ip_route_output_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502593128,
      "name": "ip_route_output_flow",
      "external": true,
      "loc": "net/ipv4/route.c:2720",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_req",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/igmp.c:ip_mc_find_dev",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:nf_ip_route",
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502593128,
      "name": "ip_route_output_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
struct rtable * ip_route_output_flow(struct net * net, struct flowi4 * flp4, const struct sock * sk)
```

```json
{
  "name": "ip_route_output_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235298692,
      "name": "ip_route_output_flow",
      "external": true,
      "loc": "net/ipv4/route.c:2720",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_req",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/igmp.c:ip_mc_find_dev",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:nf_ip_route",
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235298692,
      "name": "ip_route_output_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
struct rtable * ip_route_output_flow(struct net * net, struct flowi4 * flp4, const struct sock * sk)
```

```json
{
  "name": "ip_route_output_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296183024,
      "name": "ip_route_output_flow",
      "external": true,
      "loc": "net/ipv4/route.c:2720",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_req",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/igmp.c:ip_mc_find_dev",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:nf_ip_route",
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296183024,
      "name": "ip_route_output_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
struct rtable * ip_route_output_flow(struct net * net, struct flowi4 * flp4, const struct sock * sk)
```

```json
{
  "name": "ip_route_output_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278746582,
      "name": "ip_route_output_flow",
      "external": true,
      "loc": "net/ipv4/route.c:2720",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_req",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/igmp.c:ip_mc_find_dev",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:nf_ip_route",
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278746582,
      "name": "ip_route_output_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
struct rtable * ip_route_output_flow(struct net * net, struct flowi4 * flp4, const struct sock * sk)
```

```json
{
  "name": "ip_route_output_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588594640,
      "name": "ip_route_output_flow",
      "external": true,
      "loc": "net/ipv4/route.c:2720",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_req",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/igmp.c:ip_mc_find_dev",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:nf_ip_route",
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588594640,
      "name": "ip_route_output_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct rtable * ip_route_output_flow(struct net * net, struct flowi4 * flp4, const struct sock * sk)
```

```json
{
  "name": "ip_route_output_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588306624,
      "name": "ip_route_output_flow",
      "external": true,
      "loc": "net/ipv4/route.c:2720",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/vxlan.c:vxlan_get_route",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_req",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/igmp.c:ip_mc_find_dev",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ip_tunnel.c:ip_tunnel_xmit",
        "net/ipv4/ip_tunnel.c:ip_tunnel_xmit",
        "net/ipv4/ip_tunnel.c:ip_md_tunnel_xmit",
        "net/ipv4/ip_tunnel.c:ip_md_tunnel_xmit",
        "net/ipv4/ip_tunnel.c:ip_tunnel_bind_dev",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:nf_ip_route",
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588306624,
      "name": "ip_route_output_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct rtable * ip_route_output_flow(struct net * net, struct flowi4 * flp4, const struct sock * sk)
```

```json
{
  "name": "ip_route_output_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589030816,
      "name": "ip_route_output_flow",
      "external": true,
      "loc": "net/ipv4/route.c:2720",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_req",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/igmp.c:ip_mc_find_dev",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:nf_ip_route",
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589030816,
      "name": "ip_route_output_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct rtable * ip_route_output_flow(struct net * net, struct flowi4 * flp4, const struct sock * sk)
```

```json
{
  "name": "ip_route_output_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589069840,
      "name": "ip_route_output_flow",
      "external": true,
      "loc": "net/ipv4/route.c:2720",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_req",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/igmp.c:ip_mc_find_dev",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/netfilter.c:nf_ip_route",
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589069840,
      "name": "ip_route_output_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
