# Function: <code>__xfrm_policy_check</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __xfrm_policy_check(struct sock * sk, int dir, struct sk_buff * skb, short unsigned int family)
```

```json
{
  "name": "__xfrm_policy_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586931360,
      "name": "__xfrm_policy_check",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:2462",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_local_deliver_finish",
        "net/ipv4/ip_input.c:ip_local_deliver_finish",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586931360,
      "name": "__xfrm_policy_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1558
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
int __xfrm_policy_check(struct sock * sk, int dir, struct sk_buff * skb, short unsigned int family)
```

```json
{
  "name": "__xfrm_policy_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587377808,
      "name": "__xfrm_policy_check",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:2466",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_local_deliver_finish",
        "net/ipv4/ip_input.c:ip_local_deliver_finish",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587377808,
      "name": "__xfrm_policy_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1607
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
int __xfrm_policy_check(struct sock * sk, int dir, struct sk_buff * skb, short unsigned int family)
```

```json
{
  "name": "__xfrm_policy_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587580896,
      "name": "__xfrm_policy_check",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:2494",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_local_deliver_finish",
        "net/ipv4/ip_input.c:ip_local_deliver_finish",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587580896,
      "name": "__xfrm_policy_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1607
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
int __xfrm_policy_check(struct sock * sk, int dir, struct sk_buff * skb, short unsigned int family)
```

```json
{
  "name": "__xfrm_policy_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587727136,
      "name": "__xfrm_policy_check",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:2440",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_local_deliver_finish",
        "net/ipv4/ip_input.c:ip_local_deliver_finish",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587727136,
      "name": "__xfrm_policy_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1704
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
int __xfrm_policy_check(struct sock * sk, int dir, struct sk_buff * skb, short unsigned int family)
```

```json
{
  "name": "__xfrm_policy_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588253792,
      "name": "__xfrm_policy_check",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:2382",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_local_deliver_finish",
        "net/ipv4/ip_input.c:ip_local_deliver_finish",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588253792,
      "name": "__xfrm_policy_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1706
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
int __xfrm_policy_check(struct sock * sk, int dir, struct sk_buff * skb, short unsigned int family)
```

```json
{
  "name": "__xfrm_policy_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588608720,
      "name": "__xfrm_policy_check",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:2392",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_local_deliver_finish",
        "net/ipv4/ip_input.c:ip_local_deliver_finish",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588608720,
      "name": "__xfrm_policy_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1701
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
int __xfrm_policy_check(struct sock * sk, int dir, struct sk_buff * skb, short unsigned int family)
```

```json
{
  "name": "__xfrm_policy_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588819200,
      "name": "__xfrm_policy_check",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3295",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588819200,
      "name": "__xfrm_policy_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1836
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
int __xfrm_policy_check(struct sock * sk, int dir, struct sk_buff * skb, short unsigned int family)
```

```json
{
  "name": "__xfrm_policy_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589252336,
      "name": "__xfrm_policy_check",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3505",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589252336,
      "name": "__xfrm_policy_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1817
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
int __xfrm_policy_check(struct sock * sk, int dir, struct sk_buff * skb, short unsigned int family)
```

```json
{
  "name": "__xfrm_policy_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589477632,
      "name": "__xfrm_policy_check",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3507",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589477632,
      "name": "__xfrm_policy_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1817
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
int __xfrm_policy_check(struct sock * sk, int dir, struct sk_buff * skb, short unsigned int family)
```

```json
{
  "name": "__xfrm_policy_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590468896,
      "name": "__xfrm_policy_check",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3497",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590468896,
      "name": "__xfrm_policy_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1454
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
int __xfrm_policy_check(struct sock * sk, int dir, struct sk_buff * skb, short unsigned int family)
```

```json
{
  "name": "__xfrm_policy_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590527376,
      "name": "__xfrm_policy_check",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3518",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590527376,
      "name": "__xfrm_policy_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1464
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
int __xfrm_policy_check(struct sock * sk, int dir, struct sk_buff * skb, short unsigned int family)
```

```json
{
  "name": "__xfrm_policy_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590452672,
      "name": "__xfrm_policy_check",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3478",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590452672,
      "name": "__xfrm_policy_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1444
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
int __xfrm_policy_check(struct sock * sk, int dir, struct sk_buff * skb, short unsigned int family)
```

```json
{
  "name": "__xfrm_policy_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591254384,
      "name": "__xfrm_policy_check",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3503",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591254384,
      "name": "__xfrm_policy_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2208
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
int __xfrm_policy_check(struct sock * sk, int dir, struct sk_buff * skb, short unsigned int family)
```

```json
{
  "name": "__xfrm_policy_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592919456,
      "name": "__xfrm_policy_check",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3505",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592919456,
      "name": "__xfrm_policy_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1967
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
int __xfrm_policy_check(struct sock * sk, int dir, struct sk_buff * skb, short unsigned int family)
```

```json
{
  "name": "__xfrm_policy_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594800400,
      "name": "__xfrm_policy_check",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3579",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_forward.c:ip_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594800400,
      "name": "__xfrm_policy_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2034
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
int __xfrm_policy_check(struct sock * sk, int dir, struct sk_buff * skb, short unsigned int family)
```

```json
{
  "name": "__xfrm_policy_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595192032,
      "name": "__xfrm_policy_check",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3589",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_forward.c:ip_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595192032,
      "name": "__xfrm_policy_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2074
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
int __xfrm_policy_check(struct sock * sk, int dir, struct sk_buff * skb, short unsigned int family)
```

```json
{
  "name": "__xfrm_policy_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596032608,
      "name": "__xfrm_policy_check",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3508",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_forward.c:ip_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596032608,
      "name": "__xfrm_policy_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2061
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
int __xfrm_policy_check(struct sock * sk, int dir, struct sk_buff * skb, short unsigned int family)
```

```json
{
  "name": "__xfrm_policy_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503136184,
      "name": "__xfrm_policy_check",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3507",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503136184,
      "name": "__xfrm_policy_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1668
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
int __xfrm_policy_check(struct sock * sk, int dir, struct sk_buff * skb, short unsigned int family)
```

```json
{
  "name": "__xfrm_policy_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235816168,
      "name": "__xfrm_policy_check",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3507",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235816168,
      "name": "__xfrm_policy_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1872
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
int __xfrm_policy_check(struct sock * sk, int dir, struct sk_buff * skb, short unsigned int family)
```

```json
{
  "name": "__xfrm_policy_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296857184,
      "name": "__xfrm_policy_check",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3507",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296857184,
      "name": "__xfrm_policy_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2312
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
int __xfrm_policy_check(struct sock * sk, int dir, struct sk_buff * skb, short unsigned int family)
```

```json
{
  "name": "__xfrm_policy_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279182194,
      "name": "__xfrm_policy_check",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3507",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/raw.c:raw_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279182194,
      "name": "__xfrm_policy_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1508
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
int __xfrm_policy_check(struct sock * sk, int dir, struct sk_buff * skb, short unsigned int family)
```

```json
{
  "name": "__xfrm_policy_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589082000,
      "name": "__xfrm_policy_check",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3507",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589082000,
      "name": "__xfrm_policy_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1817
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
int __xfrm_policy_check(struct sock * sk, int dir, struct sk_buff * skb, short unsigned int family)
```

```json
{
  "name": "__xfrm_policy_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588807040,
      "name": "__xfrm_policy_check",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3507",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588807040,
      "name": "__xfrm_policy_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1817
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
int __xfrm_policy_check(struct sock * sk, int dir, struct sk_buff * skb, short unsigned int family)
```

```json
{
  "name": "__xfrm_policy_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589518864,
      "name": "__xfrm_policy_check",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3507",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589518864,
      "name": "__xfrm_policy_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1817
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
int __xfrm_policy_check(struct sock * sk, int dir, struct sk_buff * skb, short unsigned int family)
```

```json
{
  "name": "__xfrm_policy_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589565936,
      "name": "__xfrm_policy_check",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3507",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589565936,
      "name": "__xfrm_policy_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1837
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
