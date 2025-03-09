# Function: <code>regulator_balance_voltage</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int regulator_balance_voltage(struct regulator_dev * rdev, suspend_state_t state)
```

```json
{
  "name": "regulator_balance_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_balance_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3615",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585292848,
      "name": "regulator_balance_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1631
    },
    {
      "addr": 18446744071585304857,
      "name": "regulator_balance_voltage.cold.63",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int regulator_balance_voltage(struct regulator_dev * rdev, suspend_state_t state)
```

```json
{
  "name": "regulator_balance_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_balance_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3631",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585502704,
      "name": "regulator_balance_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1250
    },
    {
      "addr": 18446744071585517096,
      "name": "regulator_balance_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int regulator_balance_voltage(struct regulator_dev * rdev, suspend_state_t state)
```

```json
{
  "name": "regulator_balance_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_balance_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3640",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585646944,
      "name": "regulator_balance_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1250
    },
    {
      "addr": 18446744071585658606,
      "name": "regulator_balance_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int regulator_balance_voltage(struct regulator_dev * rdev, suspend_state_t state)
```

```json
{
  "name": "regulator_balance_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_balance_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3754",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586374000,
      "name": "regulator_balance_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071586383615,
      "name": "regulator_balance_voltage.cold",
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
int regulator_balance_voltage(struct regulator_dev * rdev, suspend_state_t state)
```

```json
{
  "name": "regulator_balance_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_balance_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3884",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586491776,
      "name": "regulator_balance_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071591455742,
      "name": "regulator_balance_voltage.cold",
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
int regulator_balance_voltage(struct regulator_dev * rdev, suspend_state_t state)
```

```json
{
  "name": "regulator_balance_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_balance_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3882",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586374736,
      "name": "regulator_balance_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071591397529,
      "name": "regulator_balance_voltage.cold",
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
int regulator_balance_voltage(struct regulator_dev * rdev, suspend_state_t state)
```

```json
{
  "name": "regulator_balance_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_balance_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3982",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:regulator_sync_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586897968,
      "name": "regulator_balance_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071592442531,
      "name": "regulator_balance_voltage.cold",
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
int regulator_balance_voltage(struct regulator_dev * rdev, suspend_state_t state)
```

```json
{
  "name": "regulator_balance_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_balance_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:4024",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:regulator_sync_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588188112,
      "name": "regulator_balance_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071594310773,
      "name": "regulator_balance_voltage.cold",
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
int regulator_balance_voltage(struct regulator_dev * rdev, suspend_state_t state)
```

```json
{
  "name": "regulator_balance_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589589568,
      "name": "regulator_balance_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:4054",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:regulator_sync_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589589568,
      "name": "regulator_balance_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
int regulator_balance_voltage(struct regulator_dev * rdev, suspend_state_t state)
```

```json
{
  "name": "regulator_balance_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589891408,
      "name": "regulator_balance_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:4120",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:regulator_sync_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589891408,
      "name": "regulator_balance_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
int regulator_balance_voltage(struct regulator_dev * rdev, suspend_state_t state)
```

```json
{
  "name": "regulator_balance_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590229056,
      "name": "regulator_balance_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:4126",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:regulator_sync_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590229056,
      "name": "regulator_balance_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
int regulator_balance_voltage(struct regulator_dev * rdev, suspend_state_t state)
```

```json
{
  "name": "regulator_balance_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498308528,
      "name": "regulator_balance_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3640",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498308528,
      "name": "regulator_balance_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1072
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
int regulator_balance_voltage(struct regulator_dev * rdev, suspend_state_t state)
```

```json
{
  "name": "regulator_balance_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230989396,
      "name": "regulator_balance_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3640",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230989396,
      "name": "regulator_balance_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1308
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
int regulator_balance_voltage(struct regulator_dev * rdev, suspend_state_t state)
```

```json
{
  "name": "regulator_balance_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291478880,
      "name": "regulator_balance_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3640",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291478880,
      "name": "regulator_balance_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1644
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
int regulator_balance_voltage(struct regulator_dev * rdev, suspend_state_t state)
```

```json
{
  "name": "regulator_balance_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275999518,
      "name": "regulator_balance_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3640",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275999518,
      "name": "regulator_balance_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1010
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
int regulator_balance_voltage(struct regulator_dev * rdev, suspend_state_t state)
```

```json
{
  "name": "regulator_balance_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_balance_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3640",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585407552,
      "name": "regulator_balance_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1250
    },
    {
      "addr": 18446744071585419527,
      "name": "regulator_balance_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int regulator_balance_voltage(struct regulator_dev * rdev, suspend_state_t state)
```

```json
{
  "name": "regulator_balance_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_balance_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3640",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585278016,
      "name": "regulator_balance_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1250
    },
    {
      "addr": 18446744071585289678,
      "name": "regulator_balance_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int regulator_balance_voltage(struct regulator_dev * rdev, suspend_state_t state)
```

```json
{
  "name": "regulator_balance_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_balance_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3640",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585597344,
      "name": "regulator_balance_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1250
    },
    {
      "addr": 18446744071585609006,
      "name": "regulator_balance_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int regulator_balance_voltage(struct regulator_dev * rdev, suspend_state_t state)
```

```json
{
  "name": "regulator_balance_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_balance_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3640",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585705472,
      "name": "regulator_balance_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1250
    },
    {
      "addr": 18446744071585717134,
      "name": "regulator_balance_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int regulator_balance_voltage(struct regulator_dev * rdev, suspend_state_t state)
```
</details>
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
