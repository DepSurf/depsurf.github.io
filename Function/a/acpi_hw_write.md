# Function: <code>acpi_hw_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_hw_write(u32 value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583673356,
      "name": "acpi_hw_write",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:212",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_runtime_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_wakeup_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583673356,
      "name": "acpi_hw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
acpi_status acpi_hw_write(u32 value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583997030,
      "name": "acpi_hw_write",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:306",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_wakeup_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_runtime_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583997030,
      "name": "acpi_hw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
acpi_status acpi_hw_write(u32 value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584138478,
      "name": "acpi_hw_write",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:306",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_wakeup_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_runtime_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584138478,
      "name": "acpi_hw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
acpi_status acpi_hw_write(u32 value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584205615,
      "name": "acpi_hw_write",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:327",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_wakeup_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_runtime_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584205615,
      "name": "acpi_hw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584535012,
      "name": "acpi_hw_write",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:326",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_wakeup_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_runtime_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwxface.c:acpi_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584535012,
      "name": "acpi_hw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584759340,
      "name": "acpi_hw_write",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:290",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_wakeup_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_runtime_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwxface.c:acpi_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584759340,
      "name": "acpi_hw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584860100,
      "name": "acpi_hw_write",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:290",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_wakeup_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_runtime_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwxface.c:acpi_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584860100,
      "name": "acpi_hw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585063855,
      "name": "acpi_hw_write",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:290",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_wakeup_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_runtime_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwxface.c:acpi_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585063855,
      "name": "acpi_hw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
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
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585200189,
      "name": "acpi_hw_write",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:290",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_wakeup_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_runtime_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwxface.c:acpi_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585200189,
      "name": "acpi_hw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
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
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585905706,
      "name": "acpi_hw_write",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:290",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_gpe_enable_write",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwxface.c:acpi_write",
        "drivers/acpi/acpica/hwxface.c:acpi_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585905706,
      "name": "acpi_hw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586027320,
      "name": "acpi_hw_write",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:290",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwxface.c:acpi_write",
        "drivers/acpi/acpica/hwxface.c:acpi_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586027320,
      "name": "acpi_hw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585904331,
      "name": "acpi_hw_write",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:290",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwxface.c:acpi_write",
        "drivers/acpi/acpica/hwxface.c:acpi_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585904331,
      "name": "acpi_hw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 386
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
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586392012,
      "name": "acpi_hw_write",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:290",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwxface.c:acpi_write",
        "drivers/acpi/acpica/hwxface.c:acpi_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586392012,
      "name": "acpi_hw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 461
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
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587640854,
      "name": "acpi_hw_write",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:290",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwxface.c:acpi_write",
        "drivers/acpi/acpica/hwxface.c:acpi_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587640854,
      "name": "acpi_hw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 486
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
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_hw_write",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:290",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status",
        "drivers/acpi/acpica/hwxface.c:acpi_write",
        "drivers/acpi/acpica/hwxface.c:acpi_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596220812,
      "name": "acpi_hw_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071588941904,
      "name": "acpi_hw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 509
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
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_hw_write",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:290",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status",
        "drivers/acpi/acpica/hwxface.c:acpi_write",
        "drivers/acpi/acpica/hwxface.c:acpi_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596747392,
      "name": "acpi_hw_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071589231920,
      "name": "acpi_hw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 509
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
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_hw_write",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:290",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status",
        "drivers/acpi/acpica/hwxface.c:acpi_write",
        "drivers/acpi/acpica/hwxface.c:acpi_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597656020,
      "name": "acpi_hw_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071589538432,
      "name": "acpi_hw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 509
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
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497541096,
      "name": "acpi_hw_write",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:290",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwxface.c:acpi_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497541096,
      "name": "acpi_hw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585074601,
      "name": "acpi_hw_write",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:290",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_wakeup_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_runtime_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwxface.c:acpi_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585074601,
      "name": "acpi_hw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584990075,
      "name": "acpi_hw_write",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:290",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_wakeup_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_runtime_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwxface.c:acpi_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584990075,
      "name": "acpi_hw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585151773,
      "name": "acpi_hw_write",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:290",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_wakeup_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_runtime_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwxface.c:acpi_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585151773,
      "name": "acpi_hw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
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
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585257933,
      "name": "acpi_hw_write",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:290",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_wakeup_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_runtime_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_gpe_block",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write_pm1_control",
        "drivers/acpi/acpica/hwxface.c:acpi_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585257933,
      "name": "acpi_hw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u32 value</code> ➡️ <code>u64 value</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address * reg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address * reg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_hw_write(u64 value, struct acpi_generic_address * reg)
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
