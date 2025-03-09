# Function: <code>mp_find_ioapic_pin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int mp_find_ioapic_pin(int ioapic, u32 gsi)
```

```json
{
  "name": "mp_find_ioapic_pin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579202320,
      "name": "mp_find_ioapic_pin",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2676",
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
      "addr": 18446744071579202320,
      "name": "mp_find_ioapic_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int mp_find_ioapic_pin(int ioapic, u32 gsi)
```

```json
{
  "name": "mp_find_ioapic_pin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579202992,
      "name": "mp_find_ioapic_pin",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2673",
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
      "addr": 18446744071579202992,
      "name": "mp_find_ioapic_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int mp_find_ioapic_pin(int ioapic, u32 gsi)
```

```json
{
  "name": "mp_find_ioapic_pin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579214656,
      "name": "mp_find_ioapic_pin",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2674",
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
      "addr": 18446744071579214656,
      "name": "mp_find_ioapic_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int mp_find_ioapic_pin(int ioapic, u32 gsi)
```

```json
{
  "name": "mp_find_ioapic_pin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579212192,
      "name": "mp_find_ioapic_pin",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2672",
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
      "addr": 18446744071579212192,
      "name": "mp_find_ioapic_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int mp_find_ioapic_pin(int ioapic, u32 gsi)
```

```json
{
  "name": "mp_find_ioapic_pin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579229840,
      "name": "mp_find_ioapic_pin",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2682",
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
      "addr": 18446744071579229840,
      "name": "mp_find_ioapic_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int mp_find_ioapic_pin(int ioapic, u32 gsi)
```

```json
{
  "name": "mp_find_ioapic_pin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579242192,
      "name": "mp_find_ioapic_pin",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2675",
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
      "addr": 18446744071579242192,
      "name": "mp_find_ioapic_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int mp_find_ioapic_pin(int ioapic, u32 gsi)
```

```json
{
  "name": "mp_find_ioapic_pin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579265968,
      "name": "mp_find_ioapic_pin",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2676",
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
      "addr": 18446744071579265968,
      "name": "mp_find_ioapic_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int mp_find_ioapic_pin(int ioapic, u32 gsi)
```

```json
{
  "name": "mp_find_ioapic_pin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mp_find_ioapic_pin",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2739",
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
      "addr": 18446744071579284910,
      "name": "mp_find_ioapic_pin.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071579280240,
      "name": "mp_find_ioapic_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int mp_find_ioapic_pin(int ioapic, u32 gsi)
```

```json
{
  "name": "mp_find_ioapic_pin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579282704,
      "name": "mp_find_ioapic_pin",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2742",
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
      "addr": 18446744071579282704,
      "name": "mp_find_ioapic_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int mp_find_ioapic_pin(int ioapic, u32 gsi)
```

```json
{
  "name": "mp_find_ioapic_pin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579312416,
      "name": "mp_find_ioapic_pin",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2735",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579312416,
      "name": "mp_find_ioapic_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int mp_find_ioapic_pin(int ioapic, u32 gsi)
```

```json
{
  "name": "mp_find_ioapic_pin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579317728,
      "name": "mp_find_ioapic_pin",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2758",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq",
        "arch/x86/kernel/apic/io_apic.c:__acpi_get_override_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579317728,
      "name": "mp_find_ioapic_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int mp_find_ioapic_pin(int ioapic, u32 gsi)
```

```json
{
  "name": "mp_find_ioapic_pin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579320496,
      "name": "mp_find_ioapic_pin",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2760",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq",
        "arch/x86/kernel/apic/io_apic.c:__acpi_get_override_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579320496,
      "name": "mp_find_ioapic_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int mp_find_ioapic_pin(int ioapic, u32 gsi)
```

```json
{
  "name": "mp_find_ioapic_pin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579375049,
      "name": "mp_find_ioapic_pin",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2760",
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
      "addr": 18446744071579375872,
      "name": "mp_find_ioapic_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int mp_find_ioapic_pin(int ioapic, u32 gsi)
```

```json
{
  "name": "mp_find_ioapic_pin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579439270,
      "name": "mp_find_ioapic_pin",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2774",
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
      "addr": 18446744071579440176,
      "name": "mp_find_ioapic_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int mp_find_ioapic_pin(int ioapic, u32 gsi)
```

```json
{
  "name": "mp_find_ioapic_pin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579524257,
      "name": "mp_find_ioapic_pin",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2774",
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
      "addr": 18446744071579525264,
      "name": "mp_find_ioapic_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int mp_find_ioapic_pin(int ioapic, u32 gsi)
```

```json
{
  "name": "mp_find_ioapic_pin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579537060,
      "name": "mp_find_ioapic_pin",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2781",
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
      "addr": 18446744071579538064,
      "name": "mp_find_ioapic_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int mp_find_ioapic_pin(int ioapic, u32 gsi)
```

```json
{
  "name": "mp_find_ioapic_pin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579565876,
      "name": "mp_find_ioapic_pin",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2777",
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
      "addr": 18446744071579566880,
      "name": "mp_find_ioapic_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int mp_find_ioapic_pin(int ioapic, u32 gsi)
```

```json
{
  "name": "mp_find_ioapic_pin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579281408,
      "name": "mp_find_ioapic_pin",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2748",
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
      "addr": 18446744071579281408,
      "name": "mp_find_ioapic_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int mp_find_ioapic_pin(int ioapic, u32 gsi)
```

```json
{
  "name": "mp_find_ioapic_pin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579216736,
      "name": "mp_find_ioapic_pin",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2742",
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
      "addr": 18446744071579216736,
      "name": "mp_find_ioapic_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int mp_find_ioapic_pin(int ioapic, u32 gsi)
```

```json
{
  "name": "mp_find_ioapic_pin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579282608,
      "name": "mp_find_ioapic_pin",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2742",
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
      "addr": 18446744071579282608,
      "name": "mp_find_ioapic_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int mp_find_ioapic_pin(int ioapic, u32 gsi)
```

```json
{
  "name": "mp_find_ioapic_pin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579288496,
      "name": "mp_find_ioapic_pin",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:2742",
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
      "addr": 18446744071579288496,
      "name": "mp_find_ioapic_pin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int mp_find_ioapic_pin(int ioapic, u32 gsi)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int mp_find_ioapic_pin(int ioapic, u32 gsi)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int mp_find_ioapic_pin(int ioapic, u32 gsi)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int mp_find_ioapic_pin(int ioapic, u32 gsi)
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
