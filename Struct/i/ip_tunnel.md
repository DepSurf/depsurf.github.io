# Struct: <code>ip_tunnel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ip_tunnel {
    struct ip_tunnel * next;
    struct hlist_node hash_node;
    struct net_device * dev;
    struct net * net;
    int err_count;
    long unsigned int err_time;
    u32 i_seqno;
    u32 o_seqno;
    int tun_hlen;
    int mlink;
    struct ip_tunnel_dst * dst_cache;
    struct ip_tunnel_parm parms;
    int encap_hlen;
    struct ip_tunnel_encap encap;
    int hlen;
    struct ip_tunnel_6rd_parm ip6rd;
    struct ip_tunnel_prl_entry * prl;
    unsigned int prl_count;
    struct ip_tunnel_fan fan;
    int ip_tnl_net_id;
    struct gro_cells gro_cells;
    bool collect_md;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct ip_tunnel {
    struct ip_tunnel * next;
    struct hlist_node hash_node;
    struct net_device * dev;
    struct net * net;
    long unsigned int err_time;
    int err_count;
    u32 i_seqno;
    u32 o_seqno;
    int tun_hlen;
    struct dst_cache dst_cache;
    struct ip_tunnel_parm parms;
    int mlink;
    int encap_hlen;
    int hlen;
    struct ip_tunnel_encap encap;
    struct ip_tunnel_6rd_parm ip6rd;
    struct ip_tunnel_prl_entry * prl;
    unsigned int prl_count;
    struct ip_tunnel_fan fan;
    int ip_tnl_net_id;
    struct gro_cells gro_cells;
    bool collect_md;
    bool ignore_df;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct ip_tunnel {
    struct ip_tunnel * next;
    struct hlist_node hash_node;
    struct net_device * dev;
    struct net * net;
    long unsigned int err_time;
    int err_count;
    u32 i_seqno;
    u32 o_seqno;
    int tun_hlen;
    struct dst_cache dst_cache;
    struct ip_tunnel_parm parms;
    int mlink;
    int encap_hlen;
    int hlen;
    struct ip_tunnel_encap encap;
    struct ip_tunnel_6rd_parm ip6rd;
    struct ip_tunnel_prl_entry * prl;
    unsigned int prl_count;
    struct ip_tunnel_fan fan;
    unsigned int ip_tnl_net_id;
    struct gro_cells gro_cells;
    bool collect_md;
    bool ignore_df;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct ip_tunnel {
    struct ip_tunnel * next;
    struct hlist_node hash_node;
    struct net_device * dev;
    struct net * net;
    long unsigned int err_time;
    int err_count;
    u32 i_seqno;
    u32 o_seqno;
    int tun_hlen;
    struct dst_cache dst_cache;
    struct ip_tunnel_parm parms;
    int mlink;
    int encap_hlen;
    int hlen;
    struct ip_tunnel_encap encap;
    struct ip_tunnel_6rd_parm ip6rd;
    struct ip_tunnel_prl_entry * prl;
    unsigned int prl_count;
    struct ip_tunnel_fan fan;
    unsigned int ip_tnl_net_id;
    struct gro_cells gro_cells;
    __u32 fwmark;
    bool collect_md;
    bool ignore_df;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ip_tunnel {
    struct ip_tunnel * next;
    struct hlist_node hash_node;
    struct net_device * dev;
    struct net * net;
    long unsigned int err_time;
    int err_count;
    u32 i_seqno;
    u32 o_seqno;
    int tun_hlen;
    u32 index;
    struct dst_cache dst_cache;
    struct ip_tunnel_parm parms;
    int mlink;
    int encap_hlen;
    int hlen;
    struct ip_tunnel_encap encap;
    struct ip_tunnel_6rd_parm ip6rd;
    struct ip_tunnel_prl_entry * prl;
    unsigned int prl_count;
    struct ip_tunnel_fan fan;
    unsigned int ip_tnl_net_id;
    struct gro_cells gro_cells;
    __u32 fwmark;
    bool collect_md;
    bool ignore_df;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ip_tunnel {
    struct ip_tunnel * next;
    struct hlist_node hash_node;
    struct net_device * dev;
    struct net * net;
    long unsigned int err_time;
    int err_count;
    u32 i_seqno;
    u32 o_seqno;
    int tun_hlen;
    u32 index;
    u8 erspan_ver;
    u8 dir;
    u16 hwid;
    struct dst_cache dst_cache;
    struct ip_tunnel_parm parms;
    int mlink;
    int encap_hlen;
    int hlen;
    struct ip_tunnel_encap encap;
    struct ip_tunnel_6rd_parm ip6rd;
    struct ip_tunnel_prl_entry * prl;
    unsigned int prl_count;
    struct ip_tunnel_fan fan;
    unsigned int ip_tnl_net_id;
    struct gro_cells gro_cells;
    __u32 fwmark;
    bool collect_md;
    bool ignore_df;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ip_tunnel {
    struct ip_tunnel * next;
    struct hlist_node hash_node;
    struct net_device * dev;
    struct net * net;
    long unsigned int err_time;
    int err_count;
    u32 i_seqno;
    u32 o_seqno;
    int tun_hlen;
    u32 index;
    u8 erspan_ver;
    u8 dir;
    u16 hwid;
    struct dst_cache dst_cache;
    struct ip_tunnel_parm parms;
    int mlink;
    int encap_hlen;
    int hlen;
    struct ip_tunnel_encap encap;
    struct ip_tunnel_6rd_parm ip6rd;
    struct ip_tunnel_prl_entry * prl;
    unsigned int prl_count;
    struct ip_tunnel_fan fan;
    unsigned int ip_tnl_net_id;
    struct gro_cells gro_cells;
    __u32 fwmark;
    bool collect_md;
    bool ignore_df;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ip_tunnel {
    struct ip_tunnel * next;
    struct hlist_node hash_node;
    struct net_device * dev;
    struct net * net;
    long unsigned int err_time;
    int err_count;
    u32 i_seqno;
    u32 o_seqno;
    int tun_hlen;
    u32 index;
    u8 erspan_ver;
    u8 dir;
    u16 hwid;
    struct dst_cache dst_cache;
    struct ip_tunnel_parm parms;
    int mlink;
    int encap_hlen;
    int hlen;
    struct ip_tunnel_encap encap;
    struct ip_tunnel_6rd_parm ip6rd;
    struct ip_tunnel_prl_entry * prl;
    unsigned int prl_count;
    struct ip_tunnel_fan fan;
    unsigned int ip_tnl_net_id;
    struct gro_cells gro_cells;
    __u32 fwmark;
    bool collect_md;
    bool ignore_df;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ip_tunnel {
    struct ip_tunnel * next;
    struct hlist_node hash_node;
    struct net_device * dev;
    struct net * net;
    long unsigned int err_time;
    int err_count;
    u32 i_seqno;
    u32 o_seqno;
    int tun_hlen;
    u32 index;
    u8 erspan_ver;
    u8 dir;
    u16 hwid;
    struct dst_cache dst_cache;
    struct ip_tunnel_parm parms;
    int mlink;
    int encap_hlen;
    int hlen;
    struct ip_tunnel_encap encap;
    struct ip_tunnel_6rd_parm ip6rd;
    struct ip_tunnel_prl_entry * prl;
    unsigned int prl_count;
    struct ip_tunnel_fan fan;
    unsigned int ip_tnl_net_id;
    struct gro_cells gro_cells;
    __u32 fwmark;
    bool collect_md;
    bool ignore_df;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ip_tunnel {
    struct ip_tunnel * next;
    struct hlist_node hash_node;
    struct net_device * dev;
    struct net * net;
    long unsigned int err_time;
    int err_count;
    u32 i_seqno;
    u32 o_seqno;
    int tun_hlen;
    u32 index;
    u8 erspan_ver;
    u8 dir;
    u16 hwid;
    struct dst_cache dst_cache;
    struct ip_tunnel_parm parms;
    int mlink;
    int encap_hlen;
    int hlen;
    struct ip_tunnel_encap encap;
    struct ip_tunnel_6rd_parm ip6rd;
    struct ip_tunnel_prl_entry * prl;
    unsigned int prl_count;
    struct ip_tunnel_fan fan;
    unsigned int ip_tnl_net_id;
    struct gro_cells gro_cells;
    __u32 fwmark;
    bool collect_md;
    bool ignore_df;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ip_tunnel {
    struct ip_tunnel * next;
    struct hlist_node hash_node;
    struct net_device * dev;
    struct net * net;
    long unsigned int err_time;
    int err_count;
    u32 i_seqno;
    u32 o_seqno;
    int tun_hlen;
    u32 index;
    u8 erspan_ver;
    u8 dir;
    u16 hwid;
    struct dst_cache dst_cache;
    struct ip_tunnel_parm parms;
    int mlink;
    int encap_hlen;
    int hlen;
    struct ip_tunnel_encap encap;
    struct ip_tunnel_6rd_parm ip6rd;
    struct ip_tunnel_prl_entry * prl;
    unsigned int prl_count;
    struct ip_tunnel_fan fan;
    unsigned int ip_tnl_net_id;
    struct gro_cells gro_cells;
    __u32 fwmark;
    bool collect_md;
    bool ignore_df;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ip_tunnel {
    struct ip_tunnel * next;
    struct hlist_node hash_node;
    struct net_device * dev;
    struct net * net;
    long unsigned int err_time;
    int err_count;
    u32 i_seqno;
    u32 o_seqno;
    int tun_hlen;
    u32 index;
    u8 erspan_ver;
    u8 dir;
    u16 hwid;
    struct dst_cache dst_cache;
    struct ip_tunnel_parm parms;
    int mlink;
    int encap_hlen;
    int hlen;
    struct ip_tunnel_encap encap;
    struct ip_tunnel_6rd_parm ip6rd;
    struct ip_tunnel_prl_entry * prl;
    unsigned int prl_count;
    struct ip_tunnel_fan fan;
    unsigned int ip_tnl_net_id;
    struct gro_cells gro_cells;
    __u32 fwmark;
    bool collect_md;
    bool ignore_df;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ip_tunnel {
    struct ip_tunnel * next;
    struct hlist_node hash_node;
    struct net_device * dev;
    struct net * net;
    long unsigned int err_time;
    int err_count;
    u32 i_seqno;
    u32 o_seqno;
    int tun_hlen;
    u32 index;
    u8 erspan_ver;
    u8 dir;
    u16 hwid;
    struct dst_cache dst_cache;
    struct ip_tunnel_parm parms;
    int mlink;
    int encap_hlen;
    int hlen;
    struct ip_tunnel_encap encap;
    struct ip_tunnel_6rd_parm ip6rd;
    struct ip_tunnel_prl_entry * prl;
    unsigned int prl_count;
    struct ip_tunnel_fan fan;
    unsigned int ip_tnl_net_id;
    struct gro_cells gro_cells;
    __u32 fwmark;
    bool collect_md;
    bool ignore_df;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ip_tunnel {
    struct ip_tunnel * next;
    struct hlist_node hash_node;
    struct net_device * dev;
    netdevice_tracker dev_tracker;
    struct net * net;
    long unsigned int err_time;
    int err_count;
    u32 i_seqno;
    atomic_t o_seqno;
    int tun_hlen;
    u32 index;
    u8 erspan_ver;
    u8 dir;
    u16 hwid;
    struct dst_cache dst_cache;
    struct ip_tunnel_parm parms;
    int mlink;
    int encap_hlen;
    int hlen;
    struct ip_tunnel_encap encap;
    struct ip_tunnel_6rd_parm ip6rd;
    struct ip_tunnel_prl_entry * prl;
    unsigned int prl_count;
    struct ip_tunnel_fan fan;
    unsigned int ip_tnl_net_id;
    struct gro_cells gro_cells;
    __u32 fwmark;
    bool collect_md;
    bool ignore_df;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ip_tunnel {
    struct ip_tunnel * next;
    struct hlist_node hash_node;
    struct net_device * dev;
    netdevice_tracker dev_tracker;
    struct net * net;
    long unsigned int err_time;
    int err_count;
    u32 i_seqno;
    atomic_t o_seqno;
    int tun_hlen;
    u32 index;
    u8 erspan_ver;
    u8 dir;
    u16 hwid;
    struct dst_cache dst_cache;
    struct ip_tunnel_parm parms;
    int mlink;
    int encap_hlen;
    int hlen;
    struct ip_tunnel_encap encap;
    struct ip_tunnel_6rd_parm ip6rd;
    struct ip_tunnel_prl_entry * prl;
    unsigned int prl_count;
    struct ip_tunnel_fan fan;
    unsigned int ip_tnl_net_id;
    struct gro_cells gro_cells;
    __u32 fwmark;
    bool collect_md;
    bool ignore_df;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ip_tunnel {
    struct ip_tunnel * next;
    struct hlist_node hash_node;
    struct net_device * dev;
    netdevice_tracker dev_tracker;
    struct net * net;
    long unsigned int err_time;
    int err_count;
    u32 i_seqno;
    atomic_t o_seqno;
    int tun_hlen;
    u32 index;
    u8 erspan_ver;
    u8 dir;
    u16 hwid;
    struct dst_cache dst_cache;
    struct ip_tunnel_parm parms;
    int mlink;
    int encap_hlen;
    int hlen;
    struct ip_tunnel_encap encap;
    struct ip_tunnel_6rd_parm ip6rd;
    struct ip_tunnel_prl_entry * prl;
    unsigned int prl_count;
    struct ip_tunnel_fan fan;
    unsigned int ip_tnl_net_id;
    struct gro_cells gro_cells;
    __u32 fwmark;
    bool collect_md;
    bool ignore_df;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ip_tunnel {
    struct ip_tunnel * next;
    struct hlist_node hash_node;
    struct net_device * dev;
    netdevice_tracker dev_tracker;
    struct net * net;
    long unsigned int err_time;
    int err_count;
    u32 i_seqno;
    atomic_t o_seqno;
    int tun_hlen;
    u32 index;
    u8 erspan_ver;
    u8 dir;
    u16 hwid;
    struct dst_cache dst_cache;
    struct ip_tunnel_parm parms;
    int mlink;
    int encap_hlen;
    int hlen;
    struct ip_tunnel_encap encap;
    struct ip_tunnel_6rd_parm ip6rd;
    struct ip_tunnel_prl_entry * prl;
    unsigned int prl_count;
    unsigned int ip_tnl_net_id;
    struct gro_cells gro_cells;
    __u32 fwmark;
    bool collect_md;
    bool ignore_df;
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
struct ip_tunnel {
    struct ip_tunnel * next;
    struct hlist_node hash_node;
    struct net_device * dev;
    struct net * net;
    long unsigned int err_time;
    int err_count;
    u32 i_seqno;
    u32 o_seqno;
    int tun_hlen;
    u32 index;
    u8 erspan_ver;
    u8 dir;
    u16 hwid;
    struct dst_cache dst_cache;
    struct ip_tunnel_parm parms;
    int mlink;
    int encap_hlen;
    int hlen;
    struct ip_tunnel_encap encap;
    struct ip_tunnel_6rd_parm ip6rd;
    struct ip_tunnel_prl_entry * prl;
    unsigned int prl_count;
    struct ip_tunnel_fan fan;
    unsigned int ip_tnl_net_id;
    struct gro_cells gro_cells;
    __u32 fwmark;
    bool collect_md;
    bool ignore_df;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ip_tunnel {
    struct ip_tunnel * next;
    struct hlist_node hash_node;
    struct net_device * dev;
    struct net * net;
    long unsigned int err_time;
    int err_count;
    u32 i_seqno;
    u32 o_seqno;
    int tun_hlen;
    u32 index;
    u8 erspan_ver;
    u8 dir;
    u16 hwid;
    struct dst_cache dst_cache;
    struct ip_tunnel_parm parms;
    int mlink;
    int encap_hlen;
    int hlen;
    struct ip_tunnel_encap encap;
    struct ip_tunnel_6rd_parm ip6rd;
    struct ip_tunnel_prl_entry * prl;
    unsigned int prl_count;
    struct ip_tunnel_fan fan;
    unsigned int ip_tnl_net_id;
    struct gro_cells gro_cells;
    __u32 fwmark;
    bool collect_md;
    bool ignore_df;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ip_tunnel {
    struct ip_tunnel * next;
    struct hlist_node hash_node;
    struct net_device * dev;
    struct net * net;
    long unsigned int err_time;
    int err_count;
    u32 i_seqno;
    u32 o_seqno;
    int tun_hlen;
    u32 index;
    u8 erspan_ver;
    u8 dir;
    u16 hwid;
    struct dst_cache dst_cache;
    struct ip_tunnel_parm parms;
    int mlink;
    int encap_hlen;
    int hlen;
    struct ip_tunnel_encap encap;
    struct ip_tunnel_6rd_parm ip6rd;
    struct ip_tunnel_prl_entry * prl;
    unsigned int prl_count;
    struct ip_tunnel_fan fan;
    unsigned int ip_tnl_net_id;
    struct gro_cells gro_cells;
    __u32 fwmark;
    bool collect_md;
    bool ignore_df;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ip_tunnel {
    struct ip_tunnel * next;
    struct hlist_node hash_node;
    struct net_device * dev;
    struct net * net;
    long unsigned int err_time;
    int err_count;
    u32 i_seqno;
    u32 o_seqno;
    int tun_hlen;
    u32 index;
    u8 erspan_ver;
    u8 dir;
    u16 hwid;
    struct dst_cache dst_cache;
    struct ip_tunnel_parm parms;
    int mlink;
    int encap_hlen;
    int hlen;
    struct ip_tunnel_encap encap;
    struct ip_tunnel_6rd_parm ip6rd;
    struct ip_tunnel_prl_entry * prl;
    unsigned int prl_count;
    struct ip_tunnel_fan fan;
    unsigned int ip_tnl_net_id;
    struct gro_cells gro_cells;
    __u32 fwmark;
    bool collect_md;
    bool ignore_df;
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
struct ip_tunnel {
    struct ip_tunnel * next;
    struct hlist_node hash_node;
    struct net_device * dev;
    struct net * net;
    long unsigned int err_time;
    int err_count;
    u32 i_seqno;
    u32 o_seqno;
    int tun_hlen;
    u32 index;
    u8 erspan_ver;
    u8 dir;
    u16 hwid;
    struct dst_cache dst_cache;
    struct ip_tunnel_parm parms;
    int mlink;
    int encap_hlen;
    int hlen;
    struct ip_tunnel_encap encap;
    struct ip_tunnel_6rd_parm ip6rd;
    struct ip_tunnel_prl_entry * prl;
    unsigned int prl_count;
    struct ip_tunnel_fan fan;
    unsigned int ip_tnl_net_id;
    struct gro_cells gro_cells;
    __u32 fwmark;
    bool collect_md;
    bool ignore_df;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ip_tunnel {
    struct ip_tunnel * next;
    struct hlist_node hash_node;
    struct net_device * dev;
    struct net * net;
    long unsigned int err_time;
    int err_count;
    u32 i_seqno;
    u32 o_seqno;
    int tun_hlen;
    u32 index;
    u8 erspan_ver;
    u8 dir;
    u16 hwid;
    struct dst_cache dst_cache;
    struct ip_tunnel_parm parms;
    int mlink;
    int encap_hlen;
    int hlen;
    struct ip_tunnel_encap encap;
    struct ip_tunnel_6rd_parm ip6rd;
    struct ip_tunnel_prl_entry * prl;
    unsigned int prl_count;
    struct ip_tunnel_fan fan;
    unsigned int ip_tnl_net_id;
    struct gro_cells gro_cells;
    __u32 fwmark;
    bool collect_md;
    bool ignore_df;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ip_tunnel {
    struct ip_tunnel * next;
    struct hlist_node hash_node;
    struct net_device * dev;
    struct net * net;
    long unsigned int err_time;
    int err_count;
    u32 i_seqno;
    u32 o_seqno;
    int tun_hlen;
    u32 index;
    u8 erspan_ver;
    u8 dir;
    u16 hwid;
    struct dst_cache dst_cache;
    struct ip_tunnel_parm parms;
    int mlink;
    int encap_hlen;
    int hlen;
    struct ip_tunnel_encap encap;
    struct ip_tunnel_6rd_parm ip6rd;
    struct ip_tunnel_prl_entry * prl;
    unsigned int prl_count;
    struct ip_tunnel_fan fan;
    unsigned int ip_tnl_net_id;
    struct gro_cells gro_cells;
    __u32 fwmark;
    bool collect_md;
    bool ignore_df;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ip_tunnel {
    struct ip_tunnel * next;
    struct hlist_node hash_node;
    struct net_device * dev;
    struct net * net;
    long unsigned int err_time;
    int err_count;
    u32 i_seqno;
    u32 o_seqno;
    int tun_hlen;
    u32 index;
    u8 erspan_ver;
    u8 dir;
    u16 hwid;
    struct dst_cache dst_cache;
    struct ip_tunnel_parm parms;
    int mlink;
    int encap_hlen;
    int hlen;
    struct ip_tunnel_encap encap;
    struct ip_tunnel_6rd_parm ip6rd;
    struct ip_tunnel_prl_entry * prl;
    unsigned int prl_count;
    struct ip_tunnel_fan fan;
    unsigned int ip_tnl_net_id;
    struct gro_cells gro_cells;
    __u32 fwmark;
    bool collect_md;
    bool ignore_df;
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool ignore_df</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct ip_tunnel_dst * dst_cache</code> ➡️ <code>struct dst_cache dst_cache</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int ip_tnl_net_id</code> ➡️ <code>unsigned int ip_tnl_net_id</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u32 fwmark</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 index</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u8 erspan_ver</code>
</li>
<li>
<b>Field added. </b>
<code>u8 dir</code>
</li>
<li>
<b>Field added. </b>
<code>u16 hwid</code>
</li>
</ul>
</details>
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
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>netdevice_tracker dev_tracker</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32 o_seqno</code> ➡️ <code>atomic_t o_seqno</code>
</li>
</ul>
</details>
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
<b>Field removed. </b>
<code>struct ip_tunnel_fan fan</code>
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
