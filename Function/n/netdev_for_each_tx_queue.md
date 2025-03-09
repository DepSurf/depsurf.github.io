# Function: <code>netdev_for_each_tx_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netdev_for_each_tx_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586298880,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:1918",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:alloc_netdev_mqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586454014,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:1918",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:dev_init_scheduler",
        "net/sched/sch_generic.c:dev_shutdown"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netdev_for_each_tx_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586727075,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:1958",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:alloc_netdev_mqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586901454,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:1958",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_init_scheduler",
        "net/sched/sch_generic.c:dev_deactivate_many"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netdev_for_each_tx_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586912935,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:1940",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:alloc_netdev_mqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587095630,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:1940",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_init_scheduler",
        "net/sched/sch_generic.c:dev_deactivate_many"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netdev_for_each_tx_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587018760,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:1964",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:alloc_netdev_mqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587224222,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:1964",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_init_scheduler",
        "net/sched/sch_generic.c:dev_deactivate_many"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netdev_for_each_tx_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587516503,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:1980",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:alloc_netdev_mqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587739326,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:1980",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_init_scheduler",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:dev_deactivate_many"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netdev_for_each_tx_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587828408,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2048",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:alloc_netdev_mqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588076773,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2048",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_init_scheduler",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:dev_deactivate_many"
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
  "name": "netdev_for_each_tx_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587961064,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2113",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:alloc_netdev_mqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588253365,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2113",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_init_scheduler",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:dev_deactivate_many"
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
  "name": "netdev_for_each_tx_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588275848,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2102",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:alloc_netdev_mqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588644501,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2102",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_init_scheduler",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:dev_deactivate_many"
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
  "name": "netdev_for_each_tx_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588481477,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2132",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:alloc_netdev_mqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588866885,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2132",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_init_scheduler",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:dev_deactivate_many"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void netdev_for_each_tx_queue(struct net_device * dev, void (*)(struct net_device *, struct netdev_queue *, void *) f, void * arg)
```

```json
{
  "name": "netdev_for_each_tx_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589348855,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2200",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:alloc_netdev_mqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589751077,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2200",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_init_scheduler",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:attach_default_qdiscs"
      ],
      "caller_func": [
        "net/sched/sch_generic.c:attach_default_qdiscs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589751253,
      "name": "netdev_for_each_tx_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void netdev_for_each_tx_queue(struct net_device * dev, void (*)(struct net_device *, struct netdev_queue *, void *) f, void * arg)
```

```json
{
  "name": "netdev_for_each_tx_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589357143,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2264",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:alloc_netdev_mqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589784069,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2264",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_init_scheduler",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:attach_default_qdiscs"
      ],
      "caller_func": [
        "net/sched/sch_generic.c:attach_default_qdiscs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591632867,
      "name": "netdev_for_each_tx_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void netdev_for_each_tx_queue(struct net_device * dev, void (*)(struct net_device *, struct netdev_queue *, void *) f, void * arg)
```

```json
{
  "name": "netdev_for_each_tx_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589253542,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2328",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:alloc_netdev_mqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589687957,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2328",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_init_scheduler",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:attach_default_qdiscs"
      ],
      "caller_func": [
        "net/sched/sch_generic.c:attach_default_qdiscs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591576262,
      "name": "netdev_for_each_tx_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void netdev_for_each_tx_queue(struct net_device * dev, void (*)(struct net_device *, struct netdev_queue *, void *) f, void * arg)
```

```json
{
  "name": "netdev_for_each_tx_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589979074,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2348",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:alloc_netdev_mqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590445301,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2348",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_init_scheduler",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:attach_default_qdiscs"
      ],
      "caller_func": [
        "net/sched/sch_generic.c:attach_default_qdiscs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592709243,
      "name": "netdev_for_each_tx_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void netdev_for_each_tx_queue(struct net_device * dev, void (*)(struct net_device *, struct netdev_queue *, void *) f, void * arg)
```

```json
{
  "name": "netdev_for_each_tx_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591504889,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2428",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:alloc_netdev_mqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592047285,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2428",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_init_scheduler",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:dev_activate",
        "net/sched/sch_generic.c:attach_default_qdiscs"
      ],
      "caller_func": [
        "net/sched/sch_generic.c:attach_default_qdiscs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594595551,
      "name": "netdev_for_each_tx_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netdev_for_each_tx_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593274653,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2455",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:alloc_netdev_mqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593865445,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2455",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_init_scheduler",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:dev_activate",
        "net/sched/sch_generic.c:attach_default_qdiscs",
        "net/sched/sch_generic.c:attach_default_qdiscs",
        "net/sched/sch_generic.c:attach_default_qdiscs"
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
  "name": "netdev_for_each_tx_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593730501,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2508",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:alloc_netdev_mqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594240357,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2508",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_init_scheduler",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:dev_activate",
        "net/sched/sch_generic.c:attach_default_qdiscs",
        "net/sched/sch_generic.c:attach_default_qdiscs",
        "net/sched/sch_generic.c:attach_default_qdiscs"
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
  "name": "netdev_for_each_tx_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594509944,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2567",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:alloc_netdev_mqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595037701,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2567",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_init_scheduler",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:dev_activate",
        "net/sched/sch_generic.c:attach_default_qdiscs",
        "net/sched/sch_generic.c:attach_default_qdiscs",
        "net/sched/sch_generic.c:attach_default_qdiscs"
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
  "name": "netdev_for_each_tx_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502003824,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2132",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:alloc_netdev_mqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502453628,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2132",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_init_scheduler",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:dev_deactivate_many"
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
  "name": "netdev_for_each_tx_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234753644,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2132",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:alloc_netdev_mqs"
      ],
      "caller_func": []
    },
    {
      "addr": 3235170092,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2132",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_init_scheduler",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:dev_deactivate_many"
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
  "name": "netdev_for_each_tx_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295450080,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2132",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:alloc_netdev_mqs"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296005748,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2132",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_init_scheduler",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:dev_deactivate_many"
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
  "name": "netdev_for_each_tx_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278299350,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2132",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:alloc_netdev_mqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278640198,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2132",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_init_scheduler",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:dev_deactivate_many"
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
  "name": "netdev_for_each_tx_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588088261,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2132",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:alloc_netdev_mqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588473269,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2132",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_init_scheduler",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:dev_deactivate_many"
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
  "name": "netdev_for_each_tx_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587801253,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2132",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:alloc_netdev_mqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588185269,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2132",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_init_scheduler",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:dev_deactivate_many"
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
  "name": "netdev_for_each_tx_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588420037,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2132",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:alloc_netdev_mqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588805445,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2132",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_init_scheduler",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:dev_deactivate_many"
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
  "name": "netdev_for_each_tx_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588545429,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2132",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:alloc_netdev_mqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588946085,
      "name": "netdev_for_each_tx_queue",
      "external": false,
      "loc": "include/linux/netdevice.h:2132",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_init_scheduler",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:dev_deactivate_many"
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void netdev_for_each_tx_queue(struct net_device * dev, void (*)(struct net_device *, struct netdev_queue *, void *) f, void * arg)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void netdev_for_each_tx_queue(struct net_device * dev, void (*)(struct net_device *, struct netdev_queue *, void *) f, void * arg)
```
</details>
</li>
</ul>
