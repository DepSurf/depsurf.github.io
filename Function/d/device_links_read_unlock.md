# Function: <code>device_links_read_unlock</code>

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
void device_links_read_unlock(int idx)
```

```json
{
  "name": "device_links_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584905344,
      "name": "device_links_read_unlock",
      "external": true,
      "loc": "drivers/base/core.c:68",
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
      "addr": 18446744071584905344,
      "name": "device_links_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void device_links_read_unlock(int idx)
```

```json
{
  "name": "device_links_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584990576,
      "name": "device_links_read_unlock",
      "external": true,
      "loc": "drivers/base/core.c:69",
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
      "addr": 18446744071584990576,
      "name": "device_links_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void device_links_read_unlock(int idx)
```

```json
{
  "name": "device_links_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585412528,
      "name": "device_links_read_unlock",
      "external": true,
      "loc": "drivers/base/core.c:69",
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
      "addr": 18446744071585412528,
      "name": "device_links_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void device_links_read_unlock(int idx)
```

```json
{
  "name": "device_links_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585656513,
      "name": "device_links_read_unlock",
      "external": true,
      "loc": "drivers/base/core.c:66",
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
      "addr": 18446744071585655136,
      "name": "device_links_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void device_links_read_unlock(int idx)
```

```json
{
  "name": "device_links_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585788673,
      "name": "device_links_read_unlock",
      "external": true,
      "loc": "drivers/base/core.c:67",
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
      "addr": 18446744071585787264,
      "name": "device_links_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void device_links_read_unlock(int idx)
```

```json
{
  "name": "device_links_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586019651,
      "name": "device_links_read_unlock",
      "external": true,
      "loc": "drivers/base/core.c:67",
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
      "addr": 18446744071586018096,
      "name": "device_links_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void device_links_read_unlock(int idx)
```

```json
{
  "name": "device_links_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586167395,
      "name": "device_links_read_unlock",
      "external": true,
      "loc": "drivers/base/core.c:68",
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
      "addr": 18446744071586165808,
      "name": "device_links_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void device_links_read_unlock(int idx)
```

```json
{
  "name": "device_links_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586927235,
      "name": "device_links_read_unlock",
      "external": true,
      "loc": "drivers/base/core.c:76",
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
      "addr": 18446744071586924352,
      "name": "device_links_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void device_links_read_unlock(int idx)
```

```json
{
  "name": "device_links_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587010931,
      "name": "device_links_read_unlock",
      "external": true,
      "loc": "drivers/base/core.c:170",
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
      "addr": 18446744071587008080,
      "name": "device_links_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void device_links_read_unlock(int idx)
```

```json
{
  "name": "device_links_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586894179,
      "name": "device_links_read_unlock",
      "external": true,
      "loc": "drivers/base/core.c:188",
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
      "addr": 18446744071586890848,
      "name": "device_links_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void device_links_read_unlock(int idx)
```

```json
{
  "name": "device_links_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587456083,
      "name": "device_links_read_unlock",
      "external": true,
      "loc": "drivers/base/core.c:200",
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
      "addr": 18446744071587452608,
      "name": "device_links_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void device_links_read_unlock(int idx)
```

```json
{
  "name": "device_links_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588774993,
      "name": "device_links_read_unlock",
      "external": true,
      "loc": "drivers/base/core.c:201",
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
      "addr": 18446744071588771280,
      "name": "device_links_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void device_links_read_unlock(int idx)
```

```json
{
  "name": "device_links_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590268097,
      "name": "device_links_read_unlock",
      "external": true,
      "loc": "drivers/base/core.c:269",
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
      "addr": 18446744071590264624,
      "name": "device_links_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void device_links_read_unlock(int idx)
```

```json
{
  "name": "device_links_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590588497,
      "name": "device_links_read_unlock",
      "external": true,
      "loc": "drivers/base/core.c:255",
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
      "addr": 18446744071590584864,
      "name": "device_links_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void device_links_read_unlock(int idx)
```

```json
{
  "name": "device_links_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590947169,
      "name": "device_links_read_unlock",
      "external": true,
      "loc": "drivers/base/core.c:256",
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
      "addr": 18446744071590943840,
      "name": "device_links_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void device_links_read_unlock(int idx)
```

```json
{
  "name": "device_links_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498963332,
      "name": "device_links_read_unlock",
      "external": true,
      "loc": "drivers/base/core.c:68",
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
      "addr": 18446603336498961320,
      "name": "device_links_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void device_links_read_unlock(int idx)
```

```json
{
  "name": "device_links_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231533496,
      "name": "device_links_read_unlock",
      "external": true,
      "loc": "drivers/base/core.c:68",
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
      "addr": 3231531572,
      "name": "device_links_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void device_links_read_unlock(int idx)
```

```json
{
  "name": "device_links_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292108848,
      "name": "device_links_read_unlock",
      "external": true,
      "loc": "drivers/base/core.c:68",
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
      "addr": 13835058055292106144,
      "name": "device_links_read_unlock",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void device_links_read_unlock(int idx)
```

```json
{
  "name": "device_links_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276344344,
      "name": "device_links_read_unlock",
      "external": true,
      "loc": "drivers/base/core.c:68",
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
      "addr": 18446743936276342624,
      "name": "device_links_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void device_links_read_unlock(int idx)
```

```json
{
  "name": "device_links_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585927763,
      "name": "device_links_read_unlock",
      "external": true,
      "loc": "drivers/base/core.c:68",
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
      "addr": 18446744071585926176,
      "name": "device_links_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void device_links_read_unlock(int idx)
```

```json
{
  "name": "device_links_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585776899,
      "name": "device_links_read_unlock",
      "external": true,
      "loc": "drivers/base/core.c:68",
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
      "addr": 18446744071585775312,
      "name": "device_links_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void device_links_read_unlock(int idx)
```

```json
{
  "name": "device_links_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586117411,
      "name": "device_links_read_unlock",
      "external": true,
      "loc": "drivers/base/core.c:68",
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
      "addr": 18446744071586115824,
      "name": "device_links_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void device_links_read_unlock(int idx)
```

```json
{
  "name": "device_links_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586226019,
      "name": "device_links_read_unlock",
      "external": true,
      "loc": "drivers/base/core.c:68",
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
      "addr": 18446744071586224432,
      "name": "device_links_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void device_links_read_unlock(int idx)
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
