# Function: <code>unregister_net_sysctl_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void unregister_net_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_net_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587324784,
      "name": "unregister_net_sysctl_table",
      "external": true,
      "loc": "net/sysctl_net.c:114",
      "file": "net/sysctl_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_sysctl_unregister",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/ipv4/ip_fragment.c:ipv4_frags_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini",
        "net/unix/sysctl_net_unix.c:unix_sysctl_unregister",
        "net/ipv6/reassembly.c:ipv6_frags_exit_net",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587324784,
      "name": "unregister_net_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void unregister_net_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_net_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587795520,
      "name": "unregister_net_sysctl_table",
      "external": true,
      "loc": "net/sysctl_net.c:114",
      "file": "net/sysctl_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_sysctl_unregister",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/ipv4/ip_fragment.c:ipv4_frags_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini",
        "net/unix/sysctl_net_unix.c:unix_sysctl_unregister",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/reassembly.c:ipv6_frags_exit_net",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587795520,
      "name": "unregister_net_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void unregister_net_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_net_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588010608,
      "name": "unregister_net_sysctl_table",
      "external": true,
      "loc": "net/sysctl_net.c:125",
      "file": "net/sysctl_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_sysctl_unregister",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/ipv4/ip_fragment.c:ipv4_frags_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini",
        "net/unix/sysctl_net_unix.c:unix_sysctl_unregister",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/reassembly.c:ipv6_frags_exit_net",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588010608,
      "name": "unregister_net_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void unregister_net_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_net_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588168640,
      "name": "unregister_net_sysctl_table",
      "external": true,
      "loc": "net/sysctl_net.c:124",
      "file": "net/sysctl_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_sysctl_unregister",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/ip_fragment.c:ipv4_frags_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini",
        "net/unix/sysctl_net_unix.c:unix_sysctl_unregister",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/reassembly.c:ipv6_frags_exit_net",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588168640,
      "name": "unregister_net_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void unregister_net_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_net_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588717056,
      "name": "unregister_net_sysctl_table",
      "external": true,
      "loc": "net/sysctl_net.c:124",
      "file": "net/sysctl_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_sysctl_unregister",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/ip_fragment.c:ipv4_frags_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini",
        "net/unix/sysctl_net_unix.c:unix_sysctl_unregister",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/reassembly.c:ipv6_frags_exit_net",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588717056,
      "name": "unregister_net_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void unregister_net_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_net_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589084128,
      "name": "unregister_net_sysctl_table",
      "external": true,
      "loc": "net/sysctl_net.c:124",
      "file": "net/sysctl_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_sysctl_unregister",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/ip_fragment.c:ipv4_frags_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini",
        "net/unix/sysctl_net_unix.c:unix_sysctl_unregister",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/reassembly.c:ipv6_frags_exit_net",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589084128,
      "name": "unregister_net_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void unregister_net_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_net_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589310352,
      "name": "unregister_net_sysctl_table",
      "external": true,
      "loc": "net/sysctl_net.c:124",
      "file": "net/sysctl_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_sysctl_unregister",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/ip_fragment.c:ipv4_frags_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini",
        "net/unix/sysctl_net_unix.c:unix_sysctl_unregister",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/reassembly.c:ipv6_frags_exit_net",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589310352,
      "name": "unregister_net_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void unregister_net_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_net_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589766688,
      "name": "unregister_net_sysctl_table",
      "external": true,
      "loc": "net/sysctl_net.c:125",
      "file": "net/sysctl_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_sysctl_unregister",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/ip_fragment.c:ipv4_frags_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini",
        "net/unix/sysctl_net_unix.c:unix_sysctl_unregister",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/reassembly.c:ipv6_frags_exit_net",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589766688,
      "name": "unregister_net_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void unregister_net_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_net_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589990416,
      "name": "unregister_net_sysctl_table",
      "external": true,
      "loc": "net/sysctl_net.c:125",
      "file": "net/sysctl_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_sysctl_unregister",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/ip_fragment.c:ipv4_frags_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini",
        "net/unix/sysctl_net_unix.c:unix_sysctl_unregister",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/reassembly.c:ipv6_frags_exit_net",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589990416,
      "name": "unregister_net_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void unregister_net_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_net_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591020928,
      "name": "unregister_net_sysctl_table",
      "external": true,
      "loc": "net/sysctl_net.c:125",
      "file": "net/sysctl_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_sysctl_unregister",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/ip_fragment.c:ipv4_frags_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_destroy",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini",
        "net/unix/sysctl_net_unix.c:unix_sysctl_unregister",
        "net/ipv6/addrconf.c:addrconf_exit_net",
        "net/ipv6/addrconf.c:addrconf_exit_net",
        "net/ipv6/addrconf.c:addrconf_init_net",
        "net/ipv6/addrconf.c:addrconf_sysctl_unregister",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/reassembly.c:ipv6_frags_exit_net",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit",
        "net/mptcp/ctrl.c:mptcp_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591020928,
      "name": "unregister_net_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void unregister_net_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_net_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591085712,
      "name": "unregister_net_sysctl_table",
      "external": true,
      "loc": "net/sysctl_net.c:125",
      "file": "net/sysctl_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_sysctl_unregister",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/ip_fragment.c:ipv4_frags_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_destroy",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini",
        "net/unix/sysctl_net_unix.c:unix_sysctl_unregister",
        "net/ipv6/addrconf.c:addrconf_exit_net",
        "net/ipv6/addrconf.c:addrconf_exit_net",
        "net/ipv6/addrconf.c:addrconf_init_net",
        "net/ipv6/addrconf.c:addrconf_sysctl_unregister",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/reassembly.c:ipv6_frags_exit_net",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit",
        "net/mptcp/ctrl.c:mptcp_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591085712,
      "name": "unregister_net_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void unregister_net_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_net_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591016480,
      "name": "unregister_net_sysctl_table",
      "external": true,
      "loc": "net/sysctl_net.c:173",
      "file": "net/sysctl_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_sysctl_unregister",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/ip_fragment.c:ipv4_frags_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini",
        "net/unix/sysctl_net_unix.c:unix_sysctl_unregister",
        "net/ipv6/addrconf.c:addrconf_exit_net",
        "net/ipv6/addrconf.c:addrconf_exit_net",
        "net/ipv6/addrconf.c:addrconf_init_net",
        "net/ipv6/addrconf.c:addrconf_sysctl_unregister",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/reassembly.c:ipv6_frags_exit_net",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit",
        "net/mptcp/ctrl.c:mptcp_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591016480,
      "name": "unregister_net_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void unregister_net_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_net_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591855984,
      "name": "unregister_net_sysctl_table",
      "external": true,
      "loc": "net/sysctl_net.c:173",
      "file": "net/sysctl_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sysctl_net_core.c:sysctl_core_net_exit",
        "net/core/neighbour.c:neigh_sysctl_unregister",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/route.c:sysctl_route_net_exit",
        "net/ipv4/ip_fragment.c:ipv4_frags_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini",
        "net/unix/sysctl_net_unix.c:unix_sysctl_unregister",
        "net/ipv6/addrconf.c:addrconf_exit_net",
        "net/ipv6/addrconf.c:addrconf_exit_net",
        "net/ipv6/addrconf.c:addrconf_init_net",
        "net/ipv6/addrconf.c:addrconf_sysctl_unregister",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/reassembly.c:ipv6_frags_exit_net",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit",
        "net/mptcp/ctrl.c:mptcp_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591855984,
      "name": "unregister_net_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void unregister_net_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_net_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593572528,
      "name": "unregister_net_sysctl_table",
      "external": true,
      "loc": "net/sysctl_net.c:173",
      "file": "net/sysctl_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sysctl_net_core.c:sysctl_core_net_exit",
        "net/core/neighbour.c:neigh_sysctl_unregister",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/route.c:sysctl_route_net_exit",
        "net/ipv4/ip_fragment.c:ipv4_frags_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini",
        "net/unix/sysctl_net_unix.c:unix_sysctl_unregister",
        "net/ipv6/addrconf.c:addrconf_exit_net",
        "net/ipv6/addrconf.c:addrconf_exit_net",
        "net/ipv6/addrconf.c:addrconf_init_net",
        "net/ipv6/addrconf.c:addrconf_sysctl_unregister",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/reassembly.c:ipv6_frags_exit_net",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit",
        "net/mptcp/ctrl.c:mptcp_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593572528,
      "name": "unregister_net_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void unregister_net_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_net_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595496720,
      "name": "unregister_net_sysctl_table",
      "external": true,
      "loc": "net/sysctl_net.c:173",
      "file": "net/sysctl_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sysctl_net_core.c:sysctl_core_net_exit",
        "net/core/neighbour.c:neigh_sysctl_unregister",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/route.c:sysctl_route_net_exit",
        "net/ipv4/ip_fragment.c:ipv4_frags_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_destroy",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini",
        "net/unix/sysctl_net_unix.c:unix_sysctl_unregister",
        "net/ipv6/addrconf.c:addrconf_exit_net",
        "net/ipv6/addrconf.c:addrconf_exit_net",
        "net/ipv6/addrconf.c:addrconf_init_net",
        "net/ipv6/addrconf.c:addrconf_sysctl_unregister",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/reassembly.c:ipv6_frags_exit_net",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit",
        "net/mptcp/ctrl.c:mptcp_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595496720,
      "name": "unregister_net_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void unregister_net_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_net_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596005264,
      "name": "unregister_net_sysctl_table",
      "external": true,
      "loc": "net/sysctl_net.c:173",
      "file": "net/sysctl_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sysctl_net_core.c:sysctl_core_net_exit",
        "net/core/neighbour.c:neigh_sysctl_unregister",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/route.c:sysctl_route_net_exit",
        "net/ipv4/ip_fragment.c:ipv4_frags_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_destroy",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini",
        "net/unix/sysctl_net_unix.c:unix_sysctl_unregister",
        "net/ipv6/addrconf.c:addrconf_exit_net",
        "net/ipv6/addrconf.c:addrconf_exit_net",
        "net/ipv6/addrconf.c:addrconf_init_net",
        "net/ipv6/addrconf.c:addrconf_sysctl_unregister",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/reassembly.c:ipv6_frags_exit_net",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit",
        "net/mptcp/ctrl.c:mptcp_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596005264,
      "name": "unregister_net_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void unregister_net_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_net_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596868544,
      "name": "unregister_net_sysctl_table",
      "external": true,
      "loc": "net/sysctl_net.c:183",
      "file": "net/sysctl_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sysctl_net_core.c:sysctl_core_net_exit",
        "net/core/neighbour.c:neigh_sysctl_unregister",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/route.c:sysctl_route_net_exit",
        "net/ipv4/ip_fragment.c:ipv4_frags_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_destroy",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini",
        "net/unix/sysctl_net_unix.c:unix_sysctl_unregister",
        "net/ipv6/addrconf.c:addrconf_exit_net",
        "net/ipv6/addrconf.c:addrconf_exit_net",
        "net/ipv6/addrconf.c:addrconf_init_net",
        "net/ipv6/addrconf.c:addrconf_sysctl_unregister",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/reassembly.c:ipv6_frags_exit_net",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit",
        "net/mptcp/ctrl.c:mptcp_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596868544,
      "name": "unregister_net_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void unregister_net_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_net_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503731392,
      "name": "unregister_net_sysctl_table",
      "external": true,
      "loc": "net/sysctl_net.c:125",
      "file": "net/sysctl_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_sysctl_unregister",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/ip_fragment.c:ipv4_frags_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini",
        "net/unix/sysctl_net_unix.c:unix_sysctl_unregister",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/reassembly.c:ipv6_frags_exit_net",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503731392,
      "name": "unregister_net_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void unregister_net_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_net_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236361352,
      "name": "unregister_net_sysctl_table",
      "external": true,
      "loc": "net/sysctl_net.c:125",
      "file": "net/sysctl_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_sysctl_unregister",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/ip_fragment.c:ipv4_frags_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:__devinet_sysctl_unregister",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini",
        "net/unix/sysctl_net_unix.c:unix_sysctl_unregister",
        "net/ipv6/addrconf.c:__addrconf_sysctl_unregister",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/reassembly.c:ipv6_frags_exit_net",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236361352,
      "name": "unregister_net_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void unregister_net_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_net_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297569712,
      "name": "unregister_net_sysctl_table",
      "external": true,
      "loc": "net/sysctl_net.c:125",
      "file": "net/sysctl_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sysctl_net_core.c:sysctl_core_net_exit",
        "net/core/neighbour.c:neigh_sysctl_unregister",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/route.c:sysctl_route_net_exit",
        "net/ipv4/ip_fragment.c:ipv4_frags_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini",
        "net/unix/sysctl_net_unix.c:unix_sysctl_unregister",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/reassembly.c:ipv6_frags_exit_net",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297569712,
      "name": "unregister_net_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void unregister_net_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_net_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279653104,
      "name": "unregister_net_sysctl_table",
      "external": true,
      "loc": "net/sysctl_net.c:125",
      "file": "net/sysctl_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_sysctl_unregister",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/ip_fragment.c:ipv4_frags_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini",
        "net/unix/sysctl_net_unix.c:unix_sysctl_unregister",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/reassembly.c:ipv6_frags_exit_net",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279653104,
      "name": "unregister_net_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void unregister_net_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_net_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589594016,
      "name": "unregister_net_sysctl_table",
      "external": true,
      "loc": "net/sysctl_net.c:125",
      "file": "net/sysctl_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_sysctl_unregister",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/ip_fragment.c:ipv4_frags_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini",
        "net/unix/sysctl_net_unix.c:unix_sysctl_unregister",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/reassembly.c:ipv6_frags_exit_net",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589594016,
      "name": "unregister_net_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void unregister_net_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_net_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589318544,
      "name": "unregister_net_sysctl_table",
      "external": true,
      "loc": "net/sysctl_net.c:125",
      "file": "net/sysctl_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/vxlan.c:vxlan_cleanup_module",
        "net/core/neighbour.c:neigh_sysctl_unregister",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/ip_fragment.c:ipv4_frags_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini",
        "net/unix/sysctl_net_unix.c:unix_sysctl_unregister",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/reassembly.c:ipv6_frags_exit_net",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589318544,
      "name": "unregister_net_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void unregister_net_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_net_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590036048,
      "name": "unregister_net_sysctl_table",
      "external": true,
      "loc": "net/sysctl_net.c:125",
      "file": "net/sysctl_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_sysctl_unregister",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/netfilter/nf_conntrack_standalone.c:nf_conntrack_standalone_fini",
        "net/netfilter/nf_conntrack_standalone.c:nf_conntrack_standalone_init",
        "net/netfilter/nf_conntrack_standalone.c:nf_conntrack_pernet_exit",
        "net/ipv4/ip_fragment.c:ipv4_frags_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini",
        "net/unix/sysctl_net_unix.c:unix_sysctl_unregister",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/reassembly.c:ipv6_frags_exit_net",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit",
        "net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590036048,
      "name": "unregister_net_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void unregister_net_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_net_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590086080,
      "name": "unregister_net_sysctl_table",
      "external": true,
      "loc": "net/sysctl_net.c:125",
      "file": "net/sysctl_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_sysctl_unregister",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_exit",
        "net/netfilter/nf_log.c:nf_log_net_init",
        "net/ipv4/ip_fragment.c:ipv4_frags_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini",
        "net/unix/sysctl_net_unix.c:unix_sysctl_unregister",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/reassembly.c:ipv6_frags_exit_net",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590086080,
      "name": "unregister_net_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
