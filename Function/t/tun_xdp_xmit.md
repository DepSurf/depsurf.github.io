# Function: <code>tun_xdp_xmit</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int tun_xdp_xmit(struct net_device * dev, int n, struct xdp_frame * * frames, u32 flags)
```

```json
{
  "name": "tun_xdp_xmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586434272,
      "name": "tun_xdp_xmit",
      "external": false,
      "loc": "drivers/net/tun.c:1300",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586434272,
      "name": "tun_xdp_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int tun_xdp_xmit(struct net_device * dev, int n, struct xdp_frame * * frames, u32 flags)
```

```json
{
  "name": "tun_xdp_xmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586580352,
      "name": "tun_xdp_xmit",
      "external": false,
      "loc": "drivers/net/tun.c:1293",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586580352,
      "name": "tun_xdp_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
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
int tun_xdp_xmit(struct net_device * dev, int n, struct xdp_frame * * frames, u32 flags)
```

```json
{
  "name": "tun_xdp_xmit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586832224,
      "name": "tun_xdp_xmit",
      "external": false,
      "loc": "drivers/net/tun.c:1281",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586832224,
      "name": "tun_xdp_xmit.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
    },
    {
      "addr": 18446744071586832592,
      "name": "tun_xdp_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int tun_xdp_xmit(struct net_device * dev, int n, struct xdp_frame * * frames, u32 flags)
```

```json
{
  "name": "tun_xdp_xmit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586978288,
      "name": "tun_xdp_xmit",
      "external": false,
      "loc": "drivers/net/tun.c:1281",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586978288,
      "name": "tun_xdp_xmit.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
    },
    {
      "addr": 18446744071586978656,
      "name": "tun_xdp_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int tun_xdp_xmit(struct net_device * dev, int n, struct xdp_frame * * frames, u32 flags)
```

```json
{
  "name": "tun_xdp_xmit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587810345,
      "name": "tun_xdp_xmit",
      "external": false,
      "loc": "drivers/net/tun.c:1247",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_act"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_xdp_act"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587809552,
      "name": "tun_xdp_xmit.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
    },
    {
      "addr": 18446744071587809936,
      "name": "tun_xdp_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int tun_xdp_xmit(struct net_device * dev, int n, struct xdp_frame * * frames, u32 flags)
```

```json
{
  "name": "tun_xdp_xmit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587868288,
      "name": "tun_xdp_xmit",
      "external": false,
      "loc": "drivers/net/tun.c:1178",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_act"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_xdp_act"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587867520,
      "name": "tun_xdp_xmit.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071587867904,
      "name": "tun_xdp_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int tun_xdp_xmit(struct net_device * dev, int n, struct xdp_frame * * frames, u32 flags)
```

```json
{
  "name": "tun_xdp_xmit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587747549,
      "name": "tun_xdp_xmit",
      "external": false,
      "loc": "drivers/net/tun.c:1186",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_act"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_xdp_act"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587746816,
      "name": "tun_xdp_xmit.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
    },
    {
      "addr": 18446744071587747168,
      "name": "tun_xdp_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int tun_xdp_xmit(struct net_device * dev, int n, struct xdp_frame * * frames, u32 flags)
```

```json
{
  "name": "tun_xdp_xmit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588343130,
      "name": "tun_xdp_xmit",
      "external": false,
      "loc": "drivers/net/tun.c:1241",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_act"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_xdp_act"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588342352,
      "name": "tun_xdp_xmit.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
    },
    {
      "addr": 18446744071588342752,
      "name": "tun_xdp_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tun_xdp_xmit(struct net_device * dev, int n, struct xdp_frame * * frames, u32 flags)
```

```json
{
  "name": "tun_xdp_xmit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589733648,
      "name": "tun_xdp_xmit",
      "external": false,
      "loc": "drivers/net/tun.c:1269",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_act"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_xdp_act"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589728080,
      "name": "tun_xdp_xmit.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
    },
    {
      "addr": 18446744071589728528,
      "name": "tun_xdp_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tun_xdp_xmit(struct net_device * dev, int n, struct xdp_frame * * frames, u32 flags)
```

```json
{
  "name": "tun_xdp_xmit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591349416,
      "name": "tun_xdp_xmit",
      "external": false,
      "loc": "drivers/net/tun.c:1271",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_act"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_xdp_act"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591346752,
      "name": "tun_xdp_xmit.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
    },
    {
      "addr": 18446744071591347216,
      "name": "tun_xdp_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tun_xdp_xmit(struct net_device * dev, int n, struct xdp_frame * * frames, u32 flags)
```

```json
{
  "name": "tun_xdp_xmit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591711144,
      "name": "tun_xdp_xmit",
      "external": false,
      "loc": "drivers/net/tun.c:1271",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_act"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_xdp_act"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591708464,
      "name": "tun_xdp_xmit.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 445
    },
    {
      "addr": 18446744071591708928,
      "name": "tun_xdp_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tun_xdp_xmit(struct net_device * dev, int n, struct xdp_frame * * frames, u32 flags)
```

```json
{
  "name": "tun_xdp_xmit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592453118,
      "name": "tun_xdp_xmit",
      "external": false,
      "loc": "drivers/net/tun.c:1272",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_act"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_xdp_act"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592452128,
      "name": "tun_xdp_xmit.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
    },
    {
      "addr": 18446744071592452544,
      "name": "tun_xdp_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
int tun_xdp_xmit(struct net_device * dev, int n, struct xdp_frame * * frames, u32 flags)
```

```json
{
  "name": "tun_xdp_xmit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499970832,
      "name": "tun_xdp_xmit",
      "external": false,
      "loc": "drivers/net/tun.c:1281",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499970832,
      "name": "tun_xdp_xmit.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    },
    {
      "addr": 18446603336499971280,
      "name": "tun_xdp_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
int tun_xdp_xmit(struct net_device * dev, int n, struct xdp_frame * * frames, u32 flags)
```

```json
{
  "name": "tun_xdp_xmit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232510344,
      "name": "tun_xdp_xmit",
      "external": false,
      "loc": "drivers/net/tun.c:1281",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_act"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_xdp_act"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232509488,
      "name": "tun_xdp_xmit.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    },
    {
      "addr": 3232509860,
      "name": "tun_xdp_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int tun_xdp_xmit(struct net_device * dev, int n, struct xdp_frame * * frames, u32 flags)
```

```json
{
  "name": "tun_xdp_xmit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293298712,
      "name": "tun_xdp_xmit",
      "external": false,
      "loc": "drivers/net/tun.c:1281",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_act"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_xdp_act"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293297696,
      "name": "tun_xdp_xmit.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 568
    },
    {
      "addr": 13835058055293298272,
      "name": "tun_xdp_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int tun_xdp_xmit(struct net_device * dev, int n, struct xdp_frame * * frames, u32 flags)
```

```json
{
  "name": "tun_xdp_xmit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277051178,
      "name": "tun_xdp_xmit",
      "external": false,
      "loc": "drivers/net/tun.c:1281",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_act"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_xdp_act"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277050320,
      "name": "tun_xdp_xmit.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
    },
    {
      "addr": 18446743936277050726,
      "name": "tun_xdp_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
int tun_xdp_xmit(struct net_device * dev, int n, struct xdp_frame * * frames, u32 flags)
```

```json
{
  "name": "tun_xdp_xmit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586735296,
      "name": "tun_xdp_xmit",
      "external": false,
      "loc": "drivers/net/tun.c:1281",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586735296,
      "name": "tun_xdp_xmit.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
    },
    {
      "addr": 18446744071586735664,
      "name": "tun_xdp_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int tun_xdp_xmit(struct net_device * dev, int n, struct xdp_frame * * frames, u32 flags)
```

```json
{
  "name": "tun_xdp_xmit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586602512,
      "name": "tun_xdp_xmit",
      "external": false,
      "loc": "drivers/net/tun.c:1281",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586602512,
      "name": "tun_xdp_xmit.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
    },
    {
      "addr": 18446744071586602880,
      "name": "tun_xdp_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int tun_xdp_xmit(struct net_device * dev, int n, struct xdp_frame * * frames, u32 flags)
```

```json
{
  "name": "tun_xdp_xmit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586932848,
      "name": "tun_xdp_xmit",
      "external": false,
      "loc": "drivers/net/tun.c:1281",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586932848,
      "name": "tun_xdp_xmit.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
    },
    {
      "addr": 18446744071586933216,
      "name": "tun_xdp_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int tun_xdp_xmit(struct net_device * dev, int n, struct xdp_frame * * frames, u32 flags)
```

```json
{
  "name": "tun_xdp_xmit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587039792,
      "name": "tun_xdp_xmit",
      "external": false,
      "loc": "drivers/net/tun.c:1281",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587039792,
      "name": "tun_xdp_xmit.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
    },
    {
      "addr": 18446744071587040192,
      "name": "tun_xdp_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int tun_xdp_xmit(struct net_device * dev, int n, struct xdp_frame * * frames, u32 flags)
```
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
