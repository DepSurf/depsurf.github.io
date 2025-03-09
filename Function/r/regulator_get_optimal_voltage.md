# Function: <code>regulator_get_optimal_voltage</code>

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
  "name": "regulator_get_optimal_voltage",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585293006,
      "name": "regulator_get_optimal_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3473",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_get_optimal_voltage",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585502998,
      "name": "regulator_get_optimal_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3488",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_get_optimal_voltage",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585647238,
      "name": "regulator_get_optimal_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3497",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int regulator_get_optimal_voltage(struct regulator_dev * rdev, int * current_uV, int * min_uV, int * max_uV, suspend_state_t state, int n_coupled)
```

```json
{
  "name": "regulator_get_optimal_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586372224,
      "name": "regulator_get_optimal_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3528",
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
      "addr": 18446744071586372224,
      "name": "regulator_get_optimal_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 986
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
int regulator_get_optimal_voltage(struct regulator_dev * rdev, int * current_uV, int * min_uV, int * max_uV, suspend_state_t state, int n_coupled)
```

```json
{
  "name": "regulator_get_optimal_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586490000,
      "name": "regulator_get_optimal_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3658",
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
      "addr": 18446744071586490000,
      "name": "regulator_get_optimal_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 986
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_get_optimal_voltage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586373360,
      "name": "regulator_get_optimal_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3656",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_do_balance_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586373360,
      "name": "regulator_get_optimal_voltage.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 980
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_get_optimal_voltage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586896592,
      "name": "regulator_get_optimal_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3756",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_do_balance_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586896592,
      "name": "regulator_get_optimal_voltage.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 989
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
int regulator_get_optimal_voltage(struct regulator_dev * rdev, int * current_uV, int * min_uV, int * max_uV, suspend_state_t state, int n_coupled)
```

```json
{
  "name": "regulator_get_optimal_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588186592,
      "name": "regulator_get_optimal_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3798",
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
      "addr": 18446744071588186592,
      "name": "regulator_get_optimal_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1058
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
int regulator_get_optimal_voltage(struct regulator_dev * rdev, int * current_uV, int * min_uV, int * max_uV, suspend_state_t state, int n_coupled)
```

```json
{
  "name": "regulator_get_optimal_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589588032,
      "name": "regulator_get_optimal_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3828",
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
      "addr": 18446744071589588032,
      "name": "regulator_get_optimal_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1058
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
int regulator_get_optimal_voltage(struct regulator_dev * rdev, int * current_uV, int * min_uV, int * max_uV, suspend_state_t state, int n_coupled)
```

```json
{
  "name": "regulator_get_optimal_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589889888,
      "name": "regulator_get_optimal_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3894",
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
      "addr": 18446744071589889888,
      "name": "regulator_get_optimal_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1010
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
int regulator_get_optimal_voltage(struct regulator_dev * rdev, int * current_uV, int * min_uV, int * max_uV, suspend_state_t state, int n_coupled)
```

```json
{
  "name": "regulator_get_optimal_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590227536,
      "name": "regulator_get_optimal_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3900",
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
      "addr": 18446744071590227536,
      "name": "regulator_get_optimal_voltage",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_get_optimal_voltage",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336498308748,
      "name": "regulator_get_optimal_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3497",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "regulator_get_optimal_voltage",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230989884,
      "name": "regulator_get_optimal_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3497",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "regulator_get_optimal_voltage",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055291479228,
      "name": "regulator_get_optimal_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3497",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_get_optimal_voltage",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275999644,
      "name": "regulator_get_optimal_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3497",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_get_optimal_voltage",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585407846,
      "name": "regulator_get_optimal_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3497",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_get_optimal_voltage",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585278310,
      "name": "regulator_get_optimal_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3497",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_get_optimal_voltage",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585597638,
      "name": "regulator_get_optimal_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3497",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_get_optimal_voltage",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585705766,
      "name": "regulator_get_optimal_voltage",
      "external": false,
      "loc": "drivers/regulator/core.c:3497",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int regulator_get_optimal_voltage(struct regulator_dev * rdev, int * current_uV, int * min_uV, int * max_uV, suspend_state_t state, int n_coupled)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int regulator_get_optimal_voltage(struct regulator_dev * rdev, int * current_uV, int * min_uV, int * max_uV, suspend_state_t state, int n_coupled)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int regulator_get_optimal_voltage(struct regulator_dev * rdev, int * current_uV, int * min_uV, int * max_uV, suspend_state_t state, int n_coupled)
```
</details>
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
