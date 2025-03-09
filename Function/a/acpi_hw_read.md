# Function: <code>acpi_hw_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_hw_read(u32 * value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583673094,
      "name": "acpi_hw_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:155",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_read",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583673094,
      "name": "acpi_hw_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
acpi_status acpi_hw_read(u32 * value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583996493,
      "name": "acpi_hw_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:197",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583996493,
      "name": "acpi_hw_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 401
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
acpi_status acpi_hw_read(u32 * value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584137941,
      "name": "acpi_hw_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:197",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584137941,
      "name": "acpi_hw_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 401
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
acpi_status acpi_hw_read(u32 * value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584205169,
      "name": "acpi_hw_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:232",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584205169,
      "name": "acpi_hw_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
acpi_status acpi_hw_read(u64 * value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584534459,
      "name": "acpi_hw_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:231",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_read",
        "drivers/acpi/acpica/hwxface.c:acpi_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584534459,
      "name": "acpi_hw_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
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
acpi_status acpi_hw_read(u64 * value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584758787,
      "name": "acpi_hw_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:195",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_read",
        "drivers/acpi/acpica/hwxface.c:acpi_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584758787,
      "name": "acpi_hw_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
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
acpi_status acpi_hw_read(u64 * value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584859547,
      "name": "acpi_hw_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:195",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_read",
        "drivers/acpi/acpica/hwxface.c:acpi_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584859547,
      "name": "acpi_hw_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
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
acpi_status acpi_hw_read(u64 * value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585063297,
      "name": "acpi_hw_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:195",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_read",
        "drivers/acpi/acpica/hwxface.c:acpi_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585063297,
      "name": "acpi_hw_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
acpi_status acpi_hw_read(u64 * value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585199631,
      "name": "acpi_hw_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:195",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_read",
        "drivers/acpi/acpica/hwxface.c:acpi_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585199631,
      "name": "acpi_hw_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
acpi_status acpi_hw_read(u64 * value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585905138,
      "name": "acpi_hw_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:195",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_read",
        "drivers/acpi/acpica/hwxface.c:acpi_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585905138,
      "name": "acpi_hw_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 435
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
acpi_status acpi_hw_read(u64 * value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586026752,
      "name": "acpi_hw_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:195",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_read",
        "drivers/acpi/acpica/hwxface.c:acpi_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586026752,
      "name": "acpi_hw_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 435
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
acpi_status acpi_hw_read(u64 * value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585903759,
      "name": "acpi_hw_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:195",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_read",
        "drivers/acpi/acpica/hwxface.c:acpi_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585903759,
      "name": "acpi_hw_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 439
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
acpi_status acpi_hw_read(u64 * value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586391373,
      "name": "acpi_hw_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:195",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_read",
        "drivers/acpi/acpica/hwxface.c:acpi_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586391373,
      "name": "acpi_hw_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 506
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
acpi_status acpi_hw_read(u64 * value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587640168,
      "name": "acpi_hw_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:195",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_read",
        "drivers/acpi/acpica/hwxface.c:acpi_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587640168,
      "name": "acpi_hw_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
acpi_status acpi_hw_read(u64 * value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_hw_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:195",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_read",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_read",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_read",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_read",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_read",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_read",
        "drivers/acpi/acpica/hwxface.c:acpi_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596220701,
      "name": "acpi_hw_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071588941296,
      "name": "acpi_hw_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 582
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
acpi_status acpi_hw_read(u64 * value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_hw_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:195",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_read",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_read",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_read",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_read",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_read",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_read",
        "drivers/acpi/acpica/hwxface.c:acpi_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596747281,
      "name": "acpi_hw_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071589231312,
      "name": "acpi_hw_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 582
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
acpi_status acpi_hw_read(u64 * value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_hw_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:195",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_read",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_read",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_read",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_read",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_read",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_read",
        "drivers/acpi/acpica/hwxface.c:acpi_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597655909,
      "name": "acpi_hw_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071589537824,
      "name": "acpi_hw_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 582
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
acpi_status acpi_hw_read(u64 * value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497540756,
      "name": "acpi_hw_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:195",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwxface.c:acpi_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497540756,
      "name": "acpi_hw_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
acpi_status acpi_hw_read(u64 * value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585074137,
      "name": "acpi_hw_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:195",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_read",
        "drivers/acpi/acpica/hwxface.c:acpi_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585074137,
      "name": "acpi_hw_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
acpi_status acpi_hw_read(u64 * value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584989611,
      "name": "acpi_hw_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:195",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_read",
        "drivers/acpi/acpica/hwxface.c:acpi_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584989611,
      "name": "acpi_hw_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
acpi_status acpi_hw_read(u64 * value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585151215,
      "name": "acpi_hw_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:195",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_read",
        "drivers/acpi/acpica/hwxface.c:acpi_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585151215,
      "name": "acpi_hw_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
acpi_status acpi_hw_read(u64 * value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_hw_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585257375,
      "name": "acpi_hw_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:195",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read_multiple",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_register_read",
        "drivers/acpi/acpica/hwxface.c:acpi_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585257375,
      "name": "acpi_hw_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
<code>u32 * value</code> ➡️ <code>u64 * value</code>
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
acpi_status acpi_hw_read(u64 * value, struct acpi_generic_address * reg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_hw_read(u64 * value, struct acpi_generic_address * reg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_hw_read(u64 * value, struct acpi_generic_address * reg)
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
