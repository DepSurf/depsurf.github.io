# Function: <code>pm_dev_err</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void pm_dev_err(struct device * dev, pm_message_t state, char * info, int error)
```

```json
{
  "name": "pm_dev_err",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584450080,
      "name": "pm_dev_err",
      "external": false,
      "loc": "drivers/base/power/main.c:352",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:async_resume_noirq",
        "drivers/base/power/main.c:async_resume_early",
        "drivers/base/power/main.c:async_resume",
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584450080,
      "name": "pm_dev_err",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
void pm_dev_err(struct device * dev, pm_message_t state, char * info, int error)
```

```json
{
  "name": "pm_dev_err",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584786208,
      "name": "pm_dev_err",
      "external": false,
      "loc": "drivers/base/power/main.c:354",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:async_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:async_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:async_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584786208,
      "name": "pm_dev_err",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
void pm_dev_err(struct device * dev, pm_message_t state, char * info, int error)
```

```json
{
  "name": "pm_dev_err",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584978000,
      "name": "pm_dev_err",
      "external": false,
      "loc": "drivers/base/power/main.c:412",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:async_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:async_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:async_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584978000,
      "name": "pm_dev_err",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
void pm_dev_err(struct device * dev, pm_message_t state, const char * info, int error)
```

```json
{
  "name": "pm_dev_err",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585062672,
      "name": "pm_dev_err",
      "external": false,
      "loc": "drivers/base/power/main.c:414",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:async_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:async_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:async_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585062672,
      "name": "pm_dev_err",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
void pm_dev_err(struct device * dev, pm_message_t state, const char * info, int error)
```

```json
{
  "name": "pm_dev_err",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585485504,
      "name": "pm_dev_err",
      "external": false,
      "loc": "drivers/base/power/main.c:414",
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
        "drivers/base/power/main.c:async_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:async_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:async_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585485504,
      "name": "pm_dev_err",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
void pm_dev_err(struct device * dev, pm_message_t state, const char * info, int error)
```

```json
{
  "name": "pm_dev_err",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585743776,
      "name": "pm_dev_err",
      "external": false,
      "loc": "drivers/base/power/main.c:410",
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
        "drivers/base/power/main.c:async_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:async_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:async_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585743776,
      "name": "pm_dev_err",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
void pm_dev_err(struct device * dev, pm_message_t state, const char * info, int error)
```

```json
{
  "name": "pm_dev_err",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585876512,
      "name": "pm_dev_err",
      "external": false,
      "loc": "drivers/base/power/main.c:411",
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
        "drivers/base/power/main.c:async_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:async_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:async_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585876512,
      "name": "pm_dev_err",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
void pm_dev_err(struct device * dev, pm_message_t state, const char * info, int error)
```

```json
{
  "name": "pm_dev_err",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pm_dev_err",
      "external": false,
      "loc": "drivers/base/power/main.c:418",
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
        "drivers/base/power/main.c:async_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:async_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:async_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586099792,
      "name": "pm_dev_err",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071586113760,
      "name": "pm_dev_err.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void pm_dev_err(struct device * dev, pm_message_t state, const char * info, int error)
```

```json
{
  "name": "pm_dev_err",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pm_dev_err",
      "external": false,
      "loc": "drivers/base/power/main.c:446",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:async_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:async_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:async_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586247184,
      "name": "pm_dev_err",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071586261184,
      "name": "pm_dev_err.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void pm_dev_err(struct device * dev, pm_message_t state, const char * info, int error)
```

```json
{
  "name": "pm_dev_err",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587029216,
      "name": "pm_dev_err",
      "external": false,
      "loc": "drivers/base/power/main.c:450",
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
        "drivers/base/power/main.c:async_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:async_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:async_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587029216,
      "name": "pm_dev_err",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void pm_dev_err(struct device * dev, pm_message_t state, const char * info, int error)
```

```json
{
  "name": "pm_dev_err",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591488692,
      "name": "pm_dev_err",
      "external": false,
      "loc": "drivers/base/power/main.c:449",
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
        "drivers/base/power/main.c:async_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:async_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:async_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591488692,
      "name": "pm_dev_err",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void pm_dev_err(struct device * dev, pm_message_t state, const char * info, int error)
```

```json
{
  "name": "pm_dev_err",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591431734,
      "name": "pm_dev_err",
      "external": false,
      "loc": "drivers/base/power/main.c:450",
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
        "drivers/base/power/main.c:async_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:async_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:async_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591431734,
      "name": "pm_dev_err",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void pm_dev_err(struct device * dev, pm_message_t state, const char * info, int error)
```

```json
{
  "name": "pm_dev_err",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592491248,
      "name": "pm_dev_err",
      "external": false,
      "loc": "drivers/base/power/main.c:447",
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
        "drivers/base/power/main.c:async_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:async_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:async_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592491248,
      "name": "pm_dev_err",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void pm_dev_err(struct device * dev, pm_message_t state, const char * info, int error)
```

```json
{
  "name": "pm_dev_err",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594361025,
      "name": "pm_dev_err",
      "external": false,
      "loc": "drivers/base/power/main.c:446",
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
        "drivers/base/power/main.c:async_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:async_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:async_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594361025,
      "name": "pm_dev_err",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pm_dev_err",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590408808,
      "name": "pm_dev_err",
      "external": false,
      "loc": "drivers/base/power/main.c:446",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:async_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:async_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:async_resume_noirq"
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
  "name": "pm_dev_err",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590728376,
      "name": "pm_dev_err",
      "external": false,
      "loc": "drivers/base/power/main.c:446",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:async_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:async_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:async_resume_noirq"
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
  "name": "pm_dev_err",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591090296,
      "name": "pm_dev_err",
      "external": false,
      "loc": "drivers/base/power/main.c:446",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void pm_dev_err(struct device * dev, pm_message_t state, const char * info, int error)
```

```json
{
  "name": "pm_dev_err",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499082604,
      "name": "pm_dev_err",
      "external": false,
      "loc": "drivers/base/power/main.c:446",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:async_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:async_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:async_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499082604,
      "name": "pm_dev_err",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void pm_dev_err(struct device * dev, pm_message_t state, const char * info, int error)
```

```json
{
  "name": "pm_dev_err",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231635588,
      "name": "pm_dev_err",
      "external": false,
      "loc": "drivers/base/power/main.c:446",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:async_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:async_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:async_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231635588,
      "name": "pm_dev_err",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void pm_dev_err(struct device * dev, pm_message_t state, const char * info, int error)
```

```json
{
  "name": "pm_dev_err",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292242544,
      "name": "pm_dev_err",
      "external": false,
      "loc": "drivers/base/power/main.c:446",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:async_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:async_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:async_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292242544,
      "name": "pm_dev_err",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void pm_dev_err(struct device * dev, pm_message_t state, const char * info, int error)
```

```json
{
  "name": "pm_dev_err",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pm_dev_err",
      "external": false,
      "loc": "drivers/base/power/main.c:446",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:async_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:async_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:async_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586008912,
      "name": "pm_dev_err",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071586024512,
      "name": "pm_dev_err.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void pm_dev_err(struct device * dev, pm_message_t state, const char * info, int error)
```

```json
{
  "name": "pm_dev_err",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pm_dev_err",
      "external": false,
      "loc": "drivers/base/power/main.c:446",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:async_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:async_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:async_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585856512,
      "name": "pm_dev_err",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071585870464,
      "name": "pm_dev_err.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void pm_dev_err(struct device * dev, pm_message_t state, const char * info, int error)
```

```json
{
  "name": "pm_dev_err",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pm_dev_err",
      "external": false,
      "loc": "drivers/base/power/main.c:446",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:async_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:async_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:async_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586197200,
      "name": "pm_dev_err",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071586211200,
      "name": "pm_dev_err.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void pm_dev_err(struct device * dev, pm_message_t state, const char * info, int error)
```

```json
{
  "name": "pm_dev_err",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pm_dev_err",
      "external": false,
      "loc": "drivers/base/power/main.c:446",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:async_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:async_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:async_suspend_noirq",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:async_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:async_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:async_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586305872,
      "name": "pm_dev_err",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071586320272,
      "name": "pm_dev_err.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char * info</code> ➡️ <code>const char * info</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void pm_dev_err(struct device * dev, pm_message_t state, const char * info, int error)
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
void pm_dev_err(struct device * dev, pm_message_t state, const char * info, int error)
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
