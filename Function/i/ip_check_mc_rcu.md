# Function: <code>ip_check_mc_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ip_check_mc_rcu(struct in_device * in_dev, __be32 mc_addr, __be32 src_addr, u8 proto)
```

```json
{
  "name": "ip_check_mc_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586814272,
      "name": "ip_check_mc_rcu",
      "external": true,
      "loc": "net/ipv4/igmp.c:2569",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__ip_route_output_key_hash",
        "net/ipv4/udp.c:udp_v4_early_demux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586814272,
      "name": "ip_check_mc_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int ip_check_mc_rcu(struct in_device * in_dev, __be32 mc_addr, __be32 src_addr, u8 proto)
```

```json
{
  "name": "ip_check_mc_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587263696,
      "name": "ip_check_mc_rcu",
      "external": true,
      "loc": "net/ipv4/igmp.c:2580",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__ip_route_output_key_hash",
        "net/ipv4/udp.c:udp_v4_early_demux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587263696,
      "name": "ip_check_mc_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int ip_check_mc_rcu(struct in_device * in_dev, __be32 mc_addr, __be32 src_addr, u8 proto)
```

```json
{
  "name": "ip_check_mc_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587464544,
      "name": "ip_check_mc_rcu",
      "external": true,
      "loc": "net/ipv4/igmp.c:2618",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__ip_route_output_key_hash",
        "net/ipv4/route.c:ip_route_input_noref",
        "net/ipv4/route.c:ip_route_input_noref",
        "net/ipv4/udp.c:udp_v4_early_demux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587464544,
      "name": "ip_check_mc_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
int ip_check_mc_rcu(struct in_device * in_dev, __be32 mc_addr, __be32 src_addr, u8 proto)
```

```json
{
  "name": "ip_check_mc_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587600816,
      "name": "ip_check_mc_rcu",
      "external": true,
      "loc": "net/ipv4/igmp.c:2632",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/udp.c:udp_v4_early_demux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587600816,
      "name": "ip_check_mc_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int ip_check_mc_rcu(struct in_device * in_dev, __be32 mc_addr, __be32 src_addr, u8 proto)
```

```json
{
  "name": "ip_check_mc_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588124848,
      "name": "ip_check_mc_rcu",
      "external": true,
      "loc": "net/ipv4/igmp.c:2660",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/udp.c:udp_v4_early_demux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588124848,
      "name": "ip_check_mc_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int ip_check_mc_rcu(struct in_device * in_dev, __be32 mc_addr, __be32 src_addr, u8 proto)
```

```json
{
  "name": "ip_check_mc_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588479728,
      "name": "ip_check_mc_rcu",
      "external": true,
      "loc": "net/ipv4/igmp.c:2686",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/udp.c:udp_v4_early_demux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588479728,
      "name": "ip_check_mc_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int ip_check_mc_rcu(struct in_device * in_dev, __be32 mc_addr, __be32 src_addr, u8 proto)
```

```json
{
  "name": "ip_check_mc_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588673488,
      "name": "ip_check_mc_rcu",
      "external": true,
      "loc": "net/ipv4/igmp.c:2702",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/udp.c:udp_v4_early_demux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588673488,
      "name": "ip_check_mc_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int ip_check_mc_rcu(struct in_device * in_dev, __be32 mc_addr, __be32 src_addr, u8 proto)
```

```json
{
  "name": "ip_check_mc_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589086816,
      "name": "ip_check_mc_rcu",
      "external": true,
      "loc": "net/ipv4/igmp.c:2698",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/udp.c:udp_v4_early_demux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589086816,
      "name": "ip_check_mc_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int ip_check_mc_rcu(struct in_device * in_dev, __be32 mc_addr, __be32 src_addr, u8 proto)
```

```json
{
  "name": "ip_check_mc_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589310976,
      "name": "ip_check_mc_rcu",
      "external": true,
      "loc": "net/ipv4/igmp.c:2698",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/udp.c:udp_v4_early_demux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589310976,
      "name": "ip_check_mc_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int ip_check_mc_rcu(struct in_device * in_dev, __be32 mc_addr, __be32 src_addr, u8 proto)
```

```json
{
  "name": "ip_check_mc_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590288176,
      "name": "ip_check_mc_rcu",
      "external": true,
      "loc": "net/ipv4/igmp.c:2688",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__mkroute_output",
        "net/ipv4/udp.c:udp_v4_early_demux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590288176,
      "name": "ip_check_mc_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
int ip_check_mc_rcu(struct in_device * in_dev, __be32 mc_addr, __be32 src_addr, u8 proto)
```

```json
{
  "name": "ip_check_mc_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590341072,
      "name": "ip_check_mc_rcu",
      "external": true,
      "loc": "net/ipv4/igmp.c:2688",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__mkroute_output",
        "net/ipv4/udp.c:udp_v4_early_demux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590341072,
      "name": "ip_check_mc_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
int ip_check_mc_rcu(struct in_device * in_dev, __be32 mc_addr, __be32 src_addr, u8 proto)
```

```json
{
  "name": "ip_check_mc_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590256928,
      "name": "ip_check_mc_rcu",
      "external": true,
      "loc": "net/ipv4/igmp.c:2696",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__mkroute_output",
        "net/ipv4/udp.c:udp_v4_early_demux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590256928,
      "name": "ip_check_mc_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int ip_check_mc_rcu(struct in_device * in_dev, __be32 mc_addr, __be32 src_addr, u8 proto)
```

```json
{
  "name": "ip_check_mc_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591041216,
      "name": "ip_check_mc_rcu",
      "external": true,
      "loc": "net/ipv4/igmp.c:2702",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__mkroute_output",
        "net/ipv4/udp.c:udp_v4_early_demux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591041216,
      "name": "ip_check_mc_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int ip_check_mc_rcu(struct in_device * in_dev, __be32 mc_addr, __be32 src_addr, u8 proto)
```

```json
{
  "name": "ip_check_mc_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592689344,
      "name": "ip_check_mc_rcu",
      "external": true,
      "loc": "net/ipv4/igmp.c:2711",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__mkroute_output",
        "net/ipv4/udp.c:udp_v4_early_demux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592689344,
      "name": "ip_check_mc_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
int ip_check_mc_rcu(struct in_device * in_dev, __be32 mc_addr, __be32 src_addr, u8 proto)
```

```json
{
  "name": "ip_check_mc_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594558288,
      "name": "ip_check_mc_rcu",
      "external": true,
      "loc": "net/ipv4/igmp.c:2715",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__mkroute_output",
        "net/ipv4/udp.c:udp_v4_early_demux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594558288,
      "name": "ip_check_mc_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
int ip_check_mc_rcu(struct in_device * in_dev, __be32 mc_addr, __be32 src_addr, u8 proto)
```

```json
{
  "name": "ip_check_mc_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594950000,
      "name": "ip_check_mc_rcu",
      "external": true,
      "loc": "net/ipv4/igmp.c:2716",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__mkroute_output",
        "net/ipv4/udp.c:udp_v4_early_demux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594950000,
      "name": "ip_check_mc_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
int ip_check_mc_rcu(struct in_device * in_dev, __be32 mc_addr, __be32 src_addr, u8 proto)
```

```json
{
  "name": "ip_check_mc_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595762384,
      "name": "ip_check_mc_rcu",
      "external": true,
      "loc": "net/ipv4/igmp.c:2718",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__mkroute_output",
        "net/ipv4/udp.c:udp_v4_early_demux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595762384,
      "name": "ip_check_mc_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
int ip_check_mc_rcu(struct in_device * in_dev, __be32 mc_addr, __be32 src_addr, u8 proto)
```

```json
{
  "name": "ip_check_mc_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502947208,
      "name": "ip_check_mc_rcu",
      "external": true,
      "loc": "net/ipv4/igmp.c:2698",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/udp.c:udp_v4_early_demux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502947208,
      "name": "ip_check_mc_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
int ip_check_mc_rcu(struct in_device * in_dev, __be32 mc_addr, __be32 src_addr, u8 proto)
```

```json
{
  "name": "ip_check_mc_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235637284,
      "name": "ip_check_mc_rcu",
      "external": true,
      "loc": "net/ipv4/igmp.c:2698",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/udp.c:udp_v4_early_demux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235637284,
      "name": "ip_check_mc_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int ip_check_mc_rcu(struct in_device * in_dev, __be32 mc_addr, __be32 src_addr, u8 proto)
```

```json
{
  "name": "ip_check_mc_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296622368,
      "name": "ip_check_mc_rcu",
      "external": true,
      "loc": "net/ipv4/igmp.c:2698",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/udp.c:udp_v4_early_demux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296622368,
      "name": "ip_check_mc_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
int ip_check_mc_rcu(struct in_device * in_dev, __be32 mc_addr, __be32 src_addr, u8 proto)
```

```json
{
  "name": "ip_check_mc_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279032186,
      "name": "ip_check_mc_rcu",
      "external": true,
      "loc": "net/ipv4/igmp.c:2698",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/udp.c:udp_v4_early_demux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279032186,
      "name": "ip_check_mc_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int ip_check_mc_rcu(struct in_device * in_dev, __be32 mc_addr, __be32 src_addr, u8 proto)
```

```json
{
  "name": "ip_check_mc_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588917152,
      "name": "ip_check_mc_rcu",
      "external": true,
      "loc": "net/ipv4/igmp.c:2698",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/udp.c:udp_v4_early_demux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588917152,
      "name": "ip_check_mc_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int ip_check_mc_rcu(struct in_device * in_dev, __be32 mc_addr, __be32 src_addr, u8 proto)
```

```json
{
  "name": "ip_check_mc_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588629088,
      "name": "ip_check_mc_rcu",
      "external": true,
      "loc": "net/ipv4/igmp.c:2698",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/udp.c:udp_v4_early_demux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588629088,
      "name": "ip_check_mc_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int ip_check_mc_rcu(struct in_device * in_dev, __be32 mc_addr, __be32 src_addr, u8 proto)
```

```json
{
  "name": "ip_check_mc_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589353536,
      "name": "ip_check_mc_rcu",
      "external": true,
      "loc": "net/ipv4/igmp.c:2698",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/udp.c:udp_v4_early_demux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589353536,
      "name": "ip_check_mc_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int ip_check_mc_rcu(struct in_device * in_dev, __be32 mc_addr, __be32 src_addr, u8 proto)
```

```json
{
  "name": "ip_check_mc_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589395984,
      "name": "ip_check_mc_rcu",
      "external": true,
      "loc": "net/ipv4/igmp.c:2698",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/udp.c:udp_v4_early_demux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589395984,
      "name": "ip_check_mc_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
