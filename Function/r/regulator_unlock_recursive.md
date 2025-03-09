# Function: <code>regulator_unlock_recursive</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void regulator_unlock_recursive(struct regulator_dev * rdev, unsigned int n_coupled)
```

```json
{
  "name": "regulator_unlock_recursive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585272256,
      "name": "regulator_unlock_recursive",
      "external": false,
      "loc": "drivers/regulator/core.c:253",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_get_voltage",
        "drivers/regulator/core.c:regulator_set_suspend_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:regulator_disable",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/regulator/core.c:regulator_unlock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585272256,
      "name": "regulator_unlock_recursive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_unlock_recursive",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585485712,
      "name": "regulator_unlock_recursive",
      "external": false,
      "loc": "drivers/regulator/core.c:235",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_get_voltage",
        "drivers/regulator/core.c:regulator_set_suspend_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:regulator_disable",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585485712,
      "name": "regulator_unlock_recursive.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
  "name": "regulator_unlock_recursive",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585626304,
      "name": "regulator_unlock_recursive",
      "external": false,
      "loc": "drivers/regulator/core.c:235",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_get_voltage",
        "drivers/regulator/core.c:regulator_set_suspend_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:regulator_disable",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585626304,
      "name": "regulator_unlock_recursive.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void regulator_unlock_recursive(struct regulator_dev * rdev, unsigned int n_coupled)
```

```json
{
  "name": "regulator_unlock_recursive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586346752,
      "name": "regulator_unlock_recursive",
      "external": false,
      "loc": "drivers/regulator/core.c:235",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:regulator_set_suspend_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:set_machine_constraints",
        "drivers/regulator/core.c:drms_uA_update",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/regulator/core.c:regulator_unlock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586346752,
      "name": "regulator_unlock_recursive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
void regulator_unlock_recursive(struct regulator_dev * rdev, unsigned int n_coupled)
```

```json
{
  "name": "regulator_unlock_recursive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586465088,
      "name": "regulator_unlock_recursive",
      "external": false,
      "loc": "drivers/regulator/core.c:234",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:regulator_set_suspend_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:set_machine_constraints",
        "drivers/regulator/core.c:drms_uA_update",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/regulator/core.c:regulator_unlock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586465088,
      "name": "regulator_unlock_recursive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
void regulator_unlock_recursive(struct regulator_dev * rdev, unsigned int n_coupled)
```

```json
{
  "name": "regulator_unlock_recursive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586348768,
      "name": "regulator_unlock_recursive",
      "external": false,
      "loc": "drivers/regulator/core.c:234",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:regulator_set_suspend_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:set_machine_constraints",
        "drivers/regulator/core.c:drms_uA_update",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/regulator/core.c:regulator_unlock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586348768,
      "name": "regulator_unlock_recursive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
void regulator_unlock_recursive(struct regulator_dev * rdev, unsigned int n_coupled)
```

```json
{
  "name": "regulator_unlock_recursive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586876704,
      "name": "regulator_unlock_recursive",
      "external": false,
      "loc": "drivers/regulator/core.c:224",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:regulator_set_suspend_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:set_machine_constraints",
        "drivers/regulator/core.c:drms_uA_update",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/regulator/core.c:regulator_unlock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586876704,
      "name": "regulator_unlock_recursive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
void regulator_unlock_recursive(struct regulator_dev * rdev, unsigned int n_coupled)
```

```json
{
  "name": "regulator_unlock_recursive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588164672,
      "name": "regulator_unlock_recursive",
      "external": false,
      "loc": "drivers/regulator/core.c:225",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:regulator_set_suspend_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:set_machine_constraints",
        "drivers/regulator/core.c:drms_uA_update",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/regulator/core.c:regulator_unlock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588164672,
      "name": "regulator_unlock_recursive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
void regulator_unlock_recursive(struct regulator_dev * rdev, unsigned int n_coupled)
```

```json
{
  "name": "regulator_unlock_recursive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589561712,
      "name": "regulator_unlock_recursive",
      "external": false,
      "loc": "drivers/regulator/core.c:225",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:regulator_set_suspend_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:set_machine_constraints",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/regulator/core.c:regulator_unlock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589561712,
      "name": "regulator_unlock_recursive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
void regulator_unlock_recursive(struct regulator_dev * rdev, unsigned int n_coupled)
```

```json
{
  "name": "regulator_unlock_recursive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589863744,
      "name": "regulator_unlock_recursive",
      "external": false,
      "loc": "drivers/regulator/core.c:290",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:regulator_set_suspend_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:set_machine_constraints",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/regulator/core.c:regulator_unlock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589863744,
      "name": "regulator_unlock_recursive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
void regulator_unlock_recursive(struct regulator_dev * rdev, unsigned int n_coupled)
```

```json
{
  "name": "regulator_unlock_recursive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590201120,
      "name": "regulator_unlock_recursive",
      "external": false,
      "loc": "drivers/regulator/core.c:292",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:regulator_set_suspend_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:set_machine_constraints",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/regulator/core.c:regulator_unlock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590201120,
      "name": "regulator_unlock_recursive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
  "name": "regulator_unlock_recursive",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498285176,
      "name": "regulator_unlock_recursive",
      "external": false,
      "loc": "drivers/regulator/core.c:235",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_get_voltage",
        "drivers/regulator/core.c:regulator_set_suspend_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:regulator_disable",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498285176,
      "name": "regulator_unlock_recursive.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
void regulator_unlock_recursive(struct regulator_dev * rdev, unsigned int n_coupled)
```

```json
{
  "name": "regulator_unlock_recursive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230962384,
      "name": "regulator_unlock_recursive",
      "external": false,
      "loc": "drivers/regulator/core.c:235",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_get_voltage",
        "drivers/regulator/core.c:regulator_set_suspend_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:regulator_disable",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/regulator/core.c:regulator_unlock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230962384,
      "name": "regulator_unlock_recursive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void regulator_unlock_recursive(struct regulator_dev * rdev, unsigned int n_coupled)
```

```json
{
  "name": "regulator_unlock_recursive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291440736,
      "name": "regulator_unlock_recursive",
      "external": false,
      "loc": "drivers/regulator/core.c:235",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_get_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:regulator_disable",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/regulator/core.c:regulator_unlock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291440736,
      "name": "regulator_unlock_recursive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
void regulator_unlock_recursive(struct regulator_dev * rdev, unsigned int n_coupled)
```

```json
{
  "name": "regulator_unlock_recursive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275978850,
      "name": "regulator_unlock_recursive",
      "external": false,
      "loc": "drivers/regulator/core.c:235",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_get_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:regulator_disable",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/regulator/core.c:regulator_unlock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275978850,
      "name": "regulator_unlock_recursive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_unlock_recursive",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585387952,
      "name": "regulator_unlock_recursive",
      "external": false,
      "loc": "drivers/regulator/core.c:235",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_get_voltage",
        "drivers/regulator/core.c:regulator_set_suspend_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:regulator_disable",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585387952,
      "name": "regulator_unlock_recursive.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_unlock_recursive",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585257376,
      "name": "regulator_unlock_recursive",
      "external": false,
      "loc": "drivers/regulator/core.c:235",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_get_voltage",
        "drivers/regulator/core.c:regulator_set_suspend_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:regulator_disable",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585257376,
      "name": "regulator_unlock_recursive.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_unlock_recursive",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585576704,
      "name": "regulator_unlock_recursive",
      "external": false,
      "loc": "drivers/regulator/core.c:235",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_get_voltage",
        "drivers/regulator/core.c:regulator_set_suspend_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:regulator_disable",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585576704,
      "name": "regulator_unlock_recursive.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_unlock_recursive",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585684672,
      "name": "regulator_unlock_recursive",
      "external": false,
      "loc": "drivers/regulator/core.c:235",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_get_voltage",
        "drivers/regulator/core.c:regulator_set_suspend_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:regulator_disable",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585684672,
      "name": "regulator_unlock_recursive.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void regulator_unlock_recursive(struct regulator_dev * rdev, unsigned int n_coupled)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void regulator_unlock_recursive(struct regulator_dev * rdev, unsigned int n_coupled)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void regulator_unlock_recursive(struct regulator_dev * rdev, unsigned int n_coupled)
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void regulator_unlock_recursive(struct regulator_dev * rdev, unsigned int n_coupled)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void regulator_unlock_recursive(struct regulator_dev * rdev, unsigned int n_coupled)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void regulator_unlock_recursive(struct regulator_dev * rdev, unsigned int n_coupled)
```
</details>
</li>
</ul>
