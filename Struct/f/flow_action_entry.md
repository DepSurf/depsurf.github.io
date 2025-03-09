# Struct: <code>flow_action_entry</code>

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
struct flow_action_entry {
    enum flow_action_id id;
    u32 chain_index;
    struct net_device * dev;
    struct (anon) vlan;
    struct (anon) mangle;
    const struct ip_tunnel_info * tunnel;
    u32 csum_flags;
    u32 mark;
    struct (anon) queue;
    struct (anon) sample;
    struct (anon) police;
    struct (anon) ct;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct flow_action_entry {
    enum flow_action_id id;
    action_destr destructor;
    void * destructor_priv;
    u32 chain_index;
    struct net_device * dev;
    struct (anon) vlan;
    struct (anon) mangle;
    struct ip_tunnel_info * tunnel;
    u32 csum_flags;
    u32 mark;
    u16 ptype;
    struct (anon) queue;
    struct (anon) sample;
    struct (anon) police;
    struct (anon) ct;
    struct (anon) mpls_push;
    struct (anon) mpls_pop;
    struct (anon) mpls_mangle;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct flow_action_entry {
    enum flow_action_id id;
    enum flow_action_hw_stats hw_stats;
    action_destr destructor;
    void * destructor_priv;
    u32 chain_index;
    struct net_device * dev;
    struct (anon) vlan;
    struct (anon) mangle;
    struct ip_tunnel_info * tunnel;
    u32 csum_flags;
    u32 mark;
    u16 ptype;
    u32 priority;
    struct (anon) queue;
    struct (anon) sample;
    struct (anon) police;
    struct (anon) ct;
    struct (anon) ct_metadata;
    struct (anon) mpls_push;
    struct (anon) mpls_pop;
    struct (anon) mpls_mangle;
    struct (anon) gate;
    struct flow_action_cookie * cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct flow_action_entry {
    enum flow_action_id id;
    enum flow_action_hw_stats hw_stats;
    action_destr destructor;
    void * destructor_priv;
    u32 chain_index;
    struct net_device * dev;
    struct (anon) vlan;
    struct (anon) mangle;
    struct ip_tunnel_info * tunnel;
    u32 csum_flags;
    u32 mark;
    u16 ptype;
    u32 priority;
    struct (anon) queue;
    struct (anon) sample;
    struct (anon) police;
    struct (anon) ct;
    struct (anon) ct_metadata;
    struct (anon) mpls_push;
    struct (anon) mpls_pop;
    struct (anon) mpls_mangle;
    struct (anon) gate;
    struct flow_action_cookie * cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct flow_action_entry {
    enum flow_action_id id;
    enum flow_action_hw_stats hw_stats;
    action_destr destructor;
    void * destructor_priv;
    u32 chain_index;
    struct net_device * dev;
    struct (anon) vlan;
    struct (anon) mangle;
    struct ip_tunnel_info * tunnel;
    u32 csum_flags;
    u32 mark;
    u16 ptype;
    u32 priority;
    struct (anon) queue;
    struct (anon) sample;
    struct (anon) police;
    struct (anon) ct;
    struct (anon) ct_metadata;
    struct (anon) mpls_push;
    struct (anon) mpls_pop;
    struct (anon) mpls_mangle;
    struct (anon) gate;
    struct (anon) pppoe;
    struct flow_action_cookie * cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct flow_action_entry {
    enum flow_action_id id;
    enum flow_action_hw_stats hw_stats;
    action_destr destructor;
    void * destructor_priv;
    u32 chain_index;
    struct net_device * dev;
    struct (anon) vlan;
    struct (anon) mangle;
    struct ip_tunnel_info * tunnel;
    u32 csum_flags;
    u32 mark;
    u16 ptype;
    u32 priority;
    struct (anon) queue;
    struct (anon) sample;
    struct (anon) police;
    struct (anon) ct;
    struct (anon) ct_metadata;
    struct (anon) mpls_push;
    struct (anon) mpls_pop;
    struct (anon) mpls_mangle;
    struct (anon) gate;
    struct (anon) pppoe;
    struct flow_action_cookie * cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct flow_action_entry {
    enum flow_action_id id;
    u32 hw_index;
    enum flow_action_hw_stats hw_stats;
    action_destr destructor;
    void * destructor_priv;
    u32 chain_index;
    struct net_device * dev;
    struct (anon) vlan;
    struct (anon) vlan_push_eth;
    struct (anon) mangle;
    struct ip_tunnel_info * tunnel;
    u32 csum_flags;
    u32 mark;
    u16 ptype;
    u32 priority;
    struct (anon) queue;
    struct (anon) sample;
    struct (anon) police;
    struct (anon) ct;
    struct (anon) ct_metadata;
    struct (anon) mpls_push;
    struct (anon) mpls_pop;
    struct (anon) mpls_mangle;
    struct (anon) gate;
    struct (anon) pppoe;
    struct flow_action_cookie * cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct flow_action_entry {
    enum flow_action_id id;
    u32 hw_index;
    enum flow_action_hw_stats hw_stats;
    action_destr destructor;
    void * destructor_priv;
    u32 chain_index;
    struct net_device * dev;
    struct (anon) vlan;
    struct (anon) vlan_push_eth;
    struct (anon) mangle;
    struct ip_tunnel_info * tunnel;
    u32 csum_flags;
    u32 mark;
    u16 ptype;
    u16 rx_queue;
    u32 priority;
    struct (anon) queue;
    struct (anon) sample;
    struct (anon) police;
    struct (anon) ct;
    struct (anon) ct_metadata;
    struct (anon) mpls_push;
    struct (anon) mpls_pop;
    struct (anon) mpls_mangle;
    struct (anon) gate;
    struct (anon) pppoe;
    struct flow_action_cookie * cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct flow_action_entry {
    enum flow_action_id id;
    u32 hw_index;
    long unsigned int cookie;
    u64 miss_cookie;
    enum flow_action_hw_stats hw_stats;
    action_destr destructor;
    void * destructor_priv;
    u32 chain_index;
    struct net_device * dev;
    struct (anon) vlan;
    struct (anon) vlan_push_eth;
    struct (anon) mangle;
    struct ip_tunnel_info * tunnel;
    u32 csum_flags;
    u32 mark;
    u16 ptype;
    u16 rx_queue;
    u32 priority;
    struct (anon) queue;
    struct (anon) sample;
    struct (anon) police;
    struct (anon) ct;
    struct (anon) ct_metadata;
    struct (anon) mpls_push;
    struct (anon) mpls_pop;
    struct (anon) mpls_mangle;
    struct (anon) gate;
    struct (anon) pppoe;
    struct flow_action_cookie * user_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct flow_action_entry {
    enum flow_action_id id;
    u32 hw_index;
    long unsigned int cookie;
    u64 miss_cookie;
    enum flow_action_hw_stats hw_stats;
    action_destr destructor;
    void * destructor_priv;
    u32 chain_index;
    struct net_device * dev;
    struct (anon) vlan;
    struct (anon) vlan_push_eth;
    struct (anon) mangle;
    struct ip_tunnel_info * tunnel;
    u32 csum_flags;
    u32 mark;
    u16 ptype;
    u16 rx_queue;
    u32 priority;
    struct (anon) queue;
    struct (anon) sample;
    struct (anon) police;
    struct (anon) ct;
    struct (anon) ct_metadata;
    struct (anon) mpls_push;
    struct (anon) mpls_pop;
    struct (anon) mpls_mangle;
    struct (anon) gate;
    struct (anon) pppoe;
    struct flow_action_cookie * user_cookie;
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
struct flow_action_entry {
    enum flow_action_id id;
    action_destr destructor;
    void * destructor_priv;
    u32 chain_index;
    struct net_device * dev;
    struct (anon) vlan;
    struct (anon) mangle;
    struct ip_tunnel_info * tunnel;
    u32 csum_flags;
    u32 mark;
    u16 ptype;
    struct (anon) queue;
    struct (anon) sample;
    struct (anon) police;
    struct (anon) ct;
    struct (anon) mpls_push;
    struct (anon) mpls_pop;
    struct (anon) mpls_mangle;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct flow_action_entry {
    enum flow_action_id id;
    action_destr destructor;
    void * destructor_priv;
    u32 chain_index;
    struct net_device * dev;
    struct (anon) vlan;
    struct (anon) mangle;
    struct ip_tunnel_info * tunnel;
    u32 csum_flags;
    u32 mark;
    u16 ptype;
    struct (anon) queue;
    struct (anon) sample;
    struct (anon) police;
    struct (anon) ct;
    struct (anon) mpls_push;
    struct (anon) mpls_pop;
    struct (anon) mpls_mangle;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct flow_action_entry {
    enum flow_action_id id;
    action_destr destructor;
    void * destructor_priv;
    u32 chain_index;
    struct net_device * dev;
    struct (anon) vlan;
    struct (anon) mangle;
    struct ip_tunnel_info * tunnel;
    u32 csum_flags;
    u32 mark;
    u16 ptype;
    struct (anon) queue;
    struct (anon) sample;
    struct (anon) police;
    struct (anon) ct;
    struct (anon) mpls_push;
    struct (anon) mpls_pop;
    struct (anon) mpls_mangle;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct flow_action_entry {
    enum flow_action_id id;
    action_destr destructor;
    void * destructor_priv;
    u32 chain_index;
    struct net_device * dev;
    struct (anon) vlan;
    struct (anon) mangle;
    struct ip_tunnel_info * tunnel;
    u32 csum_flags;
    u32 mark;
    u16 ptype;
    struct (anon) queue;
    struct (anon) sample;
    struct (anon) police;
    struct (anon) ct;
    struct (anon) mpls_push;
    struct (anon) mpls_pop;
    struct (anon) mpls_mangle;
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
struct flow_action_entry {
    enum flow_action_id id;
    action_destr destructor;
    void * destructor_priv;
    u32 chain_index;
    struct net_device * dev;
    struct (anon) vlan;
    struct (anon) mangle;
    struct ip_tunnel_info * tunnel;
    u32 csum_flags;
    u32 mark;
    u16 ptype;
    struct (anon) queue;
    struct (anon) sample;
    struct (anon) police;
    struct (anon) ct;
    struct (anon) mpls_push;
    struct (anon) mpls_pop;
    struct (anon) mpls_mangle;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct flow_action_entry {
    enum flow_action_id id;
    action_destr destructor;
    void * destructor_priv;
    u32 chain_index;
    struct net_device * dev;
    struct (anon) vlan;
    struct (anon) mangle;
    struct ip_tunnel_info * tunnel;
    u32 csum_flags;
    u32 mark;
    u16 ptype;
    struct (anon) queue;
    struct (anon) sample;
    struct (anon) police;
    struct (anon) ct;
    struct (anon) mpls_push;
    struct (anon) mpls_pop;
    struct (anon) mpls_mangle;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct flow_action_entry {
    enum flow_action_id id;
    action_destr destructor;
    void * destructor_priv;
    u32 chain_index;
    struct net_device * dev;
    struct (anon) vlan;
    struct (anon) mangle;
    struct ip_tunnel_info * tunnel;
    u32 csum_flags;
    u32 mark;
    u16 ptype;
    struct (anon) queue;
    struct (anon) sample;
    struct (anon) police;
    struct (anon) ct;
    struct (anon) mpls_push;
    struct (anon) mpls_pop;
    struct (anon) mpls_mangle;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct flow_action_entry {
    enum flow_action_id id;
    action_destr destructor;
    void * destructor_priv;
    u32 chain_index;
    struct net_device * dev;
    struct (anon) vlan;
    struct (anon) mangle;
    struct ip_tunnel_info * tunnel;
    u32 csum_flags;
    u32 mark;
    u16 ptype;
    struct (anon) queue;
    struct (anon) sample;
    struct (anon) police;
    struct (anon) ct;
    struct (anon) mpls_push;
    struct (anon) mpls_pop;
    struct (anon) mpls_mangle;
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
struct flow_action_entry {
    enum flow_action_id id;
    u32 chain_index;
    struct net_device * dev;
    struct (anon) vlan;
    struct (anon) mangle;
    const struct ip_tunnel_info * tunnel;
    u32 csum_flags;
    u32 mark;
    struct (anon) queue;
    struct (anon) sample;
    struct (anon) police;
    struct (anon) ct;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>action_destr destructor</code>
</li>
<li>
<b>Field added. </b>
<code>void * destructor_priv</code>
</li>
<li>
<b>Field added. </b>
<code>u16 ptype</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) mpls_push</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) mpls_pop</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) mpls_mangle</code>
</li>
<li>
<b>Field type changed. </b>
<code>const struct ip_tunnel_info * tunnel</code> ➡️ <code>struct ip_tunnel_info * tunnel</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>enum flow_action_hw_stats hw_stats</code>
</li>
<li>
<b>Field added. </b>
<code>u32 priority</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) ct_metadata</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) gate</code>
</li>
<li>
<b>Field added. </b>
<code>struct flow_action_cookie * cookie</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct (anon) pppoe</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 hw_index</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) vlan_push_eth</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u16 rx_queue</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 miss_cookie</code>
</li>
<li>
<b>Field added. </b>
<code>struct flow_action_cookie * user_cookie</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct flow_action_cookie * cookie</code> ➡️ <code>long unsigned int cookie</code>
</li>
</ul>
</details>
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
