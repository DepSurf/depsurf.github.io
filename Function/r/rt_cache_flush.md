# Function: <code>rt_cache_flush</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rt_cache_flush(struct net * net)
```

```json
{
  "name": "rt_cache_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586525425,
      "name": "rt_cache_flush",
      "external": true,
      "loc": "net/ipv4/route.c:438",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_sysctl_rtcache_flush",
        "net/ipv4/route.c:ip_rt_multicast_event"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_netdev_event",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/fib_frontend.c:fib_flush",
        "net/ipv4/fib_frontend.c:fib_disable_ip",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_rules.c:fib4_rule_flush_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586542992,
      "name": "rt_cache_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void rt_cache_flush(struct net * net)
```

```json
{
  "name": "rt_cache_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586968177,
      "name": "rt_cache_flush",
      "external": true,
      "loc": "net/ipv4/route.c:438",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_sysctl_rtcache_flush",
        "net/ipv4/route.c:ip_rt_multicast_event"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_netdev_event",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_disable_ip",
        "net/ipv4/fib_frontend.c:fib_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_rules.c:fib4_rule_flush_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586986032,
      "name": "rt_cache_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void rt_cache_flush(struct net * net)
```

```json
{
  "name": "rt_cache_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587163073,
      "name": "rt_cache_flush",
      "external": true,
      "loc": "net/ipv4/route.c:438",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_sysctl_rtcache_flush",
        "net/ipv4/route.c:ip_rt_multicast_event"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_netdev_event",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_disable_ip",
        "net/ipv4/fib_frontend.c:fib_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_rules.c:fib4_rule_flush_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587181392,
      "name": "rt_cache_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void rt_cache_flush(struct net * net)
```

```json
{
  "name": "rt_cache_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587294337,
      "name": "rt_cache_flush",
      "external": true,
      "loc": "net/ipv4/route.c:442",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_sysctl_rtcache_flush",
        "net/ipv4/route.c:ip_rt_multicast_event"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_netdev_event",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_disable_ip",
        "net/ipv4/fib_frontend.c:fib_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_rules.c:fib4_rule_flush_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587303312,
      "name": "rt_cache_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void rt_cache_flush(struct net * net)
```

```json
{
  "name": "rt_cache_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587816001,
      "name": "rt_cache_flush",
      "external": true,
      "loc": "net/ipv4/route.c:445",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_sysctl_rtcache_flush",
        "net/ipv4/route.c:ip_rt_multicast_event"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_netdev_event",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_disable_ip",
        "net/ipv4/fib_frontend.c:fib_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_rules.c:fib4_rule_flush_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587825008,
      "name": "rt_cache_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void rt_cache_flush(struct net * net)
```

```json
{
  "name": "rt_cache_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588159325,
      "name": "rt_cache_flush",
      "external": true,
      "loc": "net/ipv4/route.c:428",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_sysctl_rtcache_flush",
        "net/ipv4/route.c:ip_rt_multicast_event"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_netdev_event",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_disable_ip",
        "net/ipv4/fib_frontend.c:fib_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_rules.c:fib4_rule_flush_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588166912,
      "name": "rt_cache_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void rt_cache_flush(struct net * net)
```

```json
{
  "name": "rt_cache_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588343293,
      "name": "rt_cache_flush",
      "external": true,
      "loc": "net/ipv4/route.c:428",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_sysctl_rtcache_flush",
        "net/ipv4/route.c:ip_rt_multicast_event"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_netdev_event",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_disable_ip",
        "net/ipv4/fib_frontend.c:fib_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_rules.c:fib4_rule_flush_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588350944,
      "name": "rt_cache_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void rt_cache_flush(struct net * net)
```

```json
{
  "name": "rt_cache_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588743441,
      "name": "rt_cache_flush",
      "external": true,
      "loc": "net/ipv4/route.c:425",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_sysctl_rtcache_flush",
        "net/ipv4/route.c:ip_rt_multicast_event"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_netdev_event",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_disable_ip",
        "net/ipv4/fib_frontend.c:fib_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/nexthop.c:nh_netdev_event",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/fib_rules.c:fib4_rule_flush_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588754128,
      "name": "rt_cache_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void rt_cache_flush(struct net * net)
```

```json
{
  "name": "rt_cache_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588967185,
      "name": "rt_cache_flush",
      "external": true,
      "loc": "net/ipv4/route.c:426",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_sysctl_rtcache_flush",
        "net/ipv4/route.c:ip_rt_multicast_event"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_netdev_event",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_disable_ip",
        "net/ipv4/fib_frontend.c:fib_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/nexthop.c:nh_netdev_event",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/fib_rules.c:fib4_rule_flush_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588977744,
      "name": "rt_cache_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void rt_cache_flush(struct net * net)
```

```json
{
  "name": "rt_cache_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589922401,
      "name": "rt_cache_flush",
      "external": true,
      "loc": "net/ipv4/route.c:427",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_sysctl_rtcache_flush",
        "net/ipv4/route.c:ip_rt_multicast_event"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_netdev_event",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/nexthop.c:nh_netdev_event",
        "net/ipv4/nexthop.c:replace_nexthop",
        "net/ipv4/fib_rules.c:fib4_rule_flush_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589938000,
      "name": "rt_cache_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void rt_cache_flush(struct net * net)
```

```json
{
  "name": "rt_cache_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589962961,
      "name": "rt_cache_flush",
      "external": true,
      "loc": "net/ipv4/route.c:427",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_sysctl_rtcache_flush",
        "net/ipv4/route.c:ip_rt_multicast_event"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_netdev_event",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/nexthop.c:nh_netdev_event",
        "net/ipv4/nexthop.c:replace_nexthop",
        "net/ipv4/fib_rules.c:fib4_rule_flush_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589978896,
      "name": "rt_cache_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void rt_cache_flush(struct net * net)
```

```json
{
  "name": "rt_cache_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589877697,
      "name": "rt_cache_flush",
      "external": true,
      "loc": "net/ipv4/route.c:404",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_sysctl_rtcache_flush",
        "net/ipv4/route.c:ip_rt_multicast_event"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_netdev_event",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/nexthop.c:nh_netdev_event",
        "net/ipv4/nexthop.c:replace_nexthop",
        "net/ipv4/fib_rules.c:fib4_rule_flush_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589892720,
      "name": "rt_cache_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void rt_cache_flush(struct net * net)
```

```json
{
  "name": "rt_cache_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590641553,
      "name": "rt_cache_flush",
      "external": true,
      "loc": "net/ipv4/route.c:405",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_sysctl_rtcache_flush",
        "net/ipv4/route.c:ip_rt_multicast_event"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_netdev_event",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/nexthop.c:nh_netdev_event",
        "net/ipv4/nexthop.c:replace_nexthop",
        "net/ipv4/fib_rules.c:fib4_rule_flush_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590657440,
      "name": "rt_cache_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void rt_cache_flush(struct net * net)
```

```json
{
  "name": "rt_cache_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592265825,
      "name": "rt_cache_flush",
      "external": true,
      "loc": "net/ipv4/route.c:398",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_sysctl_rtcache_flush",
        "net/ipv4/route.c:ip_rt_multicast_event"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_netdev_event",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/nexthop.c:nh_netdev_event",
        "net/ipv4/nexthop.c:nh_netdev_event",
        "net/ipv4/nexthop.c:replace_nexthop",
        "net/ipv4/fib_rules.c:fib4_rule_flush_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592282336,
      "name": "rt_cache_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void rt_cache_flush(struct net * net)
```

```json
{
  "name": "rt_cache_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594100737,
      "name": "rt_cache_flush",
      "external": true,
      "loc": "net/ipv4/route.c:398",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_sysctl_rtcache_flush",
        "net/ipv4/route.c:ip_rt_multicast_event"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_netdev_event",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/nexthop.c:nh_netdev_event",
        "net/ipv4/nexthop.c:nh_netdev_event",
        "net/ipv4/nexthop.c:replace_nexthop",
        "net/ipv4/fib_rules.c:fib4_rule_flush_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594117808,
      "name": "rt_cache_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void rt_cache_flush(struct net * net)
```

```json
{
  "name": "rt_cache_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594487633,
      "name": "rt_cache_flush",
      "external": true,
      "loc": "net/ipv4/route.c:398",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_sysctl_rtcache_flush",
        "net/ipv4/route.c:ip_rt_multicast_event"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_netdev_event",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/nexthop.c:nh_netdev_event",
        "net/ipv4/nexthop.c:replace_nexthop",
        "net/ipv4/fib_rules.c:fib4_rule_flush_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594504800,
      "name": "rt_cache_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void rt_cache_flush(struct net * net)
```

```json
{
  "name": "rt_cache_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595290481,
      "name": "rt_cache_flush",
      "external": true,
      "loc": "net/ipv4/route.c:398",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_sysctl_rtcache_flush",
        "net/ipv4/route.c:ip_rt_multicast_event"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_netdev_event",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/nexthop.c:nh_netdev_event",
        "net/ipv4/nexthop.c:replace_nexthop",
        "net/ipv4/fib_rules.c:fib4_rule_flush_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595307968,
      "name": "rt_cache_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void rt_cache_flush(struct net * net)
```

```json
{
  "name": "rt_cache_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502577020,
      "name": "rt_cache_flush",
      "external": true,
      "loc": "net/ipv4/route.c:426",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_sysctl_rtcache_flush",
        "net/ipv4/route.c:ip_rt_multicast_event"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_netdev_event",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_disable_ip",
        "net/ipv4/fib_frontend.c:fib_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/nexthop.c:nh_netdev_event",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/fib_rules.c:fib4_rule_flush_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502582600,
      "name": "rt_cache_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void rt_cache_flush(struct net * net)
```

```json
{
  "name": "rt_cache_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235276648,
      "name": "rt_cache_flush",
      "external": true,
      "loc": "net/ipv4/route.c:426",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_sysctl_rtcache_flush",
        "net/ipv4/route.c:ip_rt_multicast_event"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_netdev_event",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_disable_ip",
        "net/ipv4/fib_frontend.c:fib_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/nexthop.c:nh_netdev_event",
        "net/ipv4/nexthop.c:nh_netdev_event",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/fib_rules.c:fib4_rule_flush_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235288004,
      "name": "rt_cache_flush",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void rt_cache_flush(struct net * net)
```

```json
{
  "name": "rt_cache_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296155060,
      "name": "rt_cache_flush",
      "external": true,
      "loc": "net/ipv4/route.c:426",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_sysctl_rtcache_flush",
        "net/ipv4/route.c:ip_rt_multicast_event"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_netdev_event",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_disable_ip",
        "net/ipv4/fib_frontend.c:fib_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/nexthop.c:nh_netdev_event",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/fib_rules.c:fib4_rule_flush_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296169664,
      "name": "rt_cache_flush",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void rt_cache_flush(struct net * net)
```

```json
{
  "name": "rt_cache_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278728526,
      "name": "rt_cache_flush",
      "external": true,
      "loc": "net/ipv4/route.c:426",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_sysctl_rtcache_flush",
        "net/ipv4/route.c:ip_rt_multicast_event"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_netdev_event",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_disable_ip",
        "net/ipv4/fib_frontend.c:fib_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/nexthop.c:nh_netdev_event",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/fib_rules.c:fib4_rule_flush_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278737976,
      "name": "rt_cache_flush",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void rt_cache_flush(struct net * net)
```

```json
{
  "name": "rt_cache_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588573569,
      "name": "rt_cache_flush",
      "external": true,
      "loc": "net/ipv4/route.c:426",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_sysctl_rtcache_flush",
        "net/ipv4/route.c:ip_rt_multicast_event"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_netdev_event",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_disable_ip",
        "net/ipv4/fib_frontend.c:fib_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/nexthop.c:nh_netdev_event",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/fib_rules.c:fib4_rule_flush_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588584128,
      "name": "rt_cache_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void rt_cache_flush(struct net * net)
```

```json
{
  "name": "rt_cache_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588285553,
      "name": "rt_cache_flush",
      "external": true,
      "loc": "net/ipv4/route.c:426",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_sysctl_rtcache_flush",
        "net/ipv4/route.c:ip_rt_multicast_event"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_netdev_event",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_disable_ip",
        "net/ipv4/fib_frontend.c:fib_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/nexthop.c:nh_netdev_event",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/fib_rules.c:fib4_rule_flush_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588296112,
      "name": "rt_cache_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void rt_cache_flush(struct net * net)
```

```json
{
  "name": "rt_cache_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589009745,
      "name": "rt_cache_flush",
      "external": true,
      "loc": "net/ipv4/route.c:426",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_sysctl_rtcache_flush",
        "net/ipv4/route.c:ip_rt_multicast_event"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_netdev_event",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_disable_ip",
        "net/ipv4/fib_frontend.c:fib_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/nexthop.c:nh_netdev_event",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/fib_rules.c:fib4_rule_flush_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589020304,
      "name": "rt_cache_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void rt_cache_flush(struct net * net)
```

```json
{
  "name": "rt_cache_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589048305,
      "name": "rt_cache_flush",
      "external": true,
      "loc": "net/ipv4/route.c:426",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_sysctl_rtcache_flush",
        "net/ipv4/route.c:ip_rt_multicast_event"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_netdev_event",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_disable_ip",
        "net/ipv4/fib_frontend.c:fib_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/nexthop.c:nh_netdev_event",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/fib_rules.c:fib4_rule_flush_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589058960,
      "name": "rt_cache_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
