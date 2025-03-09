# Function: <code>__skb_checksum_complete_head</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
__sum16 __skb_checksum_complete_head(struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_checksum_complete_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586240320,
      "name": "__skb_checksum_complete_head",
      "external": true,
      "loc": "net/core/datagram.c:651",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:first_packet_length",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/netfilter.c:nf_ip_checksum_partial",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/netfilter.c:nf_ip6_checksum_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586240320,
      "name": "__skb_checksum_complete_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
__sum16 __skb_checksum_complete_head(struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_checksum_complete_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586663824,
      "name": "__skb_checksum_complete_head",
      "external": true,
      "loc": "net/core/datagram.c:673",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:first_packet_length",
        "net/ipv4/netfilter.c:nf_ip_checksum_partial",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/netfilter.c:nf_ip6_checksum_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586663824,
      "name": "__skb_checksum_complete_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
__sum16 __skb_checksum_complete_head(struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_checksum_complete_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586848912,
      "name": "__skb_checksum_complete_head",
      "external": true,
      "loc": "net/core/datagram.c:693",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:first_packet_length",
        "net/ipv4/netfilter.c:nf_ip_checksum_partial",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/netfilter.c:nf_ip6_checksum_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586848912,
      "name": "__skb_checksum_complete_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
__sum16 __skb_checksum_complete_head(struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_checksum_complete_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586969856,
      "name": "__skb_checksum_complete_head",
      "external": true,
      "loc": "net/core/datagram.c:719",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/netfilter.c:nf_ip_checksum_partial",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/netfilter.c:nf_ip6_checksum_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586969856,
      "name": "__skb_checksum_complete_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
__sum16 __skb_checksum_complete_head(struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_checksum_complete_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587468464,
      "name": "__skb_checksum_complete_head",
      "external": true,
      "loc": "net/core/datagram.c:733",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/netfilter.c:nf_ip_checksum_partial",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/netfilter.c:nf_ip6_checksum_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587468464,
      "name": "__skb_checksum_complete_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
__sum16 __skb_checksum_complete_head(struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_checksum_complete_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587773408,
      "name": "__skb_checksum_complete_head",
      "external": true,
      "loc": "net/core/datagram.c:731",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/netfilter.c:nf_ip_checksum_partial",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/netfilter.c:nf_ip6_checksum_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587773408,
      "name": "__skb_checksum_complete_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
__sum16 __skb_checksum_complete_head(struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_checksum_complete_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587871616,
      "name": "__skb_checksum_complete_head",
      "external": true,
      "loc": "net/core/skbuff.c:2642",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587871616,
      "name": "__skb_checksum_complete_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
__sum16 __skb_checksum_complete_head(struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_checksum_complete_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588177008,
      "name": "__skb_checksum_complete_head",
      "external": true,
      "loc": "net/core/skbuff.c:2808",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588177008,
      "name": "__skb_checksum_complete_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
__sum16 __skb_checksum_complete_head(struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_checksum_complete_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588382128,
      "name": "__skb_checksum_complete_head",
      "external": true,
      "loc": "net/core/skbuff.c:2810",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588382128,
      "name": "__skb_checksum_complete_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
__sum16 __skb_checksum_complete_head(struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_checksum_complete_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589246000,
      "name": "__skb_checksum_complete_head",
      "external": true,
      "loc": "net/core/skbuff.c:2809",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589246000,
      "name": "__skb_checksum_complete_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
__sum16 __skb_checksum_complete_head(struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_checksum_complete_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589245264,
      "name": "__skb_checksum_complete_head",
      "external": true,
      "loc": "net/core/skbuff.c:2827",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589245264,
      "name": "__skb_checksum_complete_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
__sum16 __skb_checksum_complete_head(struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_checksum_complete_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589140064,
      "name": "__skb_checksum_complete_head",
      "external": true,
      "loc": "net/core/skbuff.c:2910",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589140064,
      "name": "__skb_checksum_complete_head",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
__sum16 __skb_checksum_complete_head(struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_checksum_complete_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589859616,
      "name": "__skb_checksum_complete_head",
      "external": true,
      "loc": "net/core/skbuff.c:2982",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_read_sock",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589859616,
      "name": "__skb_checksum_complete_head",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
__sum16 __skb_checksum_complete_head(struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_checksum_complete_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591386128,
      "name": "__skb_checksum_complete_head",
      "external": true,
      "loc": "net/core/skbuff.c:3031",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_read_sock",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591386128,
      "name": "__skb_checksum_complete_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
__sum16 __skb_checksum_complete_head(struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_checksum_complete_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593148000,
      "name": "__skb_checksum_complete_head",
      "external": true,
      "loc": "net/core/skbuff.c:3237",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_read_skb",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593148000,
      "name": "__skb_checksum_complete_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
__sum16 __skb_checksum_complete_head(struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_checksum_complete_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593601744,
      "name": "__skb_checksum_complete_head",
      "external": true,
      "loc": "net/core/skbuff.c:3407",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_read_skb",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593601744,
      "name": "__skb_checksum_complete_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
__sum16 __skb_checksum_complete_head(struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_checksum_complete_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594376336,
      "name": "__skb_checksum_complete_head",
      "external": true,
      "loc": "net/core/skbuff.c:3495",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_read_skb",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594376336,
      "name": "__skb_checksum_complete_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
__sum16 __skb_checksum_complete_head(struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_checksum_complete_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501893368,
      "name": "__skb_checksum_complete_head",
      "external": true,
      "loc": "net/core/skbuff.c:2810",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501893368,
      "name": "__skb_checksum_complete_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
__sum16 __skb_checksum_complete_head(struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_checksum_complete_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234657404,
      "name": "__skb_checksum_complete_head",
      "external": true,
      "loc": "net/core/skbuff.c:2810",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234657404,
      "name": "__skb_checksum_complete_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
__sum16 __skb_checksum_complete_head(struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_checksum_complete_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295307536,
      "name": "__skb_checksum_complete_head",
      "external": true,
      "loc": "net/core/skbuff.c:2810",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295307536,
      "name": "__skb_checksum_complete_head",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
__sum16 __skb_checksum_complete_head(struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_checksum_complete_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278213380,
      "name": "__skb_checksum_complete_head",
      "external": true,
      "loc": "net/core/skbuff.c:2810",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278213380,
      "name": "__skb_checksum_complete_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
__sum16 __skb_checksum_complete_head(struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_checksum_complete_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587988912,
      "name": "__skb_checksum_complete_head",
      "external": true,
      "loc": "net/core/skbuff.c:2810",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587988912,
      "name": "__skb_checksum_complete_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
__sum16 __skb_checksum_complete_head(struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_checksum_complete_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587702016,
      "name": "__skb_checksum_complete_head",
      "external": true,
      "loc": "net/core/skbuff.c:2810",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587702016,
      "name": "__skb_checksum_complete_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
__sum16 __skb_checksum_complete_head(struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_checksum_complete_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588320688,
      "name": "__skb_checksum_complete_head",
      "external": true,
      "loc": "net/core/skbuff.c:2810",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588320688,
      "name": "__skb_checksum_complete_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
__sum16 __skb_checksum_complete_head(struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_checksum_complete_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588456096,
      "name": "__skb_checksum_complete_head",
      "external": true,
      "loc": "net/core/skbuff.c:2810",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588456096,
      "name": "__skb_checksum_complete_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
