# Function: <code>nf_hook_slow</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int nf_hook_slow(struct sk_buff * skb, struct nf_hook_state * state)
```

```json
{
  "name": "nf_hook_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586519168,
      "name": "nf_hook_slow",
      "external": true,
      "loc": "net/netfilter/core.c:295",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_core",
        "net/ipv4/ip_input.c:ip_local_deliver",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_output.c:xfrm4_output",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/xfrm6_output.c:xfrm6_output",
        "net/ipv6/output_core.c:__ip6_local_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586519168,
      "name": "nf_hook_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int nf_hook_slow(struct sk_buff * skb, struct nf_hook_state * state)
```

```json
{
  "name": "nf_hook_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586961616,
      "name": "nf_hook_slow",
      "external": true,
      "loc": "net/netfilter/core.c:295",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_core",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_output.c:xfrm4_output",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/xfrm6_output.c:xfrm6_output",
        "net/ipv6/output_core.c:__ip6_local_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586961616,
      "name": "nf_hook_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int nf_hook_slow(struct sk_buff * skb, struct nf_hook_state * state, struct nf_hook_entry * entry)
```

```json
{
  "name": "nf_hook_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587154080,
      "name": "nf_hook_slow",
      "external": true,
      "loc": "net/netfilter/core.c:303",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_core",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_output.c:xfrm4_output",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/xfrm6_output.c:xfrm6_output",
        "net/ipv6/output_core.c:__ip6_local_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587154080,
      "name": "nf_hook_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int nf_hook_slow(struct sk_buff * skb, struct nf_hook_state * state, struct nf_hook_entry * entry)
```

```json
{
  "name": "nf_hook_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587286224,
      "name": "nf_hook_slow",
      "external": true,
      "loc": "net/netfilter/core.c:232",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_core",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_output.c:xfrm4_output",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/xfrm6_output.c:xfrm6_output",
        "net/ipv6/output_core.c:__ip6_local_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587286224,
      "name": "nf_hook_slow",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int nf_hook_slow(struct sk_buff * skb, struct nf_hook_state * state, const struct nf_hook_entries * e, unsigned int s)
```

```json
{
  "name": "nf_hook_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587806864,
      "name": "nf_hook_slow",
      "external": true,
      "loc": "net/netfilter/core.c:460",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_core",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_output.c:xfrm4_output",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/xfrm6_output.c:xfrm6_output",
        "net/ipv6/output_core.c:__ip6_local_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587806864,
      "name": "nf_hook_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int nf_hook_slow(struct sk_buff * skb, struct nf_hook_state * state, const struct nf_hook_entries * e, unsigned int s)
```

```json
{
  "name": "nf_hook_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588150032,
      "name": "nf_hook_slow",
      "external": true,
      "loc": "net/netfilter/core.c:504",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_core",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_output.c:xfrm4_output",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/xfrm6_output.c:xfrm6_output",
        "net/ipv6/output_core.c:__ip6_local_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588150032,
      "name": "nf_hook_slow",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int nf_hook_slow(struct sk_buff * skb, struct nf_hook_state * state, const struct nf_hook_entries * e, unsigned int s)
```

```json
{
  "name": "nf_hook_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588333216,
      "name": "nf_hook_slow",
      "external": true,
      "loc": "net/netfilter/core.c:504",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_core",
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_output.c:xfrm4_output",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/xfrm6_output.c:xfrm6_output",
        "net/ipv6/output_core.c:__ip6_local_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588333216,
      "name": "nf_hook_slow",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int nf_hook_slow(struct sk_buff * skb, struct nf_hook_state * state, const struct nf_hook_entries * e, unsigned int s)
```

```json
{
  "name": "nf_hook_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588733584,
      "name": "nf_hook_slow",
      "external": true,
      "loc": "net/netfilter/core.c:505",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_core",
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_output.c:xfrm4_output",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/xfrm6_output.c:xfrm6_output",
        "net/ipv6/output_core.c:__ip6_local_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588733584,
      "name": "nf_hook_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int nf_hook_slow(struct sk_buff * skb, struct nf_hook_state * state, const struct nf_hook_entries * e, unsigned int s)
```

```json
{
  "name": "nf_hook_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588957392,
      "name": "nf_hook_slow",
      "external": true,
      "loc": "net/netfilter/core.c:505",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_core",
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_output.c:xfrm4_output",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/xfrm6_output.c:xfrm6_output",
        "net/ipv6/output_core.c:__ip6_local_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588957392,
      "name": "nf_hook_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int nf_hook_slow(struct sk_buff * skb, struct nf_hook_state * state, const struct nf_hook_entries * e, unsigned int s)
```

```json
{
  "name": "nf_hook_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589911536,
      "name": "nf_hook_slow",
      "external": true,
      "loc": "net/netfilter/core.c:505",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_core",
        "net/netfilter/core.c:nf_hook_slow_list",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_output.c:xfrm4_output",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/xfrm6_output.c:xfrm6_output",
        "net/ipv6/output_core.c:__ip6_local_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589911536,
      "name": "nf_hook_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int nf_hook_slow(struct sk_buff * skb, struct nf_hook_state * state, const struct nf_hook_entries * e, unsigned int s)
```

```json
{
  "name": "nf_hook_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589952448,
      "name": "nf_hook_slow",
      "external": true,
      "loc": "net/netfilter/core.c:582",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_core",
        "net/netfilter/core.c:nf_hook_slow_list",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_output.c:xfrm4_output",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/xfrm6_output.c:xfrm6_output",
        "net/ipv6/output_core.c:__ip6_local_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589952448,
      "name": "nf_hook_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int nf_hook_slow(struct sk_buff * skb, struct nf_hook_state * state, const struct nf_hook_entries * e, unsigned int s)
```

```json
{
  "name": "nf_hook_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589867280,
      "name": "nf_hook_slow",
      "external": true,
      "loc": "net/netfilter/core.c:582",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_hook_slow_list",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_output.c:xfrm4_output",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/xfrm6_output.c:xfrm6_output",
        "net/ipv6/output_core.c:__ip6_local_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589867280,
      "name": "nf_hook_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int nf_hook_slow(struct sk_buff * skb, struct nf_hook_state * state, const struct nf_hook_entries * e, unsigned int s)
```

```json
{
  "name": "nf_hook_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590628256,
      "name": "nf_hook_slow",
      "external": true,
      "loc": "net/netfilter/core.c:583",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_hook_slow_list",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_output.c:xfrm4_output",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/xfrm6_output.c:xfrm6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input",
        "net/ipv6/seg6_iptunnel.c:seg6_input_core",
        "net/ipv6/seg6_local.c:seg6_local_input",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/output_core.c:__ip6_local_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590628256,
      "name": "nf_hook_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int nf_hook_slow(struct sk_buff * skb, struct nf_hook_state * state, const struct nf_hook_entries * e, unsigned int s)
```

```json
{
  "name": "nf_hook_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592251440,
      "name": "nf_hook_slow",
      "external": true,
      "loc": "net/netfilter/core.c:613",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/netfilter/core.c:nf_hook_slow_list",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv4/arp.c:arp_rcv",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_output.c:xfrm4_output",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/xfrm6_output.c:xfrm6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input",
        "net/ipv6/seg6_iptunnel.c:seg6_input_core",
        "net/ipv6/seg6_local.c:seg6_local_input",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/output_core.c:__ip6_local_out",
        "net/packet/af_packet.c:nf_hook_direct_egress"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592251440,
      "name": "nf_hook_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int nf_hook_slow(struct sk_buff * skb, struct nf_hook_state * state, const struct nf_hook_entries * e, unsigned int s)
```

```json
{
  "name": "nf_hook_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594085296,
      "name": "nf_hook_slow",
      "external": true,
      "loc": "net/netfilter/core.c:607",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/netfilter/core.c:nf_hook_slow_list",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv4/arp.c:arp_rcv",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_output.c:xfrm4_output",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/xfrm6_output.c:xfrm6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input",
        "net/ipv6/seg6_iptunnel.c:seg6_input_core",
        "net/ipv6/seg6_local.c:seg6_local_input",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/output_core.c:__ip6_local_out",
        "net/packet/af_packet.c:nf_hook_direct_egress"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594085296,
      "name": "nf_hook_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int nf_hook_slow(struct sk_buff * skb, struct nf_hook_state * state, const struct nf_hook_entries * e, unsigned int s)
```

```json
{
  "name": "nf_hook_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594470176,
      "name": "nf_hook_slow",
      "external": true,
      "loc": "net/netfilter/core.c:619",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/netfilter/core.c:nf_hook_slow_list",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv4/arp.c:arp_rcv",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_output.c:xfrm4_output",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/xfrm6_output.c:xfrm6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input_core",
        "net/ipv6/seg6_local.c:seg6_local_input",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/output_core.c:__ip6_local_out",
        "net/packet/af_packet.c:nf_hook_direct_egress"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594470176,
      "name": "nf_hook_slow",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int nf_hook_slow(struct sk_buff * skb, struct nf_hook_state * state, const struct nf_hook_entries * e, unsigned int s)
```

```json
{
  "name": "nf_hook_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595272400,
      "name": "nf_hook_slow",
      "external": true,
      "loc": "net/netfilter/core.c:619",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/netfilter/core.c:nf_hook_slow_list",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv4/arp.c:arp_rcv",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_output.c:xfrm4_output",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/xfrm6_output.c:xfrm6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input_core",
        "net/ipv6/seg6_local.c:seg6_local_input",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/output_core.c:__ip6_local_out",
        "net/packet/af_packet.c:nf_hook_direct_egress"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595272400,
      "name": "nf_hook_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
int nf_hook_slow(struct sk_buff * skb, struct nf_hook_state * state, const struct nf_hook_entries * e, unsigned int s)
```

```json
{
  "name": "nf_hook_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502559056,
      "name": "nf_hook_slow",
      "external": true,
      "loc": "net/netfilter/core.c:505",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_core",
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_output.c:xfrm4_output",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/xfrm6_output.c:xfrm6_output",
        "net/ipv6/output_core.c:__ip6_local_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502559056,
      "name": "nf_hook_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int nf_hook_slow(struct sk_buff * skb, struct nf_hook_state * state, const struct nf_hook_entries * e, unsigned int s)
```

```json
{
  "name": "nf_hook_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235266228,
      "name": "nf_hook_slow",
      "external": true,
      "loc": "net/netfilter/core.c:505",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_core",
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_output.c:xfrm4_output",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/ip6mr.c:ip6mr_forward2",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/xfrm6_output.c:xfrm6_output",
        "net/ipv6/output_core.c:__ip6_local_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235266228,
      "name": "nf_hook_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int nf_hook_slow(struct sk_buff * skb, struct nf_hook_state * state, const struct nf_hook_entries * e, unsigned int s)
```

```json
{
  "name": "nf_hook_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296138624,
      "name": "nf_hook_slow",
      "external": true,
      "loc": "net/netfilter/core.c:505",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_core",
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_output.c:xfrm4_output",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/xfrm6_output.c:xfrm6_output",
        "net/ipv6/output_core.c:__ip6_local_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296138624,
      "name": "nf_hook_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int nf_hook_slow(struct sk_buff * skb, struct nf_hook_state * state, const struct nf_hook_entries * e, unsigned int s)
```

```json
{
  "name": "nf_hook_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278718642,
      "name": "nf_hook_slow",
      "external": true,
      "loc": "net/netfilter/core.c:505",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_core",
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_output.c:xfrm4_output",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/xfrm6_output.c:xfrm6_output",
        "net/ipv6/output_core.c:__ip6_local_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278718642,
      "name": "nf_hook_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int nf_hook_slow(struct sk_buff * skb, struct nf_hook_state * state, const struct nf_hook_entries * e, unsigned int s)
```

```json
{
  "name": "nf_hook_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588563776,
      "name": "nf_hook_slow",
      "external": true,
      "loc": "net/netfilter/core.c:505",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_core",
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_output.c:xfrm4_output",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/xfrm6_output.c:xfrm6_output",
        "net/ipv6/output_core.c:__ip6_local_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588563776,
      "name": "nf_hook_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int nf_hook_slow(struct sk_buff * skb, struct nf_hook_state * state, const struct nf_hook_entries * e, unsigned int s)
```

```json
{
  "name": "nf_hook_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588275760,
      "name": "nf_hook_slow",
      "external": true,
      "loc": "net/netfilter/core.c:505",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_core",
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_output.c:xfrm4_output",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/xfrm6_output.c:xfrm6_output",
        "net/ipv6/output_core.c:__ip6_local_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588275760,
      "name": "nf_hook_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int nf_hook_slow(struct sk_buff * skb, struct nf_hook_state * state, const struct nf_hook_entries * e, unsigned int s)
```

```json
{
  "name": "nf_hook_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588895952,
      "name": "nf_hook_slow",
      "external": true,
      "loc": "net/netfilter/core.c:505",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_core",
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_output.c:xfrm4_output",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/xfrm6_output.c:xfrm6_output",
        "net/ipv6/output_core.c:__ip6_local_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588895952,
      "name": "nf_hook_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int nf_hook_slow(struct sk_buff * skb, struct nf_hook_state * state, const struct nf_hook_entries * e, unsigned int s)
```

```json
{
  "name": "nf_hook_slow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589038256,
      "name": "nf_hook_slow",
      "external": true,
      "loc": "net/netfilter/core.c:505",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_core",
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv4/xfrm4_input.c:xfrm4_transport_finish",
        "net/ipv4/xfrm4_output.c:xfrm4_output",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_input",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/xfrm6_output.c:xfrm6_output",
        "net/ipv6/output_core.c:__ip6_local_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589038256,
      "name": "nf_hook_slow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct nf_hook_entry * entry</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct nf_hook_entries * e</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int s</code>
</li>
<li>
<b>Param removed. </b>
<code>struct nf_hook_entry * entry</code>
</li>
</ul>
</details>
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
