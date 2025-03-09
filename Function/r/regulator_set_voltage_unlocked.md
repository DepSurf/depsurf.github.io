# Function: <code>regulator_set_voltage_unlocked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int regulator_set_voltage_unlocked(struct regulator * regulator, int min_uV, int max_uV)
```

```json
{
  "name": "regulator_set_voltage_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583937520,
      "name": "regulator_set_voltage_unlocked",
      "external": false,
      "loc": "drivers/regulator/core.c:2820",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_set_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583937520,
      "name": "regulator_set_voltage_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 565
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
int regulator_set_voltage_unlocked(struct regulator * regulator, int min_uV, int max_uV)
```

```json
{
  "name": "regulator_set_voltage_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584267472,
      "name": "regulator_set_voltage_unlocked",
      "external": false,
      "loc": "drivers/regulator/core.c:2836",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584267472,
      "name": "regulator_set_voltage_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 572
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
int regulator_set_voltage_unlocked(struct regulator * regulator, int min_uV, int max_uV)
```

```json
{
  "name": "regulator_set_voltage_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584449296,
      "name": "regulator_set_voltage_unlocked",
      "external": false,
      "loc": "drivers/regulator/core.c:2872",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584449296,
      "name": "regulator_set_voltage_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 572
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
int regulator_set_voltage_unlocked(struct regulator * regulator, int min_uV, int max_uV)
```

```json
{
  "name": "regulator_set_voltage_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584532864,
      "name": "regulator_set_voltage_unlocked",
      "external": false,
      "loc": "drivers/regulator/core.c:2892",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584532864,
      "name": "regulator_set_voltage_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 636
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
int regulator_set_voltage_unlocked(struct regulator * regulator, int min_uV, int max_uV)
```

```json
{
  "name": "regulator_set_voltage_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584943088,
      "name": "regulator_set_voltage_unlocked",
      "external": false,
      "loc": "drivers/regulator/core.c:2900",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584943088,
      "name": "regulator_set_voltage_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 636
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
int regulator_set_voltage_unlocked(struct regulator * regulator, int min_uV, int max_uV, suspend_state_t state)
```

```json
{
  "name": "regulator_set_voltage_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_set_voltage_unlocked",
      "external": false,
      "loc": "drivers/regulator/core.c:2983",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_suspend_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585169040,
      "name": "regulator_set_voltage_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 781
    },
    {
      "addr": 18446744071585187669,
      "name": "regulator_set_voltage_unlocked.cold.50",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
int regulator_set_voltage_unlocked(struct regulator * regulator, int min_uV, int max_uV, suspend_state_t state)
```

```json
{
  "name": "regulator_set_voltage_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_set_voltage_unlocked",
      "external": false,
      "loc": "drivers/regulator/core.c:3311",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_suspend_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_balance_voltage",
        "drivers/regulator/core.c:regulator_balance_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585294480,
      "name": "regulator_set_voltage_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
    },
    {
      "addr": 18446744071585304943,
      "name": "regulator_set_voltage_unlocked.cold.64",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int regulator_set_voltage_unlocked(struct regulator * regulator, int min_uV, int max_uV, suspend_state_t state)
```

```json
{
  "name": "regulator_set_voltage_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585501888,
      "name": "regulator_set_voltage_unlocked",
      "external": false,
      "loc": "drivers/regulator/core.c:3329",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_suspend_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_rdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585501888,
      "name": "regulator_set_voltage_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
int regulator_set_voltage_unlocked(struct regulator * regulator, int min_uV, int max_uV, suspend_state_t state)
```

```json
{
  "name": "regulator_set_voltage_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585654672,
      "name": "regulator_set_voltage_unlocked",
      "external": false,
      "loc": "drivers/regulator/core.c:3337",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_suspend_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_rdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585654672,
      "name": "regulator_set_voltage_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
int regulator_set_voltage_unlocked(struct regulator * regulator, int min_uV, int max_uV, suspend_state_t state)
```

```json
{
  "name": "regulator_set_voltage_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_set_voltage_unlocked",
      "external": false,
      "loc": "drivers/regulator/core.c:3368",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_suspend_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_rdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586380432,
      "name": "regulator_set_voltage_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071586384831,
      "name": "regulator_set_voltage_unlocked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int regulator_set_voltage_unlocked(struct regulator * regulator, int min_uV, int max_uV, suspend_state_t state)
```

```json
{
  "name": "regulator_set_voltage_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_set_voltage_unlocked",
      "external": false,
      "loc": "drivers/regulator/core.c:3498",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_suspend_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_rdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586498400,
      "name": "regulator_set_voltage_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071591457128,
      "name": "regulator_set_voltage_unlocked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int regulator_set_voltage_unlocked(struct regulator * regulator, int min_uV, int max_uV, suspend_state_t state)
```

```json
{
  "name": "regulator_set_voltage_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_set_voltage_unlocked",
      "external": false,
      "loc": "drivers/regulator/core.c:3496",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_suspend_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_rdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586381824,
      "name": "regulator_set_voltage_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
    },
    {
      "addr": 18446744071591398933,
      "name": "regulator_set_voltage_unlocked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int regulator_set_voltage_unlocked(struct regulator * regulator, int min_uV, int max_uV, suspend_state_t state)
```

```json
{
  "name": "regulator_set_voltage_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_set_voltage_unlocked",
      "external": false,
      "loc": "drivers/regulator/core.c:3596",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_suspend_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_rdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586905600,
      "name": "regulator_set_voltage_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    },
    {
      "addr": 18446744071592444311,
      "name": "regulator_set_voltage_unlocked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int regulator_set_voltage_unlocked(struct regulator * regulator, int min_uV, int max_uV, suspend_state_t state)
```

```json
{
  "name": "regulator_set_voltage_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_set_voltage_unlocked",
      "external": false,
      "loc": "drivers/regulator/core.c:3638",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_suspend_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_rdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588196928,
      "name": "regulator_set_voltage_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
    },
    {
      "addr": 18446744071594312314,
      "name": "regulator_set_voltage_unlocked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int regulator_set_voltage_unlocked(struct regulator * regulator, int min_uV, int max_uV, suspend_state_t state)
```

```json
{
  "name": "regulator_set_voltage_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589601152,
      "name": "regulator_set_voltage_unlocked",
      "external": false,
      "loc": "drivers/regulator/core.c:3668",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_suspend_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_rdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589601152,
      "name": "regulator_set_voltage_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
int regulator_set_voltage_unlocked(struct regulator * regulator, int min_uV, int max_uV, suspend_state_t state)
```

```json
{
  "name": "regulator_set_voltage_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589904512,
      "name": "regulator_set_voltage_unlocked",
      "external": false,
      "loc": "drivers/regulator/core.c:3734",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_suspend_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_rdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589904512,
      "name": "regulator_set_voltage_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
int regulator_set_voltage_unlocked(struct regulator * regulator, int min_uV, int max_uV, suspend_state_t state)
```

```json
{
  "name": "regulator_set_voltage_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590242432,
      "name": "regulator_set_voltage_unlocked",
      "external": false,
      "loc": "drivers/regulator/core.c:3740",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_suspend_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_rdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590242432,
      "name": "regulator_set_voltage_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
int regulator_set_voltage_unlocked(struct regulator * regulator, int min_uV, int max_uV, suspend_state_t state)
```

```json
{
  "name": "regulator_set_voltage_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498316800,
      "name": "regulator_set_voltage_unlocked",
      "external": false,
      "loc": "drivers/regulator/core.c:3337",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_suspend_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_rdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498316800,
      "name": "regulator_set_voltage_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
int regulator_set_voltage_unlocked(struct regulator * regulator, int min_uV, int max_uV, suspend_state_t state)
```

```json
{
  "name": "regulator_set_voltage_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230997984,
      "name": "regulator_set_voltage_unlocked",
      "external": false,
      "loc": "drivers/regulator/core.c:3337",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_suspend_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_rdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230997984,
      "name": "regulator_set_voltage_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
int regulator_set_voltage_unlocked(struct regulator * regulator, int min_uV, int max_uV, suspend_state_t state)
```

```json
{
  "name": "regulator_set_voltage_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291491088,
      "name": "regulator_set_voltage_unlocked",
      "external": false,
      "loc": "drivers/regulator/core.c:3337",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_rdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291491088,
      "name": "regulator_set_voltage_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
int regulator_set_voltage_unlocked(struct regulator * regulator, int min_uV, int max_uV, suspend_state_t state)
```

```json
{
  "name": "regulator_set_voltage_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276007114,
      "name": "regulator_set_voltage_unlocked",
      "external": false,
      "loc": "drivers/regulator/core.c:3337",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_rdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276007114,
      "name": "regulator_set_voltage_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int regulator_set_voltage_unlocked(struct regulator * regulator, int min_uV, int max_uV, suspend_state_t state)
```

```json
{
  "name": "regulator_set_voltage_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585415664,
      "name": "regulator_set_voltage_unlocked",
      "external": false,
      "loc": "drivers/regulator/core.c:3337",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_suspend_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_rdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585415664,
      "name": "regulator_set_voltage_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
int regulator_set_voltage_unlocked(struct regulator * regulator, int min_uV, int max_uV, suspend_state_t state)
```

```json
{
  "name": "regulator_set_voltage_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585285744,
      "name": "regulator_set_voltage_unlocked",
      "external": false,
      "loc": "drivers/regulator/core.c:3337",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_suspend_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_rdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585285744,
      "name": "regulator_set_voltage_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
int regulator_set_voltage_unlocked(struct regulator * regulator, int min_uV, int max_uV, suspend_state_t state)
```

```json
{
  "name": "regulator_set_voltage_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585605072,
      "name": "regulator_set_voltage_unlocked",
      "external": false,
      "loc": "drivers/regulator/core.c:3337",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_suspend_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_rdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585605072,
      "name": "regulator_set_voltage_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
int regulator_set_voltage_unlocked(struct regulator * regulator, int min_uV, int max_uV, suspend_state_t state)
```

```json
{
  "name": "regulator_set_voltage_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585713200,
      "name": "regulator_set_voltage_unlocked",
      "external": false,
      "loc": "drivers/regulator/core.c:3337",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_suspend_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_rdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585713200,
      "name": "regulator_set_voltage_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>suspend_state_t state</code>
</li>
</ul>
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
