# Struct: <code>ip6_tnl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ip6_tnl {
    struct ip6_tnl * next;
    struct net_device * dev;
    struct net * net;
    struct __ip6_tnl_parm parms;
    struct flowi fl;
    struct ip6_tnl_dst * dst_cache;
    int err_count;
    long unsigned int err_time;
    __u32 i_seqno;
    __u32 o_seqno;
    int hlen;
    int mlink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct ip6_tnl {
    struct ip6_tnl * next;
    struct net_device * dev;
    struct net * net;
    struct __ip6_tnl_parm parms;
    struct flowi fl;
    struct dst_cache dst_cache;
    struct gro_cells gro_cells;
    int err_count;
    long unsigned int err_time;
    __u32 i_seqno;
    __u32 o_seqno;
    int hlen;
    int tun_hlen;
    int encap_hlen;
    struct ip_tunnel_encap encap;
    int mlink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct ip6_tnl {
    struct ip6_tnl * next;
    struct net_device * dev;
    struct net * net;
    struct __ip6_tnl_parm parms;
    struct flowi fl;
    struct dst_cache dst_cache;
    struct gro_cells gro_cells;
    int err_count;
    long unsigned int err_time;
    __u32 i_seqno;
    __u32 o_seqno;
    int hlen;
    int tun_hlen;
    int encap_hlen;
    struct ip_tunnel_encap encap;
    int mlink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct ip6_tnl {
    struct ip6_tnl * next;
    struct net_device * dev;
    struct net * net;
    struct __ip6_tnl_parm parms;
    struct flowi fl;
    struct dst_cache dst_cache;
    struct gro_cells gro_cells;
    int err_count;
    long unsigned int err_time;
    __u32 i_seqno;
    __u32 o_seqno;
    int hlen;
    int tun_hlen;
    int encap_hlen;
    struct ip_tunnel_encap encap;
    int mlink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ip6_tnl {
    struct ip6_tnl * next;
    struct net_device * dev;
    struct net * net;
    struct __ip6_tnl_parm parms;
    struct flowi fl;
    struct dst_cache dst_cache;
    struct gro_cells gro_cells;
    int err_count;
    long unsigned int err_time;
    __u32 i_seqno;
    __u32 o_seqno;
    int hlen;
    int tun_hlen;
    int encap_hlen;
    struct ip_tunnel_encap encap;
    int mlink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ip6_tnl {
    struct ip6_tnl * next;
    struct net_device * dev;
    struct net * net;
    struct __ip6_tnl_parm parms;
    struct flowi fl;
    struct dst_cache dst_cache;
    struct gro_cells gro_cells;
    int err_count;
    long unsigned int err_time;
    __u32 i_seqno;
    __u32 o_seqno;
    int hlen;
    int tun_hlen;
    int encap_hlen;
    struct ip_tunnel_encap encap;
    int mlink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ip6_tnl {
    struct ip6_tnl * next;
    struct net_device * dev;
    struct net * net;
    struct __ip6_tnl_parm parms;
    struct flowi fl;
    struct dst_cache dst_cache;
    struct gro_cells gro_cells;
    int err_count;
    long unsigned int err_time;
    __u32 i_seqno;
    __u32 o_seqno;
    int hlen;
    int tun_hlen;
    int encap_hlen;
    struct ip_tunnel_encap encap;
    int mlink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ip6_tnl {
    struct ip6_tnl * next;
    struct net_device * dev;
    struct net * net;
    struct __ip6_tnl_parm parms;
    struct flowi fl;
    struct dst_cache dst_cache;
    struct gro_cells gro_cells;
    int err_count;
    long unsigned int err_time;
    __u32 i_seqno;
    __u32 o_seqno;
    int hlen;
    int tun_hlen;
    int encap_hlen;
    struct ip_tunnel_encap encap;
    int mlink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ip6_tnl {
    struct ip6_tnl * next;
    struct net_device * dev;
    struct net * net;
    struct __ip6_tnl_parm parms;
    struct flowi fl;
    struct dst_cache dst_cache;
    struct gro_cells gro_cells;
    int err_count;
    long unsigned int err_time;
    __u32 i_seqno;
    __u32 o_seqno;
    int hlen;
    int tun_hlen;
    int encap_hlen;
    struct ip_tunnel_encap encap;
    int mlink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ip6_tnl {
    struct ip6_tnl * next;
    struct net_device * dev;
    struct net * net;
    struct __ip6_tnl_parm parms;
    struct flowi fl;
    struct dst_cache dst_cache;
    struct gro_cells gro_cells;
    int err_count;
    long unsigned int err_time;
    __u32 i_seqno;
    __u32 o_seqno;
    int hlen;
    int tun_hlen;
    int encap_hlen;
    struct ip_tunnel_encap encap;
    int mlink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ip6_tnl {
    struct ip6_tnl * next;
    struct net_device * dev;
    struct net * net;
    struct __ip6_tnl_parm parms;
    struct flowi fl;
    struct dst_cache dst_cache;
    struct gro_cells gro_cells;
    int err_count;
    long unsigned int err_time;
    __u32 i_seqno;
    __u32 o_seqno;
    int hlen;
    int tun_hlen;
    int encap_hlen;
    struct ip_tunnel_encap encap;
    int mlink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ip6_tnl {
    struct ip6_tnl * next;
    struct net_device * dev;
    struct net * net;
    struct __ip6_tnl_parm parms;
    struct flowi fl;
    struct dst_cache dst_cache;
    struct gro_cells gro_cells;
    int err_count;
    long unsigned int err_time;
    __u32 i_seqno;
    __u32 o_seqno;
    int hlen;
    int tun_hlen;
    int encap_hlen;
    struct ip_tunnel_encap encap;
    int mlink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ip6_tnl {
    struct ip6_tnl * next;
    struct net_device * dev;
    struct net * net;
    struct __ip6_tnl_parm parms;
    struct flowi fl;
    struct dst_cache dst_cache;
    struct gro_cells gro_cells;
    int err_count;
    long unsigned int err_time;
    __u32 i_seqno;
    __u32 o_seqno;
    int hlen;
    int tun_hlen;
    int encap_hlen;
    struct ip_tunnel_encap encap;
    int mlink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ip6_tnl {
    struct ip6_tnl * next;
    struct net_device * dev;
    netdevice_tracker dev_tracker;
    struct net * net;
    struct __ip6_tnl_parm parms;
    struct flowi fl;
    struct dst_cache dst_cache;
    struct gro_cells gro_cells;
    int err_count;
    long unsigned int err_time;
    __u32 i_seqno;
    atomic_t o_seqno;
    int hlen;
    int tun_hlen;
    int encap_hlen;
    struct ip_tunnel_encap encap;
    int mlink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ip6_tnl {
    struct ip6_tnl * next;
    struct net_device * dev;
    netdevice_tracker dev_tracker;
    struct net * net;
    struct __ip6_tnl_parm parms;
    struct flowi fl;
    struct dst_cache dst_cache;
    struct gro_cells gro_cells;
    int err_count;
    long unsigned int err_time;
    __u32 i_seqno;
    atomic_t o_seqno;
    int hlen;
    int tun_hlen;
    int encap_hlen;
    struct ip_tunnel_encap encap;
    int mlink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ip6_tnl {
    struct ip6_tnl * next;
    struct net_device * dev;
    netdevice_tracker dev_tracker;
    struct net * net;
    struct __ip6_tnl_parm parms;
    struct flowi fl;
    struct dst_cache dst_cache;
    struct gro_cells gro_cells;
    int err_count;
    long unsigned int err_time;
    __u32 i_seqno;
    atomic_t o_seqno;
    int hlen;
    int tun_hlen;
    int encap_hlen;
    struct ip_tunnel_encap encap;
    int mlink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ip6_tnl {
    struct ip6_tnl * next;
    struct net_device * dev;
    netdevice_tracker dev_tracker;
    struct net * net;
    struct __ip6_tnl_parm parms;
    struct flowi fl;
    struct dst_cache dst_cache;
    struct gro_cells gro_cells;
    int err_count;
    long unsigned int err_time;
    __u32 i_seqno;
    atomic_t o_seqno;
    int hlen;
    int tun_hlen;
    int encap_hlen;
    struct ip_tunnel_encap encap;
    int mlink;
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
struct ip6_tnl {
    struct ip6_tnl * next;
    struct net_device * dev;
    struct net * net;
    struct __ip6_tnl_parm parms;
    struct flowi fl;
    struct dst_cache dst_cache;
    struct gro_cells gro_cells;
    int err_count;
    long unsigned int err_time;
    __u32 i_seqno;
    __u32 o_seqno;
    int hlen;
    int tun_hlen;
    int encap_hlen;
    struct ip_tunnel_encap encap;
    int mlink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ip6_tnl {
    struct ip6_tnl * next;
    struct net_device * dev;
    struct net * net;
    struct __ip6_tnl_parm parms;
    struct flowi fl;
    struct dst_cache dst_cache;
    struct gro_cells gro_cells;
    int err_count;
    long unsigned int err_time;
    __u32 i_seqno;
    __u32 o_seqno;
    int hlen;
    int tun_hlen;
    int encap_hlen;
    struct ip_tunnel_encap encap;
    int mlink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ip6_tnl {
    struct ip6_tnl * next;
    struct net_device * dev;
    struct net * net;
    struct __ip6_tnl_parm parms;
    struct flowi fl;
    struct dst_cache dst_cache;
    struct gro_cells gro_cells;
    int err_count;
    long unsigned int err_time;
    __u32 i_seqno;
    __u32 o_seqno;
    int hlen;
    int tun_hlen;
    int encap_hlen;
    struct ip_tunnel_encap encap;
    int mlink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ip6_tnl {
    struct ip6_tnl * next;
    struct net_device * dev;
    struct net * net;
    struct __ip6_tnl_parm parms;
    struct flowi fl;
    struct dst_cache dst_cache;
    struct gro_cells gro_cells;
    int err_count;
    long unsigned int err_time;
    __u32 i_seqno;
    __u32 o_seqno;
    int hlen;
    int tun_hlen;
    int encap_hlen;
    struct ip_tunnel_encap encap;
    int mlink;
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
struct ip6_tnl {
    struct ip6_tnl * next;
    struct net_device * dev;
    struct net * net;
    struct __ip6_tnl_parm parms;
    struct flowi fl;
    struct dst_cache dst_cache;
    struct gro_cells gro_cells;
    int err_count;
    long unsigned int err_time;
    __u32 i_seqno;
    __u32 o_seqno;
    int hlen;
    int tun_hlen;
    int encap_hlen;
    struct ip_tunnel_encap encap;
    int mlink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ip6_tnl {
    struct ip6_tnl * next;
    struct net_device * dev;
    struct net * net;
    struct __ip6_tnl_parm parms;
    struct flowi fl;
    struct dst_cache dst_cache;
    struct gro_cells gro_cells;
    int err_count;
    long unsigned int err_time;
    __u32 i_seqno;
    __u32 o_seqno;
    int hlen;
    int tun_hlen;
    int encap_hlen;
    struct ip_tunnel_encap encap;
    int mlink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ip6_tnl {
    struct ip6_tnl * next;
    struct net_device * dev;
    struct net * net;
    struct __ip6_tnl_parm parms;
    struct flowi fl;
    struct dst_cache dst_cache;
    struct gro_cells gro_cells;
    int err_count;
    long unsigned int err_time;
    __u32 i_seqno;
    __u32 o_seqno;
    int hlen;
    int tun_hlen;
    int encap_hlen;
    struct ip_tunnel_encap encap;
    int mlink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ip6_tnl {
    struct ip6_tnl * next;
    struct net_device * dev;
    struct net * net;
    struct __ip6_tnl_parm parms;
    struct flowi fl;
    struct dst_cache dst_cache;
    struct gro_cells gro_cells;
    int err_count;
    long unsigned int err_time;
    __u32 i_seqno;
    __u32 o_seqno;
    int hlen;
    int tun_hlen;
    int encap_hlen;
    struct ip_tunnel_encap encap;
    int mlink;
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
<code>struct gro_cells gro_cells</code>
</li>
<li>
<b>Field added. </b>
<code>int tun_hlen</code>
</li>
<li>
<b>Field added. </b>
<code>int encap_hlen</code>
</li>
<li>
<b>Field added. </b>
<code>struct ip_tunnel_encap encap</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct ip6_tnl_dst * dst_cache</code> ➡️ <code>struct dst_cache dst_cache</code>
</li>
</ul>
</details>
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
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>netdevice_tracker dev_tracker</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 o_seqno</code> ➡️ <code>atomic_t o_seqno</code>
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
