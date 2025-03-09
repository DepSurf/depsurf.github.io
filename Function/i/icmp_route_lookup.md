# Function: <code>icmp_route_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct rtable * icmp_route_lookup(struct net * net, struct flowi4 * fl4, struct sk_buff * skb_in, const struct iphdr * iph, __be32 saddr, u8 tos, u32 mark, int type, int code, struct icmp_bxm * param)
```

```json
{
  "name": "icmp_route_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586767168,
      "name": "icmp_route_lookup",
      "external": false,
      "loc": "net/ipv4/icmp.c:459",
      "file": "net/ipv4/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/icmp.c:icmp_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586767168,
      "name": "icmp_route_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 876
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
struct rtable * icmp_route_lookup(struct net * net, struct flowi4 * fl4, struct sk_buff * skb_in, const struct iphdr * iph, __be32 saddr, u8 tos, u32 mark, int type, int code, struct icmp_bxm * param)
```

```json
{
  "name": "icmp_route_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587215152,
      "name": "icmp_route_lookup",
      "external": false,
      "loc": "net/ipv4/icmp.c:459",
      "file": "net/ipv4/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/icmp.c:icmp_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587215152,
      "name": "icmp_route_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 871
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
struct rtable * icmp_route_lookup(struct net * net, struct flowi4 * fl4, struct sk_buff * skb_in, const struct iphdr * iph, __be32 saddr, u8 tos, u32 mark, int type, int code, struct icmp_bxm * param)
```

```json
{
  "name": "icmp_route_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587415536,
      "name": "icmp_route_lookup",
      "external": false,
      "loc": "net/ipv4/icmp.c:460",
      "file": "net/ipv4/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/icmp.c:icmp_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587415536,
      "name": "icmp_route_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1011
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "icmp_route_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587551856,
      "name": "icmp_route_lookup",
      "external": false,
      "loc": "net/ipv4/icmp.c:467",
      "file": "net/ipv4/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/icmp.c:icmp_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587551856,
      "name": "icmp_route_lookup.constprop.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 921
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "icmp_route_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588075392,
      "name": "icmp_route_lookup",
      "external": false,
      "loc": "net/ipv4/icmp.c:467",
      "file": "net/ipv4/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/icmp.c:icmp_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588075392,
      "name": "icmp_route_lookup.constprop.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 942
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
  "name": "icmp_route_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588428640,
      "name": "icmp_route_lookup",
      "external": false,
      "loc": "net/ipv4/icmp.c:467",
      "file": "net/ipv4/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/icmp.c:icmp_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588428640,
      "name": "icmp_route_lookup.constprop.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 899
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
  "name": "icmp_route_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588620624,
      "name": "icmp_route_lookup",
      "external": false,
      "loc": "net/ipv4/icmp.c:464",
      "file": "net/ipv4/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/icmp.c:__icmp_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588620624,
      "name": "icmp_route_lookup.constprop.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 879
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
  "name": "icmp_route_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589032368,
      "name": "icmp_route_lookup",
      "external": false,
      "loc": "net/ipv4/icmp.c:459",
      "file": "net/ipv4/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/icmp.c:__icmp_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589032368,
      "name": "icmp_route_lookup.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 889
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
  "name": "icmp_route_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589256880,
      "name": "icmp_route_lookup",
      "external": false,
      "loc": "net/ipv4/icmp.c:460",
      "file": "net/ipv4/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/icmp.c:__icmp_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589256880,
      "name": "icmp_route_lookup.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 889
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
  "name": "icmp_route_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590231184,
      "name": "icmp_route_lookup",
      "external": false,
      "loc": "net/ipv4/icmp.c:460",
      "file": "net/ipv4/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/icmp.c:__icmp_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590231184,
      "name": "icmp_route_lookup.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 856
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
  "name": "icmp_route_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590283120,
      "name": "icmp_route_lookup",
      "external": false,
      "loc": "net/ipv4/icmp.c:480",
      "file": "net/ipv4/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/icmp.c:__icmp_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590283120,
      "name": "icmp_route_lookup.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 980
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
  "name": "icmp_route_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590197776,
      "name": "icmp_route_lookup",
      "external": false,
      "loc": "net/ipv4/icmp.c:480",
      "file": "net/ipv4/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/icmp.c:__icmp_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590197776,
      "name": "icmp_route_lookup.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1007
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
  "name": "icmp_route_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590979280,
      "name": "icmp_route_lookup",
      "external": false,
      "loc": "net/ipv4/icmp.c:480",
      "file": "net/ipv4/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/icmp.c:__icmp_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590979280,
      "name": "icmp_route_lookup.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1048
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
  "name": "icmp_route_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592623376,
      "name": "icmp_route_lookup",
      "external": false,
      "loc": "net/ipv4/icmp.c:473",
      "file": "net/ipv4/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/icmp.c:__icmp_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592623376,
      "name": "icmp_route_lookup.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1068
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
  "name": "icmp_route_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594488736,
      "name": "icmp_route_lookup",
      "external": false,
      "loc": "net/ipv4/icmp.c:473",
      "file": "net/ipv4/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/icmp.c:__icmp_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594488736,
      "name": "icmp_route_lookup.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1068
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
  "name": "icmp_route_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594880192,
      "name": "icmp_route_lookup",
      "external": false,
      "loc": "net/ipv4/icmp.c:476",
      "file": "net/ipv4/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/icmp.c:__icmp_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594880192,
      "name": "icmp_route_lookup.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1081
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
  "name": "icmp_route_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595691472,
      "name": "icmp_route_lookup",
      "external": false,
      "loc": "net/ipv4/icmp.c:476",
      "file": "net/ipv4/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/icmp.c:__icmp_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595691472,
      "name": "icmp_route_lookup.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1075
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
  "name": "icmp_route_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502884944,
      "name": "icmp_route_lookup",
      "external": false,
      "loc": "net/ipv4/icmp.c:460",
      "file": "net/ipv4/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/icmp.c:__icmp_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502884944,
      "name": "icmp_route_lookup.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 880
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "icmp_route_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235579616,
      "name": "icmp_route_lookup",
      "external": false,
      "loc": "net/ipv4/icmp.c:460",
      "file": "net/ipv4/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/icmp.c:__icmp_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235579616,
      "name": "icmp_route_lookup.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 856
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
  "name": "icmp_route_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296545648,
      "name": "icmp_route_lookup",
      "external": false,
      "loc": "net/ipv4/icmp.c:460",
      "file": "net/ipv4/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/icmp.c:__icmp_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296545648,
      "name": "icmp_route_lookup.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "icmp_route_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278985064,
      "name": "icmp_route_lookup",
      "external": false,
      "loc": "net/ipv4/icmp.c:460",
      "file": "net/ipv4/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/icmp.c:__icmp_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278985064,
      "name": "icmp_route_lookup.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 684
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
  "name": "icmp_route_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588863056,
      "name": "icmp_route_lookup",
      "external": false,
      "loc": "net/ipv4/icmp.c:460",
      "file": "net/ipv4/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/icmp.c:__icmp_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588863056,
      "name": "icmp_route_lookup.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 889
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
  "name": "icmp_route_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588574992,
      "name": "icmp_route_lookup",
      "external": false,
      "loc": "net/ipv4/icmp.c:460",
      "file": "net/ipv4/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/icmp.c:__icmp_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588574992,
      "name": "icmp_route_lookup.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 889
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
  "name": "icmp_route_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589299440,
      "name": "icmp_route_lookup",
      "external": false,
      "loc": "net/ipv4/icmp.c:460",
      "file": "net/ipv4/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/icmp.c:__icmp_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589299440,
      "name": "icmp_route_lookup.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 889
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
  "name": "icmp_route_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589341200,
      "name": "icmp_route_lookup",
      "external": false,
      "loc": "net/ipv4/icmp.c:460",
      "file": "net/ipv4/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/icmp.c:__icmp_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589341200,
      "name": "icmp_route_lookup.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 967
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
struct rtable * icmp_route_lookup(struct net * net, struct flowi4 * fl4, struct sk_buff * skb_in, const struct iphdr * iph, __be32 saddr, u8 tos, u32 mark, int type, int code, struct icmp_bxm * param)
```
</details>
</li>
</ul>
