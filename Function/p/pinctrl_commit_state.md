# Function: <code>pinctrl_commit_state</code>

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
int pinctrl_commit_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_commit_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583868928,
      "name": "pinctrl_commit_state",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1196",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_pm_select_state",
        "drivers/pinctrl/core.c:pinctrl_init_done",
        "drivers/pinctrl/core.c:pinctrl_force_default",
        "drivers/pinctrl/core.c:pinctrl_force_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583868928,
      "name": "pinctrl_commit_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
int pinctrl_commit_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_commit_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584069472,
      "name": "pinctrl_commit_state",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1196",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_pm_select_state",
        "drivers/pinctrl/core.c:pinctrl_init_done",
        "drivers/pinctrl/core.c:pinctrl_force_default",
        "drivers/pinctrl/core.c:pinctrl_force_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584069472,
      "name": "pinctrl_commit_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
int pinctrl_commit_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_commit_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584154160,
      "name": "pinctrl_commit_state",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1224",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_pm_select_state",
        "drivers/pinctrl/core.c:pinctrl_init_done",
        "drivers/pinctrl/core.c:pinctrl_force_default",
        "drivers/pinctrl/core.c:pinctrl_force_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584154160,
      "name": "pinctrl_commit_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
int pinctrl_commit_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_commit_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pinctrl_commit_state",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1209",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_pm_select_state",
        "drivers/pinctrl/core.c:pinctrl_init_done",
        "drivers/pinctrl/core.c:pinctrl_force_default",
        "drivers/pinctrl/core.c:pinctrl_force_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584344352,
      "name": "pinctrl_commit_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    },
    {
      "addr": 18446744071584352456,
      "name": "pinctrl_commit_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
int pinctrl_commit_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_commit_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pinctrl_commit_state",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1237",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_pm_select_state",
        "drivers/pinctrl/core.c:pinctrl_init_done",
        "drivers/pinctrl/core.c:pinctrl_force_default",
        "drivers/pinctrl/core.c:pinctrl_force_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584479168,
      "name": "pinctrl_commit_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    },
    {
      "addr": 18446744071584487298,
      "name": "pinctrl_commit_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
int pinctrl_commit_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_commit_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pinctrl_commit_state",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1238",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_claim_hogs",
        "drivers/pinctrl/core.c:pinctrl_pm_select_idle_state",
        "drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state",
        "drivers/pinctrl/core.c:pinctrl_pm_select_default_state",
        "drivers/pinctrl/core.c:pinctrl_init_done",
        "drivers/pinctrl/core.c:pinctrl_force_default",
        "drivers/pinctrl/core.c:pinctrl_force_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585143536,
      "name": "pinctrl_commit_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    },
    {
      "addr": 18446744071585152037,
      "name": "pinctrl_commit_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
int pinctrl_commit_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_commit_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pinctrl_commit_state",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1239",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_claim_hogs",
        "drivers/pinctrl/core.c:pinctrl_pm_select_idle_state",
        "drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state",
        "drivers/pinctrl/core.c:pinctrl_pm_select_default_state",
        "drivers/pinctrl/core.c:pinctrl_init_done",
        "drivers/pinctrl/core.c:pinctrl_force_default",
        "drivers/pinctrl/core.c:pinctrl_force_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585294672,
      "name": "pinctrl_commit_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    },
    {
      "addr": 18446744071591382603,
      "name": "pinctrl_commit_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
int pinctrl_commit_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_commit_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pinctrl_commit_state",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1239",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_claim_hogs",
        "drivers/pinctrl/core.c:pinctrl_pm_select_idle_state",
        "drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state",
        "drivers/pinctrl/core.c:pinctrl_pm_select_default_state",
        "drivers/pinctrl/core.c:pinctrl_init_done",
        "drivers/pinctrl/core.c:pinctrl_force_default",
        "drivers/pinctrl/core.c:pinctrl_force_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585182160,
      "name": "pinctrl_commit_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
    },
    {
      "addr": 18446744071591325290,
      "name": "pinctrl_commit_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
int pinctrl_commit_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_commit_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pinctrl_commit_state",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1239",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_claim_hogs",
        "drivers/pinctrl/core.c:pinctrl_pm_select_idle_state",
        "drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state",
        "drivers/pinctrl/core.c:pinctrl_pm_select_default_state",
        "drivers/pinctrl/core.c:pinctrl_init_done",
        "drivers/pinctrl/core.c:pinctrl_force_default",
        "drivers/pinctrl/core.c:pinctrl_force_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585636816,
      "name": "pinctrl_commit_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
    },
    {
      "addr": 18446744071592346406,
      "name": "pinctrl_commit_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
int pinctrl_commit_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_commit_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pinctrl_commit_state",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1239",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_claim_hogs",
        "drivers/pinctrl/core.c:pinctrl_pm_select_idle_state",
        "drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state",
        "drivers/pinctrl/core.c:pinctrl_pm_select_default_state",
        "drivers/pinctrl/core.c:pinctrl_init_done",
        "drivers/pinctrl/core.c:pinctrl_force_default",
        "drivers/pinctrl/core.c:pinctrl_force_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586797392,
      "name": "pinctrl_commit_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
    },
    {
      "addr": 18446744071594207861,
      "name": "pinctrl_commit_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
int pinctrl_commit_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_commit_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pinctrl_commit_state",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1239",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_claim_hogs",
        "drivers/pinctrl/core.c:pinctrl_pm_select_idle_state",
        "drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state",
        "drivers/pinctrl/core.c:pinctrl_pm_select_default_state",
        "drivers/pinctrl/core.c:pinctrl_init_done",
        "drivers/pinctrl/core.c:pinctrl_force_default",
        "drivers/pinctrl/core.c:pinctrl_force_sleep",
        "drivers/pinctrl/core.c:pinctrl_commit_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587934144,
      "name": "pinctrl_commit_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 511
    },
    {
      "addr": 18446744071596203704,
      "name": "pinctrl_commit_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int pinctrl_commit_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_commit_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pinctrl_commit_state",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1243",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_claim_hogs",
        "drivers/pinctrl/core.c:pinctrl_pm_select_idle_state",
        "drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state",
        "drivers/pinctrl/core.c:pinctrl_pm_select_default_state",
        "drivers/pinctrl/core.c:pinctrl_init_done",
        "drivers/pinctrl/core.c:pinctrl_force_default",
        "drivers/pinctrl/core.c:pinctrl_force_sleep",
        "drivers/pinctrl/core.c:pinctrl_commit_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588208304,
      "name": "pinctrl_commit_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 522
    },
    {
      "addr": 18446744071596728760,
      "name": "pinctrl_commit_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int pinctrl_commit_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_commit_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pinctrl_commit_state",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1257",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_claim_hogs",
        "drivers/pinctrl/core.c:pinctrl_pm_select_idle_state",
        "drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state",
        "drivers/pinctrl/core.c:pinctrl_pm_select_default_state",
        "drivers/pinctrl/core.c:pinctrl_init_done",
        "drivers/pinctrl/core.c:pinctrl_force_default",
        "drivers/pinctrl/core.c:pinctrl_force_sleep",
        "drivers/pinctrl/core.c:pinctrl_commit_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588501120,
      "name": "pinctrl_commit_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 511
    },
    {
      "addr": 18446744071597637109,
      "name": "pinctrl_commit_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int pinctrl_commit_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_commit_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496495904,
      "name": "pinctrl_commit_state",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1237",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_pm_select_state",
        "drivers/pinctrl/core.c:pinctrl_init_done",
        "drivers/pinctrl/core.c:pinctrl_force_default",
        "drivers/pinctrl/core.c:pinctrl_force_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496495904,
      "name": "pinctrl_commit_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
int pinctrl_commit_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_commit_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229802484,
      "name": "pinctrl_commit_state",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1237",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_pm_select_state",
        "drivers/pinctrl/core.c:pinctrl_init_done",
        "drivers/pinctrl/core.c:pinctrl_force_default",
        "drivers/pinctrl/core.c:pinctrl_force_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229802484,
      "name": "pinctrl_commit_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
int pinctrl_commit_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_commit_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290702176,
      "name": "pinctrl_commit_state",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1237",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_pm_select_state",
        "drivers/pinctrl/core.c:pinctrl_init_done",
        "drivers/pinctrl/core.c:pinctrl_force_default",
        "drivers/pinctrl/core.c:pinctrl_force_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290702176,
      "name": "pinctrl_commit_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int pinctrl_commit_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_commit_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275415388,
      "name": "pinctrl_commit_state",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1237",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_pm_select_state",
        "drivers/pinctrl/core.c:pinctrl_init_done",
        "drivers/pinctrl/core.c:pinctrl_force_default",
        "drivers/pinctrl/core.c:pinctrl_force_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275415388,
      "name": "pinctrl_commit_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int pinctrl_commit_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_commit_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pinctrl_commit_state",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1237",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_pm_select_state",
        "drivers/pinctrl/core.c:pinctrl_init_done",
        "drivers/pinctrl/core.c:pinctrl_force_default",
        "drivers/pinctrl/core.c:pinctrl_force_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584447920,
      "name": "pinctrl_commit_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    },
    {
      "addr": 18446744071584456050,
      "name": "pinctrl_commit_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
int pinctrl_commit_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_commit_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pinctrl_commit_state",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1237",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_pm_select_state",
        "drivers/pinctrl/core.c:pinctrl_init_done",
        "drivers/pinctrl/core.c:pinctrl_force_default",
        "drivers/pinctrl/core.c:pinctrl_force_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584383600,
      "name": "pinctrl_commit_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    },
    {
      "addr": 18446744071584391730,
      "name": "pinctrl_commit_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
int pinctrl_commit_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_commit_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pinctrl_commit_state",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1237",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_pm_select_state",
        "drivers/pinctrl/core.c:pinctrl_init_done",
        "drivers/pinctrl/core.c:pinctrl_force_default",
        "drivers/pinctrl/core.c:pinctrl_force_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584430832,
      "name": "pinctrl_commit_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    },
    {
      "addr": 18446744071584438962,
      "name": "pinctrl_commit_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
int pinctrl_commit_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_commit_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pinctrl_commit_state",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1237",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_pm_select_state",
        "drivers/pinctrl/core.c:pinctrl_init_done",
        "drivers/pinctrl/core.c:pinctrl_force_default",
        "drivers/pinctrl/core.c:pinctrl_force_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584536960,
      "name": "pinctrl_commit_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    },
    {
      "addr": 18446744071584545090,
      "name": "pinctrl_commit_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
int pinctrl_commit_state(struct pinctrl * p, struct pinctrl_state * state)
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
