# Function: <code>fib_get_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fib_table * fib_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib_get_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586815678,
      "name": "fib_get_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:115",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/fib_frontend.c:inet_addr_type",
        "net/ipv4/fib_frontend.c:inet_addr_type_dev_table",
        "net/ipv4/fib_frontend.c:inet_dev_addr_type",
        "net/ipv4/fib_frontend.c:fib_new_table",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl"
      ],
      "caller_func": [
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_trie.c:fib_route_seq_start",
        "net/ipv4/fib_rules.c:fib4_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586818272,
      "name": "fib_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fib_table * fib_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib_get_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587266506,
      "name": "fib_get_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:116",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/fib_frontend.c:inet_addr_type_dev_table",
        "net/ipv4/fib_frontend.c:inet_dev_addr_type",
        "net/ipv4/fib_frontend.c:inet_addr_type",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_new_table"
      ],
      "caller_func": [
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_trie.c:fib_route_seq_start",
        "net/ipv4/fib_rules.c:fib4_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587267856,
      "name": "fib_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fib_table * fib_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib_get_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587467418,
      "name": "fib_get_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:114",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/fib_frontend.c:inet_addr_type_dev_table",
        "net/ipv4/fib_frontend.c:inet_dev_addr_type",
        "net/ipv4/fib_frontend.c:inet_addr_type",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_new_table"
      ],
      "caller_func": [
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_trie.c:fib_route_seq_start",
        "net/ipv4/fib_rules.c:fib4_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587468784,
      "name": "fib_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fib_table * fib_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib_get_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587603902,
      "name": "fib_get_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:114",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/fib_frontend.c:inet_addr_type_dev_table",
        "net/ipv4/fib_frontend.c:inet_dev_addr_type",
        "net/ipv4/fib_frontend.c:inet_addr_type",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_new_table"
      ],
      "caller_func": [
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_trie.c:fib_route_seq_start",
        "net/ipv4/fib_rules.c:fib4_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587605328,
      "name": "fib_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fib_table * fib_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib_get_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588127966,
      "name": "fib_get_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:119",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/fib_frontend.c:inet_addr_type_dev_table",
        "net/ipv4/fib_frontend.c:inet_dev_addr_type",
        "net/ipv4/fib_frontend.c:inet_addr_type",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_new_table"
      ],
      "caller_func": [
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_trie.c:fib_route_seq_start",
        "net/ipv4/fib_rules.c:fib4_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588129408,
      "name": "fib_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fib_table * fib_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib_get_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588482914,
      "name": "fib_get_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:119",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/fib_frontend.c:inet_addr_type_dev_table",
        "net/ipv4/fib_frontend.c:inet_dev_addr_type",
        "net/ipv4/fib_frontend.c:inet_addr_type",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_new_table"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_semantics.c:fib_check_nh",
        "net/ipv4/fib_trie.c:fib_route_seq_start",
        "net/ipv4/fib_rules.c:fib4_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588485648,
      "name": "fib_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fib_table * fib_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib_get_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588677727,
      "name": "fib_get_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:119",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/fib_frontend.c:inet_dump_fib",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/fib_frontend.c:inet_addr_type_dev_table",
        "net/ipv4/fib_frontend.c:inet_dev_addr_type",
        "net/ipv4/fib_frontend.c:inet_addr_type",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_new_table"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_trie.c:fib_route_seq_start",
        "net/ipv4/fib_rules.c:fib4_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588680304,
      "name": "fib_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fib_table * fib_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib_get_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589089889,
      "name": "fib_get_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:116",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:inet_dump_fib",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_new_table"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_trie.c:fib_route_seq_start",
        "net/ipv4/fib_rules.c:fib4_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589091744,
      "name": "fib_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fib_table * fib_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib_get_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589314049,
      "name": "fib_get_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:116",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:inet_dump_fib",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_new_table"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_trie.c:fib_route_seq_start",
        "net/ipv4/fib_rules.c:fib4_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589315904,
      "name": "fib_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fib_table * fib_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib_get_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590291977,
      "name": "fib_get_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:111",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:nl_fib_lookup",
        "net/ipv4/fib_frontend.c:inet_dump_fib",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/fib_frontend.c:__inet_dev_addr_type",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_new_table"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_trie.c:fib_route_seq_start",
        "net/ipv4/fib_trie.c:fib_find_matching_alias",
        "net/ipv4/fib_rules.c:fib4_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590294288,
      "name": "fib_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fib_table * fib_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib_get_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590344873,
      "name": "fib_get_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:111",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:nl_fib_lookup",
        "net/ipv4/fib_frontend.c:inet_dump_fib",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/fib_frontend.c:__inet_dev_addr_type",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_new_table"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_trie.c:fib_route_seq_start",
        "net/ipv4/fib_trie.c:fib_find_matching_alias",
        "net/ipv4/fib_rules.c:fib4_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590347280,
      "name": "fib_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fib_table * fib_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib_get_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590260681,
      "name": "fib_get_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:111",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:nl_fib_lookup",
        "net/ipv4/fib_frontend.c:inet_dump_fib",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/fib_frontend.c:__inet_dev_addr_type",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_new_table"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_trie.c:fib_route_seq_start",
        "net/ipv4/fib_trie.c:fib_alias_hw_flags_set",
        "net/ipv4/fib_rules.c:fib4_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590263088,
      "name": "fib_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fib_table * fib_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib_get_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591044601,
      "name": "fib_get_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:111",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:nl_fib_lookup",
        "net/ipv4/fib_frontend.c:inet_dump_fib",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/fib_frontend.c:__inet_dev_addr_type",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_new_table"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_trie.c:fib_route_seq_start",
        "net/ipv4/fib_trie.c:fib_alias_hw_flags_set",
        "net/ipv4/fib_rules.c:fib4_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591047744,
      "name": "fib_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fib_table * fib_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib_get_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592692966,
      "name": "fib_get_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:112",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:nl_fib_lookup",
        "net/ipv4/fib_frontend.c:inet_dump_fib",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/fib_frontend.c:__inet_dev_addr_type",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_new_table"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_trie.c:fib_route_seq_start",
        "net/ipv4/fib_trie.c:fib_alias_hw_flags_set",
        "net/ipv4/fib_rules.c:fib4_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592696384,
      "name": "fib_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fib_table * fib_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib_get_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594562038,
      "name": "fib_get_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:112",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:nl_fib_lookup",
        "net/ipv4/fib_frontend.c:inet_dump_fib",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/fib_frontend.c:__inet_dev_addr_type",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_new_table"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_trie.c:fib_route_seq_start",
        "net/ipv4/fib_trie.c:fib_alias_hw_flags_set",
        "net/ipv4/fib_rules.c:fib4_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594565632,
      "name": "fib_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fib_table * fib_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib_get_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594953782,
      "name": "fib_get_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:112",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:nl_fib_lookup",
        "net/ipv4/fib_frontend.c:inet_dump_fib",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/fib_frontend.c:__inet_dev_addr_type",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_new_table"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_trie.c:fib_route_seq_start",
        "net/ipv4/fib_trie.c:fib_alias_hw_flags_set",
        "net/ipv4/fib_rules.c:fib4_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594957456,
      "name": "fib_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fib_table * fib_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib_get_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595766198,
      "name": "fib_get_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:112",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:nl_fib_lookup",
        "net/ipv4/fib_frontend.c:inet_dump_fib",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/fib_frontend.c:__inet_dev_addr_type",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_new_table"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_trie.c:fib_route_seq_start",
        "net/ipv4/fib_trie.c:fib_alias_hw_flags_set",
        "net/ipv4/fib_rules.c:fib4_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595769936,
      "name": "fib_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct fib_table * fib_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib_get_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502951500,
      "name": "fib_get_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:116",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:inet_dump_fib",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_new_table"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_trie.c:fib_route_seq_start",
        "net/ipv4/fib_rules.c:fib4_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502954216,
      "name": "fib_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct fib_table * fib_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib_get_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235640104,
      "name": "fib_get_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:116",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/fib_frontend.c:inet_dump_fib",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/fib_frontend.c:rtentry_to_fib_config",
        "net/ipv4/fib_frontend.c:inet_addr_type_dev_table",
        "net/ipv4/fib_frontend.c:inet_dev_addr_type",
        "net/ipv4/fib_frontend.c:inet_addr_type",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_new_table"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_semantics.c:fib_check_nh",
        "net/ipv4/fib_trie.c:fib_route_seq_start",
        "net/ipv4/fib_rules.c:fib4_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235644184,
      "name": "fib_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct fib_table * fib_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib_get_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296624880,
      "name": "fib_get_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:116",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:nl_fib_lookup",
        "net/ipv4/fib_frontend.c:inet_dump_fib",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/fib_frontend.c:__inet_dev_addr_type",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_new_table"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_trie.c:fib_route_seq_start",
        "net/ipv4/fib_rules.c:fib4_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296629216,
      "name": "fib_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct fib_table * fib_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib_get_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279033688,
      "name": "fib_get_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:116",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:nl_fib_lookup",
        "net/ipv4/fib_frontend.c:inet_dump_fib",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/fib_frontend.c:__inet_dev_addr_type",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_new_table"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_trie.c:fib_route_seq_start",
        "net/ipv4/fib_rules.c:fib4_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279037236,
      "name": "fib_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct fib_table * fib_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib_get_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588920225,
      "name": "fib_get_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:116",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:inet_dump_fib",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_new_table"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_trie.c:fib_route_seq_start",
        "net/ipv4/fib_rules.c:fib4_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588922080,
      "name": "fib_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct fib_table * fib_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib_get_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588632161,
      "name": "fib_get_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:116",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:inet_dump_fib",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_new_table"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_trie.c:fib_route_seq_start",
        "net/ipv4/fib_rules.c:fib4_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588634016,
      "name": "fib_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct fib_table * fib_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib_get_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589356609,
      "name": "fib_get_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:116",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:inet_dump_fib",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_new_table"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_trie.c:fib_route_seq_start",
        "net/ipv4/fib_rules.c:fib4_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589358464,
      "name": "fib_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct fib_table * fib_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib_get_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589399033,
      "name": "fib_get_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:116",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:inet_dump_fib",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_unmerge",
        "net/ipv4/fib_frontend.c:fib_new_table"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/devinet.c:__ip_dev_find",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_trie.c:fib_route_seq_start",
        "net/ipv4/fib_rules.c:fib4_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589401136,
      "name": "fib_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
