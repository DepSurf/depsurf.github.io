# Function: <code>regulator_lock_dependent</code>

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
void regulator_lock_dependent(struct regulator_dev * rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_dependent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585284096,
      "name": "regulator_lock_dependent",
      "external": false,
      "loc": "drivers/regulator/core.c:346",
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
        "drivers/regulator/core.c:regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585284096,
      "name": "regulator_lock_dependent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
void regulator_lock_dependent(struct regulator_dev * rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_dependent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585492352,
      "name": "regulator_lock_dependent",
      "external": false,
      "loc": "drivers/regulator/core.c:328",
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
        "drivers/regulator/core.c:regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585492352,
      "name": "regulator_lock_dependent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
void regulator_lock_dependent(struct regulator_dev * rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_dependent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585637056,
      "name": "regulator_lock_dependent",
      "external": false,
      "loc": "drivers/regulator/core.c:328",
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
        "drivers/regulator/core.c:regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585637056,
      "name": "regulator_lock_dependent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
void regulator_lock_dependent(struct regulator_dev * rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_dependent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586354352,
      "name": "regulator_lock_dependent",
      "external": false,
      "loc": "drivers/regulator/core.c:331",
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
        "drivers/regulator/core.c:drms_uA_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586354352,
      "name": "regulator_lock_dependent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
void regulator_lock_dependent(struct regulator_dev * rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_dependent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586472032,
      "name": "regulator_lock_dependent",
      "external": false,
      "loc": "drivers/regulator/core.c:330",
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
        "drivers/regulator/core.c:drms_uA_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586472032,
      "name": "regulator_lock_dependent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
void regulator_lock_dependent(struct regulator_dev * rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_dependent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586355824,
      "name": "regulator_lock_dependent",
      "external": false,
      "loc": "drivers/regulator/core.c:330",
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
        "drivers/regulator/core.c:drms_uA_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586355824,
      "name": "regulator_lock_dependent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
void regulator_lock_dependent(struct regulator_dev * rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_dependent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586888752,
      "name": "regulator_lock_dependent",
      "external": false,
      "loc": "drivers/regulator/core.c:320",
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
        "drivers/regulator/core.c:drms_uA_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586888752,
      "name": "regulator_lock_dependent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
void regulator_lock_dependent(struct regulator_dev * rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_dependent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588178320,
      "name": "regulator_lock_dependent",
      "external": false,
      "loc": "drivers/regulator/core.c:321",
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
        "drivers/regulator/core.c:drms_uA_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588178320,
      "name": "regulator_lock_dependent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
void regulator_lock_dependent(struct regulator_dev * rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_dependent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589571792,
      "name": "regulator_lock_dependent",
      "external": false,
      "loc": "drivers/regulator/core.c:321",
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
        "drivers/regulator/core.c:set_machine_constraints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589571792,
      "name": "regulator_lock_dependent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
void regulator_lock_dependent(struct regulator_dev * rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_dependent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589874496,
      "name": "regulator_lock_dependent",
      "external": false,
      "loc": "drivers/regulator/core.c:386",
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
        "drivers/regulator/core.c:set_machine_constraints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589874496,
      "name": "regulator_lock_dependent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
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
void regulator_lock_dependent(struct regulator_dev * rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_dependent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590212384,
      "name": "regulator_lock_dependent",
      "external": false,
      "loc": "drivers/regulator/core.c:388",
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
        "drivers/regulator/core.c:set_machine_constraints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590212384,
      "name": "regulator_lock_dependent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
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
void regulator_lock_dependent(struct regulator_dev * rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_dependent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498292168,
      "name": "regulator_lock_dependent",
      "external": false,
      "loc": "drivers/regulator/core.c:328",
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
        "drivers/regulator/core.c:regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498292168,
      "name": "regulator_lock_dependent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
void regulator_lock_dependent(struct regulator_dev * rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_dependent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230978360,
      "name": "regulator_lock_dependent",
      "external": false,
      "loc": "drivers/regulator/core.c:328",
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
        "drivers/regulator/core.c:regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230978360,
      "name": "regulator_lock_dependent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
void regulator_lock_dependent(struct regulator_dev * rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_dependent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291463040,
      "name": "regulator_lock_dependent",
      "external": false,
      "loc": "drivers/regulator/core.c:328",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_get_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:regulator_disable",
        "drivers/regulator/core.c:regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291463040,
      "name": "regulator_lock_dependent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
void regulator_lock_dependent(struct regulator_dev * rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_dependent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275990778,
      "name": "regulator_lock_dependent",
      "external": false,
      "loc": "drivers/regulator/core.c:328",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_get_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:regulator_disable",
        "drivers/regulator/core.c:regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275990778,
      "name": "regulator_lock_dependent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
void regulator_lock_dependent(struct regulator_dev * rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_dependent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585398208,
      "name": "regulator_lock_dependent",
      "external": false,
      "loc": "drivers/regulator/core.c:328",
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
        "drivers/regulator/core.c:regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585398208,
      "name": "regulator_lock_dependent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
void regulator_lock_dependent(struct regulator_dev * rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_dependent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585268128,
      "name": "regulator_lock_dependent",
      "external": false,
      "loc": "drivers/regulator/core.c:328",
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
        "drivers/regulator/core.c:regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585268128,
      "name": "regulator_lock_dependent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
void regulator_lock_dependent(struct regulator_dev * rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_dependent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585587456,
      "name": "regulator_lock_dependent",
      "external": false,
      "loc": "drivers/regulator/core.c:328",
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
        "drivers/regulator/core.c:regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585587456,
      "name": "regulator_lock_dependent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
void regulator_lock_dependent(struct regulator_dev * rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_dependent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585695584,
      "name": "regulator_lock_dependent",
      "external": false,
      "loc": "drivers/regulator/core.c:328",
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
        "drivers/regulator/core.c:regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585695584,
      "name": "regulator_lock_dependent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
void regulator_lock_dependent(struct regulator_dev * rdev, struct ww_acquire_ctx * ww_ctx)
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
