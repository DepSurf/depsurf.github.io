# Function: <code>task_gtime</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_gtime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched.h:2060",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581468127,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched.h:2060",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat"
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
  "name": "task_gtime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched.h:2202",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581652542,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched.h:2202",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat"
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
  "name": "task_gtime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched.h:2275",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581740986,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched.h:2275",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat"
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
  "name": "task_gtime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:31",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581794878,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:31",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat"
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
  "name": "task_gtime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:32",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581944374,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:32",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat"
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
  "name": "task_gtime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579444926,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:32",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582127718,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:32",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat"
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
  "name": "task_gtime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579478434,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:32",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582222198,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:32",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat"
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
  "name": "task_gtime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579495439,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:32",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582387764,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:32",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat"
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
  "name": "task_gtime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579521439,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:32",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582486676,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:32",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_gtime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579553515,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:32",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:__exit_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582785856,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:32",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_gtime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579534772,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:32",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:__exit_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582859919,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:32",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_gtime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579538550,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:32",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:__exit_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582888143,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:32",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_gtime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579610982,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:32",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:__exit_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583221647,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:32",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_gtime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579703613,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:33",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:__exit_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583719490,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:33",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_gtime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579829133,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:33",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:__exit_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584331394,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:33",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat"
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
  "name": "task_gtime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579878221,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:24",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:__exit_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584561581,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:24",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
u64 task_gtime(struct task_struct * t)
```

```json
{
  "name": "task_gtime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580428368,
      "name": "task_gtime",
      "external": true,
      "loc": "kernel/sched/cputime.c:824",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:__exit_signal",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580428368,
      "name": "task_gtime",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
  "name": "task_gtime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490660096,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:32",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494110084,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:32",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat"
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
  "name": "task_gtime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224735640,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:32",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 3227559352,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:32",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat"
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
  "name": "task_gtime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283483968,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:32",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287779212,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:32",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat"
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
  "name": "task_gtime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271404434,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:32",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273593586,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:32",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat"
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
  "name": "task_gtime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579495103,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:32",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582455412,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:32",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
u64 task_gtime(struct task_struct * t)
```

```json
{
  "name": "task_gtime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579666960,
      "name": "task_gtime",
      "external": true,
      "loc": "kernel/sched/cputime.c:836",
      "file": "kernel/sched/cputime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:release_task",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579666960,
      "name": "task_gtime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_gtime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579495023,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:32",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582445892,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:32",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat"
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
  "name": "task_gtime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579527558,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:32",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582526164,
      "name": "task_gtime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:32",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat"
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
u64 task_gtime(struct task_struct * t)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➕</summary>

```c
u64 task_gtime(struct task_struct * t)
```
</details>
</li>
</ul>
