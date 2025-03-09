# Function: <code>rt6_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct rt6_info * rt6_lookup(struct net * net, const struct in6_addr * daddr, const struct in6_addr * saddr, int oif, int strict)
```

```json
{
  "name": "rt6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587050528,
      "name": "rt6_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:879",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/mcast.c:ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587050528,
      "name": "rt6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
struct rt6_info * rt6_lookup(struct net * net, const struct in6_addr * daddr, const struct in6_addr * saddr, int oif, int strict)
```

```json
{
  "name": "rt6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587499856,
      "name": "rt6_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:884",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/mcast.c:ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587499856,
      "name": "rt6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
struct rt6_info * rt6_lookup(struct net * net, const struct in6_addr * daddr, const struct in6_addr * saddr, int oif, int strict)
```

```json
{
  "name": "rt6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587703872,
      "name": "rt6_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:887",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/mcast.c:ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587703872,
      "name": "rt6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
struct rt6_info * rt6_lookup(struct net * net, const struct in6_addr * daddr, const struct in6_addr * saddr, int oif, int strict)
```

```json
{
  "name": "rt6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587854416,
      "name": "rt6_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:906",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/mcast.c:ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587854416,
      "name": "rt6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
struct rt6_info * rt6_lookup(struct net * net, const struct in6_addr * daddr, const struct in6_addr * saddr, int oif, int strict)
```

```json
{
  "name": "rt6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588383472,
      "name": "rt6_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:969",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/mcast.c:ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588383472,
      "name": "rt6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
struct rt6_info * rt6_lookup(struct net * net, const struct in6_addr * daddr, const struct in6_addr * saddr, int oif, const struct sk_buff * skb, int strict)
```

```json
{
  "name": "rt6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588743632,
      "name": "rt6_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:1116",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588743632,
      "name": "rt6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
struct rt6_info * rt6_lookup(struct net * net, const struct in6_addr * daddr, const struct in6_addr * saddr, int oif, const struct sk_buff * skb, int strict)
```

```json
{
  "name": "rt6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588963840,
      "name": "rt6_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:1119",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588963840,
      "name": "rt6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
struct rt6_info * rt6_lookup(struct net * net, const struct in6_addr * daddr, const struct in6_addr * saddr, int oif, const struct sk_buff * skb, int strict)
```

```json
{
  "name": "rt6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589407280,
      "name": "rt6_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:1269",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589407280,
      "name": "rt6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
struct rt6_info * rt6_lookup(struct net * net, const struct in6_addr * daddr, const struct in6_addr * saddr, int oif, const struct sk_buff * skb, int strict)
```

```json
{
  "name": "rt6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589631520,
      "name": "rt6_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:1275",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589631520,
      "name": "rt6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
struct rt6_info * rt6_lookup(struct net * net, const struct in6_addr * daddr, const struct in6_addr * saddr, int oif, const struct sk_buff * skb, int strict)
```

```json
{
  "name": "rt6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590641776,
      "name": "rt6_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:1276",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590641776,
      "name": "rt6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
struct rt6_info * rt6_lookup(struct net * net, const struct in6_addr * daddr, const struct in6_addr * saddr, int oif, const struct sk_buff * skb, int strict)
```

```json
{
  "name": "rt6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590702432,
      "name": "rt6_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:1259",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590702432,
      "name": "rt6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
struct rt6_info * rt6_lookup(struct net * net, const struct in6_addr * daddr, const struct in6_addr * saddr, int oif, const struct sk_buff * skb, int strict)
```

```json
{
  "name": "rt6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590628240,
      "name": "rt6_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:1262",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rtnl",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590628240,
      "name": "rt6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
struct rt6_info * rt6_lookup(struct net * net, const struct in6_addr * daddr, const struct in6_addr * saddr, int oif, const struct sk_buff * skb, int strict)
```

```json
{
  "name": "rt6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591441712,
      "name": "rt6_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:1262",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rtnl",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591441712,
      "name": "rt6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
struct rt6_info * rt6_lookup(struct net * net, const struct in6_addr * daddr, const struct in6_addr * saddr, int oif, const struct sk_buff * skb, int strict)
```

```json
{
  "name": "rt6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593121040,
      "name": "rt6_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:1262",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rtnl",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593121040,
      "name": "rt6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
struct rt6_info * rt6_lookup(struct net * net, const struct in6_addr * daddr, const struct in6_addr * saddr, int oif, const struct sk_buff * skb, int strict)
```

```json
{
  "name": "rt6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595017504,
      "name": "rt6_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:1262",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rtnl",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595017504,
      "name": "rt6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
struct rt6_info * rt6_lookup(struct net * net, const struct in6_addr * daddr, const struct in6_addr * saddr, int oif, const struct sk_buff * skb, int strict)
```

```json
{
  "name": "rt6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595411040,
      "name": "rt6_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:1261",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rtnl",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595411040,
      "name": "rt6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
struct rt6_info * rt6_lookup(struct net * net, const struct in6_addr * daddr, const struct in6_addr * saddr, int oif, const struct sk_buff * skb, int strict)
```

```json
{
  "name": "rt6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596252736,
      "name": "rt6_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:1263",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rtnl",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596252736,
      "name": "rt6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
struct rt6_info * rt6_lookup(struct net * net, const struct in6_addr * daddr, const struct in6_addr * saddr, int oif, const struct sk_buff * skb, int strict)
```

```json
{
  "name": "rt6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503315032,
      "name": "rt6_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:1275",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503315032,
      "name": "rt6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
struct rt6_info * rt6_lookup(struct net * net, const struct in6_addr * daddr, const struct in6_addr * saddr, int oif, const struct sk_buff * skb, int strict)
```

```json
{
  "name": "rt6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235981876,
      "name": "rt6_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:1275",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235981876,
      "name": "rt6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
struct rt6_info * rt6_lookup(struct net * net, const struct in6_addr * daddr, const struct in6_addr * saddr, int oif, const struct sk_buff * skb, int strict)
```

```json
{
  "name": "rt6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297071440,
      "name": "rt6_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:1275",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297071440,
      "name": "rt6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
struct rt6_info * rt6_lookup(struct net * net, const struct in6_addr * daddr, const struct in6_addr * saddr, int oif, const struct sk_buff * skb, int strict)
```

```json
{
  "name": "rt6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279329538,
      "name": "rt6_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:1275",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279329538,
      "name": "rt6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
struct rt6_info * rt6_lookup(struct net * net, const struct in6_addr * daddr, const struct in6_addr * saddr, int oif, const struct sk_buff * skb, int strict)
```

```json
{
  "name": "rt6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589235888,
      "name": "rt6_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:1275",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589235888,
      "name": "rt6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
struct rt6_info * rt6_lookup(struct net * net, const struct in6_addr * daddr, const struct in6_addr * saddr, int oif, const struct sk_buff * skb, int strict)
```

```json
{
  "name": "rt6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588960880,
      "name": "rt6_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:1275",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588960880,
      "name": "rt6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
struct rt6_info * rt6_lookup(struct net * net, const struct in6_addr * daddr, const struct in6_addr * saddr, int oif, const struct sk_buff * skb, int strict)
```

```json
{
  "name": "rt6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589672752,
      "name": "rt6_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:1275",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589672752,
      "name": "rt6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
struct rt6_info * rt6_lookup(struct net * net, const struct in6_addr * daddr, const struct in6_addr * saddr, int oif, const struct sk_buff * skb, int strict)
```

```json
{
  "name": "rt6_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589721888,
      "name": "rt6_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:1275",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589721888,
      "name": "rt6_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct sk_buff * skb</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, daddr, saddr, oif, strict</code> ➡️ <code>net, daddr, saddr, oif, skb, strict</code>
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
