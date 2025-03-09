# Function: <code>acpi_unlock_hp_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void acpi_unlock_hp_context()
```

```json
{
  "name": "acpi_unlock_hp_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583563313,
      "name": "acpi_unlock_hp_context",
      "external": true,
      "loc": "drivers/acpi/scan.c:78",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/acpi/scan.c:acpi_initialize_hp_context",
        "drivers/acpi/scan.c:acpi_device_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583563313,
      "name": "acpi_unlock_hp_context",
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
void acpi_unlock_hp_context()
```

```json
{
  "name": "acpi_unlock_hp_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583885220,
      "name": "acpi_unlock_hp_context",
      "external": true,
      "loc": "drivers/acpi/scan.c:79",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_initialize_hp_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583885220,
      "name": "acpi_unlock_hp_context",
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
void acpi_unlock_hp_context()
```

```json
{
  "name": "acpi_unlock_hp_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584024334,
      "name": "acpi_unlock_hp_context",
      "external": true,
      "loc": "drivers/acpi/scan.c:80",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_initialize_hp_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584024334,
      "name": "acpi_unlock_hp_context",
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
void acpi_unlock_hp_context()
```

```json
{
  "name": "acpi_unlock_hp_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584085656,
      "name": "acpi_unlock_hp_context",
      "external": true,
      "loc": "drivers/acpi/scan.c:74",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_initialize_hp_context"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584079088,
      "name": "acpi_unlock_hp_context",
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
void acpi_unlock_hp_context()
```

```json
{
  "name": "acpi_unlock_hp_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584356216,
      "name": "acpi_unlock_hp_context",
      "external": true,
      "loc": "drivers/acpi/scan.c:75",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_initialize_hp_context"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584348944,
      "name": "acpi_unlock_hp_context",
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
void acpi_unlock_hp_context()
```

```json
{
  "name": "acpi_unlock_hp_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584577096,
      "name": "acpi_unlock_hp_context",
      "external": true,
      "loc": "drivers/acpi/scan.c:75",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_initialize_hp_context"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584569952,
      "name": "acpi_unlock_hp_context",
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
void acpi_unlock_hp_context()
```

```json
{
  "name": "acpi_unlock_hp_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584674424,
      "name": "acpi_unlock_hp_context",
      "external": true,
      "loc": "drivers/acpi/scan.c:75",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_initialize_hp_context"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584667264,
      "name": "acpi_unlock_hp_context",
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
void acpi_unlock_hp_context()
```

```json
{
  "name": "acpi_unlock_hp_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584874408,
      "name": "acpi_unlock_hp_context",
      "external": true,
      "loc": "drivers/acpi/scan.c:76",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_initialize_hp_context"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584867440,
      "name": "acpi_unlock_hp_context",
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
void acpi_unlock_hp_context()
```

```json
{
  "name": "acpi_unlock_hp_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585010280,
      "name": "acpi_unlock_hp_context",
      "external": true,
      "loc": "drivers/acpi/scan.c:76",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_initialize_hp_context"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585003312,
      "name": "acpi_unlock_hp_context",
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
void acpi_unlock_hp_context()
```

```json
{
  "name": "acpi_unlock_hp_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585710439,
      "name": "acpi_unlock_hp_context",
      "external": true,
      "loc": "drivers/acpi/scan.c:75",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_initialize_hp_context"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context",
        "drivers/acpi/dock.c:dock_event",
        "drivers/acpi/dock.c:dock_event",
        "drivers/acpi/dock.c:hotplug_dock_devices",
        "drivers/acpi/dock.c:hotplug_dock_devices",
        "drivers/acpi/dock.c:hotplug_dock_devices",
        "drivers/acpi/dock.c:hotplug_dock_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585704880,
      "name": "acpi_unlock_hp_context",
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
void acpi_unlock_hp_context()
```

```json
{
  "name": "acpi_unlock_hp_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585833437,
      "name": "acpi_unlock_hp_context",
      "external": true,
      "loc": "drivers/acpi/scan.c:75",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_initialize_hp_context"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context",
        "drivers/acpi/dock.c:dock_event",
        "drivers/acpi/dock.c:dock_event",
        "drivers/acpi/dock.c:hotplug_dock_devices",
        "drivers/acpi/dock.c:hotplug_dock_devices",
        "drivers/acpi/dock.c:hotplug_dock_devices",
        "drivers/acpi/dock.c:hotplug_dock_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585827056,
      "name": "acpi_unlock_hp_context",
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
void acpi_unlock_hp_context()
```

```json
{
  "name": "acpi_unlock_hp_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585712740,
      "name": "acpi_unlock_hp_context",
      "external": true,
      "loc": "drivers/acpi/scan.c:73",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_initialize_hp_context"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:dock_event",
        "drivers/acpi/dock.c:dock_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585706096,
      "name": "acpi_unlock_hp_context",
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
void acpi_unlock_hp_context()
```

```json
{
  "name": "acpi_unlock_hp_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586194100,
      "name": "acpi_unlock_hp_context",
      "external": true,
      "loc": "drivers/acpi/scan.c:70",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_initialize_hp_context"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:dock_event",
        "drivers/acpi/dock.c:dock_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586188064,
      "name": "acpi_unlock_hp_context",
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
void acpi_unlock_hp_context()
```

```json
{
  "name": "acpi_unlock_hp_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587430324,
      "name": "acpi_unlock_hp_context",
      "external": true,
      "loc": "drivers/acpi/scan.c:71",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_initialize_hp_context"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:dock_event",
        "drivers/acpi/dock.c:dock_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587424144,
      "name": "acpi_unlock_hp_context",
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
void acpi_unlock_hp_context()
```

```json
{
  "name": "acpi_unlock_hp_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588688124,
      "name": "acpi_unlock_hp_context",
      "external": true,
      "loc": "drivers/acpi/scan.c:70",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_initialize_hp_context"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:dock_event",
        "drivers/acpi/dock.c:dock_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588680272,
      "name": "acpi_unlock_hp_context",
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
void acpi_unlock_hp_context()
```

```json
{
  "name": "acpi_unlock_hp_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588976028,
      "name": "acpi_unlock_hp_context",
      "external": true,
      "loc": "drivers/acpi/scan.c:69",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_initialize_hp_context"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:dock_event",
        "drivers/acpi/dock.c:dock_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588968032,
      "name": "acpi_unlock_hp_context",
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
void acpi_unlock_hp_context()
```

```json
{
  "name": "acpi_unlock_hp_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589273756,
      "name": "acpi_unlock_hp_context",
      "external": true,
      "loc": "drivers/acpi/scan.c:69",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_initialize_hp_context"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:dock_event",
        "drivers/acpi/dock.c:dock_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589265488,
      "name": "acpi_unlock_hp_context",
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
void acpi_unlock_hp_context()
```

```json
{
  "name": "acpi_unlock_hp_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497421036,
      "name": "acpi_unlock_hp_context",
      "external": true,
      "loc": "drivers/acpi/scan.c:76",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_initialize_hp_context"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497413672,
      "name": "acpi_unlock_hp_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void acpi_unlock_hp_context()
```

```json
{
  "name": "acpi_unlock_hp_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584953814,
      "name": "acpi_unlock_hp_context",
      "external": true,
      "loc": "drivers/acpi/scan.c:76",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_initialize_hp_context"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584946992,
      "name": "acpi_unlock_hp_context",
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
void acpi_unlock_hp_context()
```

```json
{
  "name": "acpi_unlock_hp_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584862614,
      "name": "acpi_unlock_hp_context",
      "external": true,
      "loc": "drivers/acpi/scan.c:76",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_initialize_hp_context"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584855792,
      "name": "acpi_unlock_hp_context",
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
void acpi_unlock_hp_context()
```

```json
{
  "name": "acpi_unlock_hp_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584961864,
      "name": "acpi_unlock_hp_context",
      "external": true,
      "loc": "drivers/acpi/scan.c:76",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_initialize_hp_context"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584954896,
      "name": "acpi_unlock_hp_context",
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
void acpi_unlock_hp_context()
```

```json
{
  "name": "acpi_unlock_hp_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585068040,
      "name": "acpi_unlock_hp_context",
      "external": true,
      "loc": "drivers/acpi/scan.c:76",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_initialize_hp_context"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:free_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585061072,
      "name": "acpi_unlock_hp_context",
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
void acpi_unlock_hp_context()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void acpi_unlock_hp_context()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void acpi_unlock_hp_context()
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
