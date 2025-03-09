# Function: <code>recalc_sigpending</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void recalc_sigpending()
```

```json
{
  "name": "recalc_sigpending",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579423072,
      "name": "recalc_sigpending",
      "external": true,
      "loc": "kernel/signal.c:158",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:do_sigtimedwait",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579423072,
      "name": "recalc_sigpending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void recalc_sigpending()
```

```json
{
  "name": "recalc_sigpending",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579435808,
      "name": "recalc_sigpending",
      "external": true,
      "loc": "kernel/signal.c:158",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579435808,
      "name": "recalc_sigpending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void recalc_sigpending()
```

```json
{
  "name": "recalc_sigpending",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579456160,
      "name": "recalc_sigpending",
      "external": true,
      "loc": "kernel/signal.c:158",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579456160,
      "name": "recalc_sigpending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void recalc_sigpending()
```

```json
{
  "name": "recalc_sigpending",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579443920,
      "name": "recalc_sigpending",
      "external": true,
      "loc": "kernel/signal.c:164",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579443920,
      "name": "recalc_sigpending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void recalc_sigpending()
```

```json
{
  "name": "recalc_sigpending",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579472224,
      "name": "recalc_sigpending",
      "external": true,
      "loc": "kernel/signal.c:166",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579472224,
      "name": "recalc_sigpending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void recalc_sigpending()
```

```json
{
  "name": "recalc_sigpending",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579487488,
      "name": "recalc_sigpending",
      "external": true,
      "loc": "kernel/signal.c:167",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579487488,
      "name": "recalc_sigpending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void recalc_sigpending()
```

```json
{
  "name": "recalc_sigpending",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579520064,
      "name": "recalc_sigpending",
      "external": true,
      "loc": "kernel/signal.c:172",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:calculate_sigpending",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579520064,
      "name": "recalc_sigpending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void recalc_sigpending()
```

```json
{
  "name": "recalc_sigpending",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579539776,
      "name": "recalc_sigpending",
      "external": true,
      "loc": "kernel/signal.c:182",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:calculate_sigpending",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579539776,
      "name": "recalc_sigpending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void recalc_sigpending()
```

```json
{
  "name": "recalc_sigpending",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579565872,
      "name": "recalc_sigpending",
      "external": true,
      "loc": "kernel/signal.c:182",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:calculate_sigpending",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579565872,
      "name": "recalc_sigpending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void recalc_sigpending()
```

```json
{
  "name": "recalc_sigpending",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579599568,
      "name": "recalc_sigpending",
      "external": true,
      "loc": "kernel/signal.c:182",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:dequeue_synchronous_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:calculate_sigpending",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "fs/io_uring.c:io_cqring_wait",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579599568,
      "name": "recalc_sigpending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void recalc_sigpending()
```

```json
{
  "name": "recalc_sigpending",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579579776,
      "name": "recalc_sigpending",
      "external": true,
      "loc": "kernel/signal.c:182",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:dequeue_synchronous_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:calculate_sigpending",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579579776,
      "name": "recalc_sigpending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void recalc_sigpending()
```

```json
{
  "name": "recalc_sigpending",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579585456,
      "name": "recalc_sigpending",
      "external": true,
      "loc": "kernel/signal.c:181",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:calculate_sigpending",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579585456,
      "name": "recalc_sigpending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void recalc_sigpending()
```

```json
{
  "name": "recalc_sigpending",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579659648,
      "name": "recalc_sigpending",
      "external": true,
      "loc": "kernel/signal.c:182",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:calculate_sigpending",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579659648,
      "name": "recalc_sigpending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void recalc_sigpending()
```

```json
{
  "name": "recalc_sigpending",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579757104,
      "name": "recalc_sigpending",
      "external": true,
      "loc": "kernel/signal.c:182",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:calculate_sigpending",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579757104,
      "name": "recalc_sigpending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void recalc_sigpending()
```

```json
{
  "name": "recalc_sigpending",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579889872,
      "name": "recalc_sigpending",
      "external": true,
      "loc": "kernel/signal.c:182",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:calculate_sigpending",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579889872,
      "name": "recalc_sigpending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void recalc_sigpending()
```

```json
{
  "name": "recalc_sigpending",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579939056,
      "name": "recalc_sigpending",
      "external": true,
      "loc": "kernel/signal.c:183",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:calculate_sigpending",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579939056,
      "name": "recalc_sigpending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void recalc_sigpending()
```

```json
{
  "name": "recalc_sigpending",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579977328,
      "name": "recalc_sigpending",
      "external": true,
      "loc": "kernel/signal.c:174",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:calculate_sigpending",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579977328,
      "name": "recalc_sigpending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void recalc_sigpending()
```

```json
{
  "name": "recalc_sigpending",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490726304,
      "name": "recalc_sigpending",
      "external": true,
      "loc": "kernel/signal.c:182",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:calculate_sigpending",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490726304,
      "name": "recalc_sigpending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void recalc_sigpending()
```

```json
{
  "name": "recalc_sigpending",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224780364,
      "name": "recalc_sigpending",
      "external": true,
      "loc": "kernel/signal.c:182",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:calculate_sigpending",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224780364,
      "name": "recalc_sigpending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void recalc_sigpending()
```

```json
{
  "name": "recalc_sigpending",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283548688,
      "name": "recalc_sigpending",
      "external": true,
      "loc": "kernel/signal.c:182",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:calculate_sigpending",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283548688,
      "name": "recalc_sigpending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void recalc_sigpending()
```

```json
{
  "name": "recalc_sigpending",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271439440,
      "name": "recalc_sigpending",
      "external": true,
      "loc": "kernel/signal.c:182",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:__se_sys_rt_sigtimedwait",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:calculate_sigpending",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271439440,
      "name": "recalc_sigpending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void recalc_sigpending()
```

```json
{
  "name": "recalc_sigpending",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579542176,
      "name": "recalc_sigpending",
      "external": true,
      "loc": "kernel/signal.c:182",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:calculate_sigpending",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579542176,
      "name": "recalc_sigpending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void recalc_sigpending()
```

```json
{
  "name": "recalc_sigpending",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579470928,
      "name": "recalc_sigpending",
      "external": true,
      "loc": "kernel/signal.c:182",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:calculate_sigpending",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579470928,
      "name": "recalc_sigpending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void recalc_sigpending()
```

```json
{
  "name": "recalc_sigpending",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579539456,
      "name": "recalc_sigpending",
      "external": true,
      "loc": "kernel/signal.c:182",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:calculate_sigpending",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579539456,
      "name": "recalc_sigpending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void recalc_sigpending()
```

```json
{
  "name": "recalc_sigpending",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579573136,
      "name": "recalc_sigpending",
      "external": true,
      "loc": "kernel/signal.c:182",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:calculate_sigpending",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579573136,
      "name": "recalc_sigpending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
