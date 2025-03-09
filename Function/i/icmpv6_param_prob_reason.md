# Function: <code>icmpv6_param_prob_reason</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void icmpv6_param_prob_reason(struct sk_buff * skb, u8 code, int pos, enum skb_drop_reason reason)
```

```json
{
  "name": "icmpv6_param_prob_reason",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593264464,
      "name": "icmpv6_param_prob_reason",
      "external": true,
      "loc": "net/ipv6/icmp.c:634",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ip6_parse_tlv",
        "net/ipv6/exthdrs.c:ip6_parse_tlv",
        "net/ipv6/exthdrs.c:ip6_tlvopt_unknown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593264464,
      "name": "icmpv6_param_prob_reason",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void icmpv6_param_prob_reason(struct sk_buff * skb, u8 code, int pos, enum skb_drop_reason reason)
```

```json
{
  "name": "icmpv6_param_prob_reason",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595166928,
      "name": "icmpv6_param_prob_reason",
      "external": true,
      "loc": "net/ipv6/icmp.c:634",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ip6_parse_tlv",
        "net/ipv6/exthdrs.c:ip6_parse_tlv",
        "net/ipv6/exthdrs.c:ip6_tlvopt_unknown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595166928,
      "name": "icmpv6_param_prob_reason",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void icmpv6_param_prob_reason(struct sk_buff * skb, u8 code, int pos, enum skb_drop_reason reason)
```

```json
{
  "name": "icmpv6_param_prob_reason",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595562384,
      "name": "icmpv6_param_prob_reason",
      "external": true,
      "loc": "net/ipv6/icmp.c:639",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ip6_parse_tlv",
        "net/ipv6/exthdrs.c:ip6_parse_tlv",
        "net/ipv6/exthdrs.c:ip6_tlvopt_unknown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595562384,
      "name": "icmpv6_param_prob_reason",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void icmpv6_param_prob_reason(struct sk_buff * skb, u8 code, int pos, enum skb_drop_reason reason)
```

```json
{
  "name": "icmpv6_param_prob_reason",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596405136,
      "name": "icmpv6_param_prob_reason",
      "external": true,
      "loc": "net/ipv6/icmp.c:639",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ip6_parse_tlv",
        "net/ipv6/exthdrs.c:ip6_parse_tlv",
        "net/ipv6/exthdrs.c:ip6_tlvopt_unknown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596405136,
      "name": "icmpv6_param_prob_reason",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void icmpv6_param_prob_reason(struct sk_buff * skb, u8 code, int pos, enum skb_drop_reason reason)
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
