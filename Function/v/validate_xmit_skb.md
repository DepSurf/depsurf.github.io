# Function: <code>validate_xmit_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "validate_xmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586301312,
      "name": "validate_xmit_skb",
      "external": false,
      "loc": "net/core/dev.c:2761",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:validate_xmit_skb_list",
        "net/core/dev.c:__dev_queue_xmit"
      ],
      "caller_func": [
        "net/core/dev.c:validate_xmit_skb_list",
        "net/core/dev.c:__dev_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586301312,
      "name": "validate_xmit_skb.isra.97.part.98",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 675
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
struct sk_buff * validate_xmit_skb(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "validate_xmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586729712,
      "name": "validate_xmit_skb",
      "external": false,
      "loc": "net/core/dev.c:2962",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586729712,
      "name": "validate_xmit_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 661
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
struct sk_buff * validate_xmit_skb(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "validate_xmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586915584,
      "name": "validate_xmit_skb",
      "external": false,
      "loc": "net/core/dev.c:2959",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586915584,
      "name": "validate_xmit_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 661
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
struct sk_buff * validate_xmit_skb(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "validate_xmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587036416,
      "name": "validate_xmit_skb",
      "external": false,
      "loc": "net/core/dev.c:3037",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587036416,
      "name": "validate_xmit_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 655
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
struct sk_buff * validate_xmit_skb(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "validate_xmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587534416,
      "name": "validate_xmit_skb",
      "external": false,
      "loc": "net/core/dev.c:3064",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587534416,
      "name": "validate_xmit_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 655
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
struct sk_buff * validate_xmit_skb(struct sk_buff * skb, struct net_device * dev, bool * again)
```

```json
{
  "name": "validate_xmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587837520,
      "name": "validate_xmit_skb",
      "external": false,
      "loc": "net/core/dev.c:3088",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587837520,
      "name": "validate_xmit_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 748
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
struct sk_buff * validate_xmit_skb(struct sk_buff * skb, struct net_device * dev, bool * again)
```

```json
{
  "name": "validate_xmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587971184,
      "name": "validate_xmit_skb",
      "external": false,
      "loc": "net/core/dev.c:3332",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587971184,
      "name": "validate_xmit_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 750
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct sk_buff * validate_xmit_skb(struct sk_buff * skb, struct net_device * dev, bool * again)
```

```json
{
  "name": "validate_xmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "validate_xmit_skb",
      "external": false,
      "loc": "net/core/dev.c:3334",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588284736,
      "name": "validate_xmit_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 832
    },
    {
      "addr": 18446744071588312054,
      "name": "validate_xmit_skb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
struct sk_buff * validate_xmit_skb(struct sk_buff * skb, struct net_device * dev, bool * again)
```

```json
{
  "name": "validate_xmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "validate_xmit_skb",
      "external": false,
      "loc": "net/core/dev.c:3252",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588490352,
      "name": "validate_xmit_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 832
    },
    {
      "addr": 18446744071588518384,
      "name": "validate_xmit_skb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct sk_buff * validate_xmit_skb(struct sk_buff * skb, struct net_device * dev, bool * again)
```

```json
{
  "name": "validate_xmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "validate_xmit_skb",
      "external": false,
      "loc": "net/core/dev.c:3610",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589362704,
      "name": "validate_xmit_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 450
    },
    {
      "addr": 18446744071589392312,
      "name": "validate_xmit_skb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
struct sk_buff * validate_xmit_skb(struct sk_buff * skb, struct net_device * dev, bool * again)
```

```json
{
  "name": "validate_xmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "validate_xmit_skb",
      "external": false,
      "loc": "net/core/dev.c:3640",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589368544,
      "name": "validate_xmit_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 470
    },
    {
      "addr": 18446744071591629536,
      "name": "validate_xmit_skb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
struct sk_buff * validate_xmit_skb(struct sk_buff * skb, struct net_device * dev, bool * again)
```

```json
{
  "name": "validate_xmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "validate_xmit_skb",
      "external": false,
      "loc": "net/core/dev.c:3719",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589264480,
      "name": "validate_xmit_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 450
    },
    {
      "addr": 18446744071591572902,
      "name": "validate_xmit_skb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
struct sk_buff * validate_xmit_skb(struct sk_buff * skb, struct net_device * dev, bool * again)
```

```json
{
  "name": "validate_xmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "validate_xmit_skb",
      "external": false,
      "loc": "net/core/dev.c:3649",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589990528,
      "name": "validate_xmit_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 475
    },
    {
      "addr": 18446744071592698692,
      "name": "validate_xmit_skb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
struct sk_buff * validate_xmit_skb(struct sk_buff * skb, struct net_device * dev, bool * again)
```

```json
{
  "name": "validate_xmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "validate_xmit_skb",
      "external": false,
      "loc": "net/core/dev.c:3655",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591530144,
      "name": "validate_xmit_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 653
    },
    {
      "addr": 18446744071594584858,
      "name": "validate_xmit_skb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
struct sk_buff * validate_xmit_skb(struct sk_buff * skb, struct net_device * dev, bool * again)
```

```json
{
  "name": "validate_xmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "validate_xmit_skb",
      "external": false,
      "loc": "net/core/dev.c:3642",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593303664,
      "name": "validate_xmit_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 668
    },
    {
      "addr": 18446744071596324352,
      "name": "validate_xmit_skb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
struct sk_buff * validate_xmit_skb(struct sk_buff * skb, struct net_device * dev, bool * again)
```

```json
{
  "name": "validate_xmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "validate_xmit_skb",
      "external": false,
      "loc": "net/core/dev.c:3602",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593765376,
      "name": "validate_xmit_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 643
    },
    {
      "addr": 18446744071596854672,
      "name": "validate_xmit_skb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct sk_buff * validate_xmit_skb(struct sk_buff * skb, struct net_device * dev, bool * again)
```

```json
{
  "name": "validate_xmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "validate_xmit_skb",
      "external": false,
      "loc": "net/core/dev.c:3612",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594544560,
      "name": "validate_xmit_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 622
    },
    {
      "addr": 18446744071597779705,
      "name": "validate_xmit_skb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
struct sk_buff * validate_xmit_skb(struct sk_buff * skb, struct net_device * dev, bool * again)
```

```json
{
  "name": "validate_xmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502021264,
      "name": "validate_xmit_skb",
      "external": false,
      "loc": "net/core/dev.c:3252",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502021264,
      "name": "validate_xmit_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 784
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
struct sk_buff * validate_xmit_skb(struct sk_buff * skb, struct net_device * dev, bool * again)
```

```json
{
  "name": "validate_xmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234773192,
      "name": "validate_xmit_skb",
      "external": false,
      "loc": "net/core/dev.c:3252",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234773192,
      "name": "validate_xmit_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 828
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
struct sk_buff * validate_xmit_skb(struct sk_buff * skb, struct net_device * dev, bool * again)
```

```json
{
  "name": "validate_xmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295462640,
      "name": "validate_xmit_skb",
      "external": false,
      "loc": "net/core/dev.c:3252",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295462640,
      "name": "validate_xmit_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1152
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
struct sk_buff * validate_xmit_skb(struct sk_buff * skb, struct net_device * dev, bool * again)
```

```json
{
  "name": "validate_xmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278311684,
      "name": "validate_xmit_skb",
      "external": false,
      "loc": "net/core/dev.c:3252",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278311684,
      "name": "validate_xmit_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 686
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
struct sk_buff * validate_xmit_skb(struct sk_buff * skb, struct net_device * dev, bool * again)
```

```json
{
  "name": "validate_xmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "validate_xmit_skb",
      "external": false,
      "loc": "net/core/dev.c:3252",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588097136,
      "name": "validate_xmit_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 832
    },
    {
      "addr": 18446744071588125120,
      "name": "validate_xmit_skb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
struct sk_buff * validate_xmit_skb(struct sk_buff * skb, struct net_device * dev, bool * again)
```

```json
{
  "name": "validate_xmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "validate_xmit_skb",
      "external": false,
      "loc": "net/core/dev.c:3252",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587810048,
      "name": "validate_xmit_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 832
    },
    {
      "addr": 18446744071587837952,
      "name": "validate_xmit_skb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
struct sk_buff * validate_xmit_skb(struct sk_buff * skb, struct net_device * dev, bool * again)
```

```json
{
  "name": "validate_xmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "validate_xmit_skb",
      "external": false,
      "loc": "net/core/dev.c:3252",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588428912,
      "name": "validate_xmit_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 832
    },
    {
      "addr": 18446744071588456944,
      "name": "validate_xmit_skb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
struct sk_buff * validate_xmit_skb(struct sk_buff * skb, struct net_device * dev, bool * again)
```

```json
{
  "name": "validate_xmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "validate_xmit_skb",
      "external": false,
      "loc": "net/core/dev.c:3252",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588565216,
      "name": "validate_xmit_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 832
    },
    {
      "addr": 18446744071588593856,
      "name": "validate_xmit_skb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct sk_buff * validate_xmit_skb(struct sk_buff * skb, struct net_device * dev)
```
</details>
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
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool * again</code>
</li>
</ul>
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
