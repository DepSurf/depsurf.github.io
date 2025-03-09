# Function: <code>rt_dst_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct rtable * rt_dst_alloc(struct net_device * dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm, bool will_cache)
```

```json
{
  "name": "rt_dst_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586526544,
      "name": "rt_dst_alloc",
      "external": false,
      "loc": "net/ipv4/route.c:1441",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__ip_route_output_key_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586526544,
      "name": "rt_dst_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
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
struct rtable * rt_dst_alloc(struct net_device * dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm, bool will_cache)
```

```json
{
  "name": "rt_dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586968768,
      "name": "rt_dst_alloc",
      "external": true,
      "loc": "net/ipv4/route.c:1447",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__ip_route_output_key_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586968768,
      "name": "rt_dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
struct rtable * rt_dst_alloc(struct net_device * dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm, bool will_cache)
```

```json
{
  "name": "rt_dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587163664,
      "name": "rt_dst_alloc",
      "external": true,
      "loc": "net/ipv4/route.c:1457",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__ip_route_output_key_hash",
        "net/ipv4/route.c:ip_route_input_noref",
        "net/ipv4/route.c:ip_route_input_noref",
        "net/ipv4/route.c:ip_route_input_noref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587163664,
      "name": "rt_dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
struct rtable * rt_dst_alloc(struct net_device * dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm, bool will_cache)
```

```json
{
  "name": "rt_dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587294976,
      "name": "rt_dst_alloc",
      "external": true,
      "loc": "net/ipv4/route.c:1490",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587294976,
      "name": "rt_dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
struct rtable * rt_dst_alloc(struct net_device * dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm, bool will_cache)
```

```json
{
  "name": "rt_dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587816640,
      "name": "rt_dst_alloc",
      "external": true,
      "loc": "net/ipv4/route.c:1497",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587816640,
      "name": "rt_dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
struct rtable * rt_dst_alloc(struct net_device * dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm, bool will_cache)
```

```json
{
  "name": "rt_dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588159968,
      "name": "rt_dst_alloc",
      "external": true,
      "loc": "net/ipv4/route.c:1570",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588159968,
      "name": "rt_dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
struct rtable * rt_dst_alloc(struct net_device * dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm, bool will_cache)
```

```json
{
  "name": "rt_dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588343936,
      "name": "rt_dst_alloc",
      "external": true,
      "loc": "net/ipv4/route.c:1567",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588343936,
      "name": "rt_dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
struct rtable * rt_dst_alloc(struct net_device * dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm, bool will_cache)
```

```json
{
  "name": "rt_dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588744016,
      "name": "rt_dst_alloc",
      "external": true,
      "loc": "net/ipv4/route.c:1618",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588744016,
      "name": "rt_dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
struct rtable * rt_dst_alloc(struct net_device * dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm, bool will_cache)
```

```json
{
  "name": "rt_dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588967760,
      "name": "rt_dst_alloc",
      "external": true,
      "loc": "net/ipv4/route.c:1621",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588967760,
      "name": "rt_dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
struct rtable * rt_dst_alloc(struct net_device * dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm)
```

```json
{
  "name": "rt_dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589922816,
      "name": "rt_dst_alloc",
      "external": true,
      "loc": "net/ipv4/route.c:1625",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__mkroute_output",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:__mkroute_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589922816,
      "name": "rt_dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
struct rtable * rt_dst_alloc(struct net_device * dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm)
```

```json
{
  "name": "rt_dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589963344,
      "name": "rt_dst_alloc",
      "external": true,
      "loc": "net/ipv4/route.c:1631",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__mkroute_output",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:__mkroute_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589963344,
      "name": "rt_dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
struct rtable * rt_dst_alloc(struct net_device * dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm)
```

```json
{
  "name": "rt_dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589878240,
      "name": "rt_dst_alloc",
      "external": true,
      "loc": "net/ipv4/route.c:1619",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__mkroute_output",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:__mkroute_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589878240,
      "name": "rt_dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
struct rtable * rt_dst_alloc(struct net_device * dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm)
```

```json
{
  "name": "rt_dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590642144,
      "name": "rt_dst_alloc",
      "external": true,
      "loc": "net/ipv4/route.c:1615",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__mkroute_output",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:__mkroute_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590642144,
      "name": "rt_dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
struct rtable * rt_dst_alloc(struct net_device * dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm)
```

```json
{
  "name": "rt_dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592266704,
      "name": "rt_dst_alloc",
      "external": true,
      "loc": "net/ipv4/route.c:1628",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__mkroute_output",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:__mkroute_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592266704,
      "name": "rt_dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
struct rtable * rt_dst_alloc(struct net_device * dev, unsigned int flags, u16 type, bool noxfrm)
```

```json
{
  "name": "rt_dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594101712,
      "name": "rt_dst_alloc",
      "external": true,
      "loc": "net/ipv4/route.c:1627",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__mkroute_output",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:__mkroute_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594101712,
      "name": "rt_dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
struct rtable * rt_dst_alloc(struct net_device * dev, unsigned int flags, u16 type, bool noxfrm)
```

```json
{
  "name": "rt_dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594488576,
      "name": "rt_dst_alloc",
      "external": true,
      "loc": "net/ipv4/route.c:1627",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__mkroute_output",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:__mkroute_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594488576,
      "name": "rt_dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
struct rtable * rt_dst_alloc(struct net_device * dev, unsigned int flags, u16 type, bool noxfrm)
```

```json
{
  "name": "rt_dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595291424,
      "name": "rt_dst_alloc",
      "external": true,
      "loc": "net/ipv4/route.c:1629",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__mkroute_output",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:__mkroute_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595291424,
      "name": "rt_dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
struct rtable * rt_dst_alloc(struct net_device * dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm, bool will_cache)
```

```json
{
  "name": "rt_dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502571256,
      "name": "rt_dst_alloc",
      "external": true,
      "loc": "net/ipv4/route.c:1621",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502571256,
      "name": "rt_dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
struct rtable * rt_dst_alloc(struct net_device * dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm, bool will_cache)
```

```json
{
  "name": "rt_dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235276876,
      "name": "rt_dst_alloc",
      "external": true,
      "loc": "net/ipv4/route.c:1621",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235276876,
      "name": "rt_dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
struct rtable * rt_dst_alloc(struct net_device * dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm, bool will_cache)
```

```json
{
  "name": "rt_dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296155760,
      "name": "rt_dst_alloc",
      "external": true,
      "loc": "net/ipv4/route.c:1621",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296155760,
      "name": "rt_dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
struct rtable * rt_dst_alloc(struct net_device * dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm, bool will_cache)
```

```json
{
  "name": "rt_dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278728992,
      "name": "rt_dst_alloc",
      "external": true,
      "loc": "net/ipv4/route.c:1621",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278728992,
      "name": "rt_dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
struct rtable * rt_dst_alloc(struct net_device * dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm, bool will_cache)
```

```json
{
  "name": "rt_dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588574144,
      "name": "rt_dst_alloc",
      "external": true,
      "loc": "net/ipv4/route.c:1621",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588574144,
      "name": "rt_dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
struct rtable * rt_dst_alloc(struct net_device * dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm, bool will_cache)
```

```json
{
  "name": "rt_dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588286128,
      "name": "rt_dst_alloc",
      "external": true,
      "loc": "net/ipv4/route.c:1621",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588286128,
      "name": "rt_dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
struct rtable * rt_dst_alloc(struct net_device * dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm, bool will_cache)
```

```json
{
  "name": "rt_dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589010320,
      "name": "rt_dst_alloc",
      "external": true,
      "loc": "net/ipv4/route.c:1621",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589010320,
      "name": "rt_dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
struct rtable * rt_dst_alloc(struct net_device * dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm, bool will_cache)
```

```json
{
  "name": "rt_dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589048880,
      "name": "rt_dst_alloc",
      "external": true,
      "loc": "net/ipv4/route.c:1621",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589048880,
      "name": "rt_dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool will_cache</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool nopolicy</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, flags, type, nopolicy, noxfrm</code> ➡️ <code>dev, flags, type, noxfrm</code>
</li>
</ul>
</details>
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
