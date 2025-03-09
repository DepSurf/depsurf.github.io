# Function: <code>acpi_add_pm_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device * adev, struct device * dev, void (*)(struct work_struct *) work_func)
```

```json
{
  "name": "acpi_add_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583553654,
      "name": "acpi_add_pm_notifier",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:421",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583553654,
      "name": "acpi_add_pm_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
acpi_status acpi_add_pm_notifier(struct acpi_device * adev, struct device * dev, void (*)(struct work_struct *) work_func)
```

```json
{
  "name": "acpi_add_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583875099,
      "name": "acpi_add_pm_notifier",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:423",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583875099,
      "name": "acpi_add_pm_notifier",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device * adev, struct device * dev, void (*)(struct work_struct *) work_func)
```

```json
{
  "name": "acpi_add_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584014153,
      "name": "acpi_add_pm_notifier",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:423",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584014153,
      "name": "acpi_add_pm_notifier",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device * adev, struct device * dev, void (*)(struct acpi_device_wakeup_context *) func)
```

```json
{
  "name": "acpi_add_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584065767,
      "name": "acpi_add_pm_notifier",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:432",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach"
      ],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584065488,
      "name": "acpi_add_pm_notifier.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071584067120,
      "name": "acpi_add_pm_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device * adev, struct device * dev, void (*)(struct acpi_device_wakeup_context *) func)
```

```json
{
  "name": "acpi_add_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584335160,
      "name": "acpi_add_pm_notifier",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:439",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach"
      ],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584334880,
      "name": "acpi_add_pm_notifier.part.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    },
    {
      "addr": 18446744071584336512,
      "name": "acpi_add_pm_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device * adev, struct device * dev, void (*)(struct acpi_device_wakeup_context *) func)
```

```json
{
  "name": "acpi_add_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584556001,
      "name": "acpi_add_pm_notifier",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:439",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach"
      ],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584555744,
      "name": "acpi_add_pm_notifier.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    },
    {
      "addr": 18446744071584557360,
      "name": "acpi_add_pm_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device * adev, struct device * dev, void (*)(struct acpi_device_wakeup_context *) func)
```

```json
{
  "name": "acpi_add_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584653761,
      "name": "acpi_add_pm_notifier",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:440",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach"
      ],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584653504,
      "name": "acpi_add_pm_notifier.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    },
    {
      "addr": 18446744071584654656,
      "name": "acpi_add_pm_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device * adev, struct device * dev, void (*)(struct acpi_device_wakeup_context *) func)
```

```json
{
  "name": "acpi_add_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584853153,
      "name": "acpi_add_pm_notifier",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:481",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach"
      ],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584852896,
      "name": "acpi_add_pm_notifier.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    },
    {
      "addr": 18446744071584854560,
      "name": "acpi_add_pm_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device * adev, struct device * dev, void (*)(struct acpi_device_wakeup_context *) func)
```

```json
{
  "name": "acpi_add_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584989039,
      "name": "acpi_add_pm_notifier",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:485",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach"
      ],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584988736,
      "name": "acpi_add_pm_notifier.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    },
    {
      "addr": 18446744071584990448,
      "name": "acpi_add_pm_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
acpi_status acpi_add_pm_notifier(struct acpi_device * adev, struct device * dev, void (*)(struct acpi_device_wakeup_context *) func)
```

```json
{
  "name": "acpi_add_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585687984,
      "name": "acpi_add_pm_notifier",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:485",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585687984,
      "name": "acpi_add_pm_notifier",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device * adev, struct device * dev, void (*)(struct acpi_device_wakeup_context *) func)
```

```json
{
  "name": "acpi_add_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585810272,
      "name": "acpi_add_pm_notifier",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:485",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585810272,
      "name": "acpi_add_pm_notifier",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device * adev, struct device * dev, void (*)(struct acpi_device_wakeup_context *) func)
```

```json
{
  "name": "acpi_add_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585690848,
      "name": "acpi_add_pm_notifier",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:482",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585690848,
      "name": "acpi_add_pm_notifier",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device * adev, struct device * dev, void (*)(struct acpi_device_wakeup_context *) func)
```

```json
{
  "name": "acpi_add_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586171232,
      "name": "acpi_add_pm_notifier",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:482",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586171232,
      "name": "acpi_add_pm_notifier",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device * adev, struct device * dev, void (*)(struct acpi_device_wakeup_context *) func)
```

```json
{
  "name": "acpi_add_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587405936,
      "name": "acpi_add_pm_notifier",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:510",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587405936,
      "name": "acpi_add_pm_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
acpi_status acpi_add_pm_notifier(struct acpi_device * adev, struct device * dev, void (*)(struct acpi_device_wakeup_context *) func)
```

```json
{
  "name": "acpi_add_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588660576,
      "name": "acpi_add_pm_notifier",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:557",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588660576,
      "name": "acpi_add_pm_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
acpi_status acpi_add_pm_notifier(struct acpi_device * adev, struct device * dev, void (*)(struct acpi_device_wakeup_context *) func)
```

```json
{
  "name": "acpi_add_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588948560,
      "name": "acpi_add_pm_notifier",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:557",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588948560,
      "name": "acpi_add_pm_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
acpi_status acpi_add_pm_notifier(struct acpi_device * adev, struct device * dev, void (*)(struct acpi_device_wakeup_context *) func)
```

```json
{
  "name": "acpi_add_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589245184,
      "name": "acpi_add_pm_notifier",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:570",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589245184,
      "name": "acpi_add_pm_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device * adev, struct device * dev, void (*)(struct acpi_device_wakeup_context *) func)
```

```json
{
  "name": "acpi_add_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497397388,
      "name": "acpi_add_pm_notifier",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:485",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach"
      ],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497397032,
      "name": "acpi_add_pm_notifier.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446603336497400720,
      "name": "acpi_add_pm_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device * adev, struct device * dev, void (*)(struct acpi_device_wakeup_context *) func)
```

```json
{
  "name": "acpi_add_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584933439,
      "name": "acpi_add_pm_notifier",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:485",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach"
      ],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584933136,
      "name": "acpi_add_pm_notifier.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    },
    {
      "addr": 18446744071584934720,
      "name": "acpi_add_pm_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device * adev, struct device * dev, void (*)(struct acpi_device_wakeup_context *) func)
```

```json
{
  "name": "acpi_add_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584842239,
      "name": "acpi_add_pm_notifier",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:485",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach"
      ],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584841936,
      "name": "acpi_add_pm_notifier.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    },
    {
      "addr": 18446744071584843520,
      "name": "acpi_add_pm_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device * adev, struct device * dev, void (*)(struct acpi_device_wakeup_context *) func)
```

```json
{
  "name": "acpi_add_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584940623,
      "name": "acpi_add_pm_notifier",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:485",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach"
      ],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584940320,
      "name": "acpi_add_pm_notifier.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    },
    {
      "addr": 18446744071584942032,
      "name": "acpi_add_pm_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device * adev, struct device * dev, void (*)(struct acpi_device_wakeup_context *) func)
```

```json
{
  "name": "acpi_add_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585046799,
      "name": "acpi_add_pm_notifier",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:485",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach"
      ],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:pci_acpi_add_bus_pm_notifier",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585046496,
      "name": "acpi_add_pm_notifier.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    },
    {
      "addr": 18446744071585048208,
      "name": "acpi_add_pm_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>void (*)(struct acpi_device_wakeup_context *) func</code>
</li>
<li>
<b>Param removed. </b>
<code>void (*)(struct work_struct *) work_func</code>
</li>
</ul>
</details>
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
acpi_status acpi_add_pm_notifier(struct acpi_device * adev, struct device * dev, void (*)(struct acpi_device_wakeup_context *) func)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device * adev, struct device * dev, void (*)(struct acpi_device_wakeup_context *) func)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_add_pm_notifier(struct acpi_device * adev, struct device * dev, void (*)(struct acpi_device_wakeup_context *) func)
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
