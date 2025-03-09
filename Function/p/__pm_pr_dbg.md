# Function: <code>__pm_pr_dbg</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void __pm_pr_dbg(bool defer, const char * fmt, void (anon))
```

```json
{
  "name": "__pm_pr_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579762016,
      "name": "__pm_pr_dbg",
      "external": true,
      "loc": "kernel/power/main.c:398",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time",
        "drivers/base/power/main.c:dpm_show_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579762016,
      "name": "__pm_pr_dbg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void __pm_pr_dbg(bool defer, const char * fmt, void (anon))
```

```json
{
  "name": "__pm_pr_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pm_pr_dbg",
      "external": true,
      "loc": "kernel/power/main.c:427",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time",
        "drivers/base/power/main.c:dpm_show_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579796582,
      "name": "__pm_pr_dbg.cold.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071579796480,
      "name": "__pm_pr_dbg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void __pm_pr_dbg(bool defer, const char * fmt, void (anon))
```

```json
{
  "name": "__pm_pr_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pm_pr_dbg",
      "external": true,
      "loc": "kernel/power/main.c:416",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time",
        "drivers/base/power/main.c:dpm_show_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579843190,
      "name": "__pm_pr_dbg.cold.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071579843088,
      "name": "__pm_pr_dbg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void __pm_pr_dbg(bool defer, const char * fmt, void (anon))
```

```json
{
  "name": "__pm_pr_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pm_pr_dbg",
      "external": true,
      "loc": "kernel/power/main.c:428",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time",
        "drivers/base/power/main.c:dpm_show_time",
        "drivers/base/power/wakeup.c:pm_wakeup_pending",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579877222,
      "name": "__pm_pr_dbg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071579877120,
      "name": "__pm_pr_dbg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void __pm_pr_dbg(bool defer, const char * fmt, void (anon))
```

```json
{
  "name": "__pm_pr_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pm_pr_dbg",
      "external": true,
      "loc": "kernel/power/main.c:514",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time",
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe",
        "drivers/base/power/main.c:dpm_show_time",
        "drivers/base/power/wakeup.c:pm_wakeup_pending",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579927430,
      "name": "__pm_pr_dbg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071579927328,
      "name": "__pm_pr_dbg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void __pm_pr_dbg(bool defer, const char * fmt, void (anon))
```

```json
{
  "name": "__pm_pr_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pm_pr_dbg",
      "external": true,
      "loc": "kernel/power/main.c:553",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time",
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe",
        "drivers/base/power/main.c:dpm_show_time",
        "drivers/base/power/wakeup.c:pm_wakeup_pending",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579971446,
      "name": "__pm_pr_dbg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071579971344,
      "name": "__pm_pr_dbg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void __pm_pr_dbg(bool defer, const char * fmt, void (anon))
```

```json
{
  "name": "__pm_pr_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pm_pr_dbg",
      "external": true,
      "loc": "kernel/power/main.c:553",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time",
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/power/main.c:dpm_show_time",
        "drivers/base/power/wakeup.c:pm_wakeup_pending",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591291130,
      "name": "__pm_pr_dbg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071579959232,
      "name": "__pm_pr_dbg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void __pm_pr_dbg(bool defer, const char * fmt, void (anon))
```

```json
{
  "name": "__pm_pr_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pm_pr_dbg",
      "external": true,
      "loc": "kernel/power/main.c:553",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time",
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/power/main.c:dpm_show_time",
        "drivers/base/power/wakeup.c:pm_wakeup_pending",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591234163,
      "name": "__pm_pr_dbg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071579961856,
      "name": "__pm_pr_dbg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void __pm_pr_dbg(bool defer, const char * fmt, void (anon))
```

```json
{
  "name": "__pm_pr_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pm_pr_dbg",
      "external": true,
      "loc": "kernel/power/main.c:556",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time",
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe",
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/power/main.c:dpm_show_time",
        "drivers/base/power/wakeup.c:pm_wakeup_pending",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592122180,
      "name": "__pm_pr_dbg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071580091568,
      "name": "__pm_pr_dbg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void __pm_pr_dbg(bool defer, const char * fmt, void (anon))
```

```json
{
  "name": "__pm_pr_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491136424,
      "name": "__pm_pr_dbg",
      "external": true,
      "loc": "kernel/power/main.c:514",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time",
        "drivers/base/power/main.c:dpm_show_time",
        "drivers/base/power/wakeup.c:pm_wakeup_pending",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491136424,
      "name": "__pm_pr_dbg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void __pm_pr_dbg(bool defer, const char * fmt, void (anon))
```

```json
{
  "name": "__pm_pr_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225133572,
      "name": "__pm_pr_dbg",
      "external": true,
      "loc": "kernel/power/main.c:514",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time",
        "drivers/base/power/main.c:dpm_show_time",
        "drivers/base/power/wakeup.c:pm_wakeup_pending",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225133572,
      "name": "__pm_pr_dbg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void __pm_pr_dbg(bool defer, const char * fmt, void (anon))
```

```json
{
  "name": "__pm_pr_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284028592,
      "name": "__pm_pr_dbg",
      "external": true,
      "loc": "kernel/power/main.c:514",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time",
        "drivers/base/power/main.c:dpm_show_time",
        "drivers/base/power/wakeup.c:pm_wakeup_pending",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284028592,
      "name": "__pm_pr_dbg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void __pm_pr_dbg(bool defer, const char * fmt, void (anon))
```

```json
{
  "name": "__pm_pr_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pm_pr_dbg",
      "external": true,
      "loc": "kernel/power/main.c:514",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time",
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe",
        "drivers/base/power/main.c:dpm_show_time",
        "drivers/base/power/wakeup.c:pm_wakeup_pending",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579899078,
      "name": "__pm_pr_dbg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071579898976,
      "name": "__pm_pr_dbg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void __pm_pr_dbg(bool defer, const char * fmt, void (anon))
```

```json
{
  "name": "__pm_pr_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pm_pr_dbg",
      "external": true,
      "loc": "kernel/power/main.c:514",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time",
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe",
        "drivers/base/power/main.c:dpm_show_time",
        "drivers/base/power/wakeup.c:pm_wakeup_pending",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579834502,
      "name": "__pm_pr_dbg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071579834400,
      "name": "__pm_pr_dbg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void __pm_pr_dbg(bool defer, const char * fmt, void (anon))
```

```json
{
  "name": "__pm_pr_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pm_pr_dbg",
      "external": true,
      "loc": "kernel/power/main.c:514",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time",
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe",
        "drivers/base/power/main.c:dpm_show_time",
        "drivers/base/power/wakeup.c:pm_wakeup_pending",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579887702,
      "name": "__pm_pr_dbg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071579887600,
      "name": "__pm_pr_dbg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void __pm_pr_dbg(bool defer, const char * fmt, void (anon))
```

```json
{
  "name": "__pm_pr_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pm_pr_dbg",
      "external": true,
      "loc": "kernel/power/main.c:514",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time",
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe",
        "drivers/base/power/main.c:dpm_show_time",
        "drivers/base/power/wakeup.c:pm_wakeup_pending",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579933462,
      "name": "__pm_pr_dbg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071579933360,
      "name": "__pm_pr_dbg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void __pm_pr_dbg(bool defer, const char * fmt, void (anon))
```
</details>
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void __pm_pr_dbg(bool defer, const char * fmt, void (anon))
```
</details>
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
void __pm_pr_dbg(bool defer, const char * fmt, void (anon))
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
