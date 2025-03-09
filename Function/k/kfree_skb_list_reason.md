# Function: <code>kfree_skb_list_reason</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kfree_skb_list_reason(struct sk_buff * segs, enum skb_drop_reason reason)
```

```json
{
  "name": "kfree_skb_list_reason",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591416969,
      "name": "kfree_skb_list_reason",
      "external": true,
      "loc": "net/core/skbuff.c:782",
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
      "addr": 18446744071591395984,
      "name": "kfree_skb_list_reason",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void kfree_skb_list_reason(struct sk_buff * segs, enum skb_drop_reason reason)
```

```json
{
  "name": "kfree_skb_list_reason",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593181957,
      "name": "kfree_skb_list_reason",
      "external": true,
      "loc": "net/core/skbuff.c:960",
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
      "addr": 18446744071593163136,
      "name": "kfree_skb_list_reason",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void kfree_skb_list_reason(struct sk_buff * segs, enum skb_drop_reason reason)
```

```json
{
  "name": "kfree_skb_list_reason",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593615792,
      "name": "kfree_skb_list_reason",
      "external": true,
      "loc": "net/core/skbuff.c:1090",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_release_data",
        "net/core/dev.c:__dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
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
      "addr": 18446744071593615792,
      "name": "kfree_skb_list_reason",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 595
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
void kfree_skb_list_reason(struct sk_buff * segs, enum skb_drop_reason reason)
```

```json
{
  "name": "kfree_skb_list_reason",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594390992,
      "name": "kfree_skb_list_reason",
      "external": true,
      "loc": "net/core/skbuff.c:1176",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_release_data",
        "net/core/dev.c:__dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
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
      "addr": 18446744071594390992,
      "name": "kfree_skb_list_reason",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 595
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void kfree_skb_list_reason(struct sk_buff * segs, enum skb_drop_reason reason)
```
</details>
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
