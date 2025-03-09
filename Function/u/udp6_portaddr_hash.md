# Function: <code>udp6_portaddr_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
u32 udp6_portaddr_hash(const struct net * net, const struct in6_addr * addr6, unsigned int port)
```

```json
{
  "name": "udp6_portaddr_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587116224,
      "name": "udp6_portaddr_hash",
      "external": false,
      "loc": "net/ipv6/udp.c:107",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udp_v6_get_port",
        "net/ipv6/udp.c:udp_v6_get_port",
        "net/ipv6/udp.c:udp_v6_rehash",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587116224,
      "name": "udp6_portaddr_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
u32 udp6_portaddr_hash(const struct net * net, const struct in6_addr * addr6, unsigned int port)
```

```json
{
  "name": "udp6_portaddr_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587568576,
      "name": "udp6_portaddr_hash",
      "external": false,
      "loc": "net/ipv6/udp.c:81",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:udp_v6_rehash",
        "net/ipv6/udp.c:udp_v6_get_port",
        "net/ipv6/udp.c:udp_v6_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587568576,
      "name": "udp6_portaddr_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
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
u32 udp6_portaddr_hash(const struct net * net, const struct in6_addr * addr6, unsigned int port)
```

```json
{
  "name": "udp6_portaddr_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587772800,
      "name": "udp6_portaddr_hash",
      "external": false,
      "loc": "net/ipv6/udp.c:81",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:udp_v6_rehash",
        "net/ipv6/udp.c:udp_v6_get_port",
        "net/ipv6/udp.c:udp_v6_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587772800,
      "name": "udp6_portaddr_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
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
u32 udp6_portaddr_hash(const struct net * net, const struct in6_addr * addr6, unsigned int port)
```

```json
{
  "name": "udp6_portaddr_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587929072,
      "name": "udp6_portaddr_hash",
      "external": false,
      "loc": "net/ipv6/udp.c:92",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:udp_v6_rehash",
        "net/ipv6/udp.c:udp_v6_get_port",
        "net/ipv6/udp.c:udp_v6_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587929072,
      "name": "udp6_portaddr_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
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
u32 udp6_portaddr_hash(const struct net * net, const struct in6_addr * addr6, unsigned int port)
```

```json
{
  "name": "udp6_portaddr_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588464112,
      "name": "udp6_portaddr_hash",
      "external": false,
      "loc": "net/ipv6/udp.c:92",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:udp_v6_rehash",
        "net/ipv6/udp.c:udp_v6_get_port",
        "net/ipv6/udp.c:udp_v6_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588464112,
      "name": "udp6_portaddr_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    }
  ]
}
```
</details>
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
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
u32 udp6_portaddr_hash(const struct net * net, const struct in6_addr * addr6, unsigned int port)
```
</details>
</li>
</ul>
