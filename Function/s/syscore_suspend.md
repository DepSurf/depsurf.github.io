# Function: <code>syscore_suspend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int syscore_suspend()
```

```json
{
  "name": "syscore_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584400400,
      "name": "syscore_suspend",
      "external": true,
      "loc": "drivers/base/syscore.c:48",
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
      "addr": 18446744071584400400,
      "name": "syscore_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
int syscore_suspend()
```

```json
{
  "name": "syscore_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584735728,
      "name": "syscore_suspend",
      "external": true,
      "loc": "drivers/base/syscore.c:48",
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
      "addr": 18446744071584735728,
      "name": "syscore_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 548
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
int syscore_suspend()
```

```json
{
  "name": "syscore_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584925600,
      "name": "syscore_suspend",
      "external": true,
      "loc": "drivers/base/syscore.c:48",
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
      "addr": 18446744071584925600,
      "name": "syscore_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 548
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
int syscore_suspend()
```

```json
{
  "name": "syscore_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585010480,
      "name": "syscore_suspend",
      "external": true,
      "loc": "drivers/base/syscore.c:48",
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
      "addr": 18446744071585010480,
      "name": "syscore_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 501
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
int syscore_suspend()
```

```json
{
  "name": "syscore_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585432672,
      "name": "syscore_suspend",
      "external": true,
      "loc": "drivers/base/syscore.c:48",
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
      "addr": 18446744071585432672,
      "name": "syscore_suspend",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int syscore_suspend()
```

```json
{
  "name": "syscore_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_suspend",
      "external": true,
      "loc": "drivers/base/syscore.c:47",
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
      "addr": 18446744071585676365,
      "name": "syscore_suspend.cold.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071585675792,
      "name": "syscore_suspend",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int syscore_suspend()
```

```json
{
  "name": "syscore_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_suspend",
      "external": true,
      "loc": "drivers/base/syscore.c:47",
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
      "addr": 18446744071585806621,
      "name": "syscore_suspend.cold.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071585806048,
      "name": "syscore_suspend",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int syscore_suspend()
```

```json
{
  "name": "syscore_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_suspend",
      "external": true,
      "loc": "drivers/base/syscore.c:47",
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
      "addr": 18446744071586039826,
      "name": "syscore_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071586039280,
      "name": "syscore_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 417
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
int syscore_suspend()
```

```json
{
  "name": "syscore_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_suspend",
      "external": true,
      "loc": "drivers/base/syscore.c:47",
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
      "addr": 18446744071586187426,
      "name": "syscore_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071586186880,
      "name": "syscore_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 417
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
int syscore_suspend()
```

```json
{
  "name": "syscore_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_suspend",
      "external": true,
      "loc": "drivers/base/syscore.c:47",
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
      "addr": 18446744071586949072,
      "name": "syscore_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071586948192,
      "name": "syscore_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 417
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
int syscore_suspend()
```

```json
{
  "name": "syscore_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_suspend",
      "external": true,
      "loc": "drivers/base/syscore.c:47",
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
      "addr": 18446744071591486532,
      "name": "syscore_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071587033456,
      "name": "syscore_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
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
int syscore_suspend()
```

```json
{
  "name": "syscore_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_suspend",
      "external": true,
      "loc": "drivers/base/syscore.c:47",
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
      "addr": 18446744071591430212,
      "name": "syscore_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071586917248,
      "name": "syscore_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
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
int syscore_suspend()
```

```json
{
  "name": "syscore_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_suspend",
      "external": true,
      "loc": "drivers/base/syscore.c:47",
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
      "addr": 18446744071592489243,
      "name": "syscore_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071587479584,
      "name": "syscore_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
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
int syscore_suspend()
```

```json
{
  "name": "syscore_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_suspend",
      "external": true,
      "loc": "drivers/base/syscore.c:47",
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
      "addr": 18446744071594358850,
      "name": "syscore_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    },
    {
      "addr": 18446744071588800896,
      "name": "syscore_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 533
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
int syscore_suspend()
```

```json
{
  "name": "syscore_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_suspend",
      "external": true,
      "loc": "drivers/base/syscore.c:47",
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
      "addr": 18446744071596246644,
      "name": "syscore_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071590297472,
      "name": "syscore_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 689
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
int syscore_suspend()
```

```json
{
  "name": "syscore_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_suspend",
      "external": true,
      "loc": "drivers/base/syscore.c:47",
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
      "addr": 18446744071596775053,
      "name": "syscore_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071590617504,
      "name": "syscore_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 649
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
int syscore_suspend()
```

```json
{
  "name": "syscore_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_suspend",
      "external": true,
      "loc": "drivers/base/syscore.c:47",
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
      "addr": 18446744071597684304,
      "name": "syscore_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071590976608,
      "name": "syscore_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 649
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
int syscore_suspend()
```

```json
{
  "name": "syscore_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498985432,
      "name": "syscore_suspend",
      "external": true,
      "loc": "drivers/base/syscore.c:47",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498985432,
      "name": "syscore_suspend",
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int syscore_suspend()
```

```json
{
  "name": "syscore_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231554064,
      "name": "syscore_suspend",
      "external": true,
      "loc": "drivers/base/syscore.c:47",
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
      "addr": 3231554064,
      "name": "syscore_suspend",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int syscore_suspend()
```

```json
{
  "name": "syscore_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292137824,
      "name": "syscore_suspend",
      "external": true,
      "loc": "drivers/base/syscore.c:47",
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
      "addr": 13835058055292137824,
      "name": "syscore_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 824
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
int syscore_suspend()
```

```json
{
  "name": "syscore_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_suspend",
      "external": true,
      "loc": "drivers/base/syscore.c:47",
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
      "addr": 18446744071585947794,
      "name": "syscore_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071585947248,
      "name": "syscore_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 417
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
int syscore_suspend()
```

```json
{
  "name": "syscore_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_suspend",
      "external": true,
      "loc": "drivers/base/syscore.c:47",
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
      "addr": 18446744071585796850,
      "name": "syscore_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071585796320,
      "name": "syscore_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 407
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
int syscore_suspend()
```

```json
{
  "name": "syscore_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_suspend",
      "external": true,
      "loc": "drivers/base/syscore.c:47",
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
      "addr": 18446744071586137442,
      "name": "syscore_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071586136896,
      "name": "syscore_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 417
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
int syscore_suspend()
```

```json
{
  "name": "syscore_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_suspend",
      "external": true,
      "loc": "drivers/base/syscore.c:47",
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
      "addr": 18446744071586246130,
      "name": "syscore_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071586245536,
      "name": "syscore_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 465
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
int syscore_suspend()
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
