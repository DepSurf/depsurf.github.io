# Function: <code>regulator_set_voltage_rdev</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_set_voltage_rdev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585293430,
      "name": "regulator_set_voltage_rdev",
      "external": false,
      "loc": "drivers/regulator/core.c:3373",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_balance_voltage"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int regulator_set_voltage_rdev(struct regulator_dev * rdev, int min_uV, int max_uV, suspend_state_t state)
```

```json
{
  "name": "regulator_set_voltage_rdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_set_voltage_rdev",
      "external": true,
      "loc": "drivers/regulator/core.c:3388",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_balance_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585517041,
      "name": "regulator_set_voltage_rdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071585502144,
      "name": "regulator_set_voltage_rdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 555
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
int regulator_set_voltage_rdev(struct regulator_dev * rdev, int min_uV, int max_uV, suspend_state_t state)
```

```json
{
  "name": "regulator_set_voltage_rdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_set_voltage_rdev",
      "external": true,
      "loc": "drivers/regulator/core.c:3396",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_balance_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585659326,
      "name": "regulator_set_voltage_rdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071585654928,
      "name": "regulator_set_voltage_rdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 555
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
int regulator_set_voltage_rdev(struct regulator_dev * rdev, int min_uV, int max_uV, suspend_state_t state)
```

```json
{
  "name": "regulator_set_voltage_rdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_set_voltage_rdev",
      "external": true,
      "loc": "drivers/regulator/core.c:3427",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_do_balance_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586384859,
      "name": "regulator_set_voltage_rdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071586380656,
      "name": "regulator_set_voltage_rdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 577
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
int regulator_set_voltage_rdev(struct regulator_dev * rdev, int min_uV, int max_uV, suspend_state_t state)
```

```json
{
  "name": "regulator_set_voltage_rdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_set_voltage_rdev",
      "external": true,
      "loc": "drivers/regulator/core.c:3557",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_do_balance_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591457156,
      "name": "regulator_set_voltage_rdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071586498624,
      "name": "regulator_set_voltage_rdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 577
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
int regulator_set_voltage_rdev(struct regulator_dev * rdev, int min_uV, int max_uV, suspend_state_t state)
```

```json
{
  "name": "regulator_set_voltage_rdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_set_voltage_rdev",
      "external": true,
      "loc": "drivers/regulator/core.c:3555",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_do_balance_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591398961,
      "name": "regulator_set_voltage_rdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071586382048,
      "name": "regulator_set_voltage_rdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 579
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
int regulator_set_voltage_rdev(struct regulator_dev * rdev, int min_uV, int max_uV, suspend_state_t state)
```

```json
{
  "name": "regulator_set_voltage_rdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_set_voltage_rdev",
      "external": true,
      "loc": "drivers/regulator/core.c:3655",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_do_balance_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592444339,
      "name": "regulator_set_voltage_rdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071586905856,
      "name": "regulator_set_voltage_rdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 579
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
int regulator_set_voltage_rdev(struct regulator_dev * rdev, int min_uV, int max_uV, suspend_state_t state)
```

```json
{
  "name": "regulator_set_voltage_rdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_set_voltage_rdev",
      "external": true,
      "loc": "drivers/regulator/core.c:3697",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_do_balance_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594312342,
      "name": "regulator_set_voltage_rdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071588197232,
      "name": "regulator_set_voltage_rdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
int regulator_set_voltage_rdev(struct regulator_dev * rdev, int min_uV, int max_uV, suspend_state_t state)
```

```json
{
  "name": "regulator_set_voltage_rdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589601520,
      "name": "regulator_set_voltage_rdev",
      "external": true,
      "loc": "drivers/regulator/core.c:3727",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_do_balance_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589601520,
      "name": "regulator_set_voltage_rdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 646
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
int regulator_set_voltage_rdev(struct regulator_dev * rdev, int min_uV, int max_uV, suspend_state_t state)
```

```json
{
  "name": "regulator_set_voltage_rdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589904880,
      "name": "regulator_set_voltage_rdev",
      "external": true,
      "loc": "drivers/regulator/core.c:3793",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_do_balance_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589904880,
      "name": "regulator_set_voltage_rdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 639
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
int regulator_set_voltage_rdev(struct regulator_dev * rdev, int min_uV, int max_uV, suspend_state_t state)
```

```json
{
  "name": "regulator_set_voltage_rdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590242800,
      "name": "regulator_set_voltage_rdev",
      "external": true,
      "loc": "drivers/regulator/core.c:3799",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_do_balance_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590242800,
      "name": "regulator_set_voltage_rdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 639
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
int regulator_set_voltage_rdev(struct regulator_dev * rdev, int min_uV, int max_uV, suspend_state_t state)
```

```json
{
  "name": "regulator_set_voltage_rdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498317088,
      "name": "regulator_set_voltage_rdev",
      "external": true,
      "loc": "drivers/regulator/core.c:3396",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_balance_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498317088,
      "name": "regulator_set_voltage_rdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 556
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
int regulator_set_voltage_rdev(struct regulator_dev * rdev, int min_uV, int max_uV, suspend_state_t state)
```

```json
{
  "name": "regulator_set_voltage_rdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230998288,
      "name": "regulator_set_voltage_rdev",
      "external": true,
      "loc": "drivers/regulator/core.c:3396",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_balance_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230998288,
      "name": "regulator_set_voltage_rdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
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
int regulator_set_voltage_rdev(struct regulator_dev * rdev, int min_uV, int max_uV, suspend_state_t state)
```

```json
{
  "name": "regulator_set_voltage_rdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291491504,
      "name": "regulator_set_voltage_rdev",
      "external": true,
      "loc": "drivers/regulator/core.c:3396",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_balance_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291491504,
      "name": "regulator_set_voltage_rdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 868
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
int regulator_set_voltage_rdev(struct regulator_dev * rdev, int min_uV, int max_uV, suspend_state_t state)
```

```json
{
  "name": "regulator_set_voltage_rdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276007352,
      "name": "regulator_set_voltage_rdev",
      "external": true,
      "loc": "drivers/regulator/core.c:3396",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_balance_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276007352,
      "name": "regulator_set_voltage_rdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
int regulator_set_voltage_rdev(struct regulator_dev * rdev, int min_uV, int max_uV, suspend_state_t state)
```

```json
{
  "name": "regulator_set_voltage_rdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_set_voltage_rdev",
      "external": true,
      "loc": "drivers/regulator/core.c:3396",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_balance_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585420350,
      "name": "regulator_set_voltage_rdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071585415920,
      "name": "regulator_set_voltage_rdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 555
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
int regulator_set_voltage_rdev(struct regulator_dev * rdev, int min_uV, int max_uV, suspend_state_t state)
```

```json
{
  "name": "regulator_set_voltage_rdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_set_voltage_rdev",
      "external": true,
      "loc": "drivers/regulator/core.c:3396",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_balance_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585290398,
      "name": "regulator_set_voltage_rdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071585286000,
      "name": "regulator_set_voltage_rdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 555
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
int regulator_set_voltage_rdev(struct regulator_dev * rdev, int min_uV, int max_uV, suspend_state_t state)
```

```json
{
  "name": "regulator_set_voltage_rdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_set_voltage_rdev",
      "external": true,
      "loc": "drivers/regulator/core.c:3396",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_balance_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585609726,
      "name": "regulator_set_voltage_rdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071585605328,
      "name": "regulator_set_voltage_rdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 555
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
int regulator_set_voltage_rdev(struct regulator_dev * rdev, int min_uV, int max_uV, suspend_state_t state)
```

```json
{
  "name": "regulator_set_voltage_rdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_set_voltage_rdev",
      "external": true,
      "loc": "drivers/regulator/core.c:3396",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_balance_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585717854,
      "name": "regulator_set_voltage_rdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071585713456,
      "name": "regulator_set_voltage_rdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 555
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int regulator_set_voltage_rdev(struct regulator_dev * rdev, int min_uV, int max_uV, suspend_state_t state)
```
</details>
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
