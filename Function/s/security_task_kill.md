# Function: <code>security_task_kill</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int security_task_kill(struct task_struct * p, struct siginfo * info, int sig, u32 secid)
```

```json
{
  "name": "security_task_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582246880,
      "name": "security_task_kill",
      "external": true,
      "loc": "security/security.c:987",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kill_pid_info_as_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582246880,
      "name": "security_task_kill",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int security_task_kill(struct task_struct * p, struct siginfo * info, int sig, u32 secid)
```

```json
{
  "name": "security_task_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582465520,
      "name": "security_task_kill",
      "external": true,
      "loc": "security/security.c:1011",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kill_pid_info_as_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582465520,
      "name": "security_task_kill",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int security_task_kill(struct task_struct * p, struct siginfo * info, int sig, u32 secid)
```

```json
{
  "name": "security_task_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582557984,
      "name": "security_task_kill",
      "external": true,
      "loc": "security/security.c:1032",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kill_pid_info_as_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582557984,
      "name": "security_task_kill",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int security_task_kill(struct task_struct * p, struct siginfo * info, int sig, u32 secid)
```

```json
{
  "name": "security_task_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582645360,
      "name": "security_task_kill",
      "external": true,
      "loc": "security/security.c:1675",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kill_pid_info_as_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582645360,
      "name": "security_task_kill",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int security_task_kill(struct task_struct * p, struct siginfo * info, int sig, u32 secid)
```

```json
{
  "name": "security_task_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582800048,
      "name": "security_task_kill",
      "external": true,
      "loc": "security/security.c:1637",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kill_pid_info_as_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582800048,
      "name": "security_task_kill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int security_task_kill(struct task_struct * p, struct siginfo * info, int sig, const struct cred * cred)
```

```json
{
  "name": "security_task_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582996624,
      "name": "security_task_kill",
      "external": true,
      "loc": "security/security.c:1141",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kill_pid_info_as_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582996624,
      "name": "security_task_kill",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int security_task_kill(struct task_struct * p, struct kernel_siginfo * info, int sig, const struct cred * cred)
```

```json
{
  "name": "security_task_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583108800,
      "name": "security_task_kill",
      "external": true,
      "loc": "security/security.c:1749",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kill_pid_info_as_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583108800,
      "name": "security_task_kill",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int security_task_kill(struct task_struct * p, struct kernel_siginfo * info, int sig, const struct cred * cred)
```

```json
{
  "name": "security_task_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583295232,
      "name": "security_task_kill",
      "external": true,
      "loc": "security/security.c:1768",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kill_pid_usb_asyncio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583295232,
      "name": "security_task_kill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int security_task_kill(struct task_struct * p, struct kernel_siginfo * info, int sig, const struct cred * cred)
```

```json
{
  "name": "security_task_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583400192,
      "name": "security_task_kill",
      "external": true,
      "loc": "security/security.c:1807",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kill_pid_usb_asyncio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583400192,
      "name": "security_task_kill",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int security_task_kill(struct task_struct * p, struct kernel_siginfo * info, int sig, const struct cred * cred)
```

```json
{
  "name": "security_task_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583739792,
      "name": "security_task_kill",
      "external": true,
      "loc": "security/security.c:2003",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kill_pid_usb_asyncio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583739792,
      "name": "security_task_kill",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int security_task_kill(struct task_struct * p, struct kernel_siginfo * info, int sig, const struct cred * cred)
```

```json
{
  "name": "security_task_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583860112,
      "name": "security_task_kill",
      "external": true,
      "loc": "security/security.c:2020",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kill_pid_usb_asyncio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583860112,
      "name": "security_task_kill",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int security_task_kill(struct task_struct * p, struct kernel_siginfo * info, int sig, const struct cred * cred)
```

```json
{
  "name": "security_task_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583886288,
      "name": "security_task_kill",
      "external": true,
      "loc": "security/security.c:2083",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kill_pid_usb_asyncio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583886288,
      "name": "security_task_kill",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int security_task_kill(struct task_struct * p, struct kernel_siginfo * info, int sig, const struct cred * cred)
```

```json
{
  "name": "security_task_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584250000,
      "name": "security_task_kill",
      "external": true,
      "loc": "security/security.c:2091",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kill_pid_usb_asyncio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584250000,
      "name": "security_task_kill",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int security_task_kill(struct task_struct * p, struct kernel_siginfo * info, int sig, const struct cred * cred)
```

```json
{
  "name": "security_task_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584860000,
      "name": "security_task_kill",
      "external": true,
      "loc": "security/security.c:2097",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kill_pid_usb_asyncio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584860000,
      "name": "security_task_kill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int security_task_kill(struct task_struct * p, struct kernel_siginfo * info, int sig, const struct cred * cred)
```

```json
{
  "name": "security_task_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585564656,
      "name": "security_task_kill",
      "external": true,
      "loc": "security/security.c:2149",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kill_pid_usb_asyncio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585564656,
      "name": "security_task_kill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int security_task_kill(struct task_struct * p, struct kernel_siginfo * info, int sig, const struct cred * cred)
```

```json
{
  "name": "security_task_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585795648,
      "name": "security_task_kill",
      "external": true,
      "loc": "security/security.c:3554",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kill_pid_usb_asyncio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585795648,
      "name": "security_task_kill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int security_task_kill(struct task_struct * p, struct kernel_siginfo * info, int sig, const struct cred * cred)
```

```json
{
  "name": "security_task_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586043920,
      "name": "security_task_kill",
      "external": true,
      "loc": "security/security.c:3613",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kill_pid_usb_asyncio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586043920,
      "name": "security_task_kill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int security_task_kill(struct task_struct * p, struct kernel_siginfo * info, int sig, const struct cred * cred)
```

```json
{
  "name": "security_task_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495152872,
      "name": "security_task_kill",
      "external": true,
      "loc": "security/security.c:1807",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kill_pid_usb_asyncio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495152872,
      "name": "security_task_kill",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int security_task_kill(struct task_struct * p, struct kernel_siginfo * info, int sig, const struct cred * cred)
```

```json
{
  "name": "security_task_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228540480,
      "name": "security_task_kill",
      "external": true,
      "loc": "security/security.c:1807",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kill_pid_usb_asyncio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228540480,
      "name": "security_task_kill",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int security_task_kill(struct task_struct * p, struct kernel_siginfo * info, int sig, const struct cred * cred)
```

```json
{
  "name": "security_task_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289079728,
      "name": "security_task_kill",
      "external": true,
      "loc": "security/security.c:1807",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kill_pid_usb_asyncio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289079728,
      "name": "security_task_kill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int security_task_kill(struct task_struct * p, struct kernel_siginfo * info, int sig, const struct cred * cred)
```

```json
{
  "name": "security_task_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274399720,
      "name": "security_task_kill",
      "external": true,
      "loc": "security/security.c:1807",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kill_pid_usb_asyncio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274399720,
      "name": "security_task_kill",
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
int security_task_kill(struct task_struct * p, struct kernel_siginfo * info, int sig, const struct cred * cred)
```

```json
{
  "name": "security_task_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583368928,
      "name": "security_task_kill",
      "external": true,
      "loc": "security/security.c:1807",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kill_pid_usb_asyncio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583368928,
      "name": "security_task_kill",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int security_task_kill(struct task_struct * p, struct kernel_siginfo * info, int sig, const struct cred * cred)
```

```json
{
  "name": "security_task_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583306032,
      "name": "security_task_kill",
      "external": true,
      "loc": "security/security.c:1807",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kill_pid_usb_asyncio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583306032,
      "name": "security_task_kill",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int security_task_kill(struct task_struct * p, struct kernel_siginfo * info, int sig, const struct cred * cred)
```

```json
{
  "name": "security_task_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583352704,
      "name": "security_task_kill",
      "external": true,
      "loc": "security/security.c:1807",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kill_pid_usb_asyncio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583352704,
      "name": "security_task_kill",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int security_task_kill(struct task_struct * p, struct kernel_siginfo * info, int sig, const struct cred * cred)
```

```json
{
  "name": "security_task_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583447888,
      "name": "security_task_kill",
      "external": true,
      "loc": "security/security.c:1807",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kill_pid_usb_asyncio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583447888,
      "name": "security_task_kill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cred * cred</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 secid</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
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
