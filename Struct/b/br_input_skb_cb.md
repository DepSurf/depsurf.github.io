# Struct: <code>br_input_skb_cb</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct br_input_skb_cb {
    struct net_device * brdev;
    u16 frag_max_size;
    u8 igmp;
    u8 mrouters_only;
    u8 proxyarp_replied;
    u8 src_port_isolated;
    u8 vlan_filtered;
    u8 br_netfilter_broute;
    int offload_fwd_mark;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct br_input_skb_cb {
    struct net_device * brdev;
    u16 frag_max_size;
    u8 igmp;
    u8 mrouters_only;
    u8 proxyarp_replied;
    u8 src_port_isolated;
    u8 vlan_filtered;
    u8 br_netfilter_broute;
    int offload_fwd_mark;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct br_input_skb_cb {
    struct net_device * brdev;
    u16 frag_max_size;
    u8 igmp;
    u8 mrouters_only;
    u8 proxyarp_replied;
    u8 src_port_isolated;
    u8 vlan_filtered;
    u8 br_netfilter_broute;
    int offload_fwd_mark;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct br_input_skb_cb {
    struct net_device * brdev;
    u16 frag_max_size;
    u8 igmp;
    u8 mrouters_only;
    u8 proxyarp_replied;
    u8 src_port_isolated;
    u8 vlan_filtered;
    u8 br_netfilter_broute;
    int offload_fwd_mark;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct br_input_skb_cb {
    struct net_device * brdev;
    u16 frag_max_size;
    u8 igmp;
    u8 mrouters_only;
    u8 proxyarp_replied;
    u8 src_port_isolated;
    u8 vlan_filtered;
    u8 br_netfilter_broute;
    int offload_fwd_mark;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct br_input_skb_cb {
    struct net_device * brdev;
    u16 frag_max_size;
    u8 igmp;
    u8 mrouters_only;
    u8 proxyarp_replied;
    u8 src_port_isolated;
    u8 vlan_filtered;
    u8 br_netfilter_broute;
    u8 tx_fwd_offload;
    int src_hwdom;
    long unsigned int fwd_hwdoms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct br_input_skb_cb {
    struct net_device * brdev;
    u16 frag_max_size;
    u8 igmp;
    u8 mrouters_only;
    u8 proxyarp_replied;
    u8 src_port_isolated;
    u8 vlan_filtered;
    u8 br_netfilter_broute;
    u8 tx_fwd_offload;
    int src_hwdom;
    long unsigned int fwd_hwdoms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct br_input_skb_cb {
    struct net_device * brdev;
    u16 frag_max_size;
    u8 igmp;
    u8 mrouters_only;
    u8 proxyarp_replied;
    u8 src_port_isolated;
    u8 vlan_filtered;
    u8 br_netfilter_broute;
    u8 tx_fwd_offload;
    int src_hwdom;
    long unsigned int fwd_hwdoms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct br_input_skb_cb {
    struct net_device * brdev;
    u16 frag_max_size;
    u8 igmp;
    u8 mrouters_only;
    u8 proxyarp_replied;
    u8 src_port_isolated;
    u8 vlan_filtered;
    u8 br_netfilter_broute;
    u8 tx_fwd_offload;
    int src_hwdom;
    long unsigned int fwd_hwdoms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct br_input_skb_cb {
    struct net_device * brdev;
    u16 frag_max_size;
    u8 igmp;
    u8 mrouters_only;
    u8 proxyarp_replied;
    u8 src_port_isolated;
    u8 vlan_filtered;
    u8 br_netfilter_broute;
    u8 tx_fwd_offload;
    int src_hwdom;
    long unsigned int fwd_hwdoms;
    u32 backup_nhid;
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
struct br_input_skb_cb {
    struct net_device * brdev;
    u16 frag_max_size;
    u8 igmp;
    u8 mrouters_only;
    u8 proxyarp_replied;
    u8 src_port_isolated;
    u8 vlan_filtered;
    u8 br_netfilter_broute;
    int offload_fwd_mark;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct br_input_skb_cb {
    struct net_device * brdev;
    u16 frag_max_size;
    u8 igmp;
    u8 mrouters_only;
    u8 proxyarp_replied;
    u8 src_port_isolated;
    u8 vlan_filtered;
    u8 br_netfilter_broute;
    int offload_fwd_mark;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct br_input_skb_cb {
    struct net_device * brdev;
    u16 frag_max_size;
    u8 igmp;
    u8 mrouters_only;
    u8 proxyarp_replied;
    u8 src_port_isolated;
    u8 vlan_filtered;
    u8 br_netfilter_broute;
    int offload_fwd_mark;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct br_input_skb_cb {
    struct net_device * brdev;
    u16 frag_max_size;
    u8 igmp;
    u8 mrouters_only;
    u8 proxyarp_replied;
    u8 src_port_isolated;
    u8 vlan_filtered;
    u8 br_netfilter_broute;
    int offload_fwd_mark;
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
struct br_input_skb_cb {
    struct net_device * brdev;
    u16 frag_max_size;
    u8 igmp;
    u8 mrouters_only;
    u8 proxyarp_replied;
    u8 src_port_isolated;
    u8 vlan_filtered;
    u8 br_netfilter_broute;
    int offload_fwd_mark;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct br_input_skb_cb {
    struct net_device * brdev;
    u16 frag_max_size;
    u8 igmp;
    u8 mrouters_only;
    u8 proxyarp_replied;
    u8 src_port_isolated;
    u8 vlan_filtered;
    u8 br_netfilter_broute;
    int offload_fwd_mark;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct br_input_skb_cb {
    struct net_device * brdev;
    u16 frag_max_size;
    u8 igmp;
    u8 mrouters_only;
    u8 proxyarp_replied;
    u8 src_port_isolated;
    u8 vlan_filtered;
    u8 br_netfilter_broute;
    int offload_fwd_mark;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct br_input_skb_cb {
    struct net_device * brdev;
    u16 frag_max_size;
    u8 igmp;
    u8 mrouters_only;
    u8 proxyarp_replied;
    u8 src_port_isolated;
    u8 vlan_filtered;
    u8 br_netfilter_broute;
    int offload_fwd_mark;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct br_input_skb_cb {
    struct net_device * brdev;
    u16 frag_max_size;
    u8 igmp;
    u8 mrouters_only;
    u8 proxyarp_replied;
    u8 src_port_isolated;
    u8 vlan_filtered;
    u8 br_netfilter_broute;
    int offload_fwd_mark;
}
```
</details>
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u8 tx_fwd_offload</code>
</li>
<li>
<b>Field added. </b>
<code>int src_hwdom</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int fwd_hwdoms</code>
</li>
<li>
<b>Field removed. </b>
<code>int offload_fwd_mark</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 backup_nhid</code>
</li>
</ul>
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
