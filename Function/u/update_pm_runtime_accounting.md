# Function: <code>update_pm_runtime_accounting</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void update_pm_runtime_accounting(struct device * dev)
```

```json
{
  "name": "update_pm_runtime_accounting",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584442680,
      "name": "update_pm_runtime_accounting",
      "external": true,
      "loc": "drivers/base/power/runtime.c:63",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:__pm_runtime_set_status"
      ],
      "caller_func": [
        "drivers/base/power/sysfs.c:rtpm_active_time_show",
        "drivers/base/power/sysfs.c:rtpm_suspended_time_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584447920,
      "name": "update_pm_runtime_accounting",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void update_pm_runtime_accounting(struct device * dev)
```

```json
{
  "name": "update_pm_runtime_accounting",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584781937,
      "name": "update_pm_runtime_accounting",
      "external": true,
      "loc": "drivers/base/power/runtime.c:63",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend"
      ],
      "caller_func": [
        "drivers/base/power/sysfs.c:rtpm_suspended_time_show",
        "drivers/base/power/sysfs.c:rtpm_active_time_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584783968,
      "name": "update_pm_runtime_accounting",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void update_pm_runtime_accounting(struct device * dev)
```

```json
{
  "name": "update_pm_runtime_accounting",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584973633,
      "name": "update_pm_runtime_accounting",
      "external": true,
      "loc": "drivers/base/power/runtime.c:65",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend"
      ],
      "caller_func": [
        "drivers/base/power/sysfs.c:rtpm_suspended_time_show",
        "drivers/base/power/sysfs.c:rtpm_active_time_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584974960,
      "name": "update_pm_runtime_accounting",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void update_pm_runtime_accounting(struct device * dev)
```

```json
{
  "name": "update_pm_runtime_accounting",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585057184,
      "name": "update_pm_runtime_accounting",
      "external": true,
      "loc": "drivers/base/power/runtime.c:65",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend"
      ],
      "caller_func": [
        "drivers/base/power/sysfs.c:rtpm_suspended_time_show",
        "drivers/base/power/sysfs.c:rtpm_active_time_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585059712,
      "name": "update_pm_runtime_accounting",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void update_pm_runtime_accounting(struct device * dev)
```

```json
{
  "name": "update_pm_runtime_accounting",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585480030,
      "name": "update_pm_runtime_accounting",
      "external": true,
      "loc": "drivers/base/power/runtime.c:65",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend"
      ],
      "caller_func": [
        "drivers/base/power/sysfs.c:rtpm_suspended_time_show",
        "drivers/base/power/sysfs.c:rtpm_active_time_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585482544,
      "name": "update_pm_runtime_accounting",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void update_pm_runtime_accounting(struct device * dev)
```

```json
{
  "name": "update_pm_runtime_accounting",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585721741,
      "name": "update_pm_runtime_accounting",
      "external": true,
      "loc": "drivers/base/power/runtime.c:65",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend"
      ],
      "caller_func": [
        "drivers/base/power/sysfs.c:runtime_suspended_time_show",
        "drivers/base/power/sysfs.c:runtime_active_time_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585726480,
      "name": "update_pm_runtime_accounting",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void update_pm_runtime_accounting(struct device * dev)
```

```json
{
  "name": "update_pm_runtime_accounting",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585853629,
      "name": "update_pm_runtime_accounting",
      "external": true,
      "loc": "drivers/base/power/runtime.c:67",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume"
      ],
      "caller_func": [
        "drivers/base/power/sysfs.c:runtime_suspended_time_show",
        "drivers/base/power/sysfs.c:runtime_active_time_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585859184,
      "name": "update_pm_runtime_accounting",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_pm_runtime_accounting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586093662,
      "name": "update_pm_runtime_accounting",
      "external": false,
      "loc": "drivers/base/power/runtime.c:65",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time"
      ],
      "caller_func": [
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586086896,
      "name": "update_pm_runtime_accounting.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_pm_runtime_accounting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586241214,
      "name": "update_pm_runtime_accounting",
      "external": false,
      "loc": "drivers/base/power/runtime.c:65",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time"
      ],
      "caller_func": [
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586234448,
      "name": "update_pm_runtime_accounting.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_pm_runtime_accounting",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587010542,
      "name": "update_pm_runtime_accounting",
      "external": false,
      "loc": "drivers/base/power/runtime.c:65",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_pm_runtime_accounting",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587095278,
      "name": "update_pm_runtime_accounting",
      "external": false,
      "loc": "drivers/base/power/runtime.c:65",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_pm_runtime_accounting",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586981633,
      "name": "update_pm_runtime_accounting",
      "external": false,
      "loc": "drivers/base/power/runtime.c:65",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_pm_runtime_accounting",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587545793,
      "name": "update_pm_runtime_accounting",
      "external": false,
      "loc": "drivers/base/power/runtime.c:65",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_pm_runtime_accounting",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588879509,
      "name": "update_pm_runtime_accounting",
      "external": false,
      "loc": "drivers/base/power/runtime.c:65",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_pm_runtime_accounting",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590387973,
      "name": "update_pm_runtime_accounting",
      "external": false,
      "loc": "drivers/base/power/runtime.c:65",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_pm_runtime_accounting",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590707701,
      "name": "update_pm_runtime_accounting",
      "external": false,
      "loc": "drivers/base/power/runtime.c:65",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_pm_runtime_accounting",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591069557,
      "name": "update_pm_runtime_accounting",
      "external": false,
      "loc": "drivers/base/power/runtime.c:66",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "update_pm_runtime_accounting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499056872,
      "name": "update_pm_runtime_accounting",
      "external": false,
      "loc": "drivers/base/power/runtime.c:65",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time"
      ],
      "caller_func": [
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499047776,
      "name": "update_pm_runtime_accounting.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "update_pm_runtime_accounting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231614852,
      "name": "update_pm_runtime_accounting",
      "external": false,
      "loc": "drivers/base/power/runtime.c:65",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time"
      ],
      "caller_func": [
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231605964,
      "name": "update_pm_runtime_accounting.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "update_pm_runtime_accounting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292229980,
      "name": "update_pm_runtime_accounting",
      "external": false,
      "loc": "drivers/base/power/runtime.c:65",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time"
      ],
      "caller_func": [
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292221792,
      "name": "update_pm_runtime_accounting.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "update_pm_runtime_accounting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276414280,
      "name": "update_pm_runtime_accounting",
      "external": false,
      "loc": "drivers/base/power/runtime.c:65",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time"
      ],
      "caller_func": [
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276407142,
      "name": "update_pm_runtime_accounting.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_pm_runtime_accounting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586001422,
      "name": "update_pm_runtime_accounting",
      "external": false,
      "loc": "drivers/base/power/runtime.c:65",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time"
      ],
      "caller_func": [
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585994656,
      "name": "update_pm_runtime_accounting.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_pm_runtime_accounting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585850622,
      "name": "update_pm_runtime_accounting",
      "external": false,
      "loc": "drivers/base/power/runtime.c:65",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time"
      ],
      "caller_func": [
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585843904,
      "name": "update_pm_runtime_accounting.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_pm_runtime_accounting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586191230,
      "name": "update_pm_runtime_accounting",
      "external": false,
      "loc": "drivers/base/power/runtime.c:65",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time"
      ],
      "caller_func": [
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586184464,
      "name": "update_pm_runtime_accounting.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_pm_runtime_accounting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586301246,
      "name": "update_pm_runtime_accounting",
      "external": false,
      "loc": "drivers/base/power/runtime.c:65",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time"
      ],
      "caller_func": [
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586293744,
      "name": "update_pm_runtime_accounting.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void update_pm_runtime_accounting(struct device * dev)
```
</details>
</li>
</ul>
