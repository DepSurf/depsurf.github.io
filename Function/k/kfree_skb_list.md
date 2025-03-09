# Function: <code>kfree_skb_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kfree_skb_list(struct sk_buff * segs)
```

```json
{
  "name": "kfree_skb_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586209952,
      "name": "kfree_skb_list",
      "external": true,
      "loc": "net/core/skbuff.c:708",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_segment"
      ],
      "caller_func": [
        "net/core/skbuff.c:skb_release_data",
        "net/core/dev.c:netif_napi_del",
        "net/core/dev.c:__dev_queue_xmit",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/ipv6/ip6_output.c:ip6_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586209952,
      "name": "kfree_skb_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void kfree_skb_list(struct sk_buff * segs)
```

```json
{
  "name": "kfree_skb_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586655805,
      "name": "kfree_skb_list",
      "external": true,
      "loc": "net/core/skbuff.c:709",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:___pskb_trim"
      ],
      "caller_func": [
        "net/core/skbuff.c:skb_release_data",
        "net/core/dev.c:netif_napi_del",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/ipv6/ip6_output.c:ip6_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586636048,
      "name": "kfree_skb_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void kfree_skb_list(struct sk_buff * segs)
```

```json
{
  "name": "kfree_skb_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586840526,
      "name": "kfree_skb_list",
      "external": true,
      "loc": "net/core/skbuff.c:709",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:___pskb_trim"
      ],
      "caller_func": [
        "net/core/skbuff.c:skb_release_data",
        "net/core/dev.c:netif_napi_del",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/packet/af_packet.c:packet_direct_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586821456,
      "name": "kfree_skb_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void kfree_skb_list(struct sk_buff * segs)
```

```json
{
  "name": "kfree_skb_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586967504,
      "name": "kfree_skb_list",
      "external": true,
      "loc": "net/core/skbuff.c:703",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": [
        "net/core/dev.c:netif_napi_del",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment",
        "net/packet/af_packet.c:packet_direct_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586952560,
      "name": "kfree_skb_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void kfree_skb_list(struct sk_buff * segs)
```

```json
{
  "name": "kfree_skb_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587465473,
      "name": "kfree_skb_list",
      "external": true,
      "loc": "net/core/skbuff.c:663",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": [
        "net/core/dev.c:netif_napi_del",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment",
        "net/packet/af_packet.c:packet_direct_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587444240,
      "name": "kfree_skb_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void kfree_skb_list(struct sk_buff * segs)
```

```json
{
  "name": "kfree_skb_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587770181,
      "name": "kfree_skb_list",
      "external": true,
      "loc": "net/core/skbuff.c:663",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": [
        "net/core/dev.c:netif_napi_del",
        "net/core/dev.c:dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587748528,
      "name": "kfree_skb_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void kfree_skb_list(struct sk_buff * segs)
```

```json
{
  "name": "kfree_skb_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587903906,
      "name": "kfree_skb_list",
      "external": true,
      "loc": "net/core/skbuff.c:667",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": [
        "net/core/dev.c:dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587882624,
      "name": "kfree_skb_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void kfree_skb_list(struct sk_buff * segs)
```

```json
{
  "name": "kfree_skb_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588210469,
      "name": "kfree_skb_list",
      "external": true,
      "loc": "net/core/skbuff.c:701",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": [
        "net/core/dev.c:dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/netfilter.c:br_ip6_fragment",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588187888,
      "name": "kfree_skb_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void kfree_skb_list(struct sk_buff * segs)
```

```json
{
  "name": "kfree_skb_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588415521,
      "name": "kfree_skb_list",
      "external": true,
      "loc": "net/core/skbuff.c:701",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": [
        "net/core/dev.c:dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/netfilter.c:br_ip6_fragment",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588393040,
      "name": "kfree_skb_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void kfree_skb_list(struct sk_buff * segs)
```

```json
{
  "name": "kfree_skb_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589264515,
      "name": "kfree_skb_list",
      "external": true,
      "loc": "net/core/skbuff.c:700",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": [
        "net/core/dev.c:dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/netfilter.c:br_ip6_fragment",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589256544,
      "name": "kfree_skb_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void kfree_skb_list(struct sk_buff * segs)
```

```json
{
  "name": "kfree_skb_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589263660,
      "name": "kfree_skb_list",
      "external": true,
      "loc": "net/core/skbuff.c:714",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": [
        "net/core/dev.c:__dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/netfilter.c:br_ip6_fragment",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589255680,
      "name": "kfree_skb_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void kfree_skb_list(struct sk_buff * segs)
```

```json
{
  "name": "kfree_skb_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589175359,
      "name": "kfree_skb_list",
      "external": true,
      "loc": "net/core/skbuff.c:762",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": [
        "net/core/dev.c:__dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/netfilter.c:br_ip6_fragment",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589148304,
      "name": "kfree_skb_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void kfree_skb_list(struct sk_buff * segs)
```

```json
{
  "name": "kfree_skb_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589896361,
      "name": "kfree_skb_list",
      "external": true,
      "loc": "net/core/skbuff.c:778",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": [
        "net/core/dev.c:__dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/netfilter.c:br_ip6_fragment",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589868528,
      "name": "kfree_skb_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kfree_skb_list",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591416969,
      "name": "kfree_skb_list",
      "external": false,
      "loc": "include/linux/skbuff.h:1384",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591531106,
      "name": "kfree_skb_list",
      "external": false,
      "loc": "include/linux/skbuff.h:1384",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592322420,
      "name": "kfree_skb_list",
      "external": false,
      "loc": "include/linux/skbuff.h:1384",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592968591,
      "name": "kfree_skb_list",
      "external": false,
      "loc": "include/linux/skbuff.h:1384",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592977482,
      "name": "kfree_skb_list",
      "external": false,
      "loc": "include/linux/skbuff.h:1384",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593043948,
      "name": "kfree_skb_list",
      "external": false,
      "loc": "include/linux/skbuff.h:1384",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593399472,
      "name": "kfree_skb_list",
      "external": false,
      "loc": "include/linux/skbuff.h:1384",
      "file": "net/ipv6/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/netfilter.c:br_ip6_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593453539,
      "name": "kfree_skb_list",
      "external": false,
      "loc": "include/linux/skbuff.h:1384",
      "file": "net/ipv6/ip6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_offload.c:ipv6_gso_segment"
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
  "name": "kfree_skb_list",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593181957,
      "name": "kfree_skb_list",
      "external": false,
      "loc": "include/linux/skbuff.h:1227",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:___pskb_trim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593304674,
      "name": "kfree_skb_list",
      "external": false,
      "loc": "include/linux/skbuff.h:1227",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594159412,
      "name": "kfree_skb_list",
      "external": false,
      "loc": "include/linux/skbuff.h:1227",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594854959,
      "name": "kfree_skb_list",
      "external": false,
      "loc": "include/linux/skbuff.h:1227",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594865568,
      "name": "kfree_skb_list",
      "external": false,
      "loc": "include/linux/skbuff.h:1227",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594936192,
      "name": "kfree_skb_list",
      "external": false,
      "loc": "include/linux/skbuff.h:1227",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595309328,
      "name": "kfree_skb_list",
      "external": false,
      "loc": "include/linux/skbuff.h:1227",
      "file": "net/ipv6/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/netfilter.c:br_ip6_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595369430,
      "name": "kfree_skb_list",
      "external": false,
      "loc": "include/linux/skbuff.h:1227",
      "file": "net/ipv6/ip6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_offload.c:ipv6_gso_segment"
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
  "name": "kfree_skb_list",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593640326,
      "name": "kfree_skb_list",
      "external": false,
      "loc": "include/linux/skbuff.h:1246",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:___pskb_trim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593766370,
      "name": "kfree_skb_list",
      "external": false,
      "loc": "include/linux/skbuff.h:1246",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594546889,
      "name": "kfree_skb_list",
      "external": false,
      "loc": "include/linux/skbuff.h:1246",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595246095,
      "name": "kfree_skb_list",
      "external": false,
      "loc": "include/linux/skbuff.h:1246",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595257331,
      "name": "kfree_skb_list",
      "external": false,
      "loc": "include/linux/skbuff.h:1246",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595328451,
      "name": "kfree_skb_list",
      "external": false,
      "loc": "include/linux/skbuff.h:1246",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595704364,
      "name": "kfree_skb_list",
      "external": false,
      "loc": "include/linux/skbuff.h:1246",
      "file": "net/ipv6/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/netfilter.c:br_ip6_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595766614,
      "name": "kfree_skb_list",
      "external": false,
      "loc": "include/linux/skbuff.h:1246",
      "file": "net/ipv6/ip6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_offload.c:ipv6_gso_segment"
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
  "name": "kfree_skb_list",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594416259,
      "name": "kfree_skb_list",
      "external": false,
      "loc": "include/linux/skbuff.h:1253",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:___pskb_trim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594545526,
      "name": "kfree_skb_list",
      "external": false,
      "loc": "include/linux/skbuff.h:1253",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595349478,
      "name": "kfree_skb_list",
      "external": false,
      "loc": "include/linux/skbuff.h:1253",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596086591,
      "name": "kfree_skb_list",
      "external": false,
      "loc": "include/linux/skbuff.h:1253",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596097749,
      "name": "kfree_skb_list",
      "external": false,
      "loc": "include/linux/skbuff.h:1253",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596169650,
      "name": "kfree_skb_list",
      "external": false,
      "loc": "include/linux/skbuff.h:1253",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596552579,
      "name": "kfree_skb_list",
      "external": false,
      "loc": "include/linux/skbuff.h:1253",
      "file": "net/ipv6/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/netfilter.c:br_ip6_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596614710,
      "name": "kfree_skb_list",
      "external": false,
      "loc": "include/linux/skbuff.h:1253",
      "file": "net/ipv6/ip6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_offload.c:ipv6_gso_segment"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void kfree_skb_list(struct sk_buff * segs)
```

```json
{
  "name": "kfree_skb_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501932432,
      "name": "kfree_skb_list",
      "external": true,
      "loc": "net/core/skbuff.c:701",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": [
        "net/core/dev.c:dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/netfilter.c:br_ip6_fragment",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501908592,
      "name": "kfree_skb_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void kfree_skb_list(struct sk_buff * segs)
```

```json
{
  "name": "kfree_skb_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234691484,
      "name": "kfree_skb_list",
      "external": true,
      "loc": "net/core/skbuff.c:701",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": [
        "net/core/dev.c:dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/netfilter.c:br_ip6_fragment",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234669880,
      "name": "kfree_skb_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void kfree_skb_list(struct sk_buff * segs)
```

```json
{
  "name": "kfree_skb_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295352624,
      "name": "kfree_skb_list",
      "external": true,
      "loc": "net/core/skbuff.c:701",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": [
        "net/core/dev.c:dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/netfilter.c:br_ip6_fragment",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295321472,
      "name": "kfree_skb_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void kfree_skb_list(struct sk_buff * segs)
```

```json
{
  "name": "kfree_skb_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278241670,
      "name": "kfree_skb_list",
      "external": true,
      "loc": "net/core/skbuff.c:701",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": [
        "net/core/dev.c:dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/netfilter.c:br_ip6_fragment",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278222056,
      "name": "kfree_skb_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void kfree_skb_list(struct sk_buff * segs)
```

```json
{
  "name": "kfree_skb_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588022305,
      "name": "kfree_skb_list",
      "external": true,
      "loc": "net/core/skbuff.c:701",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": [
        "net/core/dev.c:dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/netfilter.c:br_ip6_fragment",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587999824,
      "name": "kfree_skb_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void kfree_skb_list(struct sk_buff * segs)
```

```json
{
  "name": "kfree_skb_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587735393,
      "name": "kfree_skb_list",
      "external": true,
      "loc": "net/core/skbuff.c:701",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": [
        "net/core/dev.c:dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/netfilter.c:br_ip6_fragment",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587712912,
      "name": "kfree_skb_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void kfree_skb_list(struct sk_buff * segs)
```

```json
{
  "name": "kfree_skb_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588354081,
      "name": "kfree_skb_list",
      "external": true,
      "loc": "net/core/skbuff.c:701",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": [
        "net/core/dev.c:dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/netfilter.c:br_ip6_fragment",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588331600,
      "name": "kfree_skb_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void kfree_skb_list(struct sk_buff * segs)
```

```json
{
  "name": "kfree_skb_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588489601,
      "name": "kfree_skb_list",
      "external": true,
      "loc": "net/core/skbuff.c:701",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": [
        "net/core/dev.c:dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/netfilter.c:br_ip6_fragment",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588467072,
      "name": "kfree_skb_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void kfree_skb_list(struct sk_buff * segs)
```
</details>
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
