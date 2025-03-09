# Function: <code>syscore_resume</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void syscore_resume()
```

```json
{
  "name": "syscore_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584400000,
      "name": "syscore_resume",
      "external": true,
      "loc": "drivers/base/syscore.c:93",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:xen_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584400000,
      "name": "syscore_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
void syscore_resume()
```

```json
{
  "name": "syscore_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584735344,
      "name": "syscore_resume",
      "external": true,
      "loc": "drivers/base/syscore.c:93",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:xen_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584735344,
      "name": "syscore_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
void syscore_resume()
```

```json
{
  "name": "syscore_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584925216,
      "name": "syscore_resume",
      "external": true,
      "loc": "drivers/base/syscore.c:93",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:xen_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584925216,
      "name": "syscore_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
void syscore_resume()
```

```json
{
  "name": "syscore_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585010112,
      "name": "syscore_resume",
      "external": true,
      "loc": "drivers/base/syscore.c:93",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:xen_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585010112,
      "name": "syscore_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
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
void syscore_resume()
```

```json
{
  "name": "syscore_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585432288,
      "name": "syscore_resume",
      "external": true,
      "loc": "drivers/base/syscore.c:93",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:xen_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585432288,
      "name": "syscore_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
void syscore_resume()
```

```json
{
  "name": "syscore_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_resume",
      "external": true,
      "loc": "drivers/base/syscore.c:92",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:xen_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585676344,
      "name": "syscore_resume.cold.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585675440,
      "name": "syscore_resume",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void syscore_resume()
```

```json
{
  "name": "syscore_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_resume",
      "external": true,
      "loc": "drivers/base/syscore.c:92",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:xen_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585806600,
      "name": "syscore_resume.cold.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585805696,
      "name": "syscore_resume",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void syscore_resume()
```

```json
{
  "name": "syscore_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_resume",
      "external": true,
      "loc": "drivers/base/syscore.c:92",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:xen_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586039805,
      "name": "syscore_resume.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586038928,
      "name": "syscore_resume",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void syscore_resume()
```

```json
{
  "name": "syscore_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_resume",
      "external": true,
      "loc": "drivers/base/syscore.c:92",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:xen_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586187405,
      "name": "syscore_resume.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586186528,
      "name": "syscore_resume",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void syscore_resume()
```

```json
{
  "name": "syscore_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_resume",
      "external": true,
      "loc": "drivers/base/syscore.c:92",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:resume_target_kernel",
        "kernel/power/hibernate.c:create_image",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:xen_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586949145,
      "name": "syscore_resume.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586948624,
      "name": "syscore_resume",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void syscore_resume()
```

```json
{
  "name": "syscore_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587033840,
      "name": "syscore_resume",
      "external": true,
      "loc": "drivers/base/syscore.c:91",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:resume_target_kernel",
        "kernel/power/hibernate.c:create_image",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:xen_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587033840,
      "name": "syscore_resume",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void syscore_resume()
```

```json
{
  "name": "syscore_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586917632,
      "name": "syscore_resume",
      "external": true,
      "loc": "drivers/base/syscore.c:91",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernation_restore",
        "kernel/power/hibernate.c:create_image",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:xen_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586917632,
      "name": "syscore_resume",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void syscore_resume()
```

```json
{
  "name": "syscore_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_resume",
      "external": true,
      "loc": "drivers/base/syscore.c:91",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernation_restore",
        "kernel/power/hibernate.c:create_image",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:xen_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592489336,
      "name": "syscore_resume.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071587480000,
      "name": "syscore_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
void syscore_resume()
```

```json
{
  "name": "syscore_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_resume",
      "external": true,
      "loc": "drivers/base/syscore.c:91",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:resume_target_kernel",
        "kernel/power/hibernate.c:create_image",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:xen_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594358760,
      "name": "syscore_resume.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071588800448,
      "name": "syscore_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 439
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
void syscore_resume()
```

```json
{
  "name": "syscore_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_resume",
      "external": true,
      "loc": "drivers/base/syscore.c:91",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:resume_target_kernel",
        "kernel/power/hibernate.c:create_image",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:xen_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596246578,
      "name": "syscore_resume.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071590296976,
      "name": "syscore_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 465
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
void syscore_resume()
```

```json
{
  "name": "syscore_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_resume",
      "external": true,
      "loc": "drivers/base/syscore.c:91",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:resume_target_kernel",
        "kernel/power/hibernate.c:create_image",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:xen_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596775012,
      "name": "syscore_resume.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071590617040,
      "name": "syscore_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 446
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
void syscore_resume()
```

```json
{
  "name": "syscore_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_resume",
      "external": true,
      "loc": "drivers/base/syscore.c:91",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:resume_target_kernel",
        "kernel/power/hibernate.c:create_image",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:xen_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597684263,
      "name": "syscore_resume.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071590976144,
      "name": "syscore_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 446
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
void syscore_resume()
```

```json
{
  "name": "syscore_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498984928,
      "name": "syscore_resume",
      "external": true,
      "loc": "drivers/base/syscore.c:92",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498984928,
      "name": "syscore_resume",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void syscore_resume()
```

```json
{
  "name": "syscore_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231553496,
      "name": "syscore_resume",
      "external": true,
      "loc": "drivers/base/syscore.c:92",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernation_snapshot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231553496,
      "name": "syscore_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 568
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
void syscore_resume()
```

```json
{
  "name": "syscore_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292137168,
      "name": "syscore_resume",
      "external": true,
      "loc": "drivers/base/syscore.c:92",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292137168,
      "name": "syscore_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 644
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
void syscore_resume()
```

```json
{
  "name": "syscore_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_resume",
      "external": true,
      "loc": "drivers/base/syscore.c:92",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:xen_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585947773,
      "name": "syscore_resume.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585946896,
      "name": "syscore_resume",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void syscore_resume()
```

```json
{
  "name": "syscore_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_resume",
      "external": true,
      "loc": "drivers/base/syscore.c:92",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/kexec_core.c:kernel_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585796829,
      "name": "syscore_resume.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585795984,
      "name": "syscore_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
void syscore_resume()
```

```json
{
  "name": "syscore_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_resume",
      "external": true,
      "loc": "drivers/base/syscore.c:92",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:xen_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586137421,
      "name": "syscore_resume.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586136544,
      "name": "syscore_resume",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void syscore_resume()
```

```json
{
  "name": "syscore_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_resume",
      "external": true,
      "loc": "drivers/base/syscore.c:92",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:xen_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586246109,
      "name": "syscore_resume.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586245136,
      "name": "syscore_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void syscore_resume()
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
