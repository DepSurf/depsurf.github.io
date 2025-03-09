# Function: <code>cpuidle_enable_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int cpuidle_enable_device(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585903696,
      "name": "cpuidle_enable_device",
      "external": true,
      "loc": "drivers/cpuidle/cpuidle.c:359",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device"
      ],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug",
        "drivers/acpi/processor_idle.c:acpi_processor_cst_has_changed",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585903696,
      "name": "cpuidle_enable_device.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071585903840,
      "name": "cpuidle_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int cpuidle_enable_device(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586303623,
      "name": "cpuidle_enable_device",
      "external": true,
      "loc": "drivers/cpuidle/cpuidle.c:359",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device"
      ],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586303184,
      "name": "cpuidle_enable_device.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071586303344,
      "name": "cpuidle_enable_device",
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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int cpuidle_enable_device(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586511415,
      "name": "cpuidle_enable_device",
      "external": true,
      "loc": "drivers/cpuidle/cpuidle.c:376",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device"
      ],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586510976,
      "name": "cpuidle_enable_device.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071586511136,
      "name": "cpuidle_enable_device",
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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int cpuidle_enable_device(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586637016,
      "name": "cpuidle_enable_device",
      "external": true,
      "loc": "drivers/cpuidle/cpuidle.c:379",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device"
      ],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586636560,
      "name": "cpuidle_enable_device.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    },
    {
      "addr": 18446744071586636736,
      "name": "cpuidle_enable_device",
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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int cpuidle_enable_device(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587118112,
      "name": "cpuidle_enable_device",
      "external": true,
      "loc": "drivers/cpuidle/cpuidle.c:380",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587118112,
      "name": "cpuidle_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int cpuidle_enable_device(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587417632,
      "name": "cpuidle_enable_device",
      "external": true,
      "loc": "drivers/cpuidle/cpuidle.c:395",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587417632,
      "name": "cpuidle_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int cpuidle_enable_device(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587597824,
      "name": "cpuidle_enable_device",
      "external": true,
      "loc": "drivers/cpuidle/cpuidle.c:424",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587597824,
      "name": "cpuidle_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int cpuidle_enable_device(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587874624,
      "name": "cpuidle_enable_device",
      "external": true,
      "loc": "drivers/cpuidle/cpuidle.c:438",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587874624,
      "name": "cpuidle_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int cpuidle_enable_device(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588080224,
      "name": "cpuidle_enable_device",
      "external": true,
      "loc": "drivers/cpuidle/cpuidle.c:469",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588080224,
      "name": "cpuidle_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int cpuidle_enable_device(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588941728,
      "name": "cpuidle_enable_device",
      "external": true,
      "loc": "drivers/cpuidle/cpuidle.c:472",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588941728,
      "name": "cpuidle_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int cpuidle_enable_device(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588954096,
      "name": "cpuidle_enable_device",
      "external": true,
      "loc": "drivers/cpuidle/cpuidle.c:497",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588954096,
      "name": "cpuidle_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int cpuidle_enable_device(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588842352,
      "name": "cpuidle_enable_device",
      "external": true,
      "loc": "drivers/cpuidle/cpuidle.c:497",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588842352,
      "name": "cpuidle_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int cpuidle_enable_device(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589538832,
      "name": "cpuidle_enable_device",
      "external": true,
      "loc": "drivers/cpuidle/cpuidle.c:497",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589538832,
      "name": "cpuidle_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int cpuidle_enable_device(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591031696,
      "name": "cpuidle_enable_device",
      "external": true,
      "loc": "drivers/cpuidle/cpuidle.c:497",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device",
        "drivers/cpuidle/governor.c:cpuidle_switch_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591031696,
      "name": "cpuidle_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int cpuidle_enable_device(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592742288,
      "name": "cpuidle_enable_device",
      "external": true,
      "loc": "drivers/cpuidle/cpuidle.c:502",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device",
        "drivers/cpuidle/governor.c:cpuidle_switch_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592742288,
      "name": "cpuidle_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int cpuidle_enable_device(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593178976,
      "name": "cpuidle_enable_device",
      "external": true,
      "loc": "drivers/cpuidle/cpuidle.c:534",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device",
        "drivers/cpuidle/governor.c:cpuidle_switch_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593178976,
      "name": "cpuidle_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int cpuidle_enable_device(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593932800,
      "name": "cpuidle_enable_device",
      "external": true,
      "loc": "drivers/cpuidle/cpuidle.c:534",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device",
        "drivers/cpuidle/governor.c:cpuidle_switch_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593932800,
      "name": "cpuidle_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int cpuidle_enable_device(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501323496,
      "name": "cpuidle_enable_device",
      "external": true,
      "loc": "drivers/cpuidle/cpuidle.c:469",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501323496,
      "name": "cpuidle_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int cpuidle_enable_device(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233813616,
      "name": "cpuidle_enable_device",
      "external": true,
      "loc": "drivers/cpuidle/cpuidle.c:469",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233813616,
      "name": "cpuidle_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int cpuidle_enable_device(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294866896,
      "name": "cpuidle_enable_device",
      "external": true,
      "loc": "drivers/cpuidle/cpuidle.c:469",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device",
        "drivers/cpuidle/cpuidle-pseries.c:pseries_cpuidle_cpu_online",
        "drivers/cpuidle/cpuidle-powernv.c:powernv_cpuidle_cpu_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294866896,
      "name": "cpuidle_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
    }
  ]
}
```
</details>
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
int cpuidle_enable_device(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587702368,
      "name": "cpuidle_enable_device",
      "external": true,
      "loc": "drivers/cpuidle/cpuidle.c:469",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587702368,
      "name": "cpuidle_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int cpuidle_enable_device(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587480320,
      "name": "cpuidle_enable_device",
      "external": true,
      "loc": "drivers/cpuidle/cpuidle.c:469",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587480320,
      "name": "cpuidle_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int cpuidle_enable_device(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588036368,
      "name": "cpuidle_enable_device",
      "external": true,
      "loc": "drivers/cpuidle/cpuidle.c:469",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588036368,
      "name": "cpuidle_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int cpuidle_enable_device(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588151936,
      "name": "cpuidle_enable_device",
      "external": true,
      "loc": "drivers/cpuidle/cpuidle.c:469",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588151936,
      "name": "cpuidle_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int cpuidle_enable_device(struct cpuidle_device * dev)
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
