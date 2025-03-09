# Function: <code>__queue_work</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __queue_work(int cpu, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "__queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579467936,
      "name": "__queue_work",
      "external": false,
      "loc": "kernel/workqueue.c:1307",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:delayed_work_timer_fn",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/workqueue.c:queue_work_on",
        "kernel/workqueue.c:flush_delayed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579467936,
      "name": "__queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 935
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
void __queue_work(int cpu, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "__queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579481568,
      "name": "__queue_work",
      "external": false,
      "loc": "kernel/workqueue.c:1361",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/workqueue.c:delayed_work_timer_fn",
        "kernel/workqueue.c:queue_work_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579481568,
      "name": "__queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1121
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
void __queue_work(int cpu, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "__queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579501840,
      "name": "__queue_work",
      "external": false,
      "loc": "kernel/workqueue.c:1363",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/workqueue.c:delayed_work_timer_fn",
        "kernel/workqueue.c:queue_work_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579501840,
      "name": "__queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1126
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
void __queue_work(int cpu, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "__queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579490080,
      "name": "__queue_work",
      "external": false,
      "loc": "kernel/workqueue.c:1363",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/workqueue.c:delayed_work_timer_fn",
        "kernel/workqueue.c:queue_work_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579490080,
      "name": "__queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1024
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
void __queue_work(int cpu, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "__queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579516512,
      "name": "__queue_work",
      "external": false,
      "loc": "kernel/workqueue.c:1365",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/workqueue.c:delayed_work_timer_fn",
        "kernel/workqueue.c:queue_work_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579516512,
      "name": "__queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1006
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
void __queue_work(int cpu, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "__queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__queue_work",
      "external": false,
      "loc": "kernel/workqueue.c:1363",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:rcu_work_rcufn",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/workqueue.c:delayed_work_timer_fn",
        "kernel/workqueue.c:queue_work_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579549248,
      "name": "__queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1008
    },
    {
      "addr": 18446744071579566656,
      "name": "__queue_work.cold.44",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void __queue_work(int cpu, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "__queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__queue_work",
      "external": false,
      "loc": "kernel/workqueue.c:1383",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:rcu_work_rcufn",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/workqueue.c:delayed_work_timer_fn",
        "kernel/workqueue.c:queue_work_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579585824,
      "name": "__queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1008
    },
    {
      "addr": 18446744071579603888,
      "name": "__queue_work.cold.46",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void __queue_work(int cpu, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "__queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__queue_work",
      "external": false,
      "loc": "kernel/workqueue.c:1394",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:rcu_work_rcufn",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/workqueue.c:delayed_work_timer_fn",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:queue_work_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579609888,
      "name": "__queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 993
    },
    {
      "addr": 18446744071579627440,
      "name": "__queue_work.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
void __queue_work(int cpu, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "__queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__queue_work",
      "external": false,
      "loc": "kernel/workqueue.c:1395",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:rcu_work_rcufn",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/workqueue.c:delayed_work_timer_fn",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:queue_work_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579635072,
      "name": "__queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 993
    },
    {
      "addr": 18446744071579653309,
      "name": "__queue_work.cold",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void __queue_work(int cpu, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "__queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579668528,
      "name": "__queue_work",
      "external": false,
      "loc": "kernel/workqueue.c:1392",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:rcu_work_rcufn",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/workqueue.c:delayed_work_timer_fn",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:queue_work_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579668528,
      "name": "__queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 873
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
void __queue_work(int cpu, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "__queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579648416,
      "name": "__queue_work",
      "external": false,
      "loc": "kernel/workqueue.c:1398",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:rcu_work_rcufn",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/workqueue.c:delayed_work_timer_fn",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:queue_work_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579648416,
      "name": "__queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 829
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
void __queue_work(int cpu, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "__queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__queue_work",
      "external": false,
      "loc": "kernel/workqueue.c:1399",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:rcu_work_rcufn",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/workqueue.c:delayed_work_timer_fn",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:queue_work_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579654512,
      "name": "__queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1002
    },
    {
      "addr": 18446744071591223288,
      "name": "__queue_work.cold",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void __queue_work(int cpu, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "__queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__queue_work",
      "external": false,
      "loc": "kernel/workqueue.c:1429",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:rcu_work_rcufn",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/workqueue.c:delayed_work_timer_fn",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:queue_work_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579731392,
      "name": "__queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1149
    },
    {
      "addr": 18446744071592104337,
      "name": "__queue_work.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void __queue_work(int cpu, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "__queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__queue_work",
      "external": false,
      "loc": "kernel/workqueue.c:1418",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:rcu_work_rcufn",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/workqueue.c:delayed_work_timer_fn",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:queue_work_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579832544,
      "name": "__queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1046
    },
    {
      "addr": 18446744071593871870,
      "name": "__queue_work.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void __queue_work(int cpu, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "__queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__queue_work",
      "external": false,
      "loc": "kernel/workqueue.c:1418",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:rcu_work_rcufn",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/workqueue.c:delayed_work_timer_fn",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:queue_work_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579973344,
      "name": "__queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1159
    },
    {
      "addr": 18446744071595976162,
      "name": "__queue_work.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void __queue_work(int cpu, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "__queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__queue_work",
      "external": false,
      "loc": "kernel/workqueue.c:1614",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:rcu_work_rcufn",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/workqueue.c:delayed_work_timer_fn",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:queue_work_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580024256,
      "name": "__queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1162
    },
    {
      "addr": 18446744071596493646,
      "name": "__queue_work.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void __queue_work(int cpu, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "__queue_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580073674,
      "name": "__queue_work",
      "external": false,
      "loc": "kernel/workqueue.c:1705",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:delayed_work_timer_fn"
      ],
      "caller_func": [
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:rcu_work_rcufn",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/workqueue.c:delayed_work_timer_fn",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:queue_work_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580070016,
      "name": "__queue_work.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 978
    },
    {
      "addr": 18446744071597390442,
      "name": "__queue_work.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071580071024,
      "name": "__queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
void __queue_work(int cpu, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "__queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490805928,
      "name": "__queue_work",
      "external": false,
      "loc": "kernel/workqueue.c:1395",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:rcu_work_rcufn",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/workqueue.c:delayed_work_timer_fn",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:queue_work_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490805928,
      "name": "__queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1392
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
void __queue_work(int cpu, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "__queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224837752,
      "name": "__queue_work",
      "external": false,
      "loc": "kernel/workqueue.c:1395",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:rcu_work_rcufn",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/workqueue.c:delayed_work_timer_fn",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:queue_work_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224837752,
      "name": "__queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1336
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
void __queue_work(int cpu, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "__queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283626096,
      "name": "__queue_work",
      "external": false,
      "loc": "kernel/workqueue.c:1395",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:rcu_work_rcufn",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/workqueue.c:delayed_work_timer_fn",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:queue_work_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283626096,
      "name": "__queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1684
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
void __queue_work(int cpu, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "__queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271483492,
      "name": "__queue_work",
      "external": false,
      "loc": "kernel/workqueue.c:1395",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:work_on_cpu",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:rcu_work_rcufn",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/workqueue.c:delayed_work_timer_fn",
        "kernel/workqueue.c:queue_work_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271483492,
      "name": "__queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1122
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
void __queue_work(int cpu, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "__queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__queue_work",
      "external": false,
      "loc": "kernel/workqueue.c:1395",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:rcu_work_rcufn",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/workqueue.c:delayed_work_timer_fn",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:queue_work_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579611376,
      "name": "__queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 993
    },
    {
      "addr": 18446744071579629613,
      "name": "__queue_work.cold",
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
void __queue_work(int cpu, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "__queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__queue_work",
      "external": false,
      "loc": "kernel/workqueue.c:1395",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:rcu_work_rcufn",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/workqueue.c:delayed_work_timer_fn",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:queue_work_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579540448,
      "name": "__queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 993
    },
    {
      "addr": 18446744071579557965,
      "name": "__queue_work.cold",
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
void __queue_work(int cpu, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "__queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__queue_work",
      "external": false,
      "loc": "kernel/workqueue.c:1395",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:rcu_work_rcufn",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/workqueue.c:delayed_work_timer_fn",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:queue_work_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579608656,
      "name": "__queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 993
    },
    {
      "addr": 18446744071579626893,
      "name": "__queue_work.cold",
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
void __queue_work(int cpu, struct workqueue_struct * wq, struct work_struct * work)
```

```json
{
  "name": "__queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__queue_work",
      "external": false,
      "loc": "kernel/workqueue.c:1395",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:rcu_work_rcufn",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/workqueue.c:delayed_work_timer_fn",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:queue_work_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579639936,
      "name": "__queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1073
    },
    {
      "addr": 18446744071579660463,
      "name": "__queue_work.cold",
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
