# Function: <code>signal_wake_up_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void signal_wake_up_state(struct task_struct * t, unsigned int state)
```

```json
{
  "name": "signal_wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579426160,
      "name": "signal_wake_up_state",
      "external": true,
      "loc": "kernel/signal.c:639",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/signal.c:recalc_sigpending_and_wake",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:retarget_shared_pending",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/freezer.c:freeze_task",
        "fs/coredump.c:zap_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579426160,
      "name": "signal_wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void signal_wake_up_state(struct task_struct * t, unsigned int state)
```

```json
{
  "name": "signal_wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579438576,
      "name": "signal_wake_up_state",
      "external": true,
      "loc": "kernel/signal.c:639",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/signal.c:retarget_shared_pending",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:recalc_sigpending_and_wake",
        "kernel/freezer.c:freeze_task",
        "fs/coredump.c:zap_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579438576,
      "name": "signal_wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void signal_wake_up_state(struct task_struct * t, unsigned int state)
```

```json
{
  "name": "signal_wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579458928,
      "name": "signal_wake_up_state",
      "external": true,
      "loc": "kernel/signal.c:645",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/signal.c:retarget_shared_pending",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:recalc_sigpending_and_wake",
        "kernel/freezer.c:freeze_task",
        "fs/coredump.c:zap_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579458928,
      "name": "signal_wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void signal_wake_up_state(struct task_struct * t, unsigned int state)
```

```json
{
  "name": "signal_wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579446560,
      "name": "signal_wake_up_state",
      "external": true,
      "loc": "kernel/signal.c:659",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/signal.c:retarget_shared_pending",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:recalc_sigpending_and_wake",
        "kernel/freezer.c:freeze_task",
        "fs/coredump.c:zap_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579446560,
      "name": "signal_wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void signal_wake_up_state(struct task_struct * t, unsigned int state)
```

```json
{
  "name": "signal_wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579474944,
      "name": "signal_wake_up_state",
      "external": true,
      "loc": "kernel/signal.c:661",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/signal.c:retarget_shared_pending",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:recalc_sigpending_and_wake",
        "kernel/freezer.c:freeze_task",
        "fs/coredump.c:zap_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579474944,
      "name": "signal_wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void signal_wake_up_state(struct task_struct * t, unsigned int state)
```

```json
{
  "name": "signal_wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579491280,
      "name": "signal_wake_up_state",
      "external": true,
      "loc": "kernel/signal.c:667",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/signal.c:retarget_shared_pending",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:recalc_sigpending_and_wake",
        "kernel/livepatch/transition.c:klp_send_signals",
        "kernel/freezer.c:freeze_task",
        "fs/coredump.c:zap_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579491280,
      "name": "signal_wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void signal_wake_up_state(struct task_struct * t, unsigned int state)
```

```json
{
  "name": "signal_wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579524832,
      "name": "signal_wake_up_state",
      "external": true,
      "loc": "kernel/signal.c:744",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/signal.c:retarget_shared_pending",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:recalc_sigpending_and_wake",
        "kernel/livepatch/transition.c:klp_send_signals",
        "kernel/freezer.c:freeze_task",
        "fs/coredump.c:zap_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579524832,
      "name": "signal_wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void signal_wake_up_state(struct task_struct * t, unsigned int state)
```

```json
{
  "name": "signal_wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579544496,
      "name": "signal_wake_up_state",
      "external": true,
      "loc": "kernel/signal.c:754",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/signal.c:retarget_shared_pending",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:recalc_sigpending_and_wake",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/freezer.c:freeze_task",
        "kernel/cgroup/freezer.c:cgroup_freeze_task",
        "fs/coredump.c:zap_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579544496,
      "name": "signal_wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void signal_wake_up_state(struct task_struct * t, unsigned int state)
```

```json
{
  "name": "signal_wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579570608,
      "name": "signal_wake_up_state",
      "external": true,
      "loc": "kernel/signal.c:759",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/signal.c:retarget_shared_pending",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:recalc_sigpending_and_wake",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/freezer.c:freeze_task",
        "kernel/cgroup/freezer.c:cgroup_freeze_task",
        "fs/coredump.c:zap_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579570608,
      "name": "signal_wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void signal_wake_up_state(struct task_struct * t, unsigned int state)
```

```json
{
  "name": "signal_wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579616512,
      "name": "signal_wake_up_state",
      "external": true,
      "loc": "kernel/signal.c:759",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:ptrace_trap_notify"
      ],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/livepatch/transition.c:klp_send_signals",
        "kernel/freezer.c:freeze_task",
        "kernel/cgroup/freezer.c:cgroup_freeze_task",
        "fs/coredump.c:zap_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579609168,
      "name": "signal_wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void signal_wake_up_state(struct task_struct * t, unsigned int state)
```

```json
{
  "name": "signal_wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579596784,
      "name": "signal_wake_up_state",
      "external": true,
      "loc": "kernel/signal.c:760",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:ptrace_trap_notify"
      ],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/livepatch/transition.c:klp_send_signals",
        "kernel/freezer.c:freeze_task",
        "kernel/cgroup/freezer.c:cgroup_freeze_task",
        "fs/coredump.c:zap_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579589392,
      "name": "signal_wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void signal_wake_up_state(struct task_struct * t, unsigned int state)
```

```json
{
  "name": "signal_wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579602272,
      "name": "signal_wake_up_state",
      "external": true,
      "loc": "kernel/signal.c:759",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:ptrace_trap_notify"
      ],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/freezer.c:freeze_task",
        "kernel/cgroup/freezer.c:cgroup_freeze_task",
        "fs/coredump.c:zap_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579596560,
      "name": "signal_wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void signal_wake_up_state(struct task_struct * t, unsigned int state)
```

```json
{
  "name": "signal_wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579677424,
      "name": "signal_wake_up_state",
      "external": true,
      "loc": "kernel/signal.c:760",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:ptrace_trap_notify"
      ],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/freezer.c:freeze_task",
        "kernel/cgroup/freezer.c:cgroup_freeze_task",
        "fs/coredump.c:zap_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579671392,
      "name": "signal_wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void signal_wake_up_state(struct task_struct * t, unsigned int state)
```

```json
{
  "name": "signal_wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579781439,
      "name": "signal_wake_up_state",
      "external": true,
      "loc": "kernel/signal.c:763",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:ptrace_trap_notify"
      ],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/freezer.c:freeze_task",
        "kernel/cgroup/freezer.c:cgroup_freeze_task",
        "fs/coredump.c:coredump_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579768272,
      "name": "signal_wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void signal_wake_up_state(struct task_struct * t, unsigned int state)
```

```json
{
  "name": "signal_wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579914175,
      "name": "signal_wake_up_state",
      "external": true,
      "loc": "kernel/signal.c:763",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:ptrace_trap_notify"
      ],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/freezer.c:freeze_task",
        "kernel/cgroup/freezer.c:cgroup_freeze_task",
        "fs/coredump.c:coredump_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579900064,
      "name": "signal_wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void signal_wake_up_state(struct task_struct * t, unsigned int state)
```

```json
{
  "name": "signal_wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579963967,
      "name": "signal_wake_up_state",
      "external": true,
      "loc": "kernel/signal.c:768",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:ptrace_trap_notify"
      ],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/freezer.c:freeze_task",
        "kernel/cgroup/freezer.c:cgroup_freeze_task",
        "fs/coredump.c:coredump_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579949728,
      "name": "signal_wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void signal_wake_up_state(struct task_struct * t, unsigned int state)
```

```json
{
  "name": "signal_wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580003262,
      "name": "signal_wake_up_state",
      "external": true,
      "loc": "kernel/signal.c:759",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:ptrace_trap_notify"
      ],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/freezer.c:freeze_task",
        "kernel/cgroup/freezer.c:cgroup_freeze_task",
        "fs/coredump.c:coredump_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579988960,
      "name": "signal_wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void signal_wake_up_state(struct task_struct * t, unsigned int state)
```

```json
{
  "name": "signal_wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490732968,
      "name": "signal_wake_up_state",
      "external": true,
      "loc": "kernel/signal.c:759",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/signal.c:retarget_shared_pending",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:recalc_sigpending_and_wake",
        "kernel/freezer.c:freeze_task",
        "kernel/cgroup/freezer.c:cgroup_freeze_task",
        "fs/coredump.c:zap_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490732968,
      "name": "signal_wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void signal_wake_up_state(struct task_struct * t, unsigned int state)
```

```json
{
  "name": "signal_wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224784932,
      "name": "signal_wake_up_state",
      "external": true,
      "loc": "kernel/signal.c:759",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__se_sys_ptrace",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/signal.c:retarget_shared_pending",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:recalc_sigpending_and_wake",
        "kernel/freezer.c:freeze_task",
        "kernel/cgroup/freezer.c:cgroup_freeze_task",
        "fs/coredump.c:zap_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224784932,
      "name": "signal_wake_up_state",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void signal_wake_up_state(struct task_struct * t, unsigned int state)
```

```json
{
  "name": "signal_wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283555568,
      "name": "signal_wake_up_state",
      "external": true,
      "loc": "kernel/signal.c:759",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/signal.c:retarget_shared_pending",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:ptrace_trap_notify",
        "kernel/signal.c:recalc_sigpending_and_wake",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/freezer.c:freeze_task",
        "kernel/cgroup/freezer.c:cgroup_freeze_task",
        "fs/coredump.c:zap_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283555568,
      "name": "signal_wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void signal_wake_up_state(struct task_struct * t, unsigned int state)
```

```json
{
  "name": "signal_wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271442776,
      "name": "signal_wake_up_state",
      "external": true,
      "loc": "kernel/signal.c:759",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__se_sys_ptrace",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/signal.c:retarget_shared_pending",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:recalc_sigpending_and_wake",
        "kernel/freezer.c:freeze_task",
        "kernel/cgroup/freezer.c:cgroup_freeze_task",
        "fs/coredump.c:zap_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271442776,
      "name": "signal_wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void signal_wake_up_state(struct task_struct * t, unsigned int state)
```

```json
{
  "name": "signal_wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579546912,
      "name": "signal_wake_up_state",
      "external": true,
      "loc": "kernel/signal.c:759",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/signal.c:retarget_shared_pending",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:recalc_sigpending_and_wake",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/freezer.c:freeze_task",
        "kernel/cgroup/freezer.c:cgroup_freeze_task",
        "fs/coredump.c:zap_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579546912,
      "name": "signal_wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void signal_wake_up_state(struct task_struct * t, unsigned int state)
```

```json
{
  "name": "signal_wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579475648,
      "name": "signal_wake_up_state",
      "external": true,
      "loc": "kernel/signal.c:759",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/signal.c:retarget_shared_pending",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:recalc_sigpending_and_wake",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/freezer.c:freeze_task",
        "kernel/cgroup/freezer.c:cgroup_freeze_task",
        "fs/coredump.c:zap_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579475648,
      "name": "signal_wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void signal_wake_up_state(struct task_struct * t, unsigned int state)
```

```json
{
  "name": "signal_wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579544192,
      "name": "signal_wake_up_state",
      "external": true,
      "loc": "kernel/signal.c:759",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/signal.c:retarget_shared_pending",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:recalc_sigpending_and_wake",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/freezer.c:freeze_task",
        "kernel/cgroup/freezer.c:cgroup_freeze_task",
        "fs/coredump.c:zap_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579544192,
      "name": "signal_wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void signal_wake_up_state(struct task_struct * t, unsigned int state)
```

```json
{
  "name": "signal_wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579577184,
      "name": "signal_wake_up_state",
      "external": true,
      "loc": "kernel/signal.c:759",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/signal.c:retarget_shared_pending",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:recalc_sigpending_and_wake",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/freezer.c:freeze_task",
        "kernel/cgroup/freezer.c:cgroup_freeze_task",
        "fs/coredump.c:zap_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579577184,
      "name": "signal_wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
