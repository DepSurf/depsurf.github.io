# Function: <code>__build_packet_message</code>

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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int __build_packet_message(struct nfnl_log_net * log, struct nfulnl_instance * inst, const struct sk_buff * skb, unsigned int data_len, u_int8_t pf, unsigned int hooknum, const struct net_device * indev, const struct net_device * outdev, const char * prefix, unsigned int plen, const struct nfnl_ct_hook * nfnl_ct, struct nf_conn * ct, enum ip_conntrack_info ctinfo)
```

```json
{
  "name": "__build_packet_message",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__build_packet_message",
      "external": false,
      "loc": "net/netfilter/nfnetlink_log.c:442",
      "file": "net/netfilter/nfnetlink_log.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nfnetlink_log.c:nfulnl_log_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588920496,
      "name": "__build_packet_message",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2386
    },
    {
      "addr": 18446744071588924006,
      "name": "__build_packet_message.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int __build_packet_message(struct nfnl_log_net * log, struct nfulnl_instance * inst, const struct sk_buff * skb, unsigned int data_len, u_int8_t pf, unsigned int hooknum, const struct net_device * indev, const struct net_device * outdev, const char * prefix, unsigned int plen, const struct nfnl_ct_hook * nfnl_ct, struct nf_conn * ct, enum ip_conntrack_info ctinfo)
```
</details>
</li>
</ul>
