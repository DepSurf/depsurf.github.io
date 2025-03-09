# Function: <code>__suspend_set_state</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int __suspend_set_state(struct regulator_dev * rdev, const struct regulator_state * rstate)
```

```json
{
  "name": "__suspend_set_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__suspend_set_state",
      "external": false,
      "loc": "drivers/regulator/core.c:1012",
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
      "addr": 18446744071586484464,
      "name": "__suspend_set_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    },
    {
      "addr": 18446744071591454748,
      "name": "__suspend_set_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
int __suspend_set_state(struct regulator_dev * rdev, const struct regulator_state * rstate)
```

```json
{
  "name": "__suspend_set_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__suspend_set_state",
      "external": false,
      "loc": "drivers/regulator/core.c:1014",
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
      "addr": 18446744071586367904,
      "name": "__suspend_set_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    },
    {
      "addr": 18446744071591396541,
      "name": "__suspend_set_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
int __suspend_set_state(struct regulator_dev * rdev, const struct regulator_state * rstate)
```

```json
{
  "name": "__suspend_set_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__suspend_set_state",
      "external": false,
      "loc": "drivers/regulator/core.c:994",
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
      "addr": 18446744071586871456,
      "name": "__suspend_set_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    },
    {
      "addr": 18446744071592440784,
      "name": "__suspend_set_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
int __suspend_set_state(struct regulator_dev * rdev, const struct regulator_state * rstate)
```

```json
{
  "name": "__suspend_set_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__suspend_set_state",
      "external": false,
      "loc": "drivers/regulator/core.c:1019",
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
      "addr": 18446744071588159696,
      "name": "__suspend_set_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
    },
    {
      "addr": 18446744071594309028,
      "name": "__suspend_set_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
int __suspend_set_state(struct regulator_dev * rdev, const struct regulator_state * rstate)
```

```json
{
  "name": "__suspend_set_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589572176,
      "name": "__suspend_set_state",
      "external": false,
      "loc": "drivers/regulator/core.c:1037",
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
      "addr": 18446744071589572176,
      "name": "__suspend_set_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
int __suspend_set_state(struct regulator_dev * rdev, const struct regulator_state * rstate)
```

```json
{
  "name": "__suspend_set_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589874896,
      "name": "__suspend_set_state",
      "external": false,
      "loc": "drivers/regulator/core.c:1103",
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
      "addr": 18446744071589874896,
      "name": "__suspend_set_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
int __suspend_set_state(struct regulator_dev * rdev, const struct regulator_state * rstate)
```

```json
{
  "name": "__suspend_set_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590212784,
      "name": "__suspend_set_state",
      "external": false,
      "loc": "drivers/regulator/core.c:1105",
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
      "addr": 18446744071590212784,
      "name": "__suspend_set_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
int __suspend_set_state(struct regulator_dev * rdev, const struct regulator_state * rstate)
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
