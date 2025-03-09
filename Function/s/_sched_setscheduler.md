# Function: <code>_sched_setscheduler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int _sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param, bool check)
```

```json
{
  "name": "_sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579541552,
      "name": "_sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:4025",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:sched_set_stop_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579541552,
      "name": "_sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
int _sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param, bool check)
```

```json
{
  "name": "_sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579552944,
      "name": "_sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:4275",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:sched_set_stop_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579552944,
      "name": "_sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
int _sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param, bool check)
```

```json
{
  "name": "_sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579577664,
      "name": "_sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:4312",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:sched_set_stop_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579577664,
      "name": "_sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
int _sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param, bool check)
```

```json
{
  "name": "_sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579561056,
      "name": "_sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:4212",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:sched_set_stop_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579561056,
      "name": "_sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
int _sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param, bool check)
```

```json
{
  "name": "_sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579590304,
      "name": "_sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:4256",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:sched_set_stop_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579590304,
      "name": "_sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
int _sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param, bool check)
```

```json
{
  "name": "_sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579622144,
      "name": "_sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:4386",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:sched_set_stop_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579622144,
      "name": "_sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
int _sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param, bool check)
```

```json
{
  "name": "_sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579659440,
      "name": "_sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:4371",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:sched_set_stop_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579659440,
      "name": "_sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
int _sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param, bool check)
```

```json
{
  "name": "_sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579685360,
      "name": "_sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:4808",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:sched_set_stop_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579685360,
      "name": "_sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int _sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param, bool check)
```

```json
{
  "name": "_sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579724768,
      "name": "_sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:5023",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:sched_set_stop_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579724768,
      "name": "_sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579778200,
      "name": "_sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:5256",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_set_stop_task"
      ],
      "caller_func": [
        "kernel/sched/core.c:do_sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579768032,
      "name": "_sched_setscheduler.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579768552,
      "name": "_sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:6031",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_set_stop_task"
      ],
      "caller_func": [
        "kernel/sched/core.c:do_sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579756640,
      "name": "_sched_setscheduler.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579776248,
      "name": "_sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:6332",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_set_stop_task"
      ],
      "caller_func": [
        "kernel/sched/core.c:do_sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579763792,
      "name": "_sched_setscheduler.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579851238,
      "name": "_sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:7495",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_set_fifo_low",
        "kernel/sched/core.c:sched_set_fifo",
        "kernel/sched/core.c:sched_set_stop_task"
      ],
      "caller_func": [
        "kernel/sched/core.c:do_sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579850432,
      "name": "_sched_setscheduler.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579968806,
      "name": "_sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:7603",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_set_fifo_low",
        "kernel/sched/core.c:sched_set_fifo",
        "kernel/sched/core.c:sched_set_stop_task"
      ],
      "caller_func": [
        "kernel/sched/core.c:do_sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579967856,
      "name": "_sched_setscheduler.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
  "name": "_sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580128694,
      "name": "_sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:7745",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_set_fifo_low",
        "kernel/sched/core.c:sched_set_fifo",
        "kernel/sched/core.c:sched_set_stop_task"
      ],
      "caller_func": [
        "kernel/sched/core.c:do_sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580127632,
      "name": "_sched_setscheduler.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580190758,
      "name": "_sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:7854",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_set_fifo_low",
        "kernel/sched/core.c:sched_set_fifo",
        "kernel/sched/core.c:sched_set_stop_task"
      ],
      "caller_func": [
        "kernel/sched/core.c:do_sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580189696,
      "name": "_sched_setscheduler.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580237894,
      "name": "_sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:7915",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_set_fifo_low",
        "kernel/sched/core.c:sched_set_fifo",
        "kernel/sched/core.c:sched_set_stop_task"
      ],
      "caller_func": [
        "kernel/sched/core.c:do_sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580236592,
      "name": "_sched_setscheduler.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "_sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490906560,
      "name": "_sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:5023",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:sched_set_stop_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490906560,
      "name": "_sched_setscheduler.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
int _sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param, bool check)
```

```json
{
  "name": "_sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224920852,
      "name": "_sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:5023",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:sched_set_stop_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224920852,
      "name": "_sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "_sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283747264,
      "name": "_sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:5023",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:sched_set_stop_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283747264,
      "name": "_sched_setscheduler.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "_sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271547226,
      "name": "_sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:5023",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:sched_set_stop_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271547226,
      "name": "_sched_setscheduler.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
int _sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param, bool check)
```

```json
{
  "name": "_sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579701680,
      "name": "_sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:5023",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:sched_set_stop_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579701680,
      "name": "_sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int _sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param, bool check)
```

```json
{
  "name": "_sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579628832,
      "name": "_sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:5023",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:sched_set_stop_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579628832,
      "name": "_sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int _sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param, bool check)
```

```json
{
  "name": "_sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579693680,
      "name": "_sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:5023",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:sched_set_stop_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579693680,
      "name": "_sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int _sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param, bool check)
```

```json
{
  "name": "_sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579732112,
      "name": "_sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:5023",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:sched_set_stop_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579732112,
      "name": "_sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int _sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param, bool check)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int _sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param, bool check)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int _sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param, bool check)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int _sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param, bool check)
```
</details>
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
