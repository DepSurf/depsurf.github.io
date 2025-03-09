# Function: <code>acpi_write_bit_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_write_bit_register(u32 register_id, u32 value)
```

```json
{
  "name": "acpi_write_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583675824,
      "name": "acpi_write_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:361",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/processor_idle.c:acpi_processor_resume",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583675824,
      "name": "acpi_write_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
acpi_status acpi_write_bit_register(u32 register_id, u32 value)
```

```json
{
  "name": "acpi_write_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583999532,
      "name": "acpi_write_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:360",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583999532,
      "name": "acpi_write_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
acpi_status acpi_write_bit_register(u32 register_id, u32 value)
```

```json
{
  "name": "acpi_write_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584140980,
      "name": "acpi_write_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:360",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584140980,
      "name": "acpi_write_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
acpi_status acpi_write_bit_register(u32 register_id, u32 value)
```

```json
{
  "name": "acpi_write_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584208491,
      "name": "acpi_write_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:360",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584208491,
      "name": "acpi_write_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
acpi_status acpi_write_bit_register(u32 register_id, u32 value)
```

```json
{
  "name": "acpi_write_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584539217,
      "name": "acpi_write_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:248",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584539217,
      "name": "acpi_write_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
acpi_status acpi_write_bit_register(u32 register_id, u32 value)
```

```json
{
  "name": "acpi_write_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584763696,
      "name": "acpi_write_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:214",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584763696,
      "name": "acpi_write_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
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
acpi_status acpi_write_bit_register(u32 register_id, u32 value)
```

```json
{
  "name": "acpi_write_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584864491,
      "name": "acpi_write_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:214",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584864491,
      "name": "acpi_write_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 414
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
acpi_status acpi_write_bit_register(u32 register_id, u32 value)
```

```json
{
  "name": "acpi_write_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585068269,
      "name": "acpi_write_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:214",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585068269,
      "name": "acpi_write_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
acpi_status acpi_write_bit_register(u32 register_id, u32 value)
```

```json
{
  "name": "acpi_write_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585204603,
      "name": "acpi_write_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:214",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585204603,
      "name": "acpi_write_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
acpi_status acpi_write_bit_register(u32 register_id, u32 value)
```

```json
{
  "name": "acpi_write_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585910344,
      "name": "acpi_write_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:214",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evxfevnt.c:acpi_clear_event",
        "drivers/acpi/acpica/evxfevnt.c:acpi_disable_event",
        "drivers/acpi/acpica/evxfevnt.c:acpi_enable_event",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_bm_check",
        "drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585910344,
      "name": "acpi_write_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
acpi_status acpi_write_bit_register(u32 register_id, u32 value)
```

```json
{
  "name": "acpi_write_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586032106,
      "name": "acpi_write_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:214",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evxfevnt.c:acpi_clear_event",
        "drivers/acpi/acpica/evxfevnt.c:acpi_disable_event",
        "drivers/acpi/acpica/evxfevnt.c:acpi_enable_event",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_bm_check",
        "drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586032106,
      "name": "acpi_write_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
acpi_status acpi_write_bit_register(u32 register_id, u32 value)
```

```json
{
  "name": "acpi_write_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585909127,
      "name": "acpi_write_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:214",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evxfevnt.c:acpi_clear_event",
        "drivers/acpi/acpica/evxfevnt.c:acpi_disable_event",
        "drivers/acpi/acpica/evxfevnt.c:acpi_enable_event",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585909127,
      "name": "acpi_write_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
acpi_status acpi_write_bit_register(u32 register_id, u32 value)
```

```json
{
  "name": "acpi_write_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586397126,
      "name": "acpi_write_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:214",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evxfevnt.c:acpi_clear_event",
        "drivers/acpi/acpica/evxfevnt.c:acpi_disable_event",
        "drivers/acpi/acpica/evxfevnt.c:acpi_enable_event",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586397126,
      "name": "acpi_write_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
acpi_status acpi_write_bit_register(u32 register_id, u32 value)
```

```json
{
  "name": "acpi_write_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587646264,
      "name": "acpi_write_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:214",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evxfevnt.c:acpi_clear_event",
        "drivers/acpi/acpica/evxfevnt.c:acpi_disable_event",
        "drivers/acpi/acpica/evxfevnt.c:acpi_enable_event",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state_s4bios",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587646264,
      "name": "acpi_write_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 492
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
acpi_status acpi_write_bit_register(u32 register_id, u32 value)
```

```json
{
  "name": "acpi_write_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_write_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:214",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evxfevnt.c:acpi_clear_event",
        "drivers/acpi/acpica/evxfevnt.c:acpi_disable_event",
        "drivers/acpi/acpica/evxfevnt.c:acpi_enable_event",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state_s4bios",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596221122,
      "name": "acpi_write_bit_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071588948720,
      "name": "acpi_write_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 493
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
acpi_status acpi_write_bit_register(u32 register_id, u32 value)
```

```json
{
  "name": "acpi_write_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_write_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:214",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evxfevnt.c:acpi_clear_event",
        "drivers/acpi/acpica/evxfevnt.c:acpi_disable_event",
        "drivers/acpi/acpica/evxfevnt.c:acpi_enable_event",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state_s4bios",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596747702,
      "name": "acpi_write_bit_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071589238688,
      "name": "acpi_write_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 492
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
acpi_status acpi_write_bit_register(u32 register_id, u32 value)
```

```json
{
  "name": "acpi_write_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_write_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:214",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evxfevnt.c:acpi_clear_event",
        "drivers/acpi/acpica/evxfevnt.c:acpi_disable_event",
        "drivers/acpi/acpica/evxfevnt.c:acpi_enable_event",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state_s4bios",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597656330,
      "name": "acpi_write_bit_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071589545200,
      "name": "acpi_write_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 492
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
acpi_status acpi_write_bit_register(u32 register_id, u32 value)
```

```json
{
  "name": "acpi_write_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585077246,
      "name": "acpi_write_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:214",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585077246,
      "name": "acpi_write_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
acpi_status acpi_write_bit_register(u32 register_id, u32 value)
```

```json
{
  "name": "acpi_write_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584992677,
      "name": "acpi_write_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:214",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584992677,
      "name": "acpi_write_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
acpi_status acpi_write_bit_register(u32 register_id, u32 value)
```

```json
{
  "name": "acpi_write_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585156187,
      "name": "acpi_write_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:214",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585156187,
      "name": "acpi_write_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
acpi_status acpi_write_bit_register(u32 register_id, u32 value)
```

```json
{
  "name": "acpi_write_bit_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585262347,
      "name": "acpi_write_bit_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:214",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_restore_bm_rld",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585262347,
      "name": "acpi_write_bit_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
acpi_status acpi_write_bit_register(u32 register_id, u32 value)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
acpi_status acpi_write_bit_register(u32 register_id, u32 value)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_write_bit_register(u32 register_id, u32 value)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_write_bit_register(u32 register_id, u32 value)
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
