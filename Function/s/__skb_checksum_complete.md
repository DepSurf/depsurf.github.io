# Function: <code>__skb_checksum_complete</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
__sum16 __skb_checksum_complete(struct sk_buff * skb)
```

```json
{
  "name": "__skb_checksum_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586240464,
      "name": "__skb_checksum_complete",
      "external": true,
      "loc": "net/core/datagram.c:667",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:first_packet_length",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/netfilter.c:nf_ip_checksum",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/netfilter.c:nf_ip6_checksum",
        "net/ipv6/ip6_checksum.c:udp6_csum_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586240464,
      "name": "__skb_checksum_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
__sum16 __skb_checksum_complete(struct sk_buff * skb)
```

```json
{
  "name": "__skb_checksum_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586663984,
      "name": "__skb_checksum_complete",
      "external": true,
      "loc": "net/core/datagram.c:689",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:first_packet_length",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/netfilter.c:nf_ip_checksum",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/netfilter.c:nf_ip6_checksum",
        "net/ipv6/ip6_checksum.c:udp6_csum_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586663984,
      "name": "__skb_checksum_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
__sum16 __skb_checksum_complete(struct sk_buff * skb)
```

```json
{
  "name": "__skb_checksum_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586849072,
      "name": "__skb_checksum_complete",
      "external": true,
      "loc": "net/core/datagram.c:709",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:first_packet_length",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/netfilter.c:nf_ip_checksum",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/netfilter.c:nf_ip6_checksum",
        "net/ipv6/ip6_checksum.c:udp6_csum_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586849072,
      "name": "__skb_checksum_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
__sum16 __skb_checksum_complete(struct sk_buff * skb)
```

```json
{
  "name": "__skb_checksum_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586970000,
      "name": "__skb_checksum_complete",
      "external": true,
      "loc": "net/core/datagram.c:735",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/netfilter.c:nf_ip_checksum",
        "net/ipv4/netfilter.c:nf_ip_checksum",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/netfilter.c:nf_ip6_checksum",
        "net/ipv6/ip6_checksum.c:udp6_csum_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586970000,
      "name": "__skb_checksum_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
__sum16 __skb_checksum_complete(struct sk_buff * skb)
```

```json
{
  "name": "__skb_checksum_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587468608,
      "name": "__skb_checksum_complete",
      "external": true,
      "loc": "net/core/datagram.c:749",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/netfilter.c:nf_ip_checksum",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/netfilter.c:nf_ip6_checksum"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587468608,
      "name": "__skb_checksum_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
__sum16 __skb_checksum_complete(struct sk_buff * skb)
```

```json
{
  "name": "__skb_checksum_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587773552,
      "name": "__skb_checksum_complete",
      "external": true,
      "loc": "net/core/datagram.c:747",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/netfilter.c:nf_ip_checksum",
        "net/ipv4/netfilter.c:nf_ip_checksum",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/netfilter.c:nf_ip6_checksum"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587773552,
      "name": "__skb_checksum_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
__sum16 __skb_checksum_complete(struct sk_buff * skb)
```

```json
{
  "name": "__skb_checksum_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587871824,
      "name": "__skb_checksum_complete",
      "external": true,
      "loc": "net/core/skbuff.c:2668",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/ip6_checksum.c:udp6_csum_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587871824,
      "name": "__skb_checksum_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
__sum16 __skb_checksum_complete(struct sk_buff * skb)
```

```json
{
  "name": "__skb_checksum_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588177216,
      "name": "__skb_checksum_complete",
      "external": true,
      "loc": "net/core/skbuff.c:2834",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/ip6_checksum.c:udp6_csum_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588177216,
      "name": "__skb_checksum_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
__sum16 __skb_checksum_complete(struct sk_buff * skb)
```

```json
{
  "name": "__skb_checksum_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588382336,
      "name": "__skb_checksum_complete",
      "external": true,
      "loc": "net/core/skbuff.c:2836",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/ip6_checksum.c:udp6_csum_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588382336,
      "name": "__skb_checksum_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
__sum16 __skb_checksum_complete(struct sk_buff * skb)
```

```json
{
  "name": "__skb_checksum_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589246208,
      "name": "__skb_checksum_complete",
      "external": true,
      "loc": "net/core/skbuff.c:2835",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp4_csum_init",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/ip6_checksum.c:udp6_csum_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589246208,
      "name": "__skb_checksum_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
__sum16 __skb_checksum_complete(struct sk_buff * skb)
```

```json
{
  "name": "__skb_checksum_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589245472,
      "name": "__skb_checksum_complete",
      "external": true,
      "loc": "net/core/skbuff.c:2853",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp4_csum_init",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/ip6_checksum.c:udp6_csum_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589245472,
      "name": "__skb_checksum_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
__sum16 __skb_checksum_complete(struct sk_buff * skb)
```

```json
{
  "name": "__skb_checksum_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589140272,
      "name": "__skb_checksum_complete",
      "external": true,
      "loc": "net/core/skbuff.c:2936",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp4_csum_init",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/ip6_checksum.c:udp6_csum_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589140272,
      "name": "__skb_checksum_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
__sum16 __skb_checksum_complete(struct sk_buff * skb)
```

```json
{
  "name": "__skb_checksum_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589859824,
      "name": "__skb_checksum_complete",
      "external": true,
      "loc": "net/core/skbuff.c:3008",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp4_csum_init",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_read_sock",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/ip6_checksum.c:udp6_csum_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589859824,
      "name": "__skb_checksum_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
__sum16 __skb_checksum_complete(struct sk_buff * skb)
```

```json
{
  "name": "__skb_checksum_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591386352,
      "name": "__skb_checksum_complete",
      "external": true,
      "loc": "net/core/skbuff.c:3057",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp4_csum_init",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_read_sock",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/ip6_checksum.c:udp6_csum_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591386352,
      "name": "__skb_checksum_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
__sum16 __skb_checksum_complete(struct sk_buff * skb)
```

```json
{
  "name": "__skb_checksum_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593148240,
      "name": "__skb_checksum_complete",
      "external": true,
      "loc": "net/core/skbuff.c:3263",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp4_csum_init",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_read_skb",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/ip6_checksum.c:udp6_csum_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593148240,
      "name": "__skb_checksum_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
__sum16 __skb_checksum_complete(struct sk_buff * skb)
```

```json
{
  "name": "__skb_checksum_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593601984,
      "name": "__skb_checksum_complete",
      "external": true,
      "loc": "net/core/skbuff.c:3433",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp4_csum_init",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_read_skb",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/ip6_checksum.c:udp6_csum_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593601984,
      "name": "__skb_checksum_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
__sum16 __skb_checksum_complete(struct sk_buff * skb)
```

```json
{
  "name": "__skb_checksum_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594376576,
      "name": "__skb_checksum_complete",
      "external": true,
      "loc": "net/core/skbuff.c:3521",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp4_csum_init",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_read_skb",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/ip6_checksum.c:udp6_csum_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594376576,
      "name": "__skb_checksum_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
__sum16 __skb_checksum_complete(struct sk_buff * skb)
```

```json
{
  "name": "__skb_checksum_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501893592,
      "name": "__skb_checksum_complete",
      "external": true,
      "loc": "net/core/skbuff.c:2836",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/ip6_checksum.c:udp6_csum_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501893592,
      "name": "__skb_checksum_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
__sum16 __skb_checksum_complete(struct sk_buff * skb)
```

```json
{
  "name": "__skb_checksum_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234657628,
      "name": "__skb_checksum_complete",
      "external": true,
      "loc": "net/core/skbuff.c:2836",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/ip6_checksum.c:udp6_csum_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234657628,
      "name": "__skb_checksum_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
__sum16 __skb_checksum_complete(struct sk_buff * skb)
```

```json
{
  "name": "__skb_checksum_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295307792,
      "name": "__skb_checksum_complete",
      "external": true,
      "loc": "net/core/skbuff.c:2836",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/ip6_checksum.c:udp6_csum_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295307792,
      "name": "__skb_checksum_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
__sum16 __skb_checksum_complete(struct sk_buff * skb)
```

```json
{
  "name": "__skb_checksum_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278213578,
      "name": "__skb_checksum_complete",
      "external": true,
      "loc": "net/core/skbuff.c:2836",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/ip6_checksum.c:udp6_csum_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278213578,
      "name": "__skb_checksum_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
__sum16 __skb_checksum_complete(struct sk_buff * skb)
```

```json
{
  "name": "__skb_checksum_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587989120,
      "name": "__skb_checksum_complete",
      "external": true,
      "loc": "net/core/skbuff.c:2836",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/ip6_checksum.c:udp6_csum_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587989120,
      "name": "__skb_checksum_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
__sum16 __skb_checksum_complete(struct sk_buff * skb)
```

```json
{
  "name": "__skb_checksum_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587702224,
      "name": "__skb_checksum_complete",
      "external": true,
      "loc": "net/core/skbuff.c:2836",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/vxlan.c:vxlan_rcv",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/ip6_checksum.c:udp6_csum_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587702224,
      "name": "__skb_checksum_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
__sum16 __skb_checksum_complete(struct sk_buff * skb)
```

```json
{
  "name": "__skb_checksum_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588320896,
      "name": "__skb_checksum_complete",
      "external": true,
      "loc": "net/core/skbuff.c:2836",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/ip6_checksum.c:udp6_csum_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588320896,
      "name": "__skb_checksum_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
__sum16 __skb_checksum_complete(struct sk_buff * skb)
```

```json
{
  "name": "__skb_checksum_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588456304,
      "name": "__skb_checksum_complete",
      "external": true,
      "loc": "net/core/skbuff.c:2836",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/ip6_checksum.c:udp6_csum_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588456304,
      "name": "__skb_checksum_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
