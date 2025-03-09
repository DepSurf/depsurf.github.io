# Function: <code>acpi_scan_lock_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void acpi_scan_lock_release()
```

```json
{
  "name": "acpi_scan_lock_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583560861,
      "name": "acpi_scan_lock_release",
      "external": true,
      "loc": "drivers/acpi/scan.c:67",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_freeze_end",
        "drivers/acpi/sleep.c:acpi_pm_end",
        "drivers/acpi/dock.c:write_undock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583560861,
      "name": "acpi_scan_lock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void acpi_scan_lock_release()
```

```json
{
  "name": "acpi_scan_lock_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583882534,
      "name": "acpi_scan_lock_release",
      "external": true,
      "loc": "drivers/acpi/scan.c:68",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_freeze_end",
        "drivers/acpi/sleep.c:acpi_pm_end",
        "drivers/acpi/scan.c:acpi_table_events_fn",
        "drivers/acpi/dock.c:write_undock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583882534,
      "name": "acpi_scan_lock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void acpi_scan_lock_release()
```

```json
{
  "name": "acpi_scan_lock_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584021643,
      "name": "acpi_scan_lock_release",
      "external": true,
      "loc": "drivers/acpi/scan.c:69",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_freeze_end",
        "drivers/acpi/sleep.c:acpi_pm_end",
        "drivers/acpi/scan.c:acpi_table_events_fn",
        "drivers/acpi/dock.c:write_undock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584021643,
      "name": "acpi_scan_lock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void acpi_scan_lock_release()
```

```json
{
  "name": "acpi_scan_lock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584086668,
      "name": "acpi_scan_lock_release",
      "external": true,
      "loc": "drivers/acpi/scan.c:63",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_table_events_fn"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_freeze_end",
        "drivers/acpi/sleep.c:acpi_pm_end",
        "drivers/acpi/dock.c:write_undock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584075232,
      "name": "acpi_scan_lock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void acpi_scan_lock_release()
```

```json
{
  "name": "acpi_scan_lock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584357324,
      "name": "acpi_scan_lock_release",
      "external": true,
      "loc": "drivers/acpi/scan.c:64",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_table_events_fn"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_s2idle_end",
        "drivers/acpi/sleep.c:acpi_pm_end",
        "drivers/acpi/dock.c:write_undock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584344864,
      "name": "acpi_scan_lock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void acpi_scan_lock_release()
```

```json
{
  "name": "acpi_scan_lock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584578215,
      "name": "acpi_scan_lock_release",
      "external": true,
      "loc": "drivers/acpi/scan.c:64",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_table_events_fn"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_s2idle_end",
        "drivers/acpi/sleep.c:acpi_pm_end",
        "drivers/acpi/dock.c:write_undock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584565856,
      "name": "acpi_scan_lock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void acpi_scan_lock_release()
```

```json
{
  "name": "acpi_scan_lock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584675559,
      "name": "acpi_scan_lock_release",
      "external": true,
      "loc": "drivers/acpi/scan.c:64",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_table_events_fn"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_s2idle_end",
        "drivers/acpi/sleep.c:acpi_pm_end",
        "drivers/acpi/dock.c:write_undock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584663168,
      "name": "acpi_scan_lock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void acpi_scan_lock_release()
```

```json
{
  "name": "acpi_scan_lock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584875337,
      "name": "acpi_scan_lock_release",
      "external": true,
      "loc": "drivers/acpi/scan.c:65",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_table_events_fn"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_s2idle_end",
        "drivers/acpi/sleep.c:acpi_pm_end",
        "drivers/acpi/dock.c:write_undock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584863328,
      "name": "acpi_scan_lock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void acpi_scan_lock_release()
```

```json
{
  "name": "acpi_scan_lock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585011209,
      "name": "acpi_scan_lock_release",
      "external": true,
      "loc": "drivers/acpi/scan.c:65",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_table_events_fn"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_s2idle_end",
        "drivers/acpi/sleep.c:acpi_pm_end",
        "drivers/acpi/dock.c:write_undock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584999200,
      "name": "acpi_scan_lock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void acpi_scan_lock_release()
```

```json
{
  "name": "acpi_scan_lock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585710843,
      "name": "acpi_scan_lock_release",
      "external": true,
      "loc": "drivers/acpi/scan.c:64",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_table_events_fn"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_s2idle_end",
        "drivers/acpi/sleep.c:acpi_pm_end",
        "drivers/acpi/dock.c:write_undock",
        "drivers/acpi/dock.c:write_undock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585698000,
      "name": "acpi_scan_lock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void acpi_scan_lock_release()
```

```json
{
  "name": "acpi_scan_lock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585833851,
      "name": "acpi_scan_lock_release",
      "external": true,
      "loc": "drivers/acpi/scan.c:64",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_table_events_fn"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_s2idle_end",
        "drivers/acpi/sleep.c:acpi_pm_end",
        "drivers/acpi/dock.c:write_undock",
        "drivers/acpi/dock.c:write_undock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585819744,
      "name": "acpi_scan_lock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void acpi_scan_lock_release()
```

```json
{
  "name": "acpi_scan_lock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585713147,
      "name": "acpi_scan_lock_release",
      "external": true,
      "loc": "drivers/acpi/scan.c:62",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_table_events_fn"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_s2idle_end",
        "drivers/acpi/sleep.c:acpi_pm_end",
        "drivers/acpi/dock.c:undock_store",
        "drivers/acpi/dock.c:undock_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585700080,
      "name": "acpi_scan_lock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void acpi_scan_lock_release()
```

```json
{
  "name": "acpi_scan_lock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586194486,
      "name": "acpi_scan_lock_release",
      "external": true,
      "loc": "drivers/acpi/scan.c:59",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_table_events_fn",
        "drivers/acpi/scan.c:acpi_scan_clear_dep_fn"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_s2idle_end",
        "drivers/acpi/sleep.c:acpi_pm_end",
        "drivers/acpi/dock.c:undock_store",
        "drivers/acpi/dock.c:undock_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586180560,
      "name": "acpi_scan_lock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void acpi_scan_lock_release()
```

```json
{
  "name": "acpi_scan_lock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587430773,
      "name": "acpi_scan_lock_release",
      "external": true,
      "loc": "drivers/acpi/scan.c:60",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_table_events_fn",
        "drivers/acpi/scan.c:acpi_scan_clear_dep_fn"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_s2idle_end",
        "drivers/acpi/sleep.c:acpi_pm_end",
        "drivers/acpi/dock.c:undock_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587415936,
      "name": "acpi_scan_lock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void acpi_scan_lock_release()
```

```json
{
  "name": "acpi_scan_lock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588688773,
      "name": "acpi_scan_lock_release",
      "external": true,
      "loc": "drivers/acpi/scan.c:59",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_table_events_fn",
        "drivers/acpi/scan.c:acpi_scan_clear_dep_fn"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_s2idle_end",
        "drivers/acpi/sleep.c:acpi_pm_end",
        "drivers/acpi/dock.c:undock_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588672496,
      "name": "acpi_scan_lock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void acpi_scan_lock_release()
```

```json
{
  "name": "acpi_scan_lock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588976693,
      "name": "acpi_scan_lock_release",
      "external": true,
      "loc": "drivers/acpi/scan.c:58",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_table_events_fn",
        "drivers/acpi/scan.c:acpi_scan_clear_dep_fn"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_s2idle_end",
        "drivers/acpi/sleep.c:acpi_pm_end",
        "drivers/acpi/dock.c:undock_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588960240,
      "name": "acpi_scan_lock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void acpi_scan_lock_release()
```

```json
{
  "name": "acpi_scan_lock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589273269,
      "name": "acpi_scan_lock_release",
      "external": true,
      "loc": "drivers/acpi/scan.c:58",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_table_events_fn",
        "drivers/acpi/scan.c:acpi_scan_clear_dep_fn"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_s2idle_end",
        "drivers/acpi/sleep.c:acpi_pm_end",
        "drivers/acpi/dock.c:undock_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589257584,
      "name": "acpi_scan_lock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void acpi_scan_lock_release()
```

```json
{
  "name": "acpi_scan_lock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497422108,
      "name": "acpi_scan_lock_release",
      "external": true,
      "loc": "drivers/acpi/scan.c:65",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_table_events_fn"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/dock.c:write_undock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497408904,
      "name": "acpi_scan_lock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void acpi_scan_lock_release()
```

```json
{
  "name": "acpi_scan_lock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584954585,
      "name": "acpi_scan_lock_release",
      "external": true,
      "loc": "drivers/acpi/scan.c:65",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_table_events_fn"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_pm_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584943104,
      "name": "acpi_scan_lock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void acpi_scan_lock_release()
```

```json
{
  "name": "acpi_scan_lock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584863385,
      "name": "acpi_scan_lock_release",
      "external": true,
      "loc": "drivers/acpi/scan.c:65",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_table_events_fn"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_s2idle_end",
        "drivers/acpi/sleep.c:acpi_pm_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584851904,
      "name": "acpi_scan_lock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void acpi_scan_lock_release()
```

```json
{
  "name": "acpi_scan_lock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584962793,
      "name": "acpi_scan_lock_release",
      "external": true,
      "loc": "drivers/acpi/scan.c:65",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_table_events_fn"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_s2idle_end",
        "drivers/acpi/sleep.c:acpi_pm_end",
        "drivers/acpi/dock.c:write_undock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584950784,
      "name": "acpi_scan_lock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void acpi_scan_lock_release()
```

```json
{
  "name": "acpi_scan_lock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585068969,
      "name": "acpi_scan_lock_release",
      "external": true,
      "loc": "drivers/acpi/scan.c:65",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_table_events_fn"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_s2idle_end",
        "drivers/acpi/sleep.c:acpi_pm_end",
        "drivers/acpi/dock.c:write_undock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585056960,
      "name": "acpi_scan_lock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void acpi_scan_lock_release()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void acpi_scan_lock_release()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void acpi_scan_lock_release()
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
