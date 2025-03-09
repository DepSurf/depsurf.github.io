# Function: <code>wq_update_unbound_numa</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void wq_update_unbound_numa(struct workqueue_struct * wq, int cpu, bool online)
```

```json
{
  "name": "wq_update_unbound_numa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579482944,
      "name": "wq_update_unbound_numa",
      "external": false,
      "loc": "kernel/workqueue.c:3687",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_cpu_up_callback",
        "kernel/workqueue.c:workqueue_cpu_down_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579482944,
      "name": "wq_update_unbound_numa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 443
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
void wq_update_unbound_numa(struct workqueue_struct * wq, int cpu, bool online)
```

```json
{
  "name": "wq_update_unbound_numa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579496816,
      "name": "wq_update_unbound_numa",
      "external": false,
      "loc": "kernel/workqueue.c:3785",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_offline_cpu",
        "kernel/workqueue.c:workqueue_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579496816,
      "name": "wq_update_unbound_numa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 443
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
void wq_update_unbound_numa(struct workqueue_struct * wq, int cpu, bool online)
```

```json
{
  "name": "wq_update_unbound_numa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579517056,
      "name": "wq_update_unbound_numa",
      "external": false,
      "loc": "kernel/workqueue.c:3813",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_offline_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579517056,
      "name": "wq_update_unbound_numa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
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
void wq_update_unbound_numa(struct workqueue_struct * wq, int cpu, bool online)
```

```json
{
  "name": "wq_update_unbound_numa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579504976,
      "name": "wq_update_unbound_numa",
      "external": false,
      "loc": "kernel/workqueue.c:3822",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_offline_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579504976,
      "name": "wq_update_unbound_numa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
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
void wq_update_unbound_numa(struct workqueue_struct * wq, int cpu, bool online)
```

```json
{
  "name": "wq_update_unbound_numa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579531712,
      "name": "wq_update_unbound_numa",
      "external": false,
      "loc": "kernel/workqueue.c:3833",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_offline_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579531712,
      "name": "wq_update_unbound_numa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 499
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
void wq_update_unbound_numa(struct workqueue_struct * wq, int cpu, bool online)
```

```json
{
  "name": "wq_update_unbound_numa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wq_update_unbound_numa",
      "external": false,
      "loc": "kernel/workqueue.c:3906",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_offline_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579559200,
      "name": "wq_update_unbound_numa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
    },
    {
      "addr": 18446744071579566747,
      "name": "wq_update_unbound_numa.cold.47",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void wq_update_unbound_numa(struct workqueue_struct * wq, int cpu, bool online)
```

```json
{
  "name": "wq_update_unbound_numa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wq_update_unbound_numa",
      "external": false,
      "loc": "kernel/workqueue.c:3929",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_offline_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579596416,
      "name": "wq_update_unbound_numa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
    },
    {
      "addr": 18446744071579603931,
      "name": "wq_update_unbound_numa.cold.48",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void wq_update_unbound_numa(struct workqueue_struct * wq, int cpu, bool online)
```

```json
{
  "name": "wq_update_unbound_numa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wq_update_unbound_numa",
      "external": false,
      "loc": "kernel/workqueue.c:4069",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_offline_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579617824,
      "name": "wq_update_unbound_numa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 495
    },
    {
      "addr": 18446744071579627588,
      "name": "wq_update_unbound_numa.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void wq_update_unbound_numa(struct workqueue_struct * wq, int cpu, bool online)
```

```json
{
  "name": "wq_update_unbound_numa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wq_update_unbound_numa",
      "external": false,
      "loc": "kernel/workqueue.c:4082",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_offline_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579645808,
      "name": "wq_update_unbound_numa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
    },
    {
      "addr": 18446744071579653423,
      "name": "wq_update_unbound_numa.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void wq_update_unbound_numa(struct workqueue_struct * wq, int cpu, bool online)
```

```json
{
  "name": "wq_update_unbound_numa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wq_update_unbound_numa",
      "external": false,
      "loc": "kernel/workqueue.c:4091",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_offline_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579676800,
      "name": "wq_update_unbound_numa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
    },
    {
      "addr": 18446744071579685082,
      "name": "wq_update_unbound_numa.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void wq_update_unbound_numa(struct workqueue_struct * wq, int cpu, bool online)
```

```json
{
  "name": "wq_update_unbound_numa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wq_update_unbound_numa",
      "external": false,
      "loc": "kernel/workqueue.c:4104",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_offline_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579656624,
      "name": "wq_update_unbound_numa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
    },
    {
      "addr": 18446744071591280443,
      "name": "wq_update_unbound_numa.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void wq_update_unbound_numa(struct workqueue_struct * wq, int cpu, bool online)
```

```json
{
  "name": "wq_update_unbound_numa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wq_update_unbound_numa",
      "external": false,
      "loc": "kernel/workqueue.c:4111",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_offline_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579663072,
      "name": "wq_update_unbound_numa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 582
    },
    {
      "addr": 18446744071591223384,
      "name": "wq_update_unbound_numa.cold",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void wq_update_unbound_numa(struct workqueue_struct * wq, int cpu, bool online)
```

```json
{
  "name": "wq_update_unbound_numa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wq_update_unbound_numa",
      "external": false,
      "loc": "kernel/workqueue.c:4150",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_offline_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579740240,
      "name": "wq_update_unbound_numa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 621
    },
    {
      "addr": 18446744071592104583,
      "name": "wq_update_unbound_numa.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void wq_update_unbound_numa(struct workqueue_struct * wq, int cpu, bool online)
```

```json
{
  "name": "wq_update_unbound_numa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wq_update_unbound_numa",
      "external": false,
      "loc": "kernel/workqueue.c:4133",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_offline_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579844544,
      "name": "wq_update_unbound_numa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 575
    },
    {
      "addr": 18446744071593872318,
      "name": "wq_update_unbound_numa.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
void wq_update_unbound_numa(struct workqueue_struct * wq, int cpu, bool online)
```

```json
{
  "name": "wq_update_unbound_numa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wq_update_unbound_numa",
      "external": false,
      "loc": "kernel/workqueue.c:4142",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_offline_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579984416,
      "name": "wq_update_unbound_numa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 587
    },
    {
      "addr": 18446744071595976374,
      "name": "wq_update_unbound_numa.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void wq_update_unbound_numa(struct workqueue_struct * wq, int cpu, bool online)
```

```json
{
  "name": "wq_update_unbound_numa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wq_update_unbound_numa",
      "external": false,
      "loc": "kernel/workqueue.c:4470",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_offline_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580037056,
      "name": "wq_update_unbound_numa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 587
    },
    {
      "addr": 18446744071596493900,
      "name": "wq_update_unbound_numa.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void wq_update_unbound_numa(struct workqueue_struct * wq, int cpu, bool online)
```

```json
{
  "name": "wq_update_unbound_numa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490816648,
      "name": "wq_update_unbound_numa",
      "external": false,
      "loc": "kernel/workqueue.c:4082",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_offline_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490816648,
      "name": "wq_update_unbound_numa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
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
void wq_update_unbound_numa(struct workqueue_struct * wq, int cpu, bool online)
```

```json
{
  "name": "wq_update_unbound_numa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224850996,
      "name": "wq_update_unbound_numa",
      "external": false,
      "loc": "kernel/workqueue.c:4082",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3224850996,
      "name": "wq_update_unbound_numa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void wq_update_unbound_numa(struct workqueue_struct * wq, int cpu, bool online)
```

```json
{
  "name": "wq_update_unbound_numa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283649200,
      "name": "wq_update_unbound_numa",
      "external": false,
      "loc": "kernel/workqueue.c:4082",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_offline_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283649200,
      "name": "wq_update_unbound_numa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 720
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
void wq_update_unbound_numa(struct workqueue_struct * wq, int cpu, bool online)
```

```json
{
  "name": "wq_update_unbound_numa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271491918,
      "name": "wq_update_unbound_numa",
      "external": false,
      "loc": "kernel/workqueue.c:4082",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271491918,
      "name": "wq_update_unbound_numa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
void wq_update_unbound_numa(struct workqueue_struct * wq, int cpu, bool online)
```

```json
{
  "name": "wq_update_unbound_numa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wq_update_unbound_numa",
      "external": false,
      "loc": "kernel/workqueue.c:4082",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_offline_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579622112,
      "name": "wq_update_unbound_numa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
    },
    {
      "addr": 18446744071579629727,
      "name": "wq_update_unbound_numa.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void wq_update_unbound_numa(struct workqueue_struct * wq, int cpu, bool online)
```

```json
{
  "name": "wq_update_unbound_numa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wq_update_unbound_numa",
      "external": false,
      "loc": "kernel/workqueue.c:4082",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_offline_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579550480,
      "name": "wq_update_unbound_numa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
    },
    {
      "addr": 18446744071579558079,
      "name": "wq_update_unbound_numa.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void wq_update_unbound_numa(struct workqueue_struct * wq, int cpu, bool online)
```

```json
{
  "name": "wq_update_unbound_numa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wq_update_unbound_numa",
      "external": false,
      "loc": "kernel/workqueue.c:4082",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_offline_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579619392,
      "name": "wq_update_unbound_numa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
    },
    {
      "addr": 18446744071579627007,
      "name": "wq_update_unbound_numa.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void wq_update_unbound_numa(struct workqueue_struct * wq, int cpu, bool online)
```

```json
{
  "name": "wq_update_unbound_numa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wq_update_unbound_numa",
      "external": false,
      "loc": "kernel/workqueue.c:4082",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_offline_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579653056,
      "name": "wq_update_unbound_numa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 501
    },
    {
      "addr": 18446744071579660650,
      "name": "wq_update_unbound_numa.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void wq_update_unbound_numa(struct workqueue_struct * wq, int cpu, bool online)
```
</details>
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
