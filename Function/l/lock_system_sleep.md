# Function: <code>lock_system_sleep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_system_sleep",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579685315,
      "name": "lock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:437",
      "file": "kernel/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_test_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579688998,
      "name": "lock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:437",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_set_ops",
        "kernel/power/suspend.c:freeze_set_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579693039,
      "name": "lock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:437",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:hibernate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579718902,
      "name": "lock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:437",
      "file": "kernel/power/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/user.c:snapshot_release",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_write",
        "kernel/power/user.c:snapshot_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579949804,
      "name": "lock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:437",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kernel_kexec"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_system_sleep",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579704419,
      "name": "lock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:436",
      "file": "kernel/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_test_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579708294,
      "name": "lock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:436",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_set_ops",
        "kernel/power/suspend.c:freeze_set_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579715548,
      "name": "lock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:436",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579739656,
      "name": "lock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:436",
      "file": "kernel/power/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/user.c:snapshot_write",
        "kernel/power/user.c:snapshot_read",
        "kernel/power/user.c:snapshot_release",
        "kernel/power/user.c:snapshot_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579981196,
      "name": "lock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:436",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kernel_kexec"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_system_sleep",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579731971,
      "name": "lock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:438",
      "file": "kernel/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_test_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579735830,
      "name": "lock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:438",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_set_ops",
        "kernel/power/suspend.c:freeze_set_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579743116,
      "name": "lock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:438",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579767000,
      "name": "lock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:438",
      "file": "kernel/power/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/user.c:snapshot_write",
        "kernel/power/user.c:snapshot_read",
        "kernel/power/user.c:snapshot_release",
        "kernel/power/user.c:snapshot_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580011692,
      "name": "lock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:438",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kernel_kexec"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_system_sleep",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579727875,
      "name": "lock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:441",
      "file": "kernel/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_test_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579731702,
      "name": "lock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:441",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_set_ops",
        "kernel/power/suspend.c:freeze_set_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579739261,
      "name": "lock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:441",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernation_set_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579764664,
      "name": "lock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:441",
      "file": "kernel/power/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/user.c:snapshot_write",
        "kernel/power/user.c:snapshot_read",
        "kernel/power/user.c:snapshot_release",
        "kernel/power/user.c:snapshot_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580018908,
      "name": "lock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:441",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kernel_kexec"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_system_sleep",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579760723,
      "name": "lock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:446",
      "file": "kernel/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_test_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579764710,
      "name": "lock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:446",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_set_ops",
        "kernel/power/suspend.c:s2idle_set_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579772429,
      "name": "lock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:446",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernation_set_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579798152,
      "name": "lock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:446",
      "file": "kernel/power/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/user.c:snapshot_write",
        "kernel/power/user.c:snapshot_read",
        "kernel/power/user.c:snapshot_release",
        "kernel/power/user.c:snapshot_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580065852,
      "name": "lock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:446",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kernel_kexec"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void lock_system_sleep()
