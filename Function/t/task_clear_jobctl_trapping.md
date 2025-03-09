# Function: <code>task_clear_jobctl_trapping</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void task_clear_jobctl_trapping(struct task_struct * task)
```

```json
{
  "name": "task_clear_jobctl_trapping",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579425280,
      "name": "task_clear_jobctl_trapping",
      "external": true,
      "loc": "kernel/signal.c:276",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:ptrace_stop"
      ],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579425280,
      "name": "task_clear_jobctl_trapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void task_clear_jobctl_trapping(struct task_struct * task)
```

```json
{
  "name": "task_clear_jobctl_trapping",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579442063,
      "name": "task_clear_jobctl_trapping",
      "external": true,
      "loc": "kernel/signal.c:276",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:ptrace_stop"
      ],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579437696,
      "name": "task_clear_jobctl_trapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void task_clear_jobctl_trapping(struct task_struct * task)
```

```json
{
  "name": "task_clear_jobctl_trapping",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579462419,
      "name": "task_clear_jobctl_trapping",
      "external": true,
      "loc": "kernel/signal.c:276",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:ptrace_stop"
      ],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579458032,
      "name": "task_clear_jobctl_trapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void task_clear_jobctl_trapping(struct task_struct * task)
```

```json
{
  "name": "task_clear_jobctl_trapping",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579450915,
      "name": "task_clear_jobctl_trapping",
      "external": true,
      "loc": "kernel/signal.c:282",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:ptrace_stop"
      ],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579445760,
      "name": "task_clear_jobctl_trapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void task_clear_jobctl_trapping(struct task_struct * task)
