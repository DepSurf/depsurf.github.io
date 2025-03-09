# Function: <code>udp_v6_send_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int udp_v6_send_skb(struct sk_buff * skb, struct flowi6 * fl6)
```

```json
{
  "name": "udp_v6_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587109632,
      "name": "udp_v6_send_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:1029",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udp_v6_push_pending_frames",
        "net/ipv6/udp.c:udpv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587109632,
      "name": "udp_v6_send_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 807
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
int udp_v6_send_skb(struct sk_buff * skb, struct flowi6 * fl6)
```

```json
{
  "name": "udp_v6_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587561328,
      "name": "udp_v6_send_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:935",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587561328,
      "name": "udp_v6_send_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 807
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
int udp_v6_send_skb(struct sk_buff * skb, struct flowi6 * fl6)
```

```json
{
  "name": "udp_v6_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587765616,
      "name": "udp_v6_send_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:921",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587765616,
      "name": "udp_v6_send_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 807
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
int udp_v6_send_skb(struct sk_buff * skb, struct flowi6 * fl6)
```

```json
{
  "name": "udp_v6_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587923280,
      "name": "udp_v6_send_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:1032",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587923280,
      "name": "udp_v6_send_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 848
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
int udp_v6_send_skb(struct sk_buff * skb, struct flowi6 * fl6)
```

```json
{
  "name": "udp_v6_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588458496,
      "name": "udp_v6_send_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:1037",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588458496,
      "name": "udp_v6_send_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 848
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
  "name": "udp_v6_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588819680,
      "name": "udp_v6_send_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:1033",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588819680,
      "name": "udp_v6_send_skb.isra.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1058
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
  "name": "udp_v6_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589042160,
      "name": "udp_v6_send_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:1113",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589042160,
      "name": "udp_v6_send_skb.isra.33",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1058
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
  "name": "udp_v6_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589495840,
      "name": "udp_v6_send_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:1102",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589495840,
      "name": "udp_v6_send_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1082
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
  "name": "udp_v6_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589719728,
      "name": "udp_v6_send_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:1102",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589719728,
      "name": "udp_v6_send_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1171
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
int udp_v6_send_skb(struct sk_buff * skb, struct flowi6 * fl6, struct inet_cork * cork)
```

```json
{
  "name": "udp_v6_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590737920,
      "name": "udp_v6_send_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:1107",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590737920,
      "name": "udp_v6_send_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 887
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
int udp_v6_send_skb(struct sk_buff * skb, struct flowi6 * fl6, struct inet_cork * cork)
```

```json
{
  "name": "udp_v6_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590796560,
      "name": "udp_v6_send_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:1164",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590796560,
      "name": "udp_v6_send_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 887
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
int udp_v6_send_skb(struct sk_buff * skb, struct flowi6 * fl6, struct inet_cork * cork)
```

```json
{
  "name": "udp_v6_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590722992,
      "name": "udp_v6_send_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:1177",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590722992,
      "name": "udp_v6_send_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1117
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
int udp_v6_send_skb(struct sk_buff * skb, struct flowi6 * fl6, struct inet_cork * cork)
```

```json
{
  "name": "udp_v6_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "udp_v6_send_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:1179",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591547488,
      "name": "udp_v6_send_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1115
    },
    {
      "addr": 18446744071592740610,
      "name": "udp_v6_send_skb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
int udp_v6_send_skb(struct sk_buff * skb, struct flowi6 * fl6, struct inet_cork * cork)
```

```json
{
  "name": "udp_v6_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "udp_v6_send_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:1188",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593236672,
      "name": "udp_v6_send_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1104
    },
    {
      "addr": 18446744071594627292,
      "name": "udp_v6_send_skb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
int udp_v6_send_skb(struct sk_buff * skb, struct flowi6 * fl6, struct inet_cork * cork)
```

```json
{
  "name": "udp_v6_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "udp_v6_send_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:1223",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595137360,
      "name": "udp_v6_send_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1104
    },
    {
      "addr": 18446744071596360998,
      "name": "udp_v6_send_skb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
int udp_v6_send_skb(struct sk_buff * skb, struct flowi6 * fl6, struct inet_cork * cork)
```

```json
{
  "name": "udp_v6_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "udp_v6_send_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:1240",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595528704,
      "name": "udp_v6_send_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1110
    },
    {
      "addr": 18446744071596889606,
      "name": "udp_v6_send_skb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
int udp_v6_send_skb(struct sk_buff * skb, struct flowi6 * fl6, struct inet_cork * cork)
```

```json
{
  "name": "udp_v6_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596367120,
      "name": "udp_v6_send_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:1214",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596367120,
      "name": "udp_v6_send_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1076
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
  "name": "udp_v6_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503414056,
      "name": "udp_v6_send_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:1102",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503414056,
      "name": "udp_v6_send_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1112
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
int udp_v6_send_skb(struct sk_buff * skb, struct flowi6 * fl6, struct inet_cork * cork)
```

```json
{
  "name": "udp_v6_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236070024,
      "name": "udp_v6_send_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:1102",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236070024,
      "name": "udp_v6_send_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1108
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
  "name": "udp_v6_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297188992,
      "name": "udp_v6_send_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:1102",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297188992,
      "name": "udp_v6_send_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1396
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
  "name": "udp_v6_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279401866,
      "name": "udp_v6_send_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:1102",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279401866,
      "name": "udp_v6_send_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1050
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
  "name": "udp_v6_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589324096,
      "name": "udp_v6_send_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:1102",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589324096,
      "name": "udp_v6_send_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1171
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
  "name": "udp_v6_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589049088,
      "name": "udp_v6_send_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:1102",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589049088,
      "name": "udp_v6_send_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1171
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
  "name": "udp_v6_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589760960,
      "name": "udp_v6_send_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:1102",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589760960,
      "name": "udp_v6_send_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1171
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
  "name": "udp_v6_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589811616,
      "name": "udp_v6_send_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:1102",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589811616,
      "name": "udp_v6_send_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1171
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
int udp_v6_send_skb(struct sk_buff * skb, struct flowi6 * fl6)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int udp_v6_send_skb(struct sk_buff * skb, struct flowi6 * fl6, struct inet_cork * cork)
```
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int udp_v6_send_skb(struct sk_buff * skb, struct flowi6 * fl6, struct inet_cork * cork)
```
</details>
</li>
</ul>
