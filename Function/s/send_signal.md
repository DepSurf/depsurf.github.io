# Function: <code>send_signal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int send_signal(int sig, struct siginfo * info, struct task_struct * t, int group)
```

```json
{
  "name": "send_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579428912,
      "name": "send_signal",
      "external": false,
      "loc": "kernel/signal.c:1076",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:force_sig_info",
        "kernel/signal.c:do_send_sig_info",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:get_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579428912,
      "name": "send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
int send_signal(int sig, struct siginfo * info, struct task_struct * t, int group)
```

```json
{
  "name": "send_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579441328,
      "name": "send_signal",
      "external": false,
      "loc": "kernel/signal.c:1076",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:force_sig_info",
        "kernel/signal.c:do_send_sig_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579441328,
      "name": "send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
int send_signal(int sig, struct siginfo * info, struct task_struct * t, int group)
```

```json
{
  "name": "send_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579461696,
      "name": "send_signal",
      "external": false,
      "loc": "kernel/signal.c:1082",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:force_sig_info",
        "kernel/signal.c:do_send_sig_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579461696,
      "name": "send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
int send_signal(int sig, struct siginfo * info, struct task_struct * t, int group)
```

```json
{
  "name": "send_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579450208,
      "name": "send_signal",
      "external": false,
      "loc": "kernel/signal.c:1096",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:force_sig_info",
        "kernel/signal.c:do_send_sig_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579450208,
      "name": "send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
int send_signal(int sig, struct siginfo * info, struct task_struct * t, int group)
```

```json
{
  "name": "send_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579478608,
      "name": "send_signal",
      "external": false,
      "loc": "kernel/signal.c:1097",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:force_sig_info",
        "kernel/signal.c:do_send_sig_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579478608,
      "name": "send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
int send_signal(int sig, struct siginfo * info, struct task_struct * t, int group)
```

```json
{
  "name": "send_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579494752,
      "name": "send_signal",
      "external": false,
      "loc": "kernel/signal.c:1105",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kdb_send_sig",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:force_sig_info",
        "kernel/signal.c:do_send_sig_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579494752,
      "name": "send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
int send_signal(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type)
```

```json
{
  "name": "send_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579528304,
      "name": "send_signal",
      "external": false,
      "loc": "kernel/signal.c:1194",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kdb_send_sig",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:force_sig_info",
        "kernel/signal.c:do_send_sig_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579528304,
      "name": "send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
int send_signal(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type)
```

```json
{
  "name": "send_signal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579569854,
      "name": "send_signal",
      "external": false,
      "loc": "kernel/signal.c:1203",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:kdb_send_sig"
      ],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:do_send_sig_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579552224,
      "name": "send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
int send_signal(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type)
```

```json
{
  "name": "send_signal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579596302,
      "name": "send_signal",
      "external": false,
      "loc": "kernel/signal.c:1208",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:kdb_send_sig"
      ],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:do_send_sig_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579578352,
      "name": "send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
int send_signal(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type)
```

```json
{
  "name": "send_signal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579628894,
      "name": "send_signal",
      "external": false,
      "loc": "kernel/signal.c:1208",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:kdb_send_sig"
      ],
      "caller_func": [
        "kernel/signal.c:ptrace_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:do_send_sig_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579614400,
      "name": "send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
int send_signal(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type)
```

```json
{
  "name": "send_signal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579608926,
      "name": "send_signal",
      "external": false,
      "loc": "kernel/signal.c:1209",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:kdb_send_sig"
      ],
      "caller_func": [
        "kernel/signal.c:ptrace_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:do_send_sig_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579594624,
      "name": "send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
int send_signal(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type)
```

```json
{
  "name": "send_signal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579615374,
      "name": "send_signal",
      "external": false,
      "loc": "kernel/signal.c:1211",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:kdb_send_sig"
      ],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:do_send_sig_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579600256,
      "name": "send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
int send_signal(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type)
```

```json
{
  "name": "send_signal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579691644,
      "name": "send_signal",
      "external": false,
      "loc": "kernel/signal.c:1212",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:kdb_send_sig"
      ],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:do_send_sig_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579675248,
      "name": "send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int send_signal(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type)
```

```json
{
  "name": "send_signal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490760900,
      "name": "send_signal",
      "external": false,
      "loc": "kernel/signal.c:1208",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:kdb_send_sig"
      ],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:do_send_sig_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490741320,
      "name": "send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
int send_signal(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type)
```

```json
{
  "name": "send_signal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224808040,
      "name": "send_signal",
      "external": false,
      "loc": "kernel/signal.c:1208",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:kdb_send_sig"
      ],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:do_send_sig_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224791924,
      "name": "send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
int send_signal(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type)
```

```json
{
  "name": "send_signal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283586944,
      "name": "send_signal",
      "external": false,
      "loc": "kernel/signal.c:1208",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:kdb_send_sig"
      ],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:do_send_sig_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283565040,
      "name": "send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
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
int send_signal(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type)
```

```json
{
  "name": "send_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271447240,
      "name": "send_signal",
      "external": false,
      "loc": "kernel/signal.c:1208",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:do_send_sig_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271447240,
      "name": "send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
int send_signal(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type)
```

```json
{
  "name": "send_signal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579572606,
      "name": "send_signal",
      "external": false,
      "loc": "kernel/signal.c:1208",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:kdb_send_sig"
      ],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:do_send_sig_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579554656,
      "name": "send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
int send_signal(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type)
```

```json
{
  "name": "send_signal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579501214,
      "name": "send_signal",
      "external": false,
      "loc": "kernel/signal.c:1208",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:kdb_send_sig"
      ],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:do_send_sig_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579483360,
      "name": "send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
int send_signal(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type)
```

```json
{
  "name": "send_signal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579569886,
      "name": "send_signal",
      "external": false,
      "loc": "kernel/signal.c:1208",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:kdb_send_sig"
      ],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:do_send_sig_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579551936,
      "name": "send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
int send_signal(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type)
```

```json
{
  "name": "send_signal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579603376,
      "name": "send_signal",
      "external": false,
      "loc": "kernel/signal.c:1208",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:kdb_send_sig"
      ],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:do_send_sig_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579585072,
      "name": "send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum pid_type type</code>
</li>
<li>
<b>Param removed. </b>
<code>int group</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct siginfo * info</code> ➡️ <code>struct kernel_siginfo * info</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int send_signal(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type)
```
</details>
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
