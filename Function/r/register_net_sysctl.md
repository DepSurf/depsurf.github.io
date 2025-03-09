# Function: <code>register_net_sysctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ctl_table_header * register_net_sysctl(struct net * net, const char * path, struct ctl_table * table)
```

```json
{
  "name": "register_net_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587324880,
      "name": "register_net_sysctl",
      "external": true,
      "loc": "net/sysctl_net.c:107",
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
        "net/ipv4/route.c:sysctl_route_net_init",
        "net/ipv4/route.c:sysctl_route_net_init",
        "net/ipv4/route.c:ip_static_sysctl_init",
        "net/ipv4/ip_fragment.c:ipv4_frags_init_net",
        "net/ipv4/ip_fragment.c:ipv4_frags_init_net",
        "net/ipv4/ip_fragment.c:ipfrag_init",
        "net/ipv4/devinet.c:__devinet_sysctl_register",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init",
        "net/unix/sysctl_net_unix.c:unix_sysctl_register",
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/reassembly.c:ipv6_frags_init_net",
        "net/ipv6/reassembly.c:ipv6_frags_init_net",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587324880,
      "name": "register_net_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct ctl_table_header * register_net_sysctl(struct net * net, const char * path, struct ctl_table * table)
```

```json
{
  "name": "register_net_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587795616,
      "name": "register_net_sysctl",
      "external": true,
      "loc": "net/sysctl_net.c:107",
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
        "net/ipv4/ip_fragment.c:ipv4_frags_init_net",
        "net/ipv4/ip_fragment.c:ipv4_frags_init_net",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:__devinet_sysctl_register",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init",
        "net/unix/sysctl_net_unix.c:unix_sysctl_register",
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/reassembly.c:ipv6_frags_init_net",
        "net/ipv6/reassembly.c:ipv6_frags_init_net",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587795616,
      "name": "register_net_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct ctl_table_header * register_net_sysctl(struct net * net, const char * path, struct ctl_table * table)
```

```json
{
  "name": "register_net_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588010784,
      "name": "register_net_sysctl",
      "external": true,
      "loc": "net/sysctl_net.c:118",
      "file": "net/sysctl_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sysctl_net_core.c:sysctl_core_init",
        "net/core/sysctl_net_core.c:sysctl_core_net_init",
        "net/core/sysctl_net_core.c:sysctl_core_net_init",
        "net/core/neighbour.c:neigh_sysctl_register",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/route.c:ip_static_sysctl_init",
        "net/ipv4/route.c:sysctl_route_net_init",
        "net/ipv4/route.c:sysctl_route_net_init",
        "net/ipv4/ip_fragment.c:ipfrag_init",
        "net/ipv4/ip_fragment.c:ipv4_frags_init_net",
        "net/ipv4/ip_fragment.c:ipv4_frags_init_net",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:__devinet_sysctl_register",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init",
        "net/unix/sysctl_net_unix.c:unix_sysctl_register",
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/reassembly.c:ipv6_frags_init_net",
        "net/ipv6/reassembly.c:ipv6_frags_init_net",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588010784,
      "name": "register_net_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct ctl_table_header * register_net_sysctl(struct net * net, const char * path, struct ctl_table * table)
```

```json
{
  "name": "register_net_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588168816,
      "name": "register_net_sysctl",
      "external": true,
      "loc": "net/sysctl_net.c:117",
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
        "net/ipv4/ip_fragment.c:ipv4_frags_init_net",
        "net/ipv4/ip_fragment.c:ipv4_frags_init_net",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:__devinet_sysctl_register",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init",
        "net/unix/sysctl_net_unix.c:unix_sysctl_register",
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/reassembly.c:ipv6_frags_init_net",
        "net/ipv6/reassembly.c:ipv6_frags_init_net",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588168816,
      "name": "register_net_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct ctl_table_header * register_net_sysctl(struct net * net, const char * path, struct ctl_table * table)
```

```json
{
  "name": "register_net_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588717232,
      "name": "register_net_sysctl",
      "external": true,
      "loc": "net/sysctl_net.c:117",
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
        "net/ipv4/ip_fragment.c:ipv4_frags_init_net",
        "net/ipv4/ip_fragment.c:ipv4_frags_init_net",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:__devinet_sysctl_register",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init",
        "net/unix/sysctl_net_unix.c:unix_sysctl_register",
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/reassembly.c:ipv6_frags_init_net",
        "net/ipv6/reassembly.c:ipv6_frags_init_net",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588717232,
      "name": "register_net_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct ctl_table_header * register_net_sysctl(struct net * net, const char * path, struct ctl_table * table)
```

```json
{
  "name": "register_net_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589084304,
      "name": "register_net_sysctl",
      "external": true,
      "loc": "net/sysctl_net.c:117",
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
        "net/ipv4/ip_fragment.c:ipv4_frags_init_net",
        "net/ipv4/ip_fragment.c:ipv4_frags_init_net",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:__devinet_sysctl_register",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init",
        "net/unix/sysctl_net_unix.c:unix_sysctl_register",
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/reassembly.c:ipv6_frags_init_net",
        "net/ipv6/reassembly.c:ipv6_frags_init_net",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589084304,
      "name": "register_net_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct ctl_table_header * register_net_sysctl(struct net * net, const char * path, struct ctl_table * table)
```

```json
{
  "name": "register_net_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589310528,
      "name": "register_net_sysctl",
      "external": true,
      "loc": "net/sysctl_net.c:117",
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
        "net/ipv4/ip_fragment.c:ipv4_frags_init_net",
        "net/ipv4/ip_fragment.c:ipv4_frags_init_net",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:__devinet_sysctl_register",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init",
        "net/unix/sysctl_net_unix.c:unix_sysctl_register",
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/reassembly.c:ipv6_frags_init_net",
        "net/ipv6/reassembly.c:ipv6_frags_init_net",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589310528,
      "name": "register_net_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct ctl_table_header * register_net_sysctl(struct net * net, const char * path, struct ctl_table * table)
```

```json
{
  "name": "register_net_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589766864,
      "name": "register_net_sysctl",
      "external": true,
      "loc": "net/sysctl_net.c:118",
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
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589766864,
      "name": "register_net_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct ctl_table_header * register_net_sysctl(struct net * net, const char * path, struct ctl_table * table)
```

```json
{
  "name": "register_net_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589990592,
      "name": "register_net_sysctl",
      "external": true,
      "loc": "net/sysctl_net.c:118",
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
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589990592,
      "name": "register_net_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct ctl_table_header * register_net_sysctl(struct net * net, const char * path, struct ctl_table * table)
```

```json
{
  "name": "register_net_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591021104,
      "name": "register_net_sysctl",
      "external": true,
      "loc": "net/sysctl_net.c:118",
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
      "addr": 18446744071591021104,
      "name": "register_net_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct ctl_table_header * register_net_sysctl(struct net * net, const char * path, struct ctl_table * table)
```

```json
{
  "name": "register_net_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591085888,
      "name": "register_net_sysctl",
      "external": true,
      "loc": "net/sysctl_net.c:118",
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
      "addr": 18446744071591085888,
      "name": "register_net_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct ctl_table_header * register_net_sysctl(struct net * net, const char * path, struct ctl_table * table)
```

```json
{
  "name": "register_net_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591016896,
      "name": "register_net_sysctl",
      "external": true,
      "loc": "net/sysctl_net.c:163",
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
      "addr": 18446744071591016896,
      "name": "register_net_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
struct ctl_table_header * register_net_sysctl(struct net * net, const char * path, struct ctl_table * table)
```

```json
{
  "name": "register_net_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591856384,
      "name": "register_net_sysctl",
      "external": true,
      "loc": "net/sysctl_net.c:163",
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
      "addr": 18446744071591856384,
      "name": "register_net_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
struct ctl_table_header * register_net_sysctl(struct net * net, const char * path, struct ctl_table * table)
```

```json
{
  "name": "register_net_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593573040,
      "name": "register_net_sysctl",
      "external": true,
      "loc": "net/sysctl_net.c:163",
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
      "addr": 18446744071593573040,
      "name": "register_net_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct ctl_table_header * register_net_sysctl(struct net * net, const char * path, struct ctl_table * table)
```

```json
{
  "name": "register_net_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595497312,
      "name": "register_net_sysctl",
      "external": true,
      "loc": "net/sysctl_net.c:163",
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
      "addr": 18446744071595497312,
      "name": "register_net_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct ctl_table_header * register_net_sysctl(struct net * net, const char * path, struct ctl_table * table)
```

```json
{
  "name": "register_net_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596005856,
      "name": "register_net_sysctl",
      "external": true,
      "loc": "net/sysctl_net.c:163",
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
      "addr": 18446744071596005856,
      "name": "register_net_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct ctl_table_header * register_net_sysctl(struct net * net, const char * path, struct ctl_table * table)
```

```json
{
  "name": "register_net_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503731656,
      "name": "register_net_sysctl",
      "external": true,
      "loc": "net/sysctl_net.c:118",
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
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503731656,
      "name": "register_net_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct ctl_table_header * register_net_sysctl(struct net * net, const char * path, struct ctl_table * table)
```

```json
{
  "name": "register_net_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236361540,
      "name": "register_net_sysctl",
      "external": true,
      "loc": "net/sysctl_net.c:118",
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
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236361540,
      "name": "register_net_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct ctl_table_header * register_net_sysctl(struct net * net, const char * path, struct ctl_table * table)
```

```json
{
  "name": "register_net_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297570064,
      "name": "register_net_sysctl",
      "external": true,
      "loc": "net/sysctl_net.c:118",
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
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297570064,
      "name": "register_net_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct ctl_table_header * register_net_sysctl(struct net * net, const char * path, struct ctl_table * table)
```

```json
{
  "name": "register_net_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279653354,
      "name": "register_net_sysctl",
      "external": true,
      "loc": "net/sysctl_net.c:118",
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
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279653354,
      "name": "register_net_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
struct ctl_table_header * register_net_sysctl(struct net * net, const char * path, struct ctl_table * table)
```

```json
{
  "name": "register_net_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589594192,
      "name": "register_net_sysctl",
      "external": true,
      "loc": "net/sysctl_net.c:118",
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
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589594192,
      "name": "register_net_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct ctl_table_header * register_net_sysctl(struct net * net, const char * path, struct ctl_table * table)
```

```json
{
  "name": "register_net_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589318720,
      "name": "register_net_sysctl",
      "external": true,
      "loc": "net/sysctl_net.c:118",
      "file": "net/sysctl_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/vxlan.c:vxlan_init_module",
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
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589318720,
      "name": "register_net_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct ctl_table_header * register_net_sysctl(struct net * net, const char * path, struct ctl_table * table)
```

```json
{
  "name": "register_net_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590036224,
      "name": "register_net_sysctl",
      "external": true,
      "loc": "net/sysctl_net.c:118",
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
        "net/netfilter/nf_conntrack_standalone.c:nf_conntrack_standalone_init",
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
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590036224,
      "name": "register_net_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct ctl_table_header * register_net_sysctl(struct net * net, const char * path, struct ctl_table * table)
```

```json
{
  "name": "register_net_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590086256,
      "name": "register_net_sysctl",
      "external": true,
      "loc": "net/sysctl_net.c:118",
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
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590086256,
      "name": "register_net_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
struct ctl_table_header * register_net_sysctl(struct net * net, const char * path, struct ctl_table * table)
```
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
