# Function: <code>create_worker</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct worker * create_worker(struct worker_pool * pool)
```

```json
{
  "name": "create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579475168,
      "name": "create_worker",
      "external": false,
      "loc": "kernel/workqueue.c:1697",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:workqueue_cpu_up_callback",
        "kernel/workqueue.c:init_workqueues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579475168,
      "name": "create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
struct worker * create_worker(struct worker_pool * pool)
```

```json
{
  "name": "create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579488880,
      "name": "create_worker",
      "external": false,
      "loc": "kernel/workqueue.c:1753",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:init_workqueues",
        "kernel/workqueue.c:workqueue_prepare_cpu",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:worker_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579488880,
      "name": "create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
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
struct worker * create_worker(struct worker_pool * pool)
```

```json
{
  "name": "create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579508192,
      "name": "create_worker",
      "external": false,
      "loc": "kernel/workqueue.c:1755",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_prepare_cpu",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:workqueue_init",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579508192,
      "name": "create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
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
struct worker * create_worker(struct worker_pool * pool)
```

```json
{
  "name": "create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579497200,
      "name": "create_worker",
      "external": false,
      "loc": "kernel/workqueue.c:1754",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_prepare_cpu",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:workqueue_init",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579497200,
      "name": "create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
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
struct worker * create_worker(struct worker_pool * pool)
```

```json
{
  "name": "create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579523872,
      "name": "create_worker",
      "external": false,
      "loc": "kernel/workqueue.c:1755",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_prepare_cpu",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:workqueue_init",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579523872,
      "name": "create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
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
struct worker * create_worker(struct worker_pool * pool)
```

```json
{
  "name": "create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579548816,
      "name": "create_worker",
      "external": false,
      "loc": "kernel/workqueue.c:1790",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_prepare_cpu",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:workqueue_init",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579548816,
      "name": "create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
struct worker * create_worker(struct worker_pool * pool)
```

```json
{
  "name": "create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579588416,
      "name": "create_worker",
      "external": false,
      "loc": "kernel/workqueue.c:1810",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_prepare_cpu",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:workqueue_init",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579588416,
      "name": "create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct worker * create_worker(struct worker_pool * pool)
```

```json
{
  "name": "create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579612720,
      "name": "create_worker",
      "external": false,
      "loc": "kernel/workqueue.c:1906",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_prepare_cpu",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:workqueue_init",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579612720,
      "name": "create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct worker * create_worker(struct worker_pool * pool)
```

```json
{
  "name": "create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579637920,
      "name": "create_worker",
      "external": false,
      "loc": "kernel/workqueue.c:1909",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_prepare_cpu",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:workqueue_init",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579637920,
      "name": "create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
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
struct worker * create_worker(struct worker_pool * pool)
```

```json
{
  "name": "create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579666288,
      "name": "create_worker",
      "external": false,
      "loc": "kernel/workqueue.c:1906",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_prepare_cpu",
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/workqueue.c:maybe_create_worker",
        "kernel/workqueue.c:workqueue_init",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579666288,
      "name": "create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
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
struct worker * create_worker(struct worker_pool * pool)
```

```json
{
  "name": "create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579646160,
      "name": "create_worker",
      "external": false,
      "loc": "kernel/workqueue.c:1912",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_prepare_cpu",
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/workqueue.c:maybe_create_worker",
        "kernel/workqueue.c:workqueue_init",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579646160,
      "name": "create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
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
struct worker * create_worker(struct worker_pool * pool)
```

```json
{
  "name": "create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579652624,
      "name": "create_worker",
      "external": false,
      "loc": "kernel/workqueue.c:1913",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_prepare_cpu",
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:workqueue_init",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579652624,
      "name": "create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct worker * create_worker(struct worker_pool * pool)
```

```json
{
  "name": "create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579729408,
      "name": "create_worker",
      "external": false,
      "loc": "kernel/workqueue.c:1943",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_prepare_cpu",
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:workqueue_init",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579729408,
      "name": "create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
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
struct worker * create_worker(struct worker_pool * pool)
```

```json
{
  "name": "create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579828240,
      "name": "create_worker",
      "external": false,
      "loc": "kernel/workqueue.c:1926",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_prepare_cpu",
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:workqueue_init",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579828240,
      "name": "create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
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
struct worker * create_worker(struct worker_pool * pool)
```

```json
{
  "name": "create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579965904,
      "name": "create_worker",
      "external": false,
      "loc": "kernel/workqueue.c:1926",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_prepare_cpu",
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:workqueue_init",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579965904,
      "name": "create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
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
struct worker * create_worker(struct worker_pool * pool)
```

```json
{
  "name": "create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_worker",
      "external": false,
      "loc": "kernel/workqueue.c:2128",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_prepare_cpu",
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:workqueue_init",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580017728,
      "name": "create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 599
    },
    {
      "addr": 18446744071596493383,
      "name": "create_worker.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
struct worker * create_worker(struct worker_pool * pool)
```

```json
{
  "name": "create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_worker",
      "external": false,
      "loc": "kernel/workqueue.c:2168",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_prepare_cpu",
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:workqueue_init",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580061280,
      "name": "create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
    },
    {
      "addr": 18446744071597390241,
      "name": "create_worker.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
struct worker * create_worker(struct worker_pool * pool)
```

```json
{
  "name": "create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490803776,
      "name": "create_worker",
      "external": false,
      "loc": "kernel/workqueue.c:1909",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_prepare_cpu",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:workqueue_init",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490803776,
      "name": "create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
struct worker * create_worker(struct worker_pool * pool)
```

```json
{
  "name": "create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224835104,
      "name": "create_worker",
      "external": false,
      "loc": "kernel/workqueue.c:1909",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_prepare_cpu",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:workqueue_init",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224835104,
      "name": "create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
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
struct worker * create_worker(struct worker_pool * pool)
```

```json
{
  "name": "create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283638400,
      "name": "create_worker",
      "external": false,
      "loc": "kernel/workqueue.c:1909",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_prepare_cpu",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:workqueue_init",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283638400,
      "name": "create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 624
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
struct worker * create_worker(struct worker_pool * pool)
```

```json
{
  "name": "create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271481608,
      "name": "create_worker",
      "external": false,
      "loc": "kernel/workqueue.c:1909",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_prepare_cpu",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:workqueue_init",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271481608,
      "name": "create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct worker * create_worker(struct worker_pool * pool)
```

```json
{
  "name": "create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579614224,
      "name": "create_worker",
      "external": false,
      "loc": "kernel/workqueue.c:1909",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_prepare_cpu",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:workqueue_init",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579614224,
      "name": "create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct worker * create_worker(struct worker_pool * pool)
```

```json
{
  "name": "create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579539744,
      "name": "create_worker",
      "external": false,
      "loc": "kernel/workqueue.c:1909",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_prepare_cpu",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:workqueue_init",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579539744,
      "name": "create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct worker * create_worker(struct worker_pool * pool)
```

```json
{
  "name": "create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579611504,
      "name": "create_worker",
      "external": false,
      "loc": "kernel/workqueue.c:1909",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_prepare_cpu",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:workqueue_init",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579611504,
      "name": "create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct worker * create_worker(struct worker_pool * pool)
```

```json
{
  "name": "create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579636736,
      "name": "create_worker",
      "external": false,
      "loc": "kernel/workqueue.c:1909",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_prepare_cpu",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:workqueue_init",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579636736,
      "name": "create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 413
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
