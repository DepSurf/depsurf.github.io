# Function: <code>unregister_ftrace_function</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int unregister_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "unregister_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580174448,
      "name": "unregister_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5577",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_disable_func",
        "kernel/kprobes.c:disarm_kprobe",
        "kernel/trace/trace_functions.c:function_trace_reset",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "kernel/trace/trace_event_perf.c:perf_ftrace_event_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580174448,
      "name": "unregister_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int unregister_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "unregister_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580204240,
      "name": "unregister_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5611",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:disarm_kprobe",
        "kernel/trace/trace_functions.c:function_trace_reset",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "kernel/trace/trace_event_perf.c:perf_ftrace_event_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580204240,
      "name": "unregister_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int unregister_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "unregister_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580244944,
      "name": "unregister_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5660",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:disarm_kprobe",
        "kernel/trace/trace_functions.c:function_trace_reset",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "kernel/trace/trace_event_perf.c:perf_ftrace_event_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580244944,
      "name": "unregister_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int unregister_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "unregister_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580255664,
      "name": "unregister_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6440",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/patch.c:klp_unpatch_object",
        "kernel/kprobes.c:disarm_kprobe",
        "kernel/trace/trace_functions.c:function_trace_reset",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "kernel/trace/trace_event_perf.c:perf_ftrace_event_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580255664,
      "name": "unregister_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int unregister_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "unregister_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580307616,
      "name": "unregister_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6739",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/patch.c:klp_unpatch_object",
        "kernel/kprobes.c:disarm_kprobe",
        "kernel/trace/trace_functions.c:function_trace_reset",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "kernel/trace/trace_event_perf.c:perf_ftrace_event_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580307616,
      "name": "unregister_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int unregister_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "unregister_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580368256,
      "name": "unregister_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6725",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/patch.c:klp_unpatch_object",
        "kernel/kprobes.c:disarm_kprobe",
        "kernel/trace/trace_functions.c:function_trace_reset",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "kernel/trace/trace_event_perf.c:perf_ftrace_event_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580368256,
      "name": "unregister_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int unregister_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "unregister_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580424656,
      "name": "unregister_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6664",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/patch.c:klp_unpatch_object",
        "kernel/kprobes.c:disarm_kprobe",
        "kernel/trace/trace_functions.c:function_trace_reset",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "kernel/trace/trace_event_perf.c:perf_ftrace_event_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580424656,
      "name": "unregister_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int unregister_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "unregister_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580477296,
      "name": "unregister_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6718",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/patch.c:__klp_unpatch_object",
        "kernel/kprobes.c:disarm_kprobe",
        "kernel/trace/trace_functions.c:function_trace_reset",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "kernel/trace/trace_event_perf.c:perf_ftrace_event_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580477296,
      "name": "unregister_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int unregister_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "unregister_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580526320,
      "name": "unregister_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6753",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/patch.c:__klp_unpatch_object",
        "kernel/trace/trace_functions.c:function_trace_reset",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "kernel/trace/trace_event_perf.c:perf_ftrace_event_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580526320,
      "name": "unregister_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int unregister_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "unregister_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580628979,
      "name": "unregister_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:7393",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_modify_direct_caller",
        "kernel/trace/ftrace.c:unregister_ftrace_direct"
      ],
      "caller_func": [
        "kernel/livepatch/patch.c:klp_unpatch_func",
        "kernel/kprobes.c:__disarm_kprobe_ftrace",
        "kernel/trace/trace_functions.c:function_trace_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed",
        "kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "kernel/trace/trace_event_perf.c:perf_ftrace_event_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580615680,
      "name": "unregister_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int unregister_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "unregister_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580619715,
      "name": "unregister_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:7563",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_modify_direct_caller",
        "kernel/trace/ftrace.c:unregister_ftrace_direct"
      ],
      "caller_func": [
        "kernel/livepatch/patch.c:klp_unpatch_func",
        "kernel/kprobes.c:__disarm_kprobe_ftrace",
        "kernel/trace/trace_functions.c:function_trace_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed",
        "kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "kernel/trace/trace_event_perf.c:perf_ftrace_event_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580606080,
      "name": "unregister_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int unregister_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "unregister_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580622595,
      "name": "unregister_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:7568",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_modify_direct_caller",
        "kernel/trace/ftrace.c:unregister_ftrace_direct"
      ],
      "caller_func": [
        "kernel/livepatch/patch.c:klp_unpatch_func",
        "kernel/kprobes.c:__disarm_kprobe_ftrace",
        "kernel/trace/trace_functions.c:func_set_flag",
        "kernel/trace/trace_functions.c:function_trace_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed",
        "kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "kernel/trace/trace_event_perf.c:perf_ftrace_event_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580608592,
      "name": "unregister_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int unregister_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "unregister_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580794419,
      "name": "unregister_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:7571",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_modify_direct_caller",
        "kernel/trace/ftrace.c:unregister_ftrace_direct"
      ],
      "caller_func": [
        "kernel/livepatch/patch.c:__klp_unpatch_object",
        "kernel/kprobes.c:__disarm_kprobe_ftrace",
        "kernel/trace/trace_functions.c:func_set_flag",
        "kernel/trace/trace_functions.c:function_trace_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed",
        "kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "kernel/trace/trace_event_perf.c:perf_ftrace_event_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580780144,
      "name": "unregister_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int unregister_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "unregister_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581016552,
      "name": "unregister_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:8011",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:modify_ftrace_direct_multi",
        "kernel/trace/ftrace.c:unregister_ftrace_direct_multi",
        "kernel/trace/ftrace.c:ftrace_modify_direct_caller",
        "kernel/trace/ftrace.c:unregister_ftrace_direct"
      ],
      "caller_func": [
        "kernel/livepatch/patch.c:klp_unpatch_func",
        "kernel/kprobes.c:__disarm_kprobe_ftrace",
        "kernel/trace/trace_functions.c:func_set_flag",
        "kernel/trace/trace_functions.c:function_trace_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed",
        "kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "kernel/trace/trace_event_perf.c:perf_ftrace_event_register",
        "kernel/trace/fprobe.c:unregister_fprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580999504,
      "name": "unregister_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int unregister_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "unregister_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unregister_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:8263",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/patch.c:klp_unpatch_func",
        "kernel/kprobes.c:disarm_kprobe_ftrace",
        "kernel/trace/ftrace.c:unregister_ftrace_direct_multi",
        "kernel/trace/ftrace.c:ftrace_modify_direct_caller",
        "kernel/trace/ftrace.c:unregister_ftrace_direct",
        "kernel/trace/trace_functions.c:func_set_flag",
        "kernel/trace/trace_functions.c:function_trace_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed",
        "kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "kernel/trace/trace_event_perf.c:perf_ftrace_event_register",
        "kernel/trace/fprobe.c:unregister_fprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596002847,
      "name": "unregister_ftrace_function.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071581298608,
      "name": "unregister_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
int unregister_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "unregister_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unregister_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:8078",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/patch.c:__klp_unpatch_object",
        "kernel/kprobes.c:disarm_kprobe_ftrace",
        "kernel/trace/ftrace.c:unregister_ftrace_direct",
        "kernel/trace/trace_functions.c:func_set_flag",
        "kernel/trace/trace_functions.c:function_trace_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed",
        "kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "kernel/trace/trace_event_perf.c:perf_ftrace_event_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596521387,
      "name": "unregister_ftrace_function.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071581394080,
      "name": "unregister_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
int unregister_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "unregister_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unregister_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:8078",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/patch.c:__klp_unpatch_object",
        "kernel/kprobes.c:disarm_kprobe_ftrace",
        "kernel/trace/ftrace.c:unregister_ftrace_direct",
        "kernel/trace/trace_functions.c:func_set_flag",
        "kernel/trace/trace_functions.c:function_trace_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed",
        "kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "kernel/trace/trace_event_perf.c:perf_ftrace_event_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597421750,
      "name": "unregister_ftrace_function.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071581501824,
      "name": "unregister_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
int unregister_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "unregister_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491807776,
      "name": "unregister_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6753",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_functions.c:function_trace_reset",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "kernel/trace/trace_event_perf.c:perf_ftrace_event_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491807776,
      "name": "unregister_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int unregister_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "unregister_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225756184,
      "name": "unregister_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6753",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_functions.c:function_trace_reset",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "kernel/trace/trace_event_perf.c:perf_ftrace_event_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225756184,
      "name": "unregister_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int unregister_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "unregister_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284864896,
      "name": "unregister_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6753",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/patch.c:__klp_unpatch_object",
        "kernel/trace/trace_functions.c:function_trace_reset",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "kernel/trace/trace_event_perf.c:perf_ftrace_event_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284864896,
      "name": "unregister_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int unregister_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "unregister_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272119480,
      "name": "unregister_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6753",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_functions.c:function_trace_reset",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "kernel/trace/trace_event_perf.c:perf_ftrace_event_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272119480,
      "name": "unregister_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int unregister_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "unregister_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580495120,
      "name": "unregister_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6753",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/patch.c:__klp_unpatch_object",
        "kernel/trace/trace_functions.c:function_trace_reset",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "kernel/trace/trace_event_perf.c:perf_ftrace_event_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580495120,
      "name": "unregister_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int unregister_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "unregister_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580442144,
      "name": "unregister_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6753",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/patch.c:__klp_unpatch_object",
        "kernel/trace/trace_functions.c:function_trace_reset",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "kernel/trace/trace_event_perf.c:perf_ftrace_event_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580442144,
      "name": "unregister_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int unregister_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "unregister_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580486368,
      "name": "unregister_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6753",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/patch.c:__klp_unpatch_object",
        "kernel/trace/trace_functions.c:function_trace_reset",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "kernel/trace/trace_event_perf.c:perf_ftrace_event_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580486368,
      "name": "unregister_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int unregister_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "unregister_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580542576,
      "name": "unregister_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6753",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/patch.c:__klp_unpatch_object",
        "kernel/trace/trace_functions.c:function_trace_reset",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "kernel/trace/trace_event_perf.c:perf_ftrace_event_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580542576,
      "name": "unregister_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
