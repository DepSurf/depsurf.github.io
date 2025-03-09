# Function: <code>acpi_ev_get_gpe_event_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct acpi_gpe_event_info * acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_get_gpe_event_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583629640,
      "name": "acpi_ev_get_gpe_event_info",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:272",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583629640,
      "name": "acpi_ev_get_gpe_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
struct acpi_gpe_event_info * acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_get_gpe_event_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583952703,
      "name": "acpi_ev_get_gpe_event_info",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:272",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583952703,
      "name": "acpi_ev_get_gpe_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct acpi_gpe_event_info * acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_get_gpe_event_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584094366,
      "name": "acpi_ev_get_gpe_event_info",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:326",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584094366,
      "name": "acpi_ev_get_gpe_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct acpi_gpe_event_info * acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_get_gpe_event_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584161142,
      "name": "acpi_ev_get_gpe_event_info",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:326",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584161142,
      "name": "acpi_ev_get_gpe_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct acpi_gpe_event_info * acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_get_gpe_event_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584455792,
      "name": "acpi_ev_get_gpe_event_info",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:326",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584455792,
      "name": "acpi_ev_get_gpe_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct acpi_gpe_event_info * acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_get_gpe_event_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584679792,
      "name": "acpi_ev_get_gpe_event_info",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:285",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584679792,
      "name": "acpi_ev_get_gpe_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct acpi_gpe_event_info * acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_get_gpe_event_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584779770,
      "name": "acpi_ev_get_gpe_event_info",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:285",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584779770,
      "name": "acpi_ev_get_gpe_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct acpi_gpe_event_info * acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_get_gpe_event_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584982399,
      "name": "acpi_ev_get_gpe_event_info",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:291",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584982399,
      "name": "acpi_ev_get_gpe_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct acpi_gpe_event_info * acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_get_gpe_event_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585118399,
      "name": "acpi_ev_get_gpe_event_info",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:291",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585118399,
      "name": "acpi_ev_get_gpe_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct acpi_gpe_event_info * acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_get_gpe_event_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585823202,
      "name": "acpi_ev_get_gpe_event_info",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:291",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585823202,
      "name": "acpi_ev_get_gpe_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct acpi_gpe_event_info * acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_get_gpe_event_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585944024,
      "name": "acpi_ev_get_gpe_event_info",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:291",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585944024,
      "name": "acpi_ev_get_gpe_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct acpi_gpe_event_info * acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_get_gpe_event_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585821274,
      "name": "acpi_ev_get_gpe_event_info",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:291",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585821274,
      "name": "acpi_ev_get_gpe_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct acpi_gpe_event_info * acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_get_gpe_event_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586307745,
      "name": "acpi_ev_get_gpe_event_info",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:291",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586307745,
      "name": "acpi_ev_get_gpe_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
struct acpi_gpe_event_info * acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_get_gpe_event_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587553110,
      "name": "acpi_ev_get_gpe_event_info",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:291",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587553110,
      "name": "acpi_ev_get_gpe_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
struct acpi_gpe_event_info * acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_get_gpe_event_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588836736,
      "name": "acpi_ev_get_gpe_event_info",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:291",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588836736,
      "name": "acpi_ev_get_gpe_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
struct acpi_gpe_event_info * acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_get_gpe_event_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589126080,
      "name": "acpi_ev_get_gpe_event_info",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:291",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589126080,
      "name": "acpi_ev_get_gpe_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
struct acpi_gpe_event_info * acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_get_gpe_event_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589431952,
      "name": "acpi_ev_get_gpe_event_info",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:291",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589431952,
      "name": "acpi_ev_get_gpe_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct acpi_gpe_event_info * acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_get_gpe_event_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585028437,
      "name": "acpi_ev_get_gpe_event_info",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:291",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585028437,
      "name": "acpi_ev_get_gpe_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct acpi_gpe_event_info * acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_get_gpe_event_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584944060,
      "name": "acpi_ev_get_gpe_event_info",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:291",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584944060,
      "name": "acpi_ev_get_gpe_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct acpi_gpe_event_info * acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_get_gpe_event_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585069983,
      "name": "acpi_ev_get_gpe_event_info",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:291",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585069983,
      "name": "acpi_ev_get_gpe_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct acpi_gpe_event_info * acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_get_gpe_event_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585176143,
      "name": "acpi_ev_get_gpe_event_info",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:291",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585176143,
      "name": "acpi_ev_get_gpe_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct acpi_gpe_event_info * acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct acpi_gpe_event_info * acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct acpi_gpe_event_info * acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct acpi_gpe_event_info * acpi_ev_get_gpe_event_info(acpi_handle gpe_device, u32 gpe_number)
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
