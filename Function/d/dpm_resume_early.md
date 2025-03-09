# Function: <code>dpm_resume_early</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void dpm_resume_early(pm_message_t state)
```

```json
{
  "name": "dpm_resume_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584456992,
      "name": "dpm_resume_early",
      "external": true,
      "loc": "drivers/base/power/main.c:667",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "drivers/base/power/main.c:dpm_resume_start",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_end",
        "drivers/base/power/main.c:dpm_suspend_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584456992,
      "name": "dpm_resume_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 704
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
void dpm_resume_early(pm_message_t state)
```

```json
{
  "name": "dpm_resume_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584792832,
      "name": "dpm_resume_early",
      "external": true,
      "loc": "drivers/base/power/main.c:669",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "drivers/base/power/main.c:dpm_suspend_end",
        "drivers/base/power/main.c:dpm_suspend_end",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_resume_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584792832,
      "name": "dpm_resume_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 723
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
void dpm_resume_early(pm_message_t state)
```

```json
{
  "name": "dpm_resume_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584984736,
      "name": "dpm_resume_early",
      "external": true,
      "loc": "drivers/base/power/main.c:727",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "drivers/base/power/main.c:dpm_suspend_end",
        "drivers/base/power/main.c:dpm_suspend_end",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_resume_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584984736,
      "name": "dpm_resume_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 726
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
void dpm_resume_early(pm_message_t state)
```

```json
{
  "name": "dpm_resume_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585069632,
      "name": "dpm_resume_early",
      "external": true,
      "loc": "drivers/base/power/main.c:735",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "drivers/base/power/main.c:dpm_suspend_end",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_resume_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585069632,
      "name": "dpm_resume_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 729
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
void dpm_resume_early(pm_message_t state)
```

```json
{
  "name": "dpm_resume_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585492768,
      "name": "dpm_resume_early",
      "external": true,
      "loc": "drivers/base/power/main.c:780",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "drivers/base/power/main.c:dpm_suspend_end",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_resume_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585492768,
      "name": "dpm_resume_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 737
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
void dpm_resume_early(pm_message_t state)
```

```json
{
  "name": "dpm_resume_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585737424,
      "name": "dpm_resume_early",
      "external": true,
      "loc": "drivers/base/power/main.c:868",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "drivers/base/power/main.c:dpm_suspend_end",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_resume_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585737424,
      "name": "dpm_resume_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 734
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
void dpm_resume_early(pm_message_t state)
```

```json
{
  "name": "dpm_resume_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585870144,
      "name": "dpm_resume_early",
      "external": true,
      "loc": "drivers/base/power/main.c:869",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "drivers/base/power/main.c:dpm_suspend_end",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_resume_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585870144,
      "name": "dpm_resume_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 734
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
void dpm_resume_early(pm_message_t state)
```

```json
{
  "name": "dpm_resume_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586107184,
      "name": "dpm_resume_early",
      "external": true,
      "loc": "drivers/base/power/main.c:871",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "drivers/base/power/main.c:dpm_suspend_end",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_resume_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586107184,
      "name": "dpm_resume_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 678
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
void dpm_resume_early(pm_message_t state)
```

```json
{
  "name": "dpm_resume_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586254688,
      "name": "dpm_resume_early",
      "external": true,
      "loc": "drivers/base/power/main.c:898",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "drivers/base/power/main.c:dpm_suspend_end",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_resume_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586254688,
      "name": "dpm_resume_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 678
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
void dpm_resume_early(pm_message_t state)
```

```json
{
  "name": "dpm_resume_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587023712,
      "name": "dpm_resume_early",
      "external": true,
      "loc": "drivers/base/power/main.c:837",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "drivers/base/power/main.c:dpm_suspend_end",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_resume_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587023712,
      "name": "dpm_resume_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 686
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
void dpm_resume_early(pm_message_t state)
```

```json
{
  "name": "dpm_resume_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587108240,
      "name": "dpm_resume_early",
      "external": true,
      "loc": "drivers/base/power/main.c:836",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "drivers/base/power/main.c:dpm_suspend_end",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_resume_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587108240,
      "name": "dpm_resume_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 650
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
void dpm_resume_early(pm_message_t state)
```

```json
{
  "name": "dpm_resume_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586994592,
      "name": "dpm_resume_early",
      "external": true,
      "loc": "drivers/base/power/main.c:837",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "drivers/base/power/main.c:dpm_suspend_end",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_resume_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586994592,
      "name": "dpm_resume_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 650
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
void dpm_resume_early(pm_message_t state)
```

```json
{
  "name": "dpm_resume_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpm_resume_early",
      "external": true,
      "loc": "drivers/base/power/main.c:836",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "drivers/base/power/main.c:dpm_suspend_end",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_resume_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592492225,
      "name": "dpm_resume_early.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071587560736,
      "name": "dpm_resume_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 638
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
void dpm_resume_early(pm_message_t state)
```

```json
{
  "name": "dpm_resume_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpm_resume_early",
      "external": true,
      "loc": "drivers/base/power/main.c:833",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "drivers/base/power/main.c:dpm_suspend_end",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_resume_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594362179,
      "name": "dpm_resume_early.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071588894240,
      "name": "dpm_resume_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 673
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
void dpm_resume_early(pm_message_t state)
```

```json
{
  "name": "dpm_resume_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590404480,
      "name": "dpm_resume_early",
      "external": true,
      "loc": "drivers/base/power/main.c:833",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "drivers/base/power/main.c:dpm_suspend_end",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_resume_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590404480,
      "name": "dpm_resume_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 703
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
void dpm_resume_early(pm_message_t state)
```

```json
{
  "name": "dpm_resume_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590724032,
      "name": "dpm_resume_early",
      "external": true,
      "loc": "drivers/base/power/main.c:833",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "drivers/base/power/main.c:dpm_suspend_end",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_resume_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590724032,
      "name": "dpm_resume_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 703
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
void dpm_resume_early(pm_message_t state)
```

```json
{
  "name": "dpm_resume_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591086352,
      "name": "dpm_resume_early",
      "external": true,
      "loc": "drivers/base/power/main.c:839",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "drivers/base/power/main.c:dpm_suspend_end",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_resume_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591086352,
      "name": "dpm_resume_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 483
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
void dpm_resume_early(pm_message_t state)
```

```json
{
  "name": "dpm_resume_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499075032,
      "name": "dpm_resume_early",
      "external": true,
      "loc": "drivers/base/power/main.c:898",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "drivers/base/power/main.c:dpm_suspend_end",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_resume_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499075032,
      "name": "dpm_resume_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 796
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
void dpm_resume_early(pm_message_t state)
```

```json
{
  "name": "dpm_resume_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231627784,
      "name": "dpm_resume_early",
      "external": true,
      "loc": "drivers/base/power/main.c:898",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "drivers/base/power/main.c:dpm_suspend_end",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_resume_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231627784,
      "name": "dpm_resume_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 796
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
void dpm_resume_early(pm_message_t state)
```

```json
{
  "name": "dpm_resume_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292253696,
      "name": "dpm_resume_early",
      "external": true,
      "loc": "drivers/base/power/main.c:898",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "drivers/base/power/main.c:dpm_suspend_end",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_resume_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292253696,
      "name": "dpm_resume_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1012
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void dpm_resume_early(pm_message_t state)
```

```json
{
  "name": "dpm_resume_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586018016,
      "name": "dpm_resume_early",
      "external": true,
      "loc": "drivers/base/power/main.c:898",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend_end",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_resume_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586018016,
      "name": "dpm_resume_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 678
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
void dpm_resume_early(pm_message_t state)
```

```json
{
  "name": "dpm_resume_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585864000,
      "name": "dpm_resume_early",
      "external": true,
      "loc": "drivers/base/power/main.c:898",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "drivers/base/power/main.c:dpm_suspend_end",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_resume_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585864000,
      "name": "dpm_resume_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 678
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
void dpm_resume_early(pm_message_t state)
```

```json
{
  "name": "dpm_resume_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586204704,
      "name": "dpm_resume_early",
      "external": true,
      "loc": "drivers/base/power/main.c:898",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "drivers/base/power/main.c:dpm_suspend_end",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_resume_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586204704,
      "name": "dpm_resume_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 678
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
void dpm_resume_early(pm_message_t state)
```

```json
{
  "name": "dpm_resume_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586313424,
      "name": "dpm_resume_early",
      "external": true,
      "loc": "drivers/base/power/main.c:898",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "drivers/base/power/main.c:dpm_suspend_end",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_resume_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586313424,
      "name": "dpm_resume_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 722
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
void dpm_resume_early(pm_message_t state)
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
