# Function: <code>__udp6_lib_demux_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__udp6_lib_demux_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587930630,
      "name": "__udp6_lib_demux_lookup",
      "external": false,
      "loc": "net/ipv6/udp.c:903",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__udp6_lib_demux_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588465785,
      "name": "__udp6_lib_demux_lookup",
      "external": false,
      "loc": "net/ipv6/udp.c:906",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__udp6_lib_demux_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588828004,
      "name": "__udp6_lib_demux_lookup",
      "external": false,
      "loc": "net/ipv6/udp.c:883",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__udp6_lib_demux_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589051102,
      "name": "__udp6_lib_demux_lookup",
      "external": false,
      "loc": "net/ipv6/udp.c:963",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__udp6_lib_demux_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589504798,
      "name": "__udp6_lib_demux_lookup",
      "external": false,
      "loc": "net/ipv6/udp.c:950",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__udp6_lib_demux_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589728878,
      "name": "__udp6_lib_demux_lookup",
      "external": false,
      "loc": "net/ipv6/udp.c:950",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct sock * __udp6_lib_demux_lookup(struct net * net, __be16 loc_port, const struct in6_addr * loc_addr, __be16 rmt_port, const struct in6_addr * rmt_addr, int dif, int sdif)
```

```json
{
  "name": "__udp6_lib_demux_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590749344,
      "name": "__udp6_lib_demux_lookup",
      "external": false,
      "loc": "net/ipv6/udp.c:955",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udp_v6_early_demux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590749344,
      "name": "__udp6_lib_demux_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
struct sock * __udp6_lib_demux_lookup(struct net * net, __be16 loc_port, const struct in6_addr * loc_addr, __be16 rmt_port, const struct in6_addr * rmt_addr, int dif, int sdif)
```

```json
{
  "name": "__udp6_lib_demux_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590808480,
      "name": "__udp6_lib_demux_lookup",
      "external": false,
      "loc": "net/ipv6/udp.c:1009",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udp_v6_early_demux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590808480,
      "name": "__udp6_lib_demux_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
  "name": "__udp6_lib_demux_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590735453,
      "name": "__udp6_lib_demux_lookup",
      "external": false,
      "loc": "net/ipv6/udp.c:1022",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__udp6_lib_demux_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591547005,
      "name": "__udp6_lib_demux_lookup",
      "external": false,
      "loc": "net/ipv6/udp.c:1024",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__udp6_lib_demux_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593245691,
      "name": "__udp6_lib_demux_lookup",
      "external": false,
      "loc": "net/ipv6/udp.c:1033",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__udp6_lib_demux_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595146537,
      "name": "__udp6_lib_demux_lookup",
      "external": false,
      "loc": "net/ipv6/udp.c:1063",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__udp6_lib_demux_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595541705,
      "name": "__udp6_lib_demux_lookup",
      "external": false,
      "loc": "net/ipv6/udp.c:1080",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__udp6_lib_demux_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596384473,
      "name": "__udp6_lib_demux_lookup",
      "external": false,
      "loc": "net/ipv6/udp.c:1054",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
  "name": "__udp6_lib_demux_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503411920,
      "name": "__udp6_lib_demux_lookup",
      "external": false,
      "loc": "net/ipv6/udp.c:950",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__udp6_lib_demux_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3236082476,
      "name": "__udp6_lib_demux_lookup",
      "external": false,
      "loc": "net/ipv6/udp.c:950",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__udp6_lib_demux_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055297199460,
      "name": "__udp6_lib_demux_lookup",
      "external": false,
      "loc": "net/ipv6/udp.c:950",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__udp6_lib_demux_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279412740,
      "name": "__udp6_lib_demux_lookup",
      "external": false,
      "loc": "net/ipv6/udp.c:950",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
  "name": "__udp6_lib_demux_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589333246,
      "name": "__udp6_lib_demux_lookup",
      "external": false,
      "loc": "net/ipv6/udp.c:950",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__udp6_lib_demux_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589058238,
      "name": "__udp6_lib_demux_lookup",
      "external": false,
      "loc": "net/ipv6/udp.c:950",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__udp6_lib_demux_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589770110,
      "name": "__udp6_lib_demux_lookup",
      "external": false,
      "loc": "net/ipv6/udp.c:950",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__udp6_lib_demux_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589820814,
      "name": "__udp6_lib_demux_lookup",
      "external": false,
      "loc": "net/ipv6/udp.c:950",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct sock * __udp6_lib_demux_lookup(struct net * net, __be16 loc_port, const struct in6_addr * loc_addr, __be16 rmt_port, const struct in6_addr * rmt_addr, int dif, int sdif)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
struct sock * __udp6_lib_demux_lookup(struct net * net, __be16 loc_port, const struct in6_addr * loc_addr, __be16 rmt_port, const struct in6_addr * rmt_addr, int dif, int sdif)
```
</details>
</li>
</ul>
