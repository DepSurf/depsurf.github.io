# Function: <code>unhandled_signal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int unhandled_signal(struct task_struct * tsk, int sig)
```

```json
{
  "name": "unhandled_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579426096,
      "name": "unhandled_signal",
      "external": true,
      "loc": "kernel/signal.c:495",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579426096,
      "name": "unhandled_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int unhandled_signal(struct task_struct * tsk, int sig)
```

```json
{
  "name": "unhandled_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579438512,
      "name": "unhandled_signal",
      "external": true,
      "loc": "kernel/signal.c:495",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579438512,
      "name": "unhandled_signal",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int unhandled_signal(struct task_struct * tsk, int sig)
```

```json
{
  "name": "unhandled_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579458864,
      "name": "unhandled_signal",
      "external": true,
      "loc": "kernel/signal.c:497",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579458864,
      "name": "unhandled_signal",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int unhandled_signal(struct task_struct * tsk, int sig)
```

```json
{
  "name": "unhandled_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579446496,
      "name": "unhandled_signal",
      "external": true,
      "loc": "kernel/signal.c:503",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579446496,
      "name": "unhandled_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int unhandled_signal(struct task_struct * tsk, int sig)
```

```json
{
  "name": "unhandled_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579474880,
      "name": "unhandled_signal",
      "external": true,
      "loc": "kernel/signal.c:505",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/umip.c:force_sig_info_umip_fault",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579474880,
      "name": "unhandled_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int unhandled_signal(struct task_struct * tsk, int sig)
```

```json
{
  "name": "unhandled_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579491216,
      "name": "unhandled_signal",
      "external": true,
      "loc": "kernel/signal.c:507",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/umip.c:force_sig_info_umip_fault",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579491216,
      "name": "unhandled_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
bool unhandled_signal(struct task_struct * tsk, int sig)
```

```json
{
  "name": "unhandled_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579524768,
      "name": "unhandled_signal",
      "external": true,
      "loc": "kernel/signal.c:539",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579524768,
      "name": "unhandled_signal",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool unhandled_signal(struct task_struct * tsk, int sig)
```

```json
{
  "name": "unhandled_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579544432,
      "name": "unhandled_signal",
      "external": true,
      "loc": "kernel/signal.c:549",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579544432,
      "name": "unhandled_signal",
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
bool unhandled_signal(struct task_struct * tsk, int sig)
```

```json
{
  "name": "unhandled_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579570544,
      "name": "unhandled_signal",
      "external": true,
      "loc": "kernel/signal.c:554",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579570544,
      "name": "unhandled_signal",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool unhandled_signal(struct task_struct * tsk, int sig)
```

```json
{
  "name": "unhandled_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579609104,
      "name": "unhandled_signal",
      "external": true,
      "loc": "kernel/signal.c:554",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579609104,
      "name": "unhandled_signal",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool unhandled_signal(struct task_struct * tsk, int sig)
```

```json
{
  "name": "unhandled_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579589328,
      "name": "unhandled_signal",
      "external": true,
      "loc": "kernel/signal.c:555",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579589328,
      "name": "unhandled_signal",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
bool unhandled_signal(struct task_struct * tsk, int sig)
```

```json
{
  "name": "unhandled_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579596496,
      "name": "unhandled_signal",
      "external": true,
      "loc": "kernel/signal.c:554",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579596496,
      "name": "unhandled_signal",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
bool unhandled_signal(struct task_struct * tsk, int sig)
```

```json
{
  "name": "unhandled_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579671328,
      "name": "unhandled_signal",
      "external": true,
      "loc": "kernel/signal.c:555",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579671328,
      "name": "unhandled_signal",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool unhandled_signal(struct task_struct * tsk, int sig)
```

```json
{
  "name": "unhandled_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579768192,
      "name": "unhandled_signal",
      "external": true,
      "loc": "kernel/signal.c:555",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:gp_user_force_sig_segv",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579768192,
      "name": "unhandled_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool unhandled_signal(struct task_struct * tsk, int sig)
```

```json
{
  "name": "unhandled_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579899968,
      "name": "unhandled_signal",
      "external": true,
      "loc": "kernel/signal.c:555",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579899968,
      "name": "unhandled_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool unhandled_signal(struct task_struct * tsk, int sig)
```

```json
{
  "name": "unhandled_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579949552,
      "name": "unhandled_signal",
      "external": true,
      "loc": "kernel/signal.c:556",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579949552,
      "name": "unhandled_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
bool unhandled_signal(struct task_struct * tsk, int sig)
```

```json
{
  "name": "unhandled_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579988784,
      "name": "unhandled_signal",
      "external": true,
      "loc": "kernel/signal.c:547",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/cet.c:do_user_cp_fault",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579988784,
      "name": "unhandled_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
bool unhandled_signal(struct task_struct * tsk, int sig)
```

```json
{
  "name": "unhandled_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490732872,
      "name": "unhandled_signal",
      "external": true,
      "loc": "kernel/signal.c:554",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/traps.c:arm64_show_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490732872,
      "name": "unhandled_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
bool unhandled_signal(struct task_struct * tsk, int sig)
```

```json
{
  "name": "unhandled_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224784840,
      "name": "unhandled_signal",
      "external": true,
      "loc": "kernel/signal.c:554",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3224784840,
      "name": "unhandled_signal",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
bool unhandled_signal(struct task_struct * tsk, int sig)
```

```json
{
  "name": "unhandled_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283555472,
      "name": "unhandled_signal",
      "external": true,
      "loc": "kernel/signal.c:554",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/traps.c:show_signal_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283555472,
      "name": "unhandled_signal",
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
bool unhandled_signal(struct task_struct * tsk, int sig)
```

```json
{
  "name": "unhandled_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271442692,
      "name": "unhandled_signal",
      "external": true,
      "loc": "kernel/signal.c:554",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/kernel/traps.c:do_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271442692,
      "name": "unhandled_signal",
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
bool unhandled_signal(struct task_struct * tsk, int sig)
```

```json
{
  "name": "unhandled_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579546848,
      "name": "unhandled_signal",
      "external": true,
      "loc": "kernel/signal.c:554",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579546848,
      "name": "unhandled_signal",
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
bool unhandled_signal(struct task_struct * tsk, int sig)
```

```json
{
  "name": "unhandled_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579475584,
      "name": "unhandled_signal",
      "external": true,
      "loc": "kernel/signal.c:554",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579475584,
      "name": "unhandled_signal",
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
bool unhandled_signal(struct task_struct * tsk, int sig)
```

```json
{
  "name": "unhandled_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579544128,
      "name": "unhandled_signal",
      "external": true,
      "loc": "kernel/signal.c:554",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579544128,
      "name": "unhandled_signal",
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
bool unhandled_signal(struct task_struct * tsk, int sig)
```

```json
{
  "name": "unhandled_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579577120,
      "name": "unhandled_signal",
      "external": true,
      "loc": "kernel/signal.c:554",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579577120,
      "name": "unhandled_signal",
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
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
