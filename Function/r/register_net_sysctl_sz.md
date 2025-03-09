# Function: <code>register_net_sysctl_sz</code>

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
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ctl_table_header * register_net_sysctl_sz(struct net * net, const char * path, struct ctl_table * table, size_t table_size)
```

```json
{
  "name": "register_net_sysctl_sz",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596869184,
      "name": "register_net_sysctl_sz",
      "external": true,
      "loc": "net/sysctl_net.c:164",
      "file": "net/sysctl_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sysctl_net_core.c:sysctl_core_init",
        "net/core/sysctl_net_core.c:sysctl_core_net_init",
        "net/core/sysctl_net_core.c:sysctl_core_net_init",
        "net/core/neighbour.c:neigh_sysctl_register",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/route.c:ip_static_sysctl_init",
        "net/ipv4/route.c:sysctl_route_net_init",
        "net/ipv4/route.c:sysctl_route_net_init",
        "net/ipv4/ip_fragment.c:ipfrag_init",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:__devinet_sysctl_register",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init",
        "net/unix/sysctl_net_unix.c:unix_sysctl_register",
        "net/unix/sysctl_net_unix.c:unix_sysctl_register",
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "net/mptcp/ctrl.c:mptcp_net_init",
        "net/mptcp/ctrl.c:mptcp_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596869184,
      "name": "register_net_sysctl_sz",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
struct ctl_table_header * register_net_sysctl_sz(struct net * net, const char * path, struct ctl_table * table, size_t table_size)
```
</details>
</li>
</ul>
