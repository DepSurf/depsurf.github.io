# Function: <code>csum_ipv6_magic</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
__sum16 csum_ipv6_magic(const struct in6_addr * saddr, const struct in6_addr * daddr, __u32 len, short unsigned int proto, __wsum sum)
```

```json
{
  "name": "csum_ipv6_magic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587330832,
      "name": "csum_ipv6_magic",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:136",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_setup",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/netfilter.c:nf_ip6_checksum",
        "net/ipv6/netfilter.c:nf_ip6_checksum",
        "net/ipv6/netfilter.c:nf_ip6_checksum_partial",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_complete",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_gro_complete",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587330832,
      "name": "csum_ipv6_magic",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
__sum16 csum_ipv6_magic(const struct in6_addr * saddr, const struct in6_addr * daddr, __u32 len, __u8 proto, __wsum sum)
```

```json
{
  "name": "csum_ipv6_magic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587829184,
      "name": "csum_ipv6_magic",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:137",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_setup",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/udp_offload.c:udp6_gro_complete",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/netfilter.c:nf_ip6_checksum_partial",
        "net/ipv6/netfilter.c:nf_ip6_checksum",
        "net/ipv6/netfilter.c:nf_ip6_checksum",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_complete",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587829184,
      "name": "csum_ipv6_magic",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
__sum16 csum_ipv6_magic(const struct in6_addr * saddr, const struct in6_addr * daddr, __u32 len, __u8 proto, __wsum sum)
```

```json
{
  "name": "csum_ipv6_magic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588044496,
      "name": "csum_ipv6_magic",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:137",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_setup",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/udp_offload.c:udp6_gro_complete",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/netfilter.c:nf_ip6_checksum_partial",
        "net/ipv6/netfilter.c:nf_ip6_checksum",
        "net/ipv6/netfilter.c:nf_ip6_checksum",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_complete",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588044496,
      "name": "csum_ipv6_magic",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
__sum16 csum_ipv6_magic(const struct in6_addr * saddr, const struct in6_addr * daddr, __u32 len, __u8 proto, __wsum sum)
```

```json
{
  "name": "csum_ipv6_magic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588264608,
      "name": "csum_ipv6_magic",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:137",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_setup",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/udp_offload.c:udp6_gro_complete",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/netfilter.c:nf_ip6_checksum_partial",
        "net/ipv6/netfilter.c:nf_ip6_checksum",
        "net/ipv6/netfilter.c:nf_ip6_checksum",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_complete",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588264608,
      "name": "csum_ipv6_magic",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
__sum16 csum_ipv6_magic(const struct in6_addr * saddr, const struct in6_addr * daddr, __u32 len, __u8 proto, __wsum sum)
```

```json
{
  "name": "csum_ipv6_magic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588817136,
      "name": "csum_ipv6_magic",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:137",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_setup",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/udp_offload.c:udp6_gro_complete",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/netfilter.c:nf_ip6_checksum_partial",
        "net/ipv6/netfilter.c:nf_ip6_checksum",
        "net/ipv6/netfilter.c:nf_ip6_checksum",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_complete",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588817136,
      "name": "csum_ipv6_magic",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
__sum16 csum_ipv6_magic(const struct in6_addr * saddr, const struct in6_addr * daddr, __u32 len, __u8 proto, __wsum sum)
```

```json
{
  "name": "csum_ipv6_magic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589195296,
      "name": "csum_ipv6_magic",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:137",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_setup",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/udp_offload.c:udp6_gro_complete",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/netfilter.c:nf_ip6_checksum_partial",
        "net/ipv6/netfilter.c:nf_ip6_checksum",
        "net/ipv6/netfilter.c:nf_ip6_checksum",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_complete",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589195296,
      "name": "csum_ipv6_magic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
__sum16 csum_ipv6_magic(const struct in6_addr * saddr, const struct in6_addr * daddr, __u32 len, __u8 proto, __wsum sum)
```

```json
{
  "name": "csum_ipv6_magic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589436752,
      "name": "csum_ipv6_magic",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:137",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_setup",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/udp_offload.c:udp6_gro_complete",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_complete",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589436752,
      "name": "csum_ipv6_magic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
__sum16 csum_ipv6_magic(const struct in6_addr * saddr, const struct in6_addr * daddr, __u32 len, __u8 proto, __wsum sum)
```

```json
{
  "name": "csum_ipv6_magic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589894768,
      "name": "csum_ipv6_magic",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:137",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_setup",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/udp_offload.c:udp6_gro_complete",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_complete",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589894768,
      "name": "csum_ipv6_magic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
__sum16 csum_ipv6_magic(const struct in6_addr * saddr, const struct in6_addr * daddr, __u32 len, __u8 proto, __wsum sum)
```

```json
{
  "name": "csum_ipv6_magic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590120720,
      "name": "csum_ipv6_magic",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:137",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_setup",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/udp_offload.c:udp6_gro_complete",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_complete",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590120720,
      "name": "csum_ipv6_magic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
__sum16 csum_ipv6_magic(const struct in6_addr * saddr, const struct in6_addr * daddr, __u32 len, __u8 proto, __wsum sum)
```

```json
{
  "name": "csum_ipv6_magic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585124704,
      "name": "csum_ipv6_magic",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:138",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_setup_ipv6",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp6_unicast_rcv_skb",
        "net/ipv6/raw.c:rawv6_push_pending_frames",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/udp_offload.c:udp6_gro_complete",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_complete",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585124704,
      "name": "csum_ipv6_magic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
__sum16 csum_ipv6_magic(const struct in6_addr * saddr, const struct in6_addr * daddr, __u32 len, __u8 proto, __wsum sum)
```

```json
{
  "name": "csum_ipv6_magic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585275728,
      "name": "csum_ipv6_magic",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:78",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_setup_ipv6",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp6_unicast_rcv_skb",
        "net/ipv6/raw.c:rawv6_push_pending_frames",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/udp_offload.c:udp6_gro_complete",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_complete",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585275728,
      "name": "csum_ipv6_magic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
__sum16 csum_ipv6_magic(const struct in6_addr * saddr, const struct in6_addr * daddr, __u32 len, __u8 proto, __wsum sum)
```

```json
{
  "name": "csum_ipv6_magic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585159264,
      "name": "csum_ipv6_magic",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:78",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_setup_ipv6",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp6_unicast_rcv_skb",
        "net/ipv6/raw.c:rawv6_push_pending_frames",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/udp_offload.c:udp6_gro_complete",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_complete",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585159264,
      "name": "csum_ipv6_magic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
__sum16 csum_ipv6_magic(const struct in6_addr * saddr, const struct in6_addr * daddr, __u32 len, __u8 proto, __wsum sum)
```

```json
{
  "name": "csum_ipv6_magic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585612112,
      "name": "csum_ipv6_magic",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:78",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_setup_ipv6",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp6_unicast_rcv_skb",
        "net/ipv6/raw.c:rawv6_push_pending_frames",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/udp_offload.c:udp6_gro_complete",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_complete",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585612112,
      "name": "csum_ipv6_magic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
__sum16 csum_ipv6_magic(const struct in6_addr * saddr, const struct in6_addr * daddr, __u32 len, __u8 proto, __wsum sum)
```

```json
{
  "name": "csum_ipv6_magic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586768896,
      "name": "csum_ipv6_magic",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:76",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_setup_ipv6",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp6_unicast_rcv_skb",
        "net/ipv6/raw.c:rawv6_push_pending_frames",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/udp_offload.c:udp6_gro_complete",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_complete",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586768896,
      "name": "csum_ipv6_magic",
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
__sum16 csum_ipv6_magic(const struct in6_addr * saddr, const struct in6_addr * daddr, __u32 len, __u8 proto, __wsum sum)
```

```json
{
  "name": "csum_ipv6_magic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595933968,
      "name": "csum_ipv6_magic",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:76",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_setup_ipv6",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp6_unicast_rcv_skb",
        "net/ipv6/raw.c:rawv6_push_pending_frames",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/udp_offload.c:udp6_gro_complete",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_complete",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595933968,
      "name": "csum_ipv6_magic",
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
__sum16 csum_ipv6_magic(const struct in6_addr * saddr, const struct in6_addr * daddr, __u32 len, __u8 proto, __wsum sum)
```

```json
{
  "name": "csum_ipv6_magic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596452352,
      "name": "csum_ipv6_magic",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:76",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_setup_ipv6",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp6_unicast_rcv_skb",
        "net/ipv6/raw.c:rawv6_push_pending_frames",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/udp_offload.c:udp6_gro_complete",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_complete",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596452352,
      "name": "csum_ipv6_magic",
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
__sum16 csum_ipv6_magic(const struct in6_addr * saddr, const struct in6_addr * daddr, __u32 len, __u8 proto, __wsum sum)
```

```json
{
  "name": "csum_ipv6_magic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597347392,
      "name": "csum_ipv6_magic",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:71",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_setup_ipv6",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp6_unicast_rcv_skb",
        "net/ipv6/raw.c:rawv6_push_pending_frames",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/udp_offload.c:udp6_gro_complete",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_complete",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597347392,
      "name": "csum_ipv6_magic",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
__sum16 csum_ipv6_magic(const struct in6_addr * saddr, const struct in6_addr * daddr, __u32 len, __u8 proto, __wsum csum)
```

```json
{
  "name": "csum_ipv6_magic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503604656,
      "name": "csum_ipv6_magic",
      "external": true,
      "loc": "net/ipv6/ip6_checksum.c:8",
      "file": "net/ipv6/ip6_checksum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_setup",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/udp_offload.c:udp6_gro_complete",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_complete",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503604656,
      "name": "csum_ipv6_magic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "csum_ipv6_magic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234682820,
      "name": "csum_ipv6_magic",
      "external": false,
      "loc": "arch/arm/include/asm/checksum.h:148",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 3235026400,
      "name": "csum_ipv6_magic",
      "external": false,
      "loc": "arch/arm/include/asm/checksum.h:148",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 3235275372,
      "name": "csum_ipv6_magic",
      "external": false,
      "loc": "arch/arm/include/asm/checksum.h:148",
      "file": "net/netfilter/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip6_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 3236057108,
      "name": "csum_ipv6_magic",
      "external": false,
      "loc": "arch/arm/include/asm/checksum.h:148",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 3236070376,
      "name": "csum_ipv6_magic",
      "external": false,
      "loc": "arch/arm/include/asm/checksum.h:148",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp6_unicast_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 3236095680,
      "name": "csum_ipv6_magic",
      "external": false,
      "loc": "arch/arm/include/asm/checksum.h:148",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 3236104840,
      "name": "csum_ipv6_magic",
      "external": false,
      "loc": "arch/arm/include/asm/checksum.h:148",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 3236116568,
      "name": "csum_ipv6_magic",
      "external": false,
      "loc": "arch/arm/include/asm/checksum.h:148",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack"
      ],
      "caller_func": []
    },
    {
      "addr": 3236149884,
      "name": "csum_ipv6_magic",
      "external": false,
      "loc": "arch/arm/include/asm/checksum.h:148",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 3236181464,
      "name": "csum_ipv6_magic",
      "external": false,
      "loc": "arch/arm/include/asm/checksum.h:148",
      "file": "net/ipv6/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp_offload.c:udp6_gro_complete",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 3236199416,
      "name": "csum_ipv6_magic",
      "external": false,
      "loc": "arch/arm/include/asm/checksum.h:148",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:pim6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 3236249576,
      "name": "csum_ipv6_magic",
      "external": false,
      "loc": "arch/arm/include/asm/checksum.h:148",
      "file": "net/ipv6/ip6_checksum.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/ip6_checksum.c:udp6_csum_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3236255128,
      "name": "csum_ipv6_magic",
      "external": false,
      "loc": "arch/arm/include/asm/checksum.h:148",
      "file": "net/ipv6/tcpv6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcpv6_offload.c:tcp6_gro_complete",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 3236259744,
      "name": "csum_ipv6_magic",
      "external": false,
      "loc": "arch/arm/include/asm/checksum.h:148",
      "file": "net/ipv6/mcast_snoop.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "csum_ipv6_magic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "csum_ipv6_magic",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_setup",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/udp_offload.c:udp6_gro_complete",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_complete",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282859344,
      "name": "csum_ipv6_magic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 0
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
__sum16 csum_ipv6_magic(const struct in6_addr * saddr, const struct in6_addr * daddr, __u32 len, __u8 proto, __wsum csum)
```

```json
{
  "name": "csum_ipv6_magic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279556746,
      "name": "csum_ipv6_magic",
      "external": true,
      "loc": "net/ipv6/ip6_checksum.c:8",
      "file": "net/ipv6/ip6_checksum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_setup",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/udp_offload.c:udp6_gro_complete",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_complete",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279556746,
      "name": "csum_ipv6_magic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
__sum16 csum_ipv6_magic(const struct in6_addr * saddr, const struct in6_addr * daddr, __u32 len, __u8 proto, __wsum sum)
```

```json
{
  "name": "csum_ipv6_magic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589722976,
      "name": "csum_ipv6_magic",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:137",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_setup",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/udp_offload.c:udp6_gro_complete",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_complete",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589722976,
      "name": "csum_ipv6_magic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
__sum16 csum_ipv6_magic(const struct in6_addr * saddr, const struct in6_addr * daddr, __u32 len, __u8 proto, __wsum sum)
```

```json
{
  "name": "csum_ipv6_magic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589448752,
      "name": "csum_ipv6_magic",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:137",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/vxlan.c:neigh_reduce",
        "net/core/skbuff.c:skb_checksum_setup",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/udp_offload.c:udp6_gro_complete",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_complete",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589448752,
      "name": "csum_ipv6_magic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
__sum16 csum_ipv6_magic(const struct in6_addr * saddr, const struct in6_addr * daddr, __u32 len, __u8 proto, __wsum sum)
```

```json
{
  "name": "csum_ipv6_magic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590166352,
      "name": "csum_ipv6_magic",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:137",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_setup",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/udp_offload.c:udp6_gro_complete",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_complete",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590166352,
      "name": "csum_ipv6_magic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
__sum16 csum_ipv6_magic(const struct in6_addr * saddr, const struct in6_addr * daddr, __u32 len, __u8 proto, __wsum sum)
```

```json
{
  "name": "csum_ipv6_magic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590216864,
      "name": "csum_ipv6_magic",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:137",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_setup",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/udp_offload.c:udp6_gro_complete",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/ip6_checksum.c:udp6_csum_init",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_complete",
        "net/ipv6/tcpv6_offload.c:tcp6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590216864,
      "name": "csum_ipv6_magic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
<code>short unsigned int proto</code> ➡️ <code>__u8 proto</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>__wsum csum</code>
</li>
<li>
<b>Param removed. </b>
<code>__wsum sum</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
__sum16 csum_ipv6_magic(const struct in6_addr * saddr, const struct in6_addr * daddr, __u32 len, __u8 proto, __wsum sum)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
__sum16 csum_ipv6_magic(const struct in6_addr * saddr, const struct in6_addr * daddr, __u32 len, __u8 proto, __wsum sum)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>__wsum csum</code>
</li>
<li>
<b>Param removed. </b>
<code>__wsum sum</code>
</li>
</ul>
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
