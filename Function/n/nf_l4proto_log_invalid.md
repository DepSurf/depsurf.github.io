# Function: <code>nf_l4proto_log_invalid</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void nf_l4proto_log_invalid(const struct sk_buff * skb, struct net * net, u16 pf, u8 protonum, const char * fmt, void (anon))
```

```json
{
  "name": "nf_l4proto_log_invalid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588957168,
      "name": "nf_l4proto_log_invalid",
      "external": true,
      "loc": "net/netfilter/nf_conntrack_proto.c:51",
      "file": "net/netfilter/nf_conntrack_proto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_conntrack_proto.c:nf_ct_l4proto_log_invalid",
        "net/netfilter/nf_conntrack_proto_tcp.c:nf_conntrack_tcp_packet",
        "net/netfilter/nf_conntrack_proto_udp.c:nf_conntrack_udplite_packet",
        "net/netfilter/nf_conntrack_proto_udp.c:nf_conntrack_udplite_packet",
        "net/netfilter/nf_conntrack_proto_udp.c:nf_conntrack_udplite_packet",
        "net/netfilter/nf_conntrack_proto_udp.c:nf_conntrack_udplite_packet",
        "net/netfilter/nf_conntrack_proto_udp.c:nf_conntrack_udp_packet",
        "net/netfilter/nf_conntrack_proto_udp.c:nf_conntrack_udp_packet",
        "net/netfilter/nf_conntrack_proto_udp.c:nf_conntrack_udp_packet",
        "net/netfilter/nf_conntrack_proto_icmp.c:nf_conntrack_icmpv4_error",
        "net/netfilter/nf_conntrack_proto_icmp.c:nf_conntrack_icmpv4_error",
        "net/netfilter/nf_conntrack_proto_icmp.c:nf_conntrack_icmpv4_error",
        "net/netfilter/nf_conntrack_proto_icmp.c:nf_conntrack_inet_error",
        "net/netfilter/nf_conntrack_proto_icmp.c:nf_conntrack_inet_error",
        "net/netfilter/nf_conntrack_proto_icmpv6.c:nf_conntrack_icmpv6_error",
        "net/netfilter/nf_conntrack_proto_icmpv6.c:nf_conntrack_icmpv6_error",
        "net/netfilter/nf_conntrack_proto_dccp.c:nf_conntrack_dccp_packet",
        "net/netfilter/nf_conntrack_proto_sctp.c:nf_conntrack_sctp_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588957168,
      "name": "nf_l4proto_log_invalid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➕</summary>

```c
void nf_l4proto_log_invalid(const struct sk_buff * skb, struct net * net, u16 pf, u8 protonum, const char * fmt, void (anon))
```
</details>
</li>
</ul>