```

```json
{
  "name": "lock_system_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579795043,
      "name": "lock_system_sleep",
      "external": true,
      "loc": "kernel/power/main.c:25",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_test_store"
      ],
      "caller_func": [
        "kernel/power/suspend.c:suspend_set_ops",
        "kernel/power/suspend.c:s2idle_set_ops",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernation_set_ops",
        "kernel/power/hibernate.c:hibernation_set_ops",
        "kernel/power/user.c:snapshot_write",
        "kernel/power/user.c:snapshot_read",
        "kernel/power/user.c:snapshot_release",
        "kernel/power/user.c:snapshot_open",
        "kernel/kexec_core.c:kernel_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579793232,
      "name": "lock_system_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void lock_system_sleep()
```

```json
{
  "name": "lock_system_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579841651,
      "name": "lock_system_sleep",
      "external": true,
      "loc": "kernel/power/main.c:24",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_test_store"
      ],
      "caller_func": [
        "kernel/power/suspend.c:suspend_set_ops",
        "kernel/power/suspend.c:s2idle_set_ops",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernation_set_ops",
        "kernel/power/hibernate.c:hibernation_set_ops",
        "kernel/power/user.c:snapshot_write",
        "kernel/power/user.c:snapshot_read",
        "kernel/power/user.c:snapshot_release",
        "kernel/power/user.c:snapshot_open",
        "kernel/kexec_core.c:kernel_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579839824,
      "name": "lock_system_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void lock_system_sleep()
```

```json
{
  "name": "lock_system_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579875635,
      "name": "lock_system_sleep",
      "external": true,
      "loc": "kernel/power/main.c:23",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_test_store"
      ],
      "caller_func": [
        "kernel/power/suspend.c:suspend_set_ops",
        "kernel/power/suspend.c:s2idle_set_ops",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernation_set_ops",
        "kernel/power/hibernate.c:hibernation_set_ops",
        "kernel/power/user.c:snapshot_write",
        "kernel/power/user.c:snapshot_read",
        "kernel/power/user.c:snapshot_release",
        "kernel/power/user.c:snapshot_open",
        "kernel/kexec_core.c:kernel_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579873824,
      "name": "lock_system_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void lock_system_sleep()
```

```json
{
  "name": "lock_system_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579925923,
      "name": "lock_system_sleep",
      "external": true,
      "loc": "kernel/power/main.c:24",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_test_store"
      ],
      "caller_func": [
        "kernel/power/suspend.c:suspend_set_ops",
        "kernel/power/suspend.c:s2idle_set_ops",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_write",
        "kernel/power/user.c:snapshot_read",
        "kernel/power/user.c:snapshot_release",
        "kernel/power/user.c:snapshot_open",
        "kernel/kexec_core.c:kernel_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579923280,
      "name": "lock_system_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void lock_system_sleep()
```

```json
{
  "name": "lock_system_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579971043,
      "name": "lock_system_sleep",
      "external": true,
      "loc": "kernel/power/main.c:24",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_test_store"
      ],
      "caller_func": [
        "kernel/power/suspend.c:suspend_set_ops",
        "kernel/power/suspend.c:s2idle_set_ops",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernation_set_ops",
        "kernel/power/hibernate.c:hibernation_set_ops",
        "kernel/power/user.c:snapshot_write",
        "kernel/power/user.c:snapshot_read",
        "kernel/power/user.c:snapshot_release",
        "kernel/power/user.c:snapshot_open",
        "kernel/kexec_core.c:kernel_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579967056,
      "name": "lock_system_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void lock_system_sleep()
```

```json
{
  "name": "lock_system_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579958963,
      "name": "lock_system_sleep",
      "external": true,
      "loc": "kernel/power/main.c:24",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_test_store"
      ],
      "caller_func": [
        "kernel/power/suspend.c:suspend_set_ops",
        "kernel/power/suspend.c:s2idle_set_ops",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernation_set_ops",
        "kernel/power/hibernate.c:hibernation_set_ops",
        "kernel/power/user.c:snapshot_write",
        "kernel/power/user.c:snapshot_read",
        "kernel/power/user.c:snapshot_release",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579954976,
      "name": "lock_system_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void lock_system_sleep()
```

```json
{
  "name": "lock_system_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579961587,
      "name": "lock_system_sleep",
      "external": true,
      "loc": "kernel/power/main.c:24",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_test_store"
      ],
      "caller_func": [
        "kernel/power/suspend.c:suspend_set_ops",
        "kernel/power/suspend.c:s2idle_set_ops",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernation_set_ops",
        "kernel/power/hibernate.c:hibernation_set_ops",
        "kernel/power/user.c:snapshot_write",
        "kernel/power/user.c:snapshot_read",
        "kernel/power/user.c:snapshot_release",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579957696,
      "name": "lock_system_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void lock_system_sleep()
```

```json
{
  "name": "lock_system_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580091299,
      "name": "lock_system_sleep",
      "external": true,
      "loc": "kernel/power/main.c:24",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_test_store"
      ],
      "caller_func": [
        "kernel/power/suspend.c:suspend_set_ops",
        "kernel/power/suspend.c:s2idle_set_ops",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernation_set_ops",
        "kernel/power/hibernate.c:hibernation_set_ops",
        "kernel/power/user.c:snapshot_write",
        "kernel/power/user.c:snapshot_read",
        "kernel/power/user.c:snapshot_release",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580087056,
      "name": "lock_system_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void lock_system_sleep()
```

```json
{
  "name": "lock_system_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580228540,
      "name": "lock_system_sleep",
      "external": true,
      "loc": "kernel/power/main.c:24",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_test_store"
      ],
      "caller_func": [
        "kernel/power/suspend.c:suspend_set_ops",
        "kernel/power/suspend.c:s2idle_set_ops",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernation_set_ops",
        "kernel/power/hibernate.c:hibernation_set_ops",
        "kernel/power/user.c:snapshot_write",
        "kernel/power/user.c:snapshot_read",
        "kernel/power/user.c:snapshot_release",
        "kernel/power/user.c:snapshot_open",
        "drivers/acpi/x86/s2idle.c:acpi_register_lps0_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580223840,
      "name": "lock_system_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
unsigned int lock_system_sleep()
```

```json
{
  "name": "lock_system_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580420352,
      "name": "lock_system_sleep",
      "external": true,
      "loc": "kernel/power/main.c:24",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_test_store"
      ],
      "caller_func": [
        "kernel/power/suspend.c:suspend_set_ops",
        "kernel/power/suspend.c:s2idle_set_ops",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernation_set_ops",
        "kernel/power/hibernate.c:hibernation_set_ops",
        "kernel/power/user.c:snapshot_write",
        "kernel/power/user.c:snapshot_read",
        "kernel/power/user.c:snapshot_release",
        "kernel/power/user.c:snapshot_open",
        "drivers/acpi/x86/s2idle.c:acpi_register_lps0_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580414800,
      "name": "lock_system_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
unsigned int lock_system_sleep()
```

```json
{
  "name": "lock_system_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580489504,
      "name": "lock_system_sleep",
      "external": true,
      "loc": "kernel/power/main.c:52",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_test_store"
      ],
      "caller_func": [
        "kernel/power/suspend.c:suspend_set_ops",
        "kernel/power/suspend.c:s2idle_set_ops",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernation_set_ops",
        "kernel/power/hibernate.c:hibernation_set_ops",
        "kernel/power/user.c:snapshot_write",
        "kernel/power/user.c:snapshot_read",
        "kernel/power/user.c:snapshot_release",
        "kernel/power/user.c:snapshot_open",
        "drivers/acpi/x86/s2idle.c:acpi_register_lps0_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580483680,
      "name": "lock_system_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
unsigned int lock_system_sleep()
```

```json
{
  "name": "lock_system_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580549344,
      "name": "lock_system_sleep",
      "external": true,
      "loc": "kernel/power/main.c:52",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_test_store"
      ],
      "caller_func": [
        "kernel/power/suspend.c:suspend_set_ops",
        "kernel/power/suspend.c:s2idle_set_ops",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernation_set_ops",
        "kernel/power/hibernate.c:hibernation_set_ops",
        "kernel/power/user.c:snapshot_write",
        "kernel/power/user.c:snapshot_read",
        "kernel/power/user.c:snapshot_release",
        "kernel/power/user.c:snapshot_open",
        "drivers/acpi/x86/s2idle.c:acpi_register_lps0_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580543520,
      "name": "lock_system_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void lock_system_sleep()
```

```json
{
  "name": "lock_system_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491135036,
      "name": "lock_system_sleep",
      "external": true,
      "loc": "kernel/power/main.c:24",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_test_store"
      ],
      "caller_func": [
        "kernel/power/suspend.c:suspend_set_ops",
        "kernel/power/suspend.c:s2idle_set_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491131552,
      "name": "lock_system_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void lock_system_sleep()
```

```json
{
  "name": "lock_system_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225131988,
      "name": "lock_system_sleep",
      "external": true,
      "loc": "kernel/power/main.c:24",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_test_store"
      ],
      "caller_func": [
        "kernel/power/suspend.c:suspend_set_ops",
        "kernel/power/suspend.c:s2idle_set_ops",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_write",
        "kernel/power/user.c:snapshot_read",
        "kernel/power/user.c:snapshot_release",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225129224,
      "name": "lock_system_sleep",
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
void lock_system_sleep()
```

```json
{
  "name": "lock_system_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284026488,
      "name": "lock_system_sleep",
      "external": true,
      "loc": "kernel/power/main.c:24",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_test_store"
      ],
      "caller_func": [
        "kernel/power/suspend.c:suspend_set_ops",
        "kernel/power/suspend.c:s2idle_set_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284022160,
      "name": "lock_system_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void lock_system_sleep()
```

```json
{
  "name": "lock_system_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579897907,
      "name": "lock_system_sleep",
      "external": true,
      "loc": "kernel/power/main.c:24",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_test_store"
      ],
      "caller_func": [
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_write",
        "kernel/power/user.c:snapshot_read",
        "kernel/power/user.c:snapshot_release",
        "kernel/power/user.c:snapshot_open",
        "kernel/kexec_core.c:kernel_kexec",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579895392,
      "name": "lock_system_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void lock_system_sleep()
```

```json
{
  "name": "lock_system_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579832995,
      "name": "lock_system_sleep",
      "external": true,
      "loc": "kernel/power/main.c:24",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_test_store"
      ],
      "caller_func": [
        "kernel/power/suspend.c:suspend_set_ops",
        "kernel/power/suspend.c:s2idle_set_ops",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_write",
        "kernel/power/user.c:snapshot_read",
        "kernel/power/user.c:snapshot_release",
        "kernel/power/user.c:snapshot_open",
        "kernel/kexec_core.c:kernel_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579830352,
      "name": "lock_system_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void lock_system_sleep()
```

```json
{
  "name": "lock_system_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579886195,
      "name": "lock_system_sleep",
      "external": true,
      "loc": "kernel/power/main.c:24",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_test_store"
      ],
      "caller_func": [
        "kernel/power/suspend.c:suspend_set_ops",
        "kernel/power/suspend.c:s2idle_set_ops",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_write",
        "kernel/power/user.c:snapshot_read",
        "kernel/power/user.c:snapshot_release",
        "kernel/power/user.c:snapshot_open",
        "kernel/kexec_core.c:kernel_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579883552,
      "name": "lock_system_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void lock_system_sleep()
```

```json
{
  "name": "lock_system_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579931955,
      "name": "lock_system_sleep",
      "external": true,
      "loc": "kernel/power/main.c:24",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_test_store"
      ],
      "caller_func": [
        "kernel/power/suspend.c:suspend_set_ops",
        "kernel/power/suspend.c:s2idle_set_ops",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_write",
        "kernel/power/user.c:snapshot_read",
        "kernel/power/user.c:snapshot_release",
        "kernel/power/user.c:snapshot_open",
        "kernel/kexec_core.c:kernel_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579929312,
      "name": "lock_system_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void lock_system_sleep()
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>unsigned int</code>
</li>
</ul>
</details>
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
void lock_system_sleep()
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
