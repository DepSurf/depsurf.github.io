# Function: <code>inet_select_addr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
__be32 inet_select_addr(const struct net_device * dev, __be32 dst, int scope)
```

```json
{
  "name": "inet_select_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586772160,
      "name": "inet_select_addr",
      "external": true,
      "loc": "net/ipv4/devinet.c:1192",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__ip_route_output_key_hash",
        "net/ipv4/route.c:__ip_route_output_key_hash",
        "net/ipv4/route.c:__ip_route_output_key_hash",
        "net/ipv4/route.c:__ip_route_output_key_hash",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/icmp.c:icmp_send",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586772160,
      "name": "inet_select_addr",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
__be32 inet_select_addr(const struct net_device * dev, __be32 dst, int scope)
```

```json
{
  "name": "inet_select_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587220880,
      "name": "inet_select_addr",
      "external": true,
      "loc": "net/ipv4/devinet.c:1196",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__ip_route_output_key_hash",
        "net/ipv4/route.c:__ip_route_output_key_hash",
        "net/ipv4/route.c:__ip_route_output_key_hash",
        "net/ipv4/route.c:__ip_route_output_key_hash",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/icmp.c:icmp_send",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_select_path",
        "net/ipv4/fib_semantics.c:fib_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587220880,
      "name": "inet_select_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
__be32 inet_select_addr(const struct net_device * dev, __be32 dst, int scope)
```

```json
{
  "name": "inet_select_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587421424,
      "name": "inet_select_addr",
      "external": true,
      "loc": "net/ipv4/devinet.c:1196",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__ip_route_output_key_hash",
        "net/ipv4/route.c:__ip_route_output_key_hash",
        "net/ipv4/route.c:__ip_route_output_key_hash",
        "net/ipv4/route.c:__ip_route_output_key_hash",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/icmp.c:icmp_send",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_select_path",
        "net/ipv4/fib_semantics.c:fib_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587421424,
      "name": "inet_select_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
__be32 inet_select_addr(const struct net_device * dev, __be32 dst, int scope)
```

```json
{
  "name": "inet_select_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587559312,
      "name": "inet_select_addr",
      "external": true,
      "loc": "net/ipv4/devinet.c:1231",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/icmp.c:icmp_send",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_select_path",
        "net/ipv4/fib_semantics.c:fib_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587559312,
      "name": "inet_select_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
__be32 inet_select_addr(const struct net_device * dev, __be32 dst, int scope)
```

```json
{
  "name": "inet_select_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588082624,
      "name": "inet_select_addr",
      "external": true,
      "loc": "net/ipv4/devinet.c:1239",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/icmp.c:icmp_send",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_select_path",
        "net/ipv4/fib_semantics.c:fib_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588082624,
      "name": "inet_select_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
__be32 inet_select_addr(const struct net_device * dev, __be32 dst, int scope)
```

```json
{
  "name": "inet_select_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588434496,
      "name": "inet_select_addr",
      "external": true,
      "loc": "net/ipv4/devinet.c:1246",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/icmp.c:icmp_send",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_select_path",
        "net/ipv4/fib_semantics.c:fib_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588434496,
      "name": "inet_select_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
__be32 inet_select_addr(const struct net_device * dev, __be32 dst, int scope)
```

```json
{
  "name": "inet_select_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588626512,
      "name": "inet_select_addr",
      "external": true,
      "loc": "net/ipv4/devinet.c:1258",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_select_path",
        "net/ipv4/fib_semantics.c:fib_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588626512,
      "name": "inet_select_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
__be32 inet_select_addr(const struct net_device * dev, __be32 dst, int scope)
```

```json
{
  "name": "inet_select_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589040000,
      "name": "inet_select_addr",
      "external": true,
      "loc": "net/ipv4/devinet.c:1295",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589040000,
      "name": "inet_select_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
__be32 inet_select_addr(const struct net_device * dev, __be32 dst, int scope)
```

```json
{
  "name": "inet_select_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589264512,
      "name": "inet_select_addr",
      "external": true,
      "loc": "net/ipv4/devinet.c:1295",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589264512,
      "name": "inet_select_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
__be32 inet_select_addr(const struct net_device * dev, __be32 dst, int scope)
```

```json
{
  "name": "inet_select_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590240448,
      "name": "inet_select_addr",
      "external": true,
      "loc": "net/ipv4/devinet.c:1301",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_result_prefsrc",
        "net/ipv4/fib_semantics.c:fib_result_prefsrc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590240448,
      "name": "inet_select_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
__be32 inet_select_addr(const struct net_device * dev, __be32 dst, int scope)
```

```json
{
  "name": "inet_select_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590293232,
      "name": "inet_select_addr",
      "external": true,
      "loc": "net/ipv4/devinet.c:1300",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_result_prefsrc",
        "net/ipv4/fib_semantics.c:fib_result_prefsrc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590293232,
      "name": "inet_select_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
__be32 inet_select_addr(const struct net_device * dev, __be32 dst, int scope)
```

```json
{
  "name": "inet_select_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590209120,
      "name": "inet_select_addr",
      "external": true,
      "loc": "net/ipv4/devinet.c:1300",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_result_prefsrc",
        "net/ipv4/fib_semantics.c:fib_result_prefsrc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590209120,
      "name": "inet_select_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
__be32 inet_select_addr(const struct net_device * dev, __be32 dst, int scope)
```

```json
{
  "name": "inet_select_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590990752,
      "name": "inet_select_addr",
      "external": true,
      "loc": "net/ipv4/devinet.c:1300",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_result_prefsrc",
        "net/ipv4/fib_semantics.c:fib_result_prefsrc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590990752,
      "name": "inet_select_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
__be32 inet_select_addr(const struct net_device * dev, __be32 dst, int scope)
```

```json
{
  "name": "inet_select_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592636496,
      "name": "inet_select_addr",
      "external": true,
      "loc": "net/ipv4/devinet.c:1304",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_result_prefsrc",
        "net/ipv4/fib_semantics.c:fib_result_prefsrc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592636496,
      "name": "inet_select_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
__be32 inet_select_addr(const struct net_device * dev, __be32 dst, int scope)
```

```json
{
  "name": "inet_select_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594502544,
      "name": "inet_select_addr",
      "external": true,
      "loc": "net/ipv4/devinet.c:1305",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_result_prefsrc",
        "net/ipv4/fib_semantics.c:fib_result_prefsrc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594502544,
      "name": "inet_select_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
__be32 inet_select_addr(const struct net_device * dev, __be32 dst, int scope)
```

```json
{
  "name": "inet_select_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594894160,
      "name": "inet_select_addr",
      "external": true,
      "loc": "net/ipv4/devinet.c:1308",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_result_prefsrc",
        "net/ipv4/fib_semantics.c:fib_result_prefsrc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594894160,
      "name": "inet_select_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
__be32 inet_select_addr(const struct net_device * dev, __be32 dst, int scope)
```

```json
{
  "name": "inet_select_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595705472,
      "name": "inet_select_addr",
      "external": true,
      "loc": "net/ipv4/devinet.c:1325",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_result_prefsrc",
        "net/ipv4/fib_semantics.c:fib_result_prefsrc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595705472,
      "name": "inet_select_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
__be32 inet_select_addr(const struct net_device * dev, __be32 dst, int scope)
```

```json
{
  "name": "inet_select_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502893216,
      "name": "inet_select_addr",
      "external": true,
      "loc": "net/ipv4/devinet.c:1295",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502893216,
      "name": "inet_select_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
__be32 inet_select_addr(const struct net_device * dev, __be32 dst, int scope)
```

```json
{
  "name": "inet_select_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235587188,
      "name": "inet_select_addr",
      "external": true,
      "loc": "net/ipv4/devinet.c:1295",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235587188,
      "name": "inet_select_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
__be32 inet_select_addr(const struct net_device * dev, __be32 dst, int scope)
```

```json
{
  "name": "inet_select_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296555744,
      "name": "inet_select_addr",
      "external": true,
      "loc": "net/ipv4/devinet.c:1295",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296555744,
      "name": "inet_select_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
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
__be32 inet_select_addr(const struct net_device * dev, __be32 dst, int scope)
```

```json
{
  "name": "inet_select_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278991662,
      "name": "inet_select_addr",
      "external": true,
      "loc": "net/ipv4/devinet.c:1295",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278991662,
      "name": "inet_select_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
__be32 inet_select_addr(const struct net_device * dev, __be32 dst, int scope)
```

```json
{
  "name": "inet_select_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588870688,
      "name": "inet_select_addr",
      "external": true,
      "loc": "net/ipv4/devinet.c:1295",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588870688,
      "name": "inet_select_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
__be32 inet_select_addr(const struct net_device * dev, __be32 dst, int scope)
```

```json
{
  "name": "inet_select_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588582624,
      "name": "inet_select_addr",
      "external": true,
      "loc": "net/ipv4/devinet.c:1295",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588582624,
      "name": "inet_select_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
__be32 inet_select_addr(const struct net_device * dev, __be32 dst, int scope)
```

```json
{
  "name": "inet_select_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589307072,
      "name": "inet_select_addr",
      "external": true,
      "loc": "net/ipv4/devinet.c:1295",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589307072,
      "name": "inet_select_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
__be32 inet_select_addr(const struct net_device * dev, __be32 dst, int scope)
```

```json
{
  "name": "inet_select_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589348832,
      "name": "inet_select_addr",
      "external": true,
      "loc": "net/ipv4/devinet.c:1295",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_rt_get_source",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/fib_frontend.c:fib_compute_spec_dst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589348832,
      "name": "inet_select_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
