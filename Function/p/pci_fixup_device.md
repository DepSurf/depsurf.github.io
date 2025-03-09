# Function: <code>pci_fixup_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev * dev)
```

```json
{
  "name": "pci_fixup_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583322336,
      "name": "pci_fixup_device",
      "external": true,
      "loc": "drivers/pci/quirks.c:3296",
      "file": "drivers/pci/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:pci_apply_final_quirks"
      ],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_legacy_suspend_late",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pci/pci-driver.c:pci_legacy_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583322336,
      "name": "pci_fixup_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev * dev)
```

```json
{
  "name": "pci_fixup_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595405093,
      "name": "pci_fixup_device",
      "external": true,
      "loc": "drivers/pci/quirks.c:3426",
      "file": "drivers/pci/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:pci_apply_final_quirks"
      ],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_legacy_resume",
        "drivers/pci/pci-driver.c:pci_legacy_suspend_late",
        "drivers/pci/pci-driver.c:pci_legacy_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583633392,
      "name": "pci_fixup_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev * dev)
```

```json
{
  "name": "pci_fixup_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595655051,
      "name": "pci_fixup_device",
      "external": true,
      "loc": "drivers/pci/quirks.c:3545",
      "file": "drivers/pci/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:pci_apply_final_quirks"
      ],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_legacy_resume",
        "drivers/pci/pci-driver.c:pci_legacy_suspend_late",
        "drivers/pci/pci-driver.c:pci_legacy_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583770720,
      "name": "pci_fixup_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev * dev)
```

```json
{
  "name": "pci_fixup_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596576854,
      "name": "pci_fixup_device",
      "external": true,
      "loc": "drivers/pci/quirks.c:3591",
      "file": "drivers/pci/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:pci_apply_final_quirks"
      ],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_legacy_resume",
        "drivers/pci/pci-driver.c:pci_legacy_suspend_late",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pci/pci-driver.c:pci_pm_default_resume_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583812432,
      "name": "pci_fixup_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev * dev)
```

```json
{
  "name": "pci_fixup_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602904718,
      "name": "pci_fixup_device",
      "external": true,
      "loc": "drivers/pci/quirks.c:3606",
      "file": "drivers/pci/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:pci_apply_final_quirks"
      ],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_legacy_resume",
        "drivers/pci/pci-driver.c:pci_legacy_suspend_late",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pci/pci-driver.c:pci_pm_default_resume_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584075536,
      "name": "pci_fixup_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev * dev)
```

```json
{
  "name": "pci_fixup_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071603076645,
      "name": "pci_fixup_device",
      "external": true,
      "loc": "drivers/pci/quirks.c:92",
      "file": "drivers/pci/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:pci_apply_final_quirks"
      ],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_legacy_resume",
        "drivers/pci/pci-driver.c:pci_legacy_suspend_late",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pci/pci-driver.c:pci_pm_default_resume_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584267696,
      "name": "pci_fixup_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev * dev)
```

```json
{
  "name": "pci_fixup_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604878856,
      "name": "pci_fixup_device",
      "external": true,
      "loc": "drivers/pci/quirks.c:100",
      "file": "drivers/pci/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:pci_apply_final_quirks"
      ],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_legacy_resume",
        "drivers/pci/pci-driver.c:pci_legacy_suspend_late",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pci/pci-driver.c:pci_pm_default_resume_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584361520,
      "name": "pci_fixup_device",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev * dev)
```

```json
{
  "name": "pci_fixup_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604985438,
      "name": "pci_fixup_device",
      "external": true,
      "loc": "drivers/pci/quirks.c:100",
      "file": "drivers/pci/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:pci_apply_final_quirks"
      ],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_legacy_resume",
        "drivers/pci/pci-driver.c:pci_legacy_suspend_late",
        "drivers/pci/pci-driver.c:pci_legacy_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584555904,
      "name": "pci_fixup_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev * dev)
```

```json
{
  "name": "pci_fixup_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605022623,
      "name": "pci_fixup_device",
      "external": true,
      "loc": "drivers/pci/quirks.c:99",
      "file": "drivers/pci/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:pci_apply_final_quirks"
      ],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_legacy_resume",
        "drivers/pci/pci-driver.c:pci_legacy_suspend_late",
        "drivers/pci/pci-driver.c:pci_legacy_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584692688,
      "name": "pci_fixup_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev * dev)
