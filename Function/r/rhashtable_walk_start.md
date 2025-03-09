# Function: <code>rhashtable_walk_start</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int rhashtable_walk_start(struct rhashtable_iter * iter)
```

```json
{
  "name": "rhashtable_walk_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583038704,
      "name": "rhashtable_walk_start",
      "external": true,
      "loc": "lib/rhashtable.c:561",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_walk_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583038704,
      "name": "rhashtable_walk_start",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int rhashtable_walk_start(struct rhashtable_iter * iter)
```

```json
{
  "name": "rhashtable_walk_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583331312,
      "name": "rhashtable_walk_start",
      "external": true,
      "loc": "lib/rhashtable.c:566",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_walk_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583331312,
      "name": "rhashtable_walk_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int rhashtable_walk_start(struct rhashtable_iter * iter)
```

```json
{
  "name": "rhashtable_walk_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583456496,
      "name": "rhashtable_walk_start",
      "external": true,
      "loc": "lib/rhashtable.c:654",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_walk_start",
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583456496,
      "name": "rhashtable_walk_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int rhashtable_walk_start(struct rhashtable_iter * iter)
```

```json
{
  "name": "rhashtable_walk_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583477216,
      "name": "rhashtable_walk_start",
      "external": true,
      "loc": "lib/rhashtable.c:748",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_walk_start",
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583477216,
      "name": "rhashtable_walk_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int rhashtable_walk_start(struct rhashtable_iter * iter)
```

```json
{
  "name": "rhashtable_walk_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583658176,
      "name": "rhashtable_walk_start",
      "external": true,
      "loc": "lib/rhashtable.c:750",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_walk_start",
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583658176,
      "name": "rhashtable_walk_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
  "name": "rhashtable_walk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588124713,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:392",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_seq_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588919823,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:392",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
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
  "name": "rhashtable_walk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588306969,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:253",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_seq_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589144031,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:253",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
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
  "name": "rhashtable_walk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588708323,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_seq_start",
        "net/netlink/af_netlink.c:__netlink_seq_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589598223,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
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
  "name": "rhashtable_walk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588686556,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:mem_allocator_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588932227,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_seq_start",
        "net/netlink/af_netlink.c:__netlink_seq_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589822607,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rhashtable_walk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589552892,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:mem_allocator_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589818307,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_seq_start",
        "net/netlink/af_netlink.c:__netlink_seq_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590846716,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rhashtable_walk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589562060,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:mem_allocator_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589854547,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_seq_start",
        "net/netlink/af_netlink.c:__netlink_seq_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590907484,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rhashtable_walk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589459196,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:mem_allocator_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589760211,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_seq_start",
        "net/netlink/af_netlink.c:__netlink_seq_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590836671,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
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
  "name": "rhashtable_walk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590197148,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:mem_allocator_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590519443,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_seq_start",
        "net/netlink/af_netlink.c:__netlink_seq_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591656207,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591662383,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/ipv6/ioam6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ioam6.c:ioam6_genl_dumpsc",
        "net/ipv6/ioam6.c:ioam6_genl_dumpns"
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
  "name": "rhashtable_walk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591759730,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:mem_allocator_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592128114,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_seq_start",
        "net/netlink/af_netlink.c:__netlink_seq_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593350868,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593356255,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/ipv6/ioam6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ioam6.c:ioam6_genl_dumpsc",
        "net/ipv6/ioam6.c:ioam6_genl_dumpns"
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
  "name": "rhashtable_walk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593551378,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:mem_allocator_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593951186,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_seq_start",
        "net/netlink/af_netlink.c:__netlink_seq_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595257444,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595263359,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/ipv6/ioam6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ioam6.c:ioam6_genl_dumpsc",
        "net/ipv6/ioam6.c:ioam6_genl_dumpns"
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
  "name": "rhashtable_walk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594020498,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:mem_allocator_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594327618,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_seq_start",
        "net/netlink/af_netlink.c:__netlink_seq_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595652804,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595659023,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/ipv6/ioam6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ioam6.c:ioam6_genl_dumpsc",
        "net/ipv6/ioam6.c:ioam6_genl_dumpns"
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
  "name": "rhashtable_walk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594806626,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:mem_allocator_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595127298,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_seq_start",
        "net/netlink/af_netlink.c:__netlink_seq_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596500308,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596506751,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/ipv6/ioam6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ioam6.c:ioam6_genl_dumpsc",
        "net/ipv6/ioam6.c:ioam6_genl_dumpns"
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
  "name": "rhashtable_walk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502239568,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:mem_allocator_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502522996,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_seq_start",
        "net/netlink/af_netlink.c:__netlink_seq_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503531064,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
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
  "name": "rhashtable_walk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234985244,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:mem_allocator_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 3235236364,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_seq_start",
        "net/netlink/af_netlink.c:__netlink_seq_next"
      ],
      "caller_func": []
    },
    {
      "addr": 3236184084,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
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
  "name": "rhashtable_walk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295731232,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:mem_allocator_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296099524,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_seq_start",
        "net/netlink/af_netlink.c:__netlink_seq_next"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297326748,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
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
  "name": "rhashtable_walk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278480994,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:mem_allocator_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278697162,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_seq_start",
        "net/netlink/af_netlink.c:__netlink_seq_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279498022,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
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
  "name": "rhashtable_walk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588293292,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:mem_allocator_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588538611,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_seq_start",
        "net/netlink/af_netlink.c:__netlink_seq_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589426975,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
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
  "name": "rhashtable_walk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588006108,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:mem_allocator_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588250611,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_seq_start",
        "net/netlink/af_netlink.c:__netlink_seq_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589151967,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
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
  "name": "rhashtable_walk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588625116,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:mem_allocator_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588870787,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_seq_start",
        "net/netlink/af_netlink.c:__netlink_seq_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589863839,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
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
  "name": "rhashtable_walk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588763260,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:mem_allocator_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589012323,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_seq_start",
        "net/netlink/af_netlink.c:__netlink_seq_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589915311,
      "name": "rhashtable_walk_start",
      "external": false,
      "loc": "include/linux/rhashtable.h:250",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
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
int rhashtable_walk_start(struct rhashtable_iter * iter)
```
</details>
</li>
</ul>
