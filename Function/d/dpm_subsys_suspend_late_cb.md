# Function: <code>dpm_subsys_suspend_late_cb</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
pm_callback_t dpm_subsys_suspend_late_cb(struct device * dev, pm_message_t state, const char * * info_p)
```

```json
{
  "name": "dpm_subsys_suspend_late_cb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585729520,
      "name": "dpm_subsys_suspend_late_cb",
      "external": false,
      "loc": "drivers/base/power/main.c:1462",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585729520,
      "name": "dpm_subsys_suspend_late_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
pm_callback_t dpm_subsys_suspend_late_cb(struct device * dev, pm_message_t state, const char * * info_p)
```

```json
{
  "name": "dpm_subsys_suspend_late_cb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585862224,
      "name": "dpm_subsys_suspend_late_cb",
      "external": false,
      "loc": "drivers/base/power/main.c:1464",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585862224,
      "name": "dpm_subsys_suspend_late_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
pm_callback_t dpm_subsys_suspend_late_cb(struct device * dev, pm_message_t state, const char * * info_p)
```

```json
{
  "name": "dpm_subsys_suspend_late_cb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586099120,
      "name": "dpm_subsys_suspend_late_cb",
      "external": false,
      "loc": "drivers/base/power/main.c:1452",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586099120,
      "name": "dpm_subsys_suspend_late_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
pm_callback_t dpm_subsys_suspend_late_cb(struct device * dev, pm_message_t state, const char * * info_p)
```

```json
{
  "name": "dpm_subsys_suspend_late_cb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586246640,
      "name": "dpm_subsys_suspend_late_cb",
      "external": false,
      "loc": "drivers/base/power/main.c:1473",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586246640,
      "name": "dpm_subsys_suspend_late_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
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
pm_callback_t dpm_subsys_suspend_late_cb(struct device * dev, pm_message_t state, const char * * info_p)
```

```json
{
  "name": "dpm_subsys_suspend_late_cb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499065976,
      "name": "dpm_subsys_suspend_late_cb",
      "external": false,
      "loc": "drivers/base/power/main.c:1473",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499065976,
      "name": "dpm_subsys_suspend_late_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
pm_callback_t dpm_subsys_suspend_late_cb(struct device * dev, pm_message_t state, const char * * info_p)
```

```json
{
  "name": "dpm_subsys_suspend_late_cb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231619516,
      "name": "dpm_subsys_suspend_late_cb",
      "external": false,
      "loc": "drivers/base/power/main.c:1473",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231619516,
      "name": "dpm_subsys_suspend_late_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
pm_callback_t dpm_subsys_suspend_late_cb(struct device * dev, pm_message_t state, const char * * info_p)
```

```json
{
  "name": "dpm_subsys_suspend_late_cb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292241488,
      "name": "dpm_subsys_suspend_late_cb",
      "external": false,
      "loc": "drivers/base/power/main.c:1473",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292241488,
      "name": "dpm_subsys_suspend_late_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
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
pm_callback_t dpm_subsys_suspend_late_cb(struct device * dev, pm_message_t state, const char * * info_p)
```

```json
{
  "name": "dpm_subsys_suspend_late_cb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586007936,
      "name": "dpm_subsys_suspend_late_cb",
      "external": false,
      "loc": "drivers/base/power/main.c:1473",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586007936,
      "name": "dpm_subsys_suspend_late_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 597
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
pm_callback_t dpm_subsys_suspend_late_cb(struct device * dev, pm_message_t state, const char * * info_p)
```

```json
{
  "name": "dpm_subsys_suspend_late_cb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585855968,
      "name": "dpm_subsys_suspend_late_cb",
      "external": false,
      "loc": "drivers/base/power/main.c:1473",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585855968,
      "name": "dpm_subsys_suspend_late_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
pm_callback_t dpm_subsys_suspend_late_cb(struct device * dev, pm_message_t state, const char * * info_p)
```

```json
{
  "name": "dpm_subsys_suspend_late_cb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586196656,
      "name": "dpm_subsys_suspend_late_cb",
      "external": false,
      "loc": "drivers/base/power/main.c:1473",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586196656,
      "name": "dpm_subsys_suspend_late_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
pm_callback_t dpm_subsys_suspend_late_cb(struct device * dev, pm_message_t state, const char * * info_p)
```

```json
{
  "name": "dpm_subsys_suspend_late_cb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586305328,
      "name": "dpm_subsys_suspend_late_cb",
      "external": false,
      "loc": "drivers/base/power/main.c:1473",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586305328,
      "name": "dpm_subsys_suspend_late_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
pm_callback_t dpm_subsys_suspend_late_cb(struct device * dev, pm_message_t state, const char * * info_p)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
pm_callback_t dpm_subsys_suspend_late_cb(struct device * dev, pm_message_t state, const char * * info_p)
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
pm_callback_t dpm_subsys_suspend_late_cb(struct device * dev, pm_message_t state, const char * * info_p)
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