```

```json
{
  "name": "pci_fixup_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585406816,
      "name": "pci_fixup_device",
      "external": true,
      "loc": "drivers/pci/quirks.c:99",
      "file": "drivers/pci/quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_legacy_resume",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pci/quirks.c:pci_apply_final_quirks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585406816,
      "name": "pci_fixup_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev * dev)
```

```json
{
  "name": "pci_fixup_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585563584,
      "name": "pci_fixup_device",
      "external": true,
      "loc": "drivers/pci/quirks.c:99",
      "file": "drivers/pci/quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_legacy_resume",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pci/quirks.c:pci_apply_final_quirks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585563584,
      "name": "pci_fixup_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev * dev)
```

```json
{
  "name": "pci_fixup_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_fixup_device",
      "external": true,
      "loc": "drivers/pci/quirks.c:100",
      "file": "drivers/pci/quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_legacy_resume",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pci/quirks.c:pci_apply_final_quirks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591346552,
      "name": "pci_fixup_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071585441712,
      "name": "pci_fixup_device",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev * dev)
```

```json
{
  "name": "pci_fixup_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_fixup_device",
      "external": true,
      "loc": "drivers/pci/quirks.c:100",
      "file": "drivers/pci/quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_legacy_resume",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pci/quirks.c:pci_apply_final_quirks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592375723,
      "name": "pci_fixup_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071585915536,
      "name": "pci_fixup_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 489
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
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev * dev)
```

```json
{
  "name": "pci_fixup_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_fixup_device",
      "external": true,
      "loc": "drivers/pci/quirks.c:101",
      "file": "drivers/pci/quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/pci.c:do_pci_enable_device",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_legacy_resume",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pci/quirks.c:pci_apply_final_quirks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594239715,
      "name": "pci_fixup_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    },
    {
      "addr": 18446744071587119520,
      "name": "pci_fixup_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 477
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
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev * dev)
```

```json
{
  "name": "pci_fixup_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_fixup_device",
      "external": true,
      "loc": "drivers/pci/quirks.c:101",
      "file": "drivers/pci/quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/pci.c:do_pci_enable_device",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_legacy_resume",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pci/quirks.c:pci_apply_final_quirks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596209909,
      "name": "pci_fixup_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071588317104,
      "name": "pci_fixup_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 541
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
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev * dev)
```

```json
{
  "name": "pci_fixup_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_fixup_device",
      "external": true,
      "loc": "drivers/pci/quirks.c:194",
      "file": "drivers/pci/quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/pci.c:do_pci_enable_device",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_legacy_resume",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pci/quirks.c:pci_apply_final_quirks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596735062,
      "name": "pci_fixup_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071588593152,
      "name": "pci_fixup_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev * dev)
```

```json
{
  "name": "pci_fixup_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_fixup_device",
      "external": true,
      "loc": "drivers/pci/quirks.c:194",
      "file": "drivers/pci/quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/pci.c:do_pci_enable_device",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_legacy_resume",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pci/quirks.c:pci_apply_final_quirks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597643646,
      "name": "pci_fixup_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071588892880,
      "name": "pci_fixup_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev * dev)
```

```json
{
  "name": "pci_fixup_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336511098552,
      "name": "pci_fixup_device",
      "external": true,
      "loc": "drivers/pci/quirks.c:99",
      "file": "drivers/pci/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:pci_apply_final_quirks"
      ],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496949784,
      "name": "pci_fixup_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev * dev)
```

```json
{
  "name": "pci_fixup_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3243579552,
      "name": "pci_fixup_device",
      "external": true,
      "loc": "drivers/pci/quirks.c:99",
      "file": "drivers/pci/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:pci_apply_final_quirks"
      ],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_legacy_resume",
        "drivers/pci/pci-driver.c:pci_legacy_suspend_late",
        "drivers/pci/pci-driver.c:pci_legacy_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230215880,
      "name": "pci_fixup_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev * dev)
```

```json
{
  "name": "pci_fixup_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055302751868,
      "name": "pci_fixup_device",
      "external": true,
      "loc": "drivers/pci/quirks.c:99",
      "file": "drivers/pci/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:pci_apply_final_quirks"
      ],
      "caller_func": [
        "arch/powerpc/kernel/pci_of_scan.c:of_create_pci_dev",
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291045040,
      "name": "pci_fixup_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev * dev)
```

```json
{
  "name": "pci_fixup_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936270777910,
      "name": "pci_fixup_device",
      "external": true,
      "loc": "drivers/pci/quirks.c:99",
      "file": "drivers/pci/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:pci_apply_final_quirks"
      ],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275622634,
      "name": "pci_fixup_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev * dev)
```

```json
{
  "name": "pci_fixup_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604927826,
      "name": "pci_fixup_device",
      "external": true,
      "loc": "drivers/pci/quirks.c:99",
      "file": "drivers/pci/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:pci_apply_final_quirks"
      ],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_legacy_resume",
        "drivers/pci/pci-driver.c:pci_legacy_suspend_late",
        "drivers/pci/pci-driver.c:pci_legacy_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584643168,
      "name": "pci_fixup_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev * dev)
```

```json
{
  "name": "pci_fixup_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604896802,
      "name": "pci_fixup_device",
      "external": true,
      "loc": "drivers/pci/quirks.c:99",
      "file": "drivers/pci/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:pci_apply_final_quirks"
      ],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_legacy_resume",
        "drivers/pci/pci-driver.c:pci_legacy_suspend_late",
        "drivers/pci/pci-driver.c:pci_legacy_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584572944,
      "name": "pci_fixup_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev * dev)
```

```json
{
  "name": "pci_fixup_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605005273,
      "name": "pci_fixup_device",
      "external": true,
      "loc": "drivers/pci/quirks.c:99",
      "file": "drivers/pci/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:pci_apply_final_quirks"
      ],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_legacy_resume",
        "drivers/pci/pci-driver.c:pci_legacy_suspend_late",
        "drivers/pci/pci-driver.c:pci_legacy_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584642848,
      "name": "pci_fixup_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
void pci_fixup_device(enum pci_fixup_pass pass, struct pci_dev * dev)
```

```json
{
  "name": "pci_fixup_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605026803,
      "name": "pci_fixup_device",
      "external": true,
      "loc": "drivers/pci/quirks.c:99",
      "file": "drivers/pci/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:pci_apply_final_quirks"
      ],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_add_device",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_legacy_resume",
        "drivers/pci/pci-driver.c:pci_legacy_suspend_late",
        "drivers/pci/pci-driver.c:pci_legacy_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584750544,
      "name": "pci_fixup_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
