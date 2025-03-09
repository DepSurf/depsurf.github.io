# Function: <code>freeze_processes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int freeze_processes()
```

```json
{
  "name": "freeze_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579688416,
      "name": "freeze_processes",
      "external": true,
      "loc": "kernel/power/process.c:118",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/hibernate.c:hibernate",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579688416,
      "name": "freeze_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int freeze_processes()
```

```json
{
  "name": "freeze_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579707664,
      "name": "freeze_processes",
      "external": true,
      "loc": "kernel/power/process.c:119",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579707664,
      "name": "freeze_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int freeze_processes()
```

```json
{
  "name": "freeze_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579735232,
      "name": "freeze_processes",
      "external": true,
      "loc": "kernel/power/process.c:119",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579735232,
      "name": "freeze_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
int freeze_processes()
```

```json
{
  "name": "freeze_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579731088,
      "name": "freeze_processes",
      "external": true,
      "loc": "kernel/power/process.c:122",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579731088,
      "name": "freeze_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
int freeze_processes()
```

```json
{
  "name": "freeze_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579764096,
      "name": "freeze_processes",
      "external": true,
      "loc": "kernel/power/process.c:123",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579764096,
      "name": "freeze_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
int freeze_processes()
```

```json
{
  "name": "freeze_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "freeze_processes",
      "external": true,
      "loc": "kernel/power/process.c:123",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579798690,
      "name": "freeze_processes.cold.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071579798304,
      "name": "freeze_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int freeze_processes()
```

```json
{
  "name": "freeze_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "freeze_processes",
      "external": true,
      "loc": "kernel/power/process.c:123",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579845277,
      "name": "freeze_processes.cold.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071579844912,
      "name": "freeze_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int freeze_processes()
```

```json
{
  "name": "freeze_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "freeze_processes",
      "external": true,
      "loc": "kernel/power/process.c:123",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579879430,
      "name": "freeze_processes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071579878720,
      "name": "freeze_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int freeze_processes()
```

```json
{
  "name": "freeze_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "freeze_processes",
      "external": true,
      "loc": "kernel/power/process.c:123",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579929595,
      "name": "freeze_processes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071579928928,
      "name": "freeze_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int freeze_processes()
```

```json
{
  "name": "freeze_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "freeze_processes",
      "external": true,
      "loc": "kernel/power/process.c:123",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_prepare",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579973621,
      "name": "freeze_processes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071579972960,
      "name": "freeze_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
int freeze_processes()
```

```json
{
  "name": "freeze_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "freeze_processes",
      "external": true,
      "loc": "kernel/power/process.c:123",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_prepare",
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591291688,
      "name": "freeze_processes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071579960720,
      "name": "freeze_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
int freeze_processes()
```

```json
{
  "name": "freeze_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "freeze_processes",
      "external": true,
      "loc": "kernel/power/process.c:123",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591234721,
      "name": "freeze_processes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071579963344,
      "name": "freeze_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
int freeze_processes()
```

```json
{
  "name": "freeze_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "freeze_processes",
      "external": true,
      "loc": "kernel/power/process.c:123",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592122842,
      "name": "freeze_processes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071580093120,
      "name": "freeze_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int freeze_processes()
```

```json
{
  "name": "freeze_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "freeze_processes",
      "external": true,
      "loc": "kernel/power/process.c:120",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593892089,
      "name": "freeze_processes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071580230496,
      "name": "freeze_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int freeze_processes()
```

```json
{
  "name": "freeze_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "freeze_processes",
      "external": true,
      "loc": "kernel/power/process.c:121",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595983777,
      "name": "freeze_processes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580423120,
      "name": "freeze_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int freeze_processes()
```

```json
{
  "name": "freeze_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "freeze_processes",
      "external": true,
      "loc": "kernel/power/process.c:121",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596502193,
      "name": "freeze_processes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580492496,
      "name": "freeze_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int freeze_processes()
```

```json
{
  "name": "freeze_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "freeze_processes",
      "external": true,
      "loc": "kernel/power/process.c:121",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597399879,
      "name": "freeze_processes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580552384,
      "name": "freeze_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int freeze_processes()
```

```json
{
  "name": "freeze_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491139072,
      "name": "freeze_processes",
      "external": true,
      "loc": "kernel/power/process.c:123",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491139072,
      "name": "freeze_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int freeze_processes()
```

```json
{
  "name": "freeze_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225136252,
      "name": "freeze_processes",
      "external": true,
      "loc": "kernel/power/process.c:123",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225136252,
      "name": "freeze_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
int freeze_processes()
```

```json
{
  "name": "freeze_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284031856,
      "name": "freeze_processes",
      "external": true,
      "loc": "kernel/power/process.c:123",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284031856,
      "name": "freeze_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
int freeze_processes()
```

```json
{
  "name": "freeze_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271702440,
      "name": "freeze_processes",
      "external": true,
      "loc": "kernel/power/process.c:123",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271702440,
      "name": "freeze_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int freeze_processes()
```

```json
{
  "name": "freeze_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "freeze_processes",
      "external": true,
      "loc": "kernel/power/process.c:123",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579901243,
      "name": "freeze_processes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071579900576,
      "name": "freeze_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int freeze_processes()
```

```json
{
  "name": "freeze_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "freeze_processes",
      "external": true,
      "loc": "kernel/power/process.c:123",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/kexec_core.c:kernel_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579836667,
      "name": "freeze_processes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071579836000,
      "name": "freeze_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int freeze_processes()
```

```json
{
  "name": "freeze_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "freeze_processes",
      "external": true,
      "loc": "kernel/power/process.c:123",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579889867,
      "name": "freeze_processes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071579889200,
      "name": "freeze_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int freeze_processes()
```

```json
{
  "name": "freeze_processes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "freeze_processes",
      "external": true,
      "loc": "kernel/power/process.c:123",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579935696,
      "name": "freeze_processes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071579935024,
      "name": "freeze_processes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
