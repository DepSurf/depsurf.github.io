# Function: <code>do_xdp_generic</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int do_xdp_generic(struct bpf_prog * xdp_prog, struct sk_buff * skb)
```

```json
{
  "name": "do_xdp_generic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587538368,
      "name": "do_xdp_generic",
      "external": true,
      "loc": "net/core/dev.c:4022",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/dev.c:netif_receive_skb_internal",
        "net/core/dev.c:netif_rx_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587538368,
      "name": "do_xdp_generic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 788
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_xdp_generic(struct bpf_prog * xdp_prog, struct sk_buff * skb)
```

```json
{
  "name": "do_xdp_generic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587843455,
      "name": "do_xdp_generic",
      "external": true,
      "loc": "net/core/dev.c:4141",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_rx_internal"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/dev.c:netif_rx_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587842240,
      "name": "do_xdp_generic.part.126",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 966
    },
    {
      "addr": 18446744071587843216,
      "name": "do_xdp_generic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_xdp_generic(struct bpf_prog * xdp_prog, struct sk_buff * skb)
```

```json
{
  "name": "do_xdp_generic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587988020,
      "name": "do_xdp_generic",
      "external": true,
      "loc": "net/core/dev.c:4450",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_receive_skb_list",
        "net/core/dev.c:netif_rx_internal"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "net/core/dev.c:netif_receive_skb_list",
        "net/core/dev.c:netif_rx_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587975888,
      "name": "do_xdp_generic.part.133",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1043
    },
    {
      "addr": 18446744071587976944,
      "name": "do_xdp_generic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
int do_xdp_generic(struct bpf_prog * xdp_prog, struct sk_buff * skb)
```

```json
{
  "name": "do_xdp_generic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588290324,
      "name": "do_xdp_generic",
      "external": true,
      "loc": "net/core/dev.c:4464",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_receive_skb_core"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "net/core/dev.c:__netif_receive_skb_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588289728,
      "name": "do_xdp_generic.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446744071588289904,
      "name": "do_xdp_generic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_xdp_generic(struct bpf_prog * xdp_prog, struct sk_buff * skb)
```

```json
{
  "name": "do_xdp_generic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588495700,
      "name": "do_xdp_generic",
      "external": true,
      "loc": "net/core/dev.c:4366",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_receive_skb_core"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "net/core/dev.c:__netif_receive_skb_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588495104,
      "name": "do_xdp_generic.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446744071588495280,
      "name": "do_xdp_generic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_xdp_generic(struct bpf_prog * xdp_prog, struct sk_buff * skb)
```

```json
{
  "name": "do_xdp_generic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589366850,
      "name": "do_xdp_generic",
      "external": true,
      "loc": "net/core/dev.c:4728",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_receive_skb_core"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/dev.c:__netif_receive_skb_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589366032,
      "name": "do_xdp_generic.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446744071589377232,
      "name": "do_xdp_generic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_xdp_generic(struct bpf_prog * xdp_prog, struct sk_buff * skb)
```

```json
{
  "name": "do_xdp_generic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589372247,
      "name": "do_xdp_generic",
      "external": true,
      "loc": "net/core/dev.c:4757",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_receive_skb_core"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/dev.c:__netif_receive_skb_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589371584,
      "name": "do_xdp_generic.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446744071589383024,
      "name": "do_xdp_generic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_xdp_generic(struct bpf_prog * xdp_prog, struct sk_buff * skb)
```

```json
{
  "name": "do_xdp_generic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589267536,
      "name": "do_xdp_generic",
      "external": true,
      "loc": "net/core/dev.c:4865",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589267536,
      "name": "do_xdp_generic.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446744071589279776,
      "name": "do_xdp_generic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_xdp_generic(struct bpf_prog * xdp_prog, struct sk_buff * skb)
```

```json
{
  "name": "do_xdp_generic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589994560,
      "name": "do_xdp_generic",
      "external": true,
      "loc": "net/core/dev.c:4856",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589994560,
      "name": "do_xdp_generic.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 498
    },
    {
      "addr": 18446744071589995072,
      "name": "do_xdp_generic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
int do_xdp_generic(struct bpf_prog * xdp_prog, struct sk_buff * skb)
```

```json
{
  "name": "do_xdp_generic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591535792,
      "name": "do_xdp_generic",
      "external": true,
      "loc": "net/core/dev.c:4897",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591535792,
      "name": "do_xdp_generic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int do_xdp_generic(struct bpf_prog * xdp_prog, struct sk_buff * skb)
```

```json
{
  "name": "do_xdp_generic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593309504,
      "name": "do_xdp_generic",
      "external": true,
      "loc": "net/core/dev.c:4884",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593309504,
      "name": "do_xdp_generic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int do_xdp_generic(struct bpf_prog * xdp_prog, struct sk_buff * skb)
```

```json
{
  "name": "do_xdp_generic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593771216,
      "name": "do_xdp_generic",
      "external": true,
      "loc": "net/core/dev.c:4859",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593771216,
      "name": "do_xdp_generic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int do_xdp_generic(struct bpf_prog * xdp_prog, struct sk_buff * skb)
```

```json
{
  "name": "do_xdp_generic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594550768,
      "name": "do_xdp_generic",
      "external": true,
      "loc": "net/core/dev.c:5007",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594550768,
      "name": "do_xdp_generic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_xdp_generic(struct bpf_prog * xdp_prog, struct sk_buff * skb)
```

```json
{
  "name": "do_xdp_generic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502027460,
      "name": "do_xdp_generic",
      "external": true,
      "loc": "net/core/dev.c:4366",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_receive_skb_core"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "net/core/dev.c:__netif_receive_skb_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502026808,
      "name": "do_xdp_generic.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    },
    {
      "addr": 18446603336502027008,
      "name": "do_xdp_generic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
int do_xdp_generic(struct bpf_prog * xdp_prog, struct sk_buff * skb)
```

```json
{
  "name": "do_xdp_generic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234780612,
      "name": "do_xdp_generic",
      "external": true,
      "loc": "net/core/dev.c:4366",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_receive_skb_core"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_get_user",
        "net/core/dev.c:__netif_receive_skb_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234778608,
      "name": "do_xdp_generic.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 3234778800,
      "name": "do_xdp_generic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
int do_xdp_generic(struct bpf_prog * xdp_prog, struct sk_buff * skb)
```

```json
{
  "name": "do_xdp_generic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295470524,
      "name": "do_xdp_generic",
      "external": true,
      "loc": "net/core/dev.c:4366",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_receive_skb_core"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "net/core/dev.c:__netif_receive_skb_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295469568,
      "name": "do_xdp_generic.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    },
    {
      "addr": 13835058055295469824,
      "name": "do_xdp_generic",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_xdp_generic(struct bpf_prog * xdp_prog, struct sk_buff * skb)
```

```json
{
  "name": "do_xdp_generic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278318454,
      "name": "do_xdp_generic",
      "external": true,
      "loc": "net/core/dev.c:4366",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_receive_skb_core"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "net/core/dev.c:__netif_receive_skb_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278316914,
      "name": "do_xdp_generic.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446743936278317042,
      "name": "do_xdp_generic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_xdp_generic(struct bpf_prog * xdp_prog, struct sk_buff * skb)
```

```json
{
  "name": "do_xdp_generic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588102484,
      "name": "do_xdp_generic",
      "external": true,
      "loc": "net/core/dev.c:4366",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_receive_skb_core"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "net/core/dev.c:__netif_receive_skb_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588101888,
      "name": "do_xdp_generic.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446744071588102064,
      "name": "do_xdp_generic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_xdp_generic(struct bpf_prog * xdp_prog, struct sk_buff * skb)
```

```json
{
  "name": "do_xdp_generic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587815396,
      "name": "do_xdp_generic",
      "external": true,
      "loc": "net/core/dev.c:4366",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_receive_skb_core"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "net/core/dev.c:__netif_receive_skb_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587814800,
      "name": "do_xdp_generic.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446744071587814976,
      "name": "do_xdp_generic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_xdp_generic(struct bpf_prog * xdp_prog, struct sk_buff * skb)
```

```json
{
  "name": "do_xdp_generic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588434260,
      "name": "do_xdp_generic",
      "external": true,
      "loc": "net/core/dev.c:4366",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_receive_skb_core"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "net/core/dev.c:__netif_receive_skb_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588433664,
      "name": "do_xdp_generic.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446744071588433840,
      "name": "do_xdp_generic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_xdp_generic(struct bpf_prog * xdp_prog, struct sk_buff * skb)
```

```json
{
  "name": "do_xdp_generic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588570683,
      "name": "do_xdp_generic",
      "external": true,
      "loc": "net/core/dev.c:4366",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_receive_skb_core"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "net/core/dev.c:__netif_receive_skb_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588570080,
      "name": "do_xdp_generic.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446744071588570256,
      "name": "do_xdp_generic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int do_xdp_generic(struct bpf_prog * xdp_prog, struct sk_buff * skb)
```
</details>
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
