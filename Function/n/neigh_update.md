# Function: <code>neigh_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int neigh_update(struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags)
```

```json
{
  "name": "neigh_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586350608,
      "name": "neigh_update",
      "external": true,
      "loc": "net/core/neighbour.c:1075",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_event_ns",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_rcv",
        "net/ipv6/ndisc.c:ndisc_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586350608,
      "name": "neigh_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1895
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
int neigh_update(struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags)
```

```json
{
  "name": "neigh_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586783600,
      "name": "neigh_update",
      "external": true,
      "loc": "net/core/neighbour.c:1073",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_event_ns",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ndisc.c:ndisc_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586783600,
      "name": "neigh_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1765
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
int neigh_update(struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags)
```

```json
{
  "name": "neigh_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586970176,
      "name": "neigh_update",
      "external": true,
      "loc": "net/core/neighbour.c:1074",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_event_ns",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ndisc.c:ndisc_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586970176,
      "name": "neigh_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1774
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
int neigh_update(struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u32 nlmsg_pid)
```

```json
{
  "name": "neigh_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587094720,
      "name": "neigh_update",
      "external": true,
      "loc": "net/core/neighbour.c:1110",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_event_ns",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ndisc.c:ndisc_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587094720,
      "name": "neigh_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1768
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
int neigh_update(struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u32 nlmsg_pid)
```

```json
{
  "name": "neigh_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587596576,
      "name": "neigh_update",
      "external": true,
      "loc": "net/core/neighbour.c:1110",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_event_ns",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ndisc.c:ndisc_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587596576,
      "name": "neigh_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1792
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
int neigh_update(struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u32 nlmsg_pid)
```

```json
{
  "name": "neigh_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587904912,
      "name": "neigh_update",
      "external": true,
      "loc": "net/core/neighbour.c:1121",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_event_ns",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ndisc.c:ndisc_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587904912,
      "name": "neigh_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1973
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
int neigh_update(struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u32 nlmsg_pid)
```

```json
{
  "name": "neigh_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588053775,
      "name": "neigh_update",
      "external": true,
      "loc": "net/core/neighbour.c:1399",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_event_ns"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ndisc.c:ndisc_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588051680,
      "name": "neigh_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int neigh_update(struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u32 nlmsg_pid)
```

```json
{
  "name": "neigh_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588367856,
      "name": "neigh_update",
      "external": true,
      "loc": "net/core/neighbour.c:1413",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_event_ns"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ndisc.c:ndisc_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588364768,
      "name": "neigh_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int neigh_update(struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u32 nlmsg_pid)
```

```json
{
  "name": "neigh_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588574304,
      "name": "neigh_update",
      "external": true,
      "loc": "net/core/neighbour.c:1410",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_event_ns"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ndisc.c:ndisc_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588571216,
      "name": "neigh_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int neigh_update(struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u32 nlmsg_pid)
```

```json
{
  "name": "neigh_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589426608,
      "name": "neigh_update",
      "external": true,
      "loc": "net/core/neighbour.c:1411",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_event_ns"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589424416,
      "name": "neigh_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int neigh_update(struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u32 nlmsg_pid)
```

```json
{
  "name": "neigh_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589427328,
      "name": "neigh_update",
      "external": true,
      "loc": "net/core/neighbour.c:1414",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_event_ns"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589424208,
      "name": "neigh_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int neigh_update(struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u32 nlmsg_pid)
```

```json
{
  "name": "neigh_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589324688,
      "name": "neigh_update",
      "external": true,
      "loc": "net/core/neighbour.c:1418",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_event_ns"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589320928,
      "name": "neigh_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int neigh_update(struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u32 nlmsg_pid)
```

```json
{
  "name": "neigh_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590054131,
      "name": "neigh_update",
      "external": true,
      "loc": "net/core/neighbour.c:1419",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_event_ns"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590051584,
      "name": "neigh_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int neigh_update(struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u32 nlmsg_pid)
```

```json
{
  "name": "neigh_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591598472,
      "name": "neigh_update",
      "external": true,
      "loc": "net/core/neighbour.c:1465",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_event_ns"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_invalidate",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591595632,
      "name": "neigh_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int neigh_update(struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u32 nlmsg_pid)
```

```json
{
  "name": "neigh_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593379512,
      "name": "neigh_update",
      "external": true,
      "loc": "net/core/neighbour.c:1505",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_event_ns"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_invalidate",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593376624,
      "name": "neigh_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int neigh_update(struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u32 nlmsg_pid)
```

```json
{
  "name": "neigh_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593841720,
      "name": "neigh_update",
      "external": true,
      "loc": "net/core/neighbour.c:1474",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_event_ns"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_invalidate",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593838784,
      "name": "neigh_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int neigh_update(struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u32 nlmsg_pid)
```

```json
{
  "name": "neigh_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594623384,
      "name": "neigh_update",
      "external": true,
      "loc": "net/core/neighbour.c:1485",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_event_ns"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_invalidate",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594620368,
      "name": "neigh_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int neigh_update(struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u32 nlmsg_pid)
```

```json
{
  "name": "neigh_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502118492,
      "name": "neigh_update",
      "external": true,
      "loc": "net/core/neighbour.c:1410",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_event_ns"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ndisc.c:ndisc_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502110072,
      "name": "neigh_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int neigh_update(struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u32 nlmsg_pid)
```

```json
{
  "name": "neigh_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234863664,
      "name": "neigh_update",
      "external": true,
      "loc": "net/core/neighbour.c:1410",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_event_ns"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ndisc.c:ndisc_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234852744,
      "name": "neigh_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int neigh_update(struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u32 nlmsg_pid)
```

```json
{
  "name": "neigh_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295577568,
      "name": "neigh_update",
      "external": true,
      "loc": "net/core/neighbour.c:1410",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_event_ns"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ndisc.c:ndisc_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295566192,
      "name": "neigh_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int neigh_update(struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u32 nlmsg_pid)
```

```json
{
  "name": "neigh_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278383806,
      "name": "neigh_update",
      "external": true,
      "loc": "net/core/neighbour.c:1410",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_event_ns"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ndisc.c:ndisc_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278377128,
      "name": "neigh_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int neigh_update(struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u32 nlmsg_pid)
```

```json
{
  "name": "neigh_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588181040,
      "name": "neigh_update",
      "external": true,
      "loc": "net/core/neighbour.c:1410",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_event_ns"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ndisc.c:ndisc_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588177952,
      "name": "neigh_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int neigh_update(struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u32 nlmsg_pid)
```

```json
{
  "name": "neigh_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587893872,
      "name": "neigh_update",
      "external": true,
      "loc": "net/core/neighbour.c:1410",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_event_ns"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ndisc.c:ndisc_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587890784,
      "name": "neigh_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int neigh_update(struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u32 nlmsg_pid)
```

```json
{
  "name": "neigh_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588512864,
      "name": "neigh_update",
      "external": true,
      "loc": "net/core/neighbour.c:1410",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_event_ns"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ndisc.c:ndisc_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588509776,
      "name": "neigh_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int neigh_update(struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u32 nlmsg_pid)
```

```json
{
  "name": "neigh_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588650096,
      "name": "neigh_update",
      "external": true,
      "loc": "net/core/neighbour.c:1410",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_event_ns"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ndisc.c:ndisc_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588646944,
      "name": "neigh_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 nlmsg_pid</code>
</li>
</ul>
</details>
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
