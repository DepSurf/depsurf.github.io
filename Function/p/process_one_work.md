# Function: <code>process_one_work</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void process_one_work(struct worker * worker, struct work_struct * work)
```

```json
{
  "name": "process_one_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579475600,
      "name": "process_one_work",
      "external": false,
      "loc": "kernel/workqueue.c:1961",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:rescuer_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579475600,
      "name": "process_one_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1147
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
void process_one_work(struct worker * worker, struct work_struct * work)
```

```json
{
  "name": "process_one_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579489312,
      "name": "process_one_work",
      "external": false,
      "loc": "kernel/workqueue.c:2017",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579489312,
      "name": "process_one_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1190
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
void process_one_work(struct worker * worker, struct work_struct * work)
```

```json
{
  "name": "process_one_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579508624,
      "name": "process_one_work",
      "external": false,
      "loc": "kernel/workqueue.c:2019",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579508624,
      "name": "process_one_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1190
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
void process_one_work(struct worker * worker, struct work_struct * work)
```

```json
{
  "name": "process_one_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579497632,
      "name": "process_one_work",
      "external": false,
      "loc": "kernel/workqueue.c:2018",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579497632,
      "name": "process_one_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1026
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
void process_one_work(struct worker * worker, struct work_struct * work)
```

```json
{
  "name": "process_one_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579524304,
      "name": "process_one_work",
      "external": false,
      "loc": "kernel/workqueue.c:2012",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579524304,
      "name": "process_one_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1029
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
void process_one_work(struct worker * worker, struct work_struct * work)
```

```json
{
  "name": "process_one_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "process_one_work",
      "external": false,
      "loc": "kernel/workqueue.c:2046",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579551840,
      "name": "process_one_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 960
    },
    {
      "addr": 18446744071579566687,
      "name": "process_one_work.cold.45",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
void process_one_work(struct worker * worker, struct work_struct * work)
```

```json
{
  "name": "process_one_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579588848,
      "name": "process_one_work",
      "external": false,
      "loc": "kernel/workqueue.c:2066",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579588848,
      "name": "process_one_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1038
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
void process_one_work(struct worker * worker, struct work_struct * work)
```

```json
{
  "name": "process_one_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "process_one_work",
      "external": false,
      "loc": "kernel/workqueue.c:2162",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579613152,
      "name": "process_one_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 890
    },
    {
      "addr": 18446744071579627483,
      "name": "process_one_work.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
void process_one_work(struct worker * worker, struct work_struct * work)
```

```json
{
  "name": "process_one_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "process_one_work",
      "external": false,
      "loc": "kernel/workqueue.c:2165",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579638352,
      "name": "process_one_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 933
    },
    {
      "addr": 18446744071579653333,
      "name": "process_one_work.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
void process_one_work(struct worker * worker, struct work_struct * work)
```

```json
{
  "name": "process_one_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "process_one_work",
      "external": false,
      "loc": "kernel/workqueue.c:2162",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579669984,
      "name": "process_one_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 936
    },
    {
      "addr": 18446744071579685022,
      "name": "process_one_work.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
void process_one_work(struct worker * worker, struct work_struct * work)
```

```json
{
  "name": "process_one_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "process_one_work",
      "external": false,
      "loc": "kernel/workqueue.c:2168",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579649824,
      "name": "process_one_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 947
    },
    {
      "addr": 18446744071591280371,
      "name": "process_one_work.cold",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void process_one_work(struct worker * worker, struct work_struct * work)
```

```json
{
  "name": "process_one_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "process_one_work",
      "external": false,
      "loc": "kernel/workqueue.c:2169",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579656112,
      "name": "process_one_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 947
    },
    {
      "addr": 18446744071591223312,
      "name": "process_one_work.cold",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void process_one_work(struct worker * worker, struct work_struct * work)
```

```json
{
  "name": "process_one_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "process_one_work",
      "external": false,
      "loc": "kernel/workqueue.c:2198",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579733088,
      "name": "process_one_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 967
    },
    {
      "addr": 18446744071592104429,
      "name": "process_one_work.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void process_one_work(struct worker * worker, struct work_struct * work)
```

```json
{
  "name": "process_one_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "process_one_work",
      "external": false,
      "loc": "kernel/workqueue.c:2181",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579837552,
      "name": "process_one_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1010
    },
    {
      "addr": 18446744071593872077,
      "name": "process_one_work.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void process_one_work(struct worker * worker, struct work_struct * work)
```

```json
{
  "name": "process_one_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579975184,
      "name": "process_one_work",
      "external": false,
      "loc": "kernel/workqueue.c:2181",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579975184,
      "name": "process_one_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1070
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
void process_one_work(struct worker * worker, struct work_struct * work)
```

```json
{
  "name": "process_one_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580030384,
      "name": "process_one_work",
      "external": false,
      "loc": "kernel/workqueue.c:2491",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580030384,
      "name": "process_one_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1087
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
void process_one_work(struct worker * worker, struct work_struct * work)
```

```json
{
  "name": "process_one_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580064480,
      "name": "process_one_work",
      "external": false,
      "loc": "kernel/workqueue.c:2539",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580064480,
      "name": "process_one_work",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void process_one_work(struct worker * worker, struct work_struct * work)
```

```json
{
  "name": "process_one_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490810976,
      "name": "process_one_work",
      "external": false,
      "loc": "kernel/workqueue.c:2165",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490810976,
      "name": "process_one_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1116
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
void process_one_work(struct worker * worker, struct work_struct * work)
```

```json
{
  "name": "process_one_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224845360,
      "name": "process_one_work",
      "external": false,
      "loc": "kernel/workqueue.c:2165",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224845360,
      "name": "process_one_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1340
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
void process_one_work(struct worker * worker, struct work_struct * work)
```

```json
{
  "name": "process_one_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283639024,
      "name": "process_one_work",
      "external": false,
      "loc": "kernel/workqueue.c:2165",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283639024,
      "name": "process_one_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1352
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
void process_one_work(struct worker * worker, struct work_struct * work)
```

```json
{
  "name": "process_one_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271486184,
      "name": "process_one_work",
      "external": false,
      "loc": "kernel/workqueue.c:2165",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271486184,
      "name": "process_one_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 886
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
void process_one_work(struct worker * worker, struct work_struct * work)
```

```json
{
  "name": "process_one_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "process_one_work",
      "external": false,
      "loc": "kernel/workqueue.c:2165",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579614656,
      "name": "process_one_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 933
    },
    {
      "addr": 18446744071579629637,
      "name": "process_one_work.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
void process_one_work(struct worker * worker, struct work_struct * work)
```

```json
{
  "name": "process_one_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "process_one_work",
      "external": false,
      "loc": "kernel/workqueue.c:2165",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579543136,
      "name": "process_one_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 927
    },
    {
      "addr": 18446744071579557989,
      "name": "process_one_work.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
void process_one_work(struct worker * worker, struct work_struct * work)
```

```json
{
  "name": "process_one_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "process_one_work",
      "external": false,
      "loc": "kernel/workqueue.c:2165",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579611936,
      "name": "process_one_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 933
    },
    {
      "addr": 18446744071579626917,
      "name": "process_one_work.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
void process_one_work(struct worker * worker, struct work_struct * work)
```

```json
{
  "name": "process_one_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "process_one_work",
      "external": false,
      "loc": "kernel/workqueue.c:2165",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579645696,
      "name": "process_one_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 969
    },
    {
      "addr": 18446744071579660533,
      "name": "process_one_work.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
