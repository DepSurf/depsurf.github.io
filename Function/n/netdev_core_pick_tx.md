# Function: <code>netdev_core_pick_tx</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct netdev_queue * netdev_core_pick_tx(struct net_device * dev, struct sk_buff * skb, struct net_device * sb_dev)
```

```json
{
  "name": "netdev_core_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_core_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:3744",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588312071,
      "name": "netdev_core_pick_tx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071588286640,
      "name": "netdev_core_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
struct netdev_queue * netdev_core_pick_tx(struct net_device * dev, struct sk_buff * skb, struct net_device * sb_dev)
```

```json
{
  "name": "netdev_core_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_core_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:3644",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588518401,
      "name": "netdev_core_pick_tx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071588492256,
      "name": "netdev_core_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
struct netdev_queue * netdev_core_pick_tx(struct net_device * dev, struct sk_buff * skb, struct net_device * sb_dev)
```

```json
{
  "name": "netdev_core_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_core_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:4002",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589392329,
      "name": "netdev_core_pick_tx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071589364304,
      "name": "netdev_core_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
struct netdev_queue * netdev_core_pick_tx(struct net_device * dev, struct sk_buff * skb, struct net_device * sb_dev)
```

```json
{
  "name": "netdev_core_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_core_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:4033",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591629553,
      "name": "netdev_core_pick_tx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071589369824,
      "name": "netdev_core_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
struct netdev_queue * netdev_core_pick_tx(struct net_device * dev, struct sk_buff * skb, struct net_device * sb_dev)
```

```json
{
  "name": "netdev_core_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_core_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:4116",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591572919,
      "name": "netdev_core_pick_tx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071589265744,
      "name": "netdev_core_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
struct netdev_queue * netdev_core_pick_tx(struct net_device * dev, struct sk_buff * skb, struct net_device * sb_dev)
```

```json
{
  "name": "netdev_core_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_core_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:4081",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592698741,
      "name": "netdev_core_pick_tx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071589991808,
      "name": "netdev_core_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
struct netdev_queue * netdev_core_pick_tx(struct net_device * dev, struct sk_buff * skb, struct net_device * sb_dev)
```

```json
{
  "name": "netdev_core_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_core_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:4113",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594584907,
      "name": "netdev_core_pick_tx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071591531952,
      "name": "netdev_core_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
struct netdev_queue * netdev_core_pick_tx(struct net_device * dev, struct sk_buff * skb, struct net_device * sb_dev)
```

```json
{
  "name": "netdev_core_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593305552,
      "name": "netdev_core_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:4100",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593305552,
      "name": "netdev_core_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
struct netdev_queue * netdev_core_pick_tx(struct net_device * dev, struct sk_buff * skb, struct net_device * sb_dev)
```

```json
{
  "name": "netdev_core_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593767248,
      "name": "netdev_core_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:4060",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593767248,
      "name": "netdev_core_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
struct netdev_queue * netdev_core_pick_tx(struct net_device * dev, struct sk_buff * skb, struct net_device * sb_dev)
```

```json
{
  "name": "netdev_core_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594546464,
      "name": "netdev_core_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:4210",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594546464,
      "name": "netdev_core_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct netdev_queue * netdev_core_pick_tx(struct net_device * dev, struct sk_buff * skb, struct net_device * sb_dev)
```

```json
{
  "name": "netdev_core_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502023320,
      "name": "netdev_core_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:3644",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502023320,
      "name": "netdev_core_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
struct netdev_queue * netdev_core_pick_tx(struct net_device * dev, struct sk_buff * skb, struct net_device * sb_dev)
```

```json
{
  "name": "netdev_core_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234775272,
      "name": "netdev_core_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:3644",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234775272,
      "name": "netdev_core_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
struct netdev_queue * netdev_core_pick_tx(struct net_device * dev, struct sk_buff * skb, struct net_device * sb_dev)
```

```json
{
  "name": "netdev_core_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295465376,
      "name": "netdev_core_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:3644",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295465376,
      "name": "netdev_core_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
struct netdev_queue * netdev_core_pick_tx(struct net_device * dev, struct sk_buff * skb, struct net_device * sb_dev)
```

```json
{
  "name": "netdev_core_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278313416,
      "name": "netdev_core_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:3644",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278313416,
      "name": "netdev_core_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct netdev_queue * netdev_core_pick_tx(struct net_device * dev, struct sk_buff * skb, struct net_device * sb_dev)
```

```json
{
  "name": "netdev_core_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_core_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:3644",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588125137,
      "name": "netdev_core_pick_tx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071588099040,
      "name": "netdev_core_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
struct netdev_queue * netdev_core_pick_tx(struct net_device * dev, struct sk_buff * skb, struct net_device * sb_dev)
```

```json
{
  "name": "netdev_core_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_core_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:3644",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587837969,
      "name": "netdev_core_pick_tx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071587811952,
      "name": "netdev_core_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
struct netdev_queue * netdev_core_pick_tx(struct net_device * dev, struct sk_buff * skb, struct net_device * sb_dev)
```

```json
{
  "name": "netdev_core_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_core_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:3644",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588456961,
      "name": "netdev_core_pick_tx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071588430816,
      "name": "netdev_core_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
struct netdev_queue * netdev_core_pick_tx(struct net_device * dev, struct sk_buff * skb, struct net_device * sb_dev)
```

```json
{
  "name": "netdev_core_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_core_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:3644",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588593873,
      "name": "netdev_core_pick_tx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071588567152,
      "name": "netdev_core_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct netdev_queue * netdev_core_pick_tx(struct net_device * dev, struct sk_buff * skb, struct net_device * sb_dev)
```
</details>
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
