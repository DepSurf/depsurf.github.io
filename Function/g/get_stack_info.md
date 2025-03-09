# Function: <code>get_stack_info</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int get_stack_info(long unsigned int * stack, struct task_struct * task, struct stack_info * info, long unsigned int * visit_mask)
```

```json
{
  "name": "get_stack_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579042320,
      "name": "get_stack_info",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack_64.c:96",
      "file": "arch/x86/kernel/dumpstack_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579042320,
      "name": "get_stack_info",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int get_stack_info(long unsigned int * stack, struct task_struct * task, struct stack_info * info, long unsigned int * visit_mask)
```

```json
{
  "name": "get_stack_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579034736,
      "name": "get_stack_info",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack_64.c:97",
      "file": "arch/x86/kernel/dumpstack_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/unwind_frame.c:update_stack_state",
        "arch/x86/kernel/unwind_frame.c:unwind_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579034736,
      "name": "get_stack_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
int get_stack_info(long unsigned int * stack, struct task_struct * task, struct stack_info * info, long unsigned int * visit_mask)
```

```json
{
  "name": "get_stack_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579042560,
      "name": "get_stack_info",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack_64.c:107",
      "file": "arch/x86/kernel/dumpstack_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/unwind_frame.c:update_stack_state",
        "arch/x86/kernel/unwind_frame.c:unwind_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579042560,
      "name": "get_stack_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 347
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
int get_stack_info(long unsigned int * stack, struct task_struct * task, struct stack_info * info, long unsigned int * visit_mask)
```

```json
{
  "name": "get_stack_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_stack_info",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack_64.c:107",
      "file": "arch/x86/kernel/dumpstack_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/unwind_frame.c:__unwind_start",
        "arch/x86/kernel/unwind_frame.c:update_stack_state",
        "arch/x86/kernel/unwind_frame.c:unwind_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579047639,
      "name": "get_stack_info.cold.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579047312,
      "name": "get_stack_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
int get_stack_info(long unsigned int * stack, struct task_struct * task, struct stack_info * info, long unsigned int * visit_mask)
```

```json
{
  "name": "get_stack_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_stack_info",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack_64.c:107",
      "file": "arch/x86/kernel/dumpstack_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/unwind_frame.c:__unwind_start",
        "arch/x86/kernel/unwind_frame.c:update_stack_state",
        "arch/x86/kernel/unwind_frame.c:unwind_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579052407,
      "name": "get_stack_info.cold.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579052080,
      "name": "get_stack_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
int get_stack_info(long unsigned int * stack, struct task_struct * task, struct stack_info * info, long unsigned int * visit_mask)
```

```json
{
  "name": "get_stack_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_stack_info",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack_64.c:146",
      "file": "arch/x86/kernel/dumpstack_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/unwind_frame.c:__unwind_start",
        "arch/x86/kernel/unwind_frame.c:update_stack_state",
        "arch/x86/kernel/unwind_frame.c:unwind_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579060092,
      "name": "get_stack_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579059776,
      "name": "get_stack_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
int get_stack_info(long unsigned int * stack, struct task_struct * task, struct stack_info * info, long unsigned int * visit_mask)
```

```json
{
  "name": "get_stack_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_stack_info",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack_64.c:153",
      "file": "arch/x86/kernel/dumpstack_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/unwind_frame.c:__unwind_start",
        "arch/x86/kernel/unwind_frame.c:update_stack_state",
        "arch/x86/kernel/unwind_frame.c:unwind_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579062289,
      "name": "get_stack_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579061968,
      "name": "get_stack_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
int get_stack_info(long unsigned int * stack, struct task_struct * task, struct stack_info * info, long unsigned int * visit_mask)
```

```json
{
  "name": "get_stack_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_stack_info",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack_64.c:150",
      "file": "arch/x86/kernel/dumpstack_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/unwind_frame.c:__unwind_start",
        "arch/x86/kernel/unwind_frame.c:update_stack_state",
        "arch/x86/kernel/unwind_frame.c:unwind_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579070079,
      "name": "get_stack_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579069744,
      "name": "get_stack_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
int get_stack_info(long unsigned int * stack, struct task_struct * task, struct stack_info * info, long unsigned int * visit_mask)
```

```json
{
  "name": "get_stack_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_stack_info",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack_64.c:175",
      "file": "arch/x86/kernel/dumpstack_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/unwind_frame.c:__unwind_start",
        "arch/x86/kernel/unwind_frame.c:update_stack_state",
        "arch/x86/kernel/unwind_frame.c:unwind_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591244689,
      "name": "get_stack_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579074304,
      "name": "get_stack_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int get_stack_info(long unsigned int * stack, struct task_struct * task, struct stack_info * info, long unsigned int * visit_mask)
```

```json
{
  "name": "get_stack_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_stack_info",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack_64.c:185",
      "file": "arch/x86/kernel/dumpstack_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/unwind_frame.c:__unwind_start",
        "arch/x86/kernel/unwind_frame.c:update_stack_state",
        "arch/x86/kernel/unwind_frame.c:unwind_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591188483,
      "name": "get_stack_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579081280,
      "name": "get_stack_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int get_stack_info(long unsigned int * stack, struct task_struct * task, struct stack_info * info, long unsigned int * visit_mask)
```

```json
{
  "name": "get_stack_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_stack_info",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack_64.c:191",
      "file": "arch/x86/kernel/dumpstack_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/unwind_frame.c:__unwind_start",
        "arch/x86/kernel/unwind_frame.c:update_stack_state",
        "arch/x86/kernel/unwind_frame.c:unwind_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592051936,
      "name": "get_stack_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    },
    {
      "addr": 18446744071579104208,
      "name": "get_stack_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int get_stack_info(long unsigned int * stack, struct task_struct * task, struct stack_info * info, long unsigned int * visit_mask)
```

```json
{
  "name": "get_stack_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_stack_info",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack_64.c:191",
      "file": "arch/x86/kernel/dumpstack_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/unwind_frame.c:__unwind_start",
        "arch/x86/kernel/unwind_frame.c:update_stack_state",
        "arch/x86/kernel/unwind_frame.c:unwind_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593818596,
      "name": "get_stack_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071579134512,
      "name": "get_stack_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int get_stack_info(long unsigned int * stack, struct task_struct * task, struct stack_info * info, long unsigned int * visit_mask)
```

```json
{
  "name": "get_stack_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_stack_info",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack_64.c:191",
      "file": "arch/x86/kernel/dumpstack_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/unwind_frame.c:__unwind_start",
        "arch/x86/kernel/unwind_frame.c:update_stack_state",
        "arch/x86/kernel/unwind_frame.c:unwind_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595958471,
      "name": "get_stack_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071579175616,
      "name": "get_stack_info",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int get_stack_info(long unsigned int * stack, struct task_struct * task, struct stack_info * info, long unsigned int * visit_mask)
```

```json
{
  "name": "get_stack_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_stack_info",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack_64.c:191",
      "file": "arch/x86/kernel/dumpstack_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/unwind_frame.c:__unwind_start",
        "arch/x86/kernel/unwind_frame.c:update_stack_state",
        "arch/x86/kernel/unwind_frame.c:unwind_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596475890,
      "name": "get_stack_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071579178992,
      "name": "get_stack_info",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int get_stack_info(long unsigned int * stack, struct task_struct * task, struct stack_info * info, long unsigned int * visit_mask)
```

```json
{
  "name": "get_stack_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_stack_info",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack_64.c:191",
      "file": "arch/x86/kernel/dumpstack_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/unwind_frame.c:__unwind_start",
        "arch/x86/kernel/unwind_frame.c:update_stack_state",
        "arch/x86/kernel/unwind_frame.c:unwind_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597371655,
      "name": "get_stack_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071579208208,
      "name": "get_stack_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int get_stack_info(long unsigned int * stack, struct task_struct * task, struct stack_info * info, long unsigned int * visit_mask)
```

```json
{
  "name": "get_stack_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_stack_info",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack_64.c:153",
      "file": "arch/x86/kernel/dumpstack_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/unwind_frame.c:__unwind_start",
        "arch/x86/kernel/unwind_frame.c:update_stack_state",
        "arch/x86/kernel/unwind_frame.c:unwind_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579062641,
      "name": "get_stack_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579062320,
      "name": "get_stack_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
int get_stack_info(long unsigned int * stack, struct task_struct * task, struct stack_info * info, long unsigned int * visit_mask)
```

```json
{
  "name": "get_stack_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_stack_info",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack_64.c:153",
      "file": "arch/x86/kernel/dumpstack_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/unwind_frame.c:__unwind_start",
        "arch/x86/kernel/unwind_frame.c:update_stack_state",
        "arch/x86/kernel/unwind_frame.c:unwind_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578995377,
      "name": "get_stack_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071578995056,
      "name": "get_stack_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
int get_stack_info(long unsigned int * stack, struct task_struct * task, struct stack_info * info, long unsigned int * visit_mask)
```

```json
{
  "name": "get_stack_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_stack_info",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack_64.c:153",
      "file": "arch/x86/kernel/dumpstack_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/unwind_frame.c:__unwind_start",
        "arch/x86/kernel/unwind_frame.c:update_stack_state",
        "arch/x86/kernel/unwind_frame.c:unwind_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579062225,
      "name": "get_stack_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579061904,
      "name": "get_stack_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
int get_stack_info(long unsigned int * stack, struct task_struct * task, struct stack_info * info, long unsigned int * visit_mask)
```

```json
{
  "name": "get_stack_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_stack_info",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack_64.c:153",
      "file": "arch/x86/kernel/dumpstack_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/unwind_frame.c:__unwind_start",
        "arch/x86/kernel/unwind_frame.c:update_stack_state",
        "arch/x86/kernel/unwind_frame.c:unwind_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579066129,
      "name": "get_stack_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579065808,
      "name": "get_stack_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int get_stack_info(long unsigned int * stack, struct task_struct * task, struct stack_info * info, long unsigned int * visit_mask)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int get_stack_info(long unsigned int * stack, struct task_struct * task, struct stack_info * info, long unsigned int * visit_mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int get_stack_info(long unsigned int * stack, struct task_struct * task, struct stack_info * info, long unsigned int * visit_mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int get_stack_info(long unsigned int * stack, struct task_struct * task, struct stack_info * info, long unsigned int * visit_mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int get_stack_info(long unsigned int * stack, struct task_struct * task, struct stack_info * info, long unsigned int * visit_mask)
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
