# Function: <code>usb_hub_to_struct_hub</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct usb_hub * usb_hub_to_struct_hub(struct usb_device * hdev)
```

```json
{
  "name": "usb_hub_to_struct_hub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585151350,
      "name": "usb_hub_to_struct_hub",
      "external": true,
      "loc": "drivers/usb/core/hub.c:118",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:find_port_owner",
        "drivers/usb/core/hub.c:recursively_mark_NOTATTACHED",
        "drivers/usb/core/hub.c:usb_hub_find_child",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:hub_ioctl",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_kick_hub_wq",
        "drivers/usb/core/hub.c:usb_remove_device",
        "drivers/usb/core/hub.c:usb_hub_release_all_ports",
        "drivers/usb/core/hub.c:usb_device_is_owned",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable",
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle"
      ],
      "caller_func": [
        "drivers/usb/core/port.c:usb_port_runtime_resume",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:match_location",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585158640,
      "name": "usb_hub_to_struct_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct usb_hub * usb_hub_to_struct_hub(struct usb_device * hdev)
```

```json
{
  "name": "usb_hub_to_struct_hub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585577798,
      "name": "usb_hub_to_struct_hub",
      "external": true,
      "loc": "drivers/usb/core/hub.c:120",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable",
        "drivers/usb/core/hub.c:usb_hub_find_child",
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_enable_lpm",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:recursively_mark_NOTATTACHED",
        "drivers/usb/core/hub.c:usb_device_is_owned",
        "drivers/usb/core/hub.c:usb_hub_release_all_ports",
        "drivers/usb/core/hub.c:find_port_owner",
        "drivers/usb/core/hub.c:hub_ioctl",
        "drivers/usb/core/hub.c:usb_remove_device",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:match_location",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume",
        "drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585551248,
      "name": "usb_hub_to_struct_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct usb_hub * usb_hub_to_struct_hub(struct usb_device * hdev)
```

```json
{
  "name": "usb_hub_to_struct_hub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585765446,
      "name": "usb_hub_to_struct_hub",
      "external": true,
      "loc": "drivers/usb/core/hub.c:123",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable",
        "drivers/usb/core/hub.c:usb_hub_find_child",
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_enable_lpm",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:recursively_mark_NOTATTACHED",
        "drivers/usb/core/hub.c:usb_device_is_owned",
        "drivers/usb/core/hub.c:usb_hub_release_all_ports",
        "drivers/usb/core/hub.c:find_port_owner",
        "drivers/usb/core/hub.c:hub_ioctl",
        "drivers/usb/core/hub.c:usb_remove_device",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:match_location",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume",
        "drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585738416,
      "name": "usb_hub_to_struct_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct usb_hub * usb_hub_to_struct_hub(struct usb_device * hdev)
```

```json
{
  "name": "usb_hub_to_struct_hub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585852294,
      "name": "usb_hub_to_struct_hub",
      "external": true,
      "loc": "drivers/usb/core/hub.c:123",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable",
        "drivers/usb/core/hub.c:usb_hub_find_child",
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_enable_lpm",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:recursively_mark_NOTATTACHED",
        "drivers/usb/core/hub.c:usb_device_is_owned",
        "drivers/usb/core/hub.c:usb_hub_release_all_ports",
        "drivers/usb/core/hub.c:find_port_owner",
        "drivers/usb/core/hub.c:hub_ioctl",
        "drivers/usb/core/hub.c:usb_remove_device",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:match_location",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume",
        "drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585826176,
      "name": "usb_hub_to_struct_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct usb_hub * usb_hub_to_struct_hub(struct usb_device * hdev)
```

```json
{
  "name": "usb_hub_to_struct_hub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586292085,
      "name": "usb_hub_to_struct_hub",
      "external": true,
      "loc": "drivers/usb/core/hub.c:123",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable",
        "drivers/usb/core/hub.c:usb_hub_find_child",
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:usb_enable_lpm",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:recursively_mark_NOTATTACHED",
        "drivers/usb/core/hub.c:usb_device_is_owned",
        "drivers/usb/core/hub.c:usb_hub_release_all_ports",
        "drivers/usb/core/hub.c:find_port_owner",
        "drivers/usb/core/hub.c:hub_ioctl",
        "drivers/usb/core/hub.c:usb_remove_device",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:match_location",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume",
        "drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586265472,
      "name": "usb_hub_to_struct_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct usb_hub * usb_hub_to_struct_hub(struct usb_device * hdev)
```

```json
{
  "name": "usb_hub_to_struct_hub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586549525,
      "name": "usb_hub_to_struct_hub",
      "external": true,
      "loc": "drivers/usb/core/hub.c:126",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable",
        "drivers/usb/core/hub.c:usb_hub_find_child",
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:usb_enable_lpm",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:recursively_mark_NOTATTACHED",
        "drivers/usb/core/hub.c:usb_device_is_owned",
        "drivers/usb/core/hub.c:usb_hub_release_all_ports",
        "drivers/usb/core/hub.c:find_port_owner",
        "drivers/usb/core/hub.c:hub_ioctl",
        "drivers/usb/core/hub.c:usb_remove_device",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:match_location",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume",
        "drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586522864,
      "name": "usb_hub_to_struct_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct usb_hub * usb_hub_to_struct_hub(struct usb_device * hdev)
```

```json
{
  "name": "usb_hub_to_struct_hub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586698373,
      "name": "usb_hub_to_struct_hub",
      "external": true,
      "loc": "drivers/usb/core/hub.c:127",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable",
        "drivers/usb/core/hub.c:usb_hub_find_child",
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:usb_enable_lpm",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:recursively_mark_NOTATTACHED",
        "drivers/usb/core/hub.c:usb_device_is_owned",
        "drivers/usb/core/hub.c:usb_hub_release_all_ports",
        "drivers/usb/core/hub.c:find_port_owner",
        "drivers/usb/core/hub.c:hub_ioctl",
        "drivers/usb/core/hub.c:usb_remove_device",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:match_location",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume",
        "drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586671472,
      "name": "usb_hub_to_struct_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct usb_hub * usb_hub_to_struct_hub(struct usb_device * hdev)
```

```json
{
  "name": "usb_hub_to_struct_hub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586947045,
      "name": "usb_hub_to_struct_hub",
      "external": true,
      "loc": "drivers/usb/core/hub.c:129",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable",
        "drivers/usb/core/hub.c:usb_hub_find_child",
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:usb_enable_lpm",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:recursively_mark_NOTATTACHED",
        "drivers/usb/core/hub.c:usb_device_is_owned",
        "drivers/usb/core/hub.c:usb_hub_release_all_ports",
        "drivers/usb/core/hub.c:find_port_owner",
        "drivers/usb/core/hub.c:hub_ioctl",
        "drivers/usb/core/hub.c:usb_remove_device",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:match_location",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume",
        "drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586925664,
      "name": "usb_hub_to_struct_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct usb_hub * usb_hub_to_struct_hub(struct usb_device * hdev)
```

```json
{
  "name": "usb_hub_to_struct_hub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587145781,
      "name": "usb_hub_to_struct_hub",
      "external": true,
      "loc": "drivers/usb/core/hub.c:131",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable",
        "drivers/usb/core/hub.c:usb_hub_find_child",
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:usb_enable_lpm",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:recursively_mark_NOTATTACHED",
        "drivers/usb/core/hub.c:usb_device_is_owned",
        "drivers/usb/core/hub.c:usb_hub_release_all_ports",
        "drivers/usb/core/hub.c:find_port_owner",
        "drivers/usb/core/hub.c:hub_ioctl",
        "drivers/usb/core/hub.c:usb_remove_device",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:match_location",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume",
        "drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587124112,
      "name": "usb_hub_to_struct_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct usb_hub * usb_hub_to_struct_hub(struct usb_device * hdev)
```

```json
{
  "name": "usb_hub_to_struct_hub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587994757,
      "name": "usb_hub_to_struct_hub",
      "external": true,
      "loc": "drivers/usb/core/hub.c:133",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable",
        "drivers/usb/core/hub.c:usb_hub_find_child",
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:usb_enable_lpm",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:recursively_mark_NOTATTACHED",
        "drivers/usb/core/hub.c:usb_device_is_owned",
        "drivers/usb/core/hub.c:usb_hub_release_all_ports",
        "drivers/usb/core/hub.c:usb_hub_release_port",
        "drivers/usb/core/hub.c:usb_hub_claim_port",
        "drivers/usb/core/hub.c:hub_ioctl",
        "drivers/usb/core/hub.c:usb_remove_device",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq",
        "drivers/usb/core/hub.c:usb_set_lpm_parameters"
      ],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/port.c:match_location",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume",
        "drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587977968,
      "name": "usb_hub_to_struct_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct usb_hub * usb_hub_to_struct_hub(struct usb_device * hdev)
```

```json
{
  "name": "usb_hub_to_struct_hub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588054373,
      "name": "usb_hub_to_struct_hub",
      "external": true,
      "loc": "drivers/usb/core/hub.c:133",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable",
        "drivers/usb/core/hub.c:usb_hub_find_child",
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:usb_enable_lpm",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:recursively_mark_NOTATTACHED",
        "drivers/usb/core/hub.c:usb_device_is_owned",
        "drivers/usb/core/hub.c:usb_hub_release_all_ports",
        "drivers/usb/core/hub.c:usb_hub_release_port",
        "drivers/usb/core/hub.c:usb_hub_claim_port",
        "drivers/usb/core/hub.c:hub_ioctl",
        "drivers/usb/core/hub.c:usb_remove_device",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq",
        "drivers/usb/core/hub.c:usb_set_lpm_parameters"
      ],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/port.c:match_location",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume",
        "drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588037696,
      "name": "usb_hub_to_struct_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct usb_hub * usb_hub_to_struct_hub(struct usb_device * hdev)
```

```json
{
  "name": "usb_hub_to_struct_hub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587937205,
      "name": "usb_hub_to_struct_hub",
      "external": true,
      "loc": "drivers/usb/core/hub.c:137",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable",
        "drivers/usb/core/hub.c:usb_hub_find_child",
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:usb_enable_lpm",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:recursively_mark_NOTATTACHED",
        "drivers/usb/core/hub.c:usb_device_is_owned",
        "drivers/usb/core/hub.c:usb_hub_release_all_ports",
        "drivers/usb/core/hub.c:usb_hub_release_port",
        "drivers/usb/core/hub.c:usb_hub_claim_port",
        "drivers/usb/core/hub.c:hub_ioctl",
        "drivers/usb/core/hub.c:usb_remove_device",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq",
        "drivers/usb/core/hub.c:usb_set_lpm_parameters"
      ],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/usb.c:__each_hub",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:match_location",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume",
        "drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587919552,
      "name": "usb_hub_to_struct_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct usb_hub * usb_hub_to_struct_hub(struct usb_device * hdev)
```

```json
{
  "name": "usb_hub_to_struct_hub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588547541,
      "name": "usb_hub_to_struct_hub",
      "external": true,
      "loc": "drivers/usb/core/hub.c:137",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable",
        "drivers/usb/core/hub.c:usb_hub_find_child",
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:usb_enable_lpm",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:recursively_mark_NOTATTACHED",
        "drivers/usb/core/hub.c:usb_device_is_owned",
        "drivers/usb/core/hub.c:usb_hub_release_all_ports",
        "drivers/usb/core/hub.c:usb_hub_release_port",
        "drivers/usb/core/hub.c:usb_hub_claim_port",
        "drivers/usb/core/hub.c:hub_ioctl",
        "drivers/usb/core/hub.c:usb_remove_device",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq",
        "drivers/usb/core/hub.c:usb_set_lpm_parameters"
      ],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/usb.c:__each_hub",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:match_location",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume",
        "drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588529488,
      "name": "usb_hub_to_struct_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct usb_hub * usb_hub_to_struct_hub(struct usb_device * hdev)
```

```json
{
  "name": "usb_hub_to_struct_hub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589957093,
      "name": "usb_hub_to_struct_hub",
      "external": true,
      "loc": "drivers/usb/core/hub.c:137",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable",
        "drivers/usb/core/hub.c:usb_hub_find_child",
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:usb_enable_lpm",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:recursively_mark_NOTATTACHED",
        "drivers/usb/core/hub.c:usb_device_is_owned",
        "drivers/usb/core/hub.c:usb_hub_release_all_ports",
        "drivers/usb/core/hub.c:usb_hub_release_port",
        "drivers/usb/core/hub.c:usb_hub_claim_port",
        "drivers/usb/core/hub.c:hub_ioctl",
        "drivers/usb/core/hub.c:usb_remove_device",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:match_location",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume",
        "drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589937808,
      "name": "usb_hub_to_struct_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct usb_hub * usb_hub_to_struct_hub(struct usb_device * hdev)
```

```json
{
  "name": "usb_hub_to_struct_hub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591546133,
      "name": "usb_hub_to_struct_hub",
      "external": true,
      "loc": "drivers/usb/core/hub.c:141",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable",
        "drivers/usb/core/hub.c:usb_hub_find_child",
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:usb_enable_lpm",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:recursively_mark_NOTATTACHED",
        "drivers/usb/core/hub.c:usb_device_is_owned",
        "drivers/usb/core/hub.c:usb_hub_release_all_ports",
        "drivers/usb/core/hub.c:usb_hub_release_port",
        "drivers/usb/core/hub.c:usb_hub_claim_port",
        "drivers/usb/core/hub.c:hub_ioctl",
        "drivers/usb/core/hub.c:usb_remove_device",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:match_location",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume",
        "drivers/usb/core/port.c:disable_store",
        "drivers/usb/core/port.c:disable_show",
        "drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591519616,
      "name": "usb_hub_to_struct_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct usb_hub * usb_hub_to_struct_hub(struct usb_device * hdev)
```

```json
{
  "name": "usb_hub_to_struct_hub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591967781,
      "name": "usb_hub_to_struct_hub",
      "external": true,
      "loc": "drivers/usb/core/hub.c:141",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable",
        "drivers/usb/core/hub.c:usb_hub_find_child",
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:usb_enable_lpm",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:recursively_mark_NOTATTACHED",
        "drivers/usb/core/hub.c:update_port_device_state",
        "drivers/usb/core/hub.c:usb_device_is_owned",
        "drivers/usb/core/hub.c:usb_hub_release_all_ports",
        "drivers/usb/core/hub.c:usb_hub_release_port",
        "drivers/usb/core/hub.c:usb_hub_claim_port",
        "drivers/usb/core/hub.c:hub_ioctl",
        "drivers/usb/core/hub.c:usb_remove_device",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:match_location",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume",
        "drivers/usb/core/port.c:disable_store",
        "drivers/usb/core/port.c:disable_show",
        "drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591941008,
      "name": "usb_hub_to_struct_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct usb_hub * usb_hub_to_struct_hub(struct usb_device * hdev)
```

```json
{
  "name": "usb_hub_to_struct_hub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592707621,
      "name": "usb_hub_to_struct_hub",
      "external": true,
      "loc": "drivers/usb/core/hub.c:153",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable",
        "drivers/usb/core/hub.c:usb_hub_find_child",
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:usb_enable_lpm",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:recursively_mark_NOTATTACHED",
        "drivers/usb/core/hub.c:update_port_device_state",
        "drivers/usb/core/hub.c:usb_device_is_owned",
        "drivers/usb/core/hub.c:usb_hub_release_all_ports",
        "drivers/usb/core/hub.c:usb_hub_release_port",
        "drivers/usb/core/hub.c:usb_hub_claim_port",
        "drivers/usb/core/hub.c:hub_ioctl",
        "drivers/usb/core/hub.c:usb_remove_device",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:match_location",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume",
        "drivers/usb/core/port.c:disable_store",
        "drivers/usb/core/port.c:disable_show",
        "drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592681264,
      "name": "usb_hub_to_struct_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct usb_hub * usb_hub_to_struct_hub(struct usb_device * hdev)
```

```json
{
  "name": "usb_hub_to_struct_hub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500224868,
      "name": "usb_hub_to_struct_hub",
      "external": true,
      "loc": "drivers/usb/core/hub.c:131",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable",
        "drivers/usb/core/hub.c:usb_hub_find_child",
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:usb_enable_lpm",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:recursively_mark_NOTATTACHED",
        "drivers/usb/core/hub.c:usb_device_is_owned",
        "drivers/usb/core/hub.c:usb_hub_release_all_ports",
        "drivers/usb/core/hub.c:find_port_owner",
        "drivers/usb/core/hub.c:hub_ioctl",
        "drivers/usb/core/hub.c:usb_remove_device",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:match_location",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume",
        "drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500199656,
      "name": "usb_hub_to_struct_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct usb_hub * usb_hub_to_struct_hub(struct usb_device * hdev)
```

```json
{
  "name": "usb_hub_to_struct_hub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232702792,
      "name": "usb_hub_to_struct_hub",
      "external": true,
      "loc": "drivers/usb/core/hub.c:131",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable",
        "drivers/usb/core/hub.c:usb_hub_find_child",
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:usb_enable_lpm",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:recursively_mark_NOTATTACHED",
        "drivers/usb/core/hub.c:usb_device_is_owned",
        "drivers/usb/core/hub.c:usb_hub_release_all_ports",
        "drivers/usb/core/hub.c:find_port_owner",
        "drivers/usb/core/hub.c:hub_ioctl",
        "drivers/usb/core/hub.c:usb_remove_device",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:match_location",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232678352,
      "name": "usb_hub_to_struct_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct usb_hub * usb_hub_to_struct_hub(struct usb_device * hdev)
```

```json
{
  "name": "usb_hub_to_struct_hub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293515048,
      "name": "usb_hub_to_struct_hub",
      "external": true,
      "loc": "drivers/usb/core/hub.c:131",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable",
        "drivers/usb/core/hub.c:usb_hub_find_child",
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:usb_enable_lpm",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:recursively_mark_NOTATTACHED",
        "drivers/usb/core/hub.c:usb_device_is_owned",
        "drivers/usb/core/hub.c:usb_hub_release_all_ports",
        "drivers/usb/core/hub.c:find_port_owner",
        "drivers/usb/core/hub.c:hub_ioctl",
        "drivers/usb/core/hub.c:usb_remove_device",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:match_location",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293484560,
      "name": "usb_hub_to_struct_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct usb_hub * usb_hub_to_struct_hub(struct usb_device * hdev)
```

```json
{
  "name": "usb_hub_to_struct_hub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277146020,
      "name": "usb_hub_to_struct_hub",
      "external": true,
      "loc": "drivers/usb/core/hub.c:131",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable",
        "drivers/usb/core/hub.c:usb_hub_find_child",
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:usb_enable_lpm",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:recursively_mark_NOTATTACHED",
        "drivers/usb/core/hub.c:usb_device_is_owned",
        "drivers/usb/core/hub.c:usb_hub_release_all_ports",
        "drivers/usb/core/hub.c:find_port_owner",
        "drivers/usb/core/hub.c:hub_ioctl",
        "drivers/usb/core/hub.c:usb_remove_device",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:match_location",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277123622,
      "name": "usb_hub_to_struct_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct usb_hub * usb_hub_to_struct_hub(struct usb_device * hdev)
```

```json
{
  "name": "usb_hub_to_struct_hub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586851861,
      "name": "usb_hub_to_struct_hub",
      "external": true,
      "loc": "drivers/usb/core/hub.c:131",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable",
        "drivers/usb/core/hub.c:usb_hub_find_child",
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:usb_enable_lpm",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:recursively_mark_NOTATTACHED",
        "drivers/usb/core/hub.c:usb_device_is_owned",
        "drivers/usb/core/hub.c:usb_hub_release_all_ports",
        "drivers/usb/core/hub.c:find_port_owner",
        "drivers/usb/core/hub.c:hub_ioctl",
        "drivers/usb/core/hub.c:usb_remove_device",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:match_location",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume",
        "drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586830192,
      "name": "usb_hub_to_struct_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct usb_hub * usb_hub_to_struct_hub(struct usb_device * hdev)
```

```json
{
  "name": "usb_hub_to_struct_hub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586794069,
      "name": "usb_hub_to_struct_hub",
      "external": true,
      "loc": "drivers/usb/core/hub.c:131",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable",
        "drivers/usb/core/hub.c:usb_hub_find_child",
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:usb_enable_lpm",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:recursively_mark_NOTATTACHED",
        "drivers/usb/core/hub.c:usb_device_is_owned",
        "drivers/usb/core/hub.c:usb_hub_release_all_ports",
        "drivers/usb/core/hub.c:find_port_owner",
        "drivers/usb/core/hub.c:hub_ioctl",
        "drivers/usb/core/hub.c:usb_remove_device",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:match_location",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume",
        "drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586771952,
      "name": "usb_hub_to_struct_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct usb_hub * usb_hub_to_struct_hub(struct usb_device * hdev)
```

```json
{
  "name": "usb_hub_to_struct_hub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587100341,
      "name": "usb_hub_to_struct_hub",
      "external": true,
      "loc": "drivers/usb/core/hub.c:131",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable",
        "drivers/usb/core/hub.c:usb_hub_find_child",
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:usb_enable_lpm",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:recursively_mark_NOTATTACHED",
        "drivers/usb/core/hub.c:usb_device_is_owned",
        "drivers/usb/core/hub.c:usb_hub_release_all_ports",
        "drivers/usb/core/hub.c:find_port_owner",
        "drivers/usb/core/hub.c:hub_ioctl",
        "drivers/usb/core/hub.c:usb_remove_device",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:match_location",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume",
        "drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587078672,
      "name": "usb_hub_to_struct_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct usb_hub * usb_hub_to_struct_hub(struct usb_device * hdev)
```

```json
{
  "name": "usb_hub_to_struct_hub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587207589,
      "name": "usb_hub_to_struct_hub",
      "external": true,
      "loc": "drivers/usb/core/hub.c:131",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable",
        "drivers/usb/core/hub.c:usb_hub_find_child",
        "drivers/usb/core/hub.c:usb_reset_device",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:usb_enable_lpm",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:recursively_mark_NOTATTACHED",
        "drivers/usb/core/hub.c:usb_device_is_owned",
        "drivers/usb/core/hub.c:usb_hub_release_all_ports",
        "drivers/usb/core/hub.c:find_port_owner",
        "drivers/usb/core/hub.c:hub_ioctl",
        "drivers/usb/core/hub.c:usb_remove_device",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:match_location",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume",
        "drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587185824,
      "name": "usb_hub_to_struct_hub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
