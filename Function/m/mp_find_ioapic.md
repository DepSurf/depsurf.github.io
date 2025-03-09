# Function: <code>mp_find_ioapic</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int mp_find_ioapic(u32 gsi)
```

```json
{
  "name": "mp_find_ioapic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579202224,
      "name": "mp_find_ioapic",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2658",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579202224,
      "name": "mp_find_ioapic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int mp_find_ioapic(u32 gsi)
```

```json
{
  "name": "mp_find_ioapic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579202896,
      "name": "mp_find_ioapic",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2655",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq",
        "arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579202896,
      "name": "mp_find_ioapic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int mp_find_ioapic(u32 gsi)
```

```json
{
  "name": "mp_find_ioapic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579214560,
      "name": "mp_find_ioapic",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2656",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq",
        "arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579214560,
      "name": "mp_find_ioapic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int mp_find_ioapic(u32 gsi)
```

```json
{
  "name": "mp_find_ioapic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579212096,
      "name": "mp_find_ioapic",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2654",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq",
        "arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579212096,
      "name": "mp_find_ioapic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int mp_find_ioapic(u32 gsi)
```

```json
{
  "name": "mp_find_ioapic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579229744,
      "name": "mp_find_ioapic",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2664",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579229744,
      "name": "mp_find_ioapic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int mp_find_ioapic(u32 gsi)
```

```json
{
  "name": "mp_find_ioapic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mp_find_ioapic",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2657",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579246854,
      "name": "mp_find_ioapic.cold.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071579242112,
      "name": "mp_find_ioapic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int mp_find_ioapic(u32 gsi)
```

```json
{
  "name": "mp_find_ioapic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mp_find_ioapic",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2658",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579270651,
      "name": "mp_find_ioapic.cold.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071579265888,
      "name": "mp_find_ioapic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int mp_find_ioapic(u32 gsi)
```

```json
{
  "name": "mp_find_ioapic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mp_find_ioapic",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2721",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579284887,
      "name": "mp_find_ioapic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579280160,
      "name": "mp_find_ioapic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int mp_find_ioapic(u32 gsi)
```

```json
{
  "name": "mp_find_ioapic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mp_find_ioapic",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2724",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579287335,
      "name": "mp_find_ioapic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579282624,
      "name": "mp_find_ioapic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mp_find_ioapic(u32 gsi)
```

```json
{
  "name": "mp_find_ioapic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579312515,
      "name": "mp_find_ioapic",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2717",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq"
      ],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579316805,
      "name": "mp_find_ioapic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579312336,
      "name": "mp_find_ioapic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mp_find_ioapic(u32 gsi)
```

```json
{
  "name": "mp_find_ioapic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579320037,
      "name": "mp_find_ioapic",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2740",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq",
        "arch/x86/kernel/apic/io_apic.c:__acpi_get_override_irq"
      ],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591261069,
      "name": "mp_find_ioapic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579317648,
      "name": "mp_find_ioapic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mp_find_ioapic(u32 gsi)
```

```json
{
  "name": "mp_find_ioapic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579322757,
      "name": "mp_find_ioapic",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2742",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq",
        "arch/x86/kernel/apic/io_apic.c:__acpi_get_override_irq"
      ],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591204160,
      "name": "mp_find_ioapic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579320416,
      "name": "mp_find_ioapic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mp_find_ioapic(u32 gsi)
```

```json
{
  "name": "mp_find_ioapic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579374949,
      "name": "mp_find_ioapic",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2742",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq",
        "arch/x86/kernel/apic/io_apic.c:__acpi_get_override_irq"
      ],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592075762,
      "name": "mp_find_ioapic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579375744,
      "name": "mp_find_ioapic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mp_find_ioapic(u32 gsi)
```

```json
{
  "name": "mp_find_ioapic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579439173,
      "name": "mp_find_ioapic",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2756",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq",
        "arch/x86/kernel/apic/io_apic.c:__acpi_get_override_irq"
      ],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593842321,
      "name": "mp_find_ioapic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579440032,
      "name": "mp_find_ioapic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int mp_find_ioapic(u32 gsi)
```

```json
{
  "name": "mp_find_ioapic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579524117,
      "name": "mp_find_ioapic",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2756",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq",
        "arch/x86/kernel/apic/io_apic.c:__acpi_get_override_irq"
      ],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579525104,
      "name": "mp_find_ioapic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int mp_find_ioapic(u32 gsi)
```

```json
{
  "name": "mp_find_ioapic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579536917,
      "name": "mp_find_ioapic",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2763",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq",
        "arch/x86/kernel/apic/io_apic.c:__acpi_get_override_irq"
      ],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579537904,
      "name": "mp_find_ioapic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int mp_find_ioapic(u32 gsi)
```

```json
{
  "name": "mp_find_ioapic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579565733,
      "name": "mp_find_ioapic",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2759",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq",
        "arch/x86/kernel/apic/io_apic.c:__acpi_get_override_irq"
      ],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579566720,
      "name": "mp_find_ioapic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int mp_find_ioapic(u32 gsi)
```

```json
{
  "name": "mp_find_ioapic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mp_find_ioapic",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2730",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579286039,
      "name": "mp_find_ioapic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579281328,
      "name": "mp_find_ioapic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int mp_find_ioapic(u32 gsi)
```

```json
{
  "name": "mp_find_ioapic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mp_find_ioapic",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2724",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579221319,
      "name": "mp_find_ioapic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579216656,
      "name": "mp_find_ioapic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int mp_find_ioapic(u32 gsi)
```

```json
{
  "name": "mp_find_ioapic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mp_find_ioapic",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2724",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579287239,
      "name": "mp_find_ioapic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579282528,
      "name": "mp_find_ioapic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int mp_find_ioapic(u32 gsi)
```

```json
{
  "name": "mp_find_ioapic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mp_find_ioapic",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2724",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579293127,
      "name": "mp_find_ioapic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579288416,
      "name": "mp_find_ioapic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int mp_find_ioapic(u32 gsi)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int mp_find_ioapic(u32 gsi)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int mp_find_ioapic(u32 gsi)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int mp_find_ioapic(u32 gsi)
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
