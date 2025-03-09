# Function: <code>dst_cache_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void dst_cache_destroy(struct dst_cache * dst_cache)
```

```json
{
  "name": "dst_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586885024,
      "name": "dst_cache_destroy",
      "external": true,
      "loc": "net/core/dst_cache.c:156",
      "file": "net/core/dst_cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586885024,
      "name": "dst_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void dst_cache_destroy(struct dst_cache * dst_cache)
```

```json
{
  "name": "dst_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587079104,
      "name": "dst_cache_destroy",
      "external": true,
      "loc": "net/core/dst_cache.c:156",
      "file": "net/core/dst_cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv6/seg6_iptunnel.c:seg6_destroy_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587079104,
      "name": "dst_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void dst_cache_destroy(struct dst_cache * dst_cache)
```

```json
{
  "name": "dst_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587206704,
      "name": "dst_cache_destroy",
      "external": true,
      "loc": "net/core/dst_cache.c:156",
      "file": "net/core/dst_cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv6/seg6_iptunnel.c:seg6_destroy_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587206704,
      "name": "dst_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void dst_cache_destroy(struct dst_cache * dst_cache)
```

```json
{
  "name": "dst_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587721040,
      "name": "dst_cache_destroy",
      "external": true,
      "loc": "net/core/dst_cache.c:156",
      "file": "net/core/dst_cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:metadata_dst_free_percpu",
        "net/core/dst.c:metadata_dst_free",
        "net/ipv6/seg6_iptunnel.c:seg6_destroy_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587721040,
      "name": "dst_cache_destroy",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dst_cache_destroy(struct dst_cache * dst_cache)
```

```json
{
  "name": "dst_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588054640,
      "name": "dst_cache_destroy",
      "external": true,
      "loc": "net/core/dst_cache.c:156",
      "file": "net/core/dst_cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:metadata_dst_free_percpu",
        "net/core/dst.c:metadata_dst_free",
        "net/ipv6/seg6_iptunnel.c:seg6_destroy_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588054640,
      "name": "dst_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void dst_cache_destroy(struct dst_cache * dst_cache)
```

```json
{
  "name": "dst_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588230560,
      "name": "dst_cache_destroy",
      "external": true,
      "loc": "net/core/dst_cache.c:156",
      "file": "net/core/dst_cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:metadata_dst_free_percpu",
        "net/core/dst.c:metadata_dst_free",
        "net/ipv6/seg6_iptunnel.c:seg6_destroy_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588230560,
      "name": "dst_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void dst_cache_destroy(struct dst_cache * dst_cache)
```

```json
{
  "name": "dst_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588567600,
      "name": "dst_cache_destroy",
      "external": true,
      "loc": "net/core/dst_cache.c:152",
      "file": "net/core/dst_cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:metadata_dst_free_percpu",
        "net/core/dst.c:metadata_dst_free",
        "net/ipv4/ip_tunnel_core.c:ip_tun_destroy_state",
        "net/ipv6/seg6_iptunnel.c:seg6_destroy_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588567600,
      "name": "dst_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void dst_cache_destroy(struct dst_cache * dst_cache)
```

```json
{
  "name": "dst_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588784720,
      "name": "dst_cache_destroy",
      "external": true,
      "loc": "net/core/dst_cache.c:152",
      "file": "net/core/dst_cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:metadata_dst_free_percpu",
        "net/core/dst.c:metadata_dst_free",
        "net/ipv4/ip_tunnel_core.c:ip_tun_destroy_state",
        "net/ipv6/seg6_iptunnel.c:seg6_destroy_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588784720,
      "name": "dst_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void dst_cache_destroy(struct dst_cache * dst_cache)
```

```json
{
  "name": "dst_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589658384,
      "name": "dst_cache_destroy",
      "external": true,
      "loc": "net/core/dst_cache.c:152",
      "file": "net/core/dst_cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:metadata_dst_free_percpu",
        "net/core/dst.c:dst_destroy",
        "net/ipv4/ip_tunnel_core.c:ip_tun_destroy_state",
        "net/ipv6/seg6_iptunnel.c:seg6_destroy_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589658384,
      "name": "dst_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void dst_cache_destroy(struct dst_cache * dst_cache)
```

```json
{
  "name": "dst_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589683024,
      "name": "dst_cache_destroy",
      "external": true,
      "loc": "net/core/dst_cache.c:152",
      "file": "net/core/dst_cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:metadata_dst_free_percpu",
        "net/core/dst.c:dst_destroy",
        "net/ipv4/ip_tunnel_core.c:ip_tun_destroy_state",
        "net/ipv6/seg6_iptunnel.c:seg6_destroy_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589683024,
      "name": "dst_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void dst_cache_destroy(struct dst_cache * dst_cache)
```

```json
{
  "name": "dst_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589564256,
      "name": "dst_cache_destroy",
      "external": true,
      "loc": "net/core/dst_cache.c:152",
      "file": "net/core/dst_cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:metadata_dst_free_percpu",
        "net/core/dst.c:dst_destroy",
        "net/ipv4/ip_tunnel_core.c:ip_tun_destroy_state",
        "net/ipv6/seg6_iptunnel.c:seg6_destroy_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589564256,
      "name": "dst_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void dst_cache_destroy(struct dst_cache * dst_cache)
```

```json
{
  "name": "dst_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590309664,
      "name": "dst_cache_destroy",
      "external": true,
      "loc": "net/core/dst_cache.c:152",
      "file": "net/core/dst_cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:metadata_dst_free_percpu",
        "net/core/dst.c:dst_destroy",
        "net/ipv4/ip_tunnel_core.c:ip_tun_destroy_state",
        "net/ipv6/seg6_iptunnel.c:seg6_destroy_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590309664,
      "name": "dst_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void dst_cache_destroy(struct dst_cache * dst_cache)
```

```json
{
  "name": "dst_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591894736,
      "name": "dst_cache_destroy",
      "external": true,
      "loc": "net/core/dst_cache.c:152",
      "file": "net/core/dst_cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:metadata_dst_free_percpu",
        "net/core/dst.c:dst_destroy",
        "net/ipv4/ip_tunnel_core.c:ip_tun_destroy_state",
        "net/ipv6/seg6_iptunnel.c:seg6_destroy_state",
        "net/ipv6/ioam6_iptunnel.c:ioam6_destroy_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591894736,
      "name": "dst_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void dst_cache_destroy(struct dst_cache * dst_cache)
```

```json
{
  "name": "dst_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593697296,
      "name": "dst_cache_destroy",
      "external": true,
      "loc": "net/core/dst_cache.c:152",
      "file": "net/core/dst_cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:metadata_dst_free_percpu",
        "net/core/dst.c:dst_destroy",
        "net/ipv4/ip_tunnel_core.c:ip_tun_destroy_state",
        "net/ipv6/seg6_iptunnel.c:seg6_destroy_state",
        "net/ipv6/ioam6_iptunnel.c:ioam6_destroy_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593697296,
      "name": "dst_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void dst_cache_destroy(struct dst_cache * dst_cache)
```

```json
{
  "name": "dst_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594178176,
      "name": "dst_cache_destroy",
      "external": true,
      "loc": "net/core/dst_cache.c:152",
      "file": "net/core/dst_cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:metadata_dst_free_percpu",
        "net/core/dst.c:dst_destroy",
        "net/ipv4/ip_tunnel_core.c:ip_tun_destroy_state",
        "net/ipv6/seg6_iptunnel.c:seg6_destroy_state",
        "net/ipv6/ioam6_iptunnel.c:ioam6_destroy_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594178176,
      "name": "dst_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void dst_cache_destroy(struct dst_cache * dst_cache)
```

```json
{
  "name": "dst_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594974704,
      "name": "dst_cache_destroy",
      "external": true,
      "loc": "net/core/dst_cache.c:152",
      "file": "net/core/dst_cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:metadata_dst_free_percpu",
        "net/core/dst.c:dst_destroy",
        "net/ipv4/ip_tunnel_core.c:ip_tun_destroy_state",
        "net/ipv6/seg6_iptunnel.c:seg6_destroy_state",
        "net/ipv6/ioam6_iptunnel.c:ioam6_destroy_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594974704,
      "name": "dst_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void dst_cache_destroy(struct dst_cache * dst_cache)
```

```json
{
  "name": "dst_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502353752,
      "name": "dst_cache_destroy",
      "external": true,
      "loc": "net/core/dst_cache.c:152",
      "file": "net/core/dst_cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:metadata_dst_free_percpu",
        "net/core/dst.c:metadata_dst_free",
        "net/ipv4/ip_tunnel_core.c:ip_tun_destroy_state",
        "net/ipv6/seg6_iptunnel.c:seg6_destroy_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502353752,
      "name": "dst_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void dst_cache_destroy(struct dst_cache * dst_cache)
```

```json
{
  "name": "dst_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235091256,
      "name": "dst_cache_destroy",
      "external": true,
      "loc": "net/core/dst_cache.c:152",
      "file": "net/core/dst_cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:metadata_dst_free_percpu",
        "net/core/dst.c:metadata_dst_free",
        "net/ipv4/ip_tunnel_core.c:ip_tun_destroy_state",
        "net/ipv6/seg6_iptunnel.c:seg6_destroy_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235091256,
      "name": "dst_cache_destroy",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void dst_cache_destroy(struct dst_cache * dst_cache)
```

```json
{
  "name": "dst_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295878496,
      "name": "dst_cache_destroy",
      "external": true,
      "loc": "net/core/dst_cache.c:152",
      "file": "net/core/dst_cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:metadata_dst_free_percpu",
        "net/core/dst.c:metadata_dst_free",
        "net/ipv4/ip_tunnel_core.c:ip_tun_destroy_state",
        "net/ipv6/seg6_iptunnel.c:seg6_destroy_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295878496,
      "name": "dst_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void dst_cache_destroy(struct dst_cache * dst_cache)
```

```json
{
  "name": "dst_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278572036,
      "name": "dst_cache_destroy",
      "external": true,
      "loc": "net/core/dst_cache.c:152",
      "file": "net/core/dst_cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:metadata_dst_free_percpu",
        "net/core/dst.c:metadata_dst_free",
        "net/ipv4/ip_tunnel_core.c:ip_tun_destroy_state",
        "net/ipv6/seg6_iptunnel.c:seg6_destroy_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278572036,
      "name": "dst_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void dst_cache_destroy(struct dst_cache * dst_cache)
```

```json
{
  "name": "dst_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588391104,
      "name": "dst_cache_destroy",
      "external": true,
      "loc": "net/core/dst_cache.c:152",
      "file": "net/core/dst_cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:metadata_dst_free_percpu",
        "net/core/dst.c:metadata_dst_free",
        "net/ipv4/ip_tunnel_core.c:ip_tun_destroy_state",
        "net/ipv6/seg6_iptunnel.c:seg6_destroy_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588391104,
      "name": "dst_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void dst_cache_destroy(struct dst_cache * dst_cache)
```

```json
{
  "name": "dst_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588103792,
      "name": "dst_cache_destroy",
      "external": true,
      "loc": "net/core/dst_cache.c:152",
      "file": "net/core/dst_cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/vxlan.c:vxlan_dst_free",
        "drivers/net/vxlan.c:__vxlan_fdb_free",
        "net/core/dst.c:metadata_dst_free_percpu",
        "net/core/dst.c:metadata_dst_free",
        "net/ipv4/ip_tunnel_core.c:ip_tun_destroy_state",
        "net/ipv4/ip_tunnel.c:ip_tunnel_init",
        "net/ipv4/ip_tunnel.c:ip_tunnel_dev_free",
        "net/ipv6/seg6_iptunnel.c:seg6_destroy_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588103792,
      "name": "dst_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void dst_cache_destroy(struct dst_cache * dst_cache)
```

```json
{
  "name": "dst_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588723280,
      "name": "dst_cache_destroy",
      "external": true,
      "loc": "net/core/dst_cache.c:152",
      "file": "net/core/dst_cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:metadata_dst_free_percpu",
        "net/core/dst.c:metadata_dst_free",
        "net/ipv4/ip_tunnel_core.c:ip_tun_destroy_state",
        "net/ipv6/seg6_iptunnel.c:seg6_destroy_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588723280,
      "name": "dst_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void dst_cache_destroy(struct dst_cache * dst_cache)
```

```json
{
  "name": "dst_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588863696,
      "name": "dst_cache_destroy",
      "external": true,
      "loc": "net/core/dst_cache.c:152",
      "file": "net/core/dst_cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:metadata_dst_free_percpu",
        "net/core/dst.c:metadata_dst_free",
        "net/ipv4/ip_tunnel_core.c:ip_tun_destroy_state",
        "net/ipv6/seg6_iptunnel.c:seg6_destroy_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588863696,
      "name": "dst_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void dst_cache_destroy(struct dst_cache * dst_cache)
```
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
