# Function: <code>trace_ignore_this_task</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
bool trace_ignore_this_task(struct trace_pid_list * filtered_pids, struct task_struct * task)
```

```json
{
  "name": "trace_ignore_this_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580247824,
      "name": "trace_ignore_this_task",
      "external": true,
      "loc": "kernel/trace/trace.c:358",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ignore_task_cpu",
        "kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe",
        "kernel/trace/trace_events.c:ignore_task_cpu",
        "kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580247824,
      "name": "trace_ignore_this_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
bool trace_ignore_this_task(struct trace_pid_list * filtered_pids, struct task_struct * task)
```

```json
{
  "name": "trace_ignore_this_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580293152,
      "name": "trace_ignore_this_task",
      "external": true,
      "loc": "kernel/trace/trace.c:360",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ignore_task_cpu",
        "kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe",
        "kernel/trace/trace_events.c:ignore_task_cpu",
        "kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580293152,
      "name": "trace_ignore_this_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
bool trace_ignore_this_task(struct trace_pid_list * filtered_pids, struct task_struct * task)
```

```json
{
  "name": "trace_ignore_this_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580306336,
      "name": "trace_ignore_this_task",
      "external": true,
      "loc": "kernel/trace/trace.c:352",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ignore_task_cpu",
        "kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe",
        "kernel/trace/trace_events.c:ignore_task_cpu",
        "kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580306336,
      "name": "trace_ignore_this_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
bool trace_ignore_this_task(struct trace_pid_list * filtered_pids, struct task_struct * task)
```

```json
{
  "name": "trace_ignore_this_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580359392,
      "name": "trace_ignore_this_task",
      "external": true,
      "loc": "kernel/trace/trace.c:352",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ignore_task_cpu",
        "kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe",
        "kernel/trace/trace_events.c:ignore_task_cpu",
        "kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580359392,
      "name": "trace_ignore_this_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
bool trace_ignore_this_task(struct trace_pid_list * filtered_pids, struct task_struct * task)
```

```json
{
  "name": "trace_ignore_this_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580421168,
      "name": "trace_ignore_this_task",
      "external": true,
      "loc": "kernel/trace/trace.c:353",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ignore_task_cpu",
        "kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe",
        "kernel/trace/trace_events.c:ignore_task_cpu",
        "kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580421168,
      "name": "trace_ignore_this_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
bool trace_ignore_this_task(struct trace_pid_list * filtered_pids, struct task_struct * task)
```

```json
{
  "name": "trace_ignore_this_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580476912,
      "name": "trace_ignore_this_task",
      "external": true,
      "loc": "kernel/trace/trace.c:354",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ignore_task_cpu",
        "kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe",
        "kernel/trace/trace_events.c:ignore_task_cpu",
        "kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580476912,
      "name": "trace_ignore_this_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
bool trace_ignore_this_task(struct trace_pid_list * filtered_pids, struct task_struct * task)
```

```json
{
  "name": "trace_ignore_this_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580532752,
      "name": "trace_ignore_this_task",
      "external": true,
      "loc": "kernel/trace/trace.c:356",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ignore_task_cpu",
        "kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe",
        "kernel/trace/trace_events.c:ignore_task_cpu",
        "kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580532752,
      "name": "trace_ignore_this_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
bool trace_ignore_this_task(struct trace_pid_list * filtered_pids, struct task_struct * task)
```

```json
{
  "name": "trace_ignore_this_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580580352,
      "name": "trace_ignore_this_task",
      "external": true,
      "loc": "kernel/trace/trace.c:374",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ignore_task_cpu",
        "kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe",
        "kernel/trace/trace_events.c:ignore_task_cpu",
        "kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580580352,
      "name": "trace_ignore_this_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
bool trace_ignore_this_task(struct trace_pid_list * filtered_pids, struct trace_pid_list * filtered_no_pids, struct task_struct * task)
```

```json
{
  "name": "trace_ignore_this_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580679520,
      "name": "trace_ignore_this_task",
      "external": true,
      "loc": "kernel/trace/trace.c:389",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe",
        "kernel/trace/trace_events.c:ignore_task_cpu",
        "kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580679520,
      "name": "trace_ignore_this_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
bool trace_ignore_this_task(struct trace_pid_list * filtered_pids, struct trace_pid_list * filtered_no_pids, struct task_struct * task)
```

```json
{
  "name": "trace_ignore_this_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580670352,
      "name": "trace_ignore_this_task",
      "external": true,
      "loc": "kernel/trace/trace.c:540",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe",
        "kernel/trace/trace_events.c:ignore_task_cpu",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580670352,
      "name": "trace_ignore_this_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
bool trace_ignore_this_task(struct trace_pid_list * filtered_pids, struct trace_pid_list * filtered_no_pids, struct task_struct * task)
```

```json
{
  "name": "trace_ignore_this_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580669072,
      "name": "trace_ignore_this_task",
      "external": true,
      "loc": "kernel/trace/trace.c:543",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe",
        "kernel/trace/trace_events.c:ignore_task_cpu",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580669072,
      "name": "trace_ignore_this_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
bool trace_ignore_this_task(struct trace_pid_list * filtered_pids, struct trace_pid_list * filtered_no_pids, struct task_struct * task)
```

```json
{
  "name": "trace_ignore_this_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580843904,
      "name": "trace_ignore_this_task",
      "external": true,
      "loc": "kernel/trace/trace.c:556",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe",
        "kernel/trace/trace_events.c:ignore_task_cpu",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580843904,
      "name": "trace_ignore_this_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
bool trace_ignore_this_task(struct trace_pid_list * filtered_pids, struct trace_pid_list * filtered_no_pids, struct task_struct * task)
```

```json
{
  "name": "trace_ignore_this_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581071840,
      "name": "trace_ignore_this_task",
      "external": true,
      "loc": "kernel/trace/trace.c:553",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe",
        "kernel/trace/trace_events.c:ignore_task_cpu",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581071840,
      "name": "trace_ignore_this_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
bool trace_ignore_this_task(struct trace_pid_list * filtered_pids, struct trace_pid_list * filtered_no_pids, struct task_struct * task)
```

```json
{
  "name": "trace_ignore_this_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581378000,
      "name": "trace_ignore_this_task",
      "external": true,
      "loc": "kernel/trace/trace.c:552",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe",
        "kernel/trace/trace_events.c:ignore_task_cpu",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581378000,
      "name": "trace_ignore_this_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
bool trace_ignore_this_task(struct trace_pid_list * filtered_pids, struct trace_pid_list * filtered_no_pids, struct task_struct * task)
```

```json
{
  "name": "trace_ignore_this_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581472592,
      "name": "trace_ignore_this_task",
      "external": true,
      "loc": "kernel/trace/trace.c:593",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe",
        "kernel/trace/trace_events.c:ignore_task_cpu",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581472592,
      "name": "trace_ignore_this_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
bool trace_ignore_this_task(struct trace_pid_list * filtered_pids, struct trace_pid_list * filtered_no_pids, struct task_struct * task)
```

```json
{
  "name": "trace_ignore_this_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581582848,
      "name": "trace_ignore_this_task",
      "external": true,
      "loc": "kernel/trace/trace.c:595",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe",
        "kernel/trace/trace_events.c:ignore_task_cpu",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581582848,
      "name": "trace_ignore_this_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
bool trace_ignore_this_task(struct trace_pid_list * filtered_pids, struct task_struct * task)
```

```json
{
  "name": "trace_ignore_this_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491876200,
      "name": "trace_ignore_this_task",
      "external": true,
      "loc": "kernel/trace/trace.c:374",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ignore_task_cpu",
        "kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe",
        "kernel/trace/trace_events.c:ignore_task_cpu",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491876200,
      "name": "trace_ignore_this_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
bool trace_ignore_this_task(struct trace_pid_list * filtered_pids, struct task_struct * task)
```

```json
{
  "name": "trace_ignore_this_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225818832,
      "name": "trace_ignore_this_task",
      "external": true,
      "loc": "kernel/trace/trace.c:374",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ignore_task_cpu",
        "kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe",
        "kernel/trace/trace_events.c:ignore_task_cpu",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225818832,
      "name": "trace_ignore_this_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
bool trace_ignore_this_task(struct trace_pid_list * filtered_pids, struct task_struct * task)
```

```json
{
  "name": "trace_ignore_this_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284952384,
      "name": "trace_ignore_this_task",
      "external": true,
      "loc": "kernel/trace/trace.c:374",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ignore_task_cpu",
        "kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe",
        "kernel/trace/trace_events.c:ignore_task_cpu",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284952384,
      "name": "trace_ignore_this_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
bool trace_ignore_this_task(struct trace_pid_list * filtered_pids, struct task_struct * task)
```

```json
{
  "name": "trace_ignore_this_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272168176,
      "name": "trace_ignore_this_task",
      "external": true,
      "loc": "kernel/trace/trace.c:374",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ignore_task_cpu",
        "kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe",
        "kernel/trace/trace_events.c:ignore_task_cpu",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272168176,
      "name": "trace_ignore_this_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
bool trace_ignore_this_task(struct trace_pid_list * filtered_pids, struct task_struct * task)
```

```json
{
  "name": "trace_ignore_this_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580549152,
      "name": "trace_ignore_this_task",
      "external": true,
      "loc": "kernel/trace/trace.c:374",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ignore_task_cpu",
        "kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe",
        "kernel/trace/trace_events.c:ignore_task_cpu",
        "kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580549152,
      "name": "trace_ignore_this_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
bool trace_ignore_this_task(struct trace_pid_list * filtered_pids, struct task_struct * task)
```

```json
{
  "name": "trace_ignore_this_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580495920,
      "name": "trace_ignore_this_task",
      "external": true,
      "loc": "kernel/trace/trace.c:374",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ignore_task_cpu",
        "kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe",
        "kernel/trace/trace_events.c:ignore_task_cpu",
        "kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580495920,
      "name": "trace_ignore_this_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
bool trace_ignore_this_task(struct trace_pid_list * filtered_pids, struct task_struct * task)
```

```json
{
  "name": "trace_ignore_this_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580540400,
      "name": "trace_ignore_this_task",
      "external": true,
      "loc": "kernel/trace/trace.c:374",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ignore_task_cpu",
        "kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe",
        "kernel/trace/trace_events.c:ignore_task_cpu",
        "kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580540400,
      "name": "trace_ignore_this_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
bool trace_ignore_this_task(struct trace_pid_list * filtered_pids, struct task_struct * task)
```

```json
{
  "name": "trace_ignore_this_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580596944,
      "name": "trace_ignore_this_task",
      "external": true,
      "loc": "kernel/trace/trace.c:374",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ignore_task_cpu",
        "kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe",
        "kernel/trace/trace_events.c:ignore_task_cpu",
        "kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580596944,
      "name": "trace_ignore_this_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
bool trace_ignore_this_task(struct trace_pid_list * filtered_pids, struct task_struct * task)
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct trace_pid_list * filtered_no_pids</code>
</li>
<li>
<b>Param reordered. </b>
<code>filtered_pids, task</code> ➡️ <code>filtered_pids, filtered_no_pids, task</code>
</li>
</ul>
</details>
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
