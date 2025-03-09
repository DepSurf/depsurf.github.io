# Function: <code>ip6_route_redirect</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dst_entry * ip6_route_redirect(struct net * net, const struct flowi6 * fl6, const struct in6_addr * gateway)
```

```json
{
  "name": "ip6_route_redirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587050704,
      "name": "ip6_route_redirect",
      "external": false,
      "loc": "net/ipv6/route.c:1479",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_redirect",
        "net/ipv6/route.c:ip6_redirect_no_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587050704,
      "name": "ip6_route_redirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
struct dst_entry * ip6_route_redirect(struct net * net, const struct flowi6 * fl6, const struct in6_addr * gateway)
```

```json
{
  "name": "ip6_route_redirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587500032,
      "name": "ip6_route_redirect",
      "external": false,
      "loc": "net/ipv6/route.c:1503",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_redirect_no_header",
        "net/ipv6/route.c:ip6_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587500032,
      "name": "ip6_route_redirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
struct dst_entry * ip6_route_redirect(struct net * net, const struct flowi6 * fl6, const struct in6_addr * gateway)
```

```json
{
  "name": "ip6_route_redirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587704048,
      "name": "ip6_route_redirect",
      "external": false,
      "loc": "net/ipv6/route.c:1515",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_redirect_no_header",
        "net/ipv6/route.c:ip6_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587704048,
      "name": "ip6_route_redirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
struct dst_entry * ip6_route_redirect(struct net * net, const struct flowi6 * fl6, const struct in6_addr * gateway)
```

```json
{
  "name": "ip6_route_redirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587854624,
      "name": "ip6_route_redirect",
      "external": false,
      "loc": "net/ipv6/route.c:1552",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_redirect_no_header",
        "net/ipv6/route.c:ip6_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587854624,
      "name": "ip6_route_redirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
struct dst_entry * ip6_route_redirect(struct net * net, const struct flowi6 * fl6, const struct in6_addr * gateway)
```

```json
{
  "name": "ip6_route_redirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588383680,
      "name": "ip6_route_redirect",
      "external": false,
      "loc": "net/ipv6/route.c:2240",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_redirect_no_header",
        "net/ipv6/route.c:ip6_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588383680,
      "name": "ip6_route_redirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_redirect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588747184,
      "name": "ip6_route_redirect",
      "external": false,
      "loc": "net/ipv6/route.c:2508",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_redirect_no_header",
        "net/ipv6/route.c:ip6_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588747184,
      "name": "ip6_route_redirect.isra.54",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_redirect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588966736,
      "name": "ip6_route_redirect",
      "external": false,
      "loc": "net/ipv6/route.c:2501",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_redirect_no_header",
        "net/ipv6/route.c:ip6_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588966736,
      "name": "ip6_route_redirect.isra.60",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_redirect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589410656,
      "name": "ip6_route_redirect",
      "external": false,
      "loc": "net/ipv6/route.c:2973",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_redirect_no_header",
        "net/ipv6/route.c:ip6_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589410656,
      "name": "ip6_route_redirect.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_redirect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589634896,
      "name": "ip6_route_redirect",
      "external": false,
      "loc": "net/ipv6/route.c:2983",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_redirect_no_header",
        "net/ipv6/route.c:ip6_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589634896,
      "name": "ip6_route_redirect.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_redirect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590645840,
      "name": "ip6_route_redirect",
      "external": false,
      "loc": "net/ipv6/route.c:3007",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_redirect_no_header",
        "net/ipv6/route.c:ip6_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590645840,
      "name": "ip6_route_redirect.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_redirect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590705936,
      "name": "ip6_route_redirect",
      "external": false,
      "loc": "net/ipv6/route.c:2991",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_redirect_no_header",
        "net/ipv6/route.c:ip6_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590705936,
      "name": "ip6_route_redirect.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_redirect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590631200,
      "name": "ip6_route_redirect",
      "external": false,
      "loc": "net/ipv6/route.c:3000",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_redirect_no_header",
        "net/ipv6/route.c:ip6_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590631200,
      "name": "ip6_route_redirect.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_redirect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591444320,
      "name": "ip6_route_redirect",
      "external": false,
      "loc": "net/ipv6/route.c:3130",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_redirect_no_header",
        "net/ipv6/route.c:ip6_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591444320,
      "name": "ip6_route_redirect.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_redirect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593124336,
      "name": "ip6_route_redirect",
      "external": false,
      "loc": "net/ipv6/route.c:3120",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_redirect_no_header",
        "net/ipv6/route.c:ip6_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593124336,
      "name": "ip6_route_redirect.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_redirect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595020432,
      "name": "ip6_route_redirect",
      "external": false,
      "loc": "net/ipv6/route.c:3120",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_redirect_no_header",
        "net/ipv6/route.c:ip6_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595020432,
      "name": "ip6_route_redirect.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_redirect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595413616,
      "name": "ip6_route_redirect",
      "external": false,
      "loc": "net/ipv6/route.c:3120",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_redirect_no_header",
        "net/ipv6/route.c:ip6_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595413616,
      "name": "ip6_route_redirect.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_redirect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596255376,
      "name": "ip6_route_redirect",
      "external": false,
      "loc": "net/ipv6/route.c:3122",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_redirect_no_header",
        "net/ipv6/route.c:ip6_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596255376,
      "name": "ip6_route_redirect.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_redirect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503317656,
      "name": "ip6_route_redirect",
      "external": false,
      "loc": "net/ipv6/route.c:2983",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_redirect_no_header",
        "net/ipv6/route.c:ip6_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503317656,
      "name": "ip6_route_redirect.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
struct dst_entry * ip6_route_redirect(struct net * net, const struct flowi6 * fl6, const struct sk_buff * skb, const struct in6_addr * gateway)
```

```json
{
  "name": "ip6_route_redirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235981572,
      "name": "ip6_route_redirect",
      "external": false,
      "loc": "net/ipv6/route.c:2983",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_redirect_no_header",
        "net/ipv6/route.c:ip6_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235981572,
      "name": "ip6_route_redirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_redirect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297077264,
      "name": "ip6_route_redirect",
      "external": false,
      "loc": "net/ipv6/route.c:2983",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_redirect_no_header",
        "net/ipv6/route.c:ip6_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297077264,
      "name": "ip6_route_redirect.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
struct dst_entry * ip6_route_redirect(struct net * net, const struct flowi6 * fl6, const struct sk_buff * skb, const struct in6_addr * gateway)
```

```json
{
  "name": "ip6_route_redirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279329180,
      "name": "ip6_route_redirect",
      "external": false,
      "loc": "net/ipv6/route.c:2983",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_redirect_no_header",
        "net/ipv6/route.c:ip6_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279329180,
      "name": "ip6_route_redirect",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_redirect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589239264,
      "name": "ip6_route_redirect",
      "external": false,
      "loc": "net/ipv6/route.c:2983",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_redirect_no_header",
        "net/ipv6/route.c:ip6_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589239264,
      "name": "ip6_route_redirect.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_redirect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588964256,
      "name": "ip6_route_redirect",
      "external": false,
      "loc": "net/ipv6/route.c:2983",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_redirect_no_header",
        "net/ipv6/route.c:ip6_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588964256,
      "name": "ip6_route_redirect.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_redirect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589676128,
      "name": "ip6_route_redirect",
      "external": false,
      "loc": "net/ipv6/route.c:2983",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_redirect_no_header",
        "net/ipv6/route.c:ip6_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589676128,
      "name": "ip6_route_redirect.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_redirect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589725264,
      "name": "ip6_route_redirect",
      "external": false,
      "loc": "net/ipv6/route.c:2983",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_redirect_no_header",
        "net/ipv6/route.c:ip6_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589725264,
      "name": "ip6_route_redirect.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
struct dst_entry * ip6_route_redirect(struct net * net, const struct flowi6 * fl6, const struct in6_addr * gateway)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct dst_entry * ip6_route_redirect(struct net * net, const struct flowi6 * fl6, const struct sk_buff * skb, const struct in6_addr * gateway)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
struct dst_entry * ip6_route_redirect(struct net * net, const struct flowi6 * fl6, const struct sk_buff * skb, const struct in6_addr * gateway)
```
</details>
</li>
</ul>
