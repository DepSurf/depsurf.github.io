# Function: <code>acpi_scan_lock_acquire</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void acpi_scan_lock_acquire()
```

```json
{
  "name": "acpi_scan_lock_acquire",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583560838,
      "name": "acpi_scan_lock_acquire",
      "external": true,
      "loc": "drivers/acpi/scan.c:61",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_freeze_begin",
        "drivers/acpi/sleep.c:acpi_suspend_begin",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_hibernation_begin",
        "drivers/acpi/dock.c:write_undock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583560838,
      "name": "acpi_scan_lock_acquire",
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
void acpi_scan_lock_acquire()
```

```json
{
  "name": "acpi_scan_lock_acquire",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583882511,
      "name": "acpi_scan_lock_acquire",
      "external": true,
      "loc": "drivers/acpi/scan.c:62",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_hibernation_begin",
        "drivers/acpi/sleep.c:acpi_freeze_begin",
        "drivers/acpi/sleep.c:acpi_suspend_begin",
        "drivers/acpi/scan.c:acpi_table_events_fn",
        "drivers/acpi/dock.c:write_undock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583882511,
      "name": "acpi_scan_lock_acquire",
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
void acpi_scan_lock_acquire()
```

```json
{
  "name": "acpi_scan_lock_acquire",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584021620,
      "name": "acpi_scan_lock_acquire",
      "external": true,
      "loc": "drivers/acpi/scan.c:63",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_hibernation_begin",
        "drivers/acpi/sleep.c:acpi_freeze_begin",
        "drivers/acpi/sleep.c:acpi_suspend_begin",
        "drivers/acpi/scan.c:acpi_table_events_fn",
        "drivers/acpi/dock.c:write_undock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584021620,
      "name": "acpi_scan_lock_acquire",
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
void acpi_scan_lock_acquire()
```

```json
{
  "name": "acpi_scan_lock_acquire",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584086644,
      "name": "acpi_scan_lock_acquire",
      "external": true,
      "loc": "drivers/acpi/scan.c:57",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_table_events_fn"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_hibernation_begin",
        "drivers/acpi/sleep.c:acpi_freeze_begin",
        "drivers/acpi/sleep.c:acpi_suspend_begin",
        "drivers/acpi/dock.c:write_undock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584075200,
      "name": "acpi_scan_lock_acquire",
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
void acpi_scan_lock_acquire()
```

```json
{
  "name": "acpi_scan_lock_acquire",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584357300,
      "name": "acpi_scan_lock_acquire",
      "external": true,
      "loc": "drivers/acpi/scan.c:58",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_table_events_fn"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_hibernation_begin",
        "drivers/acpi/sleep.c:acpi_s2idle_begin",
        "drivers/acpi/sleep.c:acpi_suspend_begin",
        "drivers/acpi/dock.c:write_undock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584344832,
      "name": "acpi_scan_lock_acquire",
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
void acpi_scan_lock_acquire()
```

```json
{
  "name": "acpi_scan_lock_acquire",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584578191,
      "name": "acpi_scan_lock_acquire",
      "external": true,
      "loc": "drivers/acpi/scan.c:58",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_table_events_fn"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_hibernation_begin",
        "drivers/acpi/sleep.c:acpi_s2idle_begin",
        "drivers/acpi/sleep.c:acpi_suspend_begin",
        "drivers/acpi/dock.c:write_undock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584565824,
      "name": "acpi_scan_lock_acquire",
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
void acpi_scan_lock_acquire()
```

```json
{
  "name": "acpi_scan_lock_acquire",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584675535,
      "name": "acpi_scan_lock_acquire",
      "external": true,
      "loc": "drivers/acpi/scan.c:58",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_table_events_fn"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_hibernation_begin",
        "drivers/acpi/sleep.c:acpi_s2idle_begin",
        "drivers/acpi/sleep.c:acpi_suspend_begin",
        "drivers/acpi/dock.c:write_undock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584663136,
      "name": "acpi_scan_lock_acquire",
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
void acpi_scan_lock_acquire()
```

```json
{
  "name": "acpi_scan_lock_acquire",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584875313,
      "name": "acpi_scan_lock_acquire",
      "external": true,
      "loc": "drivers/acpi/scan.c:59",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_table_events_fn"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_hibernation_begin",
        "drivers/acpi/sleep.c:acpi_s2idle_begin",
        "drivers/acpi/sleep.c:acpi_suspend_begin",
        "drivers/acpi/dock.c:write_undock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584863296,
      "name": "acpi_scan_lock_acquire",
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
void acpi_scan_lock_acquire()
```

```json
{
  "name": "acpi_scan_lock_acquire",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585011185,
      "name": "acpi_scan_lock_acquire",
      "external": true,
      "loc": "drivers/acpi/scan.c:59",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_table_events_fn"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_hibernation_begin",
        "drivers/acpi/sleep.c:acpi_s2idle_begin",
        "drivers/acpi/sleep.c:acpi_suspend_begin",
        "drivers/acpi/dock.c:write_undock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584999168,
      "name": "acpi_scan_lock_acquire",
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
void acpi_scan_lock_acquire()
```

```json
{
  "name": "acpi_scan_lock_acquire",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585710819,
      "name": "acpi_scan_lock_acquire",
      "external": true,
      "loc": "drivers/acpi/scan.c:58",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_table_events_fn"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_hibernation_begin",
        "drivers/acpi/sleep.c:acpi_s2idle_begin",
        "drivers/acpi/sleep.c:acpi_suspend_begin",
        "drivers/acpi/dock.c:write_undock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585697968,
      "name": "acpi_scan_lock_acquire",
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
void acpi_scan_lock_acquire()
```

```json
{
  "name": "acpi_scan_lock_acquire",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585833827,
      "name": "acpi_scan_lock_acquire",
      "external": true,
      "loc": "drivers/acpi/scan.c:58",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_table_events_fn"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_hibernation_begin",
        "drivers/acpi/sleep.c:acpi_s2idle_begin",
        "drivers/acpi/sleep.c:acpi_suspend_begin",
        "drivers/acpi/dock.c:write_undock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585819712,
      "name": "acpi_scan_lock_acquire",
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
void acpi_scan_lock_acquire()
```

```json
{
  "name": "acpi_scan_lock_acquire",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585713123,
      "name": "acpi_scan_lock_acquire",
      "external": true,
      "loc": "drivers/acpi/scan.c:56",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_table_events_fn"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_hibernation_begin",
        "drivers/acpi/sleep.c:acpi_s2idle_begin",
        "drivers/acpi/sleep.c:acpi_suspend_begin",
        "drivers/acpi/dock.c:undock_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585700048,
      "name": "acpi_scan_lock_acquire",
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
void acpi_scan_lock_acquire()
```

```json
{
  "name": "acpi_scan_lock_acquire",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586194453,
      "name": "acpi_scan_lock_acquire",
      "external": true,
      "loc": "drivers/acpi/scan.c:53",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_table_events_fn",
        "drivers/acpi/scan.c:acpi_scan_clear_dep_fn"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_hibernation_begin",
        "drivers/acpi/sleep.c:acpi_s2idle_begin",
        "drivers/acpi/sleep.c:acpi_suspend_begin",
        "drivers/acpi/dock.c:undock_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586180528,
      "name": "acpi_scan_lock_acquire",
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
void acpi_scan_lock_acquire()
```

```json
{
  "name": "acpi_scan_lock_acquire",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587430741,
      "name": "acpi_scan_lock_acquire",
      "external": true,
      "loc": "drivers/acpi/scan.c:54",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_table_events_fn",
        "drivers/acpi/scan.c:acpi_scan_clear_dep_fn"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_hibernation_begin",
        "drivers/acpi/sleep.c:acpi_s2idle_begin",
        "drivers/acpi/sleep.c:acpi_suspend_begin",
        "drivers/acpi/dock.c:undock_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587415904,
      "name": "acpi_scan_lock_acquire",
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
void acpi_scan_lock_acquire()
```

```json
{
  "name": "acpi_scan_lock_acquire",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588688741,
      "name": "acpi_scan_lock_acquire",
      "external": true,
      "loc": "drivers/acpi/scan.c:53",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_table_events_fn",
        "drivers/acpi/scan.c:acpi_scan_clear_dep_fn"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_hibernation_begin",
        "drivers/acpi/sleep.c:acpi_s2idle_begin",
        "drivers/acpi/sleep.c:acpi_suspend_begin",
        "drivers/acpi/dock.c:undock_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588672448,
      "name": "acpi_scan_lock_acquire",
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
void acpi_scan_lock_acquire()
```

```json
{
  "name": "acpi_scan_lock_acquire",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588976661,
      "name": "acpi_scan_lock_acquire",
      "external": true,
      "loc": "drivers/acpi/scan.c:52",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_table_events_fn",
        "drivers/acpi/scan.c:acpi_scan_clear_dep_fn"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_hibernation_begin",
        "drivers/acpi/sleep.c:acpi_s2idle_begin",
        "drivers/acpi/sleep.c:acpi_suspend_begin",
        "drivers/acpi/dock.c:undock_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588960192,
      "name": "acpi_scan_lock_acquire",
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
void acpi_scan_lock_acquire()
```

```json
{
  "name": "acpi_scan_lock_acquire",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589273237,
      "name": "acpi_scan_lock_acquire",
      "external": true,
      "loc": "drivers/acpi/scan.c:52",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_table_events_fn",
        "drivers/acpi/scan.c:acpi_scan_clear_dep_fn"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_hibernation_begin",
        "drivers/acpi/sleep.c:acpi_s2idle_begin",
        "drivers/acpi/sleep.c:acpi_suspend_begin",
        "drivers/acpi/dock.c:undock_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589257536,
      "name": "acpi_scan_lock_acquire",
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
void acpi_scan_lock_acquire()
```

```json
{
  "name": "acpi_scan_lock_acquire",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497422084,
      "name": "acpi_scan_lock_acquire",
      "external": true,
      "loc": "drivers/acpi/scan.c:59",
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
      "addr": 18446603336497408864,
      "name": "acpi_scan_lock_acquire",
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
void acpi_scan_lock_acquire()
```

```json
{
  "name": "acpi_scan_lock_acquire",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584954561,
      "name": "acpi_scan_lock_acquire",
      "external": true,
      "loc": "drivers/acpi/scan.c:59",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_table_events_fn"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_hibernation_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584943072,
      "name": "acpi_scan_lock_acquire",
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
void acpi_scan_lock_acquire()
```

```json
{
  "name": "acpi_scan_lock_acquire",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584863361,
      "name": "acpi_scan_lock_acquire",
      "external": true,
      "loc": "drivers/acpi/scan.c:59",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_table_events_fn"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_hibernation_begin",
        "drivers/acpi/sleep.c:acpi_s2idle_begin",
        "drivers/acpi/sleep.c:acpi_suspend_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584851872,
      "name": "acpi_scan_lock_acquire",
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
void acpi_scan_lock_acquire()
```

```json
{
  "name": "acpi_scan_lock_acquire",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584962769,
      "name": "acpi_scan_lock_acquire",
      "external": true,
      "loc": "drivers/acpi/scan.c:59",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_table_events_fn"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_hibernation_begin",
        "drivers/acpi/sleep.c:acpi_s2idle_begin",
        "drivers/acpi/sleep.c:acpi_suspend_begin",
        "drivers/acpi/dock.c:write_undock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584950752,
      "name": "acpi_scan_lock_acquire",
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
void acpi_scan_lock_acquire()
```

```json
{
  "name": "acpi_scan_lock_acquire",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585068945,
      "name": "acpi_scan_lock_acquire",
      "external": true,
      "loc": "drivers/acpi/scan.c:59",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_table_events_fn"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_hibernation_begin",
        "drivers/acpi/sleep.c:acpi_s2idle_begin",
        "drivers/acpi/sleep.c:acpi_suspend_begin",
        "drivers/acpi/dock.c:write_undock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585056928,
      "name": "acpi_scan_lock_acquire",
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
void acpi_scan_lock_acquire()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void acpi_scan_lock_acquire()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void acpi_scan_lock_acquire()
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
