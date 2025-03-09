# Function: <code>nf_ct_l4proto_find</code>

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
const struct nf_conntrack_l4proto * nf_ct_l4proto_find(u8 l4proto)
```

```json
{
  "name": "nf_ct_l4proto_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588953536,
      "name": "nf_ct_l4proto_find",
      "external": true,
      "loc": "net/netfilter/nf_conntrack_proto.c:97",
      "file": "net/netfilter/nf_conntrack_proto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_conntrack_core.c:gc_worker",
        "net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm",
        "net/netfilter/nf_conntrack_standalone.c:ct_seq_show",
        "net/netfilter/nf_conntrack_expect.c:exp_seq_show",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_exp_dump_expect",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_change_protoinfo",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_parse_tuple_proto",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_proto_size",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_protoinfo",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_tuples"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588953536,
      "name": "nf_ct_l4proto_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
const struct nf_conntrack_l4proto * nf_ct_l4proto_find(u8 l4proto)
```
</details>
</li>
</ul>
