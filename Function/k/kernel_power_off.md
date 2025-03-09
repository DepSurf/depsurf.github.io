# Function: <code>kernel_power_off</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void kernel_power_off()
```

```json
{
  "name": "kernel_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579511632,
      "name": "kernel_power_off",
      "external": true,
      "loc": "kernel/reboot.c:257",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:SYSC_reboot",
        "kernel/reboot.c:poweroff_work_func",
        "kernel/power/hibernate.c:power_down",
        "kernel/power/poweroff.c:do_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579511632,
      "name": "kernel_power_off",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void kernel_power_off()
```

```json
{
  "name": "kernel_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579525728,
      "name": "kernel_power_off",
      "external": true,
      "loc": "kernel/reboot.c:257",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:poweroff_work_func",
        "kernel/reboot.c:SYSC_reboot",
        "kernel/power/hibernate.c:power_down",
        "kernel/power/poweroff.c:do_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579525728,
      "name": "kernel_power_off",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void kernel_power_off()
```

```json
{
  "name": "kernel_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579549376,
      "name": "kernel_power_off",
      "external": true,
      "loc": "kernel/reboot.c:257",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:poweroff_work_func",
        "kernel/reboot.c:SYSC_reboot",
        "kernel/power/hibernate.c:power_down",
        "kernel/power/poweroff.c:do_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579549376,
      "name": "kernel_power_off",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void kernel_power_off()
```

```json
{
  "name": "kernel_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579536016,
      "name": "kernel_power_off",
      "external": true,
      "loc": "kernel/reboot.c:257",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:poweroff_work_func",
        "kernel/reboot.c:SYSC_reboot",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/poweroff.c:do_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579536016,
      "name": "kernel_power_off",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void kernel_power_off()
```

```json
{
  "name": "kernel_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579562752,
      "name": "kernel_power_off",
      "external": true,
      "loc": "kernel/reboot.c:284",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:poweroff_work_func",
        "kernel/reboot.c:SYSC_reboot",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/poweroff.c:do_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579562752,
      "name": "kernel_power_off",
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
void kernel_power_off()
```

```json
{
  "name": "kernel_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579590896,
      "name": "kernel_power_off",
      "external": true,
      "loc": "kernel/reboot.c:284",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:poweroff_work_func",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/poweroff.c:do_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579590896,
      "name": "kernel_power_off",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void kernel_power_off()
```

```json
{
  "name": "kernel_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579628416,
      "name": "kernel_power_off",
      "external": true,
      "loc": "kernel/reboot.c:285",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:poweroff_work_func",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/poweroff.c:do_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579628416,
      "name": "kernel_power_off",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void kernel_power_off()
```

```json
{
  "name": "kernel_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579653280,
      "name": "kernel_power_off",
      "external": true,
      "loc": "kernel/reboot.c:287",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:poweroff_work_func",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/poweroff.c:do_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579653280,
      "name": "kernel_power_off",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void kernel_power_off()
```

```json
{
  "name": "kernel_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579690400,
      "name": "kernel_power_off",
      "external": true,
      "loc": "kernel/reboot.c:287",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:poweroff_work_func",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/poweroff.c:do_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579690400,
      "name": "kernel_power_off",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void kernel_power_off()
```

```json
{
  "name": "kernel_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579730800,
      "name": "kernel_power_off",
      "external": true,
      "loc": "kernel/reboot.c:287",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:poweroff_work_func",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/hibernate.c:power_down",
        "kernel/power/poweroff.c:do_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579730800,
      "name": "kernel_power_off",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void kernel_power_off()
```

```json
{
  "name": "kernel_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579711024,
      "name": "kernel_power_off",
      "external": true,
      "loc": "kernel/reboot.c:287",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:poweroff_work_func",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/hibernate.c:power_down",
        "kernel/power/poweroff.c:do_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579711024,
      "name": "kernel_power_off",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void kernel_power_off()
```

```json
{
  "name": "kernel_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579718432,
      "name": "kernel_power_off",
      "external": true,
      "loc": "kernel/reboot.c:287",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:poweroff_work_func",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/poweroff.c:do_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579718432,
      "name": "kernel_power_off",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void kernel_power_off()
```

```json
{
  "name": "kernel_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579796784,
      "name": "kernel_power_off",
      "external": true,
      "loc": "kernel/reboot.c:288",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:hw_failure_emergency_poweroff_func",
        "kernel/reboot.c:poweroff_work_func",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/poweroff.c:do_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579796784,
      "name": "kernel_power_off",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void kernel_power_off()
```

```json
{
  "name": "kernel_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579905696,
      "name": "kernel_power_off",
      "external": true,
      "loc": "kernel/reboot.c:661",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:hw_failure_emergency_poweroff_func",
        "kernel/reboot.c:poweroff_work_func",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/poweroff.c:do_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579905696,
      "name": "kernel_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void kernel_power_off()
```

```json
{
  "name": "kernel_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580058672,
      "name": "kernel_power_off",
      "external": true,
      "loc": "kernel/reboot.c:678",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:hw_failure_emergency_poweroff_func",
        "kernel/reboot.c:poweroff_work_func",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/poweroff.c:do_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580058672,
      "name": "kernel_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void kernel_power_off()
```

```json
{
  "name": "kernel_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580113120,
      "name": "kernel_power_off",
      "external": true,
      "loc": "kernel/reboot.c:678",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:hw_failure_emergency_poweroff_func",
        "kernel/reboot.c:poweroff_work_func",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/poweroff.c:do_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580113120,
      "name": "kernel_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void kernel_power_off()
```

```json
{
  "name": "kernel_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580158304,
      "name": "kernel_power_off",
      "external": true,
      "loc": "kernel/reboot.c:693",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:hw_failure_emergency_poweroff_func",
        "kernel/reboot.c:poweroff_work_func",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/poweroff.c:do_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580158304,
      "name": "kernel_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void kernel_power_off()
```

```json
{
  "name": "kernel_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490868880,
      "name": "kernel_power_off",
      "external": true,
      "loc": "kernel/reboot.c:287",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:poweroff_work_func",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/poweroff.c:do_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490868880,
      "name": "kernel_power_off",
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
void kernel_power_off()
```

```json
{
  "name": "kernel_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224886968,
      "name": "kernel_power_off",
      "external": true,
      "loc": "kernel/reboot.c:287",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:poweroff_work_func",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/poweroff.c:do_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224886968,
      "name": "kernel_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void kernel_power_off()
```

```json
{
  "name": "kernel_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283699808,
      "name": "kernel_power_off",
      "external": true,
      "loc": "kernel/reboot.c:287",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/pseries/ras.c:ras_error_interrupt",
        "arch/powerpc/platforms/pseries/ras.c:ras_epow_interrupt",
        "kernel/reboot.c:poweroff_work_func",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/poweroff.c:do_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283699808,
      "name": "kernel_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void kernel_power_off()
```

```json
{
  "name": "kernel_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271524130,
      "name": "kernel_power_off",
      "external": true,
      "loc": "kernel/reboot.c:287",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:poweroff_work_func",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/poweroff.c:do_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271524130,
      "name": "kernel_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void kernel_power_off()
```

```json
{
  "name": "kernel_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579666720,
      "name": "kernel_power_off",
      "external": true,
      "loc": "kernel/reboot.c:287",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:poweroff_work_func",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/poweroff.c:do_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579666720,
      "name": "kernel_power_off",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void kernel_power_off()
```

```json
{
  "name": "kernel_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579595072,
      "name": "kernel_power_off",
      "external": true,
      "loc": "kernel/reboot.c:287",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:poweroff_work_func",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/poweroff.c:do_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579595072,
      "name": "kernel_power_off",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void kernel_power_off()
```

```json
{
  "name": "kernel_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579663952,
      "name": "kernel_power_off",
      "external": true,
      "loc": "kernel/reboot.c:287",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:poweroff_work_func",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/poweroff.c:do_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579663952,
      "name": "kernel_power_off",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void kernel_power_off()
```

```json
{
  "name": "kernel_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579697984,
      "name": "kernel_power_off",
      "external": true,
      "loc": "kernel/reboot.c:287",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:poweroff_work_func",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/poweroff.c:do_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579697984,
      "name": "kernel_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
