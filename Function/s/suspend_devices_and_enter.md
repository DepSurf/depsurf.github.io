# Function: <code>suspend_devices_and_enter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int suspend_devices_and_enter(suspend_state_t state)
```

```json
{
  "name": "suspend_devices_and_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579689648,
      "name": "suspend_devices_and_enter",
      "external": true,
      "loc": "kernel/power/suspend.c:403",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/hibernate.c:power_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579689648,
      "name": "suspend_devices_and_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1837
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
int suspend_devices_and_enter(suspend_state_t state)
```

```json
{
  "name": "suspend_devices_and_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579708944,
      "name": "suspend_devices_and_enter",
      "external": true,
      "loc": "kernel/power/suspend.c:405",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/hibernate.c:power_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579708944,
      "name": "suspend_devices_and_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1760
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
int suspend_devices_and_enter(suspend_state_t state)
```

```json
{
  "name": "suspend_devices_and_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579736480,
      "name": "suspend_devices_and_enter",
      "external": true,
      "loc": "kernel/power/suspend.c:428",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/hibernate.c:power_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579736480,
      "name": "suspend_devices_and_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1756
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
int suspend_devices_and_enter(suspend_state_t state)
```

```json
{
  "name": "suspend_devices_and_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579732352,
      "name": "suspend_devices_and_enter",
      "external": true,
      "loc": "kernel/power/suspend.c:451",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579732352,
      "name": "suspend_devices_and_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2005
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
int suspend_devices_and_enter(suspend_state_t state)
```

```json
{
  "name": "suspend_devices_and_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579765360,
      "name": "suspend_devices_and_enter",
      "external": true,
      "loc": "kernel/power/suspend.c:471",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579765360,
      "name": "suspend_devices_and_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2119
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
int suspend_devices_and_enter(suspend_state_t state)
```

```json
{
  "name": "suspend_devices_and_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "suspend_devices_and_enter",
      "external": true,
      "loc": "kernel/power/suspend.c:476",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579801765,
      "name": "suspend_devices_and_enter.cold.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071579799568,
      "name": "suspend_devices_and_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2034
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
int suspend_devices_and_enter(suspend_state_t state)
```

```json
{
  "name": "suspend_devices_and_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "suspend_devices_and_enter",
      "external": true,
      "loc": "kernel/power/suspend.c:482",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579848389,
      "name": "suspend_devices_and_enter.cold.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071579846192,
      "name": "suspend_devices_and_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2034
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
int suspend_devices_and_enter(suspend_state_t state)
```

```json
{
  "name": "suspend_devices_and_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "suspend_devices_and_enter",
      "external": true,
      "loc": "kernel/power/suspend.c:486",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579882580,
      "name": "suspend_devices_and_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071579881712,
      "name": "suspend_devices_and_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
int suspend_devices_and_enter(suspend_state_t state)
```

```json
{
  "name": "suspend_devices_and_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "suspend_devices_and_enter",
      "external": true,
      "loc": "kernel/power/suspend.c:476",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579932832,
      "name": "suspend_devices_and_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071579931920,
      "name": "suspend_devices_and_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
int suspend_devices_and_enter(suspend_state_t state)
```

```json
{
  "name": "suspend_devices_and_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "suspend_devices_and_enter",
      "external": true,
      "loc": "kernel/power/suspend.c:476",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/hibernate.c:power_down",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579977129,
      "name": "suspend_devices_and_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071579976000,
      "name": "suspend_devices_and_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
int suspend_devices_and_enter(suspend_state_t state)
```

```json
{
  "name": "suspend_devices_and_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "suspend_devices_and_enter",
      "external": true,
      "loc": "kernel/power/suspend.c:476",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/hibernate.c:power_down",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591292474,
      "name": "suspend_devices_and_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071579962800,
      "name": "suspend_devices_and_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 556
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
int suspend_devices_and_enter(suspend_state_t state)
```

```json
{
  "name": "suspend_devices_and_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "suspend_devices_and_enter",
      "external": true,
      "loc": "kernel/power/suspend.c:476",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591235292,
      "name": "suspend_devices_and_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071579965456,
      "name": "suspend_devices_and_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 556
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
int suspend_devices_and_enter(suspend_state_t state)
```

```json
{
  "name": "suspend_devices_and_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "suspend_devices_and_enter",
      "external": true,
      "loc": "kernel/power/suspend.c:474",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592123494,
      "name": "suspend_devices_and_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071580095104,
      "name": "suspend_devices_and_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 574
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
int suspend_devices_and_enter(suspend_state_t state)
```

```json
{
  "name": "suspend_devices_and_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "suspend_devices_and_enter",
      "external": true,
      "loc": "kernel/power/suspend.c:475",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593892860,
      "name": "suspend_devices_and_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071580232768,
      "name": "suspend_devices_and_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 682
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
int suspend_devices_and_enter(suspend_state_t state)
```

```json
{
  "name": "suspend_devices_and_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "suspend_devices_and_enter",
      "external": true,
      "loc": "kernel/power/suspend.c:482",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595983886,
      "name": "suspend_devices_and_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580426192,
      "name": "suspend_devices_and_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 739
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
int suspend_devices_and_enter(suspend_state_t state)
```

```json
{
  "name": "suspend_devices_and_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "suspend_devices_and_enter",
      "external": true,
      "loc": "kernel/power/suspend.c:482",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596502262,
      "name": "suspend_devices_and_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580495536,
      "name": "suspend_devices_and_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 739
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
int suspend_devices_and_enter(suspend_state_t state)
```

```json
{
  "name": "suspend_devices_and_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "suspend_devices_and_enter",
      "external": true,
      "loc": "kernel/power/suspend.c:482",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597399948,
      "name": "suspend_devices_and_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580555424,
      "name": "suspend_devices_and_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 739
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
int suspend_devices_and_enter(suspend_state_t state)
```

```json
{
  "name": "suspend_devices_and_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491142456,
      "name": "suspend_devices_and_enter",
      "external": true,
      "loc": "kernel/power/suspend.c:476",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491142456,
      "name": "suspend_devices_and_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 720
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
int suspend_devices_and_enter(suspend_state_t state)
```

```json
{
  "name": "suspend_devices_and_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225137536,
      "name": "suspend_devices_and_enter",
      "external": true,
      "loc": "kernel/power/suspend.c:476",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225137536,
      "name": "suspend_devices_and_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2464
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
int suspend_devices_and_enter(suspend_state_t state)
```

```json
{
  "name": "suspend_devices_and_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284033600,
      "name": "suspend_devices_and_enter",
      "external": true,
      "loc": "kernel/power/suspend.c:476",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284033600,
      "name": "suspend_devices_and_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3140
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "suspend_devices_and_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "suspend_devices_and_enter",
      "external": false,
      "loc": "kernel/power/power.h:196",
      "file": "kernel/power/user.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int suspend_devices_and_enter(suspend_state_t state)
```

```json
{
  "name": "suspend_devices_and_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "suspend_devices_and_enter",
      "external": true,
      "loc": "kernel/power/suspend.c:476",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579839720,
      "name": "suspend_devices_and_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
    },
    {
      "addr": 18446744071579837552,
      "name": "suspend_devices_and_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2011
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
int suspend_devices_and_enter(suspend_state_t state)
```

```json
{
  "name": "suspend_devices_and_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "suspend_devices_and_enter",
      "external": true,
      "loc": "kernel/power/suspend.c:476",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579893104,
      "name": "suspend_devices_and_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071579892192,
      "name": "suspend_devices_and_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
int suspend_devices_and_enter(suspend_state_t state)
```

```json
{
  "name": "suspend_devices_and_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "suspend_devices_and_enter",
      "external": true,
      "loc": "kernel/power/suspend.c:476",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579939088,
      "name": "suspend_devices_and_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071579938128,
      "name": "suspend_devices_and_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 654
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
int suspend_devices_and_enter(suspend_state_t state)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
int suspend_devices_and_enter(suspend_state_t state)
```
</details>
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
