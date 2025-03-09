# Function: <code>acpi_read_bit_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_read_bit_register(u32 register_id, u32 * return_value)
```

```json
{
  "name": "acpi_read_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583675712,
      "name": "acpi_read_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:300",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/processor_idle.c:acpi_processor_suspend",
        "drivers/acpi/processor_idle.c:acpi_processor_resume",
        "drivers/acpi/processor_idle.c:acpi_idle_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583675712,
      "name": "acpi_read_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
acpi_status acpi_read_bit_register(u32 register_id, u32 * return_value)
```

```json
{
  "name": "acpi_read_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583999420,
      "name": "acpi_read_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:299",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_save_bm_rld",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/processor_idle.c:acpi_idle_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583999420,
      "name": "acpi_read_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
acpi_status acpi_read_bit_register(u32 register_id, u32 * return_value)
```

```json
{
  "name": "acpi_read_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584140868,
      "name": "acpi_read_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:299",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_save_bm_rld",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/processor_idle.c:acpi_idle_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584140868,
      "name": "acpi_read_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
acpi_status acpi_read_bit_register(u32 register_id, u32 * return_value)
```

```json
{
  "name": "acpi_read_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584208379,
      "name": "acpi_read_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:299",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_save_bm_rld",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/processor_idle.c:acpi_idle_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584208379,
      "name": "acpi_read_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
acpi_status acpi_read_bit_register(u32 register_id, u32 * return_value)
```

```json
{
  "name": "acpi_read_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584538863,
      "name": "acpi_read_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:187",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_save_bm_rld",
        "drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status",
        "drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/processor_idle.c:acpi_idle_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584538863,
      "name": "acpi_read_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
acpi_status acpi_read_bit_register(u32 register_id, u32 * return_value)
```

```json
{
  "name": "acpi_read_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584763342,
      "name": "acpi_read_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:153",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_save_bm_rld",
        "drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status",
        "drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/processor_idle.c:acpi_idle_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584763342,
      "name": "acpi_read_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
acpi_status acpi_read_bit_register(u32 register_id, u32 * return_value)
```

```json
{
  "name": "acpi_read_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584864142,
      "name": "acpi_read_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:153",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_save_bm_rld",
        "drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status",
        "drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/processor_idle.c:acpi_idle_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584864142,
      "name": "acpi_read_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
acpi_status acpi_read_bit_register(u32 register_id, u32 * return_value)
```

```json
{
  "name": "acpi_read_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585067920,
      "name": "acpi_read_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:153",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_save_bm_rld",
        "drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status",
        "drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/processor_idle.c:acpi_idle_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585067920,
      "name": "acpi_read_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
acpi_status acpi_read_bit_register(u32 register_id, u32 * return_value)
```

```json
{
  "name": "acpi_read_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585204254,
      "name": "acpi_read_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:153",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_save_bm_rld",
        "drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status",
        "drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/processor_idle.c:acpi_idle_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585204254,
      "name": "acpi_read_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
acpi_status acpi_read_bit_register(u32 register_id, u32 * return_value)
```

```json
{
  "name": "acpi_read_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585909995,
      "name": "acpi_read_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:153",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_save_bm_rld",
        "drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status",
        "drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status",
        "drivers/acpi/acpica/evxfevnt.c:acpi_disable_event",
        "drivers/acpi/acpica/evxfevnt.c:acpi_enable_event",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/processor_idle.c:acpi_idle_bm_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585909995,
      "name": "acpi_read_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
acpi_status acpi_read_bit_register(u32 register_id, u32 * return_value)
```

```json
{
  "name": "acpi_read_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586031757,
      "name": "acpi_read_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:153",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_save_bm_rld",
        "drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status",
        "drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status",
        "drivers/acpi/acpica/evxfevnt.c:acpi_disable_event",
        "drivers/acpi/acpica/evxfevnt.c:acpi_enable_event",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/processor_idle.c:acpi_idle_bm_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586031757,
      "name": "acpi_read_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
acpi_status acpi_read_bit_register(u32 register_id, u32 * return_value)
```

```json
{
  "name": "acpi_read_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585908778,
      "name": "acpi_read_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:153",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_save_bm_rld",
        "drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status",
        "drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status",
        "drivers/acpi/acpica/evxfevnt.c:acpi_disable_event",
        "drivers/acpi/acpica/evxfevnt.c:acpi_enable_event",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585908778,
      "name": "acpi_read_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
acpi_status acpi_read_bit_register(u32 register_id, u32 * return_value)
```

```json
{
  "name": "acpi_read_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586396747,
      "name": "acpi_read_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:153",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_save_bm_rld",
        "drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status",
        "drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status",
        "drivers/acpi/acpica/evxfevnt.c:acpi_disable_event",
        "drivers/acpi/acpica/evxfevnt.c:acpi_enable_event",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586396747,
      "name": "acpi_read_bit_register",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_read_bit_register(u32 register_id, u32 * return_value)
```

```json
{
  "name": "acpi_read_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587645862,
      "name": "acpi_read_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:153",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_save_bm_rld",
        "drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status",
        "drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status",
        "drivers/acpi/acpica/evxfevnt.c:acpi_disable_event",
        "drivers/acpi/acpica/evxfevnt.c:acpi_enable_event",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state_s4bios",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587645862,
      "name": "acpi_read_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
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
acpi_status acpi_read_bit_register(u32 register_id, u32 * return_value)
```

```json
{
  "name": "acpi_read_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_read_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:153",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_save_bm_rld",
        "drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status",
        "drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status",
        "drivers/acpi/acpica/evxfevnt.c:acpi_disable_event",
        "drivers/acpi/acpica/evxfevnt.c:acpi_enable_event",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state_s4bios",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596221089,
      "name": "acpi_read_bit_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071588948288,
      "name": "acpi_read_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
acpi_status acpi_read_bit_register(u32 register_id, u32 * return_value)
```

```json
{
  "name": "acpi_read_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_read_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:153",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_save_bm_rld",
        "drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status",
        "drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status",
        "drivers/acpi/acpica/evxfevnt.c:acpi_disable_event",
        "drivers/acpi/acpica/evxfevnt.c:acpi_enable_event",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state_s4bios",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596747669,
      "name": "acpi_read_bit_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071589238256,
      "name": "acpi_read_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
acpi_status acpi_read_bit_register(u32 register_id, u32 * return_value)
```

```json
{
  "name": "acpi_read_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_read_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:153",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_save_bm_rld",
        "drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status",
        "drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status",
        "drivers/acpi/acpica/evxfevnt.c:acpi_disable_event",
        "drivers/acpi/acpica/evxfevnt.c:acpi_enable_event",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state_s4bios",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597656297,
      "name": "acpi_read_bit_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071589544768,
      "name": "acpi_read_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
acpi_status acpi_read_bit_register(u32 register_id, u32 * return_value)
```

```json
{
  "name": "acpi_read_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585077134,
      "name": "acpi_read_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:153",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_save_bm_rld",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/processor_idle.c:acpi_idle_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585077134,
      "name": "acpi_read_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
acpi_status acpi_read_bit_register(u32 register_id, u32 * return_value)
```

```json
{
  "name": "acpi_read_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584992565,
      "name": "acpi_read_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:153",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_save_bm_rld",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/processor_idle.c:acpi_idle_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584992565,
      "name": "acpi_read_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
acpi_status acpi_read_bit_register(u32 register_id, u32 * return_value)
```

```json
{
  "name": "acpi_read_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585155838,
      "name": "acpi_read_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:153",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_save_bm_rld",
        "drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status",
        "drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/processor_idle.c:acpi_idle_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585155838,
      "name": "acpi_read_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
acpi_status acpi_read_bit_register(u32 register_id, u32 * return_value)
```

```json
{
  "name": "acpi_read_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585261998,
      "name": "acpi_read_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:153",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_save_bm_rld",
        "drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status",
        "drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/processor_idle.c:acpi_idle_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585261998,
      "name": "acpi_read_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
acpi_status acpi_read_bit_register(u32 register_id, u32 * return_value)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
acpi_status acpi_read_bit_register(u32 register_id, u32 * return_value)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_read_bit_register(u32 register_id, u32 * return_value)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_read_bit_register(u32 register_id, u32 * return_value)
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
