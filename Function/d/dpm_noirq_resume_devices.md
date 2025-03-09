# Function: <code>dpm_noirq_resume_devices</code>

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
void dpm_noirq_resume_devices(pm_message_t state)
```

```json
{
  "name": "dpm_noirq_resume_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585491952,
      "name": "dpm_noirq_resume_devices",
      "external": true,
      "loc": "drivers/base/power/main.c:640",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "drivers/base/power/main.c:dpm_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585491952,
      "name": "dpm_noirq_resume_devices",
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
void dpm_noirq_resume_devices(pm_message_t state)
```

```json
{
  "name": "dpm_noirq_resume_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585736624,
      "name": "dpm_noirq_resume_devices",
      "external": true,
      "loc": "drivers/base/power/main.c:711",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "drivers/base/power/main.c:dpm_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585736624,
      "name": "dpm_noirq_resume_devices",
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
void dpm_noirq_resume_devices(pm_message_t state)
```

```json
{
  "name": "dpm_noirq_resume_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585869344,
      "name": "dpm_noirq_resume_devices",
      "external": true,
      "loc": "drivers/base/power/main.c:712",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "drivers/base/power/main.c:dpm_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585869344,
      "name": "dpm_noirq_resume_devices",
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
void dpm_noirq_resume_devices(pm_message_t state)
```

```json
{
  "name": "dpm_noirq_resume_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586106432,
      "name": "dpm_noirq_resume_devices",
      "external": true,
      "loc": "drivers/base/power/main.c:719",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "drivers/base/power/main.c:dpm_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586106432,
      "name": "dpm_noirq_resume_devices",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dpm_noirq_resume_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586254005,
      "name": "dpm_noirq_resume_devices",
      "external": false,
      "loc": "drivers/base/power/main.c:748",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void dpm_noirq_resume_devices(pm_message_t state)
```

```json
{
  "name": "dpm_noirq_resume_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587022208,
      "name": "dpm_noirq_resume_devices",
      "external": false,
      "loc": "drivers/base/power/main.c:696",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend_end",
        "drivers/base/power/main.c:dpm_resume_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587022208,
      "name": "dpm_noirq_resume_devices",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void dpm_noirq_resume_devices(pm_message_t state)
```

```json
{
  "name": "dpm_noirq_resume_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587106768,
      "name": "dpm_noirq_resume_devices",
      "external": false,
      "loc": "drivers/base/power/main.c:695",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend_end",
        "drivers/base/power/main.c:dpm_resume_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587106768,
      "name": "dpm_noirq_resume_devices",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void dpm_noirq_resume_devices(pm_message_t state)
```

```json
{
  "name": "dpm_noirq_resume_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586991200,
      "name": "dpm_noirq_resume_devices",
      "external": false,
      "loc": "drivers/base/power/main.c:696",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend_end",
        "drivers/base/power/main.c:dpm_resume_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586991200,
      "name": "dpm_noirq_resume_devices",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void dpm_noirq_resume_devices(pm_message_t state)
```

```json
{
  "name": "dpm_noirq_resume_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpm_noirq_resume_devices",
      "external": false,
      "loc": "drivers/base/power/main.c:693",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend_end",
        "drivers/base/power/main.c:dpm_resume_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587557440,
      "name": "dpm_noirq_resume_devices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 638
    },
    {
      "addr": 18446744071592491942,
      "name": "dpm_noirq_resume_devices.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void dpm_noirq_resume_devices(pm_message_t state)
```

```json
{
  "name": "dpm_noirq_resume_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpm_noirq_resume_devices",
      "external": false,
      "loc": "drivers/base/power/main.c:692",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend_end",
        "drivers/base/power/main.c:dpm_resume_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588892656,
      "name": "dpm_noirq_resume_devices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 673
    },
    {
      "addr": 18446744071594362083,
      "name": "dpm_noirq_resume_devices.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void dpm_noirq_resume_devices(pm_message_t state)
```

```json
{
  "name": "dpm_noirq_resume_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590401968,
      "name": "dpm_noirq_resume_devices",
      "external": false,
      "loc": "drivers/base/power/main.c:692",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend_end",
        "drivers/base/power/main.c:dpm_resume_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590401968,
      "name": "dpm_noirq_resume_devices",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void dpm_noirq_resume_devices(pm_message_t state)
```

```json
{
  "name": "dpm_noirq_resume_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590721472,
      "name": "dpm_noirq_resume_devices",
      "external": false,
      "loc": "drivers/base/power/main.c:692",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend_end",
        "drivers/base/power/main.c:dpm_resume_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590721472,
      "name": "dpm_noirq_resume_devices",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void dpm_noirq_resume_devices(pm_message_t state)
```

```json
{
  "name": "dpm_noirq_resume_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591084000,
      "name": "dpm_noirq_resume_devices",
      "external": false,
      "loc": "drivers/base/power/main.c:704",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend_end",
        "drivers/base/power/main.c:dpm_resume_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591084000,
      "name": "dpm_noirq_resume_devices",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "dpm_noirq_resume_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499074308,
      "name": "dpm_noirq_resume_devices",
      "external": false,
      "loc": "drivers/base/power/main.c:748",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "dpm_noirq_resume_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231627012,
      "name": "dpm_noirq_resume_devices",
      "external": false,
      "loc": "drivers/base/power/main.c:748",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "dpm_noirq_resume_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292252764,
      "name": "dpm_noirq_resume_devices",
      "external": false,
      "loc": "drivers/base/power/main.c:748",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "dpm_noirq_resume_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586017333,
      "name": "dpm_noirq_resume_devices",
      "external": false,
      "loc": "drivers/base/power/main.c:748",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "dpm_noirq_resume_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585863317,
      "name": "dpm_noirq_resume_devices",
      "external": false,
      "loc": "drivers/base/power/main.c:748",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "dpm_noirq_resume_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586204021,
      "name": "dpm_noirq_resume_devices",
      "external": false,
      "loc": "drivers/base/power/main.c:748",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "dpm_noirq_resume_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586312677,
      "name": "dpm_noirq_resume_devices",
      "external": false,
      "loc": "drivers/base/power/main.c:748",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void dpm_noirq_resume_devices(pm_message_t state)
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
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
void dpm_noirq_resume_devices(pm_message_t state)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void dpm_noirq_resume_devices(pm_message_t state)
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
