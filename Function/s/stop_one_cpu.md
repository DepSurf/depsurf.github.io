# Function: <code>stop_one_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void * arg)
```

```json
{
  "name": "stop_one_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580025664,
      "name": "stop_one_cpu",
      "external": true,
      "loc": "kernel/stop_machine.c:121",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:sched_exec",
        "kernel/sched/core.c:migrate_task_to"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580025664,
      "name": "stop_one_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void * arg)
```

```json
{
  "name": "stop_one_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580058272,
      "name": "stop_one_cpu",
      "external": true,
      "loc": "kernel/stop_machine.c:121",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:migrate_task_to",
        "kernel/sched/core.c:sched_exec",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580058272,
      "name": "stop_one_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void * arg)
```

```json
{
  "name": "stop_one_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580098352,
      "name": "stop_one_cpu",
      "external": true,
      "loc": "kernel/stop_machine.c:116",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:migrate_task_to",
        "kernel/sched/core.c:sched_exec",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580098352,
      "name": "stop_one_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void * arg)
```

```json
{
  "name": "stop_one_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580103904,
      "name": "stop_one_cpu",
      "external": true,
      "loc": "kernel/stop_machine.c:116",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:migrate_task_to",
        "kernel/sched/core.c:sched_exec",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580103904,
      "name": "stop_one_cpu",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void * arg)
```

```json
{
  "name": "stop_one_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580156560,
      "name": "stop_one_cpu",
      "external": true,
      "loc": "kernel/stop_machine.c:116",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:migrate_task_to",
        "kernel/sched/core.c:sched_exec",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580156560,
      "name": "stop_one_cpu",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void * arg)
```

```json
{
  "name": "stop_one_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580216256,
      "name": "stop_one_cpu",
      "external": true,
      "loc": "kernel/stop_machine.c:123",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:migrate_task_to",
        "kernel/sched/core.c:sched_exec",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580216256,
      "name": "stop_one_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void * arg)
```

```json
{
  "name": "stop_one_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580268704,
      "name": "stop_one_cpu",
      "external": true,
      "loc": "kernel/stop_machine.c:123",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:migrate_task_to",
        "kernel/sched/core.c:sched_exec",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580268704,
      "name": "stop_one_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void * arg)
```

```json
{
  "name": "stop_one_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580319328,
      "name": "stop_one_cpu",
      "external": true,
      "loc": "kernel/stop_machine.c:122",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:migrate_task_to",
        "kernel/sched/core.c:sched_exec",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580319328,
      "name": "stop_one_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void * arg)
```

```json
{
  "name": "stop_one_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580368160,
      "name": "stop_one_cpu",
      "external": true,
      "loc": "kernel/stop_machine.c:123",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:migrate_task_to",
        "kernel/sched/core.c:sched_exec",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580368160,
      "name": "stop_one_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void * arg)
```

```json
{
  "name": "stop_one_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580441808,
      "name": "stop_one_cpu",
      "external": true,
      "loc": "kernel/stop_machine.c:123",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:migrate_task_to",
        "kernel/sched/core.c:sched_exec",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580441808,
      "name": "stop_one_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void * arg)
```

```json
{
  "name": "stop_one_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580429872,
      "name": "stop_one_cpu",
      "external": true,
      "loc": "kernel/stop_machine.c:139",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:migrate_task_to",
        "kernel/sched/core.c:sched_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580429872,
      "name": "stop_one_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void * arg)
```

```json
{
  "name": "stop_one_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580433936,
      "name": "stop_one_cpu",
      "external": true,
      "loc": "kernel/stop_machine.c:139",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:migrate_task_to",
        "kernel/sched/core.c:sched_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580433936,
      "name": "stop_one_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void * arg)
```

```json
{
  "name": "stop_one_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580598720,
      "name": "stop_one_cpu",
      "external": true,
      "loc": "kernel/stop_machine.c:139",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:migrate_task_to",
        "kernel/sched/core.c:sched_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580598720,
      "name": "stop_one_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void * arg)
```

```json
{
  "name": "stop_one_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580802016,
      "name": "stop_one_cpu",
      "external": true,
      "loc": "kernel/stop_machine.c:139",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:migrate_task_to",
        "kernel/sched/core.c:sched_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580802016,
      "name": "stop_one_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void * arg)
```

```json
{
  "name": "stop_one_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581087392,
      "name": "stop_one_cpu",
      "external": true,
      "loc": "kernel/stop_machine.c:139",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:migrate_task_to",
        "kernel/sched/core.c:sched_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581087392,
      "name": "stop_one_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void * arg)
```

```json
{
  "name": "stop_one_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581179200,
      "name": "stop_one_cpu",
      "external": true,
      "loc": "kernel/stop_machine.c:139",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:migrate_task_to",
        "kernel/sched/core.c:sched_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581179200,
      "name": "stop_one_cpu",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void * arg)
```

```json
{
  "name": "stop_one_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581284880,
      "name": "stop_one_cpu",
      "external": true,
      "loc": "kernel/stop_machine.c:139",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:migrate_task_to",
        "kernel/sched/core.c:sched_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581284880,
      "name": "stop_one_cpu",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void * arg)
```

```json
{
  "name": "stop_one_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491631752,
      "name": "stop_one_cpu",
      "external": true,
      "loc": "kernel/stop_machine.c:123",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:migrate_task_to",
        "kernel/sched/core.c:sched_exec",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491631752,
      "name": "stop_one_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void * arg)
```

```json
{
  "name": "stop_one_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225585020,
      "name": "stop_one_cpu",
      "external": true,
      "loc": "kernel/stop_machine.c:123",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_exec",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225585020,
      "name": "stop_one_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void * arg)
```

```json
{
  "name": "stop_one_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284624848,
      "name": "stop_one_cpu",
      "external": true,
      "loc": "kernel/stop_machine.c:123",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:migrate_task_to",
        "kernel/sched/core.c:sched_exec",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284624848,
      "name": "stop_one_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void * arg)
```

```json
{
  "name": "stop_one_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272028926,
      "name": "stop_one_cpu",
      "external": true,
      "loc": "kernel/stop_machine.c:123",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_exec",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272028926,
      "name": "stop_one_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void * arg)
```

```json
{
  "name": "stop_one_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580336960,
      "name": "stop_one_cpu",
      "external": true,
      "loc": "kernel/stop_machine.c:123",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:migrate_task_to",
        "kernel/sched/core.c:sched_exec",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580336960,
      "name": "stop_one_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void * arg)
```

```json
{
  "name": "stop_one_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580284208,
      "name": "stop_one_cpu",
      "external": true,
      "loc": "kernel/stop_machine.c:123",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:migrate_task_to",
        "kernel/sched/core.c:sched_exec",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580284208,
      "name": "stop_one_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void * arg)
```

```json
{
  "name": "stop_one_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580328208,
      "name": "stop_one_cpu",
      "external": true,
      "loc": "kernel/stop_machine.c:123",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:migrate_task_to",
        "kernel/sched/core.c:sched_exec",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580328208,
      "name": "stop_one_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void * arg)
```

```json
{
  "name": "stop_one_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580383328,
      "name": "stop_one_cpu",
      "external": true,
      "loc": "kernel/stop_machine.c:123",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:migrate_task_to",
        "kernel/sched/core.c:sched_exec",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580383328,
      "name": "stop_one_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
