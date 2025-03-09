# Function: <code>put_prev_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_prev_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579541050,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1233",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_move_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579573350,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1233",
      "file": "kernel/sched/idle_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle_task.c:pick_next_task_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579622305,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1233",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579631616,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1233",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579643340,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1233",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:pick_next_task_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579643986,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1233",
      "file": "kernel/sched/stop_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/stop_task.c:pick_next_task_stop"
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
  "name": "put_prev_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579579084,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1258",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579584389,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1258",
      "file": "kernel/sched/idle_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle_task.c:pick_next_task_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579636657,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1258",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579646496,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1258",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579658076,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1258",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:pick_next_task_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579658718,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1258",
      "file": "kernel/sched/stop_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/stop_task.c:pick_next_task_stop"
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
  "name": "put_prev_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579605182,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1292",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579610549,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1292",
      "file": "kernel/sched/idle_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle_task.c:pick_next_task_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579661230,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1292",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579671184,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1292",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579682636,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1292",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:pick_next_task_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579683262,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1292",
      "file": "kernel/sched/stop_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/stop_task.c:pick_next_task_stop"
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
  "name": "put_prev_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579583506,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1462",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579588181,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1462",
      "file": "kernel/sched/idle_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle_task.c:pick_next_task_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579635586,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1462",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579651088,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1462",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:pick_next_task_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579664626,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1462",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:pick_next_task_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579687107,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1462",
      "file": "kernel/sched/stop_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/stop_task.c:pick_next_task_stop"
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
  "name": "put_prev_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579612870,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1499",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579617701,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1499",
      "file": "kernel/sched/idle_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle_task.c:pick_next_task_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579666669,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1499",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579681472,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1499",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:pick_next_task_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579695314,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1499",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:pick_next_task_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579717907,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1499",
      "file": "kernel/sched/stop_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/stop_task.c:pick_next_task_stop"
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
  "name": "put_prev_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579642822,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1540",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579648085,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1540",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:pick_next_task_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579700895,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1540",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579713502,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1540",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:pick_next_task_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579726988,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1540",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:pick_next_task_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579750631,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1540",
      "file": "kernel/sched/stop_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/stop_task.c:pick_next_task_stop"
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
  "name": "put_prev_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579680454,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1694",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579685717,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1694",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:pick_next_task_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579739947,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1694",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579753598,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1694",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:pick_next_task_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579769420,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1694",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:pick_next_task_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579790663,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1694",
      "file": "kernel/sched/stop_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/stop_task.c:pick_next_task_stop"
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
  "name": "put_prev_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579713390,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1756",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579719445,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1756",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:pick_next_task_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579769371,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1756",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579782277,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1756",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:pick_next_task_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579796780,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1756",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:pick_next_task_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579818455,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1756",
      "file": "kernel/sched/stop_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/stop_task.c:pick_next_task_stop"
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
  "name": "put_prev_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579755662,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1774",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:do_set_cpus_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579761964,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1774",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:pick_next_task_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579813217,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1774",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair"
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
  "name": "put_prev_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579790199,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1803",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:do_set_cpus_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579853148,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1803",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair"
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
  "name": "put_prev_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579781773,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1877",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:__do_set_cpus_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579845298,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1877",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair"
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
  "name": "put_prev_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579789901,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1888",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:__do_set_cpus_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579851794,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1888",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair"
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
  "name": "put_prev_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579885567,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:2179",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:put_prev_task_balance",
        "kernel/sched/core.c:__do_set_cpus_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579957573,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:2179",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair"
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
  "name": "put_prev_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580002934,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:2173",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:put_prev_task_balance",
        "kernel/sched/core.c:__do_set_cpus_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580072245,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:2173",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair"
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
  "name": "put_prev_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580164743,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:2224",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:put_prev_task_balance",
        "kernel/sched/core.c:__do_set_cpus_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580242701,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:2224",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair"
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
  "name": "put_prev_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580213123,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:2271",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:put_prev_task_balance",
        "kernel/sched/core.c:__do_set_cpus_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580308669,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:2271",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair"
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
  "name": "put_prev_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580261821,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:2323",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:__do_set_cpus_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580361224,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:2323",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_prev_task(struct rq * rq, struct task_struct * prev)
```

```json
{
  "name": "put_prev_task",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490934368,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1774",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:do_set_cpus_allowed"
      ],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule"
      ]
    },
    {
      "addr": 18446603336490940656,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1774",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:pick_next_task_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490994252,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1774",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490886424,
      "name": "put_prev_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "put_prev_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224953352,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1774",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:do_set_cpus_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 3224958980,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1774",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:pick_next_task_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 3225003840,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1774",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair"
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
  "name": "put_prev_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283790736,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1774",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:do_set_cpus_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283796480,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1774",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:pick_next_task_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283865044,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1774",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair"
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
  "name": "put_prev_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271568292,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1774",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:do_set_cpus_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271572270,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1774",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:pick_next_task_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271605588,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1774",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair"
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
  "name": "put_prev_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579731582,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1774",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:do_set_cpus_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579737884,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1774",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:pick_next_task_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579788993,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1774",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair"
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
  "name": "put_prev_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579660430,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1774",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:do_set_cpus_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579668236,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1774",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:pick_next_task_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579719777,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1774",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair"
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
  "name": "put_prev_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579717158,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1774",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:do_set_cpus_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579722332,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1774",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:pick_next_task_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579773585,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1774",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair"
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
  "name": "put_prev_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579763292,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1774",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:do_set_cpus_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579769708,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1774",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:pick_next_task_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579821665,
      "name": "put_prev_task",
      "external": false,
      "loc": "kernel/sched/sched.h:1774",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void put_prev_task(struct rq * rq, struct task_struct * prev)
```
</details>
</li>
</ul>
