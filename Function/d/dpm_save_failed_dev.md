# Function: <code>dpm_save_failed_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dpm_save_failed_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584453279,
      "name": "dpm_save_failed_dev",
      "external": false,
      "loc": "include/linux/suspend.h:76",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend"
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
  "name": "dpm_save_failed_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584797308,
      "name": "dpm_save_failed_dev",
      "external": false,
      "loc": "include/linux/suspend.h:75",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq"
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
  "name": "dpm_save_failed_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584989247,
      "name": "dpm_save_failed_dev",
      "external": false,
      "loc": "include/linux/suspend.h:75",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq"
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
  "name": "dpm_save_failed_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585074111,
      "name": "dpm_save_failed_dev",
      "external": false,
      "loc": "include/linux/suspend.h:75",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq"
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
  "name": "dpm_save_failed_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585497359,
      "name": "dpm_save_failed_dev",
      "external": false,
      "loc": "include/linux/suspend.h:76",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices"
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
void dpm_save_failed_dev(const char * name)
```

```json
{
  "name": "dpm_save_failed_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585735747,
      "name": "dpm_save_failed_dev",
      "external": false,
      "loc": "include/linux/suspend.h:76",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices"
      ],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585730192,
      "name": "dpm_save_failed_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void dpm_save_failed_dev(const char * name)
```

```json
{
  "name": "dpm_save_failed_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585868179,
      "name": "dpm_save_failed_dev",
      "external": false,
      "loc": "include/linux/suspend.h:76",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices"
      ],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585862896,
      "name": "dpm_save_failed_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
  "name": "dpm_save_failed_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586111534,
      "name": "dpm_save_failed_dev",
      "external": false,
      "loc": "include/linux/suspend.h:76",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dpm_save_failed_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586258958,
      "name": "dpm_save_failed_dev",
      "external": false,
      "loc": "include/linux/suspend.h:76",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dpm_save_failed_dev(const char * name)
```

```json
{
  "name": "dpm_save_failed_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587021973,
      "name": "dpm_save_failed_dev",
      "external": false,
      "loc": "include/linux/suspend.h:76",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices"
      ],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587014848,
      "name": "dpm_save_failed_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void dpm_save_failed_dev(const char * name)
```

```json
{
  "name": "dpm_save_failed_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587106677,
      "name": "dpm_save_failed_dev",
      "external": false,
      "loc": "include/linux/suspend.h:76",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices"
      ],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587099504,
      "name": "dpm_save_failed_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void dpm_save_failed_dev(const char * name)
```

```json
{
  "name": "dpm_save_failed_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586992933,
      "name": "dpm_save_failed_dev",
      "external": false,
      "loc": "include/linux/suspend.h:76",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices"
      ],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586985824,
      "name": "dpm_save_failed_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void dpm_save_failed_dev(const char * name)
```

```json
{
  "name": "dpm_save_failed_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587559176,
      "name": "dpm_save_failed_dev",
      "external": false,
      "loc": "include/linux/suspend.h:76",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices"
      ],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587551952,
      "name": "dpm_save_failed_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
void dpm_save_failed_dev(const char * name)
```

```json
{
  "name": "dpm_save_failed_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588892374,
      "name": "dpm_save_failed_dev",
      "external": false,
      "loc": "include/linux/suspend.h:76",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices"
      ],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588885072,
      "name": "dpm_save_failed_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void dpm_save_failed_dev(const char * name)
```

```json
{
  "name": "dpm_save_failed_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590393648,
      "name": "dpm_save_failed_dev",
      "external": false,
      "loc": "include/linux/suspend.h:76",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590393648,
      "name": "dpm_save_failed_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void dpm_save_failed_dev(const char * name)
```

```json
{
  "name": "dpm_save_failed_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590713120,
      "name": "dpm_save_failed_dev",
      "external": false,
      "loc": "include/linux/suspend.h:79",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590713120,
      "name": "dpm_save_failed_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
void dpm_save_failed_dev(const char * name)
```

```json
{
  "name": "dpm_save_failed_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591075232,
      "name": "dpm_save_failed_dev",
      "external": false,
      "loc": "include/linux/suspend.h:79",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591075232,
      "name": "dpm_save_failed_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
void dpm_save_failed_dev(const char * name)
```

```json
{
  "name": "dpm_save_failed_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499073072,
      "name": "dpm_save_failed_dev",
      "external": false,
      "loc": "include/linux/suspend.h:76",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq"
      ],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499066840,
      "name": "dpm_save_failed_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void dpm_save_failed_dev(const char * name)
```

```json
{
  "name": "dpm_save_failed_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231626132,
      "name": "dpm_save_failed_dev",
      "external": false,
      "loc": "include/linux/suspend.h:76",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq"
      ],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231620208,
      "name": "dpm_save_failed_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
  "name": "dpm_save_failed_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292259960,
      "name": "dpm_save_failed_dev",
      "external": false,
      "loc": "include/linux/suspend.h:76",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq"
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
  "name": "dpm_save_failed_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586022286,
      "name": "dpm_save_failed_dev",
      "external": false,
      "loc": "include/linux/suspend.h:76",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dpm_save_failed_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585868270,
      "name": "dpm_save_failed_dev",
      "external": false,
      "loc": "include/linux/suspend.h:76",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dpm_save_failed_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586208974,
      "name": "dpm_save_failed_dev",
      "external": false,
      "loc": "include/linux/suspend.h:76",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dpm_save_failed_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586317945,
      "name": "dpm_save_failed_dev",
      "external": false,
      "loc": "include/linux/suspend.h:76",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void dpm_save_failed_dev(const char * name)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void dpm_save_failed_dev(const char * name)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void dpm_save_failed_dev(const char * name)
```
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void dpm_save_failed_dev(const char * name)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void dpm_save_failed_dev(const char * name)
```
</details>
</li>
</ul>
