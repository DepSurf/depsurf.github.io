# Function: <code>__rseq_handle_notify_resume</code>

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
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void __rseq_handle_notify_resume(struct ksignal * ksig, struct pt_regs * regs)
```

```json
{
  "name": "__rseq_handle_notify_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__rseq_handle_notify_resume",
      "external": true,
      "loc": "kernel/rseq.c:263",
      "file": "kernel/rseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:exit_to_usermode_loop",
        "arch/x86/kernel/signal.c:do_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580854012,
      "name": "__rseq_handle_notify_resume.cold.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580852864,
      "name": "__rseq_handle_notify_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1148
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
void __rseq_handle_notify_resume(struct ksignal * ksig, struct pt_regs * regs)
```

```json
{
  "name": "__rseq_handle_notify_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__rseq_handle_notify_resume",
      "external": true,
      "loc": "kernel/rseq.c:263",
      "file": "kernel/rseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:exit_to_usermode_loop",
        "arch/x86/kernel/signal.c:do_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580922473,
      "name": "__rseq_handle_notify_resume.cold.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580921328,
      "name": "__rseq_handle_notify_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1145
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
void __rseq_handle_notify_resume(struct ksignal * ksig, struct pt_regs * regs)
```

```json
{
  "name": "__rseq_handle_notify_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__rseq_handle_notify_resume",
      "external": true,
      "loc": "kernel/rseq.c:262",
      "file": "kernel/rseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:exit_to_usermode_loop",
        "arch/x86/kernel/signal.c:do_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581018435,
      "name": "__rseq_handle_notify_resume.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071581017312,
      "name": "__rseq_handle_notify_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1123
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
void __rseq_handle_notify_resume(struct ksignal * ksig, struct pt_regs * regs)
```

```json
{
  "name": "__rseq_handle_notify_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__rseq_handle_notify_resume",
      "external": true,
      "loc": "kernel/rseq.c:262",
      "file": "kernel/rseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:exit_to_usermode_loop",
        "arch/x86/kernel/signal.c:do_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581073699,
      "name": "__rseq_handle_notify_resume.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071581072576,
      "name": "__rseq_handle_notify_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1123
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
void __rseq_handle_notify_resume(struct ksignal * ksig, struct pt_regs * regs)
```

```json
{
  "name": "__rseq_handle_notify_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581254848,
      "name": "__rseq_handle_notify_resume",
      "external": true,
      "loc": "kernel/rseq.c:262",
      "file": "kernel/rseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:exit_to_usermode_loop",
        "arch/x86/kernel/signal.c:setup_rt_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581254848,
      "name": "__rseq_handle_notify_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void __rseq_handle_notify_resume(struct ksignal * ksig, struct pt_regs * regs)
```

```json
{
  "name": "__rseq_handle_notify_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581296928,
      "name": "__rseq_handle_notify_resume",
      "external": true,
      "loc": "kernel/rseq.c:262",
      "file": "kernel/rseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:setup_rt_frame",
        "kernel/entry/common.c:exit_to_user_mode_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581296928,
      "name": "__rseq_handle_notify_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void __rseq_handle_notify_resume(struct ksignal * ksig, struct pt_regs * regs)
```

```json
{
  "name": "__rseq_handle_notify_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581314464,
      "name": "__rseq_handle_notify_resume",
      "external": true,
      "loc": "kernel/rseq.c:278",
      "file": "kernel/rseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:handle_signal",
        "kernel/entry/common.c:exit_to_user_mode_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581314464,
      "name": "__rseq_handle_notify_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void __rseq_handle_notify_resume(struct ksignal * ksig, struct pt_regs * regs)
```

```json
{
  "name": "__rseq_handle_notify_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581559696,
      "name": "__rseq_handle_notify_resume",
      "external": true,
      "loc": "kernel/rseq.c:278",
      "file": "kernel/rseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:handle_signal",
        "kernel/entry/common.c:exit_to_user_mode_loop",
        "kernel/entry/kvm.c:xfer_to_guest_mode_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581559696,
      "name": "__rseq_handle_notify_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void __rseq_handle_notify_resume(struct ksignal * ksig, struct pt_regs * regs)
```

```json
{
  "name": "__rseq_handle_notify_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581912256,
      "name": "__rseq_handle_notify_resume",
      "external": true,
      "loc": "kernel/rseq.c:278",
      "file": "kernel/rseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:handle_signal",
        "kernel/entry/common.c:exit_to_user_mode_loop",
        "kernel/entry/kvm.c:xfer_to_guest_mode_handle_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581912256,
      "name": "__rseq_handle_notify_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void __rseq_handle_notify_resume(struct ksignal * ksig, struct pt_regs * regs)
```

```json
{
  "name": "__rseq_handle_notify_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582347136,
      "name": "__rseq_handle_notify_resume",
      "external": true,
      "loc": "kernel/rseq.c:286",
      "file": "kernel/rseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:handle_signal",
        "kernel/entry/common.c:exit_to_user_mode_loop",
        "kernel/entry/kvm.c:xfer_to_guest_mode_handle_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582347136,
      "name": "__rseq_handle_notify_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void __rseq_handle_notify_resume(struct ksignal * ksig, struct pt_regs * regs)
```

```json
{
  "name": "__rseq_handle_notify_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582550144,
      "name": "__rseq_handle_notify_resume",
      "external": true,
      "loc": "kernel/rseq.c:315",
      "file": "kernel/rseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:handle_signal",
        "kernel/entry/common.c:exit_to_user_mode_loop",
        "kernel/entry/kvm.c:xfer_to_guest_mode_handle_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582550144,
      "name": "__rseq_handle_notify_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void __rseq_handle_notify_resume(struct ksignal * ksig, struct pt_regs * regs)
```

```json
{
  "name": "__rseq_handle_notify_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582720736,
      "name": "__rseq_handle_notify_resume",
      "external": true,
      "loc": "kernel/rseq.c:315",
      "file": "kernel/rseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:handle_signal",
        "kernel/entry/common.c:irqentry_exit_to_user_mode",
        "kernel/entry/common.c:syscall_exit_to_user_mode",
        "kernel/entry/common.c:syscall_exit_to_user_mode_work",
        "kernel/entry/kvm.c:xfer_to_guest_mode_handle_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582720736,
      "name": "__rseq_handle_notify_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void __rseq_handle_notify_resume(struct ksignal * ksig, struct pt_regs * regs)
```

```json
{
  "name": "__rseq_handle_notify_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492435176,
      "name": "__rseq_handle_notify_resume",
      "external": true,
      "loc": "kernel/rseq.c:262",
      "file": "kernel/rseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/signal.c:do_notify_resume",
        "arch/arm64/kernel/signal.c:do_notify_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492435176,
      "name": "__rseq_handle_notify_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3064
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
void __rseq_handle_notify_resume(struct ksignal * ksig, struct pt_regs * regs)
```

```json
{
  "name": "__rseq_handle_notify_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226311124,
      "name": "__rseq_handle_notify_resume",
      "external": true,
      "loc": "kernel/rseq.c:262",
      "file": "kernel/rseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/signal.c:do_work_pending",
        "arch/arm/kernel/signal.c:do_work_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226311124,
      "name": "__rseq_handle_notify_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
void __rseq_handle_notify_resume(struct ksignal * ksig, struct pt_regs * regs)
```

```json
{
  "name": "__rseq_handle_notify_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285704560,
      "name": "__rseq_handle_notify_resume",
      "external": true,
      "loc": "kernel/rseq.c:262",
      "file": "kernel/rseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/signal.c:do_notify_resume",
        "arch/powerpc/kernel/signal.c:do_notify_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285704560,
      "name": "__rseq_handle_notify_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1936
    }
  ]
}
```
</details>
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
void __rseq_handle_notify_resume(struct ksignal * ksig, struct pt_regs * regs)
```

```json
{
  "name": "__rseq_handle_notify_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__rseq_handle_notify_resume",
      "external": true,
      "loc": "kernel/rseq.c:262",
      "file": "kernel/rseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:exit_to_usermode_loop",
        "arch/x86/kernel/signal.c:do_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581042547,
      "name": "__rseq_handle_notify_resume.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071581041424,
      "name": "__rseq_handle_notify_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1123
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
void __rseq_handle_notify_resume(struct ksignal * ksig, struct pt_regs * regs)
```

```json
{
  "name": "__rseq_handle_notify_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__rseq_handle_notify_resume",
      "external": true,
      "loc": "kernel/rseq.c:262",
      "file": "kernel/rseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:exit_to_usermode_loop",
        "arch/x86/kernel/signal.c:do_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580989827,
      "name": "__rseq_handle_notify_resume.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071580988704,
      "name": "__rseq_handle_notify_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1123
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
void __rseq_handle_notify_resume(struct ksignal * ksig, struct pt_regs * regs)
```

```json
{
  "name": "__rseq_handle_notify_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__rseq_handle_notify_resume",
      "external": true,
      "loc": "kernel/rseq.c:262",
      "file": "kernel/rseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:exit_to_usermode_loop",
        "arch/x86/kernel/signal.c:do_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581033747,
      "name": "__rseq_handle_notify_resume.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071581032624,
      "name": "__rseq_handle_notify_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1123
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
void __rseq_handle_notify_resume(struct ksignal * ksig, struct pt_regs * regs)
```

```json
{
  "name": "__rseq_handle_notify_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581095088,
      "name": "__rseq_handle_notify_resume",
      "external": true,
      "loc": "kernel/rseq.c:262",
      "file": "kernel/rseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:exit_to_usermode_loop",
        "arch/x86/kernel/signal.c:do_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581095088,
      "name": "__rseq_handle_notify_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void __rseq_handle_notify_resume(struct ksignal * ksig, struct pt_regs * regs)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __rseq_handle_notify_resume(struct ksignal * ksig, struct pt_regs * regs)
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
