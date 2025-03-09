# Function: <code>device_links_read_lock</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int device_links_read_lock()
```

```json
{
  "name": "device_links_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584905312,
      "name": "device_links_read_lock",
      "external": true,
      "loc": "drivers/base/core.c:63",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_get_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/main.c:dpm_wait_for_suppliers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584905312,
      "name": "device_links_read_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int device_links_read_lock()
```

```json
{
  "name": "device_links_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584990544,
      "name": "device_links_read_lock",
      "external": true,
      "loc": "drivers/base/core.c:64",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_get_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/main.c:dpm_wait_for_suppliers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584990544,
      "name": "device_links_read_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int device_links_read_lock()
```

```json
{
  "name": "device_links_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585412496,
      "name": "device_links_read_lock",
      "external": true,
      "loc": "drivers/base/core.c:64",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_get_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/main.c:dpm_wait_for_suppliers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585412496,
      "name": "device_links_read_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_links_read_lock()
```

```json
{
  "name": "device_links_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585656469,
      "name": "device_links_read_lock",
      "external": true,
      "loc": "drivers/base/core.c:61",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_pm_move_to_tail"
      ],
      "caller_func": [
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_get_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/main.c:dpm_wait_for_suppliers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585655104,
      "name": "device_links_read_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int device_links_read_lock()
```

```json
{
  "name": "device_links_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585788629,
      "name": "device_links_read_lock",
      "external": true,
      "loc": "drivers/base/core.c:62",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_pm_move_to_tail"
      ],
      "caller_func": [
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_get_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/main.c:dpm_wait_for_suppliers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585787232,
      "name": "device_links_read_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int device_links_read_lock()
```

```json
{
  "name": "device_links_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586019605,
      "name": "device_links_read_lock",
      "external": true,
      "loc": "drivers/base/core.c:62",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_pm_move_to_tail"
      ],
      "caller_func": [
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_get_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/main.c:dpm_wait_for_suppliers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586018064,
      "name": "device_links_read_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int device_links_read_lock()
```

```json
{
  "name": "device_links_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586167349,
      "name": "device_links_read_lock",
      "external": true,
      "loc": "drivers/base/core.c:63",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_pm_move_to_tail"
      ],
      "caller_func": [
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_get_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:dpm_wait_for_subordinate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586165776,
      "name": "device_links_read_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int device_links_read_lock()
```

```json
{
  "name": "device_links_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586927189,
      "name": "device_links_read_lock",
      "external": true,
      "loc": "drivers/base/core.c:71",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_pm_move_to_tail"
      ],
      "caller_func": [
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_get_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:dpm_wait_for_subordinate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586924320,
      "name": "device_links_read_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int device_links_read_lock()
```

```json
{
  "name": "device_links_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587010885,
      "name": "device_links_read_lock",
      "external": true,
      "loc": "drivers/base/core.c:165",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_pm_move_to_tail"
      ],
      "caller_func": [
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_get_suppliers",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:dpm_wait_for_subordinate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587008048,
      "name": "device_links_read_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int device_links_read_lock()
```

```json
{
  "name": "device_links_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586894133,
      "name": "device_links_read_lock",
      "external": true,
      "loc": "drivers/base/core.c:183",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_pm_move_to_tail"
      ],
      "caller_func": [
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_get_suppliers",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:dpm_wait_for_subordinate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586890816,
      "name": "device_links_read_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int device_links_read_lock()
```

```json
{
  "name": "device_links_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587456037,
      "name": "device_links_read_lock",
      "external": true,
      "loc": "drivers/base/core.c:195",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_pm_move_to_tail"
      ],
      "caller_func": [
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_get_suppliers",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:dpm_wait_for_subordinate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587452576,
      "name": "device_links_read_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int device_links_read_lock()
```

```json
{
  "name": "device_links_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588774949,
      "name": "device_links_read_lock",
      "external": true,
      "loc": "drivers/base/core.c:196",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_pm_move_to_tail"
      ],
      "caller_func": [
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_get_suppliers",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:dpm_wait_for_subordinate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588771248,
      "name": "device_links_read_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int device_links_read_lock()
```

```json
{
  "name": "device_links_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590268053,
      "name": "device_links_read_lock",
      "external": true,
      "loc": "drivers/base/core.c:264",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_pm_move_to_tail"
      ],
      "caller_func": [
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_get_suppliers",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:dpm_wait_for_subordinate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590264576,
      "name": "device_links_read_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int device_links_read_lock()
```

```json
{
  "name": "device_links_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590588453,
      "name": "device_links_read_lock",
      "external": true,
      "loc": "drivers/base/core.c:250",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_pm_move_to_tail"
      ],
      "caller_func": [
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_get_suppliers",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:dpm_wait_for_subordinate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590584816,
      "name": "device_links_read_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int device_links_read_lock()
```

```json
{
  "name": "device_links_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590947125,
      "name": "device_links_read_lock",
      "external": true,
      "loc": "drivers/base/core.c:251",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_pm_move_to_tail"
      ],
      "caller_func": [
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_get_suppliers",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:dpm_wait_for_subordinate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590943792,
      "name": "device_links_read_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int device_links_read_lock()
```

```json
{
  "name": "device_links_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498963300,
      "name": "device_links_read_lock",
      "external": true,
      "loc": "drivers/base/core.c:63",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_pm_move_to_tail"
      ],
      "caller_func": [
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_get_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:dpm_wait_for_subordinate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498961280,
      "name": "device_links_read_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int device_links_read_lock()
```

```json
{
  "name": "device_links_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231533456,
      "name": "device_links_read_lock",
      "external": true,
      "loc": "drivers/base/core.c:63",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_pm_move_to_tail"
      ],
      "caller_func": [
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_get_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:dpm_wait_for_subordinate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231531536,
      "name": "device_links_read_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int device_links_read_lock()
```

```json
{
  "name": "device_links_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292108792,
      "name": "device_links_read_lock",
      "external": true,
      "loc": "drivers/base/core.c:63",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_pm_move_to_tail"
      ],
      "caller_func": [
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_get_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:dpm_wait_for_subordinate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292106080,
      "name": "device_links_read_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int device_links_read_lock()
```

```json
{
  "name": "device_links_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276344314,
      "name": "device_links_read_lock",
      "external": true,
      "loc": "drivers/base/core.c:63",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_pm_move_to_tail"
      ],
      "caller_func": [
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_get_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/runtime.c:__rpm_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276342582,
      "name": "device_links_read_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int device_links_read_lock()
```

```json
{
  "name": "device_links_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585927717,
      "name": "device_links_read_lock",
      "external": true,
      "loc": "drivers/base/core.c:63",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_pm_move_to_tail"
      ],
      "caller_func": [
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_get_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:dpm_wait_for_subordinate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585926144,
      "name": "device_links_read_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int device_links_read_lock()
```

```json
{
  "name": "device_links_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585776853,
      "name": "device_links_read_lock",
      "external": true,
      "loc": "drivers/base/core.c:63",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_pm_move_to_tail"
      ],
      "caller_func": [
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_get_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:dpm_wait_for_subordinate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585775280,
      "name": "device_links_read_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int device_links_read_lock()
```

```json
{
  "name": "device_links_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586117365,
      "name": "device_links_read_lock",
      "external": true,
      "loc": "drivers/base/core.c:63",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_pm_move_to_tail"
      ],
      "caller_func": [
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_get_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:dpm_wait_for_subordinate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586115792,
      "name": "device_links_read_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int device_links_read_lock()
```

```json
{
  "name": "device_links_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586225973,
      "name": "device_links_read_lock",
      "external": true,
      "loc": "drivers/base/core.c:63",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_pm_move_to_tail"
      ],
      "caller_func": [
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_get_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:dpm_wait_for_subordinate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586224400,
      "name": "device_links_read_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int device_links_read_lock()
```
</details>
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