```

```json
{
  "name": "task_clear_jobctl_trapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579474176,
      "name": "task_clear_jobctl_trapping",
      "external": true,
      "loc": "kernel/signal.c:284",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/signal.c:ptrace_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579474176,
      "name": "task_clear_jobctl_trapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void task_clear_jobctl_trapping(struct task_struct * task)
```

```json
{
  "name": "task_clear_jobctl_trapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579490512,
      "name": "task_clear_jobctl_trapping",
      "external": true,
      "loc": "kernel/signal.c:286",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/signal.c:ptrace_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579490512,
      "name": "task_clear_jobctl_trapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void task_clear_jobctl_trapping(struct task_struct * task)
```

```json
{
  "name": "task_clear_jobctl_trapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579523984,
      "name": "task_clear_jobctl_trapping",
      "external": true,
      "loc": "kernel/signal.c:303",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/signal.c:ptrace_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579523984,
      "name": "task_clear_jobctl_trapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void task_clear_jobctl_trapping(struct task_struct * task)
```

```json
{
  "name": "task_clear_jobctl_trapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579543648,
      "name": "task_clear_jobctl_trapping",
      "external": true,
      "loc": "kernel/signal.c:313",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/signal.c:ptrace_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579543648,
      "name": "task_clear_jobctl_trapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void task_clear_jobctl_trapping(struct task_struct * task)
```

```json
{
  "name": "task_clear_jobctl_trapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579569760,
      "name": "task_clear_jobctl_trapping",
      "external": true,
      "loc": "kernel/signal.c:313",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/signal.c:ptrace_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579569760,
      "name": "task_clear_jobctl_trapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void task_clear_jobctl_trapping(struct task_struct * task)
```

```json
{
  "name": "task_clear_jobctl_trapping",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579615263,
      "name": "task_clear_jobctl_trapping",
      "external": true,
      "loc": "kernel/signal.c:313",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:task_participate_group_stop"
      ],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579605712,
      "name": "task_clear_jobctl_trapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void task_clear_jobctl_trapping(struct task_struct * task)
```

```json
{
  "name": "task_clear_jobctl_trapping",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579595535,
      "name": "task_clear_jobctl_trapping",
      "external": true,
      "loc": "kernel/signal.c:313",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:task_participate_group_stop"
      ],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579585920,
      "name": "task_clear_jobctl_trapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void task_clear_jobctl_trapping(struct task_struct * task)
```

```json
{
  "name": "task_clear_jobctl_trapping",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579601167,
      "name": "task_clear_jobctl_trapping",
      "external": true,
      "loc": "kernel/signal.c:311",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:task_participate_group_stop"
      ],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579593104,
      "name": "task_clear_jobctl_trapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void task_clear_jobctl_trapping(struct task_struct * task)
```

```json
{
  "name": "task_clear_jobctl_trapping",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579676614,
      "name": "task_clear_jobctl_trapping",
      "external": true,
      "loc": "kernel/signal.c:312",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:task_participate_group_stop"
      ],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579670560,
      "name": "task_clear_jobctl_trapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void task_clear_jobctl_trapping(struct task_struct * task)
```

```json
{
  "name": "task_clear_jobctl_trapping",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579768461,
      "name": "task_clear_jobctl_trapping",
      "external": true,
      "loc": "kernel/signal.c:312",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:task_participate_group_stop"
      ],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579767344,
      "name": "task_clear_jobctl_trapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void task_clear_jobctl_trapping(struct task_struct * task)
```

```json
{
  "name": "task_clear_jobctl_trapping",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579900269,
      "name": "task_clear_jobctl_trapping",
      "external": true,
      "loc": "kernel/signal.c:312",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:task_participate_group_stop"
      ],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579898992,
      "name": "task_clear_jobctl_trapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void task_clear_jobctl_trapping(struct task_struct * task)
```

```json
{
  "name": "task_clear_jobctl_trapping",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579949933,
      "name": "task_clear_jobctl_trapping",
      "external": true,
      "loc": "kernel/signal.c:313",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:task_participate_group_stop"
      ],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579948496,
      "name": "task_clear_jobctl_trapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void task_clear_jobctl_trapping(struct task_struct * task)
```

```json
{
  "name": "task_clear_jobctl_trapping",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579989135,
      "name": "task_clear_jobctl_trapping",
      "external": true,
      "loc": "kernel/signal.c:304",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:task_participate_group_stop"
      ],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579987728,
      "name": "task_clear_jobctl_trapping",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void task_clear_jobctl_trapping(struct task_struct * task)
```

```json
{
  "name": "task_clear_jobctl_trapping",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490742960,
      "name": "task_clear_jobctl_trapping",
      "external": true,
      "loc": "kernel/signal.c:313",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:ptrace_stop"
      ],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490731712,
      "name": "task_clear_jobctl_trapping",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void task_clear_jobctl_trapping(struct task_struct * task)
```

```json
{
  "name": "task_clear_jobctl_trapping",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224793492,
      "name": "task_clear_jobctl_trapping",
      "external": true,
      "loc": "kernel/signal.c:313",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:ptrace_stop"
      ],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224783888,
      "name": "task_clear_jobctl_trapping",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void task_clear_jobctl_trapping(struct task_struct * task)
```

```json
{
  "name": "task_clear_jobctl_trapping",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283566980,
      "name": "task_clear_jobctl_trapping",
      "external": true,
      "loc": "kernel/signal.c:313",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:task_clear_jobctl_pending"
      ],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/ptrace.c:__ptrace_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283554320,
      "name": "task_clear_jobctl_trapping",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void task_clear_jobctl_trapping(struct task_struct * task)
```

```json
{
  "name": "task_clear_jobctl_trapping",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271448430,
      "name": "task_clear_jobctl_trapping",
      "external": true,
      "loc": "kernel/signal.c:313",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:ptrace_stop"
      ],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271441826,
      "name": "task_clear_jobctl_trapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void task_clear_jobctl_trapping(struct task_struct * task)
```

```json
{
  "name": "task_clear_jobctl_trapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579546064,
      "name": "task_clear_jobctl_trapping",
      "external": true,
      "loc": "kernel/signal.c:313",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/signal.c:ptrace_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579546064,
      "name": "task_clear_jobctl_trapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void task_clear_jobctl_trapping(struct task_struct * task)
```

```json
{
  "name": "task_clear_jobctl_trapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579474800,
      "name": "task_clear_jobctl_trapping",
      "external": true,
      "loc": "kernel/signal.c:313",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/signal.c:ptrace_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579474800,
      "name": "task_clear_jobctl_trapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void task_clear_jobctl_trapping(struct task_struct * task)
```

```json
{
  "name": "task_clear_jobctl_trapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579543344,
      "name": "task_clear_jobctl_trapping",
      "external": true,
      "loc": "kernel/signal.c:313",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/signal.c:ptrace_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579543344,
      "name": "task_clear_jobctl_trapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void task_clear_jobctl_trapping(struct task_struct * task)
```

```json
{
  "name": "task_clear_jobctl_trapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579576336,
      "name": "task_clear_jobctl_trapping",
      "external": true,
      "loc": "kernel/signal.c:313",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/signal.c:ptrace_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579576336,
      "name": "task_clear_jobctl_trapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
