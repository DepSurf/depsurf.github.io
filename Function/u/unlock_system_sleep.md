# Function: <code>unlock_system_sleep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unlock_system_sleep",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579685429,
      "name": "unlock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:443",
      "file": "kernel/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_test_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579689162,
      "name": "unlock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:443",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_set_ops",
        "kernel/power/suspend.c:freeze_set_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579693205,
      "name": "unlock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:443",
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
      "addr": 18446744071579718996,
      "name": "unlock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:443",
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
      "addr": 18446744071579949856,
      "name": "unlock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:443",
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
  "name": "unlock_system_sleep",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579704533,
      "name": "unlock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:442",
      "file": "kernel/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_test_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579708458,
      "name": "unlock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:442",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_set_ops",
        "kernel/power/suspend.c:freeze_set_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579715578,
      "name": "unlock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:442",
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
      "addr": 18446744071579739778,
      "name": "unlock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:442",
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
      "addr": 18446744071579981248,
      "name": "unlock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:442",
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
  "name": "unlock_system_sleep",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579732085,
      "name": "unlock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:444",
      "file": "kernel/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_test_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579735947,
      "name": "unlock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:444",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_set_ops",
        "kernel/power/suspend.c:freeze_set_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579743146,
      "name": "unlock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:444",
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
      "addr": 18446744071579767122,
      "name": "unlock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:444",
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
      "addr": 18446744071580011744,
      "name": "unlock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:444",
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
  "name": "unlock_system_sleep",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579727989,
      "name": "unlock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:447",
      "file": "kernel/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_test_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579731819,
      "name": "unlock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:447",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_set_ops",
        "kernel/power/suspend.c:freeze_set_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579739291,
      "name": "unlock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:447",
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
      "addr": 18446744071579764787,
      "name": "unlock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:447",
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
      "addr": 18446744071580018958,
      "name": "unlock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:447",
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
  "name": "unlock_system_sleep",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579760837,
      "name": "unlock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:452",
      "file": "kernel/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_test_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579764843,
      "name": "unlock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:452",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_set_ops",
        "kernel/power/suspend.c:s2idle_set_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579772459,
      "name": "unlock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:452",
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
      "addr": 18446744071579798275,
      "name": "unlock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:452",
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
      "addr": 18446744071580065902,
      "name": "unlock_system_sleep",
      "external": false,
      "loc": "include/linux/suspend.h:452",
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
void unlock_system_sleep()
```

```json
{
  "name": "unlock_system_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579795154,
      "name": "unlock_system_sleep",
      "external": true,
      "loc": "kernel/power/main.c:32",
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
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate",
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
      "addr": 18446744071579793280,
      "name": "unlock_system_sleep",
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
void unlock_system_sleep()
```

```json
{
  "name": "unlock_system_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579841762,
      "name": "unlock_system_sleep",
      "external": true,
      "loc": "kernel/power/main.c:31",
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
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate",
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
      "addr": 18446744071579839872,
      "name": "unlock_system_sleep",
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
void unlock_system_sleep()
```

```json
{
  "name": "unlock_system_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579875746,
      "name": "unlock_system_sleep",
      "external": true,
      "loc": "kernel/power/main.c:30",
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
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate",
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
      "addr": 18446744071579873872,
      "name": "unlock_system_sleep",
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
void unlock_system_sleep()
```

```json
{
  "name": "unlock_system_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579926034,
      "name": "unlock_system_sleep",
      "external": true,
      "loc": "kernel/power/main.c:31",
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
      "addr": 18446744071579923328,
      "name": "unlock_system_sleep",
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
void unlock_system_sleep()
```

```json
{
  "name": "unlock_system_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579971154,
      "name": "unlock_system_sleep",
      "external": true,
      "loc": "kernel/power/main.c:31",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_test_store",
        "kernel/power/main.c:pm_test_store"
      ],
      "caller_func": [
        "kernel/power/suspend.c:suspend_set_ops",
        "kernel/power/suspend.c:s2idle_set_ops",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate",
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
      "addr": 18446744071579967104,
      "name": "unlock_system_sleep",
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
void unlock_system_sleep()
```

```json
{
  "name": "unlock_system_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579959074,
      "name": "unlock_system_sleep",
      "external": true,
      "loc": "kernel/power/main.c:31",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_test_store",
        "kernel/power/main.c:pm_test_store"
      ],
      "caller_func": [
        "kernel/power/suspend.c:suspend_set_ops",
        "kernel/power/suspend.c:s2idle_set_ops",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate",
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
      "addr": 18446744071579955024,
      "name": "unlock_system_sleep",
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
void unlock_system_sleep()
```

```json
{
  "name": "unlock_system_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579961698,
      "name": "unlock_system_sleep",
      "external": true,
      "loc": "kernel/power/main.c:31",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_test_store",
        "kernel/power/main.c:pm_test_store"
      ],
      "caller_func": [
        "kernel/power/suspend.c:suspend_set_ops",
        "kernel/power/suspend.c:s2idle_set_ops",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate",
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
      "addr": 18446744071579957744,
      "name": "unlock_system_sleep",
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
void unlock_system_sleep()
```

```json
{
  "name": "unlock_system_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580091410,
      "name": "unlock_system_sleep",
      "external": true,
      "loc": "kernel/power/main.c:31",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_test_store",
        "kernel/power/main.c:pm_test_store"
      ],
      "caller_func": [
        "kernel/power/suspend.c:suspend_set_ops",
        "kernel/power/suspend.c:s2idle_set_ops",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate",
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
      "addr": 18446744071580087104,
      "name": "unlock_system_sleep",
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
void unlock_system_sleep()
```

```json
{
  "name": "unlock_system_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580228651,
      "name": "unlock_system_sleep",
      "external": true,
      "loc": "kernel/power/main.c:31",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_test_store",
        "kernel/power/main.c:pm_test_store"
      ],
      "caller_func": [
        "kernel/power/suspend.c:suspend_set_ops",
        "kernel/power/suspend.c:s2idle_set_ops",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate",
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
      "addr": 18446744071580223888,
      "name": "unlock_system_sleep",
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
void unlock_system_sleep(unsigned int flags)
```

```json
{
  "name": "unlock_system_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580420446,
      "name": "unlock_system_sleep",
      "external": true,
      "loc": "kernel/power/main.c:33",
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
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate",
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
      "addr": 18446744071580414880,
      "name": "unlock_system_sleep",
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
void unlock_system_sleep(unsigned int flags)
```

```json
{
  "name": "unlock_system_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580489598,
      "name": "unlock_system_sleep",
      "external": true,
      "loc": "kernel/power/main.c:61",
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
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate",
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
      "addr": 18446744071580483760,
      "name": "unlock_system_sleep",
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
void unlock_system_sleep(unsigned int flags)
```

```json
{
  "name": "unlock_system_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580549438,
      "name": "unlock_system_sleep",
      "external": true,
      "loc": "kernel/power/main.c:61",
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
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate",
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
      "addr": 18446744071580543600,
      "name": "unlock_system_sleep",
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
void unlock_system_sleep()
```

```json
{
  "name": "unlock_system_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491135168,
      "name": "unlock_system_sleep",
      "external": true,
      "loc": "kernel/power/main.c:31",
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
      "addr": 18446603336491131608,
      "name": "unlock_system_sleep",
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
void unlock_system_sleep()
```

```json
{
  "name": "unlock_system_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225132156,
      "name": "unlock_system_sleep",
      "external": true,
      "loc": "kernel/power/main.c:31",
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
      "addr": 3225129288,
      "name": "unlock_system_sleep",
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
void unlock_system_sleep()
```

```json
{
  "name": "unlock_system_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284026656,
      "name": "unlock_system_sleep",
      "external": true,
      "loc": "kernel/power/main.c:31",
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
      "addr": 13835058055284022240,
      "name": "unlock_system_sleep",
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
void unlock_system_sleep()
```

```json
{
  "name": "unlock_system_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579898018,
      "name": "unlock_system_sleep",
      "external": true,
      "loc": "kernel/power/main.c:31",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_test_store"
      ],
      "caller_func": [
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
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
      "addr": 18446744071579895440,
      "name": "unlock_system_sleep",
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
void unlock_system_sleep()
```

```json
{
  "name": "unlock_system_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579833106,
      "name": "unlock_system_sleep",
      "external": true,
      "loc": "kernel/power/main.c:31",
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
      "addr": 18446744071579830400,
      "name": "unlock_system_sleep",
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
void unlock_system_sleep()
```

```json
{
  "name": "unlock_system_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579886306,
      "name": "unlock_system_sleep",
      "external": true,
      "loc": "kernel/power/main.c:31",
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
      "addr": 18446744071579883600,
      "name": "unlock_system_sleep",
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
void unlock_system_sleep()
```

```json
{
  "name": "unlock_system_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579932066,
      "name": "unlock_system_sleep",
      "external": true,
      "loc": "kernel/power/main.c:31",
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
      "addr": 18446744071579929360,
      "name": "unlock_system_sleep",
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
void unlock_system_sleep()
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
<b>Param added. </b>
<code>unsigned int flags</code>
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
void unlock_system_sleep()
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
