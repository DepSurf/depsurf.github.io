# Function: <code>__skb_array_destroy_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __skb_array_destroy_skb(void * ptr)
```

```json
{
  "name": "__skb_array_destroy_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585465996,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:154",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_queue_resize",
        "drivers/net/tun.c:__tun_detach"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585451312,
      "name": "__skb_array_destroy_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __skb_array_destroy_skb(void * ptr)
```

```json
{
  "name": "__skb_array_destroy_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585669995,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:154",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_queue_resize",
        "drivers/net/tun.c:__tun_detach"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585655408,
      "name": "__skb_array_destroy_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __skb_array_destroy_skb(void * ptr)
```

```json
{
  "name": "__skb_array_destroy_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585756856,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:179",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_device_event",
        "drivers/net/tun.c:__tun_detach"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585741904,
      "name": "__skb_array_destroy_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __skb_array_destroy_skb(void * ptr)
```

```json
{
  "name": "__skb_array_destroy_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586194821,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:179",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_device_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586175616,
      "name": "__skb_array_destroy_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __skb_array_destroy_skb(void * ptr)
```

```json
{
  "name": "__skb_array_destroy_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586429263,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:189",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_ptr_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588070799,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:189",
      "file": "net/sched/sch_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588068160,
      "name": "__skb_array_destroy_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __skb_array_destroy_skb(void * ptr)
```

```json
{
  "name": "__skb_array_destroy_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586574511,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:189",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_ptr_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588247490,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:189",
      "file": "net/sched/sch_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588245056,
      "name": "__skb_array_destroy_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __skb_array_destroy_skb(void * ptr)
```

```json
{
  "name": "__skb_array_destroy_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586826095,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:185",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_ptr_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588638122,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:185",
      "file": "net/sched/sch_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588636016,
      "name": "__skb_array_destroy_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __skb_array_destroy_skb(void * ptr)
```

```json
{
  "name": "__skb_array_destroy_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586972191,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:185",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_ptr_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588860490,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:185",
      "file": "net/sched/sch_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588858384,
      "name": "__skb_array_destroy_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __skb_array_destroy_skb(void * ptr)
```

```json
{
  "name": "__skb_array_destroy_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587819483,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:185",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:tun_queue_purge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589741728,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:185",
      "file": "net/sched/sch_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589741728,
      "name": "__skb_array_destroy_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
void __skb_array_destroy_skb(void * ptr)
```

```json
{
  "name": "__skb_array_destroy_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587876608,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:185",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:tun_queue_purge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589774816,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:185",
      "file": "net/sched/sch_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589774816,
      "name": "__skb_array_destroy_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
void __skb_array_destroy_skb(void * ptr)
```

```json
{
  "name": "__skb_array_destroy_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587755392,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:185",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:tun_queue_purge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589678448,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:185",
      "file": "net/sched/sch_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589678448,
      "name": "__skb_array_destroy_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
void __skb_array_destroy_skb(void * ptr)
```

```json
{
  "name": "__skb_array_destroy_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588352991,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:185",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:tun_queue_purge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590435312,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:185",
      "file": "net/sched/sch_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590435312,
      "name": "__skb_array_destroy_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
void __skb_array_destroy_skb(void * ptr)
```

```json
{
  "name": "__skb_array_destroy_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589741192,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:185",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:tun_queue_purge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592037072,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:185",
      "file": "net/sched/sch_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592037072,
      "name": "__skb_array_destroy_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __skb_array_destroy_skb(void * ptr)
```

```json
{
  "name": "__skb_array_destroy_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591359704,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:185",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:tun_queue_purge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593854240,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:185",
      "file": "net/sched/sch_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593854240,
      "name": "__skb_array_destroy_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __skb_array_destroy_skb(void * ptr)
```

```json
{
  "name": "__skb_array_destroy_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591720376,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:185",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:tun_queue_purge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594228928,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:185",
      "file": "net/sched/sch_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594228928,
      "name": "__skb_array_destroy_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __skb_array_destroy_skb(void * ptr)
```

```json
{
  "name": "__skb_array_destroy_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592464056,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:185",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:tun_queue_purge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595026272,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:185",
      "file": "net/sched/sch_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595026272,
      "name": "__skb_array_destroy_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __skb_array_destroy_skb(void * ptr)
```

```json
{
  "name": "__skb_array_destroy_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499964356,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:185",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_ptr_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502441792,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:185",
      "file": "net/sched/sch_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502441792,
      "name": "__skb_array_destroy_skb",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline ❓</summary>

```c
void __skb_array_destroy_skb(void * ptr)
```

```json
{
  "name": "__skb_array_destroy_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232502812,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:185",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_ptr_free"
      ],
      "caller_func": []
    },
    {
      "addr": 3235163636,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:185",
      "file": "net/sched/sch_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235160608,
      "name": "__skb_array_destroy_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
void __skb_array_destroy_skb(void * ptr)
```

```json
{
  "name": "__skb_array_destroy_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293290876,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:185",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_ptr_free"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295993536,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:185",
      "file": "net/sched/sch_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295991296,
      "name": "__skb_array_destroy_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __skb_array_destroy_skb(void * ptr)
```

```json
{
  "name": "__skb_array_destroy_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277043114,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:185",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_ptr_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278633464,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:185",
      "file": "net/sched/sch_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278631242,
      "name": "__skb_array_destroy_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __skb_array_destroy_skb(void * ptr)
```

```json
{
  "name": "__skb_array_destroy_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586729199,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:185",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_ptr_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588466874,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:185",
      "file": "net/sched/sch_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588464768,
      "name": "__skb_array_destroy_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __skb_array_destroy_skb(void * ptr)
```

```json
{
  "name": "__skb_array_destroy_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586596415,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:185",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_ptr_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588178874,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:185",
      "file": "net/sched/sch_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588176768,
      "name": "__skb_array_destroy_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __skb_array_destroy_skb(void * ptr)
```

```json
{
  "name": "__skb_array_destroy_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586926751,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:185",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_ptr_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588799050,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:185",
      "file": "net/sched/sch_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588796944,
      "name": "__skb_array_destroy_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __skb_array_destroy_skb(void * ptr)
```

```json
{
  "name": "__skb_array_destroy_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587033199,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:185",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_ptr_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588940363,
      "name": "__skb_array_destroy_skb",
      "external": false,
      "loc": "include/linux/skb_array.h:185",
      "file": "net/sched/sch_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588937600,
      "name": "__skb_array_destroy_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
void __skb_array_destroy_skb(void * ptr)
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
