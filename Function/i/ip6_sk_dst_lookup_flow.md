# Function: <code>ip6_sk_dst_lookup_flow</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dst_entry * ip6_sk_dst_lookup_flow(struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst)
```

```json
{
  "name": "ip6_sk_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586989904,
      "name": "ip6_sk_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1071",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586989904,
      "name": "ip6_sk_dst_lookup_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 467
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
struct dst_entry * ip6_sk_dst_lookup_flow(struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst)
```

```json
{
  "name": "ip6_sk_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587436736,
      "name": "ip6_sk_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1078",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587436736,
      "name": "ip6_sk_dst_lookup_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
struct dst_entry * ip6_sk_dst_lookup_flow(struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst)
```

```json
{
  "name": "ip6_sk_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587640048,
      "name": "ip6_sk_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1105",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587640048,
      "name": "ip6_sk_dst_lookup_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
struct dst_entry * ip6_sk_dst_lookup_flow(struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst)
```

```json
{
  "name": "ip6_sk_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587793760,
      "name": "ip6_sk_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1100",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587793760,
      "name": "ip6_sk_dst_lookup_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
struct dst_entry * ip6_sk_dst_lookup_flow(struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst)
```

```json
{
  "name": "ip6_sk_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588319088,
      "name": "ip6_sk_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1119",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588319088,
      "name": "ip6_sk_dst_lookup_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
struct dst_entry * ip6_sk_dst_lookup_flow(struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst, bool connected)
```

```json
{
  "name": "ip6_sk_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588676160,
      "name": "ip6_sk_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1105",
      "file": "net/ipv6/ip6_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588676160,
      "name": "ip6_sk_dst_lookup_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
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
struct dst_entry * ip6_sk_dst_lookup_flow(struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst, bool connected)
```

```json
{
  "name": "ip6_sk_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588892704,
      "name": "ip6_sk_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1114",
      "file": "net/ipv6/ip6_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588892704,
      "name": "ip6_sk_dst_lookup_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct dst_entry * ip6_sk_dst_lookup_flow(struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst, bool connected)
```

```json
{
  "name": "ip6_sk_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589336492,
      "name": "ip6_sk_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1178",
      "file": "net/ipv6/ip6_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589350774,
      "name": "ip6_sk_dst_lookup_flow.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071589336272,
      "name": "ip6_sk_dst_lookup_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
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
struct dst_entry * ip6_sk_dst_lookup_flow(struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst, bool connected)
```

```json
{
  "name": "ip6_sk_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589561968,
      "name": "ip6_sk_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1181",
      "file": "net/ipv6/ip6_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589561968,
      "name": "ip6_sk_dst_lookup_flow",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct dst_entry * ip6_sk_dst_lookup_flow(struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst, bool connected)
```

```json
{
  "name": "ip6_sk_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590563168,
      "name": "ip6_sk_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1182",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590563168,
      "name": "ip6_sk_dst_lookup_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
struct dst_entry * ip6_sk_dst_lookup_flow(struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst, bool connected)
```

```json
{
  "name": "ip6_sk_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590623088,
      "name": "ip6_sk_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1221",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590623088,
      "name": "ip6_sk_dst_lookup_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
struct dst_entry * ip6_sk_dst_lookup_flow(struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst, bool connected)
```

```json
{
  "name": "ip6_sk_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590547920,
      "name": "ip6_sk_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1252",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590547920,
      "name": "ip6_sk_dst_lookup_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct dst_entry * ip6_sk_dst_lookup_flow(struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst, bool connected)
```

```json
{
  "name": "ip6_sk_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6_sk_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1231",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592735655,
      "name": "ip6_sk_dst_lookup_flow.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071591363392,
      "name": "ip6_sk_dst_lookup_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 441
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct dst_entry * ip6_sk_dst_lookup_flow(struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst, bool connected)
```

```json
{
  "name": "ip6_sk_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6_sk_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1253",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594622155,
      "name": "ip6_sk_dst_lookup_flow.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071593036240,
      "name": "ip6_sk_dst_lookup_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 441
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
struct dst_entry * ip6_sk_dst_lookup_flow(struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst, bool connected)
```

```json
{
  "name": "ip6_sk_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6_sk_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1271",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596356811,
      "name": "ip6_sk_dst_lookup_flow.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071594928080,
      "name": "ip6_sk_dst_lookup_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 441
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct dst_entry * ip6_sk_dst_lookup_flow(struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst, bool connected)
```

```json
{
  "name": "ip6_sk_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6_sk_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1272",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596885611,
      "name": "ip6_sk_dst_lookup_flow.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071595319760,
      "name": "ip6_sk_dst_lookup_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 485
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct dst_entry * ip6_sk_dst_lookup_flow(struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst, bool connected)
```

```json
{
  "name": "ip6_sk_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6_sk_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1281",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597810217,
      "name": "ip6_sk_dst_lookup_flow.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071596161168,
      "name": "ip6_sk_dst_lookup_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 485
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
struct dst_entry * ip6_sk_dst_lookup_flow(struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst, bool connected)
```

```json
{
  "name": "ip6_sk_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503238792,
      "name": "ip6_sk_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1181",
      "file": "net/ipv6/ip6_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503238792,
      "name": "ip6_sk_dst_lookup_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
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
struct dst_entry * ip6_sk_dst_lookup_flow(struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst, bool connected)
```

```json
{
  "name": "ip6_sk_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235906292,
      "name": "ip6_sk_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1181",
      "file": "net/ipv6/ip6_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235906292,
      "name": "ip6_sk_dst_lookup_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 632
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
struct dst_entry * ip6_sk_dst_lookup_flow(struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst, bool connected)
```

```json
{
  "name": "ip6_sk_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296982976,
      "name": "ip6_sk_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1181",
      "file": "net/ipv6/ip6_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296982976,
      "name": "ip6_sk_dst_lookup_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
struct dst_entry * ip6_sk_dst_lookup_flow(struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst, bool connected)
```

```json
{
  "name": "ip6_sk_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279267532,
      "name": "ip6_sk_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1181",
      "file": "net/ipv6/ip6_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279267532,
      "name": "ip6_sk_dst_lookup_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 518
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
struct dst_entry * ip6_sk_dst_lookup_flow(struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst, bool connected)
```

```json
{
  "name": "ip6_sk_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589166336,
      "name": "ip6_sk_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1181",
      "file": "net/ipv6/ip6_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589166336,
      "name": "ip6_sk_dst_lookup_flow",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct dst_entry * ip6_sk_dst_lookup_flow(struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst, bool connected)
```

```json
{
  "name": "ip6_sk_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588891328,
      "name": "ip6_sk_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1181",
      "file": "net/ipv6/ip6_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588891328,
      "name": "ip6_sk_dst_lookup_flow",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct dst_entry * ip6_sk_dst_lookup_flow(struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst, bool connected)
```

```json
{
  "name": "ip6_sk_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589603200,
      "name": "ip6_sk_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1181",
      "file": "net/ipv6/ip6_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589603200,
      "name": "ip6_sk_dst_lookup_flow",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct dst_entry * ip6_sk_dst_lookup_flow(struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst, bool connected)
```

```json
{
  "name": "ip6_sk_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589651472,
      "name": "ip6_sk_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1181",
      "file": "net/ipv6/ip6_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589651472,
      "name": "ip6_sk_dst_lookup_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
<code>bool connected</code>
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
