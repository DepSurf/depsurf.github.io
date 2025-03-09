# Function: <code>pcie_do_write_cmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void pcie_do_write_cmd(struct controller * ctrl, u16 cmd, u16 mask, bool wait)
```

```json
{
  "name": "pcie_do_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583368112,
      "name": "pcie_do_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:181",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_attention_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_on",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_off",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_blink",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_off_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_notification",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583368112,
      "name": "pcie_do_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
void pcie_do_write_cmd(struct controller * ctrl, u16 cmd, u16 mask, bool wait)
```

```json
{
  "name": "pcie_do_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583681408,
      "name": "pcie_do_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:181",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_notification",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_off_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_blink",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_off",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_on",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_attention_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583681408,
      "name": "pcie_do_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
void pcie_do_write_cmd(struct controller * ctrl, u16 cmd, u16 mask, bool wait)
```

```json
{
  "name": "pcie_do_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583819520,
      "name": "pcie_do_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:181",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_notification",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_off_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_blink",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_off",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_on",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_attention_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583819520,
      "name": "pcie_do_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
void pcie_do_write_cmd(struct controller * ctrl, u16 cmd, u16 mask, bool wait)
```

```json
{
  "name": "pcie_do_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583862496,
      "name": "pcie_do_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:181",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_notification",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_off_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_blink",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_off",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_on",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_attention_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583862496,
      "name": "pcie_do_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
void pcie_do_write_cmd(struct controller * ctrl, u16 cmd, u16 mask, bool wait)
```

```json
{
  "name": "pcie_do_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584126112,
      "name": "pcie_do_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:178",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_notification",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_off_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_blink",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_off",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_on",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_attention_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584126112,
      "name": "pcie_do_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
void pcie_do_write_cmd(struct controller * ctrl, u16 cmd, u16 mask, bool wait)
```

```json
{
  "name": "pcie_do_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584326544,
      "name": "pcie_do_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:160",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_notification",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_off_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_blink",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_off",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_on",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_attention_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584326544,
      "name": "pcie_do_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
void pcie_do_write_cmd(struct controller * ctrl, u16 cmd, u16 mask, bool wait)
```

```json
{
  "name": "pcie_do_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584421552,
      "name": "pcie_do_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:135",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_disable_interrupt",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_interrupt",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_blink",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_on",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584421552,
      "name": "pcie_do_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void pcie_do_write_cmd(struct controller * ctrl, u16 cmd, u16 mask, bool wait)
```

```json
{
  "name": "pcie_do_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_do_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:137",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_disable_interrupt",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_interrupt",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_blink",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_on",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584618032,
      "name": "pcie_do_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
    },
    {
      "addr": 18446744071584623948,
      "name": "pcie_do_write_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void pcie_do_write_cmd(struct controller * ctrl, u16 cmd, u16 mask, bool wait)
```

```json
{
  "name": "pcie_do_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_do_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:137",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_disable_interrupt",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_interrupt",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584756016,
      "name": "pcie_do_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
    },
    {
      "addr": 18446744071584761644,
      "name": "pcie_do_write_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void pcie_do_write_cmd(struct controller * ctrl, u16 cmd, u16 mask, bool wait)
```

```json
{
  "name": "pcie_do_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_do_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:154",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_disable_interrupt",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_interrupt",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585447104,
      "name": "pcie_do_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
    },
    {
      "addr": 18446744071585452943,
      "name": "pcie_do_write_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void pcie_do_write_cmd(struct controller * ctrl, u16 cmd, u16 mask, bool wait)
```

```json
{
  "name": "pcie_do_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_do_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:154",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_disable_interrupt",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_interrupt",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585595408,
      "name": "pcie_do_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
    },
    {
      "addr": 18446744071591412097,
      "name": "pcie_do_write_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void pcie_do_write_cmd(struct controller * ctrl, u16 cmd, u16 mask, bool wait)
```

```json
{
  "name": "pcie_do_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_do_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:154",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_disable_interrupt",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_interrupt",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585473808,
      "name": "pcie_do_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
    },
    {
      "addr": 18446744071591354361,
      "name": "pcie_do_write_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void pcie_do_write_cmd(struct controller * ctrl, u16 cmd, u16 mask, bool wait)
```

```json
{
  "name": "pcie_do_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_do_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:154",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_disable_interrupt",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_interrupt",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585940064,
      "name": "pcie_do_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
    },
    {
      "addr": 18446744071592381928,
      "name": "pcie_do_write_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void pcie_do_write_cmd(struct controller * ctrl, u16 cmd, u16 mask, bool wait)
```

```json
{
  "name": "pcie_do_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_do_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:156",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_disable_interrupt",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_interrupt",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587143328,
      "name": "pcie_do_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
    },
    {
      "addr": 18446744071594245778,
      "name": "pcie_do_write_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
void pcie_do_write_cmd(struct controller * ctrl, u16 cmd, u16 mask, bool wait)
```

```json
{
  "name": "pcie_do_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588347648,
      "name": "pcie_do_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:156",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_disable_interrupt",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_interrupt",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588347648,
      "name": "pcie_do_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
void pcie_do_write_cmd(struct controller * ctrl, u16 cmd, u16 mask, bool wait)
```

```json
{
  "name": "pcie_do_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588623904,
      "name": "pcie_do_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:156",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_disable_interrupt",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_interrupt",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588623904,
      "name": "pcie_do_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
void pcie_do_write_cmd(struct controller * ctrl, u16 cmd, u16 mask, bool wait)
```

```json
{
  "name": "pcie_do_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588924080,
      "name": "pcie_do_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:157",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_disable_interrupt",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_interrupt",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588924080,
      "name": "pcie_do_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
void pcie_do_write_cmd(struct controller * ctrl, u16 cmd, u16 mask, bool wait)
```

```json
{
  "name": "pcie_do_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497019512,
      "name": "pcie_do_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:137",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_disable_interrupt",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_interrupt",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497019512,
      "name": "pcie_do_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void pcie_do_write_cmd(struct controller * ctrl, u16 cmd, u16 mask, bool wait)
```

```json
{
  "name": "pcie_do_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275678618,
      "name": "pcie_do_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:137",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_disable_interrupt",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_interrupt",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275678618,
      "name": "pcie_do_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void pcie_do_write_cmd(struct controller * ctrl, u16 cmd, u16 mask, bool wait)
```

```json
{
  "name": "pcie_do_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_do_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:137",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_disable_interrupt",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_interrupt",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584704832,
      "name": "pcie_do_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
    },
    {
      "addr": 18446744071584710460,
      "name": "pcie_do_write_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void pcie_do_write_cmd(struct controller * ctrl, u16 cmd, u16 mask, bool wait)
```

```json
{
  "name": "pcie_do_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_do_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:137",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_disable_interrupt",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_interrupt",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584635600,
      "name": "pcie_do_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
    },
    {
      "addr": 18446744071584641228,
      "name": "pcie_do_write_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void pcie_do_write_cmd(struct controller * ctrl, u16 cmd, u16 mask, bool wait)
```

```json
{
  "name": "pcie_do_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_do_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:137",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_disable_interrupt",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_interrupt",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584706176,
      "name": "pcie_do_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
    },
    {
      "addr": 18446744071584711804,
      "name": "pcie_do_write_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void pcie_do_write_cmd(struct controller * ctrl, u16 cmd, u16 mask, bool wait)
```

```json
{
  "name": "pcie_do_write_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_do_write_cmd",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:137",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_disable_interrupt",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_interrupt",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584813760,
      "name": "pcie_do_write_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
    },
    {
      "addr": 18446744071584819392,
      "name": "pcie_do_write_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void pcie_do_write_cmd(struct controller * ctrl, u16 cmd, u16 mask, bool wait)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void pcie_do_write_cmd(struct controller * ctrl, u16 cmd, u16 mask, bool wait)
```
</details>
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
