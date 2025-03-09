# Function: <code>thaw_processes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void thaw_processes()
```

```json
{
  "name": "thaw_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579687904,
      "name": "thaw_processes",
      "external": true,
      "loc": "kernel/power/process.c:183",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_processes",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_release",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579687904,
      "name": "thaw_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
void thaw_processes()
```

```json
{
  "name": "thaw_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579707168,
      "name": "thaw_processes",
      "external": true,
      "loc": "kernel/power/process.c:196",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_processes",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_release",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579707168,
      "name": "thaw_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 495
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
void thaw_processes()
```

```json
{
  "name": "thaw_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579734736,
      "name": "thaw_processes",
      "external": true,
      "loc": "kernel/power/process.c:185",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_processes",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_release",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579734736,
      "name": "thaw_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 495
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
void thaw_processes()
```

```json
{
  "name": "thaw_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579730624,
      "name": "thaw_processes",
      "external": true,
      "loc": "kernel/power/process.c:188",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_processes",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_release",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579730624,
      "name": "thaw_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 454
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
void thaw_processes()
```

```json
{
  "name": "thaw_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579763632,
      "name": "thaw_processes",
      "external": true,
      "loc": "kernel/power/process.c:189",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_processes",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_release",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579763632,
      "name": "thaw_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
void thaw_processes()
```

```json
{
  "name": "thaw_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579797840,
      "name": "thaw_processes",
      "external": true,
      "loc": "kernel/power/process.c:189",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_processes",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_release",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579797840,
      "name": "thaw_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
void thaw_processes()
```

```json
{
  "name": "thaw_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579844448,
      "name": "thaw_processes",
      "external": true,
      "loc": "kernel/power/process.c:189",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_processes",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_release",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579844448,
      "name": "thaw_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
void thaw_processes()
```

```json
{
  "name": "thaw_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "thaw_processes",
      "external": true,
      "loc": "kernel/power/process.c:189",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_processes",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_release",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579879387,
      "name": "thaw_processes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071579878240,
      "name": "thaw_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 477
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
void thaw_processes()
```

```json
{
  "name": "thaw_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579928448,
      "name": "thaw_processes",
      "external": true,
      "loc": "kernel/power/process.c:189",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_processes",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_release",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579928448,
      "name": "thaw_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 474
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
void thaw_processes()
```

```json
{
  "name": "thaw_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579972480,
      "name": "thaw_processes",
      "external": true,
      "loc": "kernel/power/process.c:189",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_processes",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:suspend_prepare",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_release",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579972480,
      "name": "thaw_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
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
void thaw_processes()
```

```json
{
  "name": "thaw_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579960272,
      "name": "thaw_processes",
      "external": true,
      "loc": "kernel/power/process.c:189",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_processes",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:suspend_prepare",
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_release",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579960272,
      "name": "thaw_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 442
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
void thaw_processes()
```

```json
{
  "name": "thaw_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579962896,
      "name": "thaw_processes",
      "external": true,
      "loc": "kernel/power/process.c:189",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_processes",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_release",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579962896,
      "name": "thaw_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 442
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
void thaw_processes()
```

```json
{
  "name": "thaw_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "thaw_processes",
      "external": true,
      "loc": "kernel/power/process.c:189",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_processes",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_release",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592122822,
      "name": "thaw_processes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580092656,
      "name": "thaw_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 451
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
void thaw_processes()
```

```json
{
  "name": "thaw_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "thaw_processes",
      "external": true,
      "loc": "kernel/power/process.c:186",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_processes",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_release",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593892069,
      "name": "thaw_processes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580229984,
      "name": "thaw_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 499
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
void thaw_processes()
```

```json
{
  "name": "thaw_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "thaw_processes",
      "external": true,
      "loc": "kernel/power/process.c:179",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_processes",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_release",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595983757,
      "name": "thaw_processes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580422576,
      "name": "thaw_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 513
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
void thaw_processes()
```

```json
{
  "name": "thaw_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "thaw_processes",
      "external": true,
      "loc": "kernel/power/process.c:179",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_processes",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_release",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596502173,
      "name": "thaw_processes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580491952,
      "name": "thaw_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 513
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
void thaw_processes()
```

```json
{
  "name": "thaw_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "thaw_processes",
      "external": true,
      "loc": "kernel/power/process.c:179",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_processes",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_release",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597399859,
      "name": "thaw_processes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580551840,
      "name": "thaw_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 513
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
void thaw_processes()
```

```json
{
  "name": "thaw_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491138352,
      "name": "thaw_processes",
      "external": true,
      "loc": "kernel/power/process.c:189",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491138352,
      "name": "thaw_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 716
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
void thaw_processes()
```

```json
{
  "name": "thaw_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225135556,
      "name": "thaw_processes",
      "external": true,
      "loc": "kernel/power/process.c:189",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_processes",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225135556,
      "name": "thaw_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 696
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
void thaw_processes()
```

```json
{
  "name": "thaw_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284031104,
      "name": "thaw_processes",
      "external": true,
      "loc": "kernel/power/process.c:189",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284031104,
      "name": "thaw_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 740
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
void thaw_processes()
```

```json
{
  "name": "thaw_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271701942,
      "name": "thaw_processes",
      "external": true,
      "loc": "kernel/power/process.c:189",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271701942,
      "name": "thaw_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
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
void thaw_processes()
```

```json
{
  "name": "thaw_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579900096,
      "name": "thaw_processes",
      "external": true,
      "loc": "kernel/power/process.c:189",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_processes",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_release",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579900096,
      "name": "thaw_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 474
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
void thaw_processes()
```

```json
{
  "name": "thaw_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579835520,
      "name": "thaw_processes",
      "external": true,
      "loc": "kernel/power/process.c:189",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_processes",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_release",
        "kernel/kexec_core.c:kernel_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579835520,
      "name": "thaw_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 474
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
void thaw_processes()
```

```json
{
  "name": "thaw_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579888720,
      "name": "thaw_processes",
      "external": true,
      "loc": "kernel/power/process.c:189",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_processes",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_release",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579888720,
      "name": "thaw_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 474
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
void thaw_processes()
```

```json
{
  "name": "thaw_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579934496,
      "name": "thaw_processes",
      "external": true,
      "loc": "kernel/power/process.c:189",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_processes",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_release",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579934496,
      "name": "thaw_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 523
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
