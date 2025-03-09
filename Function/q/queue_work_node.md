# Function: <code>queue_work_node</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool queue_work_node(int node, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "queue_work_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579612032,
      "name": "queue_work_node",
      "external": true,
      "loc": "kernel/workqueue.c:1580",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/async.c:async_schedule_node_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579612032,
      "name": "queue_work_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
bool queue_work_node(int node, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "queue_work_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579637232,
      "name": "queue_work_node",
      "external": true,
      "loc": "kernel/workqueue.c:1583",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/async.c:async_schedule_node_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579637232,
      "name": "queue_work_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
bool queue_work_node(int node, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "queue_work_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579673328,
      "name": "queue_work_node",
      "external": true,
      "loc": "kernel/workqueue.c:1580",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/async.c:async_schedule_node_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579673328,
      "name": "queue_work_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
bool queue_work_node(int node, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "queue_work_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579653152,
      "name": "queue_work_node",
      "external": true,
      "loc": "kernel/workqueue.c:1586",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/async.c:async_schedule_node_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579653152,
      "name": "queue_work_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
bool queue_work_node(int node, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "queue_work_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579659536,
      "name": "queue_work_node",
      "external": true,
      "loc": "kernel/workqueue.c:1587",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/async.c:async_schedule_node_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579659536,
      "name": "queue_work_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
bool queue_work_node(int node, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "queue_work_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "queue_work_node",
      "external": true,
      "loc": "kernel/workqueue.c:1617",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/async.c:async_schedule_node_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592104489,
      "name": "queue_work_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579736512,
      "name": "queue_work_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
bool queue_work_node(int node, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "queue_work_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "queue_work_node",
      "external": true,
      "loc": "kernel/workqueue.c:1607",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/async.c:async_schedule_node_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593871897,
      "name": "queue_work_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579834880,
      "name": "queue_work_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
bool queue_work_node(int node, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "queue_work_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "queue_work_node",
      "external": true,
      "loc": "kernel/workqueue.c:1607",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/async.c:async_schedule_node_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595976210,
      "name": "queue_work_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579980048,
      "name": "queue_work_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
bool queue_work_node(int node, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "queue_work_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "queue_work_node",
      "external": true,
      "loc": "kernel/workqueue.c:1809",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/async.c:async_schedule_node_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596493694,
      "name": "queue_work_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580029152,
      "name": "queue_work_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
bool queue_work_node(int node, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "queue_work_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580072080,
      "name": "queue_work_node",
      "external": true,
      "loc": "kernel/workqueue.c:1895",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/async.c:__async_schedule_node_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580072080,
      "name": "queue_work_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
bool queue_work_node(int node, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "queue_work_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490809776,
      "name": "queue_work_node",
      "external": true,
      "loc": "kernel/workqueue.c:1583",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/async.c:async_schedule_node_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490809776,
      "name": "queue_work_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
bool queue_work_node(int node, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "queue_work_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224840524,
      "name": "queue_work_node",
      "external": true,
      "loc": "kernel/workqueue.c:1583",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/async.c:async_schedule_node_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224840524,
      "name": "queue_work_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
bool queue_work_node(int node, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "queue_work_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283627968,
      "name": "queue_work_node",
      "external": true,
      "loc": "kernel/workqueue.c:1583",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/async.c:async_schedule_node_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283627968,
      "name": "queue_work_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
bool queue_work_node(int node, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "queue_work_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271485106,
      "name": "queue_work_node",
      "external": true,
      "loc": "kernel/workqueue.c:1583",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/async.c:async_schedule_node_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271485106,
      "name": "queue_work_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
bool queue_work_node(int node, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "queue_work_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579613536,
      "name": "queue_work_node",
      "external": true,
      "loc": "kernel/workqueue.c:1583",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/async.c:async_schedule_node_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579613536,
      "name": "queue_work_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
bool queue_work_node(int node, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "queue_work_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579542528,
      "name": "queue_work_node",
      "external": true,
      "loc": "kernel/workqueue.c:1583",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/async.c:async_schedule_node_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579542528,
      "name": "queue_work_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
bool queue_work_node(int node, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "queue_work_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579610816,
      "name": "queue_work_node",
      "external": true,
      "loc": "kernel/workqueue.c:1583",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/async.c:async_schedule_node_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579610816,
      "name": "queue_work_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
bool queue_work_node(int node, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "queue_work_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579641712,
      "name": "queue_work_node",
      "external": true,
      "loc": "kernel/workqueue.c:1583",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/async.c:async_schedule_node_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579641712,
      "name": "queue_work_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
bool queue_work_node(int node, struct workqueue_struct * wq, struct work_struct * work)
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
