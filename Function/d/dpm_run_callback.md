# Function: <code>dpm_run_callback</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int dpm_run_callback(pm_callback_t cb, struct device * dev, pm_message_t state, char * info)
```

```json
{
  "name": "dpm_run_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584450832,
      "name": "dpm_run_callback",
      "external": false,
      "loc": "drivers/base/power/main.c:376",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584450832,
      "name": "dpm_run_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
int dpm_run_callback(pm_callback_t cb, struct device * dev, pm_message_t state, char * info)
```

```json
{
  "name": "dpm_run_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584787056,
      "name": "dpm_run_callback",
      "external": false,
      "loc": "drivers/base/power/main.c:378",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584787056,
      "name": "dpm_run_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
int dpm_run_callback(pm_callback_t cb, struct device * dev, pm_message_t state, char * info)
```

```json
{
  "name": "dpm_run_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584979024,
      "name": "dpm_run_callback",
      "external": false,
      "loc": "drivers/base/power/main.c:436",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584979024,
      "name": "dpm_run_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
int dpm_run_callback(pm_callback_t cb, struct device * dev, pm_message_t state, const char * info)
```

```json
{
  "name": "dpm_run_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585063488,
      "name": "dpm_run_callback",
      "external": false,
      "loc": "drivers/base/power/main.c:444",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585063488,
      "name": "dpm_run_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
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
int dpm_run_callback(pm_callback_t cb, struct device * dev, pm_message_t state, const char * info)
```

```json
{
  "name": "dpm_run_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585486496,
      "name": "dpm_run_callback",
      "external": false,
      "loc": "drivers/base/power/main.c:441",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585486496,
      "name": "dpm_run_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
int dpm_run_callback(pm_callback_t cb, struct device * dev, pm_message_t state, const char * info)
```

```json
{
  "name": "dpm_run_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpm_run_callback",
      "external": false,
      "loc": "drivers/base/power/main.c:437",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585730912,
      "name": "dpm_run_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
    },
    {
      "addr": 18446744071585743872,
      "name": "dpm_run_callback.cold.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int dpm_run_callback(pm_callback_t cb, struct device * dev, pm_message_t state, const char * info)
```

```json
{
  "name": "dpm_run_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpm_run_callback",
      "external": false,
      "loc": "drivers/base/power/main.c:438",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585863504,
      "name": "dpm_run_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
    },
    {
      "addr": 18446744071585876608,
      "name": "dpm_run_callback.cold.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int dpm_run_callback(pm_callback_t cb, struct device * dev, pm_message_t state, const char * info)
```

```json
{
  "name": "dpm_run_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpm_run_callback",
      "external": false,
      "loc": "drivers/base/power/main.c:445",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586100592,
      "name": "dpm_run_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
    },
    {
      "addr": 18446744071586113890,
      "name": "dpm_run_callback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
int dpm_run_callback(pm_callback_t cb, struct device * dev, pm_message_t state, const char * info)
```

```json
{
  "name": "dpm_run_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpm_run_callback",
      "external": false,
      "loc": "drivers/base/power/main.c:473",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586248240,
      "name": "dpm_run_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
    },
    {
      "addr": 18446744071586261314,
      "name": "dpm_run_callback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
int dpm_run_callback(pm_callback_t cb, struct device * dev, pm_message_t state, const char * info)
```

```json
{
  "name": "dpm_run_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpm_run_callback",
      "external": false,
      "loc": "drivers/base/power/main.c:477",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587015472,
      "name": "dpm_run_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
    },
    {
      "addr": 18446744071587029385,
      "name": "dpm_run_callback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
int dpm_run_callback(pm_callback_t cb, struct device * dev, pm_message_t state, const char * info)
```

```json
{
  "name": "dpm_run_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpm_run_callback",
      "external": false,
      "loc": "drivers/base/power/main.c:476",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587100128,
      "name": "dpm_run_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071591488861,
      "name": "dpm_run_callback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int dpm_run_callback(pm_callback_t cb, struct device * dev, pm_message_t state, const char * info)
```

```json
{
  "name": "dpm_run_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpm_run_callback",
      "external": false,
      "loc": "drivers/base/power/main.c:477",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586986432,
      "name": "dpm_run_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071591431894,
      "name": "dpm_run_callback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int dpm_run_callback(pm_callback_t cb, struct device * dev, pm_message_t state, const char * info)
```

```json
{
  "name": "dpm_run_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpm_run_callback",
      "external": false,
      "loc": "drivers/base/power/main.c:474",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587552608,
      "name": "dpm_run_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
    },
    {
      "addr": 18446744071592491408,
      "name": "dpm_run_callback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
int dpm_run_callback(pm_callback_t cb, struct device * dev, pm_message_t state, const char * info)
```

```json
{
  "name": "dpm_run_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpm_run_callback",
      "external": false,
      "loc": "drivers/base/power/main.c:473",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588886016,
      "name": "dpm_run_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
    },
    {
      "addr": 18446744071594361432,
      "name": "dpm_run_callback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int dpm_run_callback(pm_callback_t cb, struct device * dev, pm_message_t state, const char * info)
```

```json
{
  "name": "dpm_run_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpm_run_callback",
      "external": false,
      "loc": "drivers/base/power/main.c:473",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590395280,
      "name": "dpm_run_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
    },
    {
      "addr": 18446744071596247271,
      "name": "dpm_run_callback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int dpm_run_callback(pm_callback_t cb, struct device * dev, pm_message_t state, const char * info)
```

```json
{
  "name": "dpm_run_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpm_run_callback",
      "external": false,
      "loc": "drivers/base/power/main.c:473",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590715696,
      "name": "dpm_run_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
    },
    {
      "addr": 18446744071596775672,
      "name": "dpm_run_callback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int dpm_run_callback(pm_callback_t cb, struct device * dev, pm_message_t state, const char * info)
```

```json
{
  "name": "dpm_run_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpm_run_callback",
      "external": false,
      "loc": "drivers/base/power/main.c:473",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591077664,
      "name": "dpm_run_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
    },
    {
      "addr": 18446744071597684922,
      "name": "dpm_run_callback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int dpm_run_callback(pm_callback_t cb, struct device * dev, pm_message_t state, const char * info)
```

```json
{
  "name": "dpm_run_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499068008,
      "name": "dpm_run_callback",
      "external": false,
      "loc": "drivers/base/power/main.c:473",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499068008,
      "name": "dpm_run_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
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
int dpm_run_callback(pm_callback_t cb, struct device * dev, pm_message_t state, const char * info)
```

```json
{
  "name": "dpm_run_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231620872,
      "name": "dpm_run_callback",
      "external": false,
      "loc": "drivers/base/power/main.c:473",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231620872,
      "name": "dpm_run_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
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
int dpm_run_callback(pm_callback_t cb, struct device * dev, pm_message_t state, const char * info)
```

```json
{
  "name": "dpm_run_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292244272,
      "name": "dpm_run_callback",
      "external": false,
      "loc": "drivers/base/power/main.c:473",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292244272,
      "name": "dpm_run_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 612
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
int dpm_run_callback(pm_callback_t cb, struct device * dev, pm_message_t state, const char * info)
```

```json
{
  "name": "dpm_run_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpm_run_callback",
      "external": false,
      "loc": "drivers/base/power/main.c:473",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586009968,
      "name": "dpm_run_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
    },
    {
      "addr": 18446744071586024642,
      "name": "dpm_run_callback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
int dpm_run_callback(pm_callback_t cb, struct device * dev, pm_message_t state, const char * info)
```

```json
{
  "name": "dpm_run_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpm_run_callback",
      "external": false,
      "loc": "drivers/base/power/main.c:473",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585857568,
      "name": "dpm_run_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
    },
    {
      "addr": 18446744071585870594,
      "name": "dpm_run_callback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
int dpm_run_callback(pm_callback_t cb, struct device * dev, pm_message_t state, const char * info)
```

```json
{
  "name": "dpm_run_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpm_run_callback",
      "external": false,
      "loc": "drivers/base/power/main.c:473",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586198256,
      "name": "dpm_run_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
    },
    {
      "addr": 18446744071586211330,
      "name": "dpm_run_callback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
int dpm_run_callback(pm_callback_t cb, struct device * dev, pm_message_t state, const char * info)
```

```json
{
  "name": "dpm_run_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpm_run_callback",
      "external": false,
      "loc": "drivers/base/power/main.c:473",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586306832,
      "name": "dpm_run_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
    },
    {
      "addr": 18446744071586320402,
      "name": "dpm_run_callback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
int dpm_run_callback(pm_callback_t cb, struct device * dev, pm_message_t state, const char * info)
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
