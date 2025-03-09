# Function: <code>sch_direct_xmit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int sch_direct_xmit(struct sk_buff * skb, struct Qdisc * q, struct net_device * dev, struct netdev_queue * txq, spinlock_t * root_lock, bool validate)
```

```json
{
  "name": "sch_direct_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586452448,
      "name": "sch_direct_xmit",
      "external": true,
      "loc": "net/sched/sch_generic.c:149",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/sched/sch_generic.c:__qdisc_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586452448,
      "name": "sch_direct_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
int sch_direct_xmit(struct sk_buff * skb, struct Qdisc * q, struct net_device * dev, struct netdev_queue * txq, spinlock_t * root_lock, bool validate)
```

```json
{
  "name": "sch_direct_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586898416,
      "name": "sch_direct_xmit",
      "external": true,
      "loc": "net/sched/sch_generic.c:166",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/sched/sch_generic.c:__qdisc_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586898416,
      "name": "sch_direct_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
int sch_direct_xmit(struct sk_buff * skb, struct Qdisc * q, struct net_device * dev, struct netdev_queue * txq, spinlock_t * root_lock, bool validate)
```

```json
{
  "name": "sch_direct_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587092608,
      "name": "sch_direct_xmit",
      "external": true,
      "loc": "net/sched/sch_generic.c:166",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/sched/sch_generic.c:__qdisc_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587092608,
      "name": "sch_direct_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
int sch_direct_xmit(struct sk_buff * skb, struct Qdisc * q, struct net_device * dev, struct netdev_queue * txq, spinlock_t * root_lock, bool validate)
```

```json
{
  "name": "sch_direct_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587221168,
      "name": "sch_direct_xmit",
      "external": true,
      "loc": "net/sched/sch_generic.c:166",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/sched/sch_generic.c:__qdisc_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587221168,
      "name": "sch_direct_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
int sch_direct_xmit(struct sk_buff * skb, struct Qdisc * q, struct net_device * dev, struct netdev_queue * txq, spinlock_t * root_lock, bool validate)
```

```json
{
  "name": "sch_direct_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587735616,
      "name": "sch_direct_xmit",
      "external": true,
      "loc": "net/sched/sch_generic.c:171",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/sched/sch_generic.c:__qdisc_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587735616,
      "name": "sch_direct_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
bool sch_direct_xmit(struct sk_buff * skb, struct Qdisc * q, struct net_device * dev, struct netdev_queue * txq, spinlock_t * root_lock, bool validate)
```

```json
{
  "name": "sch_direct_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sch_direct_xmit",
      "external": true,
      "loc": "net/sched/sch_generic.c:299",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/sched/sch_generic.c:__qdisc_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588076940,
      "name": "sch_direct_xmit.cold.57",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071588071456,
      "name": "sch_direct_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 873
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
bool sch_direct_xmit(struct sk_buff * skb, struct Qdisc * q, struct net_device * dev, struct netdev_queue * txq, spinlock_t * root_lock, bool validate)
```

```json
{
  "name": "sch_direct_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sch_direct_xmit",
      "external": true,
      "loc": "net/sched/sch_generic.c:299",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/sched/sch_generic.c:__qdisc_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588253532,
      "name": "sch_direct_xmit.cold.57",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071588248432,
      "name": "sch_direct_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 911
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
bool sch_direct_xmit(struct sk_buff * skb, struct Qdisc * q, struct net_device * dev, struct netdev_queue * txq, spinlock_t * root_lock, bool validate)
```

```json
{
  "name": "sch_direct_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sch_direct_xmit",
      "external": true,
      "loc": "net/sched/sch_generic.c:285",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/sched/sch_generic.c:__qdisc_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588644672,
      "name": "sch_direct_xmit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071588639472,
      "name": "sch_direct_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 825
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
bool sch_direct_xmit(struct sk_buff * skb, struct Qdisc * q, struct net_device * dev, struct netdev_queue * txq, spinlock_t * root_lock, bool validate)
```

```json
{
  "name": "sch_direct_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sch_direct_xmit",
      "external": true,
      "loc": "net/sched/sch_generic.c:285",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/sched/sch_generic.c:__qdisc_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588867059,
      "name": "sch_direct_xmit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071588861840,
      "name": "sch_direct_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 825
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
bool sch_direct_xmit(struct sk_buff * skb, struct Qdisc * q, struct net_device * dev, struct netdev_queue * txq, spinlock_t * root_lock, bool validate)
```

```json
{
  "name": "sch_direct_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sch_direct_xmit",
      "external": true,
      "loc": "net/sched/sch_generic.c:285",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_xmit_skb",
        "net/sched/sch_generic.c:__qdisc_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589751327,
      "name": "sch_direct_xmit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071589747120,
      "name": "sch_direct_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 825
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
bool sch_direct_xmit(struct sk_buff * skb, struct Qdisc * q, struct net_device * dev, struct netdev_queue * txq, spinlock_t * root_lock, bool validate)
```

```json
{
  "name": "sch_direct_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sch_direct_xmit",
      "external": true,
      "loc": "net/sched/sch_generic.c:285",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_xmit_skb",
        "net/sched/sch_generic.c:__qdisc_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591632941,
      "name": "sch_direct_xmit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071589780176,
      "name": "sch_direct_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 825
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
bool sch_direct_xmit(struct sk_buff * skb, struct Qdisc * q, struct net_device * dev, struct netdev_queue * txq, spinlock_t * root_lock, bool validate)
```

```json
{
  "name": "sch_direct_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sch_direct_xmit",
      "external": true,
      "loc": "net/sched/sch_generic.c:308",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_xmit_skb",
        "net/sched/sch_generic.c:__qdisc_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591576336,
      "name": "sch_direct_xmit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071589683984,
      "name": "sch_direct_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 866
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
bool sch_direct_xmit(struct sk_buff * skb, struct Qdisc * q, struct net_device * dev, struct netdev_queue * txq, spinlock_t * root_lock, bool validate)
```

```json
{
  "name": "sch_direct_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sch_direct_xmit",
      "external": true,
      "loc": "net/sched/sch_generic.c:314",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/sched/sch_generic.c:__qdisc_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592709337,
      "name": "sch_direct_xmit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071590441168,
      "name": "sch_direct_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 902
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
bool sch_direct_xmit(struct sk_buff * skb, struct Qdisc * q, struct net_device * dev, struct netdev_queue * txq, spinlock_t * root_lock, bool validate)
```

```json
{
  "name": "sch_direct_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sch_direct_xmit",
      "external": true,
      "loc": "net/sched/sch_generic.c:314",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/sched/sch_generic.c:__qdisc_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594595657,
      "name": "sch_direct_xmit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071592043216,
      "name": "sch_direct_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 809
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
bool sch_direct_xmit(struct sk_buff * skb, struct Qdisc * q, struct net_device * dev, struct netdev_queue * txq, spinlock_t * root_lock, bool validate)
```

```json
{
  "name": "sch_direct_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sch_direct_xmit",
      "external": true,
      "loc": "net/sched/sch_generic.c:314",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/sched/sch_generic.c:__qdisc_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596332413,
      "name": "sch_direct_xmit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071593860800,
      "name": "sch_direct_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 833
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
bool sch_direct_xmit(struct sk_buff * skb, struct Qdisc * q, struct net_device * dev, struct netdev_queue * txq, spinlock_t * root_lock, bool validate)
```

```json
{
  "name": "sch_direct_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sch_direct_xmit",
      "external": true,
      "loc": "net/sched/sch_generic.c:314",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/sched/sch_generic.c:__qdisc_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596861223,
      "name": "sch_direct_xmit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071594235696,
      "name": "sch_direct_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 833
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
bool sch_direct_xmit(struct sk_buff * skb, struct Qdisc * q, struct net_device * dev, struct netdev_queue * txq, spinlock_t * root_lock, bool validate)
```

```json
{
  "name": "sch_direct_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sch_direct_xmit",
      "external": true,
      "loc": "net/sched/sch_generic.c:314",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/sched/sch_generic.c:__qdisc_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597786309,
      "name": "sch_direct_xmit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071595033040,
      "name": "sch_direct_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 837
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
bool sch_direct_xmit(struct sk_buff * skb, struct Qdisc * q, struct net_device * dev, struct netdev_queue * txq, spinlock_t * root_lock, bool validate)
```

```json
{
  "name": "sch_direct_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502447208,
      "name": "sch_direct_xmit",
      "external": true,
      "loc": "net/sched/sch_generic.c:285",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/sched/sch_generic.c:__qdisc_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502447208,
      "name": "sch_direct_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1352
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
bool sch_direct_xmit(struct sk_buff * skb, struct Qdisc * q, struct net_device * dev, struct netdev_queue * txq, spinlock_t * root_lock, bool validate)
```

```json
{
  "name": "sch_direct_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235164312,
      "name": "sch_direct_xmit",
      "external": true,
      "loc": "net/sched/sch_generic.c:285",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/sched/sch_generic.c:__qdisc_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235164312,
      "name": "sch_direct_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1108
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
bool sch_direct_xmit(struct sk_buff * skb, struct Qdisc * q, struct net_device * dev, struct netdev_queue * txq, spinlock_t * root_lock, bool validate)
```

```json
{
  "name": "sch_direct_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295997872,
      "name": "sch_direct_xmit",
      "external": true,
      "loc": "net/sched/sch_generic.c:285",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/sched/sch_generic.c:__qdisc_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295997872,
      "name": "sch_direct_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1388
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
bool sch_direct_xmit(struct sk_buff * skb, struct Qdisc * q, struct net_device * dev, struct netdev_queue * txq, spinlock_t * root_lock, bool validate)
```

```json
{
  "name": "sch_direct_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278635034,
      "name": "sch_direct_xmit",
      "external": true,
      "loc": "net/sched/sch_generic.c:285",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/sched/sch_generic.c:__qdisc_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278635034,
      "name": "sch_direct_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1022
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
bool sch_direct_xmit(struct sk_buff * skb, struct Qdisc * q, struct net_device * dev, struct netdev_queue * txq, spinlock_t * root_lock, bool validate)
```

```json
{
  "name": "sch_direct_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sch_direct_xmit",
      "external": true,
      "loc": "net/sched/sch_generic.c:285",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/sched/sch_generic.c:__qdisc_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588473443,
      "name": "sch_direct_xmit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071588468224,
      "name": "sch_direct_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 825
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
bool sch_direct_xmit(struct sk_buff * skb, struct Qdisc * q, struct net_device * dev, struct netdev_queue * txq, spinlock_t * root_lock, bool validate)
```

```json
{
  "name": "sch_direct_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sch_direct_xmit",
      "external": true,
      "loc": "net/sched/sch_generic.c:285",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/sched/sch_generic.c:__qdisc_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588185443,
      "name": "sch_direct_xmit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071588180224,
      "name": "sch_direct_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 825
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
bool sch_direct_xmit(struct sk_buff * skb, struct Qdisc * q, struct net_device * dev, struct netdev_queue * txq, spinlock_t * root_lock, bool validate)
```

```json
{
  "name": "sch_direct_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sch_direct_xmit",
      "external": true,
      "loc": "net/sched/sch_generic.c:285",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/sched/sch_generic.c:__qdisc_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588805619,
      "name": "sch_direct_xmit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071588800400,
      "name": "sch_direct_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 825
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
bool sch_direct_xmit(struct sk_buff * skb, struct Qdisc * q, struct net_device * dev, struct netdev_queue * txq, spinlock_t * root_lock, bool validate)
```

```json
{
  "name": "sch_direct_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sch_direct_xmit",
      "external": true,
      "loc": "net/sched/sch_generic.c:285",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/sched/sch_generic.c:__qdisc_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588946259,
      "name": "sch_direct_xmit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071588941056,
      "name": "sch_direct_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 831
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
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
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
