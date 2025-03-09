# Function: <code>modify_prefix_route</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "modify_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588729723,
      "name": "modify_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4528",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_rtm_newaddr"
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
  "name": "modify_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588949613,
      "name": "modify_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4550",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_rtm_newaddr"
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
  "name": "modify_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589387830,
      "name": "modify_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4588",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_addr_modify"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int modify_prefix_route(struct inet6_ifaddr * ifp, long unsigned int expires, u32 flags, bool modify_peer)
```

```json
{
  "name": "modify_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589591456,
      "name": "modify_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4594",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589591456,
      "name": "modify_prefix_route",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
int modify_prefix_route(struct inet6_ifaddr * ifp, long unsigned int expires, u32 flags, bool modify_peer)
```

```json
{
  "name": "modify_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590594192,
      "name": "modify_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4611",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590594192,
      "name": "modify_prefix_route",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
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
int modify_prefix_route(struct inet6_ifaddr * ifp, long unsigned int expires, u32 flags, bool modify_peer)
```

```json
{
  "name": "modify_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590654304,
      "name": "modify_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4638",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590654304,
      "name": "modify_prefix_route",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
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
int modify_prefix_route(struct inet6_ifaddr * ifp, long unsigned int expires, u32 flags, bool modify_peer)
```

```json
{
  "name": "modify_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590579840,
      "name": "modify_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4642",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590579840,
      "name": "modify_prefix_route",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
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
int modify_prefix_route(struct inet6_ifaddr * ifp, long unsigned int expires, u32 flags, bool modify_peer)
```

```json
{
  "name": "modify_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591392160,
      "name": "modify_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4678",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591392160,
      "name": "modify_prefix_route",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
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
int modify_prefix_route(struct inet6_ifaddr * ifp, long unsigned int expires, u32 flags, bool modify_peer)
```

```json
{
  "name": "modify_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593069104,
      "name": "modify_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4685",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593069104,
      "name": "modify_prefix_route",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
int modify_prefix_route(struct inet6_ifaddr * ifp, long unsigned int expires, u32 flags, bool modify_peer)
```

```json
{
  "name": "modify_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594963264,
      "name": "modify_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4698",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594963264,
      "name": "modify_prefix_route",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
int modify_prefix_route(struct inet6_ifaddr * ifp, long unsigned int expires, u32 flags, bool modify_peer)
```

```json
{
  "name": "modify_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595355376,
      "name": "modify_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4704",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595355376,
      "name": "modify_prefix_route",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
int modify_prefix_route(struct inet6_ifaddr * ifp, long unsigned int expires, u32 flags, bool modify_peer)
```

```json
{
  "name": "modify_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596196224,
      "name": "modify_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4755",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596196224,
      "name": "modify_prefix_route",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
int modify_prefix_route(struct inet6_ifaddr * ifp, long unsigned int expires, u32 flags, bool modify_peer)
```

```json
{
  "name": "modify_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503262072,
      "name": "modify_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4594",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503262072,
      "name": "modify_prefix_route",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
int modify_prefix_route(struct inet6_ifaddr * ifp, long unsigned int expires, u32 flags, bool modify_peer)
```

```json
{
  "name": "modify_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235938548,
      "name": "modify_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4594",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235938548,
      "name": "modify_prefix_route",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
int modify_prefix_route(struct inet6_ifaddr * ifp, long unsigned int expires, u32 flags, bool modify_peer)
```

```json
{
  "name": "modify_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297014976,
      "name": "modify_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4594",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297014976,
      "name": "modify_prefix_route",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
int modify_prefix_route(struct inet6_ifaddr * ifp, long unsigned int expires, u32 flags, bool modify_peer)
```

```json
{
  "name": "modify_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279285846,
      "name": "modify_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4594",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279285846,
      "name": "modify_prefix_route",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
int modify_prefix_route(struct inet6_ifaddr * ifp, long unsigned int expires, u32 flags, bool modify_peer)
```

```json
{
  "name": "modify_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589195824,
      "name": "modify_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4594",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589195824,
      "name": "modify_prefix_route",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
int modify_prefix_route(struct inet6_ifaddr * ifp, long unsigned int expires, u32 flags, bool modify_peer)
```

```json
{
  "name": "modify_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588920816,
      "name": "modify_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4594",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588920816,
      "name": "modify_prefix_route",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
int modify_prefix_route(struct inet6_ifaddr * ifp, long unsigned int expires, u32 flags, bool modify_peer)
```

```json
{
  "name": "modify_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589632688,
      "name": "modify_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4594",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589632688,
      "name": "modify_prefix_route",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
int modify_prefix_route(struct inet6_ifaddr * ifp, long unsigned int expires, u32 flags, bool modify_peer)
```

```json
{
  "name": "modify_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589681648,
      "name": "modify_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4594",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589681648,
      "name": "modify_prefix_route",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int modify_prefix_route(struct inet6_ifaddr * ifp, long unsigned int expires, u32 flags, bool modify_peer)
```
</details>
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
