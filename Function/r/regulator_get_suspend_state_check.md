# Function: <code>regulator_get_suspend_state_check</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct regulator_state * regulator_get_suspend_state_check(struct regulator_dev * rdev, suspend_state_t state)
```

```json
{
  "name": "regulator_get_suspend_state_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586484412,
      "name": "regulator_get_suspend_state_check",
      "external": false,
      "loc": "drivers/regulator/core.c:570",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:set_machine_constraints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586484352,
      "name": "regulator_get_suspend_state_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    },
    {
      "addr": 18446744071591454721,
      "name": "regulator_get_suspend_state_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct regulator_state * regulator_get_suspend_state_check(struct regulator_dev * rdev, suspend_state_t state)
```

```json
{
  "name": "regulator_get_suspend_state_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586367852,
      "name": "regulator_get_suspend_state_check",
      "external": false,
      "loc": "drivers/regulator/core.c:571",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:set_machine_constraints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586367792,
      "name": "regulator_get_suspend_state_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071591396513,
      "name": "regulator_get_suspend_state_check.cold",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct regulator_state * regulator_get_suspend_state_check(struct regulator_dev * rdev, suspend_state_t state)
```

```json
{
  "name": "regulator_get_suspend_state_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586873196,
      "name": "regulator_get_suspend_state_check",
      "external": false,
      "loc": "drivers/regulator/core.c:561",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:set_machine_constraints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586873136,
      "name": "regulator_get_suspend_state_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071592441115,
      "name": "regulator_get_suspend_state_check.cold",
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
const struct regulator_state * regulator_get_suspend_state_check(struct regulator_dev * rdev, suspend_state_t state)
```

```json
{
  "name": "regulator_get_suspend_state_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_get_suspend_state_check",
      "external": false,
      "loc": "drivers/regulator/core.c:562",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:set_machine_constraints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588161536,
      "name": "regulator_get_suspend_state_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    },
    {
      "addr": 18446744071594309355,
      "name": "regulator_get_suspend_state_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
const struct regulator_state * regulator_get_suspend_state_check(struct regulator_dev * rdev, suspend_state_t state)
```

```json
{
  "name": "regulator_get_suspend_state_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589567440,
      "name": "regulator_get_suspend_state_check",
      "external": false,
      "loc": "drivers/regulator/core.c:562",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:set_machine_constraints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589567440,
      "name": "regulator_get_suspend_state_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
const struct regulator_state * regulator_get_suspend_state_check(struct regulator_dev * rdev, suspend_state_t state)
```

```json
{
  "name": "regulator_get_suspend_state_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589869488,
      "name": "regulator_get_suspend_state_check",
      "external": false,
      "loc": "drivers/regulator/core.c:628",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:set_machine_constraints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589869488,
      "name": "regulator_get_suspend_state_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
const struct regulator_state * regulator_get_suspend_state_check(struct regulator_dev * rdev, suspend_state_t state)
```

```json
{
  "name": "regulator_get_suspend_state_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590207328,
      "name": "regulator_get_suspend_state_check",
      "external": false,
      "loc": "drivers/regulator/core.c:630",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:set_machine_constraints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590207328,
      "name": "regulator_get_suspend_state_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
const struct regulator_state * regulator_get_suspend_state_check(struct regulator_dev * rdev, suspend_state_t state)
```
</details>
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
