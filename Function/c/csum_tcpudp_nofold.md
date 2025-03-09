# Function: <code>csum_tcpudp_nofold</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "csum_tcpudp_nofold",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586224086,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586419755,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586688932,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:__tcp_v4_send_check",
        "net/ipv4/tcp_ipv4.c:__tcp_v4_send_check",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586722149,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp4_gro_complete",
        "net/ipv4/tcp_offload.c:tcp4_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586735512,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586755468,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp4_gro_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586888378,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/ipv4/inet_lro.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586890690,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/ipv4/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/netfilter.c:nf_ip_checksum",
        "net/ipv4/netfilter.c:nf_ip_checksum",
        "net/ipv4/netfilter.c:nf_ip_checksum_partial"
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
  "name": "csum_tcpudp_nofold",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586650003,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586862815,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587149944,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:__tcp_v4_send_check",
        "net/ipv4/tcp_ipv4.c:__tcp_v4_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587170044,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp4_gro_complete",
        "net/ipv4/tcp_offload.c:tcp4_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587200426,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/udp.c:udp4_hwcsum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587202193,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_complete",
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp4_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587338209,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/ipv4/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/netfilter.c:nf_ip_checksum_partial",
        "net/ipv4/netfilter.c:nf_ip_checksum",
        "net/ipv4/netfilter.c:nf_ip_checksum"
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
  "name": "csum_tcpudp_nofold",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586834515,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587053903,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587348968,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:__tcp_v4_send_check",
        "net/ipv4/tcp_ipv4.c:__tcp_v4_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587370092,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp4_gro_complete",
        "net/ipv4/tcp_offload.c:tcp4_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587400818,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/udp.c:udp4_hwcsum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587402561,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_complete",
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp4_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587541153,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/ipv4/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/netfilter.c:nf_ip_checksum_partial",
        "net/ipv4/netfilter.c:nf_ip_checksum",
        "net/ipv4/netfilter.c:nf_ip_checksum"
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
  "name": "csum_tcpudp_nofold",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586956443,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587181720,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587482049,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:__tcp_v4_send_check",
        "net/ipv4/tcp_ipv4.c:__tcp_v4_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587504460,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp4_gro_complete",
        "net/ipv4/tcp_offload.c:tcp4_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587536837,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/udp.c:udp4_hwcsum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587539717,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_complete",
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp4_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587687201,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/ipv4/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/netfilter.c:nf_ip_checksum_partial",
        "net/ipv4/netfilter.c:nf_ip_checksum",
        "net/ipv4/netfilter.c:nf_ip_checksum"
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
  "name": "csum_tcpudp_nofold",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587457899,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587686536,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588004117,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:__tcp_v4_send_check",
        "net/ipv4/tcp_ipv4.c:__tcp_v4_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588026924,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp4_gro_complete",
        "net/ipv4/tcp_offload.c:tcp4_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588058236,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/udp.c:udp4_hwcsum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588063141,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_complete",
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp4_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588213985,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/netfilter.c:nf_ip_checksum_partial",
        "net/ipv4/netfilter.c:nf_ip_checksum",
        "net/ipv4/netfilter.c:nf_ip_checksum"
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
  "name": "csum_tcpudp_nofold",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587761178,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588018718,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588180501,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588354857,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:__tcp_v4_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588378370,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp4_gro_complete",
        "net/ipv4/tcp_offload.c:tcp4_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588409824,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/udp.c:udp4_hwcsum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588414203,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_complete",
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp4_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588568718,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/netfilter.c:nf_ip_checksum_partial",
        "net/ipv4/netfilter.c:nf_ip_checksum",
        "net/ipv4/netfilter.c:nf_ip_checksum"
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
  "name": "csum_tcpudp_nofold",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587896010,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588186174,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588342555,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/netfilter/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/netfilter/utils.c:nf_ip_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588364573,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588545274,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:__tcp_v4_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588568639,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp4_gro_complete",
        "net/ipv4/tcp_offload.c:tcp4_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588601401,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/udp.c:udp4_hwcsum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588605966,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_complete",
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp4_gro_receive"
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
  "name": "csum_tcpudp_nofold",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588201874,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588511824,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588742894,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/netfilter/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/netfilter/utils.c:nf_ip_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588766963,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588956209,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:__tcp_v4_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588979829,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp4_gro_complete",
        "net/ipv4/tcp_offload.c:tcp4_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589013028,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/udp.c:udp4_hwcsum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589017598,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_complete",
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp4_gro_receive"
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
  "name": "csum_tcpudp_nofold",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588406978,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588720400,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588966622,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/netfilter/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/netfilter/utils.c:nf_ip_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588990723,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589180721,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:__tcp_v4_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589204293,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp4_gro_complete",
        "net/ipv4/tcp_offload.c:tcp4_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589237700,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/udp.c:udp4_hwcsum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589242158,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_complete",
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp4_gro_receive"
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
  "name": "csum_tcpudp_nofold",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589273211,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589588084,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589921854,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/netfilter/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/netfilter/utils.c:nf_ip_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589929950,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:inet_rtm_getroute_build_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590151638,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590176549,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp4_gro_complete",
        "net/ipv4/tcp_offload.c:tcp4_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590210451,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_unicast_rcv_skb",
        "net/ipv4/udp.c:udp4_csum_init",
        "net/ipv4/udp.c:udp4_csum_init",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/udp.c:udp4_hwcsum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590216196,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_complete",
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp4_ufo_fragment"
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
  "name": "csum_tcpudp_nofold",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589272347,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589599764,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589962510,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/netfilter/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/netfilter/utils.c:nf_ip_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589970558,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:inet_rtm_getroute_build_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590200694,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590225754,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp4_gro_complete",
        "net/ipv4/tcp_offload.c:tcp4_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590261107,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_unicast_rcv_skb",
        "net/ipv4/udp.c:udp4_csum_init",
        "net/ipv4/udp.c:udp4_csum_init",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/udp.c:udp4_hwcsum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590267044,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_complete",
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp4_ufo_fragment"
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
  "name": "csum_tcpudp_nofold",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589162395,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589487831,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589552967,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/core/selftests.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/selftests.c:net_test_get_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589877236,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/netfilter/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/netfilter/utils.c:nf_ip_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589884557,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:inet_rtm_getroute_build_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590114876,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590139866,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp4_gro_complete",
        "net/ipv4/tcp_offload.c:tcp4_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590174838,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_unicast_rcv_skb",
        "net/ipv4/udp.c:udp4_csum_init",
        "net/ipv4/udp.c:udp4_csum_init",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/udp.c:udp4_hwcsum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590181610,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_complete",
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp4_ufo_fragment"
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
  "name": "csum_tcpudp_nofold",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589884907,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590228562,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590297637,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/core/selftests.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/selftests.c:net_test_get_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590640868,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/netfilter/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/netfilter/utils.c:nf_ip_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590648397,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:inet_rtm_getroute_build_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590891908,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590920170,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp4_gro_complete",
        "net/ipv4/tcp_offload.c:tcp4_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590955574,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_unicast_rcv_skb",
        "net/ipv4/udp.c:udp4_csum_init",
        "net/ipv4/udp.c:udp4_csum_init",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/udp.c:udp4_hwcsum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590962442,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_complete",
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp4_ufo_fragment"
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
  "name": "csum_tcpudp_nofold",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591414674,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591806810,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591881159,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/core/selftests.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/selftests.c:net_test_get_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592264995,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/netfilter/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/netfilter/utils.c:nf_ip_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592294676,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592530162,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592560553,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp4_gro_complete",
        "net/ipv4/tcp_offload.c:tcp4_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592595702,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_unicast_rcv_skb",
        "net/ipv4/udp.c:udp4_csum_init",
        "net/ipv4/udp.c:udp4_csum_init",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/udp.c:udp4_hwcsum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592605482,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_complete",
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp4_ufo_fragment"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "csum_tcpudp_nofold",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593179842,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593602634,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593682679,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/core/selftests.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/selftests.c:net_test_get_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594099747,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/netfilter/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/netfilter/utils.c:nf_ip_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594130221,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594388332,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594420441,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp4_gro_complete",
        "net/ipv4/tcp_offload.c:tcp4_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594459654,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_unicast_rcv_skb",
        "net/ipv4/udp.c:udp4_csum_init",
        "net/ipv4/udp.c:udp4_csum_init",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/udp.c:udp4_hwcsum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594469642,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_complete",
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp4_ufo_fragment"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "csum_tcpudp_nofold",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593637322,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594076020,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594163352,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/core/selftests.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/selftests.c:net_test_get_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594484780,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/netfilter/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/netfilter/utils.c:nf_ip_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594517296,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594776659,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594809785,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp4_gro_complete",
        "net/ipv4/tcp_offload.c:tcp4_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594850935,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_unicast_rcv_skb",
        "net/ipv4/udp.c:udp4_csum_init",
        "net/ipv4/udp.c:udp4_csum_init",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/udp.c:udp4_hwcsum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594860874,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_complete",
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp4_ufo_fragment"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "csum_tcpudp_nofold",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594412938,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594870657,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594959864,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/core/selftests.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/selftests.c:net_test_get_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595287004,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/netfilter/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/netfilter/utils.c:nf_ip_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595320469,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595588174,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595621033,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp4_gro_complete",
        "net/ipv4/tcp_offload.c:tcp4_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595661799,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_unicast_rcv_skb",
        "net/ipv4/udp.c:udp4_csum_init",
        "net/ipv4/udp.c:udp4_csum_init",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/udp.c:udp4_hwcsum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595672202,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:87",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_complete",
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp4_ufo_fragment"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
__wsum csum_tcpudp_nofold(__be32 saddr, __be32 daddr, __u32 len, __u8 proto, __wsum sum)
```

```json
{
  "name": "csum_tcpudp_nofold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496325280,
      "name": "csum_tcpudp_nofold",
      "external": true,
      "loc": "lib/checksum.c:189",
      "file": "lib/checksum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_setup",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:__tcp_v4_send_check",
        "net/ipv4/tcp_offload.c:tcp4_gro_complete",
        "net/ipv4/tcp_offload.c:tcp4_gro_receive",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/udp_offload.c:udp4_gro_complete",
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp4_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496325280,
      "name": "csum_tcpudp_nofold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
  "name": "csum_tcpudp_nofold",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234683196,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/arm/include/asm/checksum.h:88",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 3235025956,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/arm/include/asm/checksum.h:88",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 3235275524,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/arm/include/asm/checksum.h:88",
      "file": "net/netfilter/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/netfilter/utils.c:nf_ip_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 3235301116,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/arm/include/asm/checksum.h:88",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ],
      "caller_func": []
    },
    {
      "addr": 3235502164,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/arm/include/asm/checksum.h:88",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 3235526856,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/arm/include/asm/checksum.h:88",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp4_gro_complete",
        "net/ipv4/tcp_offload.c:tcp4_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 3235561236,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/arm/include/asm/checksum.h:88",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_unicast_rcv_skb",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/udp.c:udp4_hwcsum"
      ],
      "caller_func": []
    },
    {
      "addr": 3235565632,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/arm/include/asm/checksum.h:88",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_complete",
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp4_gro_receive"
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
  "name": "csum_tcpudp_nofold",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295341228,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:57",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295788056,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:57",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296153488,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:57",
      "file": "net/netfilter/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/netfilter/utils.c:nf_ip_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296185896,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:57",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296439088,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:57",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296475396,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:57",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp4_gro_complete",
        "net/ipv4/tcp_offload.c:tcp4_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296521472,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:57",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/udp.c:udp4_hwcsum"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296527220,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:57",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_complete",
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp4_gro_receive"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
__wsum csum_tcpudp_nofold(__be32 saddr, __be32 daddr, __u32 len, __u8 proto, __wsum sum)
```

```json
{
  "name": "csum_tcpudp_nofold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275377064,
      "name": "csum_tcpudp_nofold",
      "external": true,
      "loc": "lib/checksum.c:189",
      "file": "lib/checksum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_checksum_setup",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:__tcp_v4_send_check",
        "net/ipv4/tcp_offload.c:tcp4_gro_complete",
        "net/ipv4/tcp_offload.c:tcp4_gro_receive",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/udp_offload.c:udp4_gro_complete",
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp4_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275377064,
      "name": "csum_tcpudp_nofold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "csum_tcpudp_nofold",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588013762,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588327136,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588573006,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/netfilter/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/netfilter/utils.c:nf_ip_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588597107,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588787105,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:__tcp_v4_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588810677,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp4_gro_complete",
        "net/ipv4/tcp_offload.c:tcp4_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588844084,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/udp.c:udp4_hwcsum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588848542,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_complete",
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp4_gro_receive"
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
  "name": "csum_tcpudp_nofold",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587726850,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588039803,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588284990,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/netfilter/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/netfilter/utils.c:nf_ip_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588309091,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588499041,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:__tcp_v4_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588522613,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp4_gro_complete",
        "net/ipv4/tcp_offload.c:tcp4_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588556020,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/udp.c:udp4_hwcsum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588560478,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_complete",
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp4_gro_receive"
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
  "name": "csum_tcpudp_nofold",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588345538,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588658960,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588905182,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/netfilter/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/netfilter/utils.c:nf_ip_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589033283,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589223281,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:__tcp_v4_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589246853,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp4_gro_complete",
        "net/ipv4/tcp_offload.c:tcp4_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589280260,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/udp.c:udp4_hwcsum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589284718,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_complete",
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp4_gro_receive"
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
  "name": "csum_tcpudp_nofold",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588481010,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_checksum_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588799216,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589047742,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/netfilter/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip_checksum",
        "net/netfilter/utils.c:nf_ip_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589072338,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589263409,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:__tcp_v4_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589287477,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp4_gro_complete",
        "net/ipv4/tcp_offload.c:tcp4_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589321668,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/udp.c:udp4_hwcsum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589326142,
      "name": "csum_tcpudp_nofold",
      "external": false,
      "loc": "arch/x86/include/asm/checksum_64.h:88",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_complete",
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp4_gro_receive"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
__wsum csum_tcpudp_nofold(__be32 saddr, __be32 daddr, __u32 len, __u8 proto, __wsum sum)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
__wsum csum_tcpudp_nofold(__be32 saddr, __be32 daddr, __u32 len, __u8 proto, __wsum sum)
```
</details>
</li>
</ul>
