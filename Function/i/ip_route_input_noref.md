# Function: <code>ip_route_input_noref</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ip_route_input_noref(struct sk_buff * skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device * dev)
```

```json
{
  "name": "ip_route_input_noref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586534432,
      "name": "ip_route_input_noref",
      "external": true,
      "loc": "net/ipv4/route.c:1954",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/ip_input.c:ip_rcv_finish",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_route_lookup",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586534432,
      "name": "ip_route_input_noref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3684
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
int ip_route_input_noref(struct sk_buff * skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device * dev)
```

```json
{
  "name": "ip_route_input_noref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586977200,
      "name": "ip_route_input_noref",
      "external": true,
      "loc": "net/ipv4/route.c:1961",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/ip_input.c:ip_rcv_finish",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_route_lookup",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586977200,
      "name": "ip_route_input_noref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3829
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
int ip_route_input_noref(struct sk_buff * skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device * dev)
```

```json
{
  "name": "ip_route_input_noref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587175088,
      "name": "ip_route_input_noref",
      "external": true,
      "loc": "net/ipv4/route.c:1989",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/ip_input.c:ip_rcv_finish",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_route_lookup",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587175088,
      "name": "ip_route_input_noref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 4021
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
int ip_route_input_noref(struct sk_buff * skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device * dev)
```

```json
{
  "name": "ip_route_input_noref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587308240,
      "name": "ip_route_input_noref",
      "external": true,
      "loc": "net/ipv4/route.c:2068",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_rcv_finish",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587308240,
      "name": "ip_route_input_noref",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int ip_route_input_noref(struct sk_buff * skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device * dev)
```

```json
{
  "name": "ip_route_input_noref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587830000,
      "name": "ip_route_input_noref",
      "external": true,
      "loc": "net/ipv4/route.c:2083",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_rcv_finish",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv6/seg6_local.c:input_action_end_dx4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587830000,
      "name": "ip_route_input_noref",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int ip_route_input_noref(struct sk_buff * skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device * dev)
```

```json
{
  "name": "ip_route_input_noref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588173936,
      "name": "ip_route_input_noref",
      "external": true,
      "loc": "net/ipv4/route.c:2115",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_rcv_finish",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv6/seg6_local.c:input_action_end_dx4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588173936,
      "name": "ip_route_input_noref",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int ip_route_input_noref(struct sk_buff * skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device * dev)
```

```json
{
  "name": "ip_route_input_noref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588358016,
      "name": "ip_route_input_noref",
      "external": true,
      "loc": "net/ipv4/route.c:2116",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv6/seg6_local.c:input_action_end_dx4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588358016,
      "name": "ip_route_input_noref",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int ip_route_input_noref(struct sk_buff * skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device * dev)
```

```json
{
  "name": "ip_route_input_noref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588761248,
      "name": "ip_route_input_noref",
      "external": true,
      "loc": "net/ipv4/route.c:2243",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_input",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish",
        "net/ipv6/seg6_local.c:input_action_end_dx4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588761248,
      "name": "ip_route_input_noref",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int ip_route_input_noref(struct sk_buff * skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device * dev)
```

```json
{
  "name": "ip_route_input_noref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588985024,
      "name": "ip_route_input_noref",
      "external": true,
      "loc": "net/ipv4/route.c:2247",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_input",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish",
        "net/ipv6/seg6_local.c:input_action_end_dx4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588985024,
      "name": "ip_route_input_noref",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int ip_route_input_noref(struct sk_buff * skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device * dev)
```

```json
{
  "name": "ip_route_input_noref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589944064,
      "name": "ip_route_input_noref",
      "external": true,
      "loc": "net/ipv4/route.c:2289",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_input",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish",
        "net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap",
        "net/ipv6/seg6_local.c:input_action_end_dx4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589944064,
      "name": "ip_route_input_noref",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int ip_route_input_noref(struct sk_buff * skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device * dev)
```

```json
{
  "name": "ip_route_input_noref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589985136,
      "name": "ip_route_input_noref",
      "external": true,
      "loc": "net/ipv4/route.c:2295",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_input",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish",
        "net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap",
        "net/ipv6/seg6_local.c:input_action_end_dt4",
        "net/ipv6/seg6_local.c:input_action_end_dx4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589985136,
      "name": "ip_route_input_noref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int ip_route_input_noref(struct sk_buff * skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device * dev)
```

```json
{
  "name": "ip_route_input_noref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589898928,
      "name": "ip_route_input_noref",
      "external": true,
      "loc": "net/ipv4/route.c:2296",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_input",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish",
        "net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap",
        "net/ipv6/seg6_local.c:input_action_end_dt4",
        "net/ipv6/seg6_local.c:input_action_end_dx4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589898928,
      "name": "ip_route_input_noref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int ip_route_input_noref(struct sk_buff * skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device * dev)
```

```json
{
  "name": "ip_route_input_noref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590664608,
      "name": "ip_route_input_noref",
      "external": true,
      "loc": "net/ipv4/route.c:2415",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_lwt_input_reroute",
        "net/core/lwt_bpf.c:bpf_lwt_input_reroute",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish",
        "net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap",
        "net/ipv6/seg6_local.c:input_action_end_dt4",
        "net/ipv6/seg6_local.c:input_action_end_dx4_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590664608,
      "name": "ip_route_input_noref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int ip_route_input_noref(struct sk_buff * skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device * dev)
```

```json
{
  "name": "ip_route_input_noref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592290112,
      "name": "ip_route_input_noref",
      "external": true,
      "loc": "net/ipv4/route.c:2443",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_lwt_input_reroute",
        "net/core/lwt_bpf.c:bpf_lwt_input_reroute",
        "net/core/lwt_bpf.c:bpf_lwt_input_reroute",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish",
        "net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap",
        "net/ipv6/seg6_local.c:input_action_end_dt4",
        "net/ipv6/seg6_local.c:input_action_end_dx4_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592290112,
      "name": "ip_route_input_noref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int ip_route_input_noref(struct sk_buff * skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device * dev)
```

```json
{
  "name": "ip_route_input_noref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594125360,
      "name": "ip_route_input_noref",
      "external": true,
      "loc": "net/ipv4/route.c:2486",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_lwt_input_reroute",
        "net/core/lwt_bpf.c:bpf_lwt_input_reroute",
        "net/core/lwt_bpf.c:bpf_lwt_input_reroute",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish",
        "net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap",
        "net/ipv6/seg6_local.c:input_action_end_dt4",
        "net/ipv6/seg6_local.c:input_action_end_dx4_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594125360,
      "name": "ip_route_input_noref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
int ip_route_input_noref(struct sk_buff * skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device * dev)
```

```json
{
  "name": "ip_route_input_noref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594512336,
      "name": "ip_route_input_noref",
      "external": true,
      "loc": "net/ipv4/route.c:2484",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_lwt_input_reroute",
        "net/core/lwt_bpf.c:bpf_lwt_input_reroute",
        "net/core/lwt_bpf.c:bpf_lwt_input_reroute",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish",
        "net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap",
        "net/ipv6/seg6_local.c:input_action_end_dt4",
        "net/ipv6/seg6_local.c:input_action_end_dx4_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594512336,
      "name": "ip_route_input_noref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
int ip_route_input_noref(struct sk_buff * skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device * dev)
```

```json
{
  "name": "ip_route_input_noref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595315488,
      "name": "ip_route_input_noref",
      "external": true,
      "loc": "net/ipv4/route.c:2487",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_lwt_input_reroute",
        "net/core/lwt_bpf.c:bpf_lwt_input_reroute",
        "net/core/lwt_bpf.c:bpf_lwt_input_reroute",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish",
        "net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap",
        "net/ipv6/seg6_local.c:input_action_end_dt4",
        "net/ipv6/seg6_local.c:input_action_end_dx4_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595315488,
      "name": "ip_route_input_noref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
int ip_route_input_noref(struct sk_buff * skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device * dev)
```

```json
{
  "name": "ip_route_input_noref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502590016,
      "name": "ip_route_input_noref",
      "external": true,
      "loc": "net/ipv4/route.c:2247",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_input",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish",
        "net/ipv6/seg6_local.c:input_action_end_dx4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502590016,
      "name": "ip_route_input_noref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int ip_route_input_noref(struct sk_buff * skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device * dev)
```

```json
{
  "name": "ip_route_input_noref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235295312,
      "name": "ip_route_input_noref",
      "external": true,
      "loc": "net/ipv4/route.c:2247",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_input",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish",
        "net/ipv6/seg6_local.c:input_action_end_dx4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235295312,
      "name": "ip_route_input_noref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int ip_route_input_noref(struct sk_buff * skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device * dev)
```

```json
{
  "name": "ip_route_input_noref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296178976,
      "name": "ip_route_input_noref",
      "external": true,
      "loc": "net/ipv4/route.c:2247",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_input",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish",
        "net/ipv6/seg6_local.c:input_action_end_dx4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296178976,
      "name": "ip_route_input_noref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int ip_route_input_noref(struct sk_buff * skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device * dev)
```

```json
{
  "name": "ip_route_input_noref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278744160,
      "name": "ip_route_input_noref",
      "external": true,
      "loc": "net/ipv4/route.c:2247",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_input",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish",
        "net/ipv6/seg6_local.c:input_action_end_dx4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278744160,
      "name": "ip_route_input_noref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int ip_route_input_noref(struct sk_buff * skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device * dev)
```

```json
{
  "name": "ip_route_input_noref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588591408,
      "name": "ip_route_input_noref",
      "external": true,
      "loc": "net/ipv4/route.c:2247",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_input",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish",
        "net/ipv6/seg6_local.c:input_action_end_dx4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588591408,
      "name": "ip_route_input_noref",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int ip_route_input_noref(struct sk_buff * skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device * dev)
```

```json
{
  "name": "ip_route_input_noref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588303392,
      "name": "ip_route_input_noref",
      "external": true,
      "loc": "net/ipv4/route.c:2247",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_input",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish",
        "net/ipv6/seg6_local.c:input_action_end_dx4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588303392,
      "name": "ip_route_input_noref",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int ip_route_input_noref(struct sk_buff * skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device * dev)
```

```json
{
  "name": "ip_route_input_noref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589027584,
      "name": "ip_route_input_noref",
      "external": true,
      "loc": "net/ipv4/route.c:2247",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_input",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish",
        "net/ipv6/seg6_local.c:input_action_end_dx4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589027584,
      "name": "ip_route_input_noref",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int ip_route_input_noref(struct sk_buff * skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device * dev)
```

```json
{
  "name": "ip_route_input_noref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589066432,
      "name": "ip_route_input_noref",
      "external": true,
      "loc": "net/ipv4/route.c:2247",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_input",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish",
        "net/ipv6/seg6_local.c:input_action_end_dx4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589066432,
      "name": "ip_route_input_noref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
