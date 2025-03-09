# Function: <code>acpi_hw_low_set_gpe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info * gpe_event_info, u32 action)
```

```json
{
  "name": "acpi_hw_low_set_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583671858,
      "name": "acpi_hw_low_set_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/hwgpe.c:98",
      "file": "drivers/acpi/acpica/hwgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_finish_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583671858,
      "name": "acpi_hw_low_set_gpe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info * gpe_event_info, u32 action)
```

```json
{
  "name": "acpi_hw_low_set_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583995197,
      "name": "acpi_hw_low_set_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/hwgpe.c:98",
      "file": "drivers/acpi/acpica/hwgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_finish_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583995197,
      "name": "acpi_hw_low_set_gpe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info * gpe_event_info, u32 action)
```

```json
{
  "name": "acpi_hw_low_set_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584136598,
      "name": "acpi_hw_low_set_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/hwgpe.c:98",
      "file": "drivers/acpi/acpica/hwgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_finish_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584136598,
      "name": "acpi_hw_low_set_gpe",
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
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info * gpe_event_info, u32 action)
```

```json
{
  "name": "acpi_hw_low_set_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584203723,
      "name": "acpi_hw_low_set_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/hwgpe.c:98",
      "file": "drivers/acpi/acpica/hwgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_finish_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584203723,
      "name": "acpi_hw_low_set_gpe",
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
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info * gpe_event_info, u32 action)
```

```json
{
  "name": "acpi_hw_low_set_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584532464,
      "name": "acpi_hw_low_set_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/hwgpe.c:98",
      "file": "drivers/acpi/acpica/hwgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_finish_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584532464,
      "name": "acpi_hw_low_set_gpe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info * gpe_event_info, u32 action)
```

```json
{
  "name": "acpi_hw_low_set_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584756743,
      "name": "acpi_hw_low_set_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/hwgpe.c:64",
      "file": "drivers/acpi/acpica/hwgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_finish_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_enable_gpe",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584756743,
      "name": "acpi_hw_low_set_gpe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info * gpe_event_info, u32 action)
```

```json
{
  "name": "acpi_hw_low_set_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584858322,
      "name": "acpi_hw_low_set_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/hwgpe.c:64",
      "file": "drivers/acpi/acpica/hwgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_finish_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_enable_gpe",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584858322,
      "name": "acpi_hw_low_set_gpe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info * gpe_event_info, u32 action)
```

```json
{
  "name": "acpi_hw_low_set_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585062066,
      "name": "acpi_hw_low_set_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/hwgpe.c:64",
      "file": "drivers/acpi/acpica/hwgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_finish_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_enable_gpe",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585062066,
      "name": "acpi_hw_low_set_gpe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info * gpe_event_info, u32 action)
```

```json
{
  "name": "acpi_hw_low_set_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585198294,
      "name": "acpi_hw_low_set_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/hwgpe.c:64",
      "file": "drivers/acpi/acpica/hwgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_finish_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_enable_gpe",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585198294,
      "name": "acpi_hw_low_set_gpe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info * gpe_event_info, u32 action)
```

```json
{
  "name": "acpi_hw_low_set_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585903689,
      "name": "acpi_hw_low_set_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/hwgpe.c:64",
      "file": "drivers/acpi/acpica/hwgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_finish_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_enable_gpe",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585903689,
      "name": "acpi_hw_low_set_gpe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info * gpe_event_info, u32 action)
```

```json
{
  "name": "acpi_hw_low_set_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586025303,
      "name": "acpi_hw_low_set_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/hwgpe.c:134",
      "file": "drivers/acpi/acpica/hwgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_finish_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_enable_gpe",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586025303,
      "name": "acpi_hw_low_set_gpe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info * gpe_event_info, u32 action)
```

```json
{
  "name": "acpi_hw_low_set_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585902319,
      "name": "acpi_hw_low_set_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/hwgpe.c:134",
      "file": "drivers/acpi/acpica/hwgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_finish_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_enable_gpe",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585902319,
      "name": "acpi_hw_low_set_gpe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info * gpe_event_info, u32 action)
```

```json
{
  "name": "acpi_hw_low_set_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586389846,
      "name": "acpi_hw_low_set_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/hwgpe.c:134",
      "file": "drivers/acpi/acpica/hwgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_finish_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_enable_gpe",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586389846,
      "name": "acpi_hw_low_set_gpe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info * gpe_event_info, u32 action)
```

```json
{
  "name": "acpi_hw_low_set_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587638545,
      "name": "acpi_hw_low_set_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/hwgpe.c:134",
      "file": "drivers/acpi/acpica/hwgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_finish_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_enable_gpe",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587638545,
      "name": "acpi_hw_low_set_gpe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info * gpe_event_info, u32 action)
```

```json
{
  "name": "acpi_hw_low_set_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_hw_low_set_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/hwgpe.c:134",
      "file": "drivers/acpi/acpica/hwgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_add_gpe_reference",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596220533,
      "name": "acpi_hw_low_set_gpe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071588938960,
      "name": "acpi_hw_low_set_gpe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info * gpe_event_info, u32 action)
```

```json
{
  "name": "acpi_hw_low_set_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_hw_low_set_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/hwgpe.c:134",
      "file": "drivers/acpi/acpica/hwgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_add_gpe_reference",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596747082,
      "name": "acpi_hw_low_set_gpe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071589228960,
      "name": "acpi_hw_low_set_gpe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
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
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info * gpe_event_info, u32 action)
```

```json
{
  "name": "acpi_hw_low_set_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_hw_low_set_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/hwgpe.c:134",
      "file": "drivers/acpi/acpica/hwgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_add_gpe_reference",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597655710,
      "name": "acpi_hw_low_set_gpe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071589535472,
      "name": "acpi_hw_low_set_gpe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
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
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info * gpe_event_info, u32 action)
```

```json
{
  "name": "acpi_hw_low_set_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585073068,
      "name": "acpi_hw_low_set_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/hwgpe.c:64",
      "file": "drivers/acpi/acpica/hwgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_finish_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_enable_gpe",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585073068,
      "name": "acpi_hw_low_set_gpe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info * gpe_event_info, u32 action)
```

```json
{
  "name": "acpi_hw_low_set_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584988542,
      "name": "acpi_hw_low_set_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/hwgpe.c:64",
      "file": "drivers/acpi/acpica/hwgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_finish_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_enable_gpe",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584988542,
      "name": "acpi_hw_low_set_gpe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info * gpe_event_info, u32 action)
```

```json
{
  "name": "acpi_hw_low_set_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585149878,
      "name": "acpi_hw_low_set_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/hwgpe.c:64",
      "file": "drivers/acpi/acpica/hwgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_finish_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_enable_gpe",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585149878,
      "name": "acpi_hw_low_set_gpe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info * gpe_event_info, u32 action)
```

```json
{
  "name": "acpi_hw_low_set_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585256038,
      "name": "acpi_hw_low_set_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/hwgpe.c:64",
      "file": "drivers/acpi/acpica/hwgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_finish_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_enable_gpe",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585256038,
      "name": "acpi_hw_low_set_gpe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info * gpe_event_info, u32 action)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info * gpe_event_info, u32 action)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info * gpe_event_info, u32 action)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info * gpe_event_info, u32 action)
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
